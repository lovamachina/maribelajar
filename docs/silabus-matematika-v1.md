# Silabus Matematika Interaktif — v1
Platform belajar Matematika / Fisika / Kimia format Codecademy (teori kiri, praktik kanan, cek instan).
Status: draf v1 untuk dinilai arahnya. Belum dibangun websitenya.

## Keputusan yang Sudah Terkunci (24 Nov 2026)
1. **Untuk siapa saja** — anak SD, SMP, SMA, sampai orang dewasa yang belajar ulang sebagai hobi.
2. **Semua level dan lesson TERBUKA.** Boleh loncat-loncat, tidak ada lock, tidak ada syarat menyelesaikan modul sebelumnya. Status "sudah dikuasai" hanya penanda progres, bukan gerbang.
3. **Kurikulum evergreen** — disusun dari logika materinya sendiri (konsep A memang fondasi konsep B), bukan mengikuti Kurikulum Merdeka atau kurikulum resmi mana pun. Urutan di peta hanya *saran jalur*, bukan kewajiban.
4. **Mulai dari Matematika.** Fisika dan Kimia menyusul memakai mesin yang sama.
5. Bahasa UI dan materi: Bahasa Indonesia. Contoh soal memakai konteks sehari-hari Indonesia (uang, warung, perjalanan, pasar), tanpa mengunci ke konteks anak atau dewasa saja.

## Prinsip Desain per Lesson
- **Konsep dulu, rumus belakangan.** Tiap lesson dibuka dengan situasi/visual yang bisa diutak-atik, rumus muncul sebagai kesimpulan.
- **Satu lesson = satu ide.** Target 5–10 menit, 6–10 soal. Pecah kalau mulai terasa seperti dua ide.
- **Soal parametrik.** Angka diacak dari template (rentang dan syarat diatur per template), jadi mengulang lesson selalu ketemu soal baru dan jawaban tidak bisa dihafal.
- **Cek per langkah untuk soal panjang.** Kesalahan didiagnosis di langkah tempat ia terjadi, bukan cuma "salah" di akhir.
- **Petunjuk bertingkat 3 lapis:** (1) ingatkan konsepnya, (2) tunjukkan langkah pertama, (3) contoh serupa yang dikerjakan penuh — soal aslinya tetap harus dikerjakan sendiri.
- **Toleransi jawaban:** pecahan diterima dalam bentuk paling sederhana atau ekuivalennya; desimal diterima dalam toleransi yang dinyatakan di soal; jawaban tanpa satuan di Fisika nanti = benar sebagian.

## Jenis Latihan yang Dipakai (kode dipakai di peta di bawah)
- **PG** — pilihan ganda konsep
- **NUM** — isian numerik (parametrik)
- **STEP** — soal multi-langkah, dicek per langkah
- **VIS** — interaksi visual (geser titik di garis bilangan / grafik, susun bangun, putar bangun ruang)
- **MATCH** — menjodohkan / mengurutkan
- **GRAPH** — baca atau buat grafik/tabel
- **SALAH** — temukan kesalahan pada pengerjaan contoh ("di mana letak salahnya?")
- **UJI** — uji modul: 10 soal acak lintas lesson dalam modul, tanpa petunjuk

## Aturan Penguasaan (bukan lock)
- Lesson ditandai **Dikuasai** bila skor latihan ≥ 80% tanpa memakai petunjuk lapis 3.
- Modul ditandai **Dikuasai** bila UJI modul ≥ 80%.
- Penanda ini hanya untuk peta progres dan antrean SRS nanti. Semua konten tetap terbuka.

---

# LEVEL BASIC — Fondasi (setara SD)
Sasaran: berhitung lancar, pecahan tidak menakutkan, dan berani menghadapi bangun serta data.

