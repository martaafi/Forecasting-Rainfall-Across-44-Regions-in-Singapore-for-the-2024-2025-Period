# Image-Based Time Series Forecasting of Rainfall in 44 Regions of Singapore (2024–2025)
## **Pendahuluan**

Dalam beberapa tahun terakhir, peningkatan frekuensi dan intensitas peristiwa cuaca ekstrem menjadi isu global yang semakin mendesak. Singapura, sebagai negara kecil dengan kepadatan penduduk tinggi dan infrastruktur perkotaan yang kompleks, turut merasakan dampak perubahan iklim ini. Fenomena seperti banjir lokal akibat hujan deras maupun gelombang panas yang memengaruhi kesehatan masyarakat telah menjadi perhatian serius.

Meteorological Service Singapore (MSS), sebagai lembaga resmi pengamatan dan prakiraan cuaca di Singapura, memiliki 44 stasiun pengamatan yang secara rutin mengumpulkan data harian. Namun, kompleksitas pola cuaca mikro yang sangat bervariasi di tiap wilayah serta keterbatasan data historis dalam format terstruktur menjadikan prediksi cuaca tetap menjadi tantangan besar. Di sisi lain, banyak data historis yang hanya tersedia dalam bentuk visual seperti grafik pada dokumen PDF atau gambar statis, sehingga sulit dimanfaatkan langsung untuk analisis kuantitatif.

Di tengah pesatnya perkembangan teknologi kecerdasan buatan, computer vision, dan machine learning, muncul peluang baru untuk mengekstraksi data dari gambar plot time series cuaca menjadi format numerik yang dapat digunakan untuk pelatihan model prediktif. Pendekatan ini tidak hanya berguna untuk meningkatkan akurasi prakiraan cuaca di Singapura, tetapi juga dapat diadaptasi untuk negara lain seperti Indonesia yang memiliki risiko serupa terhadap bencana cuaca ekstrem.

## **Tujuan**

Proyek ini bertujuan untuk:

1. **Mengekstraksi data numerik dari gambar grafik cuaca** menggunakan teknik *computer vision* dan *OCR* secara otomatis dan akurat.
2. **Membangun model prediksi cuaca** berdasarkan data historis yang diperoleh dari hasil ekstraksi grafik.
3. **Meningkatkan akurasi prediksi cuaca ekstrem** dengan memperluas basis data historis yang dapat dianalisis oleh model.
4. **Mendorong pemanfaatan AI dan machine learning** dalam mendukung pengambilan keputusan yang lebih cepat dan tepat terkait mitigasi bencana iklim.
5. **Mendemonstrasikan relevansi lintas negara**, khususnya bagaimana solusi ini dapat diterapkan di Indonesia untuk memperkuat sistem peringatan dini dan pengelolaan risiko bencana.


## **Fokus Proyek**

Fokus utama proyek ini adalah mengembangkan solusi inovatif berbasis *computer vision* dan *machine learning* untuk memproses dan memprediksi data cuaca dari grafik gambar. Ruang lingkup pekerjaan meliputi:

* Identifikasi dan ekstraksi sumbu, skala, dan titik data dari grafik cuaca (plot time series).
* Transformasi data visual menjadi data numerik terstruktur yang dapat digunakan dalam analisis kuantitatif.
* Pelatihan dan evaluasi model prediksi cuaca menggunakan data historis hasil ekstraksi.
* Evaluasi performa model menggunakan metrik Mean Squared Error (MSE).
* Validasi metode agar dapat direplikasi dan diadaptasi untuk wilayah lain, terutama Indonesia, yang memiliki kebutuhan mendesak terhadap prakiraan cuaca berbasis data.

## **Dataset**
Kaggle Competition  <br>
Link: https://www.kaggle.com/competitions/sebelas-maret-statistics-data-science-2025/data

Kami menggunakan Webplotdigitizer untuk mengekstrak data gambar plot daily rainfall menjadi data tabular. Berikut adalah data ekstraksi plot daily rainfall yang diperoleh, <br>
Link: https://drive.google.com/drive/folders/1Bswry-FX-nvqz4iwTJxVkglJTi8Z5n8E?usp=sharing

Kami hanya menggunakan data historis harian selama 3 tahun ke belakang yaitu 2021 hingga 2023 karena mempertimbangkan relevansi cuaca. Data ini digunakan untuk melakukan prediksi curah hujan pada januari 2024 - mei 2025.

## Hasil
- Memperoleh skor akhir pada leaderboard Kaggle dengan nilai Mean Squared Error (MSE) sebesar 19,04488, menempati peringkat 8 dari 60 tim.
- Berhasil masuk sebagai finalis kompetisi Sebelas Maret Statistics Data Science 2025.
