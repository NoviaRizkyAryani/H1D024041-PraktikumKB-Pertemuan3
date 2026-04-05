**Praktikum Kecerdasan Buatan - Pertemuan 3 - Studi Kasus Logika Fuzzy 2**

Repositori ini berisi penyelesaian dua studi kasus menggunakan metode Logika Fuzzy Mamdani dengan pustaka scikit-fuzzy pada Python.

**Studi Kasus 1 : Optimasi Stok Toko Hewan**
Udin Pet Shop ingin mengoptimalkan persediaan stok makanan hewan untuk memenuhi permintaan, memaksimalkan profit, dan meminimalkan risiko overstock.

Variabel dan Himpunan Fuzzy : 
Input : 
- Barang Terjual ($0-100$ unit): Rendah, Sedang, Tinggi.
- Permintaan ($0-300$ unit): Rendah, Sedang, Tinggi.
- Harga per Item (Rp $0 - 100.000$): Murah, Sedang, Mahal.
- Profit (Rp $0 - 4.000.000$): Rendah, Sedang, Tinggi.
Output : 
- Stok Makanan ($0-1000$): Sedang, Banyak. 

Skenario Pengujian : 
Barang Terjual: 80
Permintaan: 255
Harga per Item: Rp 25.000
Profit: Rp 3.500.000

**Studi Kasus 2 : Penilaian Kepuasan Masyarakat**
Kantor Pelayanan Masyarakat Kota Sejahtera menggunakan logika fuzzy untuk memberikan penilaian objektif terhadap tingkat kepuasan masyarakat.

Variabel dan Himpunan Fuzzy : 
Input (Semesta $0-100$) :
- Kejelasan Informasi: Tidak Memuaskan, Cukup Memuaskan, Memuaskan.
- Kejelasan Persyaratan: Tidak Memuaskan, Cukup Memuaskan, Memuaskan.
- Kemampuan Petugas: Tidak Memuaskan, Cukup Memuaskan, Memuaskan.
- Ketersediaan Sarpras: Tidak Memuaskan, Cukup Memuaskan, Memuaskan.
Output (Semesta $0-400$) : 
- Kepuasan Pelayanan: Tidak Memuaskan, Kurang Memuaskan, Cukup Memuaskan, Memuaskan, Sangat Memuaskan. 

Skenario Pengujian :
Kejelasan Informasi: 80
Kejelasan Persyaratan: 60
Kemampuan Petugas: 50
Ketersediaan Sarpras: 90

**Prasyarat Sistem**
Pastikan Anda telah menginstal pustaka berikut sebelum menjalankan kode:

pip install numpy skfuzzy matplotlib

**Cara menjalankan**

1. Jalankan skrip Python untuk masing-masing studi kasus:

toko_hewan.py
pelayanan_masyarakat.py

2. Program akan menampilkan hasil perhitungan defuzzifikasi dan grafik fungsi keanggotaan
