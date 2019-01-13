# menentukan-program-letak-kuadran


    #include<stdio.h>
    #include<conio.h>

    int main()
    {
    int x,y;
    printf("MENGETAHUI KUADRAN DARI INPUTAN KOORDINAT X DAN Y.\n");
    printf("Masukan nilai x : ");
    scanf("%i",&x);
    printf("Masukan nilai y : ");
    scanf("%i",&y);
    if(x>0&&y>0)
        printf("KUADRAN I");
    if(x>0&&y<0)
        printf("KUADRAN II");
    if(x<0&&y<0)
        printf("KUADRAN III");
    if(x<0&&y>0)
        printf("KUADRAN IV");
    if(x==0&&y==0)
        printf("TITIK PUSAT");

    getch();
    }