## B1. Bilangan & Operasi Dasar
1. Nilai tempat & garis bilangan — VIS, NUM
2. Penjumlahan & pengurangan (termasuk pinjam/simpan) — NUM, STEP
3. Perkalian sebagai penjumlahan berulang & luas persegi panjang — VIS, NUM
4. Pembagian & hubungannya dengan perkalian — NUM, STEP
5. Operasi campuran & urutan operasi (tanda kurung dulu) — NUM, SALAH
6. Faktor, kelipatan, FPB & KPK — NUM, MATCH
7. Bilangan prima & faktorisasi pohon — VIS, NUM
UJI B1

## B2. Pecahan, Desimal & Persen
1. Pecahan sebagai bagian dari keseluruhan — VIS, PG
2. Pecahan senilai & menyederhanakan — VIS, NUM
3. Membandingkan & mengurutkan pecahan — VIS, NUM
4. Penjumlahan & pengurangan pecahan — STEP, NUM
5. Perkalian & pembagian pecahan — STEP, SALAH
6. Desimal: nilai tempat & hubungan dengan pecahan — MATCH, NUM
7. Persen sebagai pecahan dari 100 — VIS, NUM
8. Pecahan–desimal–persen dalam soal sehari-hari (diskon, bagian kue, sisa uang) — STEP
UJI B2

## B3. Pengukuran, Waktu & Uang
1. Panjang, berat, volume: memilih satuan yang masuk akal — PG, MATCH
2. Konversi satuan (km–m–cm, kg–g, liter–ml) — NUM, STEP
3. Waktu: jam, durasi, selisih waktu — NUM, STEP
4. Uang: kembalian, total belanja, menabung — STEP
5. Kecepatan sederhana sebagai jarak per waktu (jembatan ke Fisika) — NUM, GRAPH
UJI B3

## B4. Geometri Dasar
1. Titik, garis, sudut & jenis-jenis sudut — VIS, PG
2. Segitiga & segiempat: mengenali dari sifatnya — VIS, MATCH
3. Keliling bangun datar — VIS, NUM
4. Luas persegi, segitiga & gabungannya — VIS, STEP
5. Simetri & pencerminan — VIS
6. Koordinat sederhana (peta grid, baris–kolom) — VIS, NUM
UJI B4

## B5. Bangun Ruang & Volume
1. Kubus, balok, prisma, tabung, kerucut, bola: sisi, rusuk, titik sudut — VIS, MATCH
2. Jaring-jaring bangun ruang — VIS
3. Volume kubus & balok — VIS, STEP
4. Volume tabung & bangun gabungan sederhana — STEP
UJI B5

## B6. Data & Diagram
1. Membaca tabel & piktogram — GRAPH, PG
2. Diagram batang & garis — GRAPH, NUM
3. Rata-rata (mean) dari data kecil — NUM, STEP
4. Nilai tengah & nilai terbanyak (median & modus, intuitif) — NUM
5. Membuat diagram dari data mentah — GRAPH
UJI B6

**Total Basic: 6 modul, 35 lesson + 6 uji modul.**

---

# LEVEL INTERMEDIATE — Aljabar & Penalaran (setara SMP)
Sasaran: lompatan dari berhitung ke berpikir simbolik — di sinilah kebanyakan orang mulai membenci matematika, jadi tempo dibuat paling pelan dan paling visual.

## I1. Bilangan Lanjut
1. Bilangan negatif di garis bilangan & suhu — VIS, NUM
2. Operasi bilangan negatif — NUM, SALAH
3. Bilangan rasional & operasi campuran — STEP
4. Pangkat & sifat-sifat pangkat — NUM, MATCH
5. Akar & pangkat pecahan (intuitif) — NUM
6. Bentuk baku / notasi ilmiah — NUM, MATCH
UJI I1

## I2. Aljabar Dasar
1. Variabel: huruf sebagai angka yang belum diketahui — PG, NUM
2. Menyederhanakan bentuk aljabar — NUM, SALAH
3. Substitusi nilai ke rumus — NUM, STEP
4. Penjumlahan & perkalian bentuk aljabar — STEP
5. Faktorisasi sederhana (mengeluarkan faktor bersama, selisih kuadrat pengantar) — NUM
UJI I2

