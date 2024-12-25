# Proyek Penilaian Kualitas Udara

## Deskripsi Proyek
Proyek ini berfokus pada penilaian kualitas udara dengan memanfaatkan teknik machine learning tingkat lanjut. Aplikasi ini dirancang untuk memberikan antarmuka yang intuitif kepada pengguna agar dapat memahami klasifikasi kualitas udara berdasarkan fitur-fitur tertentu. Proyek ini dikembangkan untuk meningkatkan kesadaran terhadap tingkat polusi dan mendukung upaya pelestarian lingkungan.

## Dataset
Dataset yang digunakan dalam proyek ini diambil dari Kaggle: [Air Quality and Pollution Assessment](https://www.kaggle.com/datasets/mujtabamatin/air-quality-and-pollution-assessment). Dataset ini terdiri dari 4.000 data. Teknik augmentasi diterapkan pada data train, sehingga jumlah data train meningkat menjadi 1.100, yang bertujuan untuk meningkatkan performa dan ketahanan model.

## Instalasi
Untuk menginstal dan menjalankan aplikasi ini:
1. Clone repositori:
   ```bash
   git clone https://github.com/yourusername/project-repo-name.git
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd project-repo-name
   ```
3. Instal dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Jalankan aplikasi:
   ```bash
   streamlit run app.py
   ```
Atau, akses aplikasi web yang dihosting di Streamlit Cloud.

## Deskripsi Model
Proyek ini menggunakan dua model transfer learning untuk klasifikasi kualitas udara:
- **GoogLeNet**: Arsitektur jaringan neural convolutional yang dikenal efisien dan akurat.
- **VGG16**: Arsitektur transfer learning lain yang terkenal karena kesederhanaan dan efektivitasnya.

Kedua model tersebut di-fine-tune untuk mengklasifikasikan kualitas udara berdasarkan dataset yang telah diaugmentasi.

## Hasil dan Analisis
Bagian ini akan memuat visualisasi dan analisis performa model, termasuk akurasi, kurva loss, dan prediksi. (Akan ditambahkan kemudian.)

## Link Pembuatan Model
[Klik di sini untuk mengakses proses pembuatan model](#)

## Link Aplikasi Web
[Telusuri Aplikasi Web Streamlit](https://uapandiaswad.streamlit.app/)

## Tampilan Web
Tangkapan layar antarmuka akan ditambahkan di sini. (Akan ditambahkan kemudian.)

## Penulis
[Andi Aswad](https://github.com/AndiAswad)

