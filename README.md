# Proyek Klasifikasi Gambar: [Flowers Recognition-Alexander Mamaev]
## Overview
Penelitian ini bertujuan untuk mengembangkan model klasifikasi gambar yang efisien dan akurat dengan memanfaatkan Convolutional Neural Network (CNN) dan metode transfer learning menggunakan arsitektur MobileNetV2. MobileNetV2 dipilih karena kemampuannya dalam memberikan performa yang cepat dan efisien secara komputasi, serta telah dilatih sebelumnya pada dataset besar seperti ImageNet.  Dalam penelitian ini, model CNN yang telah dilatih sebelumnya (pre-trained) digunakan sebagai dasar untuk melatih model baru pada dataset gambar yang spesifik. Proses transfer learning memungkinkan model untuk memanfaatkan pengetahuan yang telah diperoleh dari dataset besar dan menerapkannya pada tugas klasifikasi gambar yang baru, sehingga mempercepat waktu pelatihan dan meningkatkan akurasi.  Hasil dari penelitian ini menunjukkan bahwa penggunaan MobileNetV2 dengan transfer learning dapat menghasilkan model klasifikasi gambar yang memiliki akurasi tinggi dan waktu komputasi yang lebih cepat dibandingkan dengan model CNN yang dilatih dari awal. Implementasi ini diharapkan dapat diterapkan pada berbagai aplikasi, seperti pengenalan objek, deteksi wajah, dan klasifikasi citra medis.

## Project Structure
- `KLASIFIKASI_GAMBAR_TRIRAMDHANY.ipynb`: Direktori yang berisi notebook Jupyter untuk Model Klasifikasi Gambar.
- `requirements.txt`: Daftar dependensi Python yang diperlukan untuk menjalankan proyek.
- `README.md`: Dokumentasi proyek ini.
- 'Save Model' : for deployment
  

## Installation
1. Clone repositori ini ke mesin lokal Anda:
   ```bash
   git clone https://github.com/tri1505/Proyek-Klasifikasi-Gambar---Flowers-Recognition-Alexander-Mamaev-.git
   
'Instal dependensi yang diperlukan:'
pip install -r requirements.txt
