# Praktikum Pemrograman Asynchronous
Nama: Syifa Kharisma Nayla
NIM: 362358302019
Kelas: 2B TRPL

# Praktikum 1: Mengunduh Data dari Web Service (API)
(W11: Soal 4)
- Mencari judul buku favorite di google books, lalu ganti ID buku pada variabel path di kode tersebut. Dan kemudian akses di browser URI tersebut dengan lengkap.
Hasil:
![alt text](image.png)

- Tambah kode di ElevatedButton, lalu lakukan run aplikasi Flutter. Hasilnya seperti gambar di bawah ini.
Hasil:
![alt text](image-1.png)
- Substring adalah metode atau fungsi dalam banyak bahasa pemrograman yang digunakan untuk mengambil bagian tertentu dari sebuah string (sub-bagian string). Fungsi ini biasanya menerima parameter awal (index) dan akhir (opsional) untuk menentukan bagian string yang ingin diambil.
- catchError biasanya merujuk pada mekanisme penanganan error (kesalahan) dalam bahasa pemrograman.

#  Praktikum 2: Menggunakan await/async untuk menghindari callbacks
(W11: Soal 4)
![alt text](image-2.png)
Langkah 1 :
Kode tersebut mensimulasikan operasi yang membutuhkan waktu tertentu dengan penundaan menggunakan Future.delayed. Hal ini berguna dalam mengelola proses asinkron dalam aplikasi.

Langkah 2 : 
Kode tersebut adalah fungsi asinkron dalam bahasa Dart yang menghitung total nilai yang diperoleh dari tiga fungsi returnOneAsync, returnTwoAsync, dan returnThreeAsync. Fungsi ini juga memperbarui tampilan (UI) dengan memanfaatkan setState untuk mengubah nilai variabel result.

# Praktikum 3: Menggunakan Completer di Future 
(W11: Soal 5)
![alt text](image-3.png)
Kode pada langkah 2 bertujuan untuk membuat Future secara manual menggunakan Completer. Menunda hasil dengan menunggu selama 5 detik. Dan menyelesaikan Future dengan nilai 42 menggunakan completer.complete.