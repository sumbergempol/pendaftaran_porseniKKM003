# Sistem Pendaftaran PORSENI KKM 003 NGUMPOBAN

Aplikasi formulir pendaftaran peserta Pekan Olahraga dan Seni (PORSENI) tingkat MI se-KKM 003 NGUMPOBAN (Ngunut, Sumbergempol, Pucanglaban). Terintegrasi langsung dengan database Google Sheets dan Google Drive.

## 🚀 Cara Menjalankan di GitHub Pages

1. **Deploy Backend (Google Apps Script)**:
   - Buat project baru di [script.google.com](https://script.google.com).
   - Masukkan kode backend dari berkas `Code.gs`.
   - Klik **Deploy** > **New Deployment** > Jenis: **Web App**.
   - Set **Execute as**: *Me* dan **Who has access**: *Anyone*.
   - Salin **Web App URL** yang berakhiran `/exec`.

2. **Hubungkan Frontend**:
   - Buka berkas `index.html`.
   - Cari baris `const API_URL = "MASUKKAN_URL_WEB_APP_EXEC_DISINI";`.
   - Ganti nilainya dengan Web App URL yang disalin pada langkah ke-1.

3. **Aktifkan GitHub Pages**:
   - Masuk ke menu **Settings** pada repositori GitHub ini.
   - Pilih tab **Pages** di menu sebelah kiri.
   - Pada bagian **Build and deployment**, atur Branch: `main` (atau `master`) dan folder: `/ (root)`.
   - Klik **Save**.
   - Tunggu 1-2 menit hingga tautan publikasi aktif (contoh: `https://username.github.io/nama-repo/`).