## I3. Persamaan & Pertidaksamaan Linear
1. Persamaan satu variabel: timbangan yang seimbang — VIS, STEP
2. Persamaan dengan kurung & pecahan — STEP, SALAH
3. Sistem dua persamaan (SPLDV): substitusi & eliminasi — STEP
4. Soal cerita menjadi persamaan (umur, harga, campuran sederhana) — STEP
5. Pertidaksamaan linear & garis bilangan jawabannya — VIS, NUM
UJI I3

## I4. Rasio, Proporsi & Aritmetika Sosial
1. Rasio & perbandingan senilai — VIS, NUM
2. Skala pada peta & denah — NUM, STEP
3. Persen lanjut: untung, rugi, diskon bertingkat — STEP
4. Bunga sederhana & cicilan sederhana — STEP
5. Perbandingan berbalik nilai (pekerja & waktu) — PG, STEP
UJI I4

## I5. Fungsi & Grafik
1. Relasi & fungsi: mesin input–output — VIS, PG
2. Fungsi linear & gradien sebagai kemiringan — VIS, NUM
3. Menggambar grafik dari tabel — GRAPH, VIS
4. Persamaan garis dari dua titik / dari grafik — STEP, GRAPH
5. Membaca cerita dari grafik (perjalanan, pengisian air) — GRAPH, PG
UJI I5

## I6. Geometri Intermediate
1. Sudut pada garis sejajar & segitiga — VIS, NUM
2. Teorema Pythagoras (dibuktikan visual dulu) — VIS, STEP
3. Kesebangunan & kekongruenan — VIS, NUM
4. Lingkaran: keliling, luas, sudut pusat & keliling — NUM, STEP
5. Luas permukaan & volume bangun ruang lanjut (prisma, limas, tabung, kerucut, bola) — STEP
6. Transformasi: refleksi, translasi, rotasi, dilatasi di grid — VIS
UJI I6

## I7. Statistika & Peluang Dasar
1. Mean, median, modus: kapan memakai yang mana — PG, NUM
2. Jangkauan & sebaran sederhana — NUM, GRAPH
3. Peluang sebagai pecahan (koin, dadu, kartu) — NUM, VIS
4. Peluang kejadian majemuk sederhana & diagram pohon — STEP, VIS
5. Membaca data yang menyesatkan (sumbu diagram dimanipulasi) — PG, GRAPH
UJI I7

## I8. Pola & Barisan
1. Pola bilangan & suku berikutnya — VIS, NUM
2. Barisan aritmetika & rumus suku ke-n — NUM, STEP
3. Deret aritmetika — STEP
4. Barisan geometri pengantar — NUM
UJI I8

**Total Intermediate: 8 modul, 41 lesson + 8 uji modul.**

---

# LEVEL ADVANCED — Menuju Kalkulus & Matematika Terapan (setara SMA)
Sasaran: fungsi sebagai bahasa utama, plus pintu masuk kalkulus yang tidak menakutkan.

## A1. Fungsi & Persamaan Kuadrat
1. Fungsi: domain, kodomain, range — PG, GRAPH
2. Komposisi & invers fungsi — STEP, NUM
3. Persamaan kuadrat: faktorisasi & rumus abc — STEP, SALAH
4. Grafik parabola: puncak, sumbu simetri, diskriminan — VIS, GRAPH
5. Soal cerita kuadrat (lintasan, luas maksimum) — STEP, VIS
UJI A1

## A2. Eksponen & Logaritma
1. Pangkat rasional & sifat eksponen lanjut — NUM
2. Fungsi eksponensial & pertumbuhan/peluruhan — GRAPH, STEP
3. Logaritma sebagai invers eksponen — MATCH, NUM
4. Sifat logaritma & persamaan logaritma — STEP
5. Soal cerita: bunga majemuk, populasi, peluruhan — STEP
UJI A2

