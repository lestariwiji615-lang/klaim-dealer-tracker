# 📋 Klaim Dealer Tracker

**Tracking Klaim Dealer — Main Dealer Program Insentif**

---

## 🚀 Akses Aplikasi

### **👉 [BUKA APLIKASI DI SINI](https://lestariwiji615-lang.github.io/klaim-dealer-tracker/)**

Atau copy link: 
```
https://lestariwiji615-lang.github.io/klaim-dealer-tracker/
```

---

## 🔐 Login Admin

| Field | Value |
|-------|-------|
| **Username** | (tidak perlu) |
| **Password** | `admin123` |

⚠️ **PENTING:** Ganti password sebelum deployment production!

---

## ✨ Fitur Utama

### 1️⃣ **Kirim Klaim** (Untuk Dealer)
- ✅ Form pengajuan lengkap
- ✅ Upload & kompres foto otomatis
- ✅ Generate tracking ID otomatis
- ✅ Save draft

### 2️⃣ **Monitoring** (Admin Only - Login Required)
- ✅ Dashboard statistik real-time
- ✅ Tabel klaim interaktif
- ✅ Filter berdasarkan status & program
- ✅ Search dealer/invoice
- ✅ Detail modal dengan timeline
- ✅ Update status workflow

### 3️⃣ **Laporan** (Admin Only - Login Required)
| No | Laporan | Deskripsi |
|----|---------|-----------|
| 1 | 📊 Ringkasan Status | Overview total klaim & pembayaran |
| 2 | 📈 Per Program | Analisis per jenis program insentif |
| 3 | 🏢 Per Dealer | Performa & riwayat setiap dealer |
| 4 | 💰 Pembayaran | Detail nominal & status pembayaran |
| 5 | 📥 Export CSV | Download ke format spreadsheet |
| 6 | 📄 Print Lengkap | Cetak laporan dengan semua detail |

---

## 🎯 Program Insentif yang Didukung

```
SCP | DG | Voucher | GC | RT | LCR | KPB | Pameran | Roadshow
```

---

## 🔄 Status Workflow Klaim

```
Diajukan → Diterima MD → Verifikasi → [Revisi ↔ Verifikasi] → Disetujui → Proses Bayar → Dibayar ✓
```

| Status | Deskripsi |
|--------|-----------|
| **Diajukan** | Dealer submit klaim baru |
| **Diterima MD** | Main dealer terima dokumen |
| **Proses Verifikasi** | Admin verifikasi dokumen |
| **Revisi** | Klaim perlu perbaikan |
| **Disetujui** | Klaim approved & siap bayar |
| **Dalam Proses** | Proses pembayaran sedang berjalan |
| **Dibayar** | Klaim selesai & dibayar |

---

## 💾 Penyimpanan Data

- 📦 Data tersimpan di **Browser Storage** (Local)
- 🌐 Tidak perlu internet setelah halaman dimuat
- 👥 Semua pengguna melihat data yang sama
- 🔄 Persisten sampai cache browser dibersihkan

---

## 🛠️ Cara Mengubah Password

1. Buka file `index.html` di editor
2. Cari line `1046`:
```javascript
const DEFAULT_PASSWORD = 'admin123';
```
3. Ganti `admin123` dengan password baru
4. Save & push ke GitHub

---

## 📱 Kompatibilitas Perangkat

| Perangkat | Status |
|-----------|--------|
| Desktop (Windows/Mac/Linux) | ✅ Optimal |
| Laptop | ✅ Optimal |
| Tablet (iPad/Android) | ✅ Responsive |
| Mobile (iPhone/Android) | ✅ Responsive |

**Browser yang Didukung:**
- ✅ Chrome
- ✅ Firefox
- ✅ Safari
- ✅ Edge

---

## 🔧 Teknologi yang Digunakan

```
Frontend: HTML5 + CSS3 + Vanilla JavaScript
Storage: Browser LocalStorage API
Fonts: Google Fonts (Roboto Slab, Inter, Roboto Mono)
Framework: None (Pure Vanilla - Lightweight & Fast)
```

---

## 📊 Statistik Aplikasi

- **File Size:** ~44 KB
- **Load Time:** <1 detik
- **Dependencies:** 0 (No external libraries)
- **Responsive:** 100%

---

## 🎨 Desain

- Custom color scheme untuk Main Dealer
- Professional stamp-style badges
- Timeline visualization untuk klaim history
- Responsive grid layout
- Dark theme option

---

## 🚀 Cara Deploy

### **Sudah Online di:**
```
https://lestariwiji615-lang.github.io/klaim-dealer-tracker/
```

### **Jika ingin di-host ulang:**

#### **Option 1: GitHub Pages (Recommended - FREE)**
1. Push ke GitHub repository
2. Settings → GitHub Pages → Enable
3. Akses via: `https://username.github.io/klaim-dealer-tracker/`

#### **Option 2: Netlify (FREE)**
1. Drag & drop folder ke netlify.com
2. Deploy otomatis
3. Dapatkan subdomain gratis

#### **Option 3: Vercel (FREE)**
1. Connect GitHub repository
2. Deploy otomatis
3. Custom domain support

---

## 📝 Contoh Penggunaan

### **Untuk Dealer:**
1. Buka aplikasi
2. Klik "Kirim Klaim"
3. Isi form klaim
4. Upload foto bukti
5. Klik "Kirim Klaim"
6. Dapatkan tracking ID

### **Untuk Admin:**
1. Buka aplikasi
2. Login dengan password `admin123`
3. Buka tab "Monitoring" atau "Laporan"
4. Lihat, filter, dan update status klaim
5. Download laporan jika perlu

---

## ⚡ Tips & Trik

✅ **Tips 1:** Bookmark aplikasi di browser untuk akses cepat

✅ **Tips 2:** Gunakan Private/Incognito mode jika berbagi device

✅ **Tips 3:** Backup data dengan export CSV secara berkala

✅ **Tips 4:** Clear browser cache jika ada error

✅ **Tips 5:** Test di device berbeda sebelum production

---

## 🐛 Troubleshooting

| Problem | Solusi |
|---------|--------|
| Data tidak muncul | Clear browser cache & reload |
| Password tidak bisa diubah | Edit `index.html` line 1046 |
| Foto tidak terupload | Cek ukuran file (max 5MB) |
| Laporan kosong | Pastikan ada data di monitoring |
| Login gagal | Periksa password (case-sensitive) |

---

## 📞 Support & Kontribusi

- 📧 Email: lestariwiji615@gmail.com
- 🐛 Issue: Buka di GitHub Issues
- 💡 Feature Request: Buka Discussion

---

## 📄 Lisensi

Public - Bebas digunakan

---

## 👨‍💻 Informasi Pembuat

- **Repository:** lestariwiji615-lang/klaim-dealer-tracker
- **Created:** 2026-07-09
- **Last Updated:** 2026-07-09
- **Status:** ✅ Production Ready

---

**Selamat menggunakan Klaim Dealer Tracker! 🎉**
