# Web Profil — Tugas UTS

Website profil pribadi statis (HTML + CSS + sedikit JavaScript) untuk
memenuhi tugas Penilaian Tengah Semester. Tidak butuh instalasi apapun,
cukup dibuka langsung di browser.

## Isi tugas yang sudah dicakup

1. Biodata
2. Galeri Foto
3. Deskripsi Pribadi
4. Riwayat Pendidikan
5. Riwayat Organisasi
6. Kelebihan
7. Prestasi
8. Kompetensi
9. Portofolio Karya

## Cara mengisi konten

Semua teks placeholder ditandai dengan format `[Isi ...]` — buka
`index.html`, cari teks itu (Ctrl+F di editor), lalu ganti dengan data
kamu sendiri.

## Cara mengganti foto

1. Siapkan foto profil dan foto-foto galeri/karya kamu.
2. Simpan ke folder `assets/img/` dengan nama file berikut (atau ganti
   nama file di `index.html` sesuai nama file kamu):
   - `profil.jpg` — foto profil di bagian Biodata
   - `galeri1.jpg` sampai `galeri6.jpg` — foto di bagian Galeri
   - `karya1.jpg` sampai `karya3.jpg` — thumbnail di bagian Portofolio Karya
3. Selama foto belum ada, halaman otomatis menampilkan gambar placeholder
   abu-abu supaya layout tetap terlihat rapi.

## Cara melihat hasilnya

Buka file `index.html` langsung di browser (double-click, atau klik kanan
→ Open with → Chrome). Tidak perlu server atau instalasi apapun.

## Cara mengumpulkan ke GitHub

1. Buat akun GitHub kalau belum punya (github.com).
2. Buat repository baru (New repository), beri nama misalnya
   `web-profil-uts`, biarkan public, jangan centang tambahkan README
   (karena sudah ada).
3. Upload semua file di folder ini (index.html, style.css, script.js,
   folder assets, README.md) lewat tombol "uploading an existing file"
   di halaman repository, atau lewat Git di terminal:
   ```bash
   git init
   git add .
   git commit -m "Tugas UTS - Web Profil"
   git branch -M main
   git remote add origin https://github.com/username/web-profil-uts.git
   git push -u origin main
   ```
4. (Opsional, biar bisa dibuka lewat link web) Aktifkan GitHub Pages:
   buka Settings → Pages → pada bagian Branch pilih `main` dan folder
   `/ (root)` → Save. Setelah beberapa menit, situs kamu bisa diakses di
   `https://username.github.io/web-profil-uts/`.
5. Kumpulkan link repository (dan link GitHub Pages kalau diaktifkan)
   sesuai instruksi dosen.
