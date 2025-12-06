Judul Project:
Car Sales Performance Analysis

Deskripsi:
Project ini merupakan analisis menyeluruh terhadap USA Car Sales Dataset 2018-2024. Dataset ini memberikan tampilan multidimensi yang kaya akan transaksi penjualan mobil individual, yang mencakup informasi seputar customers, spesifikasi mobil, metrik harga, detail pembayaran, kinerja penjualan, dan konteks musiman atau regional.
Tujuan utama project ini adalah membangun end-to-end analytics pipeline mulai dari pembuatan data warehouse PostgreSQL, transformasi ETL, hingga Power BI dashboard sebagai media eksplorasi insight bisnis.

Tools:
PostgreSQL, PowerBI

Insight:
1. Total sales stabil dan cenderung naik dan profit mengikuti pola yang sama. Tidak ada penurunan besar indikasi bahwa bisnis stabil
2. Perusahaan memiliki margin yang sehat (16%)
3. Payment Method seimbang, tidak bergantung pada metode pembayaran tertentu
4. Brand paling profitable: Mercedes, BMW, Audi
5. Market stabil, tidak ada penurunan demand
6. Produk mobil cukup netral secara gender customer
7. KOntribusi sales terbesar pada customer usia 35-64
8. Dari scatter plot terlihat pola semakin tua usia, semakin tinggi sale price mobil yang dibeli
9. Gap antara top dan buttom salesperson sangat jauh. Perlu program pelatihan khusus bagi buttom performers
10. Banyak salesperson dengan profit negatif. Indikasinya kemungkinan mereka memberikan diskon terlalu tinggi, sehingga harus ada kontrol approval

Dataset:
https://www.kaggle.com/datasets/anjaliprajapati307/usa-car-sales-dataset-2018-2024

Project ini membangun Star Schema yang terdiri dari:
fact_sales
dim_dates
dim_customers
dim_car
dim_salesperson
dim_region
dim_payments

Proses ETL dilakukan melalui SQL di PostgreSQL dengan berbagai langkah:
- Standardisasi format tanggal
- Cleaning dan Validasi data
- Key mapping antara fact & dimension

Selanjutnya PowerBI import data tersebut untuk dibuat dashboard dengan struktur:
- Summary Overview
- Customers and Market Analysis
- Salesperson Performance

File pbix:
File PBIX terlalu besar untuk diunggah langsung ke GitHub. Silakan download di link berikut:
https://drive.google.com/drive/folders/1_q9_pMhwO92h1Tqc5UVCqEXZsAy9BuZ2?usp=sharing