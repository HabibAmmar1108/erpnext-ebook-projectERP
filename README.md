# Buku Interaktif ERPNext dengan Docker

Panduan praktikum **ERPNext untuk Sistem Informasi Akuntansi** menggunakan Docker. Ebook ini disusun untuk membantu mahasiswa mengikuti alur praktik dari menyiapkan lingkungan ERPNext, memasukkan data dasar, mencatat transaksi, hingga memeriksa laporan dan membuat backup.

## 📘 Ebook

Buka atau unduh file PDF:

**[Buku Interaktif ERPNext dengan Docker](Buku_Interaktif_ERPNext_Docker.pdf)**

Ebook memiliki daftar isi interaktif, tautan referensi, checklist, dan kolom refleksi. Gunakan aplikasi pembaca PDF yang mendukung tautan dan formulir agar fitur interaktif dapat digunakan dengan baik.

## 🎯 Tujuan Pembelajaran

Setelah mengikuti panduan ini, pembaca diharapkan dapat:

- Menjalankan dan menghentikan layanan ERPNext lokal menggunakan Docker.
- Menyiapkan Company, tahun fiskal, Chart of Accounts (COA), gudang, barang, pemasok, dan pelanggan.
- Menelusuri hubungan dokumen pembelian, produksi, penjualan, dan pembayaran.
- Memeriksa jurnal, persediaan, laba, dan posisi keuangan.
- Menyimpan bukti praktikum dan membuat backup di luar volume Docker.

## 🧭 Isi Ebook

1. Persiapan awal
2. Menjalankan ERPNext pada `localhost`
3. Mengatur Company dan tahun fiskal
4. Mengimpor serta memeriksa Chart of Accounts
5. Menyiapkan master data dan saldo awal
6. Mencatat transaksi pembelian, produksi, penjualan, dan pembayaran
7. Memverifikasi laporan dan merekonsiliasi hasil
8. Mengekspor laporan serta membuat backup
9. Membuka kembali pekerjaan praktikum
10. Menghentikan layanan dengan aman
11. Troubleshooting
12. Penutup dan evaluasi

Ebook juga memuat referensi dan lampiran visual untuk layar **Data Import** dan **Work Order**.

## 🛠️ Kebutuhan

- Docker Desktop
- Git
- Browser
- Repositori dan konfigurasi [Frappe Docker](https://github.com/frappe/frappe_docker)
- Pembaca PDF yang mendukung tautan dan formulir interaktif

Panduan menggunakan konfigurasi demo `pwd.yml` dan mengakses ERPNext melalui `http://localhost:8080`. Nama layanan, tampilan menu, serta langkah teknis dapat berbeda menurut versi dan konfigurasi yang digunakan.

## 🚀 Cara Menggunakan

1. Unduh atau clone repositori ini.
2. Buka file `Buku_Interaktif_ERPNext_Docker.pdf`.
3. Ikuti bab secara berurutan karena data dan dokumen pada setiap tahap saling berkaitan.
4. Siapkan lingkungan ERPNext sesuai petunjuk ebook.
5. Kerjakan transaksi pada sistem praktikum sendiri, lalu verifikasi hasilnya melalui laporan dan buku besar.
6. Isi checklist/refleksi jika diperlukan dan simpan PDF yang telah diisi dengan nama file baru.
7. Simpan bukti transaksi, ekspor laporan, dan backup di lokasi terpisah dari volume Docker.

Jika repositori ini hanya berisi ebook, konfigurasi ERPNext, dataset COA, dan data transaksi **tidak otomatis disertakan** kecuali ditambahkan sebagai file terpisah.

## 🧾 Ringkasan Studi Kasus

Ebook menggunakan studi kasus simulasi **PT Industri Maju Bersama (IMB)** dengan mata uang IDR dan tahun fiskal 2026. Alur praktik mencakup pembelian bahan baku, produksi meja, penjualan, dan penerimaan pembayaran.

Angka kontrol yang digunakan dalam simulasi:

| Komponen | Nilai kontrol |
|---|---:|
| Persediaan akhir | Rp15.750.000 |
| Laba simulasi | Rp1.250.000 |
| Total aset | Rp20.730.000 |
| Total kewajiban dan ekuitas | Rp20.730.000 |

Angka tersebut adalah **hasil simulasi berdasarkan asumsi yang dijelaskan di dalam ebook**, bukan hasil pengujian pada setiap instalasi ERPNext. Hasil aktual dapat berbeda sesuai konfigurasi akun, metode valuasi, versi, dan transaksi yang dimasukkan.

## ⚠️ Catatan Penting

- Panduan ini ditujukan untuk **pembelajaran/praktikum**, bukan petunjuk implementasi ERPNext untuk produksi bisnis.
- Tarif pajak 11% dipertahankan sebagai parameter soal, bukan pernyataan mengenai tarif pajak yang berlaku saat ini.
- Sebelum mengubah COA atau data yang sudah memiliki transaksi, buat backup dan periksa dampaknya.
- Jangan gunakan `docker compose down -v` atau menghapus volume jika data praktikum masih diperlukan; tindakan tersebut dapat menghapus data.
- Kredensial demo hanya berlaku jika konfigurasi masih menggunakan kredensial tersebut. Ganti atau gunakan kredensial yang berlaku pada instalasi masing-masing.
- Nama tombol dan tampilan dapat berubah antarversi ERPNext/Frappe.
- Lakukan verifikasi pada General Ledger, Trial Balance, Stock Ledger, dan laporan terkait. Angka kontrol pada ebook tidak menggantikan pemeriksaan transaksi aktual.

## 📚 Referensi

- [Frappe Docker — repositori resmi](https://github.com/frappe/frappe_docker)
- [Dokumentasi Frappe — Data Import](https://docs.frappe.io/framework/user/en/guides/data-management/data-import)
- [Dokumentasi ERPNext](https://docs.frappe.io/erpnext)
- [Dokumentasi Docker](https://docs.docker.com/)

Referensi dan catatan penyusunan lebih lengkap tercantum pada bagian akhir ebook.

## 🎓 Penggunaan Akademik

Gunakan ebook ini sebagai panduan belajar. Untuk pengumpulan tugas atau penilaian, lampirkan bukti dari hasil praktik sendiri dan pastikan setiap transaksi serta laporan telah diverifikasi.

---

**Format:** PDF interaktif  
**Topik:** ERPNext · Docker · Sistem Informasi Akuntansi · Praktikum Akuntansi
