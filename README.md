Analisis PCA dan FA pada Dataset Kendaraan

Deskripsi Proyek

Repositori ini berisi analisis Principal Component Analysis (PCA) dan Factor Analysis (FA) menggunakan bahasa pemrograman R. Studi ini bertujuan untuk mengeksplorasi hubungan antara variabel-variabel terkait spesifikasi kendaraan serta mengurangi dimensi dataset tanpa kehilangan informasi penting.

Dataset

Analisis dilakukan menggunakan dataset yang berisi informasi tentang berbagai kendaraan. Variabel yang digunakan dalam analisis adalah sebagai berikut:

Price_in_thousands: Harga kendaraan dalam ribuan dolar

Engine_size: Ukuran mesin kendaraan (dalam liter)

Horsepower: Daya maksimum kendaraan (dalam HP)

Wheelbase: Jarak sumbu roda (dalam inci)

Width: Lebar kendaraan (dalam inci)

Length: Panjang kendaraan (dalam inci)

Curb_weight: Berat kosong kendaraan (dalam pound)

Fuel_capacity: Kapasitas bahan bakar (dalam galon)

Fuel_efficiency: Efisiensi bahan bakar (mil per galon)

Power_perf_factor: Faktor kinerja daya kendaraan

Metodologi

Preprocessing Data: Membersihkan dataset dan menangani data yang hilang.

Eksplorasi Data: Statistik deskriptif dan visualisasi data.

Principal Component Analysis (PCA):

Normalisasi data

Analisis komponen utama

Interpretasi hasil

Factor Analysis (FA):

Menentukan jumlah faktor

Rotasi faktor untuk interpretasi yang lebih baik

Evaluasi hasil

Interpretasi & Kesimpulan

Struktur Repositori

├── data/               # Dataset mentah dan hasil preprocessing
├── scripts/            # Skrip R untuk analisis PCA dan FA
├── results/            # Hasil analisis dan visualisasi
├── README.md           # Dokumentasi proyek
└── report/             # Laporan lengkap dalam format RMarkdown atau PDF

Cara Menjalankan

Clone repositori ini:

git clone https://github.com/username/repo-name.git
cd repo-name

Jalankan RStudio dan buka skrip dalam folder scripts/.

Jalankan skrip secara berurutan untuk melakukan analisis.

Hasil Analisis

Laporan lengkap akan tersedia dalam folder report/ setelah eksekusi skrip selesai.

Kontributor

Nama Anda (@GitHubUsername)

Lisensi

Repositori ini dirilis di bawah lisensi MIT. Silakan gunakan dan modifikasi sesuai kebutuhan.
