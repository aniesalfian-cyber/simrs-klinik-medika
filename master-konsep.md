# MASTER KONSEP APLIKASI: HARVEST MEDIKA SIMRS & KLINIK

- **Nama Aplikasi**: Harvest Medika SIMRS & Klinik
- **Subdomain Produksi**: https://simrs-klinik-medika.harvestdigital.pro
- **Kategori Sistem**: Healthcare & Medical Records
- **Tech Stack**: HTML5, Tailwind CSS, Codeiginter 4, PHP 8.3, MySQL, Nginx
- **Tanggal Perumusan**: 12 November 2026
- **Disusun Oleh**: Agen Analis (Pabrik Harvest Digital Indonesia)

## 1. Latar Belakang & Tujuan Konseptual
Sistem informasi manajemen klinik pratama untuk pendaftaran rekam medis pasien, antrean poliklinik, pencatatan tarif tindakan medis, dan laporan operasional harian.

Sistem ini dirancang untuk menyediakan alur operasional yang terukur, transparan, dan responsif baik ketika diakses melalui perangkat mobile maupun desktop.

## 2. Entitas Utama & Struktur Modul
1. **Modul Utama (Rekam Medis & Antrean)**: Pencatatan real-time, pencarian instan, kalkulasi metrik otomatis, dan ekspor data CSV.
2. **Modul Pendukung (Inventori Obat)**: Pengelompokan status operasional dan rekapitulasi nilai transaksi.
3. **Modul Dokumentasi Terpadu**: Akses langsung ke seluruh berkas arsitektur, hasil audit, dan dokumen serah terima.

## 3. Arsitektur Teknis
- **Antarmuka Pengguna**: HTML5 Semantik, Tailwind CSS, Mode Gelap & Terang (Glassmorphism Adaptif), aksesibilitas WCAG AA.
- **Penyimpanan & State**: Penyimpanan persisten sisi klien yang terisolasi per subdomain serta dukungan ekspor CSV standar.
- **Infrastruktur Server**: Nginx Reverse Proxy & Virtual Host otomatis pada VPS Harvest Digital Indonesia.
