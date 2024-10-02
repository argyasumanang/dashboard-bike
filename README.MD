# Dashboard Analisis Data Bike Sharing

Ini adalah proyek analisis data untuk sistem berbagi sepeda (Bike Sharing) menggunakan dataset yang tersedia. Proyek ini mencakup pembuatan dashboard interaktif dengan Streamlit dan visualisasi data menggunakan Seaborn dan Matplotlib.

## Struktur Direktori

- **dashboard/**
  - Berisi file `dasboard.py` yang merupakan kode untuk menjalankan dashboard dengan Streamlit.
  
- **data/**
  - `day.csv`: Dataset untuk analisis per hari.
  - `hour.csv`: Dataset untuk analisis per jam.

- **README.md**
  - Berisi panduan untuk menjalankan proyek ini.

- **requirements.txt**
  - Berisi daftar library Python yang diperlukan untuk menjalankan proyek ini.

## Cara Menjalankan Dashboard

### Secara Lokal

1. Pastikan Anda sudah menginstal Python dan pip di mesin lokal Anda.
2. Install seluruh dependensi yang diperlukan dengan perintah:
3. Jalankan Streamlit dengan perintah berikut di terminal Anda:
4. Buka browser dan arahkan ke `http://localhost:8501` untuk mengakses dashboard.

### Di Streamlit Cloud

1. Clone repository ini ke akun GitHub Anda.
2. Deploy ke [Streamlit Cloud](https://streamlit.io/cloud) dengan menghubungkan repository ini ke akun Streamlit Anda.
3. Setelah deployment berhasil, tautan ke dashboard Anda akan tersedia di Streamlit Cloud.

## Insight yang Didapat:

1. **Musim dengan Pengguna Sepeda Terbanyak:** Berdasarkan analisis, musim dengan penggunaan sepeda tertinggi adalah **Musim Gugur** dengan total penggunaan sebesar 2,5 juta pengguna.
2. **Pengaruh Cuaca:** Cuaca cerah atau sebagian berawan memiliki pengaruh positif terhadap jumlah pengguna sepeda, sementara kondisi cuaca buruk seperti hujan salju ringan atau berat mengurangi penggunaan sepeda secara drastis.

## Dependencies

Lihat berkas `requirements.txt` untuk daftar lengkap library yang diperlukan.

