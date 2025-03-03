# 🚀 XBearerFinder: Ekstensi Penangkap Bearer Token untuk X/Twitter 🔍

![XBearerFinder Logo](https://github.com/user-attachments/assets/a06523f6-1378-4443-bca7-15b78d5ad3a9)
🔍 **XBearerFinder** adalah ekstensi Chrome yang otomatis mendapatkan Bearer Token dari X (Twitter). Berguna bagi pengembang dan peneliti keamanan untuk debugging, pengujian, atau analisis jaringan tanpa perlu membuka alat pengembang.

## 📌 Fitur Utama

Ekstensi ini dapat **mendeteksi otomatis** Bearer Token dari permintaan API X/Twitter dan **menyimpannya dengan aman** di popup tanpa perlu login. Token dapat **disalin sekali klik** melalui tombol *Copy Token*, atau **dihapus** menggunakan tombol *Clear* kapan saja.

## 📜 Izin yang Digunakan

Ekstensi memerlukan **`host_permissions`** untuk mengakses halaman di `https://*.twitter.com/*` dan `https://*.x.com/*` guna membaca permintaan API. Izin **`storage`** digunakan untuk menyimpan token sementara selama sesi. Sementara itu, **`webRequest`** memungkinkan deteksi otomatis Bearer Token dari permintaan API.

## 🛠️ Cara Penggunaan

Buka X (Twitter) dan pastikan sudah login, lalu akses halaman yang memicu permintaan API. Klik ikon ekstensi **XBearerFinder** di bilah browser untuk melihat Bearer Token di popup. Gunakan tombol **"Copy Token"** untuk menyalin atau **"Clear"** untuk menghapus token dari tampilan.

## 📸 Tangkapan Layar

![Image](https://github.com/user-attachments/assets/2e5658bf-2c50-42cb-97c0-562018a9ef9e)

## ⚠️ Disclaimer

XBearerFinder dibuat **hanya untuk tujuan edukasi, pengujian, dan debugging API**. Setiap token yang diperoleh harus digunakan secara etis dan mematuhi kebijakan resmi X (Twitter) serta hukum yang berlaku. Penyalahgunaan menjadi tanggung jawab penuh pengguna.

## 📄 License

Lisensi: **MIT** - Bebas digunakan dan dimodifikasi dengan syarat yang berlaku.