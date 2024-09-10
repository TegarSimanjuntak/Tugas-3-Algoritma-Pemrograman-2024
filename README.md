# Tugas-3-Alprog-2024-
[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/-aI7sY65)
# Tugas 2 Praktikum Algoritma dan Pemrograman 2024: Operator & Conditional Statement

**PENTING: Harap untuk membaca instruksi di [wiki](https://github.com/praktikum-tiunpad-angkatan-2022/modul-algoritma-dan-pemrograman/wiki) terlebih dahulu sampai dipahami sebelum mengerjakan soal!**

**Penting Juga: Biasakan menambah format berikut pada bagian paling atas setiap file kode!**

```cpp
/*
Nama Program :
Nama         :
NPM          :
Tanggal Buat :
Deskripsi    :
*/
```

## Daftar Isi
- [Latihan 1](#latihan-1)
- [Latihan 2](#latihan-2)
- [Latihan 3](#latihan-3)
- [Nilai Mutu Terbaru](#nilai-mutu-terbaru)
- [Manhattan Distance](#manhattan-distance)
- [Segitiga Apa?](#segitiga-apa)
- [Rumus ABC](#rumus-abc)

## Latihan 1
> file: `latihan_1.cpp`

### Deskripsi
Bantu Mbak Songhwa membuat program yang dapat menentukan apakah sebuah angka genap atau ganjil!

### Format Input
Sebuah bilangan bulat `A`

### Format Output
- Jika `A` genap, maka print "Genap"
- Jika `A` ganjil, maka print "Ganjil"

### Contoh
  
* Sample Input 1
  
  ```
  4
  ```

* Sample Output 1
  
  ```
  Genap
  ```
    
* Sample Input 2
  
  ```
  -11
  ```

* Sample Output 2
  
  ```
  Ganjil
  ```

## Latihan 2
> file: `latihan_2.cpp`

### Deskripsi
Bantu Mbak Xaviera membuat program untuk mencari angka terbesar dan terkecil dari 3 buah bilangan real yang dimasukkan!

### Format Input
3 buah bilangan bulat `P`, `Q`, dan `R`

### Format Output
Baris pertama merupakan nilai maksimum dari nilai `P`, `Q`, dan `R`  
Baris kedua merupakan nilai minimum dari nilai `P`, `Q`, dan `R`  

### Contoh
  
* Sample Input 1
  
  ```
  5
  4
  3
  ```

* Sample Output 1
  
  ```
  5
  3
  ```
  
* Sample Input 2
  
  ```
  -1
  -13
  -1
  ```

* Sample Output 2
  
  ```
  -1
  -13
  ```

## Latihan 3
> file: `latihan_3.cpp`

### Deskripsi

Mas Axel, seorang mahasiswa yang sedang KKN, ingin membuat alat bantu mengajar interaktif untuk pelajaran huruf vokal dan konsonan. Meskipun tidak berpengalaman dalam pemrograman, dia meminta bantuanmu, yang baru belajar C++. Mas Axel memintamu untuk membuat program sederhana yang bisa menentukan apakah sebuah huruf yang diinput (baik huruf kapital maupun kecil) adalah vokal atau konsonan. Kamu melihat ini sebagai kesempatan bagus untuk melatih kemampuanmu, namun masih sedikit bingung dengan beberapa sintaks C++. Bisakah kamu membuat program sesuai permintaan Mas Axel?

### Format Input
Sebuah karakter `C` yang merupakan huruf yang ingin diperiksa, huruf tersebut bisa berupa huruf kapital maupun huruf kecil

### Format Output
- Jika `C` adalah huruf vokal, maka print "Vokal"
- Jika `C` adalah huruf konsonan, maka print "Konsonan"

### Contoh
  
* Sample Input 1

  
  ```
  A
  ```

* Sample Output 1

  
  ```
  Vokal
  ```
    
* Sample Input 2

  
  ```
  z
  ```

* Sample Output 2

  
  ```
  Konsonan
  ```

## Nilai Mutu Terbaru
> file: `tugas_1.cpp`

### Deskripsi
Setelah dirilisnya Surat Edaran Rektor Nomor 2291/UN6.WR1/HK.01/2024 pada 20 Maret lalu, khusus untuk mahasiswa Unpad angkatan 2024 dan seterusnya berlaku perubahan pada sistem penilaian mutu. Berikut adalah tabel perubahan nilai mutu yang berlaku mulai semester ini:
| Huruf Mutu | Angka Mutu | Kisaran Nilai Akhir | Kategori        |
|------------|------------|---------------------|-----------------|
| A          | 4          | 91-100              | Sangat Istimewa |
| A-         | 3,66       | 80-90               | Istimewa        |
| B+         | 3,33       | 76-79               | Sangat Baik     |
| B          | 3          | 72-75               | Baik            |
| B-         | 2,66       | 68-71               | Cukup Baik      |
| C+         | 2,33       | 61-67               | Cukup           |
| C          | 2          | 56-60               | Kurang Cukup    |
| D          | 1          | 45-55               | Kurang          |
| E          | 0          | 0-44                | Sangat Kurang   |

Mas Kendrick adalah seorang mahasiswa Unpad angkatan 2024 yang ingin mengetahui IPK terbaru yang ia dapatkan. Bantu Mas Kendrick dalam menghitung nilai mutu yang ia dapatkan berdasarkan nilai akhir mata kuliah! Jika Mas Kendrick mendapatkan nilai akhir kurang dari C, maka print "Anda tidak lulus mata kuliah ini"


### Format Input
Sebuah bilangan real `A` yang merupakan nilai akhir dari suatu mata kuliah

### Format Output
Angka mutu yang diperoleh oleh Mas Kendrick dan tambahan keterangan apabila Mas Kendrick tidak lulus mata kuliah tersebut

### Contoh
  
* Sample Input 1
  
  ```
  42.12
  ```

* Sample Output 1
  
  ```
  E
  Anda tidak lulus mata kuliah ini
  ```
    
* Sample Input 2
  
  ```
  81.23
  ```

* Sample Output 2
  
  ```
  A-
  ```

## Manhattan Distance
> file: `tugas_2.cpp`

### Deskripsi
Manhattan distance adalah pengukuran antara dua titik dalam sistem koordinat Kartesius. Pengukuran ini dilakukan dengan menjumlahkan perubahan absolut pada sumbu x dan y, tanpa melakukan perjalanan diagonal. Konsep ini dapat dianalogikan dengan rute yang ditempuh oleh kendaraan di jalan-jalan kota yang tersusun dalam pola grid. Secara matematis, Manhattan distance dinyatakan sebagai penjumlahan dari nilai absolut perbedaan koordinat $x$ dan perbedaan koordinat $y$, yang dapat dirumuskan sebagai $|x_1 - x_2| + |y_1 - y_2|$.   

Berikut adalah visualisasinya:  

<img src="img/manhattan.png" alt="manhattan" width=400>

### Format Input
Empat buah bilangan bulat $x_1$, $y_1$, $x_2$, dan $y_2$ yang menyatakan koordinat dua titik secara berurutan

### Format Output
Manhattan distance dari dua titik tersebut

### Catatan
**Tidak boleh menggunakan fungsi bawaan absolut**

### Contoh
  
* Sample Input 1
  
  ```
  0 0 5 5
  ```

* Sample Output 1
  
  ```
  10
  ```
    
* Sample Input 2
  
  ```
  -1 -1 1 1
  ```

* Sample Output 2
  
  ```
  4
  ```

## Segitiga Apa?
> file: `tugas_3.cpp`

### Deskripsi
Bantu Mas Umemiya untuk menentukan jenis segitiga berdasarkan panjang sisi-sisinya! Segitiga dapat diklasifikasikan menjadi segitiga sama sisi, segitiga sama kaki, segitiga sembarang, atau bukan segitiga. Segitiga sama sisi memiliki panjang sisi yang sama, segitiga sama kaki memiliki dua sisi yang sama panjang, dan segitiga sembarang memiliki panjang sisi yang berbeda-beda. Sebuah segitiga dikatakan bukan segitiga jika panjang sisi yang terpendek tidak memenuhi syarat segitiga, yaitu panjang sisi terpendek lebih kecil dari jumlah panjang sisi lainnya.

<img src="img/image.png" alt="triangle" width=400>

### Format Input
Tiga buah bilangan real $A$, $B$, dan $C$ yang menyatakan panjang sisi segitiga

### Format Output
Jenis segitiga yang diperoleh dari panjang sisi segitiga tersebut:
- Jika segitiga sama sisi, print "Segitiga Sama Sisi"
- Jika segitiga sama kaki, print "Segitiga Sama Kaki"
- Jika segitiga sembarang, print "Segitiga Sembarang"
- Jika bukan segitiga, print "Bukan Segitiga" 

### Contoh
  
* Sample Input 1
  
  ```
  9
  40
  41
  ```

* Sample Output 1
  
  ```
  Segitiga Sembarang
  ```
  
* Sample Input 2
  
  ```
  14
  14
  21 
  ```

* Sample Output 2
  
  ```
  Segitiga Sama Kaki
  ```

## Rumus ABC
> file: `tugas_4_freeform.cpp`

### Deskripsi
Buatlah program yang dapat mencari akar-akar persamaan kuadrat $ax^2 + bx + c = 0$.  

Rumus:  
$D = b^2 - 4ac$  
$x_1, x_2 = \frac{-b \pm \sqrt{D}}{2a}$


### Format Input dan Output
> Tidak ada format input dan output pada tugas yang bersifat *freeform*. Selama program kamu melakukan yang diinstruksikan, **kreasikan sebebasmu!** 
