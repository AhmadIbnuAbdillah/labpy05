# labpy05
Nama : Ahmad Ibnu Abdillah

NIM : 312410489

Kelas : TI.24.A.5

# Kode Program

![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/bccc1f9540e9cee619bcbe966186f6db6ddb9f95/Screenshot%202024-11-26%20183909.png)
![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/bccc1f9540e9cee619bcbe966186f6db6ddb9f95/Screenshot%202024-11-26%20183930.png)

# Penjelasan Kode

1. Kelas Student

Kelas ini digunakan untuk merepresentasikan data seorang mahasiswa dengan atribut:

nim: Nomor Induk Mahasiswa

nama: Nama mahasiswa

tugas: Nilai tugas

uts: Nilai Ujian Tengah Semester

uas: Nilai Ujian Akhir Semester

akhir: Nilai akhir yang dihitung berdasarkan bobot nilai tugas, UTS, dan UAS.
Metode:


__init__: Konstruktor untuk menginisialisasi objek Student.

calculate_final_grade: Metode untuk menghitung nilai akhir berdasarkan formula:


Nilai Akhir=(tugas×0.3)+(uts×0.35)+(uas×0.35)

2. Fungsi Pendukung

display_menu


Menampilkan menu pilihan kepada pengguna.

display_students


Menampilkan daftar mahasiswa dalam format tabel. Jika tidak ada data, akan mencetak "TIDAK ADA DATA".

find_student_index


Mencari indeks mahasiswa berdasarkan nim di dalam daftar mahasiswa. Mengembalikan None jika mahasiswa tidak ditemukan.

3. Fungsi main

Merupakan fungsi utama yang mengatur alur program. Fungsi ini mencakup:

Menambahkan Mahasiswa (t)


Memasukkan data baru mahasiswa (NIM, Nama, Tugas, UTS, UAS) ke dalam daftar.

Melihat Data Mahasiswa (l)


Menampilkan semua data mahasiswa dalam format tabel.

Mengubah Data Mahasiswa (u)


Mengubah data mahasiswa berdasarkan nim. Jika ditemukan, data akan diubah dengan data baru.

Menghapus Data Mahasiswa (h)


Menghapus data mahasiswa dari daftar berdasarkan nim.

Mencari Mahasiswa (c)


Mencari data mahasiswa berdasarkan nim dan menampilkan data jika ditemukan.

Keluar Program (k)


Mengakhiri program.

# Hasil Progam ketika dijalankan

![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/83e69e351fdc2eb1b828f7db2227d746a5a4737a/Screenshot%202024-11-26%20183728.png)
![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/83e69e351fdc2eb1b828f7db2227d746a5a4737a/Screenshot%202024-11-26%20183750.png)

# Flowchart

![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/59ed3c3bef59d01de7e76b4264ca103a8b9de552/ss5.png)
![Foto](https://github.com/AhmadIbnuAbdillah/Foto/blob/59ed3c3bef59d01de7e76b4264ca103a8b9de552/ss6.png)
