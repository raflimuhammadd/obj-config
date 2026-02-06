# APD Detection System - Documentation Site

Situs dokumentasi untuk Sistem Deteksi APD (Alat Pelindung Diri) Real-Time.

## 🚀 Deployment ke Netlify

### Cara Deploy:

1. **Push ke GitHub:**
   ```bash
   git add .
   git commit -m "Restructure for Netlify deployment"
   git push origin main
   ```

2. **Deploy di Netlify:**
   - Buka [Netlify](https://app.netlify.com)
   - Klik "Add new site" → "Import an existing project"
   - Pilih GitHub dan repository Anda
   - Netlify akan otomatis mendeteksi konfigurasi dari `netlify.toml`
   - Klik "Deploy site"

### Konfigurasi Otomatis:

File `netlify.toml` sudah dikonfigurasi dengan:
- ✅ Publish directory: root folder
- ✅ Redirects untuk SPA routing
- ✅ Security headers
- ✅ Caching optimization

## 📁 Struktur Folder

```
obj-config/
├── index.html              # Halaman utama dengan daftar dokumentasi
├── README.html             # Project overview
├── INSTALLATION.html       # Panduan instalasi
├── CONFIGURATION.html      # Referensi konfigurasi
├── USER_GUIDE.html         # Panduan pengguna
├── style.css               # Stylesheet
├── netlify.toml            # Konfigurasi Netlify
└── README.md               # File ini
```

## 🌐 Akses Lokal

Untuk akses lokal, cukup buka `index.html` di browser Anda.

## 📖 Dokumentasi

Setelah deploy, akses dokumentasi melalui:
- `https://your-site.netlify.app/` - Halaman utama
- `https://your-site.netlify.app/README.html` - Overview
- `https://your-site.netlify.app/INSTALLATION.html` - Instalasi
- `https://your-site.netlify.app/CONFIGURATION.html` - Konfigurasi
- `https://your-site.netlify.app/USER_GUIDE.html` - User Guide

## 💡 Tips

- Setiap kali Anda push ke GitHub, Netlify akan otomatis re-deploy
- Anda bisa menggunakan custom domain di Netlify dashboard
- Deploy preview otomatis dibuat untuk setiap pull request

---

Made with ❤️ for workplace safety
