# Asa Invoice Automation 💰📄

Sistem otomatisasi penagihan (Fintech Automation) yang mengubah input formulir menjadi dokumen invoice PDF profesional secara instan.

## 🚀 Fitur Utama
- **Automated Calculation**: Menghitung total tagihan secara presisi dengan pembersihan format angka otomatis.
- **Professional PDF Template**: Desain invoice menggunakan HTML5/CSS3 yang bersih dan modern (Tanpa elemen visual yang mengganggu).
- **Auto-Distribution**: Pengiriman langsung ke email klien dengan lampiran file biner.
- **Error Handling**: Logika JavaScript yang kuat untuk menangani berbagai jenis input angka.

## 🛠️ Konfigurasi Node
- **Form Trigger**: Input (Nama, Jam, Rate, Email).
- **Edit Fields**: Kalkulasi `(Jam * Rate)` & Format IDR.
- **HTML Node**: Template dokumen dinamis.
- **HTTP Request**: Konversi HTML ke PDF via API.
- **Gmail Node**: Pengiriman lampiran menggunakan property `data`.

## 📦 Cara Instalasi
1. Download file `Asa_Invoice_Otomatis.json`.
2. Import ke dalam workflow n8n Anda.
3. Sambungkan kredensial **Gmail OAuth2**.
4. Gunakan API Key favorit Anda pada node konversi PDF.
