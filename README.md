# Praktikum Pemrograman Web Dasar — Minggu 10

Proyek ini mengikuti instruksi Praktikum Minggu 10 pada Modul Praktikum PWD Minggu 9–12.

Nama ; Diyandra Jagadditha
Nim : A12.2025.07407

## Isi folder
- `index.php` — formulir Buku Tamu Kampus yang memuat input nama, email, dan pesan.
- `style.css` — pengaturan tata letak agar formulir tampil responsif.
- `latihan.php` — kode latihan dasar variabel, echo, dan kondisi if.
- `proses.php` — halaman tujuan awal sesuai capaian Minggu 10 (belum memproses kiriman data POST).
- `cek-lingkungan.php` — skrip untuk mengecek versi PHP serta status ekstensi `mbstring`.

## Praktik subbab 10.2
Lakukan satu perubahan setiap percobaan pada `latihan.php`, simpan, lalu muat ulang browser.

| Uji | Perubahan | Hasil yang diharapkan |
|---|---|---|
| W10-01 | `$jumlah = 1;` dan `$status = "aktif";` | Jumlah pesan: 1; Form siap |
| W10-02 | Ubah `$jumlah = 3;` | Jumlah pesan: 3; Form siap |
| W10-03 | Dengan jumlah 3, ubah `$status = "tutup";` | Jumlah pesan: 3; Form ditutup |

Setelah seluruh uji selesai, kembalikan nilai awal ke $jumlah = 1; dan $status = "aktif";. Untuk latihan membaca pesan error sintaks, hapus sementara satu tanda titik koma (;), perhatikan pesan kesalahannya, lalu pasang kembali sebelum menyimpan versi final.

## Pemeriksaan hasil
- Form menampilkan kolom Nama, Email, Pesan, dan tombol Kirim.
- Kolom wajib diisi dan format email diperiksa oleh browser.
- `latihan.php` menampilkan nilai variabel dan cabang `if` yang sesuai.
- Form mengarah ke `proses.php`; halaman tersebut hanya menunjukkan bahwa alamat penerima terbuka.
- `cek-lingkungan.php` menampilkan versi PHP dan status `mbstring`.

