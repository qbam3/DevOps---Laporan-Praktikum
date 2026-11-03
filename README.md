# Dokumentasi Praktikum Workshop DevOps

Repositori ini berisi **lima laporan praktikum** beserta **README khusus untuk setiap laporan** mata kuliah Workshop DevOps, Program Studi D4 Lanjut Jenjang Teknik Informatika, Politeknik Elektronika Negeri Surabaya (PENS), tahun 2026.

## Daftar laporan

| Laporan | Materi utama | Dokumentasi | Laporan PDF |
|---|---|---|---|
| Bab 1–3 | Fondasi DevSecOps; Docker; network, storage, dan Compose | [README Bab 1–3](Bab-01-03/README.md) | [PDF](Bab-01-03/Laporan.pdf) |
| Bab 4 | Nginx, Apache, Flask, reverse proxy, dan TLS | [README Bab 4](Bab-04/README.md) | [PDF](Bab-04/Laporan.pdf) |
| Bab 5 | PostgreSQL, pgAdmin, volume, backup, dan restore | [README Bab 5](Bab-05/README.md) | [PDF](Bab-05/Laporan.pdf) |
| Bab 6 — Logging | Centralized logging Fluent Bit–PostgreSQL dan Grafana | [README Bab 6](Bab-06-Logging/README.md) | [PDF](Bab-06-Logging/Laporan.pdf) |
| Studi kasus PMB | Pengujian baseline, failure injection, recovery, dan resilience logging | [README PMB](Bab-06-PMB/README.md) | [PDF](Bab-06-PMB/Laporan.pdf) |

## Struktur repositori

```text
.
├── README.md
├── .gitignore
├── Bab-01-03/
│   ├── README.md
│   └── Laporan.pdf
├── Bab-04/
│   ├── README.md
│   └── Laporan.pdf
├── Bab-05/
│   ├── README.md
│   └── Laporan.pdf
├── Bab-06-Logging/
│   ├── README.md
│   └── Laporan.pdf
└── Bab-06-PMB/
    ├── README.md
    └── Laporan.pdf
```

## Informasi akademik

- **Mata kuliah:** Workshop DevOps
- **Dosen pengampu:** Dr. Ferry Astika Saputra, ST, M.Sc
- **Institusi:** Politeknik Elektronika Negeri Surabaya (PENS)
- **Tahun:** 2026

### Anggota Kelompok 2

| Nama | NRP |
|---|---|
| Ibram Maulana Akhsanul Qasasi | 3126640014 |
| Yusuf Rahmadhani Asy’ari | 3126640042 |
| Vernanda Mulia Hamonangan Manurung | 3126640044 |

Dokumentasi **Bab 1–6** disusun oleh Kelompok 2, sedangkan laporan **studi kasus PMB** disusun secara individu oleh Ibram Maulana Akhsanul Qasasi.

## Petunjuk membaca

Pilih README per bab untuk membaca tujuan praktikum, rancangan atau alur sistem, langkah utama, hasil pengujian, dan kesimpulan. Laporan PDF menyertakan perintah, bukti terminal, tangkapan layar, serta pembahasan lebih lengkap.

Repositori ini adalah **arsip dokumentasi praktikum**, bukan repositori source code aplikasi lengkap. Contoh perintah pada README merujuk pada aktivitas dalam laporan; berkas konfigurasi dan skrip yang disebutkan di PDF tidak otomatis tersedia untuk dijalankan dari repositori ini.

## Keamanan publikasi

Jangan mengunggah `.env`, private key, token, dump database, atau log sensitif ke repository publik. **Periksa tangkapan layar dalam PDF** sebelum memublikasikan karena bukti praktikum dapat memperlihatkan konfigurasi atau nilai kredensial laboratorium.

## Referensi

- [Materi DevSecOps — ferryas-pens](https://github.com/ferryas-pens/devsecops)
