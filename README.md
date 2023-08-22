# Pengembangan Aplikasi Bookshelf API yang Kuat dan Efisien


## Masalah
Dalam mengembangkan aplikasi Bookshelf API, kami dihadapkan pada beberapa tantangan, termasuk pengelolaan port, menjalankan aplikasi dengan perintah npm, serta implementasi fitur-fitur utama seperti penyimpanan, pengambilan, pembaruan, dan penghapusan buku.

## Solusi
- Pengelolaan Port dan Perintah:
> Menyusun aplikasi yang berjalan pada port 9000 dan menjalankan aplikasi dengan perintah npm run start.

- Penyimpanan Buku:
 > Membuat endpoint POST /books untuk menyimpan buku dengan validasi dan respons sesuai kriteria. Menggunakan nanoid untuk membuat id unik, dan menghitung finished berdasarkan observasi pageCount === readPage.

 - Pengambilan Daftar Buku:
 > Implementasi endpoint GET /books untuk mengambil seluruh daftar buku dengan respons yang relevan. Jika belum ada buku, respons akan berisi array buku kosong.

 - Detail Buku:
 > Menyediakan endpoint GET /books/{bookId} untuk menampilkan detail buku berdasarkan id. Respon sesuai dengan konten buku yang ditemukan atau pesan "Buku tidak ditemukan" jika id tidak ada.

 - Pembaruan Data Buku:
 > Menerapkan endpoint PUT /books/{bookId} untuk memperbarui data buku berdasarkan id. Validasi data dan respons yang akurat diberikan sesuai dengan kriteria.

 - Penghapusan Buku:
 > Mengimplementasikan endpoint DELETE /books/{bookId} untuk menghapus buku berdasarkan id. Respon sesuai dengan hasil penghapusan atau pesan "Buku gagal dihapus" jika id tidak ditemukan.

Dengan solusi ini, kami akan berhasil mengembangkan aplikasi Bookshelf API yang memenuhi kriteria ketat dan memberikan fungsionalitas yang unggul dalam manajemen koleksi buku.


## Arsitektur Cloud

## Dokumentasi Deploy Aplikasi
### User Interface
![UI](https://github.com/mzfuadi97/CloudArch-Sub1/assets/70827786/9edfb769-7b7e-4e8e-b9ac-522246aafe9c)



