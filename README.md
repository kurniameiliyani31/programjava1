# programjava1
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        // Deklarasi variabel
        int angka = 5;
        
        // Loop menggunakan for
        for (int i = 1; i <= angka; i++) {
            // Penggunaan if
            if (i % 2 == 0) {
                System.out.println(i + " adalah angka genap");
            } else {
                System.out.println(i + " adalah angka ganjil");
            }
        }
        
        // Loop menggunakan while
        int j = 1;
        while (j <= angka) {
            System.out.println("Loop while ke-" + j);
            j++;
        }
        
        // Loop menggunakan do-while
        int k = 1;
        do {
            System.out.println("Loop do-while ke-" + k);
            k++;
        } while (k <= angka);
        
        // Array satu dimensi
        int[] arrSatuDimensi = {1, 2, 3, 4, 5};
        
        // Array multidimensi
        int[][] arrMultiDimensi = {{1, 2, 3}, {4, 5, 6}};
        
        // Input
        Scanner input = new Scanner(System.in);
        System.out.print("Masukkan sebuah angka: ");
        int inputAngka = input.nextInt();
        
        // Output
        System.out.println("Anda memasukkan angka: " + inputAngka);
        
        // Komentar
        // Ini adalah komentar satu baris
        
        /*
        Ini adalah
        komentar
        beberapa baris
        */
    }
}
