README untuk Analisis Retensi Pelanggan Superstore
====================================================

Deskripsi Proyek
-----------------
Proyek ini bertujuan untuk menganalisis retensi pelanggan Superstore berdasarkan kategori produk (Furniture, Office Supplies, dan Technology) untuk mengevaluasi performa kategori dan mengembangkan strategi yang dapat meningkatkan loyalitas pelanggan.

Dataset mencakup informasi penjualan dari tahun 2014 hingga 2017 dengan detail seperti:
- Tanggal pesanan
- Tanggal pengiriman
- Mode pengiriman
- ID pelanggan
- Nama pelanggan
- Segmen pelanggan
- Lokasi pelanggan (negara, kota, negara bagian, kode pos, wilayah)
- ID produk
- Kategori dan sub-kategori produk
- Nama produk
- Penjualan
- Kuantitas
- Diskon
- Keuntungan

Instalasi dan Persyaratan
--------------------------
1. Python 3.x
2. Library yang diperlukan:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - plotly
   - warnings

```bash
pip install pandas numpy matplotlib seaborn plotly
```

Struktur File
--------------
- `Sample - Superstore.csv` : Dataset utama
- `notebook.ipynb` : File notebook Jupyter yang berisi analisis lengkap

Analisis Utama
---------------
1. **Visualisasi Dasar**
   - Jumlah pelanggan berdasarkan kategori
   - Proporsi pelanggan berdasarkan kategori
   - Rata-rata transaksi per pelanggan berdasarkan kategori

2. **Cohort Analysis**
   - Retensi pelanggan secara semesteran dan kuartalan
   - Heatmap retensi
   - Line plot retensi

3. **Analisis Berdasarkan Segmen dan Region**
   - Distribusi pelanggan berdasarkan segmen dan region
   - Proporsi pelanggan di setiap segmen/region

Temuan Utama
-------------
1. **Pola Retensi Umum:**
   - Retensi pelanggan cenderung meningkat pada semester kedua setiap tahun
   - Q3 dan Q4 menunjukkan retensi yang lebih baik dibandingkan Q1 dan Q2
   
2. **Insight Kategori:**
   - **Office Supplies:** Retensi terbaik di Q3 dan Q4
   - **Technology:** Peningkatan retensi di semester 2
   - **Furniture:** Pola serupa dengan Technology

Rekomendasi Strategi
---------------------
1. Fokus promosi pada semester pertama
2. Terapkan strategi sukses dari periode dengan retensi tinggi ke periode rendah
3. Tingkatkan program loyalitas lintas kategori
4. Gunakan personalisasi berdasarkan data pembelian
5. Implementasikan mekanisme feedback untuk memahami alasan churn

Cara Menjalankan
-----------------
1. Clone repositori ini
2. Instal dependensi yang diperlukan
3. Tempatkan file dataset `Sample - Superstore.csv` di direktori yang sama
4. Jalankan notebook Jupyter:
   ```bash
   jupyter notebook notebook.ipynb
   ```

Catatan Tambahan
-----------------
- Analisis ini menggunakan cohort analysis untuk melacak perilaku pelanggan dari waktu ke waktu
- Visualisasi interaktif tersedia menggunakan Plotly
- Semua grafik dapat disesuaikan sesuai kebutuhan
