**Klasifikasi Gambar Dua Objek: Nanas vs Stroberi**
Tugas ini merupakan bagian dari penugasan individu mata kuliah yang berfokus pada klasifikasi citra dua jenis objek menggunakan teknik **Transfer Learning**. Saya memilih untuk mengklasifikasikan dua buah, yaitu **nanas** dan **stroberi**, menggunakan model pretrained **MobileNetV2**.
Model ini memanfaatkan bobot awal dari ImageNet dan disesuaikan untuk mendeteksi dua kelas. Dataset terdiri dari lebih dari 200 gambar yang saya kumpulkan sendiri, dengan variasi sudut pengambilan gambar.

**Dataset**
- Total gambar: ±200
  - Kelas "nanas": 100+ gambar
  - Kelas "stroberi": 100+ gambar

**/Dataset/**
├── nanas/
    - img _ 1.jpeg
    .....
└── stroberi/
    - img _ 1.jpeg
    .....

**Training**
- Epochs: 10
- Batch size: 32
- Validasi: 20% data
- Akurasi validasi akhir: ±91% (bergantung pada run terakhir)
- Evaluasi: Confusion Matrix, Classification Report

**Author**
Nama: Azmi Nur Al Qodar  
NIM: 442023618054 
Tanggal Pengumpulan: 30/05/2025


  
