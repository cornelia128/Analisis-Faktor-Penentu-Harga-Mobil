## Business Problem
Konsumen kesulitan menentukan apakah harga sebuah mobil sudah sesuai dengan spesifikasi atau performa yang ditawarkan, karena tidak ada acuan yang jelas tentang faktor apa saja yang seharusnya memengaruhi harga jual kendaraan.

## Objectives
* Mengindentifikasi pengaruh tipe bodi mobil terhadap harga jual
* Menentukan merek mobil dengan nilai jual tertinggi maupun terendah sebagai pembanding segmen
* Mengevaluasi dampak spesifikasi teknis (bahan bakar dan aspirasi) terhadap harga
* Membandingkan efisiensi bahan bakar berdasarkan sistem penggerak
* Menganalisis korelasi antara performa mesin dan harga, termasuk segmentasi tingkat tenaga mesin
* Mengindentifikasi mobil dengan value-for-money terbaik sebagai rekomendasi objektif bagi konsumen
* Menyediakan acuan harga pasar yang objektif bagi konsumen
  
## Business Questions
* Bagaimana tipe bodi mobil memengaruhi rata-rata harga jual di pasar?
* 5 merek mobil apa saja yang memiliki rata-rata harga tertinggi, dan berapa kisaran harga yang mereka tawarkan dibandingkan rata-rata pasar?
* 5 merek mobil apa saja yang berada di segmen paling terjangkau (mobil dengan rata-rata harga terendah) 
* Bagaimana kombinasi antara jenis bahan bakar (Diesel vs Gas) dan sistem aspirasi (Standard vs Turbo) memengaruhi nilai jual kendaraan?
* Sistem penggerak roda (Drive Wheels) mana yang paling efisien dalam penggunaan bahan bakar, baik untuk penggunaan di dalam kota (City MPG) maupun jalan tol  (Highway MPG)?
* Sejauh mana peningkatan tenaga mesin (Horsepower) berkontribusi terhadap kenaikan harga sebuah mobil, dan bagaimana pola harga jika mobil dikelompokkan berdasarkan level tenaga (Low/Medium/High Power)?
* Tipe bodi mobil mana yang memiliki jumlah unit terbanyak di pasar, dan apakah dominasi jumlah ini berkaitan dengan keterjangkauan harganya?
* Mobil apa yang menawarkan efisiensi bahan bakar di atas rata-rata sekaligus harga di bawah rata-rata?
* Mobil apa saja yang menawarkan tenaga mesin besar dengan harga di bawah rata-rata pasar, dan mobil mana yang dijual mahal tanpa didukung tenaga mesin besar?
* Berapa nilai rata-rata harga pasar secara keseluruhan yang dapat digunakan oleh konsumen sebagai standar dasar sebelum mempertimbangkan spesifikasi tambahan?

## Dataset
* Sumber: [Kaggle - Automobile Dataset](https://www.kaggle.com/datasets/toramky/automobile-dataset)
* Jumlah Data: 201 unit mobil

## Tools
* Excel
* SQL
* Tableau

## Workflow
1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. SQL Analysis
5. Dashboard
6. Business Insight
7. Recommendation
8. Conclusion

## Data Cleaning
* Menangani missing value menggunakan fungsi COUNTBLANK
* Penanganan data yang tidak lengkap melalui imputasi statistik (mean untuk data dengan variasi kecil, median untuk data yang lebih tersebar atau memiliki outlier)
* Imputasi berbasis grup untuk variabel yang nilainya bergantung pada kategori tertentu
* Konversi tipe data teks ke numerik
* Standarisasi kategori menggunakan fungsi PROPER
  
## Exploratory Data Analysis
* **Analisis Deskriptif:** Memberikan gambaran umum tentang dataset melalui metrik utama yang mencakup total sampel data dan perhitungan rata-rata untuk variabel-variabel kunci seperti harga, tenaga mesin (Horsepower), konsumsi bahan bakar di kota (City MPG), dan di jalan raya (Highway MPG).
* **Analisis Segmentasi  Harga:** Membandingkan rata-rata harga di berbagai tipe bodi, mengindentifikasi 5 merek dengan rata-rata harga tertinggi dan terendah, menganalisis pengaruh kombinasi jenis bahan bakar (Gas/Disel) dan sistem aspirasi (Standard/Turbo) terhadap harga.
* **Analisis Distribusi:** Melakukan penghitungan frekuensi untuk melihat tipe bodi mana yang paling dominan dalam dataset.
* **Analisis Efisiensi Bahan Bakar:** Membandingkan efisiensi baha bakar (City MPG dan Highway MPG) berdasarkan sistem penggerak roda (4Wd, Fwd, dan Rwd).
* **Analisis Korelasi dan Segmentasi Performa:** Melihat hubungan antara tenaga mesin (Horsepower) denga harga mobil.
  
## SQL Analysis
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/1.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/2.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/3.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/4.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/5.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/6.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/7.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/8.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/9.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/10.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/11.png?raw=true" width=500 height=300>


## Dashboard Excel
[Dashboard Excel - Analisis Harga & Spesifikasi Mobil](https://1drv.ms/x/c/33df3e24b33e1e8a/IQD08wg-yxfWQqZT0MPR5NnQAW9mzsujnobUHLORorNLz1Y?e=fcrFbW)

<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/Dashboard%20Analisis%20Harga%20&%20Spesifikasi%20Mobil%20(excel).jpg?raw=true" width=500 height=300>

## Dashboard Tableau
[Dashboard Tableau - Analisis Harga & Spesifikasi Mobil](https://public.tableau.com/views/DashboardAnalisisHargaSpesifikasiMobil/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/images/Dashboard%20Analisis%20Harga%20&%20Spesifikasi%20Mobil%20(tableau).png?raw=true" width=600 height=300>

## Business Insight
**Tipe bodi menentukan segman harga, bukan populasi**
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/business%20insight%20images/1.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/business%20insight%20images/1.2.png?raw=true" width=500 height=300>
Sedan mendominasi populasi (94 unit, 47%) namun harganya menengah ($14.460) bukan yang termurah. Hatchback justru lebih murah ($9.957) meski populasinya lebih sedikit. Dominasi jumlah unit tidak berbanding lurus dengan harga termurah.

**Kesenjangan harga antar merek sangat lebar**
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/business%20insight%20images/2.png?raw=true" width=600 height=300>
Jaguar dijual lebih dari 5x lipat harga rata-rata Chevrolet ($34.600 vs $6.007), dan +$21.393 di atas rata-rata pasar; brand/merek adalah salah satu pendorong harga terkuat.

**Aspirasi turbo dan tenaga mesin mendorong harga**
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/business%20insight%20images/3.png?raw=true" width=600 height=300>
Mobil High Power dijual hampir 3x lipat dari Low Power ($25.294 vs $8.738). Korelasi Pearson horsepower-harga tergolong kuat (+0,81). Diesel Turbo adalah kombinasi termahal, Diesel Standard yang termurah; teknologi aspirasi (Turbo) lebih menentukan harga dibanding jenis bahan bakar itu sendiri.

**FWD & Hatchback: Kombinasi Value-for-Money Terbaik**
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/business%20insight%20images/4.png?raw=true" width=500 height=300>
<img src="https://github.com/cornelia128/Analisis-Faktor-Penentu-Harga-Mobil/blob/main/business%20insight%20images/4.2.png?raw=true" width=500 height=300>
FWD paling irit di kota maupun jalan tol, sementara RWD paling boros (biasanya mobil sport bertenaga besar). Hatchback konsisten muncul sebagai rekomendasi rasio tenaga & efisiensi terbaik per dollar.

## Recommendation
* Gunakan $13.207 sebagai acuan dasar; mobil jauh di atas angka ini tanpa horsepower/merek premium patut dipertanyakan value-nya.
* Pilih tipe bodi Hatchback dan sistem penggerak FWD untuk kombinasi harga terjangkau dan efisiensi BBM terbaik.
* Waspadai price premium dari merek (Jaguar, Mercedes-Benz, Porsche) dan mesin Turbo; kenaikan harga tidak selalu sebanding kenaikan performa aktual.
* Untuk performa tinggi dengan harga wajar, cek segmen Medium Power (100-150 HP) sebagai titik tengah value-for-money.

## Conclusion
* Horsepower, merek/brand, dan teknologi aspirasi (Turbo) secara konsisten menjadi pendorong harga terkuat di seluruh analisis.
* Kombinasi Hatchback + FWD paling konsisten muncul sebagai pilihan rasional dari sisi harga maupun efisiensi bahan bakar.
* Tipe bodi paling banyak beredar (Sedan) tidak selalu paling terjangkau; popularitas dan harga adalah dua dimensi yang berbeda.
* Rata-rata harga pasar $13.207 dan segmentasi tenaga mesin dapat dipakai konsumen sebagai standar dasar yang objektif.
