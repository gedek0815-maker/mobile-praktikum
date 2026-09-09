# Analisis Aplikasi Mobile: Shopee

## 1. Masalah dan Pengguna

- **Masalah yang diselesaikan:** Kesulitan mengakses pilihan produk yang lengkap dengan harga bersaing, ketiadaan rasa aman dalam transaksi jual-beli jarak jauh (risiko penipuan transfer langsung), serta rumitnya penghitungan ongkos kirim dan pelacakan barang fisik. Shopee menyelesaikannya lewat sistem rekening bersama (Garansi Shopee), katalog terintegrasi, dan kemitraan logistik nasional.

- **Pengguna utama:**
  - Konsumen ritel (pelajar, mahasiswa, pekerja, hingga ibu rumah tangga) yang membutuhkan barang kebutuhan harian, sandang, atau elektronik secara praktis.
  - Pelaku usaha mikro, kecil, dan menengah (UMKM) serta *reseller* yang memanfaatkan platform sebagai toko digital untuk menjangkau pembeli di seluruh Indonesia.

## 2. Fitur Utama dan Manfaat

- **Pencarian Visual Berbasis Kamera (*Visual Search*):** Pengguna dapat mencari barang hanya dengan memotret objek fisik atau mengunggah foto dari galeri. Manfaatnya, pengguna tidak perlu menerka nama atau kata kunci spesifik ketika mencari barang yang wujudnya mereka ketahui.

- **Shopee Live & Shopee Video:** Menyediakan wadah interaksi visual dua arah antara pembeli dan penjual secara langsung (*real-time*). Manfaatnya, pembeli bisa melihat detail fisik produk asli sebelum membeli, berkonsultasi langsung, serta memanfaatkan voucer diskon khusus sesi siaran langsung.

- **Sistem Pelacakan Paket (*Live Order Tracking*):** Menampilkan linimasa perjalanan paket secara terperinci mulai dari penyerahan ke ekspedisi, pergerakan antargudang (*hub transit*), hingga kurir mengantar ke alamat tujuan. Manfaatnya, pembeli mendapat estimasi waktu kedatangan yang akurat dan rasa aman terhadap barang yang sudah dibayar.

## 3. Alur Penggunaan (Pencarian Produk hingga Checkout)

1. **Pencarian:** Buka aplikasi, ketik nama barang di bilah pencarian atas (atau gunakan ikon kamera untuk memindai foto barang).

2. **Penyaringan (Filtering):** Terapkan filter pencarian, seperti batas harga, lokasi toko terdekat, opsi program Gratis Ongkir Xtra, dan penilaian bintang (minimal rating 4,5).

3. **Seleksi Produk:** Pilih salah satu produk, periksa ulasan dan foto dari pembeli sebelumnya, pilih varian (warna/ukuran), lalu tekan tombol **Beli Sekarang**.

4. **Halaman Checkout:** Pastikan alamat pengiriman sudah benar, pilih opsi jasa pengiriman (Reguler, Kargo, atau Instan), dan masukkan voucer Shopee (potongan harga/gratis ongkir).

5. **Pembayaran:** Pilih metode pembayaran (ShopeePay, Virtual Account bank, COD, atau SPayLater), lalu klik **Buat Pesanan**.

6. **Selesai & Lacak:** Konfirmasi pembayaran dengan PIN/biometrik, lalu pantau pergerakan kurir secara berkala di menu **Pesanan Saya**.

## 4. Alasan Menggunakan Aplikasi Mobile

Layanan belanja daring (*e-commerce*) saat ini mengandalkan spontanitas dan keterlibatan pengguna kapan saja tanpa batasan tempat.

Situs web desktop saja tidak cukup karena:

- **Fitur Eksklusif Mobile:** Banyak fitur interaktif (seperti *Shopee Live*, permainan berhadiah koin, serta voucer diskon tertentu) yang sengaja dioptimalkan dan hanya bisa diklaim secara penuh lewat aplikasi ponsel.

- **Kebutuhan Akses Kamera:** Mengambil foto barang secara instan untuk mencari produk atau mengunggah foto saat mengajukan komplain/ulasan barang jauh lebih natural dilakukan lewat kamera ponsel dibanding mengunggah berkas lewat peramban web.

- **Keterikatan (*Engagement*) Real-time:** Informasi promo kilat (*Flash Sale*) dan respons pesan instan dari penjual memerlukan notifikasi yang langsung muncul di layar kunci ponsel.

## 5. Integrasi Perangkat Keras dan Sistem Operasi

- **Kamera:**
  - Memindai kode QRIS merchant fisik menggunakan saldo ShopeePay.
  - Mengambil foto produk untuk fitur pencarian visual.
  - Merekam foto/video kondisi barang saat menulis ulasan pesanan atau mengajukan pengembalian barang (*refund*).

- **Push Notifications:** Memberikan pembaruan seketika terkait status pesanan (contoh: *"Paketmu sedang dibawa kurir menuju lokasimu"*), batas waktu pembayaran, serta pesan masuk dari penjual.

- **GPS / Layanan Lokasi:** Menentukan titik koordinat (*pin-point*) alamat pengiriman rumah secara presisi di peta, serta mendeteksi restoran terdekat saat menggunakan layanan ShopeeFood.

- **Biometrik (Fingerprint / Face ID):** Digunakan sebagai lapisan keamanan cepat saat mengonfirmasi pembayaran dengan ShopeePay atau SPayLater tanpa perlu mengetik 6 digit PIN berulang kali.

## 6. Kendala Pengguna dan Usulan Perbaikan

- **Kendala yang diamati:** Antarmuka beranda (*home screen*) terlalu padat (*cluttered*) dan agresif dengan *pop-up banner* promosi yang langsung menumpuk saat aplikasi baru dibuka. Pengguna yang hanya ingin mengecek status pengiriman barang atau mencari barang spesifik sering kali tidak sengaja mengeklik iklan gim atau promo yang tidak relevan, sehingga navigasi terasa lambat dan membingungkan.

- **Usulan perbaikan:** Menghadirkan opsi **"Tampilan Ringkas / Lite Mode"** pada menu pengaturan atau membatasi kemunculan *pop-up* otomatis saat aplikasi pertama kali dibuka (*cold boot*).

- **Alasan:** Mode ringkas ini memprioritaskan fungsi pokok (bilah pencarian, kategori belanja utama, dan status paket yang sedang berjalan) tanpa animasi berat. Hal ini membuat aplikasi lebih ringan, menghemat kuota internet dan konsumsi baterai, serta memberikan kenyamanan visual bagi pengguna yang mengutamakan kecepatan transaksi.