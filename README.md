# 📊 Performance Analytics Kimia Farma (2020-2023)

Proyek ini merupakan hasil dari **Virtual Internship** di **Kimia Farma**. Fokus utama proyek ini adalah menganalisis kinerja bisnis perusahaan selama periode 2020 hingga 2023 dengan mengolah dataset transaksi skala besar menggunakan teknologi Cloud.

### 📈 Business Dashboard Overview
![Performance Analytics Dashboard](dashboard.jpg)

### 🛠️ Tech Stack & Tools:
* **Google BigQuery (SQL)**: Digunakan untuk melakukan ekstraksi, pembersihan, dan transformasi data transaksi (*Data Processing*).
* **Google Looker Studio**: Digunakan untuk membangun dashboard interaktif yang memvisualisasikan metrik utama bisnis.

### 🔍 Key Metrics & Insights:
* **Transaction Overview**: Berhasil memproses lebih dari **672 ribu transaksi** dengan total **Nett Sales mencapai 347 Miliar**.
* **Regional Performance**: Mengidentifikasi Jawa Barat sebagai wilayah dengan volume transaksi dan total penjualan tertinggi.
* **Profitability Mapping**: Memvisualisasikan persebaran *Nett Profit* di seluruh Indonesia melalui peta interaktif untuk melihat efektivitas cabang.
* **Comparison**: Menganalisis perbandingan pendapatan tahun ke tahun untuk memantau tren pertumbuhan bisnis secara konsisten.

### 📂 Repository Structure:
* `kf_analisa.sql`: Kode SQL untuk pemrosesan data di BigQuery.
* `dashboard.jpg`: Screenshot hasil visualisasi data.
* `README.md`: Dokumentasi proyek.
### 🛠️ Data Transformation & SQL Logic
Berikut adalah proses transformasi data menggunakan SQL di Google BigQuery:

![SQL Query kf_analisa](kf_analisa.png)

### 📋 Final Table Preview
Tampilan tabel hasil olahan (`kf_final_transaction`) yang siap dihubungkan ke Looker Studio:

![Final Table Preview](kf_final_transaction.png)
