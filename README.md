# Struktur Aljabar I — Companion Web (ITERA)

Repositori ini berisi berkas sumber website pendamping interaktif untuk buku ajar **Bacaan Struktur Aljabar I: Grup** di Program Studi Matematika, Institut Teknologi Sumatera (ITERA).

## Struktur Berkas

- `_quarto.yml`: Konfigurasi navigasi, tema, dan metadata Quarto.
- `styles.css`: Gaya tampilan khusus untuk container GeoGebra dan SageMath.
- `index.qmd`: Halaman beranda website pendamping.
- `modul-01-d4-serat.qmd`: Modul 1 interaktif tentang Grup Dihedral $D_4$ dan Serat Homomorfisme.
- `.gitignore`: Mengabaikan folder build sementara.

## Cara Menggunakan Secara Lokal

1. Pastikan [Quarto](https://quarto.org/) sudah terinstal di komputer Anda.
2. Jalankan `quarto preview` di terminal folder ini untuk melihat tampilan web secara langsung.
3. Untuk melakukan publikasi otomatis ke GitHub Pages, jalankan `quarto publish gh-pages`.
