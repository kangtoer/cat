# NUSANTARA CAT & CBT PRO
**Platform Asesmen Digital Terstandar BSNP & BSKAP (Kurikulum Merdeka Fase D)**

> **Dibuat oleh [Catur Pamungkas](https://toer.my.id) — [Catatan Guru IPS](https://whatsapp.com/channel/0029Vb6R2Ny2v1J1dll5Mq27)**

## Keunggulan Utama
1. **100% Mandiri Online & Offline (Gratis Selamanya)**: Berbasis HTML5, CSS3, dan ES6 murni dengan penyimpanan otomatis `localStorage`, Service Worker (`sw.js`), dan PWA (`manifest.json`).
2. **Terstandar BSNP & BSKAP Kurikulum Merdeka Fase D**: Memuat 180 butir soal HOTS L3 (C4 Analisis, C5 Evaluasi, C6 Mencipta) untuk SMP/MTs Kelas VII, VIII, dan IX (Paket 1 & Paket 2).
3. **Dual Engine (CBT Standar & CAT Adaptif)**: Dilengkapi estimasi kemampuan real-time (Skor Theta), timer otomatis, penanda ragu-ragu, dan anti-cheat deteksi pindah tab.
4. **Multi-Peran Lengkap**:
   - **Portal Peserta Didik**: Login mandiri, CBT/CAT engine, ekspor paket hasil offline (`.json` & Kode Token), dan integrasi latihan berulang **Wayground**.
   - **Portal Proctor**: Kontrol token ujian, monitoring real-time, force submit, reset, dan impor hasil ujian offline siswa.
   - **Portal Guru Mapel (Admin)**: Koreksi otomatis PG, penilaian Uraian berbasis rubrik (manual & auto-skor kata kunci), analisis diagnostik per individu dengan **Google Gemini AI (`gemini-2.5-flash`)** atau **Mesin Diagnostik Offline**, serta generator **Laporan Hasil Studi PDF**.

## Cara Deploy Gratis Selamanya di GitHub Pages
1. Buat repositori publik baru di [GitHub](https://github.com/new) (misal: `nusantara-cat-cbt-pro`).
2. Unggah file `index.html`, `sw.js`, `manifest.json`, `README.md`, dan folder `.github/workflows/pages.yml`.
3. Buka tab **Settings → Pages** pada repositori Anda, lalu pilih **Source: GitHub Actions** (atau **Deploy from a branch: main / root**).
4. Selesai! Aplikasi dapat diakses online dari HP, Tablet, Chromebook, Laptop, maupun diunduh untuk dijalankan offline.