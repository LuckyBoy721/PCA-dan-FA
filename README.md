Analisis PCA dan FA pada Dataset Otomotif

Repositori ini berisi analisis Principal Component Analysis (PCA) dan Factor Analysis (FA) pada dataset otomotif dengan variabel yang dipilih.

Variabel yang Digunakan

Analisis dilakukan pada variabel berikut:

Price_in_thousands

Engine_size

Horsepower

Wheelbase

Width

Length

Curb_weight

Fuel_capacity

Fuel_efficiency

Power_perf_factor

Tujuan Analisis

Principal Component Analysis (PCA):

Mengurangi dimensi dataset sambil mempertahankan informasi sebanyak mungkin.

Mengidentifikasi komponen utama yang mempengaruhi karakteristik kendaraan.

Factor Analysis (FA):

Mengidentifikasi faktor tersembunyi yang mendasari hubungan antar variabel.

Menganalisis apakah variabel dapat dikelompokkan berdasarkan korelasi mereka.

Metodologi

Preprocessing Data

Menghapus nilai yang hilang

Melakukan standarisasi data

PCA

Menentukan jumlah komponen utama yang optimal berdasarkan scree plot dan proporsi varians yang dijelaskan

Menafsirkan komponen utama

FA

Menentukan jumlah faktor optimal menggunakan kriteria eigenvalue >1 dan scree plot

Menafsirkan faktor berdasarkan muatan faktor (factor loadings)

Hasil dan Interpretasi

Visualisasi varians yang dijelaskan oleh PCA

Muatan faktor dan struktur faktor dari FA

Implikasi hasil terhadap analisis otomotif

Cara Menjalankan

Analisis dilakukan menggunakan bahasa R dan dipublikasikan di RPubs.

Clone repositori:

git clone https://github.com/username/repo-name.git
cd repo-name

Jalankan skrip R yang tersedia:

source("pca_fa_analysis.R")

Publikasi Hasil

Hasil analisis dapat diakses di RPubs: Tautan RPubs

Lisensi

Repositori ini tersedia di bawah lisensi MIT.
