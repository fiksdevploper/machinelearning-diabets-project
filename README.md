# Prediksi Diabetes Menggunakan Machine Learning

Repositori ini berisi *notebook* Jupyter (`machine_learning_diabets.ipynb`) yang mendemonstrasikan proses pembangunan model *machine learning* untuk memprediksi diabetes. Model ini dikembangkan menggunakan dataset Pima Indians Diabetes.

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
.
├── machine_learning_diabets.ipynb
├── diabetes_model.pkl
└── README.md


* `machine_learning_diabets.ipynb`: *Notebook* Jupyter utama yang berisi seluruh kode untuk analisis data, pelatihan model, dan evaluasi.
* `diabetes_model.pkl`: File model Regresi Logistik yang telah dilatih dan disimpan.
* `README.md`: File deskripsi proyek ini.

## Dependensi

Proyek ini membutuhkan pustaka Python berikut:

* `pandas`
* `seaborn`
* `matplotlib`
* `scikit-learn`
* `joblib`

## Hasil Model Machine Learning (Classification Report)

### Confusion Matrix

| Prediksi \ Aktual | Kelas 0 | Kelas 1 |
|-------------------|---------|---------|
| **Kelas 0** | 106     | 45      |
| **Kelas 1** | 21      | 59      |

Akurasi: 0.7143
