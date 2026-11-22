# Kendaraanku

Aplikasi mobile sewa mobil dan motor untuk wisatawan di Yogyakarta. Dibuat dengan Kotlin dan Jetpack Compose sebagai project akhir mata kuliah Pengembangan Aplikasi Mobile 2026.

> Semua data kendaraan, harga, akun, pesanan, dan ulasan di aplikasi ini adalah **data contoh** untuk keperluan pengembangan.

## Identitas

| | |
|---|---|
| Nama | (Nabil Rafif) |
| NIM | (20240140062) |
| Kelas | (B) |

## Ringkasan

Wisatawan mencari mobil atau motor, memesan ke mitra rental, menyusun rencana perjalanan, dan memberi ulasan. Mitra rental mengelola kendaraan miliknya dan mengonfirmasi pesanan.

## Peran

| Peran | Hak akses |
|---|---|
| Wisatawan | Cari kendaraan, pesan, ulas, rencana perjalanan, pesan bantuan |
| Mitra rental | Kelola kendaraan sendiri, konfirmasi pesanan masuk |

## Teknologi (rencana, diperbarui seiring pengerjaan)

| Bagian | Teknologi |
|---|---|
| Aplikasi | Kotlin, Jetpack Compose, MVVM, Navigation Compose |
| Backend | Node.js (Express), JWT access token dan refresh token |
| Database | (postgresql) |
| File lokal | Penyimpanan internal (foto profil, voucher pesanan) |

## Status Fitur (diperbarui setiap minggu)

- [ ] Register dan login (JWT access token dan refresh token)
- [ ] Pembatasan hak akses berdasarkan peran
- [ ] Fitur 1: Kendaraan (Create, Read, Update, Delete, Search)
- [ ] Fitur 2: Pesanan (Create, Read, Update, Delete, Search)
- [ ] Fitur 3: Ulasan (Create, Read, Update, Delete, Search)
- [ ] Fitur 4: Rencana Perjalanan (Create, Read, Update, Delete, Search)
- [ ] Fitur 5: Pesan Bantuan (Create, Read, Update, Delete, Search)
- [ ] Simpan dan baca file lokal
- [ ] Validasi form dan state kosong, loading, error

## Persyaratan Pedoman

| Persyaratan | Status |
|---|---|
| Hanya Jetpack Compose | Direncanakan |
| Navigasi hanya Navigation Compose | Direncanakan |
| Arsitektur MVVM | Direncanakan |
| Minimal 4 entitas berelasi | Direncanakan (6 entitas) |
| Minimal 5 fitur CRUDS | Direncanakan |
| REST API dan parsing JSON | Direncanakan |
| Database bukan Room | Direncanakan |
| Minimal 30 commit | Berjalan |

## Progress Mingguan

| Minggu | Yang dikerjakan |
|---|---|
| 1 | Repository, README, struktur proyek |
| 2 | |
| 3 | |
| 4 | |
| 5 | |
| 6 | |

## Struktur Repository

```
.
├── android/    Aplikasi Android (Kotlin, Jetpack Compose)
├── backend/    REST API
├── docs/       SRS, ERD, catatan rancangan
└── README.md
```

## Cara Menjalankan

(Diisi setelah backend dan aplikasi dapat dijalankan.)

## Akun Demo

(Diisi setelah data awal tersedia.)

## Aset dan Lisensi

(Diisi: sumber dan lisensi ikon, font, dan gambar yang dipakai.)