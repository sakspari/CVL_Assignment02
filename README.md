# Tugas Object Detection By Segmentation: Metode Otsu pada Segmentasi Sel

Tugas ini membahas segmentasi citra menggunakan metode Otsu pada dataset citra sel dari Kaggle. Metode Otsu digunakan untuk menentukan ambang optimal secara otomatis dalam proses segmentasi citra.

Data Citra dan Mask/ground-truth diperoleh dari kaggle

## Deskripsi Singkat

- **Metode:** Otsu Thresholding
- **Dataset:** Citra sel dari Kaggle
- **Referensi:**  
    Gonzalez, R. C., & Woods, R. E. (Digital Image Processing)

## Langkah-langkah

1. **Eksplorasi Citra:**  
     Memvisualisasikan persebaran histogram

2. **Segmentasi Otsu:**  
     Mengaplikasikan metode Otsu untuk menentukan nilai threshold optimal dan memisahkan objek (sel) dari latar belakang.

     Pendekatan yang digunakan sedikit berbeda dengan teori yang diajarkan di dalam kelas. Pada materi diajarkan bahwa untuk mencari nilai threshold optimal kita perlu menemukan nilai inclass variance terkecil, pada pendekatan ini saya mencoba menggunakan nilai variance antar kelas yang paling besar. sebenarnyaa konsepnya kurang lebih sama (mencari variance/kemiripan dalam kelas yang sama dan mencari nilai yang menghasilkan vanrians terbesar antar kelas) 

3. **Evaluasi:**  
     Mengevaluasi hasil segmentasi dengan visualisasi dan metrik Accuracy dan IoU.

## Referensi

- Gonzalez, R. C., & Woods, R. E. *Digital Image Processing*. Pearson.
