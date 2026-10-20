# E-Portfolio Guru Profesional PPG

Template & source code E-Portfolio Seminar Pendidikan Profesi Guru (PPG), diadaptasi dan disesuaikan dari portofolio referensi [orisasatifaalqaf.github.io/e-portofolio-ppg](https://orisasatifaalqaf.github.io/e-portofolio-ppg/).

---

## 🌟 Fitur Utama

1. **Halaman Pembuka Interaktif (`index.html`)**
   - Efek animasi *scrapbook tear* dan kertas estetik bertema earth tone.
   - Navigasi pilihan portofolio (Topik 3, Topik 4, E-Portfolio 1 UTS, E-Portfolio 2 UAS).
   - Ornamen watermark bunga dan tekstur paper noise bertekstur.

2. **E-Portfolio 1 UTS (`portfolio.html`)**
   - **Interactive Particle Background**: Latar belakang partikel halus bergerak pada kanvas.
   - **Light / Dark Mode**: Tombol toggle tema gelap dan terang tersimpan otomatis di localStorage.
   - **Hero Section**: Kartu profil dengan animasi sambutan, badge LPTK & program studi, serta tombol tautan sosial media.
   - **Profil & Filosofi Mengajar**: Kutipan Ki Hadjar Dewantara dan refleksi nilai-nilai pengajaran.
   - **Riwayat Pendidikan**: Timeline interaktif dari SD, SMP, SMA, S1, hingga PPG dengan logo instansi.
   - **Artefak Pembelajaran (Multi-tier Filtering)**:
     - Filter berdasarkan **Siklus** (Semua, Siklus 1, Siklus 2, Siklus 3) dan **Kategori** (Modul Ajar, Bahan Ajar, Media Pembelajaran, LKM, Instrumen Asesmen, Rekap Nilai, Karya Siswa, Video Praktik).
     - Hover overlay dan tautan langsung ke Google Drive (PDF / Slide / Dokumen).
     - **Slide Drawer Analisis**: Panel geser interaktif untuk melihat refleksi, tantangan, solusi inovatif (PBL, CRT, TaRL), dan Rencana Tindak Lanjut (RTL).
   - **Penilaian & Evaluasi Pembelajaran**: Ringkasan evaluasi proses dan hasil belajar peserta didik.
   - **Model Guru Abad 21**: Refleksi kritis peran guru profesional.
   - **Galeri Foto Praktik**: Dokumentasi interaktif kegiatan PPL.
   - **Kontak & Footer**: Formulir dan tautan media sosial.

3. **E-Portfolio 2 UAS (`portfolio2.html`)**
   - Desain modern bernuansa *dark slate & amber gold*.
   - Navigasi langsung ke **Refleksi PPL Terbimbing** dan **Filosofi Mengajar**.
   - Dokumentasi praktik pengajaran dan aksi nyata di sekolah mitra PPL.

---

## 🚀 Cara Menjalankan di Komputer

1. **Cara Paling Mudah:**
   - Cukup klik dua kali (double-click) file `buka_portfolio.bat` di folder ini.
   - Atau klik kanan file `index.html` -> pilih **Open with** -> pilih browser (Google Chrome, Microsoft Edge, Firefox, dll.).

---

## ✏️ Panduan Personalisasi Data

Untuk menyesuaikan portofolio dengan identitas dan data Anda:

| Data yang Ingin Diubah | File Target | Keterangan |
| :--- | :--- | :--- |
| **Nama, Gelar, Biodata** | `index.html`, `portfolio.html`, `portfolio2.html` | Cari nama `Orisa Satifa Alqaf` dan ganti dengan nama Anda. |
| **Universitas / LPTK** | `index.html`, `portfolio.html`, `portfolio2.html` | Ganti `Universitas Ahmad Dahlan` dengan nama kampus PPG Anda. |
| **Program Studi / Bidang** | `portfolio.html`, `portfolio2.html` | Ganti `Pendidikan Bahasa dan Sastra Indonesia` dengan prodi Anda (misal: `PGSD`, `Matematika`, dll.). |
| **Foto Profil** | `foto-profil.jpg` & `gambar3.jpg` | Ganti file gambar ini dengan foto formal/toga Anda (gunakan nama file yang sama atau ubah path di html). |
| **Tautan Google Drive Artefak** | `portfolio.html` | Cari atribut `href="https://drive.google.com/..."` pada kartu modul/LKM/media dan ganti dengan link Google Drive file Anda. |
| **Sekolah Tempat PPL** | `portfolio2.html` & `portfolio.html` | Ganti `SMA Negeri 8 Yogyakarta` dengan nama sekolah mitra tempat Anda melaksanakan PPL. |

---

## 🌐 Cara Mengunggah (Hosting Gratis) ke GitHub Pages

Agar portofolio Anda memiliki alamat website online sendiri (misalnya: `https://username-anda.github.io/seminar-ppg/`):

1. Buat akun di [GitHub](https://github.com) jika belum punya.
2. Buat repositori baru bernama `seminar-ppg` (atau nama lain) dengan status **Public**.
3. Unggah seluruh file dari folder ini ke repositori tersebut.
4. Buka menu **Settings** pada repositori GitHub Anda -> pilih menu **Pages** di bilah kiri.
5. Pada bagian **Build and deployment**:
   - Source: pilih **Deploy from a branch**
   - Branch: pilih **main** (atau **master**), folder `/ (root)` -> klik **Save**.
6. Tunggu 1–2 menit, portofolio Anda sudah aktif dan dapat diakses publik oleh dosen penguji atau rekan sejawat!