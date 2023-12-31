# Bookshelf API menggunakan Hapi.js

Repositori ini berisi proyek Bookshelf API yang dibuat sebagai bagian dari penilaian Dicoding. API ini dikembangkan menggunakan Hapi.js, sebuah kerangka kerja JavaScript yang kuat dan fleksibel untuk membangun aplikasi web dan API.

## Fitur

- Operasi CRUD: Buat, Baca, Perbarui, dan Hapus buku dari rak buku.
- Validasi data: Data masukan divalidasi untuk memastikan konsistensi dan akurasi.
- Penanganan kesalahan: Penanganan kesalahan menyeluruh untuk memberikan respons bermakna kepada klien.
- Dokumentasi API: Endpoint API yang didokumentasikan dengan baik untuk integrasi dan pemahaman yang mudah.

## Persyaratan

- Node.js: Pastikan Anda telah menginstal Node.js di sistem Anda.
- npm: Node Package Manager diperlukan untuk menginstal dependensi yang diperlukan.

## Instalasi

1. Clone repositori ini ke mesin lokal Anda.
2. Buka direktori proyek di terminal.
3. Jalankan `npm install` untuk menginstal semua dependensi yang diperlukan.

## Penggunaan

1. Jalankan server: Jalankan `npm start` di terminal untuk memulai server API.
2. Server akan berjalan di `http://localhost:9000` secara default. Anda dapat mengubah port di file konfigurasi.
3. Akses dokumentasi API di `/documentation` untuk mengeksplorasi endpoint yang tersedia dan penggunaannya.

## Endpoint

- `GET /books`: Dapatkan semua buku di rak buku.
- `GET /books/{bookId}`: Dapatkan buku tertentu berdasarkan ID-nya.
- `POST /books`: Tambahkan buku baru ke rak buku.
- `PUT /books/{bookId}`: Perbarui informasi buku yang sudah ada.
- `DELETE /books/{bookId}`: Hapus buku dari rak buku.

## Format Data

API ini menerima dan mengembalikan data dalam format JSON.

## Lisensi

Proyek ini dilisensikan di bawah Lisensi MIT. Anda bebas menggunakan, memodifikasi, dan mendistribusikannya sesuai dengan ketentuan lisensi.

Terima kasih kepada Dicoding atas kesempatan untuk belajar dan mendemonstrasikan kemampuan saya melalui penilaian ini.

---
Jangan ragu untuk menghubungi saya jika Anda memiliki pertanyaan atau masukan tentang API ini. Selamat coding! 🚀
