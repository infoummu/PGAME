---
title: Kuliah PEMROGRAMAN GAME
published: true
---
## PERTEMUAN TIGA 03 :

|Status  | : Offline                    |
|Waktu   | : 13/10/2022                |
|Tema    | : Praktikum PGame - JAVA - Variabel dan Tipe Data|


###  Materi Dasar
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

### Contoh : 

* Contoh dari Tipe data dan Variabel : 

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
    class pgame_p3_19001 {

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

3. Lengkapi kode dibawah dengan beberapa contoh tipe data dan variabel, kemudian Simpan dengan nama file `pgame_p3_NPM.java` (ubah NPM pada nama file dengan 5 digit terakhir nomor NPM anda, contoh : `pgame_p3_19001.java`)
4. Gunakan shell CMD atau Command Propm untuk masuk ke direktori kerja anda dan jika telah selesai menulis code-nya, silahkan di-`compile` dengan perintah `javac pgame_p3_19001.java`
5. Setelah itu, hasil compile perintah ini akan menghasilkan file binari dengan nama `pgame_p3_19001.class`
6. Silahkan Eksekusi code binarinya dengan perintah  `java pgame_p3_19001.java`,
7. Jika telah selesai menjalankan code-nya dan berhasil, silahkan ambil/buat hasilnya dengan di-`screenshot`  dan beri nama `pgame_p3_19001.png`, 
9. Total hanya dua file yang harus dikirim yaitu: 
    1. file: `pgame_p3_19001.java` dan 
    2. file: `pgame_p3_19001.png`
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
    class pgame_p3_19001 {

        public static void main(String args[])
        {

            // Deklarasi Type dada dan Buat Variabel
            // Buat Variabel dan isi data dengan data Nama, NPM, dll

            // Cetak Ke layar
            System.out.println("\n Tipe Data : ");
            System.out.println("------------------");

            System.out.println("*********************************");

        }
    }


    ```

### Hasil Praktikum yang di Screenshot

Sertakan Hasil Screenshot dari praktikum anda !

Hasil...???


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

NPM - Nama

1. 19109 - Yusuf
2. 19137 - Ikram
3. 19139 - Fadli
4. 19084 - Akbar
5. 19091 - Nurmala
6. 19099 - Anti
7. 19079 - Ladeli
8. 19078 - Acan
9. 19035 - Aditya
10. 19132 - Andika
11. 19076 - Cahya
12. 19063 - Fatima
13. 19066 - Indah
14. 19087 - Laila
15. 19062 - Nadia
16. 19081 - Julaiha
17. 19059 - Arman 
18. 19114 - Ira

***
By : Ikhwan
