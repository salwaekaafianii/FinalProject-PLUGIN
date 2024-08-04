## HTML
1. `<!DOCTYPE html>`: Menandakan bahwa ini adalah dokumen HTML5.
2. `<html lang="id">`: Menetapkan bahasa halaman sebagai bahasa Indonesia.
3. `<head>`: Berisi informasi metadata tentang halaman web, seperti charset, viewport, title, dan link ke file CSS.
   - `<meta charset="UTF-8">`: Menetapkan encoding karakter sebagai UTF-8.
   - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Memastikan halaman responsif dengan lebar perangkat.
   - `<title>Website Pribadi - Salwa Eka Afiani</title>`: Menetapkan judul halaman.
   - `<link rel="stylesheet" href="styles.css">`: Menghubungkan file CSS eksternal.

4. `<body>`: Berisi konten utama dari halaman web.
   - `<header>`: Bagian atas halaman dengan menu navigasi.
     - `<nav>`: Menyediakan tautan navigasi ke berbagai bagian halaman menggunakan list (`<ul>` dan `<li>`).
   - `<main>`: Bagian utama dengan empat bagian: Hallo, Tentang Saya, Pendidikan, Keahlian, dan Kontak.
     - `<section class="hallo">`: Menampilkan sambutan dan tautan sosial.
     - `<section id="about" class="about">`: Bagian tentang diri Anda dengan foto profil dan deskripsi.
     - `<section id="education" class="education">`: Menampilkan informasi pendidikan.
     - `<section id="skills" class="skills">`: Menampilkan keahlian dengan ikon dan deskripsi.
     - `<section id="contact" class="contact">`: Bagian kontak dengan formulir dan tautan media sosial.
   - `<footer>`: Bagian bawah halaman dengan hak cipta.

## CSS
**1. Reset CSS:**
   - `*.{ margin: 0; padding: 0; box-sizing: border-box; }`: Mengatur margin, padding, dan box-sizing untuk semua elemen untuk memastikan konsistensi.

**2. Gaya Umum:**
   - `body`: Mengatur font, ukuran teks, warna latar belakang, dan warna teks.
   - `header`: Menetapkan gaya untuk header termasuk latar belakang transparan, padding, posisi tetap, dan efek blur pada latar belakang. Juga, mengatur gaya untuk menu navigasi di dalamnya.

**3. Navigasi:**
   - `nav ul`: Mengatur tampilan menu navigasi dengan Flexbox untuk menyelaraskan item secara horizontal.
   - `nav ul li a`: Mengatur gaya tautan navigasi, termasuk warna, padding, dan transisi saat hover.

**4. Bagian/Section:**
   - `section`: Memberikan padding, latar belakang, dan memastikan setiap bagian memiliki jarak yang konsisten.

**5. Bagian Hallo:**
   - `.hallo`: Menetapkan latar belakang gradien dan padding untuk tampilan sambutan.

**6. Bagian Tentang Saya:**
   - `.about`: Mengatur tata letak untuk bagian "Tentang Saya" dengan foto profil dan teks yang disejajarkan.

**7. Bagian Pendidikan:**
   - `.education`: Mengatur tampilan bagian "Pendidikan" termasuk daftar item pendidikan.
   - `.education-intent-item-content`: Gaya untuk item daftar pendidikan dengan gambar, judul, dan informasi waktu.
     
**8. Bagian Keahlian:**
   - `.skills`: Memberikan gaya untuk elemen keahlian, termasuk efek hover untuk item keahlian.
   - `.skills-item`: Menetapkan gaya untuk setiap item keahlian, termasuk gambar dan deskripsi.

**9. Bagian Kontak:**
   - `.contact`: Mengatur gaya untuk formulir kontak dan deskripsi kontak.
   - `.contact-form`: Menetapkan gaya untuk formulir, termasuk padding, border, dan box-shadow.

**10. Footer:**
    - `footer`: Memberikan gaya dasar untuk bagian footer dengan warna latar belakang, teks, dan padding.

**11. Responsivitas:**
    - `@media (max-width: 1200px)`, `@media (max-width: 992px)`, `@media (max-width: 768px)`, `@media (max-width: 576px)`: Mengatur gaya untuk ukuran layar yang berbeda untuk memastikan tampilan yang baik pada perangkat yang berbeda, termasuk pengaturan lebar header, ukuran gambar, dan tata letak.
