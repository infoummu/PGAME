---
title: Kuliah PEMROGRAMAN GAME
published: true
---

## PERTEMUAN ENAM 06 - PENGULANGAN (LOOP):

|Status  | : Online                   |
|Waktu   | : 03/11/2022               |
|Tema    | : Praktikum PGame - JAVA - PENGULANGAN (LOOP)|


### PENGULANGAN (LOOP) di JAVA

* Pengulangan merupakan operasi dasar dari algoritma.

* Operasi Pengulangan merupakan operasi yang harus ada pada semua Bahasa Pemrograman.

* Perulangan merupakan salah satu hal yang dapat digunakan untuk mengendalikan alur program lewat kata kunci (keyword) `for`, `while` dan `do - while`.


#### 1. Pengulangan `while`:

Pengulangan `while` merupakan stetmen java yang paling penting. Hal itu akan terus di lakukan pengulangan selama ekspresinya bernilai `true`. Berikut merupakan bentuk blok code pengulangan dalam java: 

```java 
while(kondisi) { // periksa kondisi yang di berikan
    // body of loop
    // isi perintah yang akan di ulang-ulang
}
```
bentuk perintah diatas akan melakukan pengulangan selama `kondisi`-nya selalu bernilai benar atau `true`, dan akan melanjutkan ke baris perintah berikutnya jika bernilai salah atau `false`.

#### 2. Pengulangan `do` - `while`:

Bentuk Pengulangan `do` - `while` merupakan kebalikan dari `while`, jika pada `while` kondisi diperiksa terlebih dahulu baru perintah di-eksekusi, maka di pengulangan `do` - `while` perintah di-eksekusi dahulu baru setelah itu kondisi yang diberikan akan diperiksa. Bentuk format penulisan blok code `do` - `while`:

```java 
do {
    // body of loop
    // isi perintah yang akan di ulang-ulang
} while(kondisi); // periksa kondisi yang di berikan
```



#### 3. Pengulangan `for`: 

Dalam pengulangan `for`, anda harus menentukan nilai awal pengulangan dan nilai akhir pengulangan.

```java 

for (nilai_awal/inisialisasi; kondisi; tambah/kurang) {
    // body of loop
    // perintah yang akan di ulang-ulang
} 
```

### IMPLEMENTASI PENGULANGAN (LOOP):

