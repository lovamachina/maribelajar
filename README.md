# MariBelajar — Platform Belajar Interaktif

Platform belajar interaktif Matematika, Fisika, dan Kimia dengan format ala Codecademy:
teori singkat di panel kiri, latihan di panel kanan, jawaban dicek instan dan exact.

Dibangun sebagai website statis satu file (`index.html`) — tidak butuh server, tidak butuh build.
Buka `index.html` di browser, atau aktifkan GitHub Pages dari branch `main` untuk mengaksesnya online.

## Status

- **Matematika Modul B1 — Bilangan & Operasi Dasar: SELESAI (MVP)**
  7 lesson + Uji Modul 10 soal. Soal parametrik (angka diacak tiap set), cek instan dengan
  diagnosis kesalahan, petunjuk bertingkat 3 lapis, status "Dikuasai" pada skor ≥ 80%.
- Modul lain (B2–B6, Intermediate, Advanced) dan mapel Fisika/Kimia: menyusul, memakai mesin yang sama.

## Keputusan Desain

- **Untuk siapa saja** — SD, SMP, SMA, sampai dewasa yang belajar ulang sebagai hobi.
- **Semua level dan lesson terbuka.** Boleh loncat, tidak ada lock/gating.
  Status penguasaan hanya penanda progres, bukan gerbang.
- **Kurikulum evergreen** — disusun dari logika materi, bukan mengikuti kurikulum resmi tertentu.
- Konten statis di kode. Akun/progres permanen (Supabase) dan SRS (spaced repetition)
  adalah fase berikutnya; progres MVP saat ini hidup selama halaman terbuka.

## Struktur

- `index.html` — seluruh aplikasi (satu file mandiri)
- `docs/silabus-matematika-v1.md` — silabus lengkap Matematika: 21 modul, 111 lesson
  (Basic / Intermediate / Advanced)

## Cara Menjalankan Lokal

Cukup buka `index.html` di browser. Untuk pengembangan, server statis apa pun bisa dipakai, misal:

```bash
python3 -m http.server 8000
# lalu buka http://localhost:8000
```
