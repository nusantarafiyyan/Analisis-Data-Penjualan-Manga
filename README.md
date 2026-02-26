# Analisis Data Penjualan Manga 

Proyek ini berisi eksplorasi dan analisis data penjualan manga terlaris di dunia. Dataset yang digunakan adalah `best-selling-manga.csv`, yang memuat informasi judul manga, penulis, penerbit, demografi pembaca, jumlah volume, serta total dan rata-rata penjualan per volume.

## Tujuan Analisis

- Melakukan Exploratory Data Analysis (EDA) untuk memahami distribusi penjualan manga dan karakteristik utama dataset.
- Mengidentifikasi dan mengevaluasi kualitas data, termasuk pengecekan missing value, duplikasi, serta nilai numerik yang mencurigakan.
- Mendeteksi dan menganalisis outlier pada fitur numerik seperti total penjualan dan rata-rata penjualan per volume.
- Menerapkan normalisasi/scaling pada fitur numerik sebagai persiapan untuk analisis lanjutan atau pemodelan.

## Isi Notebook

Notebook utama: `Analisis_Data_Penjualan_Manga.ipynb`

Tahapan utama di dalam notebook:
1. Pengenalan & Loading Data  
   - Import library, load dataset, dan melihat struktur awal data.

2. Exploratory Data Analysis (EDA)
   - Statistik deskriptif, distribusi penjualan, dan visualisasi dasar.

3. Pengecekan Kualitas Data  
   - Missing values, duplikasi data, serta pengecekan nilai numerik yang tidak logis.

4. Deteksi Outlier
   - Identifikasi outlier menggunakan metode IQR dan interpretasi outlier berdasarkan konteks domain (manga super populer).

5. Normalisasi Data Numerik
   - Penerapan Min-Max Scaling dan/atau Z-Score untuk fitur numerik yang relevan.

Notebook juga dilengkapi dengan penjelasan dalam bentuk markdown untuk setiap langkah analisis.
