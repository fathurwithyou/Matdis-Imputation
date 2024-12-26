# Algoritma Pohon Keputusan Termodifikasi sebagai Alat Imputasi Multivariat Data Nonlinear

Proyek ini bertujuan untuk mengembangkan dan menerapkan algoritma pohon keputusan yang dimodifikasi untuk melakukan imputasi data multivariat dengan hubungan nonlinear. Imputasi data adalah langkah penting dalam pengolahan data untuk mengatasi masalah data yang hilang atau tidak lengkap yang dapat memengaruhi akurasi analisis dan model prediksi.

# Dataset
Dataset yang digunakan dalam proyek ini adalah dataset performa murid dalam menghadapi ujian, yang terdiri dari 6607 baris dan 7 kolom (numerical). Dataset ini awalnya tidak memiliki nilai hilang, tetapi nilai hilang ditambahkan secara acak untuk tujuan pengujian.

## Kolom Dataset
- **Hours_Studied**: Jumlah jam yang dihabiskan untuk belajar per minggu.
- **Attendance**: Persentase jumlah kehadiran.
- **Sleep_Hours**: Lama murid tidur (jam).
- **Previous_Scores**: Skor ujian sebelumnya.
- **Tutoring Sessions**: Jumlah sesi bimbingan belajar yang dihadiri per bulan.
- **Physical_Activity**: Rata-rata jumlah aktivitas fisik per minggu.
- **Exam_Score**: Nilai ujian akhir.

# Instalasi
1. Clone repositori ini:
   ```bash
   git clone https://github.com/fathurwithyou/Matdis-MultivariateImputation.git
   ```
2. Masuk ke direktori proyek:
   ```bash
   cd Matdis-MultivariateImputation
   ```
3. Install dependensi yang diperlukan:
   ```bash
   pip install -r requirements.txt
   ```
4. Gunakan file `main.ipynb` untuk eksplorasi.

# Lisensi
Proyek ini dilisensikan di bawah [MIT](LICENSE)