# 📊 Anggaran.me

**Anggaran.me** adalah sebuah Sistem Manajemen Anggaran berbasis web ringan yang dibangun hanya dengan satu file HTML (Single-File Application). Memiliki antarmuka pengguna yang bersih, minimalis, dan terstruktur ala ekosistem Laravel (seperti Laravel Nova/Breeze), serta terhubung langsung ke Firebase secara *real-time*.

🔗 **Live Demo:** [https://homeprint-developer.github.io/anggaran.me/](https://homeprint-developer.github.io/anggaran.me/)

---

## ✨ Fitur Utama

- ⚡ **Single-File Architecture:** Seluruh tata letak, gaya, dan logika JavaScript berada dalam satu file `index.html`.
- 🎨 **Clean UI / UX:** Desain formal dan terstruktur menggunakan **Tailwind CSS** dengan *font* bawaan Laravel (Figtree).
- 🔄 **Real-time Synchronization:** Data otomatis tersinkronisasi antar perangkat secara *real-time* berkat **Firebase Realtime Database**.
- 💰 **Manajemen Anggaran (CRUD):** Tambah, edit (nama & dana awal), dan hapus keseluruhan pangkalan anggaran.
- 🧾 **Rincian Pengeluaran (CRUD):** Tambah, edit, dan hapus rincian item pengeluaran dengan perhitungan subtotal otomatis.
- 📈 **Kalkulasi Otomatis & Progress Bar:** Menghitung sisa anggaran secara otomatis yang divisualisasikan menggunakan *progress bar* dan persentase (%).
- 🚨 **Overbudget Indicator:** Indikator visual (merah) yang otomatis muncul apabila pengeluaran melebihi dana awal (Minus / Overbudget).
- 🔢 **Auto-Format Rupiah:** Input form otomatis menambahkan titik pemisah ribuan secara *real-time* saat mengetik.
- 📱 **Fully Responsive:** Tampilan dioptimalkan dengan sangat baik untuk pengguna Desktop maupun Mobile.

---

## 🛠️ Teknologi yang Digunakan

Aplikasi ini tidak memerlukan proses *build* atau instalasi *package/node_modules*. Semua *library* dipanggil langsung melalui CDN.

- **HTML5 / CSS3 / Vanilla JavaScript (ES6+ Module)**
- **[Tailwind CSS (CDN)](https://tailwindcss.com/)** - Framework CSS untuk tata letak dan desain.
- **[SweetAlert2](https://sweetalert2.github.io/)** - Untuk membuat pop-up interaktif (Modal).
- **[FontAwesome](https://fontawesome.com/)** - Ikon antarmuka pengguna.
- **[Firebase Realtime Database](https://firebase.google.com/)** - Backend as a Service (BaaS) untuk penyimpanan data.

---

## 🚀 Cara Penggunaan & Instalasi

Karena ini adalah aplikasi *Single-File*, cara menjalankannya sangat mudah:

1. **Clone Repositori**
   ```bash
   git clone [https://github.com/homeprint-developer/anggaran.me.git](https://github.com/homeprint-developer/anggaran.me.git)