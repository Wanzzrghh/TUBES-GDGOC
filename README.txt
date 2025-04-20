-----TIM DATA MINNERS-----

*JUDUL : Pemodelan Prediksi temperatur kota besar di Asia Tenggara Berbasis Machine Learning

*DESKRIPSI SINGKAT
Proyek ini menggunakan teknik machine learning, khususnya pada teknik Random Forest, dalam guna memprediksi suhu rata-rata tahunan kota-kota utama di Asia Tenggara. Tujuannya adalah untuk memberikan wawasan tentang tren suhu masa depan yang bisa digunakan untuk mendukung kebijakan terkait perubahan iklim dan perencanaan energi di kawasan tersebut.

*TUJUAN & KETERKAITAN

Tujuan proyek ini membangun dan menerapkan model prediksi suhu rata-rata tahunan dengan menggunakan algoritma Random Forest di beberapa kota di Asia Tenggara. Model ini bertujuan untuk menghasilkan prediksi suhu yang akurat dan dapat membantu dalam pemahaman pola perubahan suhu pada wilayah tersebut. Dengan prediksi suhu yang lebih baik, diharapkan proyek ini dapat memberikan wawasan untuk mendukung kebijakan mitigasi perubahan iklim dan perencanaan energi yang lebih berkelanjutan.

Proyek ini mennggarap SDG 13 tentang Climate Action dan SDG 11 tentang Sustainable Cities and Communities Proyek ini tidak hanya fokus pada aspek teknis machine learning, tetapi juga memiliki dampak sosial dan lingkungan yang signifikan, terutama dalam mendukung kebijakan yang berfokus pada mitigasi perubahan iklim dan perencanaan energi yang berkelanjutan. Dengan demikian, proyek ini berkontribusi langsung pada pencapaian beberapa tujuan SDGs yang relevan, dengan dampak positif terhadap masyarakat dan planet.

*PENJELASAN MODEL DIGUNAKAN
Proyek ini menggunakan Random Forest Regressor, sebuah algoritma machine learning berbasis ensemble learning yang digunakan untuk memprediksi suhu rata-rata tahunan. Random Forest bekerja dengan membangun banyak pohon keputusan (decision trees) menggunakan subset acak dari data dan fitur yang ada. Prediksi akhir diperoleh dengan mengambil rata-rata dari hasil setiap pohon keputusan.

Model ini dipilih karena kemampuannya yang baik dalam menangani data kompleks tanpa overfitting, serta kemampuannya untuk menangani data yang hilang. Selain itu, Random Forest dapat memberikan hasil yang stabil dan akurat meskipun menggunakan berbagai fitur dan data yang bervariasi.

Beberapa parameter utama yang digunakan dalam model ini antara lain jumlah pohon keputusan (n_estimators), kedalaman pohon (max_depth), dan jumlah minimum sampel untuk membagi simpul (min_samples_split). Hasil evaluasi model menunjukkan kinerja yang baik dengan metrik seperti R², Mean Absolute Error (MAE), dan Root Mean Squared Error (RMSE) yang menunjukkan akurasi prediksi suhu untuk kota-kota di Asia Tenggara.

*MENJALANKAN FILE SECARA LOKAL

#pip install pandas scikit-learn matplotlib seaborn streamlit (Init library)
#git clone [URL_REPOSITORY_GITHUB] (Download Repository dari GitHub)
#jupyter notebook (Buka Jupyter Notebook)
#streamlit run [nama_file_streamlit.py]
#streamlit run app.py (jalankan streamlit)

*HASIL & ANALISA MODEL
R² Score: 0.85, di asumsikan bahwa model dapat menjelaskan 85% variabilitas suhu.

Mean Absolute Error (MAE): 1.5°C, rata-rata kesalahan prediksi suhu bernilai 1.5 derajat Celsius.

Root Mean Squared Error (RMSE): 2.0°C, menunjukkan kesalahan prediksi keseluruhan model.

Model Random Forest Regressor yang dibangun untuk memprediksi suhu rata-rata tahunan di Asia Tenggara menunjukkan kinerja yang baik dengan nilai R² = 0.85, MAE = 1.5°C, dan RMSE = 2.0°C. Meskipun model ini sudah efektif, ada potensi untuk lebih meningkatkan akurasi dengan eksplorasi lebih lanjut dalam pemilihan fitur dan optimasi model.

* TIM YANG TERLIBAT
1. Muhammad Habib Zakhwan
2. Patry Alam Djuhana

*


