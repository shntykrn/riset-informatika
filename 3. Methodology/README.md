BAB III – METODOLOGI PENELITIAN

3.1 Jenis Penelitian
Penelitian ini bersifat kuantitatif eksperimental dengan pendekatan supervised learning untuk membangun dan mengevaluasi model prediksi waktu kelulusan mahasiswa.

3.2 Tahapan Penelitian
1. Pengumpulan Data: Mengambil data akademik mahasiswa (nyata atau simulasi).
2. Preprocessing: Pembersihan dan transformasi data ke format survival.
3. Pembagian Dataset: Training 80%, testing 20%.
4. Penerapan Model: Cox Proportional Hazard dan Gradient Boosting.
5. Evaluasi Model: Menggunakan C-index dan Brier Score.
6. Implementasi Sistem: Antarmuka sederhana berbasis Streamlit atau Flask.

3.3 Alat dan Bahasa Pemrograman
Bahasa: Python
Library: pandas, numpy, matplotlib, lifelines, scikit-survival, xgboost, sklearn.
3.4 Hasil yang Diharapkan
1. Model prediksi kelulusan dengan akurasi tinggi (C-index ≥ 0.80).
2. Visualisasi faktor-faktor yang berpengaruh terhadap kelulusan.
3. Rekomendasi strategis bagi kampus untuk intervensi dini mahasiswa berisiko.
