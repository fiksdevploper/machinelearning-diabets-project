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

Anda dapat menginstal semua dependensi ini menggunakan `pip`:

```bash
pip install pandas seaborn matplotlib scikit-learn joblib
Instalasi
Clone repositori ini:

Bash

git clone [https://github.com/nama_pengguna_anda/nama_repositori_anda.git](https://github.com/nama_pengguna_anda/nama_repositori_anda.git)
cd nama_repositori_anda
(Ganti nama_pengguna_anda dan nama_repositori_anda dengan detail GitHub Anda)

Instal dependensi yang diperlukan (lihat Dependensi).

Penggunaan
Untuk menjalankan dan bereksperimen dengan kode, ikuti langkah-langkah berikut:

Buka notebook Jupyter:
Bash

jupyter notebook
Pilih machine_learning_diabets.ipynb dari antarmuka Jupyter.
Jalankan setiap sel dalam notebook secara berurutan.
Notebook ini akan memuat data, melatih model Regresi Logistik, mengevaluasinya, dan menyimpan model yang telah dilatih sebagai diabetes_model.pkl.

Hasil
Setelah menjalankan notebook, Anda akan melihat output yang menunjukkan kinerja model, termasuk akurasi, confusion matrix, dan classification report pada test set.

Contoh output evaluasi model:

Acuraty: 0.7709
[[139  18]
 [ 26  29]]

Classification Report
              precision    recall  f1-score   support

           0       0.84      0.89      0.86       157
           1       0.62      0.53      0.57        55

    accuracy                           0.77       212
   macro avg       0.73      0.71      0.72       212
weighted avg       0.77      0.77      0.77       212
Catatan: Angka-angka ini adalah contoh dan mungkin sedikit berbeda saat Anda menjalankannya.

Model yang Disimpan
Model Regresi Logistik yang telah dilatih disimpan sebagai diabetes_model.pkl. Anda dapat memuat model ini untuk membuat prediksi baru tanpa perlu melatih ulang:

Python

import joblib

# Muat model
loaded_model = joblib.load('diabetes_model.pkl')

# Contoh prediksi (ganti dengan data input Anda)
# new_data = [[jumlah_kehamilan, glukosa, tekanan_darah, ...]]
# prediction = loaded_model.predict(new_data)
# print(prediction)
Kontribusi
Kontribusi dipersilakan! Jika Anda ingin berkontribusi pada proyek ini, silakan fork repositori dan ajukan pull request.

Lisensi
Proyek ini dilisensikan di bawah lisensi MIT. Lihat file LICENSE (jika ada, atau tambahkan jika diperlukan) untuk detail lebih lanjut.


**Penting:**

1.  **Ganti Placeholder**: Pastikan untuk mengganti `https://github.com/nama_pengguna_anda/nama_repositori_anda.git` dengan URL repositori GitHub Anda yang sebenarnya setelah Anda membuatnya.
2.  **File `LICENSE`**: Jika Anda memiliki file lisensi terpisah (misalnya `LICENSE.md`), sebutkan itu di bagian "Lisensi". Jika tidak, Anda bisa menghapus baris tersebut atau membuatnya.
3.  **Contoh Output**: Saya menyertakan contoh *output* dari evaluasi model yang terlihat di *notebook* Anda. Ini sangat membantu pengguna lain untuk memahami apa yang akan mereka dapatkan.

Semoga ini sangat jelas dan membantu untuk `README.md` GitHub Anda!

Sumber

tolong rubah semua hasil deskripsi itu menjadi format README.md



Tentu, saya akan langsung memberikan output dalam format README.md berdasarkan deskripsi yang telah kita buat sebelumnya. Ini adalah file README.md lengkap yang bisa langsung Anda gunakan.

Markdown

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

Anda dapat menginstal semua dependensi ini menggunakan `pip`:

```bash
pip install pandas seaborn matplotlib scikit-learn joblib
Instalasi
Clone repositori ini:

Bash

git clone [https://github.com/nama_pengguna_anda/nama_repositori_anda.git](https://github.com/nama_pengguna_anda/nama_repositori_anda.git)
cd nama_repositori_anda
(Ganti nama_pengguna_anda dan nama_repositori_anda dengan detail GitHub Anda)

Instal dependensi yang diperlukan (lihat Dependensi).

Penggunaan
Untuk menjalankan dan bereksperimen dengan kode, ikuti langkah-langkah berikut:

Buka notebook Jupyter:
Bash

jupyter notebook
Pilih machine_learning_diabets.ipynb dari antarmuka Jupyter.
Jalankan setiap sel dalam notebook secara berurutan.
Notebook ini akan memuat data, melatih model Regresi Logistik, mengevaluasinya, dan menyimpan model yang telah dilatih sebagai diabetes_model.pkl.

Hasil
Setelah menjalankan notebook, Anda akan melihat output yang menunjukkan kinerja model, termasuk akurasi, confusion matrix, dan classification report pada test set.

Contoh output evaluasi model:

Acuraty: 0.7709
[[139  18]
 [ 26  29]]

Classification Report
              precision    recall  f1-score   support

           0       0.84      0.89      0.86       157
           1       0.62      0.53      0.57        55

    accuracy                           0.77       212
   macro avg       0.73      0.71      0.72       212
weighted avg       0.77      0.77      0.77       212
Catatan: Angka-angka ini adalah contoh dan mungkin sedikit berbeda saat Anda menjalankannya.

Model yang Disimpan
Model Regresi Logistik yang telah dilatih disimpan sebagai diabetes_model.pkl. Anda dapat memuat model ini untuk membuat prediksi baru tanpa perlu melatih ulang:

Python

import joblib

# Muat model
loaded_model = joblib.load('diabetes_model.pkl')

# Contoh prediksi (ganti dengan data input Anda)
# new_data = [[jumlah_kehamilan, glukosa, tekanan_darah, ...]]
# prediction = loaded_model.predict(new_data)
# print(prediction)
Kontribusi
Kontribusi dipersilakan! Jika Anda ingin berkontribusi pada proyek ini, silakan fork repositori dan ajukan pull request.

Lisensi
Proyek ini dilisensikan di bawah lisensi MIT. Lihat file LICENSE (jika ada, atau tambahkan jika diperlukan) untuk detail lebih lanjut.


Sumber
