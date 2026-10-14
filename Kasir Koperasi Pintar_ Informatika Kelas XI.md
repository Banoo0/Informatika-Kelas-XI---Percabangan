[Kasir Koperasi Pintar](#atas)

[Urutan belajar](#urutan) [Materi](#materi) [Kuis](#kuis) [LKPD](#lkpd) [Flowchart](#flowchart) [Percabangan](#percabangan) [Ringkasan](#konsep)

Informatika kelas XI

# Bantu kasir koperasi memilih diskon yang benar

Koperasi sekolah punya aturan diskon bertingkat, tapi kasirnya sering salah hitung. Hari ini kamu belajar percabangan Python untuk membuat kasir otomatis.

[Mulai belajar](#urutan) [Buka materi](#materi)

Coba struk di samping: ubah total belanja, lalu lihat baris if mana yang dipilih Python dan mana yang dilewati.

**Koperasi Sekolah**Struk percobaan

Total belanja (Rp)

Coba nilai batas:

[ ] Anggota koperasi (potongan Rp2.000)

Total belanja

\-

Diskon

\-

Potongan diskon

\-

Potongan anggota

\-

Total bayar

\-

Kode yang berjalan untuk struk ini

## Urutan belajar hari ini

Ikuti urutan ini dan centang yang sudah selesai. Progresmu tersimpan di perangkat ini.

0 dari 6 selesai

1. [ ]

   ### Jawab kuis pembuka

   Tulis jawaban dengan kata-katamu sendiri. Tidak dinilai, hanya untuk mengetahui titik awalmu.

   [Ke kuis](#kuis)
2. [ ]

   ### Pahami kasus koperasi

   Lihat struk yang salah, aturan diskon, dan jawab pertanyaan pemantik di materi interaktif.

   [Ke materi](#materi)
3. [ ]

   ### Hitung manual dan uji aturan (LKPD Tahap 1)

   Isi tabel uji data. Perhatikan nilai batas seperti 49.999 dan 50.000.

   [Ke LKPD](#lkpd)
4. [ ]

   ### Gambar flowchart dan tulis pseudocode (Tahap 2)

   Pakai diagrams.net atau kertas plano. Cek bentuk simbol di bagian Flowchart.

   [Buka diagrams.net](https://app.diagrams.net/)
5. [ ]

   ### Ubah menjadi kode Python (Tahap 3-4)

   Buat notebook baru di Google Colab, tulis kodenya bergantian dengan pasanganmu, lalu uji dengan data dari Tahap 1.

   [Buka Colab](https://colab.research.google.com/)
6. [ ]

   ### Presentasikan dan refleksi (Tahap 5)

   Bandingkan solusi kelompokmu dengan kelompok lain, lalu isi refleksi pribadi di LKPD.

   [Cek ringkasan](#konsep)

## Materi interaktif

Klik tombol di dalam slide untuk membuka isinya. Menu konsep akan dibuka gurumu setelah kamu mencoba menyusun aturan sendiri.

Slide tidak muncul atau terlalu kecil? Buka di tab baru.

[Buka materi layar penuh](https://view.genially.com/6ace5516354765f38cf66fc2)

### Kuis pembuka

Soalnya berupa pertanyaan terbuka. Jawab sepanjang yang kamu perlukan untuk menjelaskan alasanmu. Tidak ada nilai, gurumu hanya ingin tahu apa yang sudah kamu pahami.

[Mulai kuis](https://wayground.com/join/quiz/6ace50ffa3a5b5d084087935/start?studentShare=true)

- **Pakai kata-katamu sendiri**Tidak perlu bahasa teknis. Contoh dan alasan lebih berharga daripada satu kata.
- **Salah itu boleh**Kuis ini mengukur titik awal, bukan hasil akhir.
- **Kuis terbuka di tab baru**Kembali ke halaman ini setelah selesai, lalu centang langkah pertama.

## LKPD kelompok

Lembar kerja berisi lima tahap: uji aturan, rancang flowchart, tulis kode, uji dan perbaiki, lalu refleksi. Salin dokumennya ke Drive kelompokmu sebelum mengisi.

Untuk mengisi, buka dokumen aslinya lalu pilih File, Buat salinan.

[Buka LKPD](https://docs.google.com/document/d/1uGU26UwlBNa7PAokAYEHcGGER0q20uZfXzOKXVexGos/edit?usp=sharing)

## Bentuk-bentuk flowchart

Pakai bentuk yang tepat saat menggambar alur kasir. Ketuk gambar untuk memperbesar.

**Belah ketupat = keputusan**Inilah tempat percabangan. Setiap panah keluar diberi label Ya atau Tidak.

**Jajar genjang = input dan output**Dipakai untuk membaca total belanja dan menampilkan total bayar.

**Persegi panjang = proses**Dipakai untuk menghitung, misalnya bayar = total dikurangi diskon.

## Memahami percabangan dari nol

Percabangan tidak hanya dipakai kasir koperasi. Hampir semua aplikasi yang kamu pakai memilih jalur berdasarkan syarat, dan kamu bisa mencobanya langsung di bawah ini.

Biasanya program berjalan lurus dari baris paling atas ke bawah. Percabangan menaruh persimpangan di jalan itu: program memeriksa sebuah syarat, lalu memilih jalur sesuai hasilnya.

**Syarat**Pertanyaan yang jawabannya hanya benar (True) atau salah (False), misalnya `suhu >= 35`.

**Jalur**Blok kode yang dijalankan kalau syaratnya benar. Di Python ditandai titik dua dan indentasi.

**Satu pilihan**Pada if-elif-else hanya satu jalur yang berjalan: yang syaratnya pertama kali benar.

Kamu sudah sering bertemu percabangan: login (kata sandi benar?), game (nyawa habis?), ATM (saldo cukup?), ojek online (jarak berapa kilometer?), dan peringatan baterai HP.

### Coba sendiri: persimpangan program

Pilih skenario, geser nilainya, dan lihat jalur mana yang dipilih. Lalu nyalakan "balik urutan" untuk melihat kenapa urutan syarat penting.

Suhu**30**

[ ] Balik urutan syarat (lihat apa yang salah)

Kodenya, ikut berubah saat kamu menggeser

### Dua syarat sekaligus: and, or, not

Kadang satu syarat tidak cukup. Nyalakan atau matikan A dan B, lalu lihat hasil tiap operator logika.

A: usia 17 tahun ke bawah[x] B: membawa kartu pelajar[ ]

```

```

`A and B`

`A or B`

`not A`

### Tebak keluarannya

Baca kodenya, tebak apa yang dicetak, lalu cek alasannya. Lima soal, tanpa nilai.

### Kesalahan yang sering terjadi

**Memakai = untuk membandingkan**`if x = 5:` salah. Gunakan `if x == 5:`.

**Lupa titik dua**Setiap if, elif, dan else harus diakhiri `:`.

**Indentasi tidak rapi**Blok di bawah syarat harus menjorok 4 spasi, kalau tidak muncul IndentationError.

**Urutan elif terbalik**Syarat longgar di atas menghentikan pemeriksaan lebih awal. Mulai dari yang paling ketat.

**Salah nilai batas**Beda `>` dan `>=` mengubah hasil tepat di angka batas, misalnya 50.000.

## Ringkasan konsep

Buka kalau kamu lupa. Semua contoh bisa kamu salin ke Colab dan dijalankan.

**Satu syarat.** Blok di bawah if hanya dijalankan kalau syaratnya benar. Kalau salah, program lanjut ke baris berikutnya.

Analogi: jika hujan, bawa payung.

Tidak ada jalur kedua. Kalau tidak hujan, tidak terjadi apa-apa.

```

```

**Dua jalur.** Program selalu memilih salah satu: jalur if kalau benar, jalur else kalau salah.

Analogi: nilai 75 atau lebih lulus, selain itu remedial.

else tidak punya syarat. Ia menangkap semua yang tidak memenuhi if.

```

```

**Banyak jalur.** Syarat diperiksa dari atas ke bawah dan berhenti di syarat pertama yang benar.

Itu sebabnya diskon koperasi diperiksa mulai dari belanja terbesar.

Kalau urutannya dibalik (mulai dari 20.000), belanja Rp120.000 berhenti di baris pertama dan hanya dapat 5%.

```

```

| Operator | Artinya |
| --- | --- |
| `==` | sama dengan |
| `!=` | tidak sama dengan |
| `>` `<` | lebih dari, kurang dari |
| `>=` `<=` | lebih atau sama dengan, kurang atau sama dengan |
| `and` | dua-duanya harus benar |
| `or` | salah satu benar sudah cukup |
| `not` | membalik benar jadi salah |

**Tiga aturan penulisan:**

1\. Akhiri syarat dengan titik dua.

2\. Beri indentasi 4 spasi pada blok di bawahnya.

3\. Gunakan `==` untuk membandingkan. Satu tanda `=` hanya untuk mengisi nilai.

Salah: `if total = 50000:`\
Benar: `if total == 50000:`

Informatika kelas XI, Fase F. Percabangan Python. Materi, kuis, LKPD, dan flowchart ada di halaman ini.

Penjelasan fungsi bentuk-bentuk diagram alur (diperbesar)