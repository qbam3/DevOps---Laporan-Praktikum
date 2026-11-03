<p align="center"><img src="assets/logo-pens.png" alt="Logo PENS" width="135"></p>

# Laporan Praktikum Workshop DevOps

Repository ini berisi **dokumentasi lengkap praktikum** mata kuliah Workshop DevOps dalam format Markdown, termasuk langkah kerja, konfigurasi, pembahasan hasil, dan gambar/evidence yang diambil dari laporan praktikum. Setiap bab disimpan pada folder `laporan/` dan gambar-gambar terkait berada pada folder `assets/`.

**Politeknik Elektronika Negeri Surabaya (PENS)** — D4 Lanjut Jenjang Teknik Informatika, 2026  
**Dosen pengampu:** Dr. Ferry Astika Saputra, ST, M.Sc  
**Kelompok 2:** Ibram Maulana Akhsanul Qasasi (3126640014), Yusuf Rahmadhani Asy’ari (3126640042), Vernanda Mulia Hamonangan Manurung (3126640044).

## Daftar Laporan

| Bab | Materi | Dokumentasi |
|---|---|---|
| Bab 1 | Fondasi Teoretis Dan Kerangka Kerja Devsecops | [Baca laporan](laporan/bab-01.md) |
| Bab 2 | Konsep Container Dan Instalasi Docker | [Baca laporan](laporan/bab-02.md) |
| Bab 3 | Docker Network, Volume, Bind Mount, Tmpfs Dan Compose | [Baca laporan](laporan/bab-03.md) |
| Bab 4 | Nginx, Apache, Flash, Dan Tls Dengan Docker Compose | [Baca laporan](laporan/bab-04.md) |
| Bab 5 | Prostgresql, Pgadmin, Volume, Backup, Dan Restore | [Baca laporan](laporan/bab-05.md) |
| Bab 6 | Centralized Logging Dengan Fluent Bit Dan Postgresql | [Baca laporan](laporan/bab-06.md) |
| Praktikum PMB (Bab 6) | Praktikum Uji Coba Pmb — Devsecops Bab Vi | [Baca laporan](laporan/bab-06-pmb.md) |

## Struktur Repository

```text
.
├── assets/
│   ├── logo-pens.png
│   ├── bab1/
│   ├── bab2/
│   ├── bab3/
│   ├── bab4/
│   ├── bab5/
│   ├── bab6/
│   └── bab6-pmb/
├── laporan/
│   ├── bab-01.md
│   ├── bab-02.md
│   ├── bab-03.md
│   ├── bab-04.md
│   ├── bab-05.md
│   ├── bab-06.md
│   └── bab-06-pmb.md
├── .gitignore
└── README.md
```

## Cara Membaca

Klik **Baca laporan** pada tabel di atas. Gambar laporan ditampilkan langsung pada halaman Markdown melalui path relatif ke folder `assets`, sehingga dapat dibuka pada GitHub tanpa mengunduh PDF.

## Referensi Materi

Materi praktikum mengacu pada [repository Workshop DevSecOps dosen](https://github.com/ferryas-pens/devsecops). Dokumentasi bab dibuat berdasarkan laporan praktik yang disusun oleh Kelompok 2 dan laporan tambahan PMB.

> **Perhatian sebelum repository dipublikasikan:** Beberapa screenshot dari laporan menampilkan konfigurasi lingkungan atau terminal. Periksa kembali gambar dan pastikan tidak ada kata sandi, token, private key, atau informasi sensitif yang masih aktif. File `.env` dan artefak privat tidak termasuk dalam paket ini.
