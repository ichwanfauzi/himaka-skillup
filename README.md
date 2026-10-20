# KasirKu — Aplikasi Kasir dan Stok Sederhana

## Informasi Proyek
- **Mata kuliah:** Pemrograman Berbasis Web (PBW)
- **Tahap:** Milestone 1 — Perencanaan Proyek dan Persiapan Lingkungan Kerja
- **Nama/anggota:** [Isi nama anggota]
- **Program studi/kelas:** [Isi program studi dan kelas]

## 1. Deskripsi Singkat
KasirKu adalah rancangan aplikasi web sederhana untuk membantu toko kecil mencatat produk, memantau persediaan, dan merencanakan pencatatan transaksi penjualan dalam satu tempat.

Pada Milestone 1, pekerjaan dibatasi pada perencanaan kebutuhan, penentuan pengguna dan fitur, wireframe, serta persiapan repository. Implementasi fitur aplikasi belum dikerjakan pada tahap ini.

## 2. Latar Belakang Masalah
Pada usaha kecil, pencatatan produk, jumlah stok, dan penjualan dapat dilakukan secara manual menggunakan buku atau lembar kerja terpisah. Cara tersebut berpotensi membuat data sulit dicari, jumlah stok terlambat diperbarui, dan rekap penjualan membutuhkan waktu lebih lama. Karena itu, diperlukan rancangan aplikasi web sederhana yang dapat membantu pengelolaan data produk dan pencatatan penjualan secara lebih teratur.

## 3. Tujuan
1. Merancang aplikasi web untuk membantu pengelolaan produk dan stok.
2. Merencanakan alur pencatatan transaksi penjualan.
3. Menentukan halaman dan kebutuhan fitur utama sebelum implementasi.
4. Menyiapkan repository sebagai tempat penyimpanan perkembangan proyek.

## 4. Target Pengguna
- **Admin/kasir:** pengguna utama yang direncanakan mengelola produk, kategori, stok, dan pencatatan penjualan.
- **Pemilik usaha (opsional):** pengguna yang direncanakan melihat ringkasan stok dan penjualan.

## 5. Kebutuhan dan Fitur yang Direncanakan
Fitur berikut merupakan rencana kebutuhan, bukan fitur yang sudah diimplementasikan:
1. Login dan logout pengguna.
2. Dashboard ringkasan produk, stok, transaksi, dan penjualan.
3. Pengelolaan kategori produk.
4. Pengelolaan data produk dan stok.
5. Pencatatan transaksi penjualan beserta detail produk, jumlah, harga, dan subtotal.
6. Pengurangan stok setelah transaksi disimpan.
7. Pencarian atau filter data.
8. Pagination pada daftar data.
9. Tampilan tanggal dan waktu.
10. Konfirmasi sebelum penghapusan data.

## 6. Rancangan Halaman
Wireframe awal mencakup:
- Halaman login.
- Halaman dashboard.
- Halaman daftar produk.
- Formulir tambah/edit produk.

Lihat `docs/wireframe.md`.

## 7. Teknologi yang Direncanakan
Mengikuti panduan PjBL PBW:
- HTML5
- CSS3
- JavaScript
- PHP native
- MySQL atau MariaDB
- jQuery dan AJAX
- Git dan GitHub/GitLab
- Hosting untuk tahap publikasi akhir

Teknologi tersebut baru dicatat sebagai rencana pada Milestone 1.

## 8. Struktur Repository Awal
```text
KasirKu/
├── docs/
│   ├── proposal.md
│   └── wireframe.md
├── assets/
│   └── .gitkeep
├── .gitignore
└── README.md
```

Struktur ini sengaja dibuat sederhana untuk tahap perencanaan. Folder dan file implementasi dapat ditambahkan pada milestone berikutnya sesuai arahan dosen.

## 9. Rencana Commit Git
Lakukan commit secara bertahap dengan pesan yang menjelaskan perubahan:
1. `docs: add project README and initial description`
2. `docs: add project proposal and user requirements`
3. `docs: add initial page wireframes`

Sesuaikan isi setiap commit dengan file yang benar-benar ditambahkan. Jangan membuat commit palsu atau mengklaim perubahan yang belum dilakukan.

## 10. Batasan Milestone 1
Pekerjaan pada tahap ini hanya meliputi perencanaan proyek, target pengguna, kebutuhan fitur, wireframe, repository Git, struktur folder awal, dan dokumentasi awal. Login PHP, koneksi database, CRUD, transaksi yang berfungsi, pagination AJAX, dan deployment belum dikerjakan.

## 11. Status
- [ ] Proposal/README diperiksa dan dilengkapi identitas anggota.
- [ ] Wireframe diperiksa.
- [ ] Repository Git dibuat.
- [ ] Minimal tiga commit bermakna dibuat.
