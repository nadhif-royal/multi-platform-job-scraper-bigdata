# Multi-Platform Job Scraper & Big Data Pipeline 🚀

Repositori ini memuat implementasi *end-to-end* rekayasa data (ETL Pipeline) untuk mengekstrak, membersihkan, dan menganalisis data lowongan pekerjaan dari berbagai platform (Karir.com dan Glints.com). Proyek ini disusun untuk memenuhi tugas akhir mata kuliah Analitika Big Data, berfokus pada penyelesaian tantangan karakteristik **Variety** (skema data heterogen) dan **Veracity** (kualitas/kebersihan data).

## 🗂️ Struktur Repositori

Repositori ini menyimpan *source code* (notebook), dataset (mentah dan bersih), serta hasil visualisasi dan dokumentasi:

### 📄 Notebooks (Source Code)
* **`ProjectAkhirABD_NadhifRifatRasendriya_235150201111074.ipynb`**: Skrip utama proyek akhir. Memuat proses *Data Preprocessing*, pembersihan *dirty data* (*handling missing values & string formatting*), hingga tahap *Exploratory Data Analysis* (EDA) dan visualisasi.
* **`LK2ABD_NadhifRifatRasendriya_235150201111074.ipynb`**: Skrip *Web Scraping* Tahap 1. Menggunakan teknik *Dynamic Web Crawling* dan *Visual Order Scraping* untuk menembus *Anti-Bot* dan mengekstrak data dari web dinamis.

### 📊 Datasets
* **`cleaned_dataset_tahap2.csv`**: *Master dataset* final yang telah dibersihkan, dinormalisasi, dan siap digunakan untuk pemodelan analitika lanjutan (11 atribut tervalidasi).
* **`raw_dataset_gabungan_tahap1.csv`**: *Dataset* mentah gabungan dari semua platform sebelum proses *cleaning*.
* **`raw_dataset_finance_glints.csv`**: *Dataset* mentah spesifik posisi Finance dari Glints.
* **`raw_dataset_finance_karir.csv`**: *Dataset* mentah spesifik posisi Finance dari Karir.com.
* **`raw_data_karir_ai_engineer.csv`**: *Dataset* sampel awal (AI Engineer) dari Karir.com.

### 📈 Laporan & Visualisasi
* **`laporan akhir.pdf`**: Dokumentasi komprehensif proyek, mencakup arsitektur *pipeline*, rasionalisasi metode, kendala, dan wawasan bisnis yang ditemukan.
* **`eda_visualisasi.png`**: Grafik distribusi lokasi lowongan kerja sebagai hasil dari tahap ekstraksi *Value*.

## 🛠️ Teknologi yang Digunakan
* **Automasi & Scraping:** `Selenium` (google-colab-selenium), `BeautifulSoup4`
* **Pemrosesan Data:** `Pandas`, `NumPy`
* **Visualisasi:** `Matplotlib`, `Seaborn`

## 👤 Penulis
**Nadhif Rif'at Rasendriya** Teknik Informatika, Universitas Brawijaya
