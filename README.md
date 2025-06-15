# Analisis dan Prediksi Diabetes dengan Penanganan Underfitting & Overfitting

Proyek ini bertujuan untuk membangun model machine learning yang dapat memprediksi diabetes menggunakan dataset Pima Indians Diabetes. Fokus utama dari proyek ini adalah bagaimana menangani masalah *underfitting* dan *overfitting* yang umum terjadi dalam pengembangan model machine learning untuk mencapai performa yang optimal.

## Ikhtisar Proyek

Dalam proyek ini, kami melakukan langkah-langkah berikut:

1.  **Memuat dan Memahami Data**: Memuat dataset diabetes dan melakukan eksplorasi awal untuk memahami struktur data dan karakteristiknya.
2.  **Pra-pemrosesan Data**: Menangani nilai-nilai yang hilang atau tidak valid, dan mempersiapkan data untuk pelatihan model.
3.  **Pembagian Data**: Memisahkan dataset menjadi data pelatihan dan data pengujian.
4.  **Pelatihan Model Regresi Logistik**: Melatih model Regresi Logistik untuk memprediksi diabetes.
5.  **Evaluasi Model**: Mengevaluasi performa model menggunakan metrik seperti akurasi, confusion matrix, dan classification report.
6.  **Penanganan Underfitting & Overfitting (Cross-Validation)**: Menggunakan Cross-Validation untuk mengidentifikasi dan mengurangi masalah underfitting atau overfitting, sehingga model menjadi lebih generalis.
7.  **Penyimpanan Model**: Menyimpan model terbaik yang telah dilatih untuk penggunaan di masa mendatang.

## Dataset

Dataset yang digunakan adalah "Pima Indians Diabetes Dataset" yang berisi informasi medis berikut:

* `Pregnancies`: Jumlah kehamilan
* `Glucose`: Konsentrasi glukosa plasma 2 jam dalam tes toleransi glukosa oral
* `BloodPressure`: Tekanan darah diastolik (mm Hg)
* `SkinThickness`: Ketebalan lipatan kulit trisep (mm)
* `Insulin`: Insulin serum 2 jam (mu U/ml)
* `BMI`: Indeks massa tubuh (berat dalam kg/(tinggi dalam m)^2)
* `DiabetesPedigreeFunction`: Fungsi silsilah diabetes
* `Age`: Usia (tahun)
* `Outcome`: Variabel kelas (1 jika diabetes, 0 jika tidak diabetes)

## Struktur Repositori

* `machine_learning_diabets.ipynb`: Notebook Jupyter yang berisi semua kode untuk analisis data, pelatihan model, penanganan underfitting/overfitting, dan evaluasi.
* `diabetes_model.pkl`: File model yang disimpan setelah pelatihan.

## Cara Menjalankan

Untuk menjalankan notebook ini, Anda memerlukan lingkungan Python dengan pustaka-pustaka berikut:

* `pandas`
* `seaborn`
* `matplotlib`
* `scikit-learn`
* `joblib`

Anda dapat menginstal dependensi ini menggunakan pip:

```bash
pip install pandas seaborn matplotlib scikit-learn joblib
