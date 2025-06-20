# Analisis Data Penjualan Mobil

## Repository Outline
1. README.md - Penjelasan gambaran umum project
2. Data Analysis.ipynb - Notebook pengolahan data menggunakan Python
3. dataset.rar - Dataset penjualan mobil yang telah diolah

## Problem Background
Project ini dilaksanakan berdasarkan permintaan dari klien yang merupakan owner dari sebuah perusahaan showroom mobil. Jumlah transaksi yang dilakukan oleh perusahaannya mengalami stagnansi dan cenderung mengalami penurunan. Dia merasa perlu melakukan strategi baru untuk meningkatkan jumlah penjualan. Sebagai seorang data analis saya mencari data penjualan mobil dalam beberapa tahun terakhir, kemudian melakukan analisis statistik pada data tersebut dan menggambarkan visualisasi data agar mudah dipahami oleh klien.

## Project Output
Hasil pengolahan data pada project ini menghasilkan beberapa dokumen antara lain:
- Data penjualan yang telah diolah .csv
- Tabel visualisasi penjualan dalam bentuk barplot atau lineplot
- Tabel interactive yang dapat diakses secara online
- Laporan analisis data yang berisi rekomendasi strategi bisnis yang dapat dilakukan

## Data
Dataset yang digunakan pada project ini berasal dari Kaggle dengan judul "Vechicle Data Sales".
Dataset berisikan lebih dari 500 ribu baris data yang terdiri dari 16 kolom. Dataset tersebut berisi data penjualan mobil di USA pada tahun 2014 hingga 2015. Deskripsi dataset lebih lanjut dapat dilihat dari tabel dibawah.
 

 0   year -         Tahun produksi mobil  Numerical \
 1   make -         Produsen mobil        Categorical \
 2   model -        Model mobil           Categorical \
 3   trim -         Kode / Alias mobil    Categorical \
 4   body -         Jenis body mobil      Categorical \
 5   transmission - Jenis Transmisi       Categorical \
 6   vin -          Nomor Rangka          Categorical \
 7   state -         Daerah Asal           Categorical \
 8   condition -     Index kondisi mobil   Numerical \
 9   odometer -     Jarak tempuh mobil    Numerical \
 10  color -        Warna mobil           Categorical \
 11  interior -     Jenis interior        Categorical \
 12  seller -       Nama Penjual          Categorical \
 13  mmr -          Standar harga pasar   Numerical \
 14  sellingprice - Harga jual            Numerical \
 15  saledate -     Tanggal penjualan     Categorical 


## Method
Metode analisis data yang digunakan pada project ini meliputi beberapa method antara lain:
1. Visualisasi data -> untuk menggambarkan grafik penjualan agar mudah dianalisis
2. Statistik deskriptif -> untuk menggambarkan karakteristik data secara umum
3. Statistik inferensial -> untuk menguji asumsi yang timbul berdasarkan data yang ada

## Stacks
Proses pengolahan data dilakukan menggunakan aplikasi VSCode dengan bahasa pemrograman Python
Terdapat beberapa tools yang digunakan untuk mempermudah proses analisis data, yaitu:
1. Pandas -> untuk memproses dataset
2. Scipy -> untuk perhitungan statistik
3. Seaborn -> untuk menggambarkan visualisasi data
4. Tableau -> untuk membuat interactive visual

## Reference
Dashboard Inteactive Hasil Analisis data penjualan mobil dapat diakses melalui : https://public.tableau.com/app/profile/pujo.prasetyo.aji/viz/Book1_17454778947720/AnalisisPenjualanMobil?publish=yes

Dataset yang digunakan bisa diakses melalui url = https://www.kaggle.com/datasets/syedanwarafridi/vehicle-sales-data
