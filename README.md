# MPI Darsana — Revisi Konsep Utama dan Labirin

Paket website statis untuk GitHub Pages. Berkas utama:
- `index.html`
- `style.css`
- `script.js`

## Pembaruan
- Beranda diringkas mengikuti konsep sketsa: banner Konsep Utama, enam kartu Sad Darsana, catatan ekspedisi, dan akses ke aktivitas interaktif.
- Halaman **Konsep Utama** memuat teks materi yang diberikan pengguna mengenai Darsana, kelompok Astika dan Nastika, Carwaka, Jaina, serta Buddha.
- Aktivitas Interaktif diubah menjadi Labirin Kebijaksanaan dengan pintu pertanyaan, 3 nyawa, kunci, bonus nyawa, skor, gerbang akhir, kontrol layar sentuh dan keyboard.
- Jawaban umpan balik materi dapat diganti sebelum menandai materi selesai.
- Navigasi halaman tidak lagi memaksa scroll kembali ke atas.
- Efek suara benar/salah dan getaran (jika didukung perangkat) disiapkan. Musik latar lembut mulai setelah interaksi pertama karena browser biasanya memblokir audio otomatis sebelum ada sentuhan/klik pengguna.
- Progres belajar memakai status di sesi halaman ini; data belum disimpan ke server.

## Cara memasang ke GitHub Pages
1. Ekstrak ZIP.
2. Buka repositori GitHub `agamahindu/darsana-mpi`.
3. Upload `index.html`, `style.css`, `script.js`, dan `README.md` langsung ke root repositori (bukan folder baru).
4. Commit perubahan, lalu tunggu proses Pages selesai.

Catatan: paket ini perlu diuji di perangkat nyata setelah dipasang, terutama audio dan respons layar HP. Semua fitur audio bergantung pada dukungan browser/perangkat.
