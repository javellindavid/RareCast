# 🎲 Rare-Cast — Diecast Intelligence PWA

> Alat Intelijen Diecast untuk kolektor dan reseller. Scan, nilai, dan jual diecast langka dengan presisi dan kecepatan.

---

## 🚀 Cara Deploy (Gratis)

### Option 1: Vercel (Rekomendasi)
1. Buat akun di [vercel.com](https://vercel.com)
2. Install Vercel CLI: `npm i -g vercel`
3. Masuk ke folder project: `cd rare-cast`
4. Jalankan: `vercel --prod`
5. Buka URL yang diberikan di browser mobile → **"Add to Home Screen"**

### Option 2: Netlify
1. Buka [netlify.com](https://netlify.com)
2. Drag & drop folder `rare-cast` ke dashboard Netlify
3. Selesai! URL langsung aktif.

### Option 3: GitHub Pages
1. Upload semua file ke GitHub repo
2. Aktifkan GitHub Pages di Settings → Pages
3. Set source ke branch `main`, folder `/` (root)

---

## 📱 Install sebagai App (PWA)

### Android (Chrome)
1. Buka URL di Chrome
2. Tap menu **⋮** → **"Add to Home Screen"**
3. Tap **Install**

### iOS (Safari)
1. Buka URL di Safari
2. Tap **Share** (kotak panah ke atas)
3. Pilih **"Add to Home Screen"**

---

## ✨ Fitur Lengkap

| Fitur | Deskripsi |
|-------|-----------|
| 📷 Visual Scan AI | Identifikasi diecast via kamera + AI |
| 📶 Barcode Scan | Scan barcode EAN/UPC produk |
| 🏆 Rare-Indicator | Haptic + efek emas saat item langka ditemukan |
| 🚦 Profit Traffic Light | Hijau/Kuning/Merah otomatis |
| 💰 Net-Margin Calculator | Hitung fee Shopee/Tokopedia/TikTok/FB |
| 📦 Grade-Price Adjustment | Slider kondisi kemasan 50–100% |
| 🏪 Digital Storefront | Toko pribadi + integrasi WhatsApp |
| 📊 Inventaris Digital | Kelola koleksi diecast kamu |

---

## 🗂️ Struktur File

```
rare-cast/
├── index.html          ← Aplikasi utama (single-page)
├── manifest.json       ← PWA manifest
├── service-worker.js   ← Offline support & caching
├── offline.html        ← Halaman offline fallback
├── favicon.ico         ← Favicon
├── README.md           ← Dokumentasi ini
├── icons/
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png    ← Digunakan manifest (maskable)
│   ├── icon-384x384.png
│   ├── icon-512x512.png    ← Digunakan manifest (maskable)
│   ├── apple-touch-icon.png
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── screenshot1.png     ← Preview install prompt
│   └── screenshot2.png     ← Preview install prompt
└── assets/
    └── (folder untuk file tambahan di masa depan)
```

---

## 🛠️ Tech Stack

- **Framework**: Vanilla JS + HTML5 + CSS3 (PWA)
- **Hosting**: Vercel / Netlify (gratis)
- **Storage**: localStorage (data lokal di device)
- **Fonts**: Google Fonts (Syne + DM Sans)
- **Offline**: Service Worker + Cache API

---

## 🔮 Pengembangan Selanjutnya

- [ ] Integrasi `html5-qrcode` untuk scan barcode nyata
- [ ] Integrasi Google Vision API untuk identifikasi visual
- [ ] Backend Supabase untuk database cloud
- [ ] Login / akun pengguna
- [ ] Push notification temuan langka
- [ ] Export katalog ke PDF/WhatsApp

---

## 📞 Support

Hubungi via WhatsApp yang sudah dikonfigurasi di **Pengaturan → Nomor WhatsApp Toko**.

---

*Made with ❤️ for the Indonesian Diecast Community*
