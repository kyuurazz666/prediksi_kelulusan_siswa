# 🎓 Prediksi Kelulusan Siswa Menggunakan Random Forest Classifier

Proyek ini merupakan implementasi **Machine Learning** untuk memprediksi **kelulusan siswa** berdasarkan faktor akademik dan sosial menggunakan algoritma **Random Forest Classifier**.  
Aplikasi ini dibangun menggunakan **Python** dan **Flask**, serta dapat dijalankan sebagai aplikasi web interaktif yang menampilkan hasil prediksi secara langsung berdasarkan input pengguna.

---

## 📘 Deskripsi Proyek

Sistem ini dikembangkan dengan tujuan membantu guru, konselor, atau lembaga pendidikan dalam memprediksi kemungkinan kelulusan siswa berdasarkan nilai akademik serta beberapa faktor sosial seperti:
- Nilai Matematika
- Nilai Membaca
- Nilai Menulis
- Jenis Kelamin
- Tingkat Pendidikan Orang Tua
- Jenis Makan Siang
- Keikutsertaan dalam Kursus Persiapan Ujian

Model yang digunakan adalah **Random Forest Classifier**, yang dilatih menggunakan dataset publik dari Kaggle — *Students Performance Dataset*.

Dataset asli dapat diunduh di sini:  
📂 [Students Performance Dataset - Kaggle](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---

## 🧩 Fitur Utama

- 🔍 Prediksi kelulusan siswa menggunakan algoritma **Random Forest**
- 📊 Visualisasi hasil model (Confusion Matrix, ROC Curve, Feature Importance)
- 🌐 Aplikasi web berbasis **Flask**
- 💾 Model disimpan dan dimuat menggunakan **Joblib**
- ☁️ Dapat di-deploy ke platform seperti **Render** atau **Railway**

---

## 🧠 Arsitektur Sistem

1. **Preprocessing Data**  
   Data dibersihkan dan diubah menjadi format numerik agar dapat diproses oleh model Random Forest.

2. **Training Model**  
   Model dilatih dengan menggunakan 80% data pelatihan dan 20% data pengujian.

3. **Evaluasi Model**  
   Performa dievaluasi menggunakan *accuracy*, *precision*, *recall*, *F1-score*, dan *ROC-AUC*.

4. **Deployment Model**  
   Model disimpan (`model_bundle.joblib`) dan diintegrasikan dengan aplikasi Flask untuk prediksi real-time.

---

## 🧰 Teknologi yang Digunakan

| Kategori | Teknologi |
|-----------|------------|
| Bahasa Pemrograman | Python 3.12 |
| Framework | Flask |
| Library ML | Scikit-Learn, Pandas, NumPy |
| Visualisasi | Matplotlib, Seaborn |
| Deployment | Render / Railway |
| Penyimpanan Model | Joblib |

---

## 🗂️ Struktur Proyek

