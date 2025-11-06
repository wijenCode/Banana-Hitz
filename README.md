# Banana Hitz - Website Form Pemesanan

Website pemesanan produk Banana Hitz dengan integrasi WhatsApp.

## 🚀 Fitur
- Form pemesanan online
- Perhitungan total otomatis
- Integrasi WhatsApp untuk pengiriman pesanan
- Responsive design
- Multiple menu items support
- Preview bukti pembayaran

## ⚙️ Setup

### 1. Clone Repository
```bash
git clone https://github.com/wijenCode/Banana_Hitz.git
cd Banana_Hitz
```

### 2. Konfigurasi WhatsApp
1. Copy file `config.example.js` menjadi `config.js`:
   ```bash
   copy config.example.js config.js
   ```
2. Edit `config.js` dan ganti nomor WhatsApp dengan nomor bisnis Anda:
   ```javascript
   const CONFIG = {
       businessWhatsApp: '6282162885153', // Ganti dengan nomor Anda
       businessName: 'Banana Hitz'
   };
   ```

### 3. Jalankan Website
Buka file `index.html` di browser Anda.

## 📁 Struktur File
```
BananaHitz/
├── index.html          # Halaman utama
├── order.html          # Form pemesanan
├── config.js           # Konfigurasi (JANGAN upload ke GitHub)
├── config.example.js   # Template konfigurasi
├── .gitignore          # File yang diabaikan Git
└── README.md           # Dokumentasi
```

## 🔒 Keamanan
File `config.js` berisi nomor WhatsApp bisnis dan **TIDAK boleh** diupload ke GitHub karena sudah ada di `.gitignore`.

Hanya upload `config.example.js` sebagai template.

## 📝 Cara Menggunakan

### Untuk Developer
1. Setup konfigurasi sesuai panduan di atas
2. Customize menu dan harga di `order.html`
3. Test form pemesanan
4. Deploy ke hosting pilihan Anda

### Untuk Customer
1. Buka website
2. Isi form pemesanan lengkap
3. Pilih menu dan jumlah pesanan
4. Klik "Kirim Pesanan via WhatsApp"
5. Lanjutkan konfirmasi di WhatsApp

## 🛠️ Teknologi
- HTML5
- CSS3 (Tailwind CSS)
- JavaScript (Vanilla)
- WhatsApp API

## 📞 Support
Jika ada pertanyaan, hubungi melalui WhatsApp di nomor yang tertera di website.

## 📄 License
© 2025 Banana Hitz. All Rights Reserved.
