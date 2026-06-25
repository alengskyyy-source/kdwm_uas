# 📊 Estimasi COVID-19 Indonesia Menggunakan Regresi Linear

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![CRISP-DM](https://img.shields.io/badge/Methodology-CRISP--DM-red)

## 📖 Deskripsi Project

Project ini merupakan implementasi metode **Data Mining** untuk melakukan **estimasi data COVID-19 di Indonesia** menggunakan algoritma **Linear Regression** dengan pendekatan **CRISP-DM (Cross Industry Standard Process for Data Mining)**.

Tujuan utama dari proyek ini adalah membangun model estimasi yang mampu memprediksi nilai berdasarkan pola historis pada dataset COVID-19 serta mengevaluasi performa model menggunakan berbagai metrik evaluasi.

---

## 🎯 Tujuan Project

* Melakukan analisis data COVID-19 Indonesia.
* Membersihkan dan mempersiapkan data sebelum pemodelan.
* Mengidentifikasi hubungan antar variabel menggunakan korelasi.
* Membangun model estimasi menggunakan Linear Regression.
* Mengevaluasi performa model menggunakan MAE, RMSE, dan R² Score.
* Menampilkan visualisasi hasil prediksi.

---

## 🧠 Metodologi

Project ini menggunakan pendekatan **CRISP-DM** yang terdiri dari:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment (Dokumentasi Hasil)

---

## 📂 Struktur Repository

```text
kdwm_uas/
│
├── ESTIMASI DATA_SEAT.xlsx
├── Estimasi_COVID19_Indonesia_CRISPDM_Penjelasan.ipynb
└── README.md
```

---

## 🔧 Library yang Digunakan

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## 🔄 Tahapan Analisis

### 1. Import Library

Mengimpor seluruh library yang diperlukan untuk pengolahan data, visualisasi, dan pemodelan.

### 2. Load Dataset

Membaca dataset dari file Excel menggunakan Pandas.

### 3. Data Understanding

Melakukan eksplorasi data menggunakan:

* `df.info()`
* `df.describe()`

### 4. Data Cleaning

Membersihkan data yang tidak sesuai dan memastikan kualitas data sebelum pemodelan.

### 5. Pemilihan Variabel

Menentukan variabel independen dan dependen yang digunakan dalam model estimasi.

### 6. Analisis Korelasi

Melakukan analisis hubungan antar variabel menggunakan:

* Correlation Matrix
* Heatmap Correlation

### 7. Modelling

Membangun model estimasi menggunakan algoritma:

**Linear Regression**

### 8. Prediksi dan Evaluasi

Evaluasi model dilakukan menggunakan:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 9. Kesimpulan

Menyimpulkan hasil analisis dan performa model yang telah dibangun.

---

## 📈 Output Project

Project menghasilkan:

* Analisis Data COVID-19 Indonesia
* Model Estimasi Linear Regression
* Visualisasi Korelasi
* Visualisasi Prediksi
* Nilai Evaluasi Model

---

## 🚀 Cara Menjalankan Project

### Clone Repository

```bash
git clone https://github.com/alengskyyy-source/kdwm_uas.git
```

### Masuk ke Folder Project

```bash
cd kdwm_uas
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

### Jalankan Notebook

```bash
jupyter notebook
```

Kemudian buka file:

```text
Estimasi_COVID19_Indonesia_CRISPDM_Penjelasan.ipynb
```

---

## 🔗 Informasi Project

| Resource                 | Link                                          |
| ------------------------ | --------------------------------------------- |
| Repository GitHub        | https://github.com/alengskyyy-source/kdwm_uas |
| Video Presentasi YouTube | Isi Link YouTube Anda                         |
| Google Sites             | Isi Link Google Sites Anda                    |
| GitHub Profile           | https://github.com/alengskyyy-source          |

---

## 👨‍💻 Author

**M. Adi Setyawan**

Mahasiswa Sistem Informasi yang memiliki minat pada bidang:

* Data Mining
* Data Analysis
* Machine Learning
* Business Intelligence
* Web Development

---

## 📝 License

Project ini dibuat untuk memenuhi tugas Ujian Akhir Semester (UAS) dan tujuan pembelajaran akademik.
