# Iklim Kabupaten Sleman 

## 📌 Deskripsi
Menganalisis klasifikasi intensitas curah hujan di Kabupaten Sleman, DIY untuk mendukung mitigasi risiko perubahan iklim. Proyek ini membandingkan dua arsitektur **Deep Learning** (RNN & LSTM) dalam mengolah data deret waktu (*time-series*) iklim historis periode **2014-2023**.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** NumPy, Pandas, TensorFlow (Sequential, SimpleRNN, LSTM, Dense, Dropout, Adam, EarlyStopping), Scikit-Learn (train_test_split, classification_report, accuracy_score, confusion_matrix), Matplotlib, Seaborn.
* **Environment:** Google Colab / Jupyter Notebook

## 📊 Tahapan Analisis
1. **Import Data** 
2. **Exploratory Data Analysis (EDA)** 
3. **Data Preprocessing & Cleaning** Penanganan *missing values* dan data anomali.
4. **Feature Engineering & Transformation** Transformasi fitur menggunakan **Min-Max Scaler**.
5. **Modeling** Konversi data ke format *3D Tensor* (Samples, Timesteps, Features).
6. **Evaluation** Implementasi *sliding window* untuk menangkap pola temporal.

## 📈 Hasil
- **Akurasi Model RNN: 75,34%**
- **Akurasi Model LSTM: 71,62%**
