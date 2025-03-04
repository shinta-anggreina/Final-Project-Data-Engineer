# 📊 Final Project - Data Engineering

Proyek ini merupakan tugas akhir kelompok menggunakan SQL berbasis database. Fokus utama proyek ini adalah mengembangkan database yang efisien serta menyusun query SQL untuk menjawab pertanyaan bisnis.  

## 📌 Tujuan Proyek  
✅ Mendesain database sesuai kebutuhan bisnis  
✅ Menyusun query untuk berbagai skenario

## 🏗 Struktur Proyek  
📁 **documents/** → Berisi dokumen pendukung proyek (Overview, Data Dictionary, dll.)  
📁 **sql/** → Berisi kumpulan query SQL yang digunakan  

## 📊 Tools & Teknologi  
- **SQL Server Management Studio** → Untuk pengelolaan database  

## 🖥 Contoh Query SQL  
```sql
SELECT category, SUM(sales) AS total_sales
FROM sales_data
GROUP BY category
ORDER BY total_sales DESC;
