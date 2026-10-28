# DOMEA Risoles — sumber aplikasi

Aplikasi katalog/pemesanan responsif untuk DOMEA Risoles, Semarang.

## Fitur
- Katalog: Risol Rogout Rp3.000, Risol Mayo Sosis Rp4.000, Risol Beef Rp5.000.
- Keranjang dengan jumlah per produk dan total otomatis.
- Checkout menyusun pesan dan membuka WhatsApp `087844610863` (`+62 878-4461-0863`).
- Alamat toko dan tautan pencarian Google Maps.
- Manifest dan service worker untuk kemampuan PWA dasar.

## Cara tes
Buka `index.html` di browser. Untuk menguji fitur PWA/service worker, jalankan melalui hosting HTTPS atau server lokal; membuka file langsung tidak mengaktifkan semua fitur PWA.

## Cara memasukkan kode ke GitHub dari ponsel
1. Masuk ke https://github.com dan buat akun atau login.
2. Tekan **New repository**. Beri nama `domea-risoles`, pilih **Public** atau **Private**, lalu **Create repository**.
3. Pada halaman repository, pilih **Add file → Upload files**.
4. Ekstrak ZIP ini terlebih dahulu, lalu unggah `index.html`, `manifest.json`, `sw.js`, `icon-192.png`, `icon-512.png`, `README.md`, dan folder `.github` jika tersedia.
5. Tekan **Commit changes**.

## Cara menerbitkan aplikasi sebagai situs HTTPS gratis dengan GitHub Pages
1. Buka repository → **Settings → Pages**.
2. Di **Build and deployment**, pilih **Deploy from a branch**.
3. Pilih branch `main`, folder `/ (root)`, lalu **Save**.
4. Tunggu beberapa menit sampai alamat GitHub Pages muncul. Uji situs di ponsel.

## Cara menghasilkan APK Android
Sumber ini adalah PWA, bukan APK native yang sudah dikompilasi. Untuk membuat APK dengan cara relatif mudah:
1. Terbitkan situs menggunakan HTTPS terlebih dahulu (langkah GitHub Pages).
2. Buka https://www.pwabuilder.com/ dan masukkan URL situs GitHub Pages.
3. Periksa hasil analisis; pastikan manifest, ikon, dan alamat situs benar.
4. Pilih paket Android (umumnya menggunakan Trusted Web Activity), ikuti instruksi yang disediakan, dan unduh proyek/paket Android yang dihasilkan.
5. Jika PWABuilder meminta proses signing, buat atau gunakan signing key milik Anda dan simpan dengan aman. Jangan membagikan kata sandi atau private key.
6. Ikuti petunjuk build Android yang disediakan untuk memperoleh APK. Uji APK di ponsel sebelum membagikannya.

Catatan penting:
- Saya belum menerbitkan repository, situs, atau membuat APK atas nama Anda. Langkah tersebut membutuhkan login dan tindakan Anda pada akun GitHub/PWABuilder.
- Tautan WhatsApp membuka aplikasi/website WhatsApp dengan draf pesanan; pelanggan tetap menekan tombol kirim sendiri.
- Harga, nomor, dan alamat diambil dari informasi yang diberikan pemilik. Periksa kembali semuanya sebelum dipublikasikan.
- Ongkir tidak dihitung oleh aplikasi dan belum termasuk total.
