# Laporan Prediksi Konsumsi Bahan Bakar Mobil Menggunakan Neural Network Regresi Linear - Muchammad Wildan Alkautsar

## Project Overview
**Deskripsi Proyek**: Proyek ini bertujuan untuk membangun model neural network regresi linear yang dapat memprediksi konsumsi bahan bakar mobil (miles per gallon/miles per gallon) berdasarkan atribut-atribut seperti displacement, jumlah silinder, tenaga kuda, berat, akselerasi, tahun model, dan asal mobil. Dataset yang digunakan berasal dari repositori UCI Machine Learning, yang menyediakan data historis mengenai berbagai karakteristik mobil.

**Pentingnya Proyek:** Memahami faktor-faktor yang memengaruhi konsumsi bahan bakar mobil sangat penting untuk berbagai tujuan, termasuk:
1. **Pengambilan Keputusan Pembelian:** Calon pembeli mobil dapat menggunakan model ini untuk memilih kendaraan yang efisien dalam penggunaan bahan bakar, sehingga mengurangi biaya operasional jangka panjang.
2. **Perencanaan Produksi Otomotif:** Produsen mobil dapat 2Lamemanfaatkan wawasan dari model ini untuk merancang kendaraan dengan efisiensi bahan bakar yang lebih baik, memenuhi permintaan pasar akan kendaraan ramah lingkungan.
3. **Kebijakan Lingkungan:** Pemerintah dan lembaga terkait dapat menggunakan hasil analisis ini untuk menetapkan regulasi emisi dan standar efisiensi bahan bakar, mendukung upaya pengurangan jejak karbon.

**Referensi Terkait:**
- Dalam penelitian yang diterbitkan di *Jurnal Komputasi* pada tahun 2022, penulis membahas penggunaan algoritma regresi linear untuk memprediksi harga mobil bekas berdasarkan berbagai atribut kendaraan. Hasil penelitian menunjukkan bahwa model regresi linear dapat memberikan estimasi harga yang akurat, dengan tingkat akurasi mencapai 76%. 
EJOURNAL.JAK-STIK.AC.ID
- Artikel di *Jurnal Teknologi dan Sistem Komputer* pada tahun 2016 membahas analisis tingkat penerimaan calon konsumen terhadap jenis mobil menggunakan metode regresi linear. Penelitian ini menyoroti pentingnya memahami preferensi konsumen dalam industri otomotif dan bagaimana regresi linear dapat digunakan untuk menganalisis data tersebut. 
JOURNAL.UNNES.AC.ID
- Dalam studi yang dipublikasikan di *Jurnal Innovative* pada tahun 2023, penulis menggunakan model regresi linear untuk memprediksi penjualan mobil Toyota. Hasil penelitian menunjukkan bahwa model regresi linear dapat memprediksi penjualan dengan akurasi yang cukup baik, dengan rata-rata kesalahan mutlak (MAE) sebesar 2.617 unit penjualan dan rata-rata persentase kesalahan absolut (MAPE) sebesar 12,47%.

## Business Understanding

### Problem Statements
- Bagaimana memprediksi konsumsi bahan bakar mobil (miles per gallon) berdasarkan atribut kendaraan seperti displacement, jumlah silinder, tenaga kuda, berat, akselerasi, tahun model, dan asal mobil?
- Faktor-faktor apa saja yang paling berpengaruh terhadap efisiensi bahan bakar kendaraan?

### Goals
- Mengembangkan model regresi linear yang dapat memprediksi konsumsi bahan bakar mobil berdasarkan atribut-atribut yang tersedia.
- Mengidentifikasi atribut kendaraan yang memiliki pengaruh signifikan terhadap efisiensi bahan bakar.

### Solution statements
Untuk memprediksi konsumsi bahan bakar mobil (mpg) berdasarkan atribut seperti displacement, jumlah silinder, tenaga kuda, berat, akselerasi, tahun model, dan asal mobil, berikut adalah tiga pendekatan yang dapat dipertimbangkan:

**Regresi Linear** 
Pendekatan ini melibatkan penggunaan variabel independen untuk memprediksi variabel dependen. Misalnya, memodelkan hubungan antara berat kendaraan dan konsumsi bahan bakar. Meskipun sederhana, metode ini dapat memberikan wawasan awal mengenai pengaruh faktor tunggal terhadap mpg.
Pendekatan ini diimplementasikan menggunakan pustaka Deep Learning Neural Network seperti TensorFlow dalam Python untuk membangun dan mengevaluasi model prediksi  

## Data Understanding
Dataset ini terdiri dari 9 kolom dan 398 baris dengan 6 nilai kosong. Sumber dataset: Auto MPG - UCI Machine Learning Repository. link https://archive.ics.uci.edu/dataset/9/auto+mpg
Variabel-variabel pada Auto MPG dataset adalah sebagai berikut:
- Car Name: Nama mobil yang mencakup merek dan model.
- Cylinders: Jumlah silinder dalam mesin mobil.
- Displacement: Volume total dari semua silinder dalam satuan cubic inches (inci kubik).
- Horsepower: Tenaga mesin mobil yang diukur dalam horsepower (HP).
- Weight: Berat kendaraan dalam satuan pounds (lbs).
- Acceleration: Waktu yang dibutuhkan mobil untuk mencapai kecepatan 60 mph dari keadaan diam (dalam detik).
- Model Year: Tahun produksi mobil.
- Origin: Asal negara manufaktur mobil (1: USA, 2: Eropa, 3: Japan).
- MPG (Miles Per Gallon): Efisiensi bahan bakar, yang menunjukkan jarak yang dapat ditempuh mobil dalam satu galon bahan bakar.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

### Menghapus kolom yang tidak diperlukan
- Menghapus kolom seperti nama mobil karena tidak akan digunakan dalam pelatihan model
- mengubah tipe data kategorikal menjadi numerikal pada kolom origin guna untuk membuat model 
- membagi dataset menjadi 2 yaitu training dan testing
- Memisahkan antara variabel fitur dan labels
- menormalisasi fitur menggunakan library tensorflow
- membandingkan antara sebelum dan sesudah dinormalisasi

## Modeling
Membuat model deep neural network mengguanakan framework TensorFlow dengan loss mae dan optimizer Adam dengan learning rate 0.001

## Evaluation

Dalam proses analisis menggunakan model regresi, hasil error yang diperoleh adalah 1.7, yang mencerminkan tingkat perbedaan antara nilai prediksi dan nilai aktual dalam dataset, sehingga dapat dievaluasi lebih lanjut untuk meningkatkan akurasi model yang digunakan.


**---Ini adalah bagian akhir laporan---**
Kesimpulan dengan algoritma Neural network telah didapat model yang memiliki tingkat error 1.7.
Dari hasil analisis juga korelasi didapatkan bahwa Cylinders, Displacement, Horse power, dan Weight memiliki pengaruh terhadap penggunaan bahan bakar

