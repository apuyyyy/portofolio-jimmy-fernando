# 🌟 Portofolio Profesional — Jimmy Fernando

Website portofolio profesional dan interaktif untuk **Jimmy Fernando** (Fullstack Developer & UI/UX Enthusiast), dibangun dengan standar industri terkini, desain modern minimalis, dan performa tinggi.

---

## 🚀 Tech Stack

- **HTML5** — Semantik modern, SEO-friendly, dan aksesibel
- **Tailwind CSS (via CDN)** — Styling elegan dengan skema warna indigo/violet profesional
- **Vanilla JavaScript (ES6+)** — Animasi mikro, scroll observer, dark mode toggle, dan modal interaktif tanpa dependensi berat
- **Font Awesome 6 & Google Fonts** — Ikonografi komprehensif dan tipografi Inter & Poppins

---

## ✨ Fitur & Keunggulan Desain

- 🌓 **Dark / Light Mode Toggle**: Pengalihan tema instan yang tersimpan otomatis di `localStorage` dan menyesuaikan preferensi sistem operasi pengguna.
- 📱 **Mobile-First & Responsif Penuh**: Tata letak adaptif yang nyaman diakses melalui smartphone, tablet, laptop, hingga layar monitor lebar.
- 🎬 **Micro-Interactions & Scroll Animations**: Animasi floating particle, typing hero effect, observer-based fade-in/slide-up saat scroll, dan counter angka statistik.
- 💼 **Interactive Project Modal**: Pop-up modal interaktif untuk melihat rincian setiap proyek (latar belakang, fitur utama, dan tech stack).
- 📄 **Langsung Unduh CV**: Tombol CTA terintegrasi langsung untuk mengunduh berkas `CV_Jimmy_Fernando.pdf`.
- 📬 **Form Kontak & Social Channels**: Formulir terstruktur dengan feedback interaktif serta tautan langsung ke LinkedIn, GitHub, Email, dan Telepon.
- ⚡ **Zero Build Step**: Siap langsung dijalankan di browser manapun tanpa perlu build tools yang rumit.

---

## 📂 Struktur Berkas

```
Portofolio Jimmy Fernando/
├── index.html               # Halaman portofolio utama (all-in-one)
├── profile.png              # Foto profil resmi Jimmy Fernando
├── CV_Jimmy_Fernando.pdf    # Dokumen CV asli yang dapat diunduh
├── vercel.json              # Konfigurasi routing static Vercel
├── .gitignore               # Pengabaian berkas sementara
└── README.md                # Panduan teknis & cara hosting
```

---

## 🌐 Panduan Hosting & Deployment

### 1. Upload ke GitHub

Jalankan perintah berikut di PowerShell atau Command Prompt Anda:

```bash
# 1. Pastikan Anda sudah membuat repository baru di GitHub (misal: "portfolio")
# 2. Hubungkan repository lokal ke GitHub Anda:
git remote add origin https://github.com/USERNAME_GITHUB_ANDA/portfolio.git

# 3. Rename branch ke main (jika belum):
git branch -M main

# 4. Push seluruh kode ke GitHub:
git push -u origin main
```

*(Catatan: Ganti `USERNAME_GITHUB_ANDA` dengan username akun GitHub Anda).*

---

### 2. Deploy ke Vercel (Otomatis & Gratis)

Ada 2 cara mudah untuk deploy ke Vercel:

#### **Metode A: Melalui Dashboard Vercel (Paling Mudah)**
1. Kunjungi [vercel.com](https://vercel.com) lalu masuk/daftar menggunakan akun **GitHub** Anda.
2. Klik tombol **"Add New..."** > **"Project"**.
3. Pilih repository `portfolio` yang sudah di-push tadi, lalu klik **"Import"**.
4. Biarkan konfigurasi default (Framework Preset: *Other* / Root Directory: `./`).
5. Klik **"Deploy"**. Dalam hitungan detik website portofolio Anda sudah aktif dengan domain gratis (contoh: `portfolio-jimmy.vercel.app`) lengkap dengan HTTPS/SSL gratis!

#### **Metode B: Melalui Vercel CLI**
```bash
# Install Vercel CLI (jika memiliki Node.js):
npm install -g vercel

# Jalankan deploy:
vercel
```

---

### 3. Deploy Alternatif ke GitHub Pages (Opsional)

Jika ingin mengaktifkan GitHub Pages secara langsung:
1. Buka repository Anda di GitHub.
2. Masuk ke menu **Settings** > tab **Pages** (di sisi kiri).
3. Pada bagian **Build and deployment > Branch**, pilih branch `main` dan folder `/ (root)`.
4. Klik **Save**. Website Anda akan aktif di `https://USERNAME_GITHUB_ANDA.github.io/portfolio/`.

---

## 👤 Kontak Jimmy Fernando

- **Email**: jimmyfrnn12@gmail.com
- **Telepon / WhatsApp**: +62 813 8464 8798
- **Lokasi**: Cakung Timur, Jakarta Timur, DKI Jakarta
