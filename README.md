# ErgoStudio 3D - Universal Parametric Assistive & Automotive Tools Generator

Platform generator 3D interaktif berbasis web untuk merancang alat bantu kerja fisik, asistif disabilitas/lansia, serta aksesoris adaptif kendaraan. Menghasilkan model parametrik langsung di browser dan siap diekspor ke format biner `.STL` siap cetak menggunakan 3D printer tanpa perlu software CAD berbayar.

Aplikasi ini berjalan 100% *client-side* (tanpa server backend atau database) dan siap di-deploy langsung menggunakan **GitHub Pages**.

---

## 🛠️ Koleksi Lengkap Modul Alat (9 Modul)

### Kategori 1: Alat Bantu Harian & Tangan
1. **Tuas Pembuka Botol & Keran (*Easy Twist Lever*)**
   * Mengurangi beban jepit tangan saat membuka botol air, toples bumbu, atau keran air yang keras menggunakan prinsip torsi/tuas pengungkit bergerigi.
2. **Selongsong Gagang Ergonomis (*Thick Grip Adapter*)**
   * Memperbesar pegangan sendok makan, kuas lukis, pena, atau obeng bengkel bagi penderita radang sendi (*arthritis*) atau saraf kejepit (*carpal tunnel*).
3. **Baji Penyangga Tangan (*Wrist Wedge / Tenting*)**
   * Penyangga sudut ergonomis untuk meja kerja, mouse, atau keyboard split guna mencegah ketegangan sendi pergelangan.
4. **Tuas Pemutar Anak Kunci Rumah (*Key Turner Lever*)**
   * Gagang pipih bertuas pengungkit untuk memutar anak kunci gerbang atau gembok yang keras dengan dorongan telapak tangan.
5. **Penahan Lembaran Buku (*Thumb Page Holder*)**
   * Cincin ibu jari bersayap ergonomis agar buku tebal dapat dibaca terbuka menggunakan satu tangan tanpa menyebabkan kram jempol.
6. **Tuas Penekan Sakelar & Tombol (*Big Button Pusher*)**
   * Tuas kontak tumpul untuk menekan sakelar lampu, tombol lift, atau kran dispenser galon menggunakan siku/telapak tanpa perlu menjepit jari.

### Kategori 2: Aksesoris & Adaptif Kendaraan
7. **Knop Pemutar Setir Mobil (*Steering Wheel Spinner Knob*)**
   * Pegangan putar ergonomis di lingkar kemudi untuk memudahkan manuver putar balik atau parkir cukup dengan satu telapak tangan.
8. **Klem Braket Setang Motor & Sepeda (*Handlebar Clamp Bracket*)**
   * Klem pipa setang (standar 22 mm atau fatbar 28 mm) lengkap dengan tapak mounting dan lubang baut untuk dudukan HP/GPS atau sakelar lampu tambahan.
9. **Ekstensi Tuas Sein & Wiper (*Stalk Lever Extension*)**
   * Selongsong pemanjang tuas di balik setir mobil dengan sirip sentuh lebar agar lampu sein dapat dijangkau tanpa melepas genggaman setir.

---

## ✨ Fitur Utama

* **Visualisasi 3D Interaktif**: Didukung oleh Three.js dengan pencahayaan realistis, grid referensi, dan panduan objek fisik (pipa/setir/tutup botol).
* **Generator Parametrik Presisi**: Geometri 3D terhitung otomatis dari input slider ukuran fisik.
* **Kalkulator Biaya Cetak Lokal**: Estimasi berat plastik (gram) dan estimasi biaya cetak jasa 3D printing lokal secara real-time.
* **Ekspor Biner .STL Langsung**: Unduh berkas format `.stl` biner langsung dari browser tanpa konversi server pihak ketiga.
* **100% Serverless & Ringan**: Cukup satu berkas `index.html` murni HTML, CSS, dan Vanilla JavaScript (ES6+).

---

## 🚀 Cara Menjalankan & Deploy ke GitHub Pages

### 1. Menjalankan di Komputer Lokal
1. Unduh berkas `index.html`.
2. Klik dua kali berkas `index.html` untuk membukanya langsung di browser (Chrome, Edge, Firefox, Safari).

### 2. Deploy Gratis ke GitHub Pages
1. Buat repositori baru di GitHub (misal: `ergostudio-3d`) dan atur visibilitas ke **Public**.
2. Unggah berkas `index.html` ke repositori.
3. Buka menu **Settings** > **Pages** di repositori tersebut.
4. Pada bagian **Branch**, pilih `main` (atau `master`) dan folder `/ (root)`, lalu klik **Save**.
5. Akses aplikasi melalui URL yang dihasilkan GitHub:
   ```text
   https://<username-kamu>.github.io/ergostudio-3d/
