# Basit-Hesap-Makinesi-Yapimi-swich-case-ile.
import java.util.Scanner;

public class class4 {
    public static void main(String[] args) {
        int N1, N2, select;


        Scanner input = new Scanner(System.in);
        System.out.print("ilk sayiniz girin");
        N1 = input.nextInt();
        System.out.print("ikinci sayiniz girin");
        N2 = input.nextInt();
        System.out.println("1-toplam\n2- cikartma\n3-carbma\n4-bolme");
        System.out.println("seciniz");
        select = input.nextInt();
        switch (select=1) {
            case 1:
                System.out.println("toplam : " + (N1 + N2));
                break;
            case 2:
                System.out.println("cikartma : " + (N1 - N2));
                break;
            case 3:
                System.out.println("carbma : " + (N1 * N2));
                break;
            case 4:
                System.out.println("bolme : " + (N1 * N2));
            default:
                System.out.println("yanlış işlem");


        }

    }
}
