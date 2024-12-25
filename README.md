# Proyek Penilaian Kualitas Udara

## Deskripsi Proyek
Proyek ini berfokus pada penilaian kualitas udara dengan memanfaatkan teknik machine learning tingkat lanjut. Aplikasi ini dirancang untuk memberikan antarmuka yang intuitif kepada pengguna agar dapat memahami klasifikasi kualitas udara berdasarkan fitur-fitur tertentu. Proyek ini dikembangkan untuk meningkatkan kesadaran terhadap tingkat polusi dan mendukung upaya pelestarian lingkungan.

## Dataset
Dataset yang digunakan dalam proyek ini diambil dari Kaggle: [Air Quality and Pollution Assessment](https://www.kaggle.com/datasets/mujtabamatin/air-quality-and-pollution-assessment). Dataset ini terdiri dari 4.000 data. Teknik augmentasi diterapkan pada data train, sehingga jumlah data train meningkat menjadi 1.100, yang bertujuan untuk meningkatkan performa dan ketahanan model.

## Dependensi
Aplikasi ini memerlukan beberapa pustaka Python berikut:
- **Streamlit**: Untuk membangun antarmuka web interaktif.
- **Joblib**: Untuk menyimpan dan memuat model machine learning.
- **NumPy**: Untuk manipulasi array numerik.
- **Pandas**: Untuk manipulasi dan analisis data.
- **Plotly**: Untuk visualisasi data yang interaktif.
- **Pathlib**: Untuk manajemen jalur file.
- **TensorFlow dan Keras**: Untuk membangun dan memuat model deep learning.

Semua pustaka ini dapat diinstal menggunakan file `requirements.txt` yang tersedia dalam repositori.

## Deskripsi Model
Proyek ini menggunakan dua model pembelajaran mesin untuk klasifikasi kualitas udara:
- **FeedForward Neural Network (FFNN)**: Model jaringan neural sederhana untuk pengolahan data tabular.
- **Random Forest**: Algoritma ensemble berbasis pohon keputusan untuk klasifikasi data tabular.

Kedua model ini dioptimalkan untuk menghasilkan prediksi kualitas udara dengan akurasi tinggi berdasarkan dataset yang telah diproses.

## Hasil dan Analisis
Bagian ini akan memuat visualisasi dan analisis performa model, termasuk akurasi, kurva loss, dan prediksi. (Akan ditambahkan kemudian.)

## Link Pembuatan Model
[Pembuatan Model RandoForest](https://colab.research.google.com/drive/1oWdJ6o3Q0Olz56l99KtgcY14z731-fXy?usp=sharing)
[Pembuatan Model Feed Forward Neural Network](https://colab.research.google.com/drive/1n58CBTxDErRA_gYWAJ0Oz9ePHVv1xyni?usp=sharing)

## Link Aplikasi Web
[Telusuri Aplikasi Web Streamlit](https://uapandiaswad.streamlit.app/)

## Tampilan Web
Tangkapan layar antarmuka akan ditambahkan di sini. (Akan ditambahkan kemudian.)

## Penulis
[Andi Aswad](https://github.com/AndiAswad)

