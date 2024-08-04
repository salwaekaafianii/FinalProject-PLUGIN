HTML
1. Struktur Umum
- <!DOCTYPE html>: Mendefinisikan dokumen ini sebagai HTML5.
- <html lang="id">: Tag root yang menentukan bahasa halaman ini adalah Bahasa Indonesia.
- <head>: Bagian metadata dari dokumen, termasuk pengaturan karakter, viewport, dan link ke stylesheet CSS.
- <body>: Bagian utama dari dokumen yang berisi konten halaman web.

2. Bagian Header
- <header>: Memuat elemen navigasi yang tetap di bagian atas halaman.
- <nav>: Membungkus menu navigasi.
- <ul>: Daftar menu navigasi dengan elemen <li> sebagai item menu yang berisi link ke bagian berbeda dari halaman.

3. Bagian Utama
- <main>: Konten utama halaman web.
- <section class="hallo">: Bagian sambutan dengan judul dan paragraf perkenalan, serta link ke profil media sosial.
- <section id="about" class="about">: Bagian "Tentang Saya" yang berisi foto profil dan informasi pribadi.
- <section id="education" class="education">: Bagian "Pendidikan" yang menampilkan riwayat pendidikan.
- <section id="skills" class="skills">: Bagian "Keahlian" yang menampilkan keterampilan dalam pemrograman dan desain grafis.
- <section id="contact" class="contact">: Bagian "Kontak" dengan formulir untuk menghubungi Anda serta link media sosial.

4. Footer
- <footer>: Bagian bawah halaman dengan teks hak cipta.

CSS 

1. Aturan Umum
- * { margin: 0; padding: 0; box-sizing: border-box; }: Menghapus margin dan padding default dari semua elemen dan menetapkan box-sizing agar padding dan border dimasukkan dalam total lebar dan tinggi elemen.

2. Gaya Body
- body: Mengatur font, ukuran teks, warna, dan latar belakang halaman.
  
3. Header
- header: Menetapkan gaya untuk header termasuk latar belakang transparan, padding, posisi tetap, dan efek blur pada latar belakang. Juga, mengatur gaya untuk menu navigasi di dalamnya.

4. Navigasi
- nav ul: Menyusun menu navigasi secara horizontal.
- nav ul li a: Mengatur gaya link menu, termasuk warna, padding, dan efek transisi saat hover.

5. Section
- section: Mengatur padding, latar belakang, dan tinggi minimal untuk semua bagian.
- .hallo: Memiliki latar belakang gradien dan teks berwarna gelap.
- .about: Mengatur tata letak untuk bagian "Tentang Saya" dengan foto profil dan teks yang disejajarkan.

6. Pendidikan
- .education: Mengatur tampilan bagian "Pendidikan" termasuk daftar item pendidikan.
- .education-intent-item-content: Gaya untuk item daftar pendidikan dengan gambar, judul, dan informasi waktu.

7. Keahlian
- .skills: Bagian "Keahlian" dengan batas dan bayangan kotak.
- .skills-item: Gaya untuk setiap item keterampilan termasuk gambar, teks, dan efek hover untuk mengubah ukuran gambar dan bayangan.

8. Kontak
- .contact: Gaya untuk bagian "Kontak" dengan formulir dan deskripsi.
- .contact-form: Gaya untuk formulir kontak termasuk padding, latar belakang, dan gaya tombol.

9. Footer
- footer: Gaya untuk bagian footer termasuk latar belakang abu-abu dan teks yang disejajarkan di tengah.

10. Media Queries
- Menyesuaikan tampilan untuk berbagai ukuran layar (@media rules) untuk memastikan tata letak yang responsif pada perangkat dengan lebar layar berbeda. Misalnya, mengubah ukuran header dan mengatur ulang tata letak menu untuk perangkat yang lebih kecil.