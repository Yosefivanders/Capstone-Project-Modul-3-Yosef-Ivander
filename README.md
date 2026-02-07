# Capstone-Project-Modul-3-Yosef-Ivander

## Efektivitas Kampanye Marketing Bank

# Project Overview

Proyek ini bertujuan menganalisis efektivitas kampanye marketing bank dalam menawarkan produk deposito kepada nasabah, dengan fokus pada pengaruh kepemilikan pinjaman seperti housing loan dan personal loan terhadap keputusan nasabah membuka deposito.
Melalui pendekatan machine learning classification, proyek ini akan mengidentifikasi faktor-faktor yang memengaruhi respons nasabah terhadap kampanye serta membantu bank meningkatkan strategi targeting marketing agar lebih efektif, efisien, dan berbasis data.

# Business Understanding

# Background

Persaingan industri perbankan semakin ketat sehingga bank perlu strategi pemasaran yang tepat untuk meningkatkan produk simpanan seperti deposito.
Namun, tidak semua nasabah merespons kampanye marketing dengan baik. Salah satu faktor yang diduga memengaruhi respons nasabah adalah kondisi finansial mereka, khususnya kepemilikan pinjaman seperti kredit rumah atau pinjaman pribadi.
Tanpa analisis data yang tepat, kampanye marketing berisiko:

* Tidak tepat sasaran
* Biaya marketing tinggi
* Tingkat konversi rendah
* Business Problem

Beberapa permasalahan bisnis yang ingin diselesaikan :
* Apakah nasabah yang memiliki pinjaman cenderung menolak penawaran deposito?
* Faktor apa saja yang paling mempengaruhi keberhasilan kampanye marketing bank?
* Bagaimana bank dapat mengoptimalkan strategi targeting agar kampanye lebih efektif?
* Bagaimana mengurangi biaya marketin tapa menurunkan tingkat konversi nasabah?

# Stakeholders

**Marketing Team Bank** : Menjalankan kampanye promosi produk bank.
**Data Analyst / Data Scientist** : Memberikan insight berbasis data dengan menggunakan model.
**Manajemen Bank (Desicion Maker)** : Menentukan kebijakan marketing.
**Nasabah Bank** : Target kampanye marketing.

# Project Objectives

* Menganalisis faktor yang mempengaruhi keberhasilan kampanye.
* Mengidentifikasi pengaruh kepemilikan pinjaman terhadap keputusan nasabah.
* Mengembangkan model classification untuk prediksi respons nasabah
* Memberikan rekomendasi strategi marketing berbasis data.

# Spesific Objectives

* Melakukan eksplorasi data nasabah bank.
* Menganalisis hubungan variabel loan dengan respons deposito.
* Membangun model machine learning classification.
* Mengevaluasi performa model menggunakan metrik classification.
* Mengidentifikasi variabel paling berpengaruh.
* Memberikan insight actionable untuk marketing bank.
* Business Impact Analysis (Confusion Matrix)
* Peran Confusion Matrix dalam Bisnis

# Business Impact Analysis (Confusion Matrix)
Peran Confusion Matrix dalam Bisnis

Confusion matrix membantu mengevaluasi performa model calssification dalam memprediksi apakah nasabah akan membuka deposito atau tidak.
Dengan memahami hasil prediksi model, bank dapat menentukan strategi marketing yang lebih efektif dan mengurangi biaya kampanye yang tidak tepat sasaran.

| Actual/Predicted | Prediksi(Ya) | Prediksi(Tidak) |
| :--- | :---: | ---: |
| Actual(Ya) | True Positive (TP) | False Negative (FN) |
| Actual(Tidak) | False Positive (FP) | True Negative (TN) |

# Business Impact Tiap Komponen
  ## True Positive (TP)
Nasabah diprediksi membuka deposito dan benar-benar membuka deposito.
  ## Impact Bisnis :
  * Kampanye tepat sasaran.
  * ROI marketing meningkat.
  * Efisiensi biaya promosi.

  ## False Positive (FP)
Diprediksi membuka deposito tetapi sebenarnya tidak.
  ## Impact Bisnis :
  * Biaya marketing terbuang.
  * Resiko nasabah merasa terganggu.
  * Potensi reputasi menurun.

  ## False Negative (FN)
Diprediksi tidak membuka deposito tetapi sebenarnya mau.
  ## Impact Bisnis :
  * Kehilangan peluang revenue.
  * Potensi dana deposito hilang.
  * Target bisnis bisa tidak tercapai.

  ## True Negative (TN)
Diprediksi tidak membuka deposito dan memang tidak.
  ## Impact Bisnis :
  * Bank tidak buang biaya marketing.
  * Kampanye lebih efisien.

# Implikasi Strategi Marketing
  ## Jika FN tinggi :
  * Banyak nasabah potensial tidak ditarget.
