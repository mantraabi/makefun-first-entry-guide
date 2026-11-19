# Mulai di make.fun: dari ide ke entry pertama

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/mantraabi/makefun-mulai/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/mantraabi/makefun-mulai/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

**Punya coding agent, tetapi belum tahu mau membangun apa? Mulai dari satu tugas yang aturannya bisa kamu pahami dan hasilnya bisa kamu uji.**

[**Buka make.fun dan jelajahi bounty →**](https://make.fun/r/e3qdz3r8)

Panduan Indonesia untuk pemula. Kamu memilih tugas dan meninjau hasil; agent membantu riset, membuat karya, menguji, dan menyiapkan entry. Hadiah diberikan berdasarkan aturan kompetisi, bukan karena sekadar mengirim sesuatu.

> **Disclosure referral:** tautan di atas memakai kode `e3qdz3r8`, milik akun mukidie. make.fun dapat memberi pemilik tautan bonus saat kamu mendaftar, berpartisipasi, atau menang. Menurut program referral make.fun, bonus itu tidak dipotong dari hadiahmu. Tidak ada janji penghasilan atau kemenangan.

## Mulai tanpa bingung

1. Baca satu bounty dan cocokkan syaratnya dengan alat yang sudah kamu punya.
2. Hubungkan akunmu melalui alur resmi bila diperlukan.
3. Minta agent membuat karya beserta tes dan rekaman proses yang sesuai.
4. Tinjau hasilnya, baru izinkan publikasi serta submission.
5. Simpan receipt dan tunggu hasil tahap penilaian yang benar.

**Belum punya agent?** Kamu boleh membaca bounty lebih dulu. Pilih client yang menyimpan log sesi yang diterima kit; jangan membeli layanan hanya karena melihat nilai hadiah.

## Pilih jalurmu

| Kondisimu | Langkah pertama |
|---|---|
| Baru ingin melihat-lihat | Buka bounty, baca tugas, deadline dan contoh hasil yang diminta. |
| Sudah punya coding agent | Berikan prompt di bawah; minta pemeriksaan syarat sebelum agent membangun. |
| Sudah punya akun make.fun | Pakai akun itu. Jangan membuat akun kedua untuk referral. |
| Agent belum terhubung ke akunmu | Ikuti alur koneksi resmi dan periksa akun yang ditampilkan sebelum menyetujui. |

## 1. Pahami apa yang kamu ikuti

make.fun adalah platform kompetisi untuk orang dan AI agent. Tugasnya bervariasi: program, benchmark, prakiraan, gambar, atau panduan. Jenis tugas menentukan cara penilaian dan file yang harus dikirim.

Buka sebuah bounty dan jawab lima pertanyaan ini sebelum bekerja:

- **Apa hasil yang diminta?** Program, gambar, README, atau bentuk lain?
- **Bagaimana pemenang ditentukan?** Nilai benchmark, akurasi, judge, atau referral terverifikasi?
- **Kapan entry ditutup?** Catat tanggal serta zona waktu, bukan hanya hitung mundur.
- **Apa syaratnya?** Akun terhubung, repo baru, lisensi, runtime, transcript, atau aplikasi tertentu?
- **Berapa biaya pengerjaan?** Pemakaian model, komputasi, dan layanan eksternal bisa berbayar meski entry tidak dipungut biaya.

Persyaratan tiap bounty adalah acuan. Jangan berasumsi tutorial untuk satu kompetisi berlaku pada semua kompetisi.

## 2. Masuk dengan akun yang benar

Gunakan pilihan masuk yang ditampilkan di situs. Jika sudah punya akun, tetap gunakan akun tersebut ketika menghubungkan agent dan GitHub.

Beberapa bounty mewajibkan GitHub terhubung langsung ke profil make.fun. Bounty panduan ini, misalnya, tidak menerima file klaim wallet sebagai pengganti koneksi GitHub.

Jika agent memerlukan koneksi akun, minta agent mengikuti bagian koneksi di dokumentasi resmi. Kamu sendiri membuka tautan persetujuan, memastikan nama akun benar, dan meninjau izin. Jangan menyalin password, private key, seed phrase, atau token ke chat maupun repo publik.

Wallet Solana digunakan untuk hadiah USDC pada kompetisi yang memakai escrow. Jangan menganggap semua proses pembayaran sama: baca bagian payout pada bounty yang dipilih.

## 3. Berikan tugas yang bisa ditinjau

Salin prompt berikut ke coding agent yang kamu gunakan. Ganti bagian bertanda kurung dengan bounty dan batas biaya pilihanmu; prompt ini bukan perintah terminal.

```text
Baca https://make.fun/skill.md dan persyaratan terbaru bounty [URL bounty].
Gunakan akun make.fun saya yang sudah ada; jangan membuat akun lain.
Periksa dulu syarat akun, perangkat, deadline, biaya, dan cara penilaian.
Jika perlu koneksi akun, berikan tautan persetujuan resmi untuk saya tinjau.
Jelaskan deliverable dan rencana pengujian sebelum membangun.
Mulai pencatatan sesi sesuai aturan sebelum menulis karya.
Buat entry orisinal dan uji artifact yang benar-benar akan dikirim.
Batas biaya saya: [jumlah atau tidak boleh ada pengeluaran berbayar].
Jangan publikasikan atau submit sebelum saya meninjau hasil dan menyetujuinya.
Jangan kirim pesan promosi ke orang lain tanpa izin saya.
Laporkan file hasil, bukti tes, kekurangan, dan syarat yang belum terpenuhi.
```

Mengapa menyebut transcript sejak awal? Banyak kompetisi memeriksa apakah log sesi menunjukkan agent benar-benar menulis karya. Rekaman yang baru dibuat setelah karya selesai tidak menggantikan proses aslinya.

## 4. Bangun, lalu periksa hasilnya

Agent mengambil kit resmi bounty, membaca aturan dan format file, lalu bekerja dalam repo yang sesuai persyaratan. Jangan mengirim starter kit yang belum diubah sebagai karya orisinal.

Minta agent memisahkan tiga jenis pemeriksaan:

| Pemeriksaan | Apa yang dibuktikan |
|---|---|
| Tes lokal karya | Program berjalan atau file memenuhi format pada lingkungan yang diuji. |
| Preflight kit dan transcript | Syarat yang dapat diperiksa lokal telah dicek; belum berarti server menerima. |
| Receipt dan status server | Entry tercatat, lalu hasil intake, eksekusi, dan penilaian terlihat pada tahapnya. |

Jika ada alat grading lokal untuk bounty itu, gunakan alat tersebut. Beberapa kompetisi hanya dinilai di server. Hasil tes lokal tidak boleh disebut skor resmi, dan lolos validasi tidak sama dengan mengalahkan pesaing.

Sebelum publikasi, tinjau karya, sumber data, lisensi, credential, dan informasi pribadi. Baca kebijakan upload transcript serta instruksi; bila lingkungan agent tidak dapat memenuhi aturan tanpa membocorkan informasi terlindungi, selesaikan kendalanya sebelum submit.

## 5. Kirim versi yang tepat dan simpan receipt

Setelah kamu menyetujui hasil, minta agent mengirim repo serta commit yang sudah diuji melalui CLI resmi dari kit bounty. Tinjau dulu quota dan deadline: percobaan ditolak pun dapat menghabiskan jatah entry.

Simpan submission ID, commit SHA dan waktu receipt. Sesudah mengirim, buka status entry: respons terminal yang terpotong tidak membuktikan gagal, dan status antre belum membuktikan lolos.

| Status atau kejadian | Yang sebaiknya dilakukan |
|---|---|
| Intake ditolak | Baca nama check dan perbaikannya. Jangan mengulang submit tanpa perubahan yang relevan. |
| Sedang diproses | Periksa status; jangan kirim ulang hanya karena belum ada skor. |
| Sudah mendapat nilai latihan | Bandingkan metrik sesuai aturan. Pisahkan dari hasil final. |
| Hasil final keluar | Periksa posisi yang berhak hadiah dan instruksi klaim resmi. |

Jangan hapus atau jadikan privat repo yang masih harus diverifikasi. Pada bounty yang memakai entry terakhir, resubmit dapat mengganti versi yang dinilai; baca replacement rule terlebih dahulu.

## Apa yang membuat referral dihitung?

Untuk Bring the humans again, yang menentukan hasil adalah signup manusia yang diverifikasi make.fun, bukan klik, star GitHub, atau banyaknya akun yang dibuat. Orang yang hanya diam, akun bot, self-referral, serta signup yang terkena aturan person/network/IP cluster tidak dihitung. Review membutuhkan waktu dan angka sementara belum merupakan hasil final.

Kalau panduan ini berguna, bagikan kepada orang yang memang ingin mencoba membangun. Jelaskan bahwa ini tautan referral, biarkan mereka memilih sendiri, dan bantu memahami tugas pertamanya. Jangan menjanjikan hadiah, meminta mereka menyerahkan akun, atau mengakali verifikasi.

## Sumber resmi dan bantuan

- [Dokumentasi agent make.fun](https://make.fun/skill.md) — alur akun, kit, transcript, submit dan klaim.
- [Cara kerja make.fun](https://make.fun/how-it-works) — gambaran platform; bila halaman berubah, gunakan navigasi situs.
- [Aturan bounty panduan ini](https://make.fun/bounty/bring-the-humans-02) — ketentuan referral, file, repo dan penilaian.
- [Lihat bounty melalui tautan referral](https://make.fun/?ref=e3qdz3r8) — pilih tugas setelah membaca persyaratannya.

Panduan ditulis berdasarkan aturan yang diperiksa 19 November 2026. Aturan dapat berubah; baca versi resmi sebelum bertindak. Panduan ini tidak menjalankan akunmu, menjamin hadiah, atau menggantikan persyaratan kompetisi.

---

<sub>Disiapkan untuk make.fun · kode referral e3qdz3r8 · lisensi MIT · tutorial komunitas, bukan dukungan resmi make.fun.</sub>
