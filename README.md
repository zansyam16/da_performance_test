# Superstore Retail Performance Dashboard

---

## 1. Ringkasan Eksekutif
Repositori ini berisi proyek **Superstore Retail Performance Dashboard**, sebuah solusi *Business Intelligence* (BI) komprehensif yang dirancang untuk menganalisis tren penjualan, profitabilitas, serta analitik tingkat lanjut dari data ritel Superstore. Seluruh detail metrik dan analisis yang dijabarkan dalam dokumentasi ini merujuk pada visualisasi di dalam file referensi **superstore_dashboard_3.pdf**. Dashboard ini memfasilitasi manajemen dalam pengambilan keputusan berbasis data yang cepat dan akurat.

---

## 2. Indikator Kinerja Utama (KPIs)
Kinerja keseluruhan bisnis dipantau secara langsung melalui metrik utama berikut. Setiap metrik dilengkapi dengan indikator pertumbuhan *Year-over-Year* (YoY) untuk mengevaluasi akselerasi bisnis:

*   **Total Sales:** **608.5K** (Naik **29.3% YoY**)
*   **Total Profit:** **81.7K** (Naik **32.6% YoY**)
*   **Total Order:** **1,310** (Naik **26.2% YoY**)
*   **Total Customer:** **637** (Naik **11.2% YoY**)
*   **Total Qty:** **9,810** (Naik **22.9% YoY**)

---

## 3. Analisis Tren & Peramalan (*Forecasting*)
Dashboard memvisualisasikan pergerakan kinerja dari waktu ke waktu untuk mengidentifikasi pola bisnis:
*   **Pemantauan Historis:** Menggunakan visualisasi *line chart* untuk melacak pergerakan metrik **"Sales & Profit"** dan **"Total Order"** secara berkesinambungan dari rentang **Januari 2011 hingga pertengahan 2014**.
*   **Peramalan Prediktif (*Forecasting*):** Dilengkapi dengan kapabilitas proyeksi masa depan menggunakan model statistik, yang direpresentasikan melalui **area interval abu-abu** pada grafik tren.

---

## 4. Distribusi Demografi & Produk
Analisis segmentasi digunakan untuk mengidentifikasi kelompok pelanggan dan kategori produk dengan kontribusi pendapatan terbesar:

*   **Berdasarkan Segmen:** Pangsa pasar didominasi oleh segmen **Consumer (48.69%)**, disusul oleh pelanggan **Corporate (34.01%)**, dan **Home Office (17.29%)**.
*   **Berdasarkan Kategori:** Penjualan tertinggi dipimpin oleh kategori **Technology (37.15%)**, diikuti dengan ketat oleh **Furniture (32.69%)**, dan **Office Supplies (30.16%)**.

---

## 5. Kinerja Geografis (Spasial)
Pemetaan performa wilayah sangat krusial dalam distribusi logistik dan strategi pemasaran. Modul spasial ini mencakup:
*   **Peta Interaktif:** Integrasi peta *Regional Performance* berbasis **Microsoft Bing** untuk visualisasi metrik secara nasional di wilayah Amerika Serikat.
*   **Tabel *Drill-Down*:** Tabel matriks mendetail pada tingkat *State* (Negara Bagian) yang membandingkan **Total Order, Total Sales,** dan **Total Profit** berserta indikator **YoY**-nya secara berdampingan (contoh: pemantauan performa spesifik di *state* seperti Mississippi, Rhode Island, dan lainnya).

---

## 6. Analitik Lanjutan (*Advanced Analytics / AI*)
Untuk menggali *insight* yang lebih mendalam melampaui visualisasi standar, dashboard ini mengintegrasikan kapabilitas AI:

*   **Decomposition Tree:** Fitur eksplorasi *root-cause* untuk membedah (*breakdown*) nilai metrik secara hierarkis dan interaktif, mulai dari nilai **Total**, turun ke **Segmen**, hingga mengerucut ke level **Kategori**.
*   **Key Influencers:** Analisis AI prediktif untuk menemukan variabel utama yang mendorong kenaikan metrik bisnis. Faktor pendorong paling signifikan (*top influencers*) secara berurutan adalah:
    1.  Ketika *sub_category* adalah **Tables** (Meningkatkan rata-rata metrik sebesar **459.6**)
    2.  Ketika *sub_category* adalah **Chairs** (Meningkatkan sebesar **334.7**)
    3.  Ketika *category* adalah **Technology** (Meningkatkan sebesar **278.8**)
    4.  Ketika *sub_category* adalah **Phones** (Meningkatkan sebesar **157.1**)

---

## 7. Penggunaan Filter
Dashboard didesain secara dinamis agar pengguna dapat mengisolasi data spesifik yang mereka butuhkan. Opsi navigasi meliputi:
*   **Slicer Dinamis:** Filter waktu kustom untuk **Trend Period** dan **Performance Period** (contoh konfigurasi: `1/1/2013 - 12/31/2013`).
*   **Filter Dropdown:** Pengaturan parameter yang mencakup pilihan **Metrik, Segmen, Kategori, Sub Kategori**, dan Mode Pengiriman (**Ship Mode**).

---
*Dokumentasi ini disusun secara otomatis merujuk pada standar portofolio Data Analytics profesional.*
"""
