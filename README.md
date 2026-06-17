# Tugas Besar ANN - Klasifikasi Dry Bean Dataset

Implementasi Artificial Neural Network (ANN) untuk klasifikasi multiclass jenis kacang kering (Dry Bean Dataset) menggunakan dua pendekatan: from scratch (NumPy) dan framework Keras.

## Deskripsi

Proyek ini bertujuan untuk memahami cara kerja Neural Network secara mendalam dengan membangun ANN tanpa library deep learning, kemudian membandingkannya dengan implementasi menggunakan Keras dan Sklearn.

**Dataset:** Dry Bean Dataset (13.611 sampel, 16 fitur, 7 kelas)

## Struktur Folder
├── src/
│   └── notebooks/
├── doc/
└── README.md

## Cara Setup & Run

1. Buka file notebook di folder `src/notebooks/` menggunakan Google Colab
2. Upload dataset `Dry_Bean_Dataset.xlsx` ke session Colab
3. Jalankan semua cell secara berurutan (Runtime → Run all)

## Library yang Digunakan

- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow/Keras

## Hasil Eksperimen Utama

| Model | Test Accuracy |
|-------|---------------|
| ANN From Scratch | 92.62% |
| Keras | 92.62% |
| Sklearn MLPClassifier | 92.25% |

## Pembagian Tugas

## Pembagian Tugas

| Nama                  | NIM        | Tugas                                                               |
|-----------------------|------------|---------------------------------------------------------------------|
| Ahmad Aqil Almutashim | 2403029828 | Eksperimen & visualisasi (arsitektur, aktivasi, learning rate, dst) |
| Suhaila Ade Syafiqa   | 2403020048 | Implementasi ANN from scratch (init, forward, backward)             |
| Hanif Hidayatullah    | 2403020041 | Implementasi Keras, perbandingan Sklearn, laporan PDF               |

## Referensi

- Koklu, M. and Ozkan, I.A., (2020) Multiclass Classification of Dry Beans Using Computer Vision and Machine Learning Techniques. Computers and Electronics in Agriculture, 174, 105507.
