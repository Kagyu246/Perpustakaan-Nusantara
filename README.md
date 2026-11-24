# Tugas Perpustakaan Nusantara

Kerangka awal proyek PHP Native dengan struktur MVC.

## Struktur

- `app/Controllers/` — menerima request dan mengatur alur aplikasi.
- `app/Models/` — aturan data dan akses database.
- `app/Views/` — halaman yang ditampilkan kepada pengguna.
- `config/` — konfigurasi aplikasi.
- `routes/` — pemetaan URL ke controller.
- `public/` — document root dan pintu masuk aplikasi.

## Menjalankan kerangka

Pastikan PHP tersedia, lalu jalankan dari folder proyek:

```sh
php -S localhost:8000 -t public
```

Buka `http://localhost:8000` di browser.

## Mulai berkolaborasi

Clone repository tim:

```sh
git clone https://github.com/Kagyu246/Perpustakaan-Nusantara.git
cd Perpustakaan-Nusantara
```

Kerjakan perubahan pada branch masing-masing, lalu ajukan pull request sebelum menggabungkannya ke branch `main`. Catat progres di [LOGBOOK.md](LOGBOOK.md).
