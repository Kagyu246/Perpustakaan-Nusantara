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

## Kolaborasi GitHub

Setelah repository tim dibuat di GitHub, sambungkan dengan:

```sh
git remote add origin <URL-repository-tim>
git branch -M main
git push -u origin main
```

Gunakan branch untuk pekerjaan masing-masing dan ajukan pull request sebelum menggabungkan perubahan ke branch utama.

## Logbook

| Tanggal | Pekerjaan | Hasil/bukti | Kendala |
| --- | --- | --- | --- |
| YYYY-MM-DD | Setup struktur MVC dan repository | Kerangka folder / tautan commit | — |
