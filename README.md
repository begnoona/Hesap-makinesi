import java.util.Scanner;


public class Main3 {



    public static void main(String[] args) {

    
        //switch case  ile hesap makinesi yapalım

        
        int sayi1,sayi2,secim;
        Scanner input= new Scanner(System.in);
        

        System.out.print("Lütfen birinci sayıyı seçiniz: ");
        sayi1= input.nextInt();
        

        System.out.print("Lütfen ikinci sayıyı seçiniz: ");
        sayi2= input.nextInt();
        

        System.out.print("lütfen bir seçim yapınız:\n");
        System.out.print("1-Toplama\n2-Çıkarma\n3-Çarpma\n4-Bölme\n5-Çıkış\n");
        secim= input.nextInt();
        

        switch (secim)
        {
            case 1:
                System.out.print("Toplama seçeneğini seçtiniz,sonuc: "+(sayi1+sayi2));
                break;
            case 2:
                System.out.print("Çıkarma seçeneğini seçtiniz,sonuc: "+(sayi1-sayi2));
                break;
            case 3:
                System.out.print("Çarpma seçeneğini seçtiniz,sonuc: "+(sayi1*sayi2));
                break;
            case 4:
                System.out.print("Bölme seçeneğini seçtiniz,sonuc: "+(sayi1/sayi2));
                break;
            case 5:
                System.out.print("Çıkış Yapılıyor");
                break;
            default:
                System.out.print("Yanlış tercih yaptınız tekrar deneyiniz.");
        }




    }
