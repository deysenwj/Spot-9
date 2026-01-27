# Kampung Warna Warni Jodipan - Mobile Website

Website mobile-optimized dengan aspek rasio 9:16 untuk Google Sites.

## 📁 Struktur Folder yang Harus Dibuat

```
jodipan-project/
│
├── index.html                 # File HTML utama (sudah disediakan)
│
└── images/                    # Folder untuk menyimpan gambar
    └── jembatan-besi.jpg      # Foto jembatan besi tua (ANDA HARUS MENAMBAHKAN INI)
```

## 🎯 Langkah-Langkah Setup

### 1. Buat Folder Project
```bash
mkdir jodipan-project
cd jodipan-project
```

### 2. Buat Folder Images
```bash
mkdir images
```

### 3. Tambahkan Gambar
- Simpan foto jembatan besi Anda dengan nama: `jembatan-besi.jpg`
- Letakkan di folder `images/`
- Rekomendasi ukuran gambar: 1080x1920px (9:16) atau minimal 720x1280px
- Format: JPG atau PNG
- Ukuran file: maksimal 500KB untuk loading cepat

### 4. Struktur Akhir
```
jodipan-project/
├── index.html
└── images/
    └── jembatan-besi.jpg
```

## 🚀 Upload ke GitHub

### 1. Inisialisasi Git Repository
```bash
git init
git add .
git commit -m "Initial commit: Jodipan mobile website"
```

### 2. Buat Repository di GitHub
- Buka https://github.com
- Klik "New Repository"
- Nama repository: `jodipan-heritage`
- Pilih "Public"
- Jangan centang "Initialize with README"

### 3. Push ke GitHub
```bash
git remote add origin https://github.com/USERNAME/jodipan-heritage.git
git branch -M main
git push -u origin main
```

### 4. Aktifkan GitHub Pages
- Buka Settings repository
- Scroll ke "Pages"
- Source: pilih "main" branch
- Folder: pilih "/ (root)"
- Save

URL website Anda: `https://USERNAME.github.io/jodipan-heritage/`

## 🔗 Implementasi di Google Sites

### Opsi 1: Embed URL (Recommended)
1. Di Google Sites, pilih "Insert" → "Embed URL"
2. Paste URL GitHub Pages Anda
3. Sesuaikan ukuran frame

### Opsi 2: Custom HTML (Advanced)
1. Di Google Sites, pilih "Insert" → "Embed"
2. Pilih "Embed code"
3. Paste kode iframe:
```html
<iframe 
  src="https://USERNAME.github.io/jodipan-heritage/" 
  width="100%" 
  height="800" 
  frameborder="0"
  style="border:0; max-width: 480px; margin: 0 auto; display: block;">
</iframe>
```

## 📱 Spesifikasi Mobile
- Aspek Rasio: 9:16
- Viewport: Responsive
- Font: Auto-scaling
- Touch: Optimized
- Loading: Lazy load untuk performa

## 🎨 Kustomisasi

### Mengganti Gambar Lain
Jika ingin menambahkan gambar spot lain:
1. Tambahkan foto di folder `images/`
2. Beri nama deskriptif, contoh: `rumah-warna.jpg`
3. Edit `index.html` pada bagian:
```html
<img src="images/NAMA-GAMBAR.jpg" alt="Deskripsi">
```

### Menambahkan Frame/Section Baru
Duplikasi section di `index.html` dan sesuaikan konten.

## 🆘 Troubleshooting

### Gambar Tidak Muncul?
- ✅ Pastikan nama file sama persis: `jembatan-besi.jpg`
- ✅ Cek folder `images/` sudah ada
- ✅ Huruf kecil semua untuk nama file
- ✅ Ekstensi file benar (.jpg bukan .jpeg atau .JPG)

### GitHub Pages Tidak Aktif?
- Tunggu 2-5 menit setelah push pertama
- Cek Settings → Pages apakah sudah hijau
- Clear browser cache

### Di Google Sites Tidak Responsive?
- Gunakan opsi "Embed URL" bukan "Embed code"
- Pastikan Google Sites dalam mode "Mobile preview"

## 📞 Support
Jika ada masalah, cek:
- GitHub repository: Public/Private status
- File structure: sesuai contoh di atas
- Image path: case-sensitive

---
**Created for Kampung Warna Warni Jodipan Digital Heritage Project**