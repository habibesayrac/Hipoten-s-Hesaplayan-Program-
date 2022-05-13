# Hipotenus-Hesaplayan-Program-

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

   int a,b;
   double c,cevre,alan;
   Scanner input = new Scanner(System.in);
        System.out.println("Birinci kenarı Giriniz: ");
        a = input.nextInt();
        System.out.println("İkinci kenarı Giriniz: ");
        b = input.nextInt();
        c=Math.sqrt(Math.pow(a,2)+Math.pow(b,2));
        System.out.println("Hipotenüs Kenar Uzunluğu: " + c);
        cevre = a+b+c;
        System.out.println("Üçgenin Çevresi: " + cevre);
        alan = a*b/2;
        System.out.println("Üçgenin Alanı : " + alan);
    }
}
