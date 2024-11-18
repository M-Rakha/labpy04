# LAPORAN PRAKTIKUM 4

# CODE PROGRAM NILAI AKHIR

## Step 1 : Menginisialisasi List Data Mahassiswa
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







