# Form Visualisasi Lapangan — Kelapa Sawit

Form digital untuk pengisian visualisasi lapangan (situasi lahan, pertumbuhan tanaman,
defisiensi hara, hama, penyakit, PT/A, foto, dll) yang dipakai sebagai data dasar
Laporan Rekomendasi Pemupukan Tanaman Kelapa Sawit.

## Fitur
- Bisa diisi sepenuhnya offline (satu file HTML, tanpa dependensi internet).
- Simpan banyak blok dalam satu sesi.
- Foto lapangan bisa dilampirkan langsung per kategori (Situasi Lahan, Cadangan
  Buah, Pertumbuhan Tanaman, Tunasan, Kondisi Piringan, Kondisi Gawangan, PT/A
  Teras, Tapak Kuda, Drainase, Water Saving, Kondisi Jalan, Jembatan Panen) — otomatis dikompres.
- Form dikelompokkan: **Konservasi Tanah dan Air** (teras, tapak kuda, drainase, water
  saving) dan **Infrastruktur** (jalan, jembatan panen).
- **Defisiensi Hara** dan **Hama & Penyakit** dicatat sebagai daftar temuan: tiap
  temuan berisi satu keterangan dan boleh lebih dari satu foto. Hama & Penyakit
  memakai dropdown bertingkat (Hama: ulat api, ulat kantong, tikus, kumbang badak;
  Penyakit: Ganoderma, busuk pupus; plus "Lainnya").
- Export semua blok jadi satu file **ZIP** berisi `data.csv` (data teks, ringan,
  gampang dibuka) dan folder `images/` berisi foto asli per blok per kategori, serta `temuan.csv`
  (satu baris per temuan defisiensi/hama/penyakit beserta daftar fotonya).
- Import CSV lama untuk melanjutkan sesi survei data teks di hari lain (foto
  perlu dilampirkan ulang saat lanjut sesi).
- Bisa di-"Add to Home Screen" di iOS/Android agar terasa seperti aplikasi.

## Cara pakai
1. Buka link GitHub Pages di Safari/Chrome HP.
2. Isi form per blok, lampirkan foto di tiap kategori yang relevan, tap
   **Simpan Blok Ini**.
3. Setelah semua blok selesai, tap **Export ZIP (CSV+Foto)** untuk mengunduh
   hasilnya.
4. Upload file ZIP tersebut ke chat Claude untuk dinarasikan menjadi bagian
   laporan (Kondisi Tanaman, Faktor Pembatas, Saran) lengkap dengan foto.

## Deploy
File `index.html` di root repo ini otomatis menjadi halaman utama saat
GitHub Pages diaktifkan (Settings → Pages → Branch: main / root).
