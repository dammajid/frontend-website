ShopHub - Template Web Penjualan Modern

Template web e-commerce yang modern, responsif, dan siap pakai untuk berbagai jenis toko online.

Fitur Utama

Responsive Design - Tampilan optimal di semua perangkat (desktop, tablet, mobile)

Modern UI/UX - Desain clean dan profesional dengan gradient yang menarik

Smooth Animations - Animasi halus dan interaktif

Easy Customization - Mudah dikustomisasi sesuai kebutuhan

SEO Friendly - Struktur HTML yang baik untuk SEO

Fast Loading - Optimasi performa untuk loading cepat

Cross Browser - Kompatibel dengan semua browser modern

Struktur Folder
shophub-template/
│
├── index.html              # File HTML utama
├── css/
│   ├── style.css          # Stylesheet utama
│   └── responsive.css     # Styling untuk responsive
├── js/
│   ├── main.js           # JavaScript utama
│   └── animations.js     # Animasi dan efek
├── images/               # Folder untuk gambar
│   ├── products/         # Gambar produk
│   ├── testimonials/     # Foto testimonial
│   └── logo/            # Logo
├── assets/              # Asset tambahan
│   └── icons/           # Icon
├── README.md            # Dokumentasi
└── LICENSE              # Lisensi

Cara Instalasi

Download/Clone Repository

git clone https://github.com/yourusername/shophub-template.git


Buka dengan VS Code

cd shophub-template
code .


Install Live Server Extension

Buka VS Code Extensions (Ctrl+Shift+X)

Cari "Live Server"

Install extension tersebut

Jalankan Template

Klik kanan pada index.html

Pilih "Open with Live Server"

Template akan terbuka di browser

Customisasi
Mengubah Warna

Edit file css/style.css bagian :root:

:root {
    --primary: #6366f1;        /* Warna utama */
    --primary-dark: #4f46e5;   /* Warna utama gelap */
    --secondary: #ec4899;      /* Warna sekunder */
    --dark: #1e293b;           /* Warna gelap */
    --light: #f8fafc;          /* Warna terang */
    --text: #334155;           /* Warna teks */
}

Menambah Produk

Edit file index.html di bagian Products Section:

<div class="product-card">
    <div class="product-image">
        <span class="product-badge">NEW</span>
        <!-- Ganti dengan gambar produk -->
    </div>
    <div class="product-info">
        <h3>Nama Produk</h3>
        <p>Deskripsi produk...</p>
        <div class="product-footer">
            <div class="price">Rp 999K</div>
            <a href="#" class="btn-small">Beli Sekarang</a>
        </div>
    </div>
</div>

Mengubah Konten Teks

Semua konten teks ada di file index.html. Cari bagian yang ingin diubah dan edit sesuai kebutuhan.

Mengganti Gambar

Simpan gambar baru ke folder images/

Ganti bagian gambar di product-card dengan tag <img>:

<div class="product-image">
    <img src="images/products/produk1.jpg" alt="Produk">
</div>

Responsive Breakpoints

Desktop: > 1024px

Tablet: 768px - 1024px

Mobile: < 768px

Small Mobile: < 480px

Fitur JavaScript
Main.js

Mobile navigation toggle

Smooth scroll

Navbar scroll effect

Notification system

Product interaction

Animations.js

Scroll reveal animation

Parallax effect

Card tilt effect

Progress bar

Cursor trail (opsional)

Tips Penggunaan

Optimasi gambar sebelum upload untuk performa lebih baik

Update meta tags di <head> sesuai bisnis Anda

Tambahkan Google Analytics untuk tracking

Gunakan hosting seperti Netlify, Vercel, atau GitHub Pages untuk domain custom

Deploy ke Hosting
Netlify (Gratis)

Daftar di Netlify

Drag & drop folder template

Domain otomatis tersedia

Vercel (Gratis)

Daftar di Vercel

Connect repository GitHub

Deploy otomatis

GitHub Pages (Gratis)

Push code ke GitHub repository

Settings → Pages

Select branch dan folder

Save

Tools yang Direkomendasikan

VS Code - Code editor

Live Server - Local development server

GitLens - Git integration

Prettier - Code formatter

Auto Rename Tag - HTML tag editing

Support & Dokumentasi

Email: info@shophub.com

Website: www.shophub.com

Dokumentasi: docs.shophub.com

Lisensi

Template ini menggunakan lisensi MIT. Anda bebas menggunakan untuk project personal maupun komersial.

Credits

Designer & Developer: Your Name

Icons: System icons

Font: System fonts (Segoe UI)

Update Log
Version 1.0.0 (2024)

Initial release

Responsive design

6 product cards

4 feature sections

3 testimonials

Smooth animations

Mobile menu