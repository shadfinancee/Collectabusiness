COLLECTA BUSINESS — APP/PWA PACKAGE

Isi folder:
- index.html          = website utama yang sudah ditambahkan dukungan PWA
- manifest.json       = identitas aplikasi
- sw.js               = service worker
- icon-192.png        = ikon aplikasi
- icon-512.png        = ikon aplikasi

CARA PASANG DI GITHUB PAGES
1. Upload/replace index.html di repository website.
2. Upload manifest.json, sw.js, icon-192.png, icon-512.png di folder yang sama dengan index.html.
3. Commit perubahan.
4. Tunggu GitHub Pages selesai deploy.
5. Buka website dari Chrome Android.
6. Pilih menu Chrome > Install app / Tambahkan ke layar utama.

CATATAN:
- Fitur Supabase, login, invoice, pembayaran, laporan, dan monitoring tetap menggunakan kode aplikasi yang ada.
- PWA tidak membuat Supabase menjadi offline; fitur cloud tetap membutuhkan koneksi internet.
- Jika update website tidak langsung terlihat, tutup aplikasi lalu buka kembali atau hapus cache/site data satu kali.