1. Tulis code pada contoh-contoh dibawah sebagai praktikum anda masing-masing, 
2. Kemudian Silahkan lakukan test untuk setiap code yang sudah ditulis,
3. Jika telah selesai menjalankan code-nya dan berhasil, silahkan ambil hasil `screenshot`-nya dari masing-masing code dan kumpul/kirim.
4. Jika telah berhasil, silahkan KUMPULKAN ke Google Drive pada LINK berikut ini [GDRIVE](https://drive.google.com/drive/folders/1dgpT55wi7BA-h-BERfI5_bJ4JBc1bJ10?usp=sharing){:target="_blank"},
5. Kumpulkan sebelum Praktikum `ke-7` yang akan datang 10/11/2022.

#### Contoh Code WHILE



*   Tulis code berikut dan simpan dengan nama file `pgame_p6_c1_19001.java`, jika berhasil dijalankan silahkan ambil `screenshot`-nya dan simpan dengan nama file `pgame_p6_c1_19001.png`.

    ```java

        // Contoh PRAKTIKUM p6_c1
        // -----------------------------

        // Anak2 Informatika UMMU Ternate
        // Mata kuliah      : Pemrograman Game
        // Praktikum        : Ke-6 / p6
        // Nama File        : pgame_p6_c1_19001 (ganti dengan npm masing2)
        // Nama Mahasiswa   : Ganti dengan Nama Anda 
        // NPM              : 19001 (contoh saja)
        // Tema             : Pengulangan - WHILE
        // *****************************************

        // Nama Class / Nama file
        class pgame_p6_c1_19001 {

            public static void main(String args[])
            {
                System.out.println("\n*******************************\n");

                // Cetak ke layar dari 0 ke 5
                int j = 0;
                    while (j <= 5) {
                    System.out.println(" Cetak data Ulangan ke -> " + j);
                    j++;
                }

                System.out.println("\n------------------------------\n");

                // Cetak ke layar dari 5 ke 0
                int i = 5;
                    while (i >= 0) {
                    System.out.println(" Cetak data Ulangan ke -> " + i);
                    i--;
                }                

                System.out.println("\n*******************************\n");
 
            }
        }

    ```


* Hasil `screenshot` code diatas dapat dilihat gambar berikut: 

    ![hasil ss p6_c1](assets/img/pgame_p6_c1_19001.png)




```java

 print();
 System.out.println();

```







#### Referensi Pertemuan ke 6: 

1. [referensi 1 - pgame/reff](https://infoummu.github.io/PGAME/Reff){:target="_blank"}
2. [referensi 2 - petanikode.com](https://www.petanikode.com/java-percabangan/){:target="_blank"}
3. [referensi 3 - kodedasar.com](https://kodedasar.com/blog/percabangan-java/){:target="_blank"}



***
***
***



## PERTEMUAN LIMA 05 - PERCABANGAN (CONDITIONAL):

|Status  | : Online                   |
|Waktu   | : 27/10/2022                |
|Tema    | : Praktikum PGame - JAVA - PERCABANGAN (CONDITIONAL)|



Sebelumnya pada pertemuan ke-3 telah dibahas jenis-jenis tipe data di dalam bahasa Java. Untuk mengolah data tersebut, butuh operator (pertemuan ke-4). Oleh karena itu pertemuan kali ini akan membahas tentang jenis percabangan dalam bahasa pemrograman Java.

### Apa itu Percabangan dalam Java ?

1.  Dalam kehidupan sehari-hari pasti kita sering menghadapi sebuah pilihan dan begitu juga dalam program. Untuk itu kita membutuhkan algoritma percabangan.

    Konsep percabangan adalah pemilihan statemen yang akan dieksekusi dimana pilihan tersebut berdasarkan kondisi tertentu untuk mengarahkan suatu proses.

2.  Percabangan hanyalah sebuah istilah yang digunakan untuk menyebut alur program yang bercabang.

    Percabangan juga dikenal dengan `“Control Flow”`, `“Struktur Kondisi”`, `“Struktur IF”`, `“Decision”`, dan lainnya. Semuanya itu sama.

#### Bentuk PERCABANGAN dan CONTOH: 



1.  Percabangan `IF`

    Percabangan ini hanya memiliki `satu kondisi` pilihan. Artinya, pilihan di dalam IF hanya akan dikerjakan kalau kondisinya benar.

    Contoh 1, `IF` (satu kondisi): 
    ```java
    // Teorinya: 
    if( kondisi ) { // hanya satu kondisi
        // lakukan sesuatu kalau kondisi benar
        // contoh: cetak pesan ke layar jika kondisi benar 
    }

    // Contoh Penerapan Codenya:
    // **************************

    // Contoh PRAKTIKUM p5_c1
    // -----------------------------
 
    // Anak2 Informatika UMMU Ternate
    // Mata kuliah      : Pemrograman Game
    // Praktikum        : Ke-5 / p5
    // Nama File        : pgame_p5_c1_19001 (ganti dengan npm masing2)
    // Nama Mahasiswa   : Ganti dengan Nama Anda 
    // NPM              : 19001 (contoh saja)
    // Tema             : Percabangan - IF
    // *****************************************

    // Nama Class
    class pgame_p5_c1_19001 {

        public static void main(String args[])
        {
            int A=5;
            if( A == 5) { // Periksa kondisi (jika nilai A == 5)
                // Jika kondisi Benar maka, cetak ke layar pesan dibawah
                System.out.println("Ya benar, A bernilai 5");
            }
        }
    }

    ```

2.  Percabangan `IF` dan `ELSE` / `IF`, `ELSE IF` dan `ELSE`

    Sedangkan percabangan IF, ELSE IF dan ELSE memiliki pilihan alternatif dan dapat menerima `beberapa kondisi` atau `lebih dari satu kondisi`, dan kalau kondisinya semua tidak terpenuhi maka kondisi ELSE yang terakhir yang akan dilaksanakan.

    * Contoh 1, `IF` dan `ELSE` (multi kondisi): 

    ```java
    // Teorinya: 
    if( kondisi ) {
    
        // lakukan sesuatu kalau kondisi BENAR
        // contoh: cetak pesan ke layar jika kondisi BENAR
    
    } else {
    
        // lakukan sesuatu kalau kondisi SALAH
        // contoh: cetak pesan ke layar jika kondisi SALAH      
    
    }

    // **************************
    // Contoh Penerapan Codenya:
    // **************************

    // Contoh PRAKTIKUM p5_c2
    // -----------------------------
 
    // Anak2 Informatika UMMU Ternate
    // Mata kuliah      : Pemrograman Game
    // Praktikum        : Ke-5 / p5
    // Nama File        : pgame_p5_c2_19001 (ganti dengan npm masing2)
    // Nama Mahasiswa   : Ganti dengan Nama Anda 
    // NPM              : 19001 (contoh saja)
    // Tema             : Percabangan - IF dan ELSE
    // *****************************************

    // Nama Class / Nama file
    class pgame_p5_c2_19001 {

        public static void main(String args[])
        {
            int B=5;
            if( B == 5) { // Periksa kondisi (jika nilai B == 5)
            
                // Jika Benar maka, cetak ke layar pesan dibawah
                System.out.println("Ya benar, B bernilai 15");
            
            } else { // Kondisi Tidak Sesuai (jika nilai B != 15)
            
                // Jika Tidak sesuai kondisi, maka cetak ke layar pesan dibawah
                System.out.println("SALAH, B TIDAK SAMA DENGAN 15");
            
            }
       }
    }
    ```

    * Contoh 2 `IF`, `IF ELSE` dan `ELSE` (multi kondisi): 

    ```java
    // Teorinya: 
    if( kondisi 1 ) { // kondisi 1
    
        // lakukan sesuatu kalau kondisi 1 BENAR
        // contoh: cetak pesan ke layar jika kondisi 1 BENAR
    
    } else if ( kondisi 2 ) { // kondisi 2 {
    
        // lakukan sesuatu kalau kondisi 2 BENAR
        // contoh: cetak pesan ke layar jika kondisi 2 BENAR     
    
    } else {
    
        // lakukan sesuatu kalau kondisi 1 dan 2 SALAH
        // contoh: cetak pesan ke layar jika kondisi 1 dan 2 SALAH      
    
    }


    // **************************
    // Contoh Penerapan Codenya:
    // **************************

    // Contoh PRAKTIKUM p5_c3
    // -----------------------------
 
    // Anak2 Informatika UMMU Ternate
    // Mata kuliah      : Pemrograman Game
    // Praktikum        : Ke-5 / p5
    // Nama File        : pgame_p5_c3_19001 (ganti dengan npm masing2)
    // Nama Mahasiswa   : Ganti dengan Nama Anda 
    // NPM              : 19001 (contoh saja)
    // Tema             : Percabangan - IF, IF ELSE dan ELSE
    // *****************************************

    // Nama Class / Nama file
    class pgame_p5_c3_19001 {

        public static void main(String args[])
        {
            int C=8;
            if ( C == 8) { // Periksa kondisi 1 (jika nilai C == 8)
            
                // Jika Benar maka, cetak ke layar pesan dibawah
                System.out.println("Ya benar, C bernilai " + C);
            
            } else if ( C >= 4) { // Periksa kondisi 2 (jika nilai C >= 4)
            
                // Jika Benar maka, cetak ke layar pesan dibawah
                System.out.println("Ya benar, C >= 4");
            
            } else { // Kondisi 1 dan Kondisi 2 Tidak Sesuai 
            
                // Jika kondisi 1 dan 2 Tidak sesuai, maka cetak ke layar pesan dibawah
                System.out.println("SALAH SEMUA  !!!");
            
            }
        }
    }

    ```

3.  Percabangan `SWITCH` dan `CASE`

    Percabangan `SWITCH` dan `CASE` sebenarnya adalah bentuk lain dari IF/ELSE/IF.

    Bedanya, percabangan ini menggunakan kata kunci `switch` dan `case`.

    * Contoh 1 `SWITCH` dan `CASE`:

    ```java

    // **************************
    // Contoh Penerapan Codenya:
    // **************************

    // Contoh PRAKTIKUM p5_c4
    // -----------------------------

    // Anak2 Informatika UMMU Ternate
    // Mata kuliah      : Pemrograman Game
    // Praktikum        : Ke-5 / p5
    // Nama File        : pgame_p5_c4_19001 (ganti dengan npm masing2)
    // Nama Mahasiswa   : Ganti dengan Nama Anda 
    // NPM              : 19001 (contoh saja)
    // Tema             : Percabangan - SWITCH dan CASE
    // *****************************************

    // Nama Class / Nama file
    class pgame_p5_c4_19001 {

        public static void main(String args[])
        {

            char NILAI='B';
            switch (NILAI) {
            case 'A':

                // Jika variabel "NILAI" isinya "A"
                System.out.println("Dapat Nilai A");
                break;
                
            case 'B':

                // Jika variabel "NILAI" isinya "B"
                System.out.println("Dapat Nilai B");
                break;
                
            default:

                // Jika variabel "NILAI" isinya SELAIN "A" dan "B"
                System.out.println("Dapat Nilai Kurang");
            }
        }
    }
            

    ```

### Arahan Praktikum ke 5: 

3. Tulis code pada contoh-contoh diatas dan lakukan praktikum sebagaimana anda praktikum di LAB pada pertemuan2 sebelumnya,
6. Kemudian Silahkan lakukan test untuk setiap code yang sudah ditulis,
7. Jika telah selesai menjalankan code-nya dan berhasil, silahkan ambil hasil `screenshot`-nya dan beri nama `pgame_p5_c1_19001.png` sampai dengan `pgame_p5_c5_19001.png`, 
8. Total ada 5 file `code` yang harus dikirim yaitu: 
    1. file: `pgame_p5_c1_19001.java`,  
    2. file: `pgame_p5_c2_19001.java`, dan seterusnya sampai 
    3. file: `pgame_p5_c5_19001.java`, 

    dan juga masing-masing dengan hasil `screenshot`nya:
    1. file: `pgame_p5_c1_19001.png`,
    2. file: `pgame_p5_c2_19001.png`, dan seterusnya sampai
    4. file: `pgame_p5_c5_19001.png`.
9. Jika telah berhasil, silahkan KUMPULKAN ke Google Drive pada LINK berikut ini [GDRIVE](https://drive.google.com/drive/folders/1dgpT55wi7BA-h-BERfI5_bJ4JBc1bJ10?usp=sharing){:target="_blank"},
10. Kumpulkan sebelum Praktikum `ke-6` yang akan datang 03/11/2022.


### TUGAS Praktikum Pertemuan ke 5:

*   TUGAS, Buatlah sebuah code untuk kondisi sebagai berikut:
    1. Sebuah variabel bernama NPM
    2. Jika Nilai NPM <= 50, maka cetak ke layar " Anda INFO 1"
    3. Jika Nilai NPM <= 100, maka cetak ke layar " Anda INFO 2"
    4. Jika Nilai NPM <= 150, maka cetak ke layar " Anda INFO 3"
    5. Selain itu cetak ke Layar " Anda TIDAK TERDADTAR !"

*   Tulis dan Simpan TUGAS anda diatas dengan nama file `pgame_p5_c5_19001.java`, dan hasilnya berupa `screenshot` dengan nama file `pgame_p5_c5_19001.png`,
*   Setelah Selesai, silahkan KUMPULKAN ke Google Drive pada LINK berikut ini [GDRIVE](https://drive.google.com/drive/folders/1dgpT55wi7BA-h-BERfI5_bJ4JBc1bJ10?usp=sharing){:target="_blank"}.

#### Referensi Pertemuan ke 5: 

1. [referensi 1 - pgame/reff](https://infoummu.github.io/PGAME/Reff){:target="_blank"}
2. [referensi 2 - petanikode.com](https://www.petanikode.com/java-percabangan/){:target="_blank"}
3. [referensi 3 - kodedasar.com](https://kodedasar.com/blog/percabangan-java/){:target="_blank"}


***
***
***


## PERTEMUAN EMPAT 04 - OPERATOR :

|Status  | : Offline                   |
|Waktu   | : 20/10/2022                |
|Tema    | : Praktikum PGame - JAVA - Operator|


### Operator dalam Java
Sebelumnya telah dibahas jenis-jenis tipe data di dalam bahasa Java. Untuk mengolah data tersebut, butuh operator. Oleh karena itu pertemuan kali ini akan membahas tentang jenis-jenis operator dalam bahasa pemrograman Java.


### Operand dan Operator dalam Java

Dalam bahasa Java, terdapat istilah `operand` dan `operator`. 
`Operand` adalah nilai asal yang dipakai dalam sebuah proses operasi. 
Sedangkan `Operator` adalah instruksi yang diberikan untuk mendapatkan hasil dari proses tersebut.

Contoh, pada operasi: 10 + 2. Angka 10 dan 2 disebut sebagai `operand`, sedangkan tanda tambah (karakter +) adalah `operator`.

### Sifat Operator :

Berdasarkan Sifat Operator dari `jumlah OPERAND-nya`, operator dibagi menjadi 3 jenis: Operator `Unary`, Operator `Binary` dan Operator `Ternary.`

1. Operator `Unary`,

    Operator `Unary` adalah operator yang hanya terdiri dari 1 operand (masukan/input). Contohnya adalah operator positif (plus): +7, +9, +10.111

    Biasanya dipakai di perulangan (looping) atau di sebuah logika if

    |Operator   |   Keterangan  |
    |-----------|---------------|
    |+	    | Positif (tanda nilai variabel tersebut bernilai positif)  |
    |-	    |Negatif (tanda nilai variabel tersebut bernilai negatif)   |
    |++	    |Tambah 1 (nilai variabel ditambahkan satu)                 |
    |--     |kurang 1 (nilai variabel dikurangi satu)                   |
    |!	    |kebalikan nilai boolean (artinya misal variabel awal bernilai true, setelah di manipulasi dengan operator ! menjadi nilainya false) |


2. Operator `Binary`,

    Operator `Binary` adalah operator yang terdiri dari 2 operand (masukan/input). Sebagian besar operator di dalam bahasa Java termasuk ke dalam operator binary. Contohnya seperti operator aritmatika: 4 + 8, 9 * 2, 8 % 2, dll.

3. Operator `Ternary`,

    Operator `Ternary `adalah operator yang terdiri dari 3 operand (masukan/input). Bahasa Java memiliki 1 operator ternary, yakni ” ? : ” seperti (a == 1) ? 20: 30.

### Jenis Operator :

Berdasarkan Fungsinya, Jenis Operator dapat dibagi menjadi beberapa jenis sebagai berikut:

1. Operator `Aritmatika`

    Operator aritmatika adalah operator yang biasa kita temukan untuk operasi matematika. Aritmatika sendiri merupakan cabang ilmu matematika yang membahas perhitungan sederhana seperti kali, bagi, tambah, kurang dan % yang dipakai untuk mencari sisa hasil bagi.

    |Operator   |Penjelasan     |Contoh |
    |-----------|---------------|-------|
    |+ 	    |Penambahan 	    |a = 5 + 2  |
    |– 	    |Pengurangan 	|a = 5 – 2  |
    |* 	    |Perkalian 	    |a = 5 * 2  |
    |/ 	    |Pembagian 	    |a = 5 / 2  |
    |% 	    |Sisa hasil bagi (modulus) 	|a = 5 % 2|

2. Operator Increment dan Decrement

    Operator increment dan decrement adalah sebutan untuk operasi seperti a++, dan a--. Ini sebenarnya penulisan singkat dari operasi a = a + 1 serta a = a – 1.

    Increment digunakan untuk menambah variabel sebanyak 1 angka, sedangkan decrement digunakan untuk mengurangi variabel sebanyak 1 angka.

    Penulisannya menggunakan tanda tambah 2 kali untuk increment, dan tanda kurang 2 kali untuk decrement. Penempatan tanda tambah atau kurang ini boleh di awal seperti ++a dan --a, atau di akhir variabel seperti a++ dan a--.

    Dengan demikian terdapat 4 jenis increment dan decrement dalam bahasa Java:

    |Operator       |Penjelasan         | Contoh        |
    |---------------|-------------------|---------------|
    |Pre-increment 	    |Tambah a sebanyak 1 angka, lalu tampilkan hasilnya     |++a |	
    |Post-increment 	|Tampilkan nilai a, lalu tambah a sebanyak 1 angka      |a++ |	
    |Pre-decrement 	    |Kurangi a sebanyak 1 angka, lalu tampilkan hasilnya    |--a |	
    |Post-decrement 	|Tampilkan nilai a, lalu kurangi a sebanyak 1 angka     |a-- |	



3. Operator Perbandingan / Relasional

    Operator perbandingan dipakai untuk membandingkan 2 buah nilai, apakah nilai tersebut sama besar, lebih kecil, lebih besar, dll. Hasil dari operator perbandingan ini adalah boolean True atau False.

    Tabel berikut merangkum hasil dari operator perbandingan dalam bahasa Java:

    |Operator 	|Penjelasan 	                |Contoh 	|Hasil  |
    |-----------|-------------------------------|-----------|-------|
    | == 	    | Sama dengan 	                | 5 == 5 	|true   |
    | != 	    | Tidak sama dengan 	        | 5 != 5 	|false  |
    | > 	    | Lebih besar 	                | 5 > 6 	|false  |
    | < 	    | Lebih kecil 	                | 5 < 6 	|true   |
    | >= 	    | Lebih besar atau sama dengan 	| 5 >= 3 	|true   |
    | <= 	    | Lebih kecil atau sama dengan 	| 5 <= 5 	|true   |



4. Operator Logika / Boolean

    Operator logika dipakai untuk menghasilkan nilai boolean true atau false dari 2 kondisi atau lebih. Tabel berikut merangkum hasil dari operator logika dalam bahasa Java:

    | Operator       | Nama 	    |Penjelasan | 	Contoh  |
    |----------------|--------------|-----------|-----------|
    | && 	|And 	|Akan menghasilkan true jika kedua operand true 	| true && false, hasilnya: false |
    | \|\| 	|Or 	|Akan menghasilkan true jika salah satu operand true 	| true \|\| false, hasilnya: false |
    | ! 	|Not 	|Akan menghasilkan true jika operand false 	| !false, hasilnya: true |



5. Operator Bitwise

    Bitwise adalah operator khusus untuk menangani operasi logika bilangan biner dalam bentuk bit.

    Bilangan biner sendiri merupakan jenis bilangan yang hanya terdiri dari 2 jenis angka, yakni 0 dan 1. Jika nilai asal yang dipakai bukan bilangan biner, akan dikonversi secara otomatis oleh compiler Java menjadi bilangan biner. Misalnya 7 desimal = 0111 dalam bilangan biner.

    Bahasa Java mendukung 6 jenis operator bitwise. Daftar lengkapnya dapat dilihat pada tabel berikut:

    | Operator 	| Nama 	    | Contoh 	    | Biner 	        | Hasil (biner) 	| Hasil (desimal) | 
    |-----------|-----------|---------------|-------------------|-------------------|-----------------|
    | & 	    | AND 	    | 10 & 12 	    | 1010 & 1100 	    | 1000 	            | 8               | 
    | \| 	    | OR 	    | 10 \| 12 	    | 1010 \| 1100 	    | 1110 	            | 14              | 
    | ^ 	    | XOR 	    | 10 ^ 1 	    | 1010 ^ 1100 	    | 0110 	            | 6                | 
    | ~ 	    | NOT 	    | ~10 	        | ~1010 	        | 0101 	            | -11 (Two’s complement) | 
    | << 	    | Left shift  | 10 << 1 	| 1010 << 1 	    | 10100 	        | 20                | 
    | >>      	| Right shift | 10 >> 1 	| 1010 >> 1 	    | 101 	            | 5                 | 


6. Operator Assignment

    Operator assignment adalah operator yang digunakan untuk memberikan nilai ke dalam suatu variabel. Di dalam bahasa Java, operator assignment menggunakan tanda sama dengan ” = “. Nantinya juga terdapat operator assignment gabungan, seperti ” += “, ” -= “, dsb.


7. Operator Type Comparison

    Operator type comparison adalah sebutan untuk operator khusus yang dipakai untuk pemeriksaan sebuah object. Di dalam bahasa Java operator ini menggunakan perintah `instanceof`. 



### Kerjakan Praktikkum : 

1. Tulis kode dibawah kemudian Simpan dengan nama file `pgame_p4_c1_NPM.java` (ubah NPM pada nama file dengan 5 digit terakhir nomor NPM anda, contoh : `pgame_p4_c1_19001.java`)
2. Setelah itu jalankan untuk di test di cmd/poweshell/terminal, perintahnya: `java pgame_p4_c1_19001.java`
3. Kemudian, lanjutkan Praktikumnya dengan buat file baru untuk praktikum code selanjutnya sampai jenis operator ke-7 yaitu `instanceof`.

* Code `p4_c1`: 

    ```java

    // Anak2 Informatika UMMU Ternate
    // Mata kuliah      : Pemrograman Game
    // Praktikum        : Ke-4 / p4
    // Nama File        : pgame_p4_c1_19001 (ganti dengan npm masing2)
    // Nama Mahasiswa   : Ganti dengan Nama Anda 
    // NPM              : 19001 (contoh saja)
    // Tema             : Operator - Aritmatika
    // *****************************************


    // Nama Class
    class pgame_p4_c1_19001 {

        public static void main(String args[])
        {

            // Latihan P4 - C1
            int   a, b;    // buat/deklarasi variabel kosong a dan b tipe integer
            float c, d;    // buat/deklarasi variabel kosong c dan d tipe float
            double xab, xcd; // buat/deklarasi variabel kosong xab dan xcd tipe double

            // isi variabel dengan nilai 
            a = 5;
            b = 10;
            c = 15;
            d = 3.1F;

            // operasi Aritmatika Penjumlahan
            xab = a + b;
            xcd = c + d;

            // Cetak Ke layar            
            System.out.println(" Nama : Ikhwan (ganti nama anda)" );
            System.out.println(" NPM  : 19001  (ganti npm anda)" );
            System.out.println("\n Operator Aritmatika : ");
            System.out.println("------------------");
            System.out.println(a);
            System.out.println(b);
            System.out.println(c);

            System.out.println("\nHasil Penambahan : ");
            System.out.println(xab);
            System.out.println(xcd);

            // operasi Aritmatika Pengurangan
            xab = c - a;
            xcd = c - d;

            System.out.println("\nHasil Pengurangan : ");
            System.out.println(xab);
            System.out.println(xcd);

            // operasi Aritmatika Pembagian
            // Lanjutkan ...


            System.out.println("*********************************");

        }
    }


    ```

### Latihan Praktikum 4 Lanjutan Operator :

3. Lanjutkan kode diatas untuk jenis operator lainnya, kemudian Simpan dengan nama file masing-masing dari `pgame_p4_c2_NPM.java` sampai `pgame_p4_c7_NPM.java` (ubah NPM pada nama file dengan 5 digit terakhir nomor NPM anda, contoh : `pgame_p3_c2_19001.java`)
4. Gunakan shell CMD atau Command Propm untuk masuk ke direktori kerja anda dan jika telah selesai menulis code-nya, silahkan di-`compile` dengan perintah `pgame_p4_c2_NPM.java`
5. Setelah itu, hasil compile perintah ini akan menghasilkan file binari dengan nama `pgame_p4_c2_19001.class`
6. Silahkan Eksekusi code binarinya dengan perintah  `java pgame_p4_c2_19001.java`,
7. Jika telah selesai menjalankan code-nya dan berhasil, silahkan ambil/buat hasilnya dengan di-`screenshot`  dan beri nama `pgame_p4_c2_19001.png`, 
9. Total ada 7 file `code` yang harus dikirim yaitu: 
    1. file: `pgame_p4_c1_19001.java`,  
    2. file: `pgame_p4_c2_19001.java`, dan seterusnya sampai 
    3. file: `pgame_p4_c7_19001.java`, 

    dan juga masing-masing dengan hasil screenshotnya:
    1. file: `pgame_p4_c1_19001.png`,
    2. file: `pgame_p4_c2_19001.png`, dan seterusnya sampai
    4. file: `pgame_p4_c7_19001.png`.
8. Jika telah berhasil, silahkan KUMPULKAN ke Google Drive pada LINK berikut ini [GDRIVE](https://drive.google.com/drive/folders/1dgpT55wi7BA-h-BERfI5_bJ4JBc1bJ10?usp=sharing){:target="_blank"}


### Hasil Screenshot Hasil code "p4_c1" 

* Melihat hasil screenshot code p4_c1: 
    ![compile code](assets/img/pgame_p4_c1_2022-10-14_09-54-21.png)


### Yang Hadir Pertemuan Ke-4

1. Yang Menyelesaikan Praktikumm `p4_c1` - `p4_c7` di LAB : 

    |No. | NPM      | Nama          |
    |----|----------|---------------|
    | 1. | 19059 	| MUHAMMAD ARMAN | 
    | 2. | 19076 	| CAHYA ANDRIANTI | 
    | 3. | 19109 	| YUSUP HI BISNU | 
    | 4. | 19132 	| ANDIKA PRATAMA ODE | 
    | 5. | 19137 	| MUHAMMAD IQRAM LATULUMAMINA | 
    | 6. | 19139 	| MUHAMMAD FADLI KHARIE | 


2. Yang Harus kumpul Sebelum Sabtu 22/10/2022 :

    |No. | NPM      | Nama          |
    |----|----------|---------------|
    | 1. | 22127 | Ramli  | 
    | 2. | 19084 | Akbar | 
    | 3. | 19099 | Anti  | 
    | 4. | 19079 | Ladeli | 
    | 5. | 19035 | Aditya  | 
    | 6. | 19063 | Fatima | 
    | 7. | 19087 | Laila | 
    | 8. | 19062 | Nadia | 
    | 9. | 19081 | Julaiha | 
    | 10. | 19112 | Nandi | 
    | 11. | 19114 | Ira | 


***

#### Reff Pertemuan ke 4: 

1. [reff 1](https://www.duniailkom.com/tutorial-belajar-java-jenis-jenis-operator-dalam-bahasa-java/){:target="_blank"}
2. [reff 2](http://mastahcode.com/blog/belajar-java-dasar-8-operator-unary-MLJ){:target="_blank"}



***
***
***



## PERTEMUAN TIGA 03 - Variabel & Tipe Data:

|Status  | : Offline                    |
|Waktu   | : 13/10/2022                |
|Tema    | : Praktikum PGame - JAVA - Variabel dan Tipe Data|


###  Keyword, Variabel dan Tipe Data di Java

1.  `Keyword dalam Java`
    Kata kunci adalah identifier yang telah dipesan untuk didefinisikan sebelumnya oleh Java
    untuk tujuan tertentu. Anda tidak dapat menggunakan keyword sebagai nama variabel, class,
    method anda, dsb
2.  `Tipe Data Primitif`
    Bahasa pemrograman Java mendefinisikan delapan tipe data primitif. Mereka diantaranya
    adalah boolean (untuk bentuk logika), char (untuk bentuk tekstual), byte, short, int, long (integral),
    double and float (floating point).
3.  `Variabel`,
    Variabel adalah item yang digunakan data untuk menyimpan pernyataan objek. Variabel
    memiliki tipe, data dan nama. Tipe data menandakan tipe nilai yang dapat dibentuk oleh variabel itu
    sendiri. Nama variabel harus mengikuti aturan untuk identifier.

### KEYWORD dalam Bahasa Pemrograman JAVA

Berikut merupakan daftar keyword yang biasa digunakan dalam Bahasa Pemrograman Java :

|abstract|   continue|  for|         new|         switch|
|assert***|  default|   goto*|       package|     synchronized|
|boolean|    do|        if|          private|     this|
|break|      double|    implements|  protected|   throw|
|byte|       else|      import|      public|      throws|
|case|       enum****|  instanceof|  return|      transient|
|catch|      extends|   int|         short|       try|
|char|       final|     interface|   static|      void|
|class|      finally|   long|        strictfp**|  volatile|
|const*|     float|     native|      super|       while|


<!-- * Note: 
    `*` 	not used
    `**` 	added in 1.2
    `***` 	added in 1.4
    `****` 	added in 5.0 -->

### Type Data di JAVA

- `byte` (number, 1 byte)
- `short` (number, 2 bytes)
- `int` (number, 4 bytes)
- `long` (number, 8 bytes)
- `float` (float number, 4 bytes)
- `double` (float number, 8 bytes)
- `char` (a character, 2 bytes)
- `boolean` (true or false, 1 byte)

### Kerjakan Praktikkum : 

1. Tulis kode dibawah kemudian Simpan dengan nama file `pgame_p3_c1_NPM.java` (ubah NPM pada nama file dengan 5 digit terakhir nomor NPM anda, contoh : `pgame_p3_c1_19001.java`)
2. Setelah itu jalankan untuk di test di cmd/poweshell/terminal, perintahnya: `java pgame_p3_c1_19001.java`
3. Jika berhasil, lanjutkan untuk ekplorasi code tersebut ke code berikutnya.

* Contoh dari Tipe data dan Variabel : 

    ```java

    // Anak2 Informatika UMMU Ternate
    // Mata kuliah      : Pemrograman Game
    // Praktikum        : Ke-3 / p3
    // Nama File        : pgame_p3_c1_19001 (ganti dengan npm masing2)
    // Nama Mahasiswa   : Ganti dengan Nama Anda 
    // NPM              : 19001 (contoh saja)
    // Materi           : Tipe Data dan Variabel
    // *****************************************


    // Nama Class
    class pgame_p3_c1_19001 {

        public static void main(String args[])
        {

            // Deklarasi Type dada dan Buat Variabel
            int data_angka = 7;                     // Tipe data Integer/nomor/angka
            float data_float = 3.39f;               // Tipe data float
            char data_karakter = 'A';               // Tipe data karakter
            boolean data_bool = true;               // Tipe data Boolean
            String data_teks = "Informatika UMMU";  // Tipe data String

            // Cetak Ke layar
            System.out.println("\n Tipe Data : ");
            System.out.println("------------------");
            System.out.println(data_angka);
            System.out.println(data_float);
            System.out.println(data_karakter);
            System.out.println(data_bool);
            System.out.println(data_teks);
            System.out.println("*********************************");

        }
    }


    ```

### Eksplore code diatas :

3. Lengkapi kode dibawah dengan beberapa contoh tipe data dan variabel, kemudian Simpan dengan nama file `pgame_p3_c2_NPM.java` (ubah NPM pada nama file dengan 5 digit terakhir nomor NPM anda, contoh : `pgame_p3_c2_19001.java`)
4. Gunakan shell CMD atau Command Propm untuk masuk ke direktori kerja anda dan jika telah selesai menulis code-nya, silahkan di-`compile` dengan perintah `javac pgame_p3_19001.java`
5. Setelah itu, hasil compile perintah ini akan menghasilkan file binari dengan nama `pgame_p3_19001.class`
6. Silahkan Eksekusi code binarinya dengan perintah  `java pgame_p3_19001.java`,
7. Jika telah selesai menjalankan code-nya dan berhasil, silahkan ambil/buat hasilnya dengan di-`screenshot`  dan beri nama `pgame_p3_19001.png`, 
9. Total hanya dua file yang harus dikirim yaitu: 
    1. file: `pgame_p3_c1_19001.java`,
    2. file: `pgame_p3_c2_19001.java`, 
    3. file: `pgame_p3_c1_19001.png`,
    4. file: `pgame_p3_c2_19001.png` dan
8. Jika telah berhasil, silahkan KUMPULKAN ke Google Drive pada LINK berikut ini [GDRIVE](https://drive.google.com/drive/folders/1dgpT55wi7BA-h-BERfI5_bJ4JBc1bJ10?usp=sharing){:target="_blank"}

    ```java
    // Anak2 Informatika UMMU Ternate
    // Mata kuliah      : Pemrograman Game
    // Praktikum        : Ke-3 / p3
    // Nama File        : pgame_p3_19001 (ganti dengan npm masing2)
    // Nama Mahasiswa   : Ganti dengan Nama Anda 
    // NPM              : 19001 (contoh saja)
    // Materi           : Tipe Data dan Variabel
    // *****************************************

    // Nama Class
    class pgame_p3_c2_19001 {

        public static void main(String args[])
        {

            // Deklarasi Type dada dan Buat Variabel
            // Buat Variabel dan isi data dengan data Nama, NPM, dll
            String nama = "Ikhwan"; // deklarasi variabel "nama" dengan data bernilai "Yusuf"
            String npm  = "19001"; // deklarasi variabel "npm" dengan data bernilai "19109"
            int tgl = 13102022;

            int usia ;
            float tinggi, ideal;
            int berat;

            tinggi  = 175.8f;
            usia = 100;
            berat = 75;
            // ideal = tinggi / berat;
            ideal = ((tinggi-100) - (0.10f*(tinggi-100))) ;
            // Cetak Ke layar
            System.out.println("\n Latihan Variabel : ");
            System.out.println("------------------");
            System.out.println(" Nama : " + nama );
            System.out.println(" NPM  : " + npm );
            System.out.println(" TGL  : " + tgl );

            System.out.println(" Usia \t: " + usia);
            System.out.println(" Tinggi\t: " + tinggi  + " CM.");
            System.out.println(" Berat \t: " + berat  + " Kg.");
            System.out.println(" Berat Ideal \t: " + ideal + " Kg.");

            System.out.println("*********************************\n");

        }
    }

    ```

### Hasil Praktikum yang di Screenshot

Sertakan Hasil Screenshot dari praktikum anda !

* Melihat hasil screenshot code 1 (c1);
    ![compile code](assets/img/pgame_p3_c1_2022-10-14_08-09-10.png)


* Melihat hasil screenshot code 2 (c2), hasil dari explorasi dari code sebelumnya ;
    ![compile code](assets/img/pgame_p3_c2_2022-10-14_09-54-21.png)



. 

***
***
***


## PERTEMUAN DUA 02 :

|Status  | : Online                    |
|Waktu   | : 06/10/2022                |
|Tema    | : Praktikum PGame - JAVA - Output Text dan Number|

### ARAHAN untuk Praktikum Pertemuan Ke-2

1. Materi online dan offline dapat dilihat di [Reff (Referensi)](/PGAME/Reff){:target="_blank"}
1. Silahkan masuk ke [halaman Download JDK ini](https://www.oracle.com/java/technologies/downloads/#jdk19-windows){:target="_blank"} atau 
3. langsung Doawnload Java Development Kit (JDK) di sini [Download_JDK](https://download.oracle.com/java/19/latest/jdk-19_windows-x64_bin.exe){:target="_blank"}
4. Silahkan install JDK-nya setelah anda download, 
5. Install juga Text Editor yang akan digunakan untuk Edit code (bisa pake Visual Code, Subleme, Atom, atua Notepad++)
6. Cara install JDK bisa dilihat:
    1. di sini [Cara Install JDK - file pdf](assets/reff/Install_jdk_1.pdf){:target="_blank"}
    2. di sini [Cara Insall JDK - https://www.nesabamedia.com/cara-install-jdk-di-windows-10](https://www.nesabamedia.com/cara-install-jdk-di-windows-10/){:target="_blank"}, dan
    2. di sini [Cara Install JDK - https://www.kodingindonesia.com/cara-install-jdk/](https://www.kodingindonesia.com/cara-install-jdk/){:target="_blank"}, atau
    3. di `google` aja [Cara Install JDK](https://www.google.com/search?q=cara+install+jdk+di+windows+10+dengan+gambar&sxsrf=ALiCzsbaQh2mAxy1QXGgacc3OHTepvbkxQ%3A1665473279828&ei=_xpFY73wMZ7QseMP8f6UyAg&ved=0ahUKEwj96-e509f6AhUeaGwGHXE_BYkQ4dUDCA0&uact=5&oq=cara+install+jdk+di+windows+10+dengan+gambar&gs_lcp=Cgdnd3Mtd2l6EAM6CggAEEcQ1gQQsAM6DQgAEOQCENYEELADGAFKBAhNGAFKBAhBGABKBAhGGAFQtAZYyWhg0WpoAXABeAGAAeQCiAHTLpIBCDAuMjIuOC4xmAEAoAEByAENwAEB2gEGCAEQARgJ&sclient=gws-wiz){:target="_blank"}



### Tugas Praktikum Pertemuan ke2 : 

1. Buatlah Folder khusus yang akan digunakan untuk menyimpan hasil praktikum anda
2. Kerjakan Praktikum Mandiri dengan Menulis code dibawah
3. Tulis Code dibawah, kemudian Simpan dengan nama file `pgame_p2_NPM.java` (ubah NPM pada nama file dengan 5 digit terakhir nomor NPM anda, contoh : `pgame_p2_19001.java`)
4. Gunakan shell CMD atau Command Propm untuk masuk ke direktori kerja anda dan jika telah selesai menulis code-nya, silahkan di-`compile` dengan perintah `javac pgame_p2_19001.java`
5. Setelah itu, hasil compile perintah ini akan menghasilkan file binari dengan nama `pgame_p2_19001.class`
6. Silahkan Eksekusi code binarinya dengan perintah  `java pgame_p2_19001.java`,
7. Jika telah selesai menjalankan code-nya dan berhasil, silahkan ambil/buat hasilnya dengan di-`screenshot`  dan beri nama `pgame_p2_19001.png`, 
9. Total hanya dua file yang harus dikirim yaitu: 
    1. file: `pgame_p2_19001.java` dan 
    2. file: `pgame_p2_19001.png`
8. Jika telah berhasil, silahkan KUMPULKAN ke Google Drive pada LINK berikut ini [GDRIVE](https://drive.google.com/drive/folders/1dgpT55wi7BA-h-BERfI5_bJ4JBc1bJ10?usp=sharing){:target="_blank"}

    ```java
    // Anak2 Informatika UMMU Ternate
    // Mata kuliah      : Pemrograman Game
    // Praktikum        : Ke-2 / p2
    // Nama File        : pgame_p2_19001 (ganti dengan npm masing2)
    // Nama Mahasiswa   : Ganti dengan Nama Anda 
    // NPM              : 19001 (contoh saja)
    // *****************************************

    // nama class (pgame_p2_19001) harus sama dengan nama file *
    public class pgame_p2_19001 {
        public static void main(String args[])
        {
            // print out text
            System.out.println("\n Halo Informatika UMMU !");
            System.out.println(" Nama    : Ikhwan Elyas");
            System.out.println(" NPM     : 19001");
            System.out.println(" Jurusan : Sistem Informasi");
            System.out.println(" Prodi   : Informatika");
            System.out.println(" Kampus  : UMMU Ternate");
            System.out.println("--------------------------");
            // print out number/angka
            System.out.println(12345);

            System.out.println("***************************************\n");
        }
    }

    ```

### Update Code : 


```java

// nama class (pgame_p2_19001) harus sama dengan nama file *
public class pgame_p2_19001 {
    public static void main(String args[])
    {
        // print out text
        System.out.println("\n Halo Informatika UMMU !");
        System.out.println(" Nama    : Ikhwan Elyas");
        System.out.println(" NPM     : 19001");
        System.out.println(" Jurusan : Sistem Informasi");
        System.out.println(" Prodi   : Informatika");
        System.out.println(" Kampus  : UMMU Ternate");
        System.out.println("--------------------------");
        // print out number/angka
        System.out.println(12345);
        System.out.println(67890);
        System.out.println(" " + 12345);
        System.out.println(" " + 67890); 
        System.out.println(" Number : " + 12345);
        System.out.println(" Number : " + 67890);         
        System.out.println("***************************************\n");
    }
}

```

### Hasil Praktikum yang di Screenshot

* Cek File pada lokasi/Direktory Praktikum 
    ![cek file dan dir](assets/img/pgame_p2_2022-10-11_15-15-30_dir0.png)

* Proses Compile code java menggunakan perintah `javac` 
    ![compile code](assets/img/pgame_p2_2022-10-11_15-17-30_cmp.png)


* Proses cek kembali file setelah berhasil di-compile
    ![compile code](assets/img/pgame_p2_2022-10-11_15-17-58_dir1.png)


* Proses Eksekusi untuk melihat hasilnya 
    ![compile code](assets/img/pgame_p2_2022-10-11_15-28-50_exe.png)


* Tampak Hasil akhir setelah dieksekusi, dan berhasil.

Praktikum Ke-2 Selesai.


***
***

## PERTEMUAN PERTAMA 01 :

|Status  | : Offline                    |
|Waktu   | : 29/09/2022                |
|MK      | : PEMROGRAMAN GAME - JAVA - P1 |
|Tema    | : Arahan dan Kontrak Kuliah|



### Variabel dan Persentase Penilaian :
- Absen  : 40 %
    - Absen Untuk Pertemuan Online dihitung berdasarkan yang mengumpulkan file praktikum
- Tugas  : 40 %
    - Tugas yang AKAN DINILAI adalah tugas yang dikerjakan dan dikumpulkan SESUAI DENGAN KETENTUAN, dan dikupul ke `Google Drive` (nanti di-share linknya)
    - Setiap tugas akan disampaikan ketentuan apa saja yang harus dipenuhi, Usahakan untuk memenuhi semua ketentuan yang ditetapkan oleh dosen.
- UTS dan UAS : 20 % (UTS 10% dan UAS 10%)


### Hasil Pertemuan ke-1, 29/09/2022
* Pemrograman Game: 
    1. Belajar Java (sesi 1 : Pertemuan 2-7)
    2. Belajar Greenfoot (Sesi 2 : Pertemuan 9-15)

### Yang Hadir Pertemuan ke-1: 

Nama-nama yang hadir pada pertemuan pertama,

|No.    | NPM       | Nama          |
|-------|-----------|---------------|
| 1. | 19109 |  Yusuf       |
| 2. | 19137 |  Ikram       |
| 3. | 19139 |  Fadli       |
| 4. | 19084 |  Akbar       |
| 5. | 19091 |  Nurmala     |
| 6. | 19099 |  Anti        |
| 7. | 19079 |  Ladeli      |
| 8. | 19078 |  Acan        |
| 9. | 19035 |  Aditya      |
| 10. | 19132 |  Andika     |
| 11. | 19076 |  Cahya      |
| 12. | 19063 |  Fatima     |
| 13. | 19066 |  Indah      |
| 14. | 19087 |  Laila      |
| 15. | 19062 |  Nadia      |
| 16. | 19081 |  Julaiha    |
| 17. | 19059 |  Arman      |
| 18. | 19114 |  Ira        |



***
By : Ikhwan
