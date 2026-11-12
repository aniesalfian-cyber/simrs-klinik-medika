# PRODUCT REQUIREMENTS DOCUMENT (PRD)

- **Nama Produk**: Harvest Medika SIMRS & Klinik
- **Target Rilis**: https://simrs-klinik-medika.harvestdigital.pro
- **Referensi Dasar**: master-konsep.md
- **Penyusun**: Agen Analis

## 1. Spesifikasi Kebutuhan Fungsional (Functional Requirements)
| Kode | Fitur | Deskripsi | Prioritas |
|------|-------|-----------|-----------|
| FR-01 | Dashboard Metrik | Menampilkan Tagihan Layanan, Pasien Terlayani, dan Dokter & Poli Aktif secara akurat. | Tinggi |
| FR-02 | Formulir Input Rekam Medis & Antrean | Mendukung input No. Rekam Medis, Nama Pasien / Layanan, Poli / Unit, Biaya Layanan (Rp), Status Pemeriksaan dengan validasi tipe data. | Tinggi |
| FR-03 | Pencarian & Penyaringan | Menyaring baris data secara langsung berdasarkan kata kunci kode, nama, atau kategori. | Tinggi |
| FR-04 | Ekspor Laporan CSV | Mengunduh seluruh data operasional ke format CSV yang kompatibel dengan Excel. | Sedang |
| FR-05 | Panel Arsip Dokumen | Menyediakan akses baca langsung ke PRD, TODO, laporan Audit, dan 5 dokumen kontrak. | Tinggi |

## 2. Spesifikasi Non-Fungsional (Non-Functional Requirements)
- **Responsivitas**: Tata letak beradaptasi penuh pada layar ponsel (375px), tablet (768px), dan desktop (1440px) tanpa scroll horizontal.
- **Kontras & Aksesibilitas**: Rasio kontras teks minimal 4.5:1 (WCAG AA) dengan indikator fokus keyboard yang jelas.
- **Keamanan**: Pemblokiran akses file tersembunyi (dotfiles) pada level konfigurasi Nginx.
