# Buku Tamu Digital

Aplikasi undangan digital dan pencatatan kehadiran tamu berbasis web.  
Dirancang untuk acara seperti pernikahan, khitanan, ulang tahun, seminar, dan event komunitas.  
Mendukung pengiriman undangan via WhatsApp, QR scanner, laporan kehadiran, dan sistem multi-user (SaaS).

---

## 🚀 Fitur Utama

### 👥 Tamu Undangan

- Pendataan tamu manual
- Import tamu massal via Excel
- Laporan kesalahan saat import (bisa diunduh)
- Download tamu yang belum menerima pesan WA
- Kirim undangan otomatis via WhatsApp (1 klik)
- Generate link undangan unik & aman (nama, jumlah orang, nomor WA)
- Laporan undangan: total, terkirim, pending

### 💬 Template WA Blast

- Buat template pesan WA sendiri
- Gunakan kode otomatis: `[nama]`, `[link-undangan]`
- Kirim pesan massal dengan fleksibilitas tinggi

### 🎟️ Kehadiran Tamu

- Pencatatan kehadiran otomatis via QR scan
- Laporan kehadiran: total tamu, tamu berpasangan, tamu belum hadir
- Laporan bisa diunduh

### 📱 Aplikasi Penerima Tamu

- Support QR code tamu (by link)
- Scan QR via gambar atau kamera langsung
- Otomatis mencatat kehadiran, device petugas, dan lokasi scan

### 🔐 Sistem SAAS

- Multi-user: 1 akun bisa kelola semua data pribadi, template WA, kehadiran, dan aplikasi petugas
- Cocok untuk EO, wedding organizer, atau pemilik acara

---

## 🛠️ Instalasi

### 1. Clone Repository

```bash
git clone https://github.com/username/buku-tamu-digital.git
cd buku-tamu-digital
```

### 2. Install Dependensi

```bash
composer install
yarn install
```

### 3. Setup Environment

```bash
cp .env.example .env
php artisan key:generate
```

### 4. Database Migration

```bash
php artisan migrate:fresh --seed
```

### 5. Jalankan Server Lokal

```bash
php artisan serve
yarn dev
```

## 📦 Struktur Teknologi

- Laravel (Backend)
- Blade + Tailwind (Frontend)
- JavaScript (QR Scanner, WA Blast)
- ZXing JS (QR Code Reader)
- MySQL / MariaDB (Database)

## 🤝 Kontribusi

- Fork repo ini
- Buat branch fitur: git checkout -b fitur-wa-blast
- Commit perubahan: git commit -m 'Tambah fitur WA Blast'
- Push ke branch: git push origin fitur-wa-blast
- Buat Pull Request

## 📄 Lisensi

Project ini berada di bawah lisensi MIT.
Silakan gunakan, modifikasi, dan distribusikan sesuai kebutuhan.

## 📬 Kontak

- Pengembang: Izalsye
- Email: veifaisal16@gmail.com
- Instagram: @izalsye.design

---
