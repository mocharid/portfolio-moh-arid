# Portfolio Moh. Arid

Website portfolio pribadi milik **Muhamad Farid Indrawan (Moh. Arid)**, fresh graduate Teknik Informatika Universitas Suryakancana. Website ini dibuat sebagai media untuk menampilkan profil, kemampuan teknis, pengalaman kerja praktik, proyek, skripsi, pendidikan, sertifikat, dan informasi kontak.

## Preview

Portfolio ini menggunakan tema **dark developer** dengan nuansa biru, tampilan responsif untuk desktop dan perangkat mobile, animasi ringan saat section muncul, serta halaman one-page dengan navigasi smooth scroll.

## Profil

- **Nama:** Muhamad Farid Indrawan
- **Nama portfolio:** Moh. Arid
- **Status:** Fresh Graduate Teknik Informatika
- **Universitas:** Universitas Suryakancana
- **IPK:** 3,51 / 4,00 — Predikat Dengan Pujian
- **Domisili:** Kabupaten Cianjur, Jawa Barat
- **Email:** ariddd.edu@gmail.com
- **GitHub:** [github.com/mocharid](https://github.com/mocharid)

## Fitur

- Tampilan satu halaman responsif
- Navbar dengan navigasi ke setiap section
- Dark developer theme dengan efek grid dan glow biru
- Bagian profil, kemampuan, proyek, pengalaman, pendidikan, sertifikat, dan kontak
- Tombol download CV
- Link GitHub, email, dan WhatsApp
- Animasi section saat halaman di-scroll
- Foto profil dengan efek glow, shadow, dan tepi yang dibuat menyatu dengan background
- Pencegahan drag gambar dan klik kanan pada area foto sebagai perlindungan dasar

> Catatan: Pencegahan drag dan klik kanan hanya mengurangi akses biasa pada browser. Foto yang ditampilkan di website tetap tidak dapat dilindungi sepenuhnya dari screenshot, DevTools, atau pengunduhan oleh pengguna yang memahami cara teknis.

## Project Unggulan

### 1. KASDIG — Aplikasi Bank Mini Sekolah

Aplikasi web untuk mendukung pengelolaan Bank Mini SMK Plus Ashabulyamin Cianjur. Fitur utamanya mencakup pengelolaan data siswa, transaksi tabungan, pencatatan, dan laporan.

- **Kategori:** Kerja Praktik
- **Teknologi:** PHP, HTML, CSS, JavaScript, MySQL
- **Live demo:** [bankminiashabulyamin.web.id](https://bankminiashabulyamin.web.id/)

### 2. Data Warehouse Analisis Persebaran Dapur MBG

Proyek skripsi mengenai implementasi data warehouse untuk menganalisis persebaran dapur Makan Bergizi Gratis (MBG) dan mendukung rekomendasi prioritas pembangunan Satuan Pelayanan Pemenuhan Gizi (SPPG) di Kabupaten Cianjur.

- **Kategori:** Skripsi / Academic Project
- **Teknologi:** Data Warehouse, ETL, OLAP, SQL, Python
- **Status:** Dalam pengembangan

## Struktur Folder

```text
portfolio-moh-arid/
├── index.html
├── README.md
├── .gitignore
└── assets/
    ├── Pas_Photo-2.jpg
    └── cv-muhamad-farid-indrawan.pdf
```

## Menjalankan Secara Lokal

1. Download atau clone repository ini.
2. Pastikan file foto tersedia pada lokasi berikut:

```text
assets/Pas_Photo-2.jpg
```

3. Jika ingin tombol **Download CV** berfungsi, masukkan CV dengan nama berikut:

```text
assets/cv-muhamad-farid-indrawan.pdf
```

4. Buka `index.html` secara langsung di browser, atau gunakan ekstensi **Live Server** di Visual Studio Code.

### Menggunakan Live Server di VS Code

1. Buka folder project di Visual Studio Code.
2. Install extension **Live Server** jika belum tersedia.
3. Klik kanan file `index.html`.
4. Pilih **Open with Live Server**.

## Mengubah Data Portfolio

Data utama berada langsung di file `index.html`. Sebelum atau setelah publikasi, kamu dapat mengganti bagian berikut:

| Data | Yang dicari di `index.html` |
|---|---|
| Nama | `Muhamad Farid Indrawan` |
| Nama branding | `Moh. Arid` |
| Email | `ariddd.edu@gmail.com` |
| Nomor WhatsApp | `62895406725790` |
| GitHub | `https://github.com/mocharid` |
| Lokasi foto | `assets/Pas_Photo-2.jpg` |
| Lokasi CV | `assets/cv-muhamad-farid-indrawan.pdf` |

Jika nama file foto diubah, sesuaikan bagian berikut:

```html
<img class="portrait" src="assets/Pas_Photo-2.jpg" alt="Foto profil Muhamad Farid Indrawan" />
```

## Upload ke GitHub

### Upload melalui website GitHub

1. Buat repository baru dengan nama, misalnya, `portfolio-moh-arid`.
2. Pilih repository **Public**.
3. Klik **Add file** → **Upload files**.
4. Upload semua isi folder project: `index.html`, `README.md`, `.gitignore`, serta folder `assets`.
5. Klik **Commit changes**.

### Upload menggunakan Git

Jalankan perintah berikut di terminal pada folder project:

```bash
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin https://github.com/mocharid/portfolio-moh-arid.git
git push -u origin main
```

> Ganti URL repository pada perintah `git remote add origin` jika nama repository kamu berbeda.

## Deploy dengan GitHub Pages

1. Buka repository di GitHub.
2. Buka menu **Settings**.
3. Pilih **Pages** pada sidebar.
4. Pada bagian **Build and deployment**, pilih:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main`
   - **Folder:** `/(root)`
5. Klik **Save**.
6. Tunggu beberapa saat hingga GitHub Pages selesai membangun website.
7. URL website biasanya berbentuk:

```text
https://mocharid.github.io/portfolio-moh-arid/
```

## Teknologi

- HTML5
- CSS3
- JavaScript
- Google Fonts: Inter dan Poppins
- GitHub Pages untuk hosting statis

## Kontak

- Email: [ariddd.edu@gmail.com](mailto:ariddd.edu@gmail.com)
- WhatsApp: [0895406725790](https://wa.me/62895406725790)
- GitHub: [github.com/mocharid](https://github.com/mocharid)

---

© 2026 Muhamad Farid Indrawan. Dibuat dengan HTML, CSS, dan JavaScript.