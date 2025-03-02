# 📊 Final Project - Data Analysis  

Proyek ini merupakan tugas akhir kelompok dalam menganalisis data menggunakan SQL dan visualisasi berbasis database. Fokus utama proyek ini adalah mengembangkan database yang efisien serta menyusun query SQL untuk menjawab pertanyaan bisnis.  

## 📌 Tujuan Proyek  
✅ Mendesain database sesuai kebutuhan bisnis  
✅ Menggunakan SQL untuk analisis data  
✅ Menyusun query untuk berbagai skenario bisnis  

## 🏗 Struktur Proyek  
📁 **documents/** → Berisi dokumen pendukung proyek (Overview, Data Dictionary, dll.)  
📁 **sql/** → Berisi kumpulan query SQL yang digunakan  

## 📊 Tools & Teknologi  
- **SQL Server** → Untuk pengelolaan database  
- **Power BI / Excel** → Untuk analisis dan visualisasi data  

## 🚀 Hasil Analisis  
1. **Optimasi Database** → Desain tabel dan relasi  
2. **Analisis Data** → Query SQL untuk menjawab pertanyaan bisnis  
3. **Visualisasi Data** → Representasi hasil analisis  

## 🖥 Contoh Query SQL  
```sql
SELECT category, SUM(sales) AS total_sales
FROM sales_data
GROUP BY category
ORDER BY total_sales DESC;
