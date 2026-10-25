# SIPUSTAKA — Project System No. 5

**Sistem Informasi Perpustakaan Berbasis Web**  
Dibuat oleh **Ilham — 240511044**  
Program Studi Teknik Informatika, Fakultas Teknik  
Universitas Muhammadiyah Cirebon · 2026

## Fitur prototipe
- Dashboard jumlah judul buku, stok, peminjaman aktif, dan anggota.
- CRUD katalog buku (tambah, edit, hapus) dan pencarian.
- CRUD anggota perpustakaan dan pencarian.
- Transaksi peminjaman serta pengembalian dengan pembaruan stok otomatis.
- Desain responsif untuk desktop dan ponsel.

## Jalankan
Website ini berupa HTML, CSS, dan JavaScript biasa. Tidak memerlukan framework maupun database. Buka `index.html` di browser atau aktifkan GitHub Pages melalui **Settings → Pages → Deploy from a branch → main → /(root)**.

## Penyimpanan data
Prototipe menyimpan data di `localStorage` browser. Data hanya ada di browser/perangkat yang digunakan, tidak tersinkron ke pengguna atau perangkat lain, dan bisa hilang jika data situs dibersihkan. Gunakan data contoh untuk demonstrasi. Versi produksi memerlukan backend/database serta autentikasi dan aturan akses.
