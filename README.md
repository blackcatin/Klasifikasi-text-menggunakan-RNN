# 📑 Klasifikasi Teks dengan RNN-LSTM

Proyek ini mendemonstrasikan cara membangun model **Recurrent Neural Network (RNN)** dengan **Long Short-Term Memory (LSTM)** untuk tugas **klasifikasi teks (spam vs ham)** menggunakan dataset SMS.  

Model dilatih menggunakan embedding layer, LSTM layer, dan dense layer dengan output sigmoid untuk klasifikasi biner.  

---

## 🎯 Tujuan Proyek
- Membangun pipeline NLP sederhana untuk deteksi spam.
- Melakukan pra-pemrosesan teks: tokenisasi, padding, dan label encoding.
- Mengimplementasikan model berbasis LSTM dengan TensorFlow/Keras.
- Mengevaluasi performa model dengan akurasi dan confusion matrix.

---

# Struktur Proyek
.
├── klasifikasi_teks_rnn.ipynb # Notebook utama
├── README.md # Dokumentasi
└── Laporan_Klasifikasi_Text_RNN_FirlanaUmiAzzakiy

---

## 📊 Dataset
Dataset yang digunakan: [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
- **ham**: pesan normal  
- **spam**: pesan iklan/spam  

Dataset diproses dengan tokenisasi, padding, dan encoding label sebelum masuk ke model.

---

## ⚙️ Instalasi & Cara Menjalankan

### 1. Clone repository (opsional)
```bash
git clone <repo-url>
cd klasifikasi-teks-rnn

