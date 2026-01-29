[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/jv7IIKFU)

# Analisis Data Informasi Bencana Indonesia (DIBI - BNPB)
> **Strategic Disaster Mitigation Policy Analysis | Milestone 2 - CODA RMT-0012**

## Project Background
Bencana alam merupakan ancaman konstan yang berdampak signifikan pada keselamatan jiwa dan infrastruktur di Indonesia. Proyek ini bertujuan untuk melakukan analisis mendalam terhadap **[Data Informasi Bencana Indonesia (DIBI)](https://dibi.bnpb.go.id/superset/dashboard/2/)** dari BNPB guna memberikan dasar strategis dalam penyusunan kebijakan mitigasi.

Fokus utama analisis ini adalah mengidentifikasi wilayah paling rentan, jenis bencana dengan dampak kerusakan terbesar, serta memberikan rekomendasi berbasis data untuk menekan angka korban dan kerugian materiil.

---

## Problem Statement (SMART Framework)
Menganalisis dampak bencana di berbagai provinsi di Indonesia untuk menentukan prioritas alokasi sumber daya mitigasi dan memperketat regulasi bangunan tahan gempa di zona merah, dengan target memberikan rekomendasi kebijakan yang terukur bagi pemerintah daerah.

---

## Tech Stack & Methodology
Proyek ini menggunakan pendekatan statistika deskriptif dan inferensial:

* **Tools:** Python (Pandas, Matplotlib, Seaborn, Scipy) & Tableau.
* **Dataset:** Data Historis Bencana Indonesia (BNPB).
* **Workflow:**
    1.  **Data Cleaning:** Penanganan missing values dan standarisasi nama wilayah.
    2.  **EDA (Exploratory Data Analysis):** Visualisasi tren bencana tahunan dan distribusi dampak per wilayah.
    3.  **Statistical Analysis:** Uji hipotesis untuk membandingkan tingkat kerusakan antar jenis bencana.
    4.  **Dashboarding:** Pembuatan story board interaktif untuk presentasi insight kepada stakeholder.

---

## Key Insights
Berdasarkan analisis pada `P1M2_raina_imtiyaz.ipynb`:
1.  **Dampak Kerusakan:** Gempa bumi ditemukan sebagai bencana yang menyebabkan kerusakan rumah berat secara signifikan lebih tinggi dibandingkan jenis bencana lainnya.
2.  **Distribusi Wilayah:** Teridentifikasi provinsi-provinsi tertentu yang memiliki tingkat kerentanan tinggi yang memerlukan bantuan darurat tingkat pusat jika kapasitas daerah terlampaui.
3.  **Rekomendasi Kebijakan:** Diperlukan pengetatan pengawasan IMB (Instruksi Mendirikan Bangunan) serta audit berkala pada bangunan publik, khususnya di zona rawan gempa.

---

## Visualisasi Interaktif
Dapatkan gambaran data secara visual melalui dashboard Tableau berikut:

**[Lihat Tableau Dashboard](https://public.tableau.com/app/profile/raina.imtiyaz4352/viz/P1M2_raina_imtiyaz/Story1?publish=yes)**
<img width="1079" height="636" alt="image" src="https://github.com/user-attachments/assets/f5a9ffe3-2eee-4d37-a2d3-4446c593d2f8" />

