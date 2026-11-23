# MOBILE-COMP Corporate Website

Website promosi statis untuk MOBILE-COMP (Mobile Control & Monitoring of Compressors).

## Struktur paket
- `index.html` — halaman promosi utama.
- `styles.css` — desain corporate responsif untuk desktop, tablet, dan mobile.
- `script.js` — navigasi mobile yang aksesibel dan animasi ringan.
- `assets/mobile-comp-mark.svg` — logo mark MOBILE-COMP.
- `assets/architecture-flow.svg` — diagram komunikasi sistem.
- `assets/dashboard-implementasi-redacted.png` — dokumentasi dashboard implementasi dengan informasi operasional yang disamarkan.
- `assets/og-mobile-comp.png` — gambar pratinjau saat tautan website dibagikan.
- `.nojekyll` — membantu GitHub Pages menyajikan aset statis tanpa pemrosesan Jekyll.

## Menjalankan secara lokal
1. Ekstrak ZIP.
2. Buka `index.html` dengan browser, atau jalankan server lokal sederhana.
3. Tidak membutuhkan database, API key, framework, atau biaya layanan tambahan.

## Memperbarui repository GitHub yang sudah ada
1. Unduh dan ekstrak paket ZIP ini.
2. Buka repository `TidakTahuu/mobile-com` di GitHub.
3. Pilih `Add file` → `Upload files`.
4. Unggah isi folder `MOBILE-COMP-WEBSITE` ke direktori utama repository. Jangan mengunggah folder pembungkusnya sebagai satu folder bertingkat.
5. Pastikan `index.html`, `styles.css`, `script.js`, `.nojekyll`, dan folder `assets` terlihat di direktori utama.
6. Klik `Commit changes`.
7. Buka tab `Actions` atau `Deployments` dan tunggu proses `github-pages` selesai.
8. Muat ulang website publik setelah deployment berhasil.

**Penting:** Jangan menghapus file lain yang tidak terkait dengan website. Jika GitHub menampilkan konflik nama file, periksa dahulu isi file sebelum memilih overwrite.

## Konten produk yang dicantumkan
Informasi fitur dan arsitektur mengikuti dokumen implementasi yang diberikan:
- Integrasi awal pada empat unit kompresor Sullair berkapasitas 110 kW per unit.
- Komunikasi controller melalui RS485 Modbus RTU dan perangkat RS485-to-Ethernet menuju Ethernet Modbus TCP.
- Antarmuka local web pada jaringan lokal perusahaan, dapat diakses dari PC maupun perangkat mobile yang terhubung ke jaringan tersebut.
- Parameter monitoring: P1, P2, T1, T2, condition, machine status, Running Hours, Loading Hours, dan Alarm History.
- Fungsi kontrol yang dipetakan: Start, Unload, Stop, dan Auto Mode.

## Catatan publikasi dan batasan
- Website promosi ini bersifat publik, tetapi sistem operasional MOBILE-COMP berjalan pada jaringan lokal fasilitas pengguna. Website promosi tidak menyediakan akses ke sistem kontrol langsung.
- Ilustrasi dashboard pada bagian hero merupakan ilustrasi antarmuka, bukan dashboard aktif dan bukan data operasional aktual.
- Screenshot implementasi ditampilkan sebagai dokumentasi dengan informasi operasional yang disamarkan.
- Kompatibilitas dengan controller atau merek kompresor lain memerlukan pemeriksaan protokol, register mapping, jaringan, dan validasi fungsi.
- Tidak ada harga, ROI, penghematan energi terjamin, atau klaim keamanan yang ditambahkan.
- Kontak WhatsApp/email belum ditambahkan karena detail kontak resmi belum diberikan.

## Pembaruan berikutnya
Sebelum menambahkan formulir prospek atau tombol WhatsApp, siapkan nomor dan email resmi yang boleh ditampilkan untuk publik.