## A3. Trigonometri
1. Sinus, kosinus, tangen dari segitiga siku-siku — VIS, NUM
2. Sudut istimewa & lingkaran satuan — VIS, MATCH
3. Identitas dasar & persamaan trigonometri sederhana — STEP
4. Aturan sinus & kosinus — STEP
5. Grafik fungsi trigonometri — GRAPH, VIS
6. Aplikasi: tinggi gedung, navigasi, gelombang — STEP
UJI A3

## A4. Barisan, Deret, Matriks & Vektor
1. Deret geometri & deret tak hingga — STEP, NUM
2. Matriks: operasi & determinan 2x2 — NUM, STEP
3. Matriks untuk menyelesaikan sistem persamaan — STEP
4. Vektor di bidang: operasi & besar arah — VIS, NUM
5. Vektor di ruang & dot product pengantar — NUM
UJI A4

## A5. Limit, Turunan & Integral (Pintu Kalkulus)
1. Limit secara intuitif: mendekati tanpa pernah sampai — VIS, NUM
2. Turunan sebagai kemiringan & laju perubahan — VIS, GRAPH
3. Aturan turunan dasar (pangkat, jumlah, kali) — NUM, STEP
4. Turunan untuk maksimum/minimum & soal optimasi — STEP, VIS
5. Integral sebagai luas & antiturunan — VIS, NUM
6. Integral tentu sederhana & luas daerah — STEP, GRAPH
UJI A5

## A6. Statistika & Peluang Lanjut
1. Kombinatorika: aturan kali, permutasi, kombinasi — NUM, STEP
2. Peluang majemuk & peluang bersyarat — STEP, VIS
3. Distribusi data: kuartil, simpangan baku (konsep & hitung data kecil) — NUM, GRAPH
4. Distribusi binomial & normal pengantar (membaca kurva, bukan menghafal tabel) — GRAPH, PG
UJI A6

## A7. Geometri Analitik & Transformasi Lanjut
1. Jarak, titik tengah & gradien di koordinat Kartesius — NUM, VIS
2. Persamaan lingkaran — STEP, GRAPH
3. Irisan kerucut pengantar (parabola, elips, hiperbola sebagai bentuk) — VIS, PG
4. Transformasi dengan matriks — STEP, VIS
UJI A7

**Total Advanced: 7 modul, 35 lesson + 7 uji modul.**

---

## Rekap Keseluruhan Matematika
- **21 modul, 111 lesson, 21 uji modul.**
- Jalur saran (bukan lock): B1 → B2 → I1 → I2 → I3 adalah tulang punggungnya; geometri, data, dan pengukuran bisa diambil kapan saja secara paralel.
- Prasyarat lunak ditampilkan sebagai saran di halaman lesson ("lesson ini lebih enak setelah B2.4"), tidak pernah sebagai penghalang.

## Yang Sengaja Tidak Masuk (evergreen, bukan kurikulum ujian)
- Program linear & sistem pertidaksamaan dua variabel versi ujian — masuk antrean v2 bila ada yang meminta.
- Logika matematika formal (implikasi, kuantor) — tidak operasional untuk jalur hobi ini.
- Statistika inferensial penuh, kalkulus lanjut (integral parsial, persamaan diferensial) — di luar cakupan SD–SMA.
- Semua teknik "trik cepat soal ujian" — platform ini mengajarkan paham, bukan hafalan jalan pintas.

## Langkah Berikutnya (belum diputuskan)
1. **MVP:** bangun mesin platformnya + Modul B1 lengkap (7 lesson + uji) sebagai bukti format, sebelum menulis 104 lesson sisanya.
2. Konten statis (JSON) di kode; Supabase hanya untuk akun, progres, dan SRS — dan itu pun fase berikutnya, MVP cukup localStorage dulu seperti kursus JS.
3. SRS (spaced repetition) masuk Fase 2: kartu otomatis dari kesalahan + konsep kunci, antrean review harian.
