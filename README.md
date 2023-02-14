# Ucgenin-Alanini-Bulan-Program
Java Ucgenin Alanini Bulan Program

www.patika.dev

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {

        int a,b,c;
        double u,alan;

        Scanner input = new Scanner(System.in);
        System.out.print("1. Kenar Uzunluğunu Giriniz : ");
        a = input.nextInt();
        System.out.print("2. Kenar Uzunluğunu Giriniz : ");
        b = input.nextInt();
        System.out.print("3. Kenar Uzunluğunu Giriniz : ");
        c = input.nextInt();

        u = (a+b+c)/2.0;
        alan = Math.sqrt(u*(u-a)*(u-b)*(u-c));
        System.out.println("Üçgenin Alanı : " + alan);
    }
}
