# Praktikum Kecerdasan Buatan - Jaringan Syaraf Tiruan
Repositori ini berisi implementasi algoritma Perceptron dan Backpropagation menggunakan Python

# 1. Perceptron
Sistem pembelajaran terawasi (supervised learning) yang menggunakan jaringan berlayer tunggal
1. Studi Kasus: Masalah logika OR
2. Fungsi Aktivasi: Bipolar (output -1 atau 1)
3. Aturan Update: Menggunakan Delta Rule untuk mengubah bobot dan bias
4. Karakteristik: Hanya dapat memisahkan data yang bersifat linier

# 2. Backpropagation
Model jaringan multi-layer yang memiliki Hidden Layer di antara input dan output
1. Studi Kasus: Masalah logika XOR
2. Fungsi Aktivasi: Sigmoid Bipolar atau Tanh
3. Mekanisme: Melibatkan operasi Forward Propagation (aliran informasi ke depan) dan Backward Propagation (perambatan mundur error untuk koreksi bobot)
4. Karakteristik: Mampu menyelesaikan masalah non-linier yang tidak bisa diatasi oleh Perceptron

# Struktur Program
1. Perceptron.py: Kelas utama algoritma Perceptron
2. Perceptron_or.py: Script untuk menjalankan pengujian masalah OR menggunakan model Perceptron
3. Backpropagation.py: Kelas utama algoritma Backpropagation
4. Backpropagation_xor.py: Script untuk menjalankan pengujian masalah XOR menggunakan model Backpropagation

# Cara Penggunaan
1. Pastikan Anda telah menginstal library numpy dan matplotlib
2. Jalankan file pengujian:
   python Perceptron_or.py
   python Backpropagation_xor.py
4. Hasil perhitungan detail akan otomatis tersimpan dalam file .txt (HasilPerceptron.txt dan hasilBackpropagation.txt)
6. Grafik Decision Boundary atau perbaikan error akan ditampilkan di akhir proses
