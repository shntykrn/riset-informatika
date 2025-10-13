BAB I – PENDAHULUAN

1.1 Latar Belakang
Ketepatan waktu kelulusan mahasiswa merupakan salah satu indikator penting dalam menilai efektivitas sistem pendidikan tinggi. Universitas di seluruh dunia, termasuk di Indonesia, menghadapi tantangan dalam memantau dan memprediksi lama studi mahasiswa. Beberapa faktor seperti prestasi akademik, kehadiran, jumlah cuti, dan IPK kumulatif terbukti memengaruhi durasi studi. Namun, dalam praktiknya, sulit bagi pihak akademik untuk mengidentifikasi secara dini mahasiswa yang berpotensi mengalami keterlambatan kelulusan.

Seiring perkembangan teknologi, metode machine learning (ML) dan analisis survival (survival analysis) memberikan pendekatan baru dalam memprediksi time-to-event, yaitu lamanya waktu sampai suatu peristiwa terjadi. Dalam konteks ini, 'peristiwa' yang dimaksud adalah kelulusan mahasiswa. Metode survival analysis mampu menangani data yang belum mengalami kejadian (censored data), misalnya mahasiswa yang masih aktif.

Selain itu, penggunaan Gradient Boosting (seperti XGBoost atau Gradient Boosted Trees) dapat meningkatkan akurasi prediksi dengan menggabungkan beberapa model lemah menjadi model yang lebih kuat. Kombinasi kedua pendekatan ini diharapkan dapat menghasilkan model prediksi yang lebih akurat, interpretatif, dan aplikatif untuk membantu pihak kampus dalam pengambilan keputusan strategis.

1.2 Rumusan Masalah
1. Bagaimana cara mengolah data akademik mahasiswa agar dapat digunakan dalam model prediksi waktu kelulusan?
2. Bagaimana penerapan metode Survival Analysis dalam memodelkan waktu kelulusan mahasiswa?
3. Bagaimana penerapan metode Gradient Boosting untuk meningkatkan akurasi prediksi waktu kelulusan?
4. Seberapa baik performa model yang dihasilkan dibandingkan dengan model statistik konvensional?

1.3 Tujuan Penelitian
1. Mengumpulkan dan menyiapkan dataset akademik mahasiswa yang relevan untuk analisis kelulusan.
2. Menerapkan metode Survival Analysis untuk memprediksi lama studi mahasiswa.
3. Mengintegrasikan Gradient Boosting sebagai model pembanding dan peningkatan performa.
4. Mengevaluasi performa model berdasarkan metrik survival seperti concordance index (C-index) atau Brier score.
5. Menghasilkan sistem prediksi sederhana yang dapat digunakan untuk memantau risiko keterlambatan kelulusan.

1.4 Manfaat Penelitian
1. Bagi institusi pendidikan: membantu memprediksi dan mengintervensi mahasiswa berisiko terlambat lulus.
2. Bagi mahasiswa: memberikan insight mengenai faktor-faktor yang berpengaruh terhadap lama studi.
3. Bagi peneliti dan pengembang sistem: sebagai referensi penerapan gabungan antara Survival Analysis dan Gradient Boosting di bidang pendidikan.
4. Bagi akademisi: memperkaya literatur penelitian data mining di bidang pendidikan tinggi (educational data mining).
