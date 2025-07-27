# Sentimen Analisis Review Tokopedia di Play Store

Proyek ini merupakan implementasi analisis sentimen terhadap ulasan pengguna aplikasi **Tokopedia** yang diambil dari **Google Play Store**. Tujuannya adalah untuk mengklasifikasikan sentimen ulasan pengguna ke dalam tiga kategori: **positif**, **netral**, dan **negatif**, menggunakan pendekatan Machine Learning dan Natural Language Processing (NLP).

## 📌 Tujuan Proyek

- Mengumpulkan dan membersihkan data ulasan pengguna Tokopedia.
- Melakukan eksplorasi dan visualisasi data untuk memahami distribusi dan karakteristik sentimen.
- Melatih model klasifikasi sentimen menggunakan pipeline NLP.
- Menyimpan dan melakukan inference model untuk keperluan prediksi lanjutan.

## 📁 Struktur Proyek

- `Pelatihan_Model_dan_Inference.ipynb`  
  Notebook utama yang memuat proses:
  - Preprocessing data teks
  - Ekstraksi fitur dengan TF-IDF
  - Pelatihan model (Logistic Regression)
  - Evaluasi model (akurasi, F1-score, confusion matrix)
  - Inference model pada data baru

## 🧪 Model yang Digunakan

- **TF-IDF Vectorizer** untuk representasi teks.
- **Logistic Regression** sebagai model klasifikasi utama.

## 📊 Evaluasi Model

Model dievaluasi menggunakan metrik berikut:

- **Akurasi**
- **F1-Score (macro average)**
- **Confusion Matrix**

Hasil evaluasi menunjukkan bahwa model mampu membedakan sentimen secara cukup baik, dengan performa yang stabil di semua kelas.

