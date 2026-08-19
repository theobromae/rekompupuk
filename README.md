# Form Visualisasi Lapangan — Kelapa Sawit

Form digital untuk pengisian visualisasi lapangan (situasi lahan, pertumbuhan tanaman,
defisiensi hara, hama, penyakit, PT/A, foto, dll) yang dipakai sebagai data dasar
Laporan Rekomendasi Pemupukan Tanaman Kelapa Sawit.

## Fitur
- Bisa diisi sepenuhnya offline (satu file HTML, tanpa dependensi internet).
- Simpan banyak blok dalam satu sesi, lalu export semuanya jadi satu file CSV.
- Ambil/lampirkan foto lapangan langsung dari kamera HP (otomatis dikompres).
- Import CSV lama untuk melanjutkan sesi survei di hari lain.
- Bisa di-"Add to Home Screen" di iOS/Android agar terasa seperti aplikasi.

## Cara pakai
1. Buka link GitHub Pages di Safari/Chrome HP.
2. Isi form per blok, tap **Simpan Blok Ini**.
3. Setelah semua blok selesai, tap **Export CSV** untuk mengunduh hasilnya.
4. Upload file CSV tersebut ke chat Claude untuk dinarasikan menjadi bagian
   laporan (Kondisi Tanaman, Faktor Pembatas, Saran) lengkap dengan foto.

## Deploy
File `index.html` di root repo ini otomatis menjadi halaman utama saat
GitHub Pages diaktifkan (Settings → Pages → Branch: main / root).
