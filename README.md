# LAPORAN PRAKTIKUM 4

# CODE PROGRAM NILAI AKHIR

## Step 1 : Menginisialisasi List Data Mahasiswa
Program dimulai dengan menginisialisasi sebuah list kosong bernama data_mahasiswa untuk menyimpan data setiap mahasiswa. List ini akan diisi dengan data mahasiswa yang diinput selama program berjalan :

![gambar](https://github.com/M-Rakha/labpy04/blob/5bc67c21b283a6d3ab9c42633ffc508048d754a0/Cuplikan%20layar%202024-11-18%20191305.png)

## Step 2 : Input Data Mahasiswa dan Perulangan While
Program kemudian masuk ke dalam sebuah perulangan while yang memungkinkan pengguna untuk memasukkan data mahasiswa secara berulang hingga pengguna memilih untuk berhenti :

- Nama Mahasiswa: Program meminta input nama mahasiswa.
- Nim Mahasiswa: Program meminta input nim mahasiswa.
- Nilai Tugas: Program meminta input nilai tugas mahasiswa dalam bentuk integer.
- Nilai UTS: Program meminta input nilai UTS mahasiswa dalam bentuk integer.
- Nilai UAS: Program meminta input nilai UAS mahasiswa dalam bentuk integer.

![gambar](https://github.com/M-Rakha/labpy04/blob/20697f3f8d27fe6baafafe1a2daa420a0d1c7aad/Cuplikan%20layar%202024-11-18%20192138.png)

## Step 3 : Menghitung Nilai Akhir
Setelah menerima input nilai tugas, UTS, dan UAS, program menghitung nilai akhir mahasiswa dengan menggunakan formula berikut :

![gambar](https://github.com/M-Rakha/labpy04/blob/eac7487f5e5aa7dbae84399ea3b49e135afa3771/Cuplikan%20layar%202024-11-18%20192655.png)

Formula ini berarti:

- Nilai tugas memiliki bobot 30% dari nilai akhir.
- Nilai UTS memiliki bobot 35% dari nilai akhir.
- Nilai UAS memiliki bobot 35% dari nilai akhir.

## Step 4 : Simpan Data Mahasiswa
Setelah nilai akhir dihitung, program membuat dictionary untuk menyimpan semua informasi tentang mahasiswa (nama, nim, nilai tugas, nilai UTS, nilai UAS, dan nilai akhir). Dictionary ini kemudian ditambahkan ke dalam list data_mahasiswa :

![gambar](https://github.com/M-Rakha/labpy04/blob/38aa34b725a137d906b2832a268e2122519b00be/Cuplikan%20layar%202024-11-18%20192931.png)

## Step 5 : Code Seleksi Untuk Tanyakan Tambahan Data Mahasiswa
Setelah menyimpan data, program bertanya kepada pengguna apakah ingin menambah data mahasiswa lagi atau tidak. If pengguna mengetik y, program akan mengulangi proses input. Jika pengguna mengetik t, perulangan akan berhenti, berikan perintah break untuk menghentikan Program :

![gambar](https://github.com/M-Rakha/labpy04/blob/111482a75222a587dd2738abe253570e4fa1abe8/Cuplikan%20layar%202024-11-18%20193243.png)

## Step 6 : Print Data Mahasiswa
Setelah perulangan selesai (pengguna memilih t untuk berhenti menambah data), program akan menampilkan daftar data mahasiswa yang telah dimasukkan. Untuk setiap mahasiswa data yang ditampilkan meliputi nama, nim, nilai tugas, nilai UTS, nilai UAS, dan nilai akhir :

![gambar](https://github.com/M-Rakha/labpy04/blob/11db96ea547c700e8a53440b05e7cfeb8753473a/Cuplikan%20layar%202024-11-18%20193732.png)

## Step 7 : Beri Batas Bawah
Print '=' dikalikan 80 :

![gambar](https://github.com/M-Rakha/labpy04/blob/54c77f092dd321d95160cb0413330577e2f1c28e/Cuplikan%20layar%202024-11-18%20193958.png)

## Step 8 : Test Code Program
Jalankan code program dengan memasukan nama, nilai tugas, nilai uts, nilai uas :

- Nama : Muhammad Rakha Ghani
- Nim : 312410421
- Nilai Tugas : 90
- Nilai UTS : 55
- Nilai UAS : 80

![gambar](https://github.com/M-Rakha/labpy04/blob/00367eafa8fa0ea57b339981b0da31627ce8c530/Cuplikan%20layar%202024-11-18%20194417.png)

# FLOWCHART NILAI AKHIR

## Step 1 : Start
Titik Mulai :

![gambar](https://github.com/M-Rakha/labpy04/blob/3c83ace9890585615c94287bd5caee2694928400/16.png)

## Step 2 : Input Data Mahasiswa
Buatkan Input Data Mahasiswa dengan mencangkup Nama, Nim, Nilai Tugas, Nilai UTS, Nilai UAS :

![gambar](https://github.com/M-Rakha/labpy04/blob/940e0982e2efed24b4817c76aa172bd4a5101f77/17.png)

## Step 3 : Lakukan Seleksi
Langkah selanjutnya yaitu buatkan decision atau seleksi berupa pertanyaan Menambahkan Data Mahasiswa (Y/T?), jika Ya maka kemabli ke Input Data mahasiswa, jika Tidak maka lanjut ke langkah selanjutnya :

![gambar](https://github.com/M-Rakha/labpy04/blob/6a0c9a87454a69adc3c684bd5b86ba9741e6d37e/22.png)

## Step 4 : Proses Perhitungan
Langkah ini untuk memproses Nilai Akhir dari Input nilai nilai yang telah dimasukan :

![gambar](https://github.com/M-Rakha/labpy04/blob/1423c610daf2a4cbdd774dd26190b1bf139660a1/23.png)

## Step 5 : Output Nilai Akhir
Masuk kelangkah Akhir yaitu menampilkan Nilai Akhir dari Data Mahasiswa yang telah diinputkan dan sudah dihitung :

![gambar](https://github.com/M-Rakha/labpy04/blob/bb8bf68c483294c4fa79c27fa91c1072a675aac6/24.png)

## Step 6 : End
Titik Berhenti :

![gambar](https://github.com/M-Rakha/labpy04/blob/ca1970ffa3eabf1bc554a1ff4035560cead5c8cd/25.png)

# KESIMPULAN
Kesimpulan dari Laporan Praktikum di atas adalah penggunaan append dapat menambahkan element lain, jika kita perhatikan penggunaan perulangan sangat membantu untuk memastikan jika ada tambahan data yang diinputkan, namun dari semua itu semua adalah kelas dari sebuah List dari tema praktikum kali ini. Penggunaan List berguna untuk mengetahui apa saja yang ada di dalam data, List mampu menampung beberapa element berbeda.

