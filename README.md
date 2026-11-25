# Praktikum Pemrograman Web Dasar — Minggu 10

Proyek ini mengikuti instruksi Praktikum Minggu 10 pada Modul Praktikum PWD Minggu 9–12.

Nama ; Diyandra Jagadditha
Nim : A12.2025.07407

## Isi folder
- `index.php` — form Buku Tamu Kampus dengan input nama, email, dan pesan.
- `style.css` — tampilan form responsif.
- `latihan.php` — latihan variabel, `echo`, dan percabangan `if`.
- `proses.php` — halaman tujuan sementara sesuai target Minggu 10; belum membaca data POST.
- `cek-lingkungan.php` — pemeriksa versi PHP dan ketersediaan ekstensi `mbstring`.

## Cara menjalankan dengan XAMPP
1. Salin folder `minggu10` ke `C:\xampp\htdocs\`.
2. Buka XAMPP Control Panel, lalu klik **Start** pada Apache. MySQL tidak diperlukan.
3. Buka `http://localhost/minggu10/index.php`.
4. Buka latihan PHP di `http://localhost/minggu10/latihan.php`.
5. Buka pemeriksa lingkungan di `http://localhost/minggu10/cek-lingkungan.php`.

Jika Apache menggunakan port selain 80, sesuaikan URL, misalnya `http://localhost:8080/minggu10/index.php`.

## Praktik subbab 10.2
Lakukan satu perubahan setiap percobaan pada `latihan.php`, simpan, lalu muat ulang browser.

| Uji | Perubahan | Hasil yang diharapkan |
|---|---|---|
| W10-01 | `$jumlah = 1;` dan `$status = "aktif";` | Jumlah pesan: 1; Form siap |
| W10-02 | Ubah `$jumlah = 3;` | Jumlah pesan: 3; Form siap |
| W10-03 | Dengan jumlah 3, ubah `$status = "tutup";` | Jumlah pesan: 3; Form ditutup |

Setelah pengujian, kembalikan nilai menjadi `$jumlah = 1;` dan `$status = "aktif";`.
Untuk diagnosis sintaks, modul meminta menghapus sementara satu titik koma, mengamati error, lalu memulihkan titik koma. Jangan menyimpan kode rusak sebagai hasil akhir.

## Pemeriksaan hasil
- Form menampilkan kolom Nama, Email, Pesan, dan tombol Kirim.
- Kolom wajib diisi dan format email diperiksa oleh browser.
- `latihan.php` menampilkan nilai variabel dan cabang `if` yang sesuai.
- Form mengarah ke `proses.php`; halaman tersebut hanya menunjukkan bahwa alamat penerima terbuka.
- `cek-lingkungan.php` menampilkan versi PHP dan status `mbstring`.

