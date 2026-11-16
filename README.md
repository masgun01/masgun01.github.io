# Portofolio Gunawan Wibisono

Website portofolio satu file. Semua gambar, gaya, dan script sudah ada di dalam `index.html`, jadi tidak perlu build atau install apa pun.

## Hosting di GitHub Pages

1. Buka repo `masgun01.github.io` di GitHub.
2. Klik **Add file → Upload files**.
3. Seret `index.html`, `README.md`, dan `.nojekyll` ke halaman itu. Kalau sudah ada file dengan nama sama, file lama otomatis ditimpa.
4. Klik **Commit changes**.
5. Tunggu 1–2 menit, lalu buka https://masgun01.github.io dan tekan Ctrl+F5.

Catatan: file `.nojekyll` diawali titik, jadi di Windows kadang tersembunyi. Kalau tidak bisa diunggah, lewati saja. Situsnya tetap jalan tanpa file itu.

## Mengubah kontak dan link project

Buka `index.html`, cari blok `var SETTINGS` di bagian bawah, lalu ubah:

- `whatsapp`: nomor dengan kode negara, tanpa + dan tanpa 0 di depan (contoh `6281477120376`)
- `email`, `github`
- `projects`: isi `demo` dan `code` dengan link lengkap (https://...). Yang dikosongkan tidak akan ditampilkan.
