# 🩺 Diabetes Prediction Using Machine Learning
## Gaussian Naive Bayes Classification  
### Universitas Amikom Yogyakarta


---

## 📌 Deskripsi Project
Project ini merupakan implementasi **Machine Learning untuk klasifikasi risiko penyakit diabetes** menggunakan dataset medis Pima Indians Diabetes.  
Model dibangun untuk memprediksi apakah seseorang berpotensi **diabetes atau non-diabetes** berdasarkan beberapa indikator kesehatan seperti kadar glukosa, BMI, tekanan darah, insulin, usia, dan riwayat keluarga.

Penelitian ini menerapkan tahapan **Data Preprocessing, Exploratory Data Analysis (EDA), Seleksi Fitur, Modeling, dan Evaluasi Model** dengan algoritma **Gaussian Naive Bayes**.

Project ini dibuat sebagai **Final Project / UAS Mata Kuliah Data Mining / Machine Learning – Universitas Amikom Yogyakarta**.

---

## 🎯 Tujuan
Mengembangkan model klasifikasi yang mampu:
- Memprediksi risiko diabetes secara otomatis
- Membantu proses screening awal pasien
- Menganalisis pengaruh fitur medis terhadap penyakit diabetes
- Mengimplementasikan teknik data mining pada kasus kesehatan

---

## 📂 Dataset
**Pima Indians Diabetes Dataset**  
Sumber: UCI Machine Learning Repository  

Berisi:
- 768 data pasien
- 8 fitur medis numerik
- 1 target kelas (Outcome)

### Fitur:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age
- Outcome (0 = Non-diabetes, 1 = Diabetes)

---

## ⚙️ Tahapan Project

### 1️⃣ Data Preprocessing
- Pembersihan missing value (nilai 0 tidak valid)
- Normalisasi fitur
- Train-test split (80:20)

### 2️⃣ Exploratory Data Analysis (EDA)
- Histogram distribusi fitur
- Boxplot deteksi outlier
- Heatmap korelasi fitur
- Distribusi kelas

### 3️⃣ Modeling
Algoritma:
- Gaussian Naive Bayes

Alasan:
- Cepat dan ringan
- Cocok untuk dataset kecil
- Sesuai asumsi independensi fitur

### 4️⃣ Evaluasi
Metode evaluasi:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📊 Hasil Evaluasi Model

| Metric | Nilai |
|--------|---------|
| Accuracy | 71% |
| Precision (Non-Diabetes) | 80% |
| Recall (Non-Diabetes) | 74% |
| F1-score (Non-Diabetes) | 77% |
| F1-score (Diabetes) | 61% |

### Confusion Matrix
[[74 26] <br>
[19 35]]
