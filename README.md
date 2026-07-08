# Lawrence and Partners Law Firm

Landing page modern dan responsif untuk **Lawrence and Partners Law Firm** yang dibuat menggunakan HTML, Tailwind CSS (CDN), Font Awesome, dan AOS (Animate On Scroll). Website ini menampilkan informasi firma hukum, layanan, tim advokat, serta formulir konsultasi.

---

## Demo

Buka file:

```
Praktikum Lawfirm.html
```

menggunakan browser modern seperti:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Brave

---

# Fitur

- Landing Page Modern
- Responsive Design
- Sticky Navigation
- Smooth Scrolling
- Hero Section
- About Section
- Practice Areas / Bidang Hukum
- Team Slider
- Contact Form
- Floating Consultation Button
- Scroll Animation (AOS)
- Font Awesome Icons
- Tailwind CSS via CDN

---

# Teknologi yang Digunakan

- HTML5
- Tailwind CSS 4 (CDN)
- JavaScript (Vanilla)
- Font Awesome 6
- AOS Animation Library

---

# Struktur Project

```
project/
│
├── Praktikum Lawfirm.html
└── README.md
```

---

# Cara Menjalankan Project

## 1. Clone Repository

```bash
git clone https://github.com/username/lawfirm-landing-page.git
```

atau download ZIP dari GitHub.

---

## 2. Masuk ke Folder Project

```bash
cd lawfirm-landing-page
```

---

## 3. Jalankan Website

Karena project ini bersifat statis, Anda cukup membuka file:

```
Praktikum Lawfirm.html
```

atau menggunakan Live Server pada Visual Studio Code.

---

# Menjalankan Menggunakan VS Code

## Install Extension

Install extension:

```
Live Server
```

Kemudian:

1. Klik kanan file **Praktikum Lawfirm.html**
2. Pilih **Open with Live Server**

Website akan terbuka pada:

```
http://127.0.0.1:5500/
```

atau

```
http://localhost:5500/
```

---

# Dependencies

Project menggunakan library melalui CDN sehingga **tidak memerlukan instalasi npm**.

### Tailwind CSS

```
https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4
```

### Font Awesome

```
https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css
```

### AOS Animation

CSS

```
https://unpkg.com/aos@next/dist/aos.css
```

JavaScript

```
https://unpkg.com/aos@next/dist/aos.js
```

---

# Fitur Halaman

## Home

Menampilkan:

- Hero Section
- CTA Button
- Background Image
- Overlay Gradient

---

## About

Berisi:

- Profil Firma
- Statistik
- Deskripsi Perusahaan

---

## Services

Menampilkan bidang praktik hukum seperti:

- Hukum Korporasi
- Litigasi Pidana & Perdata
- Hukum Keluarga & Waris

---

## Team

Menampilkan daftar partner dan advokat menggunakan slider horizontal.

Fitur:

- Tombol Next
- Tombol Previous
- Smooth Scroll

---

## Contact

Berisi:

- Alamat
- Nomor Telepon
- Email
- Form Konsultasi

---

# Responsive

Website telah mendukung:

- Desktop
- Laptop
- Tablet
- Mobile

---

# Kustomisasi

Warna utama dapat diubah pada bagian CSS berikut:

```css
.bg-gold {
    background-color: #D6AD60;
}

.bg-maroon {
    background-color: #810202;
}
```

---

# Animasi

Project menggunakan AOS.

Inisialisasi:

```javascript
AOS.init({
    offset: 120,
    delay: 45,
    duration: 800,
    easing: 'ease-in-out',
    once: true
});
```

---

# Slider Tim

Slider dibuat menggunakan JavaScript Vanilla.

Fungsi utama:

- Scroll Next
- Scroll Previous
- Smooth Animation

---

# Browser Support

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Brave
- Opera
- Safari

---

# Catatan

Karena menggunakan CDN, koneksi internet diperlukan agar:

- Tailwind CSS
- Font Awesome
- AOS

dapat dimuat dengan baik.

---

# Pengembangan Selanjutnya

Beberapa fitur yang dapat ditambahkan:

- Backend Laravel
- Database MySQL
- Login Admin
- Manajemen Artikel
- Booking Konsultasi Online
- WhatsApp Integration
- Email Integration
- Google Maps API
- Dark Mode
- Multi Language

---

# Author

**Kelompok 2**

---

# License

Project ini dibuat untuk keperluan praktikum dan pembelajaran.
