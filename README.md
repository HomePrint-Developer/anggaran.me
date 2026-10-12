# 📊 Anggaran.me

**Anggaran.me** adalah sebuah Sistem Manajemen Anggaran berbasis web ringan yang dibangun hanya dengan satu file HTML (Single-File Application). Memiliki antarmuka pengguna yang bersih, minimalis, dan terstruktur ala ekosistem Laravel (seperti Laravel Nova/Breeze). Aplikasi ini sepenuhnya berjalan secara _offline_ menggunakan pangkalan data lokal pada browser untuk menjamin keamanan dan privasi data sensitif Anda.

🔗 **Live Demo:** [https://homeprint-developer.github.io/anggaran.me/](https://homeprint-developer.github.io/anggaran.me/)

---

## ✨ Fitur Utama

- ⚡ **Single-File Architecture:** Seluruh tata letak, gaya, dan logika JavaScript berada dalam satu file `index.html`.
- 🎨 **Clean UI / UX:** Desain formal dan terstruktur menggunakan **Tailwind CSS** dengan _font_ bawaan Laravel (Figtree).
- 🔒 **Privacy First (Local Storage):** Data anggaran bersifat sensitif! Oleh karena itu, aplikasi ini tidak mengirimkan data ke server luar mana pun. Semuanya disimpan dengan aman secara lokal di dalam memori browser Anda (Local Storage).
- 💰 **Manajemen Anggaran (CRUD):** Tambah, edit (nama & dana awal), dan hapus keseluruhan pangkalan anggaran.
- 🧾 **Rincian Pengeluaran (CRUD):** Tambah, edit, dan hapus rincian item pengeluaran dengan perhitungan subtotal otomatis.
- 📈 **Kalkulasi Otomatis & Progress Bar:** Menghitung sisa anggaran secara otomatis yang divisualisasikan menggunakan _progress bar_ dan persentase (%).
- 🚨 **Overbudget Indicator:** Indikator visual (merah) yang otomatis muncul apabila pengeluaran melebihi dana awal (Minus / Overbudget).
- 🔢 **Auto-Format Rupiah:** Input form otomatis menambahkan titik pemisah ribuan secara _real-time_ saat mengetik.
- 📱 **Fully Responsive:** Tampilan dioptimalkan dengan sangat baik untuk pengguna Desktop maupun Mobile.

---

## 🛠️ Teknologi yang Digunakan

Aplikasi ini tidak memerlukan proses _build_ atau instalasi _package/node_modules_. Semua _library_ dipanggil langsung melalui CDN.

- **HTML5 / CSS3 / Vanilla JavaScript**
- **Web Storage API (Local Storage)** - Penyimpanan data lokal browser tanpa perlu _database server_.
- **[Tailwind CSS (CDN)](https://tailwindcss.com/)** - Framework CSS untuk tata letak dan desain.
- **[SweetAlert2](https://sweetalert2.github.io/)** - Untuk membuat pop-up interaktif (Modal).
- **[FontAwesome](https://fontawesome.com/)** - Ikon antarmuka pengguna.

---

## 🚀 Cara Penggunaan & Instalasi

Karena ini adalah aplikasi _Single-File_, cara menjalankannya sangat mudah:

1. **Clone Repositori**
   ```bash
   git clone https://github.com/homeprint-developer/anggaran.me.git
   ```
2. Buka folder proyek.
3. Cukup klik ganda (Double-Click) pada file `index.html` untuk membukanya di browser apa pun (Chrome, Safari, Edge, Firefox).
4. Atau, _host_ file `index.html` ini di layanan gratis seperti GitHub Pages, Vercel, Netlify, atau Hostinger.
