# Array

1. Array yang diberi nama nomor didefinisikan untuk menyimpan bilangan bulat dengan nilai 1, 3, 5, 7, dan 11.
Setelah array nomor dideklarasikan, dilakukan pencetakan ke layar dengan menggunakan perulangan for. Pencetakan dilakukan dengan menampilkan setiap elemen dalam array nomor satu per satu. Proses ini dilakukan dengan bantuan variabel i yang berperan sebagai indeks untuk mengakses setiap elemen array. Seluruh nilai dalam array nomor dicetak dengan format "- [nilai]" diikuti dengan nilai yang disimpan di setiap indeks.

        // Array dengan tipe data integer
                int[] nomor = {1, 3, 5, 7, 11};
        
                System.out.println("1) Array NOMOR:");
                for (int i = 0; i < nomor.length; i++) {
                    System.out.println("- " + nomor[i]);
                }

2. Code yang diberikan merupakan contoh penggunaan array dengan tipe data String di dalam bahasa pemrograman Java. Dalam contoh tersebut, terdapat deklarasi dan inisialisasi array 'nama' yang berisi beberapa string, seperti "Upin", "Ipin", "Susanti", "Fizi", dan "Ehsan". Program kemudian mencetak isi dari array tersebut dengan menggunakan loop 'for'. Setelah menampilkan judul "Array NAMA" ke konsol, loop 'for' digunakan untuk mengakses setiap elemen dalam array 'nama', dan setiap elemen tersebut dicetak ke layar dengan format yang telah ditentukan.

       // Array dengan tipe data String
            String[] nama = {"Upin", "Ipin", "Susanti", "Fizi", "Ehsan"};
    
            System.out.println("\n2) Array NAMA:");
            for (int i = 0; i < nama.length; i++) {
                System.out.println("- " + nama[i]);
            }

3. Code yang diberikan merupakan contoh penggunaan array dalam bahasa pemrograman Java dengan tipe data double. Array nilai dideklarasikan untuk menyimpan sekumpulan nilai numerik bertipe double, yaitu 1.2, 3.4, 5.6, 7.8, dan 9.9.
Setelah deklarasi array, code tersebut menggunakan loop for untuk mengakses setiap elemen dalam array nilai. Dalam loop tersebut, setiap nilai dari array nilai dicetak ke konsol dengan format tertentu, yaitu dengan menambahkan tanda - di depan setiap nilai.

       // Array dengan tipe data double
              double[] nilai = {1.2, 3.4, 5.6, 7.8, 9.9};
      
              System.out.println("\n3) Array NILAI:");
              for (int i = 0; i < nilai.length; i++) {
                  System.out.println("- " + nilai[i]);
              }
