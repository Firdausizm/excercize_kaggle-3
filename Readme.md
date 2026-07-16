# Deteksi Slot Parkir

Proyek ini bertujuan untuk mendeteksi status tempat parkir, apakah setiap slot dalam area parkir sedang kosong atau terisi. Sistem ini memanfaatkan pendekatan computer vision dan deep learning untuk menganalisis frame video parkir dan mengklasifikasikan tiap slot parkir secara otomatis. [Dataset](https://www.kaggle.com/datasets/iasadpanwhar/parking-lot-detection-counter) yang digunakan dari platform Kaggle sehingga bisa di akses siapapun.

## Tujuan Project

- Mendeteksi area slot parkir dari frame video
- Mengklasifikasikan setiap slot menjadi kosong atau terisi
- Menyediakan hasil prediksi yang dapat dipakai untuk analisis parkir lebih lanjut

## Teknologi yang Digunakan

- Python
- OpenCV
- NumPy
- scikit-image
- PyTorch / Torchvision
- Ultralytics YOLO
- Pandas

## Struktur Folder

- Notebook/deteksi-tempat-parkir-1.ipynb: notebook utama untuk eksperimen, training, dan inference
- parking/clf-data/: dataset citra slot parkir yang terbagi menjadi kelas empty dan not_empty
- Result/results.csv: hasil prediksi yang dihasilkan dari proses


## Hasil

<img src="https://github.com/Firdausizm/excercize_kaggle-3/blob/main/Result/sample_output.png" width=true />

## Catatan

Project ini untuk pembelajaran dan eksperimen deteksi parkir berbasis citra video. Hasil model dapat dikembangkan lebih lanjut untuk akurasi yang lebih baik dengan dataset yang lebih beragam.

