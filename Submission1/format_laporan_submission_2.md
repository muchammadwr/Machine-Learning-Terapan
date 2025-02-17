# Laporan Prediksi Konsumsi Bahan Bakar Mobil Menggunakan Neural Network Regresi Linear - Muchammad Wildan Alkautsar

## Project Overview
**Deskripsi Proyek**: Proyek ini bertujuan untuk membangun model regresi linear yang dapat memprediksi konsumsi bahan bakar mobil (miles per gallon/miles per gallon) berdasarkan atribut-atribut seperti displacement, jumlah silinder, tenaga kuda, berat, akselerasi, tahun model, dan asal mobil. Dataset yang digunakan berasal dari repositori UCI Machine Learning, yang menyediakan data historis mengenai berbagai karakteristik mobil.

**Pentingnya Proyek:** Memahami faktor-faktor yang memengaruhi konsumsi bahan bakar mobil sangat penting untuk berbagai tujuan, termasuk:

1. **Pengambilan Keputusan Pembelian:** Calon pembeli mobil dapat menggunakan model ini untuk memilih kendaraan yang efisien dalam penggunaan bahan bakar, sehingga mengurangi biaya operasional jangka panjang.

2. **Perencanaan Produksi Otomotif:** Produsen mobil dapat memanfaatkan wawasan dari model ini untuk merancang kendaraan dengan efisiensi bahan bakar yang lebih baik, memenuhi permintaan pasar akan kendaraan ramah lingkungan.

3. **Kebijakan Lingkungan:** Pemerintah dan lembaga terkait dapat menggunakan hasil analisis ini untuk menetapkan regulasi emisi dan standar efisiensi bahan bakar, mendukung upaya pengurangan jejak karbon.

**Referensi Terkait:**

- Dalam penelitian yang diterbitkan di *Jurnal Komputasi* pada tahun 2022, penulis membahas penggunaan algoritma regresi linear untuk memprediksi harga mobil bekas berdasarkan berbagai atribut kendaraan. Hasil penelitian menunjukkan bahwa model regresi linear dapat memberikan estimasi harga yang akurat, dengan tingkat akurasi mencapai 76%. 
EJOURNAL.JAK-STIK.AC.ID

- Artikel di *Jurnal Teknologi dan Sistem Komputer* pada tahun 2016 membahas analisis tingkat penerimaan calon konsumen terhadap jenis mobil menggunakan metode regresi linear. Penelitian ini menyoroti pentingnya memahami preferensi konsumen dalam industri otomotif dan bagaimana regresi linear dapat digunakan untuk menganalisis data tersebut. 
JOURNAL.UNNES.AC.ID

- Dalam studi yang dipublikasikan di *Jurnal Innovative* pada tahun 2023, penulis menggunakan model regresi linear untuk memprediksi penjualan mobil Toyota. Hasil penelitian menunjukkan bahwa model regresi linear dapat memprediksi penjualan dengan akurasi yang cukup baik, dengan rata-rata kesalahan mutlak (MAE) sebesar 2.617 unit penjualan dan rata-rata persentase kesalahan absolut (MAPE) sebesar 12,47%.
## Business Understanding

Pada bagian ini, Anda perlu menjelaskan proses klarifikasi masalah.

Bagian laporan ini mencakup:

### Problem Statements

Menjelaskan pernyataan masalah:
- Pernyataan Masalah 1
- Pernyataan Masalah 2
- Pernyataan Masalah n

### Goals

Menjelaskan tujuan proyek yang menjawab pernyataan masalah:
- Jawaban pernyataan masalah 1
- Jawaban pernyataan masalah 2
- Jawaban pernyataan masalah n

Semua poin di atas harus diuraikan dengan jelas. Anda bebas menuliskan berapa pernyataan masalah dan juga goals yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**:
- Menambahkan bagian “Solution Approach” yang menguraikan cara untuk meraih goals. Bagian ini dibuat dengan ketentuan sebagai berikut: 

### Solution statements
- Mengajukan 2 atau lebih solution approach (algoritma atau pendekatan sistem rekomendasi).

## Data Understanding
Paragraf awal bagian ini menjelaskan informasi mengenai jumlah data, kondisi data, dan informasi mengenai data yang digunakan. Sertakan juga sumber atau tautan untuk mengunduh dataset. Contoh: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Restaurant+%26+consumer+data).

Selanjutnya, uraikanlah seluruh variabel atau fitur pada data. Sebagai contoh:  

Variabel-variabel pada Restaurant UCI dataset adalah sebagai berikut:
- accepts : merupakan jenis pembayaran yang diterima pada restoran tertentu.
- cuisine : merupakan jenis masakan yang disajikan pada restoran.
- dst

**Rubrik/Kriteria Tambahan (Opsional)**:
- Melakukan beberapa tahapan yang diperlukan untuk memahami data, contohnya teknik visualisasi data beserta insight atau exploratory data analysis.

## Data Preparation
Pada bagian ini Anda menerapkan dan menyebutkan teknik data preparation yang dilakukan. Teknik yang digunakan pada notebook dan laporan harus berurutan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan proses data preparation yang dilakukan
- Menjelaskan alasan mengapa diperlukan tahapan data preparation tersebut.

## Modeling
Tahapan ini membahas mengenai model sisten rekomendasi yang Anda buat untuk menyelesaikan permasalahan. Sajikan top-N recommendation sebagai output.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menyajikan dua solusi rekomendasi dengan algoritma yang berbeda.
- Menjelaskan kelebihan dan kekurangan dari solusi/pendekatan yang dipilih.

## Evaluation
Pada bagian ini Anda perlu menyebutkan metrik evaluasi yang digunakan. Kemudian, jelaskan hasil proyek berdasarkan metrik evaluasi tersebut.

Ingatlah, metrik evaluasi yang digunakan harus sesuai dengan konteks data, problem statement, dan solusi yang diinginkan.

**Rubrik/Kriteria Tambahan (Opsional)**: 
- Menjelaskan formula metrik dan bagaimana metrik tersebut bekerja.

**---Ini adalah bagian akhir laporan---**

_Catatan:_
- _Anda dapat menambahkan gambar, kode, atau tabel ke dalam laporan jika diperlukan. Temukan caranya pada contoh dokumen markdown di situs editor [Dillinger](https://dillinger.io/), [Github Guides: Mastering markdown](https://guides.github.com/features/mastering-markdown/), atau sumber lain di internet. Semangat!_
- Jika terdapat penjelasan yang harus menyertakan code snippet, tuliskan dengan sewajarnya. Tidak perlu menuliskan keseluruhan kode project, cukup bagian yang ingin dijelaskan saja.
