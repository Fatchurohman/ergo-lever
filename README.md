# ErgoStudio 3D - Parametric Assistive Tools Generator

Platform berbasis web untuk merancang dan mengkustomisasi alat bantu kerja ergonomis serta adaptif fisik secara instan. Menghasilkan model 3D parametrik langsung di browser dan siap diekspor ke format biner `.STL` untuk dicetak menggunakan 3D printer tanpa memerlukan software CAD berbayar.

Aplikasi ini berjalan 100% *client-side* (tanpa server backend atau database) dan siap di-deploy langsung menggunakan **GitHub Pages**.

---

## 🛠️ Koleksi Alat Bantu yang Tersedia

1. **Tuas Pembuka Tutup Botol / Keran (*Easy Twist Lever*)**
   * Mengurangi beban jepit tangan saat membuka botol air, toples bumbu, atau keran air yang keras menggunakan prinsip torsi/tuas pengungkit bergerigi.
2. **Selongsong Gagang Alat (*Thick Grip Adapter*)**
   * Selongsong berongga tebal berkontur lekukan jari untuk memperbesar pegangan obeng, kuas, sendok makan, atau pena bagi penderita radang sendi (*arthritis*) atau saraf kejepit (*carpal tunnel*).
3. **Baji Miring Penyangga Tangan (*Wrist Wedge / Tenting*)**
   * Penyangga sudut ergonomis untuk meja kerja, mouse, atau keyboard split guna menjaga pergelangan tangan tetap lurus dan rileks.
4. **Tuas Pemutar Anak Kunci Rumah (*Key Turner Lever*)**
   * Gagang pipih bertuas pengungkit untuk memutar anak kunci pintu gerbang atau gembok yang macet/keras dengan dorongan telapak tangan.
5. **Penahan Lembaran Buku (*Thumb Page Holder*)**
   * Cincin ibu jari bersayap ergonomis agar buku tebal dapat dibaca terbuka menggunakan satu tangan tanpa menyebabkan kram jempol.
6. **Tuas Penekan Sakelar & Tombol (*Big Button Pusher*)**
   * Tuas kontak tumpul untuk menekan sakelar lampu, tombol lift, atau kran dispenser menggunakan dorongan telapak tangan/lengan tanpa perlu menjepit jari.

---

## ✨ Fitur Utama

* **Visualisasi 3D Real-Time**: Rendering interaktif langsung di browser menggunakan Three.js (bisa diputar, digeser, dan di-zoom).
* **Generator Parametrik Dinamis**: Setiap perubahan slider dimensi langsung mengkalkulasi ulang geometri secara matematis.
* **Kalkulator Biaya Cetak Lokal**: Estimasi berat filamen (gram) dan estimasi biaya jasa print 3D lokal (PLA/PETG/TPU).
* **Ekspor Biner .STL Instan**: Menghasilkan berkas `.stl` siap cetak ke aplikasi slicer (Cura, PrusaSlicer, Bambu Studio) tanpa login atau langganan API pihak ketiga.
* **Zero Dependency / Serverless**: Murni menggunakan HTML5, CSS3, dan Vanilla JavaScript (ES6+).

---

## 🚀 Cara Menjalankan & Deploy ke GitHub Pages

### 1. Menjalankan di Komputer Lokal
1. Unduh berkas `index.html`.
2. Klik dua kali berkas `index.html` untuk langsung membukanya di browser apa saja (Chrome, Edge, Firefox, Safari).

### 2. Deploy Gratis ke GitHub Pages
1. Buat repositori baru di GitHub (misal: `ergostudio-3d`) dan atur visibilitas ke **Public**.
2. Unggah berkas `index.html` ke *root directory* repositori tersebut.
3. Masuk ke menu **Settings** > **Pages** di halaman repositori.
4. Pada opsi **Branch**, pilih `main` (atau `master`) dan folder `/ (root)`, lalu klik **Save**.
5. Akses aplikasi melalui tautan yang disediakan GitHub:
   ```text
   https://fatchurohman.github.io/ergostudio-3d/
