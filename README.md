# 🛒 Shopee Review Sentiment Analysis using LSTM
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/)
[![Status](https://img.shields.io/badge/Status-Completed-green.svg)]()

Proyek ini adalah implementasi **Natural Language Processing (NLP)** untuk klasifikasi sentimen (Positif & Negatif) pada ulasan aplikasi Shopee. Model dibangun menggunakan arsitektur **Deep Learning LSTM (Long Short-Term Memory)** yang andal dalam memahami konteks urutan kata.

## 🚀 Fitur Utama
* **Automated Scraping**: Pengambilan data ulasan asli dari Google Play Store.
* **Text Preprocessing**: Pembersihan data, penanganan nilai kosong, dan pelabelan.
* **Deep Learning Model**: Arsitektur LSTM dengan akurasi validasi mencapai **~91%**.
* **Robust Inference**: Sistem prediksi ulasan baru menggunakan model yang telah disimpan (`.h5`).



## 📊 Analisis Performa
Berdasarkan hasil pelatihan selama 5 epoch:
* **Validation Accuracy**: Tetap stabil di angka **91%**, menunjukkan model memiliki generalisasi yang baik terhadap data baru (tidak overfitting).
* **Loss**: Penurunan loss yang signifikan pada data training dan validasi.

## 🛠️ Teknologi & Library
* **Language**: Python
* **Framework**: TensorFlow & Keras
* **Data Science**: Pandas, NumPy, Scikit-Learn
* **Visualization**: Matplotlib, Seaborn
* **Tool**: Google Colab

## 📂 Struktur File
* `Scraping_Data_Shopee_Ahmad_Faiq.ipynb`: Proses pengambilan data.
* `LSTM_Shopee_Reviews_Ahmad_Faiq.ipynb`: Notebook utama (Training & Inference).
* `dataset_shopee_reviews.csv`: Dataset ulasan (12.000+ baris).
* `model_sentimen_ahmad_faiq_zidane.h5`: Model tersimpan.
* `tokenizer.pickle`: Tokenizer untuk pemrosesan teks.
* `requirements.txt`: Daftar pustaka yang diperlukan.

## ⚙️ Instalasi & Penggunaan
1.  Instal library yang diperlukan:
    ```bash
    pip install -r requirements.txt
    ```
2.  Buka notebook `LSTM_Shopee_Reviews_Ahmad_Faiq.ipynb` di lingkungan Jupyter atau Google Colab.
3.  Jalankan cell pada bagian **Inference** untuk mencoba prediksi teks secara mandiri.

---

## 👨‍💻 Author
**Ahmad Faiq Zidane**
* Student at **Universitas Pendidikan Indonesia (UPI)**
* Mechatronics and Artificial Intelligence
* *"Fortis Fortuna Adiuvat"*

---
