# Google Maps Easy Scrape

Ekstensi Chrome yang memudahkan untuk mengambil hasil pencarian Google Maps dan mengekspornya ke format CSV.

## Ringkasan Proyek

Google Maps Easy Scrape adalah ekstensi Chrome yang kuat yang dirancang untuk mengumpulkan data bisnis dari hasil pencarian Google Maps secara otomatis. Ekstensi ini mengotomatiskan proses menggulir melalui hasil pencarian dan mengumpulkan informasi seperti nama bisnis, peringkat, ulasan, nomor telepon, situs web, dan tautan Google Maps.

## Fitur

- **Auto-scrolling**: Secara otomatis menggulir hasil pencarian Google Maps untuk mengumpulkan semua data yang tersedia
- **Pengumpulan Data**: Mengekstrak informasi bisnis yang lengkap termasuk:
  - Judul/nama bisnis
  - Peringkat
  - Jumlah ulasan
  - Nomor telepon
  - URL situs web
  - Tautan Google Maps langsung
- **Ekspor CSV**: Mengekspor data yang dikumpulkan ke format CSV dengan satu klik
- **Nama File Dapat Dikonfigurasi**: Sesuaikan nama file untuk file CSV yang diekspor
- **Tampilan Real-time**: Lihat data yang dikumpulkan dalam format tabel yang rapi dan terorganisir
- **Deteksi Cerdas**: Secara otomatis mendeteksi ketika Anda berada di halaman pencarian Google Maps

## Petunjuk Instalasi

Ikuti langkah-langkah berikut untuk menginstal ekstensi Google Maps Easy Scrape di Chrome:

### Langkah 1: Unduh atau Kloning Repository
- **Opsi A**: Unduh repository sebagai file ZIP dan ekstrak ke lokasi yang Anda inginkan
- **Opsi B**: Kloning repository menggunakan Git:
  ```bash
  git clone <repository-url>
  ```

### Langkah 2: Buka Halaman Ekstensi Chrome
- Buka Google Chrome
- Navigasi ke `chrome://extensions/` di bilah alamat
- Alternatifnya, buka menu Chrome (tiga titik) → More tools → Extensions

### Langkah 3: Aktifkan Mode Pengembang
- Di pojok kanan atas halaman Ekstensi, aktifkan **"Developer mode"**
- Ini akan menampilkan opsi tambahan untuk pengembang

### Langkah 4: Muat Ekstensi
- Klik tombol **"Load unpacked"** yang muncul di pojok kiri atas
- Dialog pemilihan file akan terbuka
- Navigasi ke dan pilih direktori ekstensi (folder yang berisi manifest.json)
- Klik "Select Folder"

### Langkah 5: Verifikasi Instalasi
- Ekstensi Google Maps Easy Scrape sekarang harus muncul dalam daftar ekstensi Anda
- Ikon ekstensi (🗺️) harus muncul di toolbar Chrome Anda
- Jika Anda tidak melihat ikonnya, klik ikon puzzle di toolbar dan sematkan ekstensi tersebut

## Cara Menggunakan

1. **Navigasi ke Google Maps**: Buka [Google Maps](https://www.google.com/maps/) dan lakukan pencarian untuk bisnis atau tempat
2. **Buka Ekstensi**: Klik ikon Google Maps Easy Scrape di toolbar Chrome Anda
3. **Mulai Scraping**: Klik tombol "Scrape Google Maps"
4. **Tunggu Pengumpulan**: Ekstensi akan secara otomatis menggulir melalui hasil dan mengumpulkan data
5. **Tinjau Hasil**: Lihat data yang dikumpulkan dalam tabel yang muncul
6. **Ekspor Data**: 
   - Masukkan nama file kustom (opsional) di bidang input
   - Klik "Download as CSV" untuk menyimpan data ke komputer Anda

## Detail Teknis

Ekstensi ini dibangun menggunakan teknologi web modern:

- **Manifest V3**: Versi manifes ekstensi Chrome terbaru untuk keamanan dan performa yang lebih baik
- **HTML**: Markup semantik untuk antarmuka popup
- **Inline CSS**: Gaya tertanam untuk antarmuka pengguna yang bersih dan responsif
- **Vanilla JavaScript**: JavaScript murni tanpa dependensi eksternal untuk performa cepat
- **Chrome Extensions API**: Menggunakan API `chrome.scripting` dan `chrome.tabs` untuk injeksi konten dan manajemen tab

## Fitur Ekspor

Fungsi ekspor CSV memungkinkan Anda untuk:

- **Nama File Kustom**: Masukkan nama file yang diinginkan sebelum mengunduh (default ke timestamp jika tidak ada nama yang diberikan)
- **Data Lengkap**: Ekspor semua informasi bisnis yang dikumpulkan dalam format CSV yang terstruktur
- **Unduh Langsung**: File diunduh langsung ke folder unduhan default Anda
- **Kompatibel Spreadsheet**: File CSV yang diekspor dapat dibuka di Excel, Google Sheets, atau aplikasi spreadsheet apa pun

Ekspor CSV mencakup semua kolom berikut:
- Title
- Rating
- Reviews
- Phone
- Website
- Google Maps Link

## Persyaratan

- Browser Google Chrome (versi 88 atau lebih tinggi untuk dukungan Manifest V3)
- Akses ke hasil pencarian Google Maps

## Pemecahan Masalah

- **Ekstensi tidak berfungsi**: Pastikan Anda berada di halaman pencarian Google Maps (URL harus mengandung `google.com/maps/search`)
- **Tidak ada data yang dikumpulkan**: Pastikan ada hasil pencarian yang terlihat di halaman sebelum memulai
- **Unduh tidak berfungsi**: Periksa apakah browser Anda mengizinkan unduhan dan tidak ada popup blocker yang mengganggu

---

Dibuat oleh [Mike Powers](https://www.youtube.com/@itsmikepowers) | [Dukung pengembang](https://www.buymeacoffee.com/itsmikepowers)
