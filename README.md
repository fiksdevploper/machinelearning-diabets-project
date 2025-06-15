# Prediksi Diabetes Menggunakan Machine Learning

Repositori ini berisi *notebook* Jupyter (`machine_learning_diabets.ipynb`) yang mendemonstrasikan proses pembangunan model *machine learning* untuk memprediksi diabetes. Model ini dikembangkan menggunakan dataset Pima Indians Diabetes.

## Daftar Isi

- [Prediksi Diabetes Menggunakan Machine Learning](#prediksi-diabetes-menggunakan-machine-learning)
  - [Daftar Isi](#daftar-isi)
  - [Tentang Proyek Ini](#tentang-proyek-ini)
  - [Dataset](#dataset)
  - [Struktur Proyek](#struktur-proyek)
  - [Dependensi](#dependensi)
  - [Instalasi](#instalasi)
  - [Penggunaan](#penggunaan)
  - [Hasil](#hasil)
  - [Model yang Disimpan](#model-yang-disimpan)
  - [Kontribusi](#kontribusi)
  - [Lisensi](#lisensi)

## Tentang Proyek Ini

Proyek ini bertujuan untuk membangun dan mengevaluasi model klasifikasi yang mampu memprediksi apakah seseorang mengidap diabetes berdasarkan beberapa fitur diagnostik. Tahapan yang dilakukan meliputi:

1.  **Pemuatan dan Eksplorasi Data**: Memahami struktur dataset, statistik deskriptif, dan distribusi fitur.
2.  **Pra-pemrosesan Data**: Penanganan nilai yang hilang (jika ada), *encoding* variabel kategorikal (jika ada), dan penskalaan fitur.
3.  **Pembagian Data**: Membagi dataset menjadi *training set* dan *test set*.
4.  **Pelatihan Model**: Melatih model Regresi Logistik.
5.  **Evaluasi Model**: Mengevaluasi kinerja model menggunakan metrik seperti akurasi, *confusion matrix*, dan *classification report*.
6.  **Penyimpanan Model**: Menyimpan model yang telah dilatih untuk penggunaan di masa mendatang.

## Dataset

Dataset yang digunakan adalah Pima Indians Diabetes Dataset, yang tersedia secara luas untuk tugas klasifikasi. Dataset ini berisi informasi diagnostik berikut:

* `Pregnancies`: Jumlah kehamilan
* `Glucose`: Konsentrasi glukosa plasma 2 jam dalam tes toleransi glukosa oral
* `BloodPressure`: Tekanan darah diastolik (mm Hg)
* `SkinThickness`: Ketebalan lipatan kulit trisep (mm)
* `Insulin`: Insulin serum 2 jam (mu U/ml)
* `BMI`: Indeks massa tubuh (berat dalam kg/(tinggi dalam m)^2)
* `DiabetesPedigreeFunction`: Fungsi silsilah diabetes
* `Age`: Usia (tahun)
* `Outcome`: Variabel kelas (0: tidak diabetes, 1: diabetes)

## Struktur Proyek
