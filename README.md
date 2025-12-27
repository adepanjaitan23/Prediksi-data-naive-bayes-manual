# 🧮 Prediksi Data: Naive Bayes Manual Implementation

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![NumPy](https://img.shields.io/badge/NumPy-Calculation-013243?style=for-the-badge&logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Repositori ini berisi implementasi algoritma **Naive Bayes Classifier** yang dibangun secara manual (step-by-step) untuk tujuan edukasi dan pemahaman mendalam tentang konsep probabilitas. Proyek ini menunjukkan bagaimana perhitungan *Posterior*, *Likelihood*, dan *Prior Probability* bekerja di balik layar tanpa langsung menggunakan fungsi instan dari library *Machine Learning*.

---

## 🌟 Fitur Utama

* **Perhitungan Manual:** Implementasi rumus Teorema Bayes langkah demi langkah.
    * $P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}$
* **Tanpa "Black Box":** Menghindari penggunaan fungsi `fit()` dan `predict()` instan dari Scikit-Learn untuk logika inti, sehingga alur matematika terlihat jelas.
* **Dukungan Data:** Mampu menangani dataset sederhana (kategorikal/numerik) untuk melakukan klasifikasi.
* **Visualisasi (Opsional):** Menampilkan distribusi data atau probabilitas kelas.

---

## 🛠️ Teknologi yang Digunakan

* **[Python](https://www.python.org/):** Bahasa pemrograman utama.
* **[Pandas](https://pandas.pydata.org/):** Untuk membaca dan memanipulasi dataset (DataFrame).
* **[NumPy](https://numpy.org/):** Melakukan operasi perhitungan numerik (seperti Mean, Standar Deviasi untuk Gaussian Naive Bayes).
* **[Jupyter Notebook](https://jupyter.org/):** Media interaktif untuk kode dan penjelasan.

---

## 📂 Susunan Proyek

```bash
Prediksi-data-naive-bayes-manual/
├── Prediksi_Naive_Bayes_Manual.ipynb  # 📓 File utama (Notebook) kode & analisis
├── dataset.csv                        # 📄 Dataset yang digunakan (jika ada)
└── README.md                          # 📄 Dokumentasi proyek ini
```
Catatan: Sesuaikan nama file .ipynb atau dataset di atas dengan file asli yang ada di folder Anda.

## ⚙️ Prasyarat Instalasi
Pastikan Anda memiliki lingkungan Python yang siap. Anda memerlukan library berikut:
```bash
pip install pandas numpy matplotlib jupyter
```

## 🚀 Cara Penggunaan
1. Clone Repositori
```bash
git clone [https://github.com/adepanjaitan23/Prediksi-data-naive-bayes-manual.git](https://github.com/adepanjaitan23/Prediksi-data-naive-bayes-manual.git)
cd Prediksi-data-naive-bayes-manual
```
2. Jalankan Jupyter Notebook
```bash
jupyter notebook
```
3. Eksekusi Program
* Buka file notebook yang tersedia.
* Jalankan sel (cell) satu per satu untuk melihat bagaimana data dimuat.
* Perhatikan bagian perhitungan Mean dan Stdev (jika Gaussian) atau frekuensi (jika Kategorikal).
* Lihat hasil prediksi akhir dibandingkan dengan label aslinya.
