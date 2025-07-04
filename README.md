## New York City Taxi Fare Prediction

Proyek ini bertujuan untuk membangun model prediksi tarif taksi di kota New York berdasarkan data perjalanan, menggunakan teknik pembelajaran mesin berbasis Big Data. Proyek ini merupakan bagian dari tugas mata kuliah Big Data and Artificial Intelligence.

# Deskripsi Singkat
Proyek ini bertujuan untuk membangun model prediksi tarif taksi di kota New York berdasarkan data perjalanan, menggunakan teknik pembelajaran mesin berbasis Big Data. Proyek ini merupakan bagian dari tugas mata kuliah Big Data and Artificial Intelligence.
- Jarak tempuh (berdasarkan koordinat pickup dan dropoff)
- Jumlah penumpang
- Waktu dan tanggal perjalanan (jam, hari, bulan)
- Lokasi geografis pickup & dropoff
Proyek ini memanfaatkan PySpark untuk pengolahan data skala besar dan membangun model prediktif menggunakan algoritma Decision Tree dan Random Forest Regressor.

# Alur Program
1. Load & Preprocessing Data
2. Data Cleaning
3. Feature Engineering (ekstraksi waktu & kalkulasi jarak)
4. Exploratory Data Analysis
5. Model Training
  - Decision Tree Regressor
  - Random Forest Regressor
6. Evaluasi Model menggunakan RMS
7. Visualisasi Hasil

# Hasil
- Random Forest Regressor menghasilkan performa terbaik dengan nilai RMSE lebih rendah dibandingkan model lainnya.
- Model menunjukkan kemampuan cukup baik dalam memprediksi tarif taksi secara real-time berbasis input lokasi dan waktu.
