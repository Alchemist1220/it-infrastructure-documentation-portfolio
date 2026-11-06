# IT Infrastructure Maintenance Documentation & Reporting Portfolio

> **Simulated Case Study — PT Arunika Digital Nusantara (October 2026)**  
> *Portofolio latihan profesional untuk posisi Technical Writer Intern.*

---

## 📌 Deskripsi Proyek
Repositori ini berisi simulasi end-to-end tata kelola dokumentasi pemeliharaan infrastruktur IT (*IT Infrastructure Maintenance Documentation*). Proyek ini mensimulasikan bagaimana seorang *Technical Writer* menerima catatan pekerjaan mentah dari tim *Engineer/Technician*, melakukan verifikasi bukti kerja (*evidence*), mengontrol versi dokumen, serta menyusun laporan ringkasan makro (bulanan) dan mikro (individu perangkat).

Seluruh perusahaan, aset, personel, work order, dan bukti dalam repositori ini bersifat **fiktif** dan dibuat khusus untuk kebutuhan portofolio profesional.

---

## 🗂️ Struktur File & Dokumen
Repositori ini terbagi menjadi dua komponen utama:

1. **Workbook Excel Master Database (`/excel`)**
   * Berisi log pemeliharaan (*Maintenance Log*), register bukti (*Evidence Register*), register kendali versi dokumen (*Document Register*), dan ringkasan eksekutif bulanan (*Monthly Summary*).
   * Menggunakan format bilingual (istilah teknis dalam Bahasa Inggris, panduan dan catatan dalam Bahasa Indonesia).

2. **Laporan Resmi Microsoft Word (`/documents`)**
   * **Monthly Maintenance Report (`MMR-2026-10`):** Laporan bulanan komprehensif yang merangkum 10 work order, statistik KPI, dan 5 poin temuan penting yang memerlukan *follow-up* proaktif dengan teknisi.
   * **Individual Maintenance Report (`MR-2026-001`):** Contoh laporan mendalam untuk perangkat *Application Server 01* (`SRV-APP-01`) berdasarkan *Work Order WO-2026-001*.

---

## ⚙️ Prinsip Kerja & Pendekatan Technical Writer
Dalam penyusunan dokumentasi ini, diterapkan standar kendali mutu berikut:
* **Traceability (Keterunutan):** Setiap laporan terhubung secara konsisten ke *Work Order ID*, *Asset ID*, dan *Evidence ID*.
* **Accuracy (Akurasi Data):** Informasi dicatat murni berdasarkan laporan teknisi; dilarang keras melakukan asumsi atau inferensi pengukuran mandiri (misal: persentase *battery health* UPS).
* **Completeness (Kelengkapan):** Memeriksa kelengkapan tanggal, aset, deskripsi kerja, temuan, dan lampiran bukti sebelum dokumen disetujui.
* **Evidence Verification (Verifikasi Bukti):** Membedakan status file yang *Received* (diterima) dengan *Verified* (terverifikasi isinya).
* **Version Control (Kontrol Versi):** Penggunaan penomoran versi yang jelas (`v0.9 Draft`, `v1.0 Released`) serta konvensi penamaan file yang terstruktur.

---

## 🚀 Cara Menggunakan Repositori Ini
* Unduh file Excel di folder `/excel` untuk melihat pemodelan data dan rumus rekapitulasi.
* Unduh file Word di folder `/documents` untuk meninjau tata letak dokumen (*formatting*), tabel metadata, dan gaya penulisan laporan teknis profesional.

---
*Disusun oleh **Muhammad Alman Firdaus** sebagai bagian dari portofolio pelamaran Technical Writer Intern.*
