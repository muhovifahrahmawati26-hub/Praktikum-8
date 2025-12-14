<!-- BOOTSTRAP ICONS -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">

<h1 align="center">
  <i class="bi bi-journal-code"></i> Praktikum 8 - Exception Handling Python
  <br>
<hr>
  
## 📌 LATIHAN 1 - Kalkulator Aman
### 🖇 Tujuan
Tujuan latihan ini adalah membuat program kalkulator sederhana yang mampu menangani tiga jenis kesalahan: input bukan angka (ValueError), pembagian dengan nol (ZeroDivisionError), dan operator yang tidak dikenal (raise Exception).
### 📖 Penjelasan Program
Konsep yang Diterapkan:

1. ```try-except ValueError```: Untuk menangani kasus di mana pengguna memasukkan teks atau karakter yang tidak bisa diubah menjadi angka (misalnya, pengguna mengetik "lima" bukan 5).

2. ```try-except ZeroDivisionError```: Untuk menangani kasus pembagian yang tidak valid secara matematis, yaitu pembagian dengan angka nol.

3. ```raise Exception```: Untuk membuat kesalahan kustom (custom error) ketika pengguna memasukkan operator yang tidak didukung oleh kalkulator (misalnya, ^), sehingga program dapat memberikan pesan kesalahan yang spesifik dan mudah dipahami.

Program ini menunjukkan prinsip EAFP (Easier to Ask for Forgiveness than Permission) di mana kode dicoba jalankan, dan jika gagal, program "meminta maaf" melalui blok except.
### 🎯 Hasil Akhir
<img width="625" height="372" alt="output kalkulator aman" src="https://github.com/user-attachments/assets/70cf3e58-c0a1-4be2-91ab-05fb68f9dfbe" />

## 📌 LATIHAN 2 - Validasi Daftar Nilai
### 🖇 Tujuan
Tujuan latihan ini adalah menghitung rata-rata nilai dari sebuah list yang bercampur antara angka dan string (nilai = [80, 90, 'A', 70, 100, 'B']). Program harus menggunakan try-except di dalam loop untuk melewati data yang bukan angka tanpa menghentikan program.
### 📖 Penjelasan Program
Konsep yang Diterapkan:

1. Iterasi (```for loop```): Program harus memproses setiap elemen dalam list secara berurutan.

2. ```try-except``` dalam Loop: Setiap item di dalam list dicoba untuk diubah menjadi angka (dengan ```float()``` atau ```int()```).

3. Penanganan ```ValueError```: Jika item berupa string ('A', 'B'), konversi akan gagal dan memicu ```ValueError```. Blok ```except``` akan menangkap error ini, mencatat item sebagai tidak valid, dan kemudian program melanjutkan ke item berikutnya di dalam list tanpa crash.

Hasil akhirnya adalah perhitungan rata-rata yang akurat, hanya menggunakan data nilai yang valid (berupa angka).
### 🎯 Hasil Akhir
<img width="602" height="229" alt="output validasi daftar nilai" src="https://github.com/user-attachments/assets/9a598462-b235-4826-a448-1eaeef7de8ff" />
<div align="center">
  
### 🎉 *Selesai — Terima kasih!*

</div>

