Insurance Loss Ratio Analysis
📌 Deskripsi Proyek

Proyek ini bertujuan untuk menganalisis Loss Ratio pada industri asuransi konvensional di Indonesia menggunakan data publik dari Otoritas Jasa Keuangan (OJK).

Analisis dilakukan mulai dari pengolahan data mentah → pembersihan data → analisis menggunakan Python → visualisasi interaktif dengan Power BI.
Hasilnya diharapkan dapat memberikan insight mengenai profitabilitas, tren klaim, serta stabilitas tiap jenis usaha (Asuransi Jiwa, Asuransi Umum, dan Reasuransi).



📂 Struktur Folder
insurance-loss-ratio-analysis/
│
├── data/                          # Dataset mentah & hasil cleaning
│   ├── Asuransi Konvensional Premi dan Klaim 29 Agu 2025.xlsx
│   └── cleaned_data.csv
│
├── notebooks/                     # Analisis eksploratif dengan Python
│   └── loss_ratio_analysis.ipynb
│
├── dashboard/                     # Dashboard interaktif Power BI
│   ├── loss_ratio_dashboard.pbix
│   └── screenshot_dashboard.png
│
├── .gitignore                     # File & folder yang diabaikan Git
└── README.md                      # Dokumentasi proyek



🔍 Data

*Sumber: OJK – Statistik Asuransi Konvensional

*Periode: 2018–2024

*Variabel Utama:
-Klaim (total klaim yang dibayarkan)
-Premi (total premi yang diterima)
-Loss Ratio = Klaim / Premi



⚙️ Tahapan Proyek

1. Data Collection → Mengunduh data premi & klaim asuransi dari OJK.

2. Data Cleaning → Menstandarkan format, menghapus nilai yang tidak konsisten, dan menyimpan dataset bersih (cleaned_data.csv).

3. Exploratory Data Analysis (EDA) → Menggunakan Python (loss_ratio_analysis.ipynb) untuk memahami tren & pola data.

4. Visualization → Membuat dashboard interaktif Power BI (loss_ratio_dashboard.pbix).



📊 Dashboard Preview

Highlight Insight:

Asuransi Jiwa: Menunjukkan trend Kenaikan, bertahan di atas 82% dan sempta melampaui 92%.


Asuransi Umum: selalu di bawah 50% → efisiensi terbaik.

Reasuransi: paling fluktuatif, naik dari 44% ke 60% (Kenaikan ~35%).



🚀 Cara Menjalankan

1. Clone repository ini:

git clone https://github.com/Ikalls75/insurance-loss-ratio-analysis.git

2. Buka folder notebooks/ untuk eksplorasi analisis Python.

3. Buka file dashboard/loss_ratio_dashboard.pbix di Power BI Desktop untuk melihat visualisasi interaktif.



📧 Kontak

Jika tertarik berdiskusi lebih lanjut seputar analisis aktuaria, data science, atau peluang internship, silakan hubungi saya melalui [LinkedIn](https://www.linkedin.com/in/haikal-al-faruqi/).


