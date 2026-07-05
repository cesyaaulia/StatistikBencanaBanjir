<div align="center">

# 🌊 Analisis Statistik Deskriptif: Sebaran Temporal Desa Terdampak Banjir (Jawa Timur 2019-2021)

![Language](https://img.shields.io/badge/Language-Python_3-blue?style=for-the-badge&logo=python&logoColor=white)
![Environment](https://img.shields.io/badge/Environment-Jupyter_Notebook-orange?style=for-the-badge&logo=jupyter&logo=googlecolab&logoColor=white)
![Data Source](https://img.shields.io/badge/Data_Source-BPS_Jawa_Timur-darkblue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

<p align="center">
  <strong>Sebuah proyek analisis data untuk memetakan kerentanan kewilayahan terhadap bencana banjir di Jawa Timur melalui pendekatan statistik deskriptif dan visualisasi temporal.</strong>
</p>

[Tentang Proyek](#-tentang-proyek) • [Tujuan Analisis](#-tujuan-analisis) • [Teknologi](#-spesifikasi-teknologi) • [Visualisasi & Temuan](#-visualisasi--temuan) • [Struktur Repositori](#-struktur-repositori)

</div>

---

## 📖 Tentang Proyek

Repositori ini berisi implementasi analisis data yang mengevaluasi tren bencana banjir di tingkat desa/kelurahan di Provinsi Jawa Timur selama periode 2019–2021. Proyek ini mengubah data sekunder dari **BPS Jawa Timur** menjadi informasi yang dapat ditindaklanjuti untuk mendukung mitigasi bencana berbasis data.

Analisis dilakukan dengan menerapkan prosedur pembersihan data (data cleaning), perhitungan statistik deskriptif, serta pemodelan sebaran untuk mendeteksi wilayah yang menjadi *hotspot* banjir.

---

## 🎯 Tujuan Analisis

Proyek ini disusun untuk mencapai sasaran berikut:
- 📊 **Pemetaan Kerentanan:** Mengidentifikasi wilayah administratif (Kabupaten/Kota) dengan tingkat kejadian banjir tertinggi setiap tahunnya.
- 📉 **Analisis Temporal:** Mengevaluasi dinamika perubahan jumlah desa terdampak dalam rentang tiga tahun untuk melihat kecenderungan kenaikan atau penurunan kasus.
- 🗺️ **Deteksi Outlier:** Menggunakan teknik visualisasi untuk menemukan wilayah dengan penyimpangan data (pencilan) guna menentukan prioritas intervensi pemerintah provinsi.

---

## 🛠️ Spesifikasi Teknologi

Pipeline pengolahan data dibangun menggunakan pustaka Python standar untuk *data science*:

| Teknologi | Fungsi dalam Proyek |
| :--- | :--- |
| **Pandas** | Manipulasi dataset, agregasi tahunan, dan pengurutan (*sorting*) wilayah terdampak. |
| **Matplotlib** | Perancangan dasar grafik visualisasi dan pengaturan layout sumbu data. |
| **Seaborn** | Pembuatan plot tingkat lanjut seperti *Kernel Density Estimate* (KDE) dan *Boxplot* untuk analisis distribusi data. |

---

## 📊 Visualisasi & Temuan

Hasil analisis menunjukkan beberapa temuan krusial:

1. **Sebaran Tidak Merata:** Kejadian banjir terpusat pada wilayah-wilayah tertentu (*hotspot*), sementara wilayah lain relatif aman.
2. **Validasi Visual:** Melalui grafik *KDE* dan *Boxplot*, terbukti bahwa distribusi data bersifat *skewed* (miring) ke kanan, yang berarti intervensi kebijakan tidak bisa disamaratakan di seluruh Jawa Timur.
3. **Prioritas Mitigasi:** Kabupaten Sampang dan Pasuruan konsisten menempati daftar "Top 10" wilayah terdampak, sehingga memerlukan audit drainase dan daerah resapan air yang lebih intensif.

---

## 📂 Struktur Repositori

```text
StatistikBencanaBanjir/
│
├── 📄 Analisis_Terdampak_Bencana_Banjir.ipynb  # Notebook utama berisi alur analisis dan kode Python
└── README.md                                   # Dokumentasi utama proyek
```
---

## 🎓 Author

**Cesya Aulia Ramadhani** *Applied Science Undergraduate Student in **Management Informatics** — Universitas Negeri Surabaya*
