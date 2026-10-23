# ArsipAset — Sistem Manajemen Aset

Prototipe dashboard inventaris untuk mencatat aset kantor, memantau kondisi, dan mengekspor daftar aset ke CSV. Dibangun menggunakan HTML, CSS, dan JavaScript murni.

## Fitur
- Dashboard total aset, total nilai perolehan, kondisi baik, dan aset yang perlu perhatian.
- Tabel aset dengan kode unik, kategori, lokasi, kondisi, nilai, tanggal perolehan, dan catatan.
- Tambah, edit, dan hapus data aset.
- Pencarian serta filter kategori/kondisi.
- Grafik ringkasan kondisi dan distribusi kategori.
- Ekspor inventaris ke CSV.
- Riwayat aktivitas selama sesi berjalan.
- Mode gelap/terang.
- Data disimpan lokal menggunakan `localStorage`.

## Menjalankan
Buka `index.html` di browser modern. Tidak membutuhkan server, database, framework, atau API key.

## Catatan penting
Versi ini merupakan prototipe front-end dengan data contoh. Data tersimpan di browser/perangkat lokal dan tidak otomatis tersinkron antarperangkat. Belum ada autentikasi, multi-user, audit log server, atau database. Jangan gunakan sebagai satu-satunya catatan resmi aset sebelum ditambahkan backend dan backup.

## Rencana pengembangan
1. Backend API dan database.
2. Login dan role admin/staf/pimpinan.
3. Upload foto dan dokumen aset.
4. Barang masuk/keluar dan riwayat perubahan permanen.
5. Laporan PDF dan ekspor Excel/CSV.
6. Validasi serta audit log di sisi server.

## Struktur
```
simaset/
├── index.html
├── style.css
├── app.js
└── README.md
``` 