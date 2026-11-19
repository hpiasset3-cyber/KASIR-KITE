KASIR KITE - paket aplikasi

Isi folder
  index.html            halaman aplikasi
  style.css, app.js     tampilan dan logika
  manifest.webmanifest, sw.js, icons/   agar bisa dipasang seperti aplikasi dan jalan offline

Cara pakai
1. Dibuka langsung: klik dua kali index.html. Semua fitur kasir jalan; mode pasang/offline hanya aktif lewat http/https.
2. Dipasang di HP: unggah seluruh isi folder ke hosting HTTPS (mis. Netlify, GitHub Pages), buka di Chrome,
   lalu menu titik tiga > "Pasang aplikasi" / "Tambahkan ke layar utama".
3. Jadi APK: unggah ke hosting HTTPS lalu pakai PWABuilder.com, atau bungkus folder ini dengan Capacitor
   / aplikasi konverter web ke APK.

Catatan
- Data (produk, transaksi) tersimpan di penyimpanan browser per alamat. Pindah dari file lokal ke hosting
  berarti data baru mulai kosong: kirim data lewat menu Sync dulu lalu impor di alamat baru.
- Ekspor XLSX memakai library dari cdn.jsdelivr.net (butuh internet saat pertama kali dimuat).
