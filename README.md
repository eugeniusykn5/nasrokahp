# AHP Multi Expert

Project ini adalah aplikasi static HTML/CSS/JavaScript untuk menghitung AHP multi expert.

## Fitur

- Input jumlah expert, kriteria, dan alternatif
- Matriks perbandingan kriteria per expert
- Matriks perbandingan alternatif untuk tiap kriteria
- Agregasi grup dengan rata-rata geometrik
- Perhitungan bobot prioritas dan Consistency Ratio
- Ranking akhir alternatif
- Export dan import JSON
- Bisa langsung di-host di GitHub Pages

## Jalankan lokal

Karena ini aplikasi statis, cukup buka `index.html` di browser.

## Publish ke GitHub Pages

1. Push isi repo ini ke GitHub.
2. Buka repository di GitHub.
3. Masuk ke `Settings` > `Pages`.
4. Pada `Build and deployment`, pilih `Deploy from a branch`.
5. Pilih branch `main` dan folder `/root`.
6. Simpan, lalu tunggu URL GitHub Pages dibuat.

Jika file utamanya tetap `index.html` di root repo, GitHub Pages akan langsung memakainya sebagai halaman utama.
