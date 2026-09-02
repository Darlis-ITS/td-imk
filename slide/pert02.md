# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer
Pertemuan 02
# Human-Centered Design & Interaction Principles

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D
Departemen Teknik Informatika - ITS

---

# Slide 01 - Posisi Pertemuan dalam Alur Perkuliahan

## Pertemuan Sebelumnya: Modern HCI & Research Landscape
- HCI berkembang dari *usable interface* menjadi *human-centered computing*.
- Penelitian HCI diarahkan pada kontribusi ilmiah, bukan sekadar membangun aplikasi.
- Hasil minggu lalu: **research interest** awal setiap mahasiswa.

## Pertemuan Ini
- Memberi **bahasa konseptual** untuk membaca dan mendiagnosis interaksi manusia-komputer.
- Memanfaatkan prinsip *design* sebagai **analytical lens** untuk menemukan masalah interaksi.

## Pertemuan Berikutnya
- *Human Factors, Cognition & User Behavior*: memahami sisi kognitif manusia sebagai penyebab atau penjelas interaksi bermasalah.

Alur: **research interest → interaction problem → candidate research problem.**

---

# Slide 02 - Tujuan Pembelajaran Pertemuan 02

Setelah mengikuti pertemuan ini, mahasiswa diharapkan mampu:

1. Menjelaskan hubungan antara Human-Centered Design, Interaction Design, usability, dan UX.
2. Membedakan serta mengoperasionalkan konsep:
   - *affordance*, *signifier*, *feedback*, *mapping*, *constraints*, *discoverability*
   - *conceptual model*, *system image*, *gulf of execution*, *gulf of evaluation*
3. Menggunakan konsep-konsep tersebut untuk menganalisis studi kasus dan menemukan **interaction problem**.
4. Menyampaikan hasil analisis secara kritis dalam diskusi kelas.

Capaian ini mendukung Sub-CPMK 2, CPMK-1, dan CPMK-2.

---

# Slide 03 - Apa itu Human-Centered Design (HCD)?

## Definisi Kerja
HCD adalah pendekatan pengembangan sistem interaktif yang menjadikan **manusia, kebutuhan, dan konteks penggunaannya** sebagai pusat setiap keputusan desain.

## Perbedaan dengan Pendekatan Lain
| Pendekatan | Titik awal | Ukuran keberhasilan |
|---|---|---|
| Technology-driven | Kapabilitas teknologi | Fitur dan inovasi teknis |
| Organization-driven | Efisiensi proses bisnis | Produktivitas organisasi |
| Human-centered | Kebutuhan, kemampuan, dan konteks manusia | Kegunaan, pengalaman, kesesuaian |

## Implikasi
- Masalah desain tidak hanya ditemukan dari "sisi sistem", tetapi dari bagaimana manusia mengalami dan menggunakan sistem.
- Pengguna bukan objek pengujian semata, melainkan sumber pemahaman.

---

# Slide 04 - Prinsip Dasar Human-Centered Design

1. **Fokus terhadap pengguna dan tugas**
   - Pahami siapa penggunanya, tugas apa yang ingin diselesaikan, serta konteks sosial-fisik.

2. **Evaluasi berbasis pengalaman nyata**
   - Keputusan desain didasarkan pada observasi dan pengukuran, bukan opini.

3. **Desain iteratif**
   - Rancang → prototipe → uji → perbaiki, berulang sampai kebutuhan terpenuhi.

4. **Cakupan pengalaman menyeluruh**
   - Desain tidak berhenti pada antarmuka; mencakup keseluruhan pengalaman sebelum, selama, dan sesudah penggunaan.

5. **Tim multidisiplin**
   - Melibatkan keahlian psikologi, desain, teknis, dan domain.

---

# Slide 05 - Proses Human-Centered Design

Secara umum, HCD berbentuk siklus:

```text
        ┌─────────────────────────────────────────┐
        │     Pahami konteks penggunaan           │
        └───────────────────┬─────────────────────┘
                            ↓
        ┌─────────────────────────────────────────┐
        │     Tentukan kebutuhan pengguna         │
        └───────────────────┬─────────────────────┘
                            ↓
        ┌─────────────────────────────────────────┐
        │     Rancang solusi desain               │
        └───────────────────┬─────────────────────┘
                            ↓
        ┌─────────────────────────────────────────┐
        │     Evaluasi desain terhadap kebutuhan  │
        └───────────────────┬─────────────────────┘
                            ↓
               (ulangi hingga kebutuhan terpenuhi)
```

- Setiap hasil evaluasi dapat membuka kembali pemahaman tentang konteks dan kebutuhan.
- Prinsip ini juga menjadi dasar dalam merancang studi HCI yang baik.

---

# Slide 06 - User-Centered Design vs Human-Centered Design

| Aspek | User-Centered Design | Human-Centered Design |
|---|---|---|
| Fokus | Keterlibatan pengguna dalam proses desain | Manusia secara utuh: kognitif, fisik, emosional, sosial |
| Lingkup | Biasanya pada produk/antarmuka | Sistem, layanan, dan dampak ekosistem |
| Kata kunci | Pengguna | Manusia dalam konteks |
| Praktik umum | Pengguna diuji dan dimintai umpan balik | Konteks penggunaan dipahami sejak awal |

## Catatan Penting
- Dalam literatur, istilah UCD dan HCD sering digunakan bergantian.
- Untuk penelitian S2, gunakan HCD sebagai orientasi menyeluruh, sementara UCD sebagai praktik desain partisipatif.

---

# Slide 07 - Mengapa HCD Penting untuk Penelitian HCI?

- Banyak kegagalan produk bukan karena teknologi tidak bekerja, tetapi karena sistem tidak sesuai dengan cara manusia berpikir dan bertindak.
- HCD memberi kerangka untuk menjelaskan **mengapa** sebuah sistem tidak berhasil digunakan.
- Peneliti HCI perlu membedakan:
  - *masalah permukaan*: "tombolnya kurang besar", dan
  - *masalah fundamental*: "pengguna tidak memahami model kerja sistem".
- Dengan HCD, masalah interaksi didefinisikan dari dunia nyata pengguna, sehingga lebih relevan untuk diteliti.

**Pertanyaan kunci**: Apa kebutuhan manusia yang belum terpenuhi oleh teknologi yang ada?

---

# Slide 08 - Interaction Design: Definisi dan Ruang Lingkup

## Definisi
*Interaction Design* adalah desain **perilaku** sistem interaktif dan bagaimana pengguna berinteraksi dengannya.

## Ruang Lingkup
- Bukan hanya tampilan visual.
- Menentukan cara pengguna melakukan tindakan: menekan, mengetik, menggeser, berbicara, melihat.
- Mengatur alur tugas, navigasi, dialog, dan umpan balik.
- Menghubungkan kebutuhan pengguna dengan kemungkinan teknologi.

## Hubungan dengan HCI
- HCI adalah bidang ilmiah yang mempelajari interaksi manusia-komputer.
- Interaction Design adalah praktik merancang interaksi tersebut.

---

# Slide 09 - Aktivitas Inti Interaction Design

Interaction Design bersifat iteratif dan melibatkan empat aktivitas utama:

1. **Menetapkan kebutuhan**
   - Identifikasi karakteristik pengguna, tugas, dan konteks.
2. **Merancang alternatif solusi**
   - Menghasilkan berbagai kemungkinan alur interaksi.
3. **Membuat prototipe**
   - Mewujudkan ide agar dapat diuji: dari sketsa hingga simulasi interaktif.
4. **Mengevaluasi**
   - Mengukur apakah solusi memenuhi kebutuhan.

```text
   kebutuhan → rancangan → prototipe → evaluasi → rancangan ulang
```

Kegiatan ini menjadi dasar eksperimen dan *user study* yang akan dibahas lebih lanjut pada pertemuan 6–9.

---

# Slide 10 - Usability: Definisi Kerja

## Definisi Umum
Usability mengacu pada sejauh mana sebuah sistem dapat digunakan oleh **pengguna tertentu** untuk mencapai **tujuan tertentu** dengan:

- **Effectiveness** — ketepatan dan kelengkapan pencapaian tujuan.
- **Efficiency** — sumber daya yang diperlukan relatif terhadap hasil.
- **Satisfaction** — kenyamanan, penerimaan, dan sikap positif pengguna.

## Kata Kunci
- Usability tidak melekat pada produk secara absolut.
- Usability selalu bergantung pada:
  - pengguna,
  - tugas,
  - lingkungan/konteks penggunaan.

---

# Slide 11 - Aspek Operasional Usability

| Aspek | Pertanyaan diagnostik |
|---|---|
| *Learnability* | Seberapa cepat pengguna baru dapat menyelesaikan tugas saat pertama kali? |
| *Efficiency* | Setelah belajar, seberapa cepat tugas dapat diselesaikan? |
| *Memorability* | Apakah pengguna yang kembali dapat langsung lancar tanpa belajar ulang? |
| *Errors* | Seberapa sering kesalahan terjadi dan seberapa parah dampaknya? |
| *Satisfaction* | Bagaimana sikap dan persepsi pengguna terhadap sistem? |

## Catatan untuk Penelitian
- Setiap aspek memerlukan indikator dan metode ukur yang berbeda.
- Rancangan pengukurannya akan dibahas pada pertemuan tentang usability evaluation.

---

# Slide 12 - User Experience (UX)

## Definisi Kerja
UX adalah keseluruhan konsekuensi yang dialami seseorang ketika berinteraksi dengan sebuah sistem, termasuk emosi, kepercayaan, preferensi, persepsi, respons fisiologis, dan perilaku.

## Karakteristik UX
- Terjadi **sebelum**, **selama**, dan **setelah** penggunaan.
- Bersifat **subjektif** dan dapat berubah seiring waktu.
- Mencakup dimensi utilitarian dan hedonik.

## Tiga Faktor Pembentuk UX

| Faktor | Contoh |
|---|---|
| Pengguna | Suasana hati, pengalaman, motivasi, kemampuan |
| Sistem | Fungsionalitas, kinerja, estetika, mode interaksi |
| Konteks | Tugas, lingkungan fisik/sosial, tekanan waktu |

---

# Slide 13 - Usability dan UX: Persamaan dan Perbedaan

| Fokus Usability | Fokus UX |
|---|---|
| Penyelesaian tugas | Pengalaman yang bermakna |
| Efektivitas dan efisiensi | Emosi, nilai, dan kesan |
| Kognitif dan perilaku | Afektif dan perseptual |
| Dapat diukur dari performa tugas | Perlu *self-report*, observasi, dan data kualitatif |

## Dalam Satu Kerangka
- Usability merupakan komponen penting dari UX.
- UX tidak dapat dipahami hanya dari waktu dan error.
- Penelitian yang kuat mengombinasikan **bukti usability** dan **pengalaman subjektif**.

---

# Slide 14 - Interaction Principles sebagai Bahasa Diagnosis

Prinsip interaksi bukan sekadar panduan desain, tetapi **instrumen analisis**.

Dengan prinsip ini, kita dapat menjawab pertanyaan:

> Di titik mana interaksi manusia-komputer gagal?

Konsep yang akan dibahas:

| Konsep | Fokus analisis |
|---|---|
| *Affordance* | Aksi apa yang dimungkinkan? |
| *Signifier* | Bagaimana pengguna tahu aksi itu ada? |
| *Feedback* | Apakah hasil aksi terlihat? |
| *Mapping* | Apakah hubungan kontrol-efek jelas? |
| *Constraints* | Apakah kesalahan dapat dicegah? |
| *Discoverability* | Apakah fungsi dapat ditemukan? |
| *Conceptual model* | Apakah pengguna memahami cara kerja sistem? |
| *System image* | Apa yang ingin disampaikan sistem? |

---

# Slide 15 - Affordance

## Definisi
*Affordance* adalah kemungkinan tindakan yang **disediakan** oleh sebuah objek terhadap seseorang.

- Kursi menawarkan "duduk".
- Tombol menawarkan "tekan".
- Gagang pintu menawarkan "tarik/dorong" bergantung bentuknya.

## Sifat Relasional
- Affordance tidak hanya milik objek; ia ada karena hubungan antara kemampuan aktor dan properti objek.
- Contoh: tombol sangat kecil tidak menawarkan "tekan" dengan nyaman bagi jari besar.

## Pertanyaan Analisis
> Aksi apa yang dapat dilakukan pengguna terhadap elemen ini, dan apakah elemen tersebut mengomunikasikan kemungkinan itu?

---

# Slide 16 - Affordance Real vs Affordance yang Dirasakan

| Jenis | Penjelasan | Contoh |
|---|---|---|
| *Real affordance* | Kemampuan fisik yang ada, terlepas dari apakah diketahui | Kaca dapat dipecahkan, tetapi tidak terlihat |
| *Perceived affordance* | Kemampuan yang tampak mungkin bagi pengguna | Tombol dengan bayangan tampak dapat ditekan |

## Di Antarmuka Digital
- Layar tidak memiliki kedalaman fisik.
- Yang menentukan perilaku adalah **perceived affordance**.
- Elemen yang dapat diklik perlu dibuat tampak dapat diklik: warna, bentuk, teks, ikon.

## Diagnosis
Pengguna tidak mengeklik area yang dapat diklik karena *perceived affordance*-nya tidak ada.

---

# Slide 17 - Signifier

## Definisi
*Signifier* adalah penanda atau petunjuk yang menunjukkan **di mana** dan **bagaimana** sebuah aksi dilakukan.

- Ikon hamburger: penanda bahwa ada menu.
- Label "klik di sini": penanda bahwa teks itu dapat diaktifkan.
- Teks *placeholder* pada kolom pencarian: penanda bahwa kolom dapat diisi.

## Hubungan dengan Affordance
- Affordance: "tombol ini dapat ditekan".
- Signifier: "tekan di sini untuk menyimpan".

## Pertanyaan Analisis
> Apakah setiap aksi penting dilengkapi dengan *signifier* yang cukup jelas dan pada waktu yang tepat?

---

# Slide 18 - Affordance vs Signifier

| Aspek | Affordance | Signifier |
|---|---|---|
| Peran | Menyediakan aksi | Menunjuk ke aksi |
| Sifat | Relasional, dapat tersembunyi | Informatif, dapat dipersepsi |
| Kegagalan tipikal | Aksi tidak mungkin | Aksi tidak ditemukan |

## Kombinasi yang Salah
- Affordance tanpa signifier → fitur tersembunyi.
- Signifier tanpa affordance → petunjuk menyesatkan.

## Contoh
- Tombol bulat tampak "dapat diputar" (signifier memutar) tetapi sebenarnya hanya dapat ditekan.
- Ikon pensil kecil pada *toolbar* memiliki affordance "klik", tetapi tanpa *signifier* berupa label, maknanya ambigu.

---

# Slide 19 - Mapping

## Definisi
*Mapping* adalah hubungan antara kontrol dan efeknya pada dunia.

## Mapping yang Baik
- Pengguna langsung tahu kontrol mana yang digunakan untuk objek mana.
- Mengikuti analogi spasial, kultural, atau logis.
- Mengurangi beban ingatan dan trial-and-error.

## Mapping yang Buruk
- Kontrol tidak berurutan dengan tata letak fisik objek.
- Pengguna harus membaca label atau mencoba-coba.

## Contoh Digital
- Tombol panah kanan memindahkan kursor ke kanan? **Tidak selalu alami**, terutama saat tata letak horizontal.
- Penggeser volume bergerak ke kanan = semakin keras? Ini konvensi yang lazim, tetapi tetap perlu dicek.

---

# Slide 20 - Contoh Mapping: Kompor

```text
Tata letak tungku:

        [1]          [2]

        [3]          [4]

Mapping yang baik (mengikuti posisi fisik):

     tombol [3] → tungku 3 kiri-depan
     tombol [1] → tungku 1 kiri-belakang
     tombol [4] → tungku 4 kanan-depan
     tombol [2] → tungku 2 kanan-belakang

Mapping yang buruk:

     tombol berjajar 1-2-3-4 dipetakan ke tungku
     secara silang tanpa pola yang mudah dipahami.
```

- *Natural mapping* mengurangi kesalahan, terutama saat label tidak terbaca.

---

# Slide 21 - Constraints

## Definisi
*Constraints* adalah pembatasan atas kemungkinan tindakan sehingga pengguna diarahkan ke perilaku yang benar.

## Tujuan
- Mencegah kesalahan sebelum terjadi.
- Mengurangi kebutuhan untuk mengingat aturan.
- Membuat desain "tidak mungkin salah", bukan hanya "memberi peringatan".

## Prinsip
> Desain yang baik tidak mengharapkan manusia selalu berhati-hati; desain membuat kesalahan menjadi sulit, tidak berdampak, atau mudah dipulihkan.

## Contoh
- Tombol kirim menjadi nonaktif sampai semua data wajib diisi.
- Tanggal lahir dibatasi pada rentang yang masuk akal.

---

# Slide 22 - Kategori Constraints

| Kategori | Penjelasan | Contoh |
|---|---|---|
| *Physical* | Pembatasan oleh bentuk fisik | Kabel USB hanya masuk pada orientasi yang benar |
| *Semantic* | Pembatasan dari makna situasi | Menu "File" tidak berisi perintah "Warna font" |
| *Cultural* | Konvensi yang dipelajari luas | Warna merah berarti berhenti/peringatan |
| *Logical* | Pembatasan dari penalaran relasi antar-elemen | Tombol *next* nonaktif jika belum ada item dipilih |

## Kegunaan dalam Analisis
- Apakah sistem sudah mencegah aksi yang tidak valid di tahap awal?
- Atau sistem baru menolak setelah pengguna mencoba?

---

# Slide 23 - Feedback

## Definisi
*Feedback* adalah informasi yang kembali kepada pengguna sebagai akibat dari suatu tindakan.

## Bentuk Feedback
- Visual: perubahan warna, ikon, *progress bar*.
- Audio: bunyi konfirmasi/peringatan.
- Haptik: getaran pada layar sentuh.

## Ciri Feedback yang Baik
- Segera.
- Jelas informasinya.
- Sesuai dengan konteks tugas.
- Membantu pengguna mengambil langkah berikutnya.

## Tanpa Feedback
- Pengguna ragu apakah aksi berhasil.
- Pengguna mengulang aksi sampai terjadi duplikasi.
- Pengguna meninggalkan sistem karena merasa gagal.

---

# Slide 24 - Contoh Analisis Feedback

| Aksi pengguna | Feedback yang baik | Feedback yang buruk |
|---|---|---|
| Menyimpan data | Status "Tersimpan", jam pembaruan | Tidak ada perubahan sama sekali |
| Menunggu proses | *Progress bar* atau animasi | Layar diam selama 10 detik |
| Salah input | Pesan spesifik dan cara perbaikan | Hanya label merah tanpa penjelasan |
| Menghapus item | Muncul konfirmasi + *undo* | Langsung hilang tanpa jejak |

## Diagnosis Interaksi
> Setiap aksi penting yang dilakukan pengguna seharusnya menghasilkan respons sistem yang dapat dipahami. Jika tidak, sistem menciptakan *gulf of evaluation*.

---

# Slide 25 - Discoverability

## Definisi
*Discoverability* adalah sejauh mana pengguna dapat **menemukan** tindakan yang tersedia dan **mengetahui cara melakukannya**.

## Dukungan Prinsip
Discoverability merupakan hasil gabungan:
- *affordance* yang jelas,
- *signifier* yang memadai,
- *mapping* yang alami,
- *feedback* yang mengonfirmasi,
- *constraint* yang menghindarkan aksi keliru.

## Tantangan Modern
- Antarmuka minimalis cenderung menyembunyikan aksi.
- Gerakan *gesture* tanpa petunjuk menurunkan *discoverability*.
- Pengguna tidak akan menggunakan fitur yang tidak ia ketahui.

---

# Slide 26 - Conceptual Model

## Definisi
*Conceptual model* adalah pemahaman sederhana tentang **cara kerja sebuah sistem** yang dimiliki oleh pengguna.

## Sumbernya
- Pengguna membentuk model dari pengalaman berinteraksi, bukan dari diagram teknis.
- Sistem berkomunikasi dengan pengguna melalui tampilan, perilaku, dan umpan balik.

## Model yang Baik
- Membantu pengguna memprediksi akibat tindakan.
- Mengurangi kebutuhan menghafal langkah.

## Model yang Buruk
- Pengguna membuat mental account yang salah.
- Sistem tampak bekerja "secara magis".
- Kesalahan terjadi bukan karena pengguna bodoh, tetapi karena model konseptual yang salah.

---

# Slide 27 - System Image

## Definisi
*System image* adalah keseluruhan informasi tentang sistem yang dapat diakses oleh pengguna:
- tampilan visual,
- perilaku sistem,
- label dan ikon,
- instruksi dan dokumentasi,
- kode status.

## Peran Penting
```text
Model desain (pikiran desainer)
        ↓
   System image (artefak yang tampak)
        ↓
Mental model (pemahaman pengguna)
```

- Desainer tidak dapat langsung "menyalin" model mentalnya ke pengguna.
- Yang dapat dirancang adalah *system image*.
- Jika *system image* tidak konsisten, pemahaman pengguna menjadi keliru.

---

# Slide 28 - Gulf of Execution dan Gulf of Evaluation

## Dua Jurang dalam Interaksi

| Jurang | Pertanyaan | Terjadi saat |
|---|---|---|
| *Gulf of Execution* | Apakah pengguna tahu **bagaimana melakukan** suatu tindakan? | Niat tidak berhasil menjadi aksi yang benar |
| *Gulf of Evaluation* | Apakah pengguna tahu **apakah tindakan berhasil**? | Hasil aksi tidak dapat dimaknai |

## Contoh
- **Execution**: ingin menghapus file, tetapi tidak menemukan ikon hapus.
- **Evaluation**: sudah menekan tombol hapus, tetapi tidak yakin file hilang atau tidak.

## Peran Desain
- Desain yang baik memperkecil kedua jurang.
- Kedua gulf ini adalah sumber **interaction problem**.

---

# Slide 29 - Action Cycle sebagai Alat Diagnosis

Proses interaksi dapat dilihat sebagai siklus:

```text
     Tujuan
        ↓
 Keinginan/rencana aksi
        ↓
 Urutan tindakan yang dipilih
        ↓
 Eksekusi tindakan      ←── Gulf of Execution
        ↓
        Sistem mengubah keadaan
        ↓
 Persepsi atas keadaan sistem
        ↓
 Interpretasi terhadap hasil
        ↓
 Perbandingan dengan tujuan  ←── Gulf of Evaluation
```

## Kegunaan
- Menemukan tahap mana interaksi mulai gagal.
- Mengklasifikasikan apakah masalah berada pada **eksekusi** atau **evaluasi**.

---

# Slide 30 - Human Error vs Design Error

## Perspektif Umum
Sistem sering menyalahkan pengguna:

> "Ternyata user salah klik."

## Perspektif Human-Centered Design
- Manusia pada dasarnya dapat salah; itu sifat alami.
- Desain yang baik **mengandaikan** manusia akan salah dan menyiapkan pencegahan.

## Diagnosis Ulang
Banyak "human error" yang sebenarnya adalah *design error*:
- Desain tidak memberi *feedback* yang cukup.
- *Mapping* membingungkan.
- *System image* tidak sesuai dengan aksi sistem.
- *Affordance* tidak terlihat.

**Pertanyaan**:
> Kesalahan apa yang sebenarnya dapat dicegah oleh desain?

---

# Slide 31 - Slips dan Mistakes

| Kategori | Ciri | Contoh | Solusi Desain |
|---|---|---|---|
| *Slip* | Niat benar, eksekusi salah | Salah tekan tombol karena tombol "hapus" berdekatan dengan "arsip" | *Constraint*, konfirmasi, *undo* |
| *Mistake* | Niat/pemahaman salah | Pengguna mengira "simpan ke cloud" berarti juga menyimpan salinan lokal | Perbaiki *system image* dan *conceptual model* |

## Implikasi
- Slip lebih mudah dicegah secara teknis.
- Mistake membutuhkan perbaikan pemahaman konseptual, bukan sekadar tata letak.

**Kaitan pertemuan 3**: pengelompokan error akan dijelaskan lebih lanjut dari sisi psikologi kognitif.

---

# Slide 32 - Interaction Problem: Definisi

## Definisi Kerja
*Interaction problem* adalah kesenjangan antara:

- kebutuhan, tujuan, dan kemampuan pengguna;
- dengan cara sistem menyajikan aksi, merespons, atau memberi umpan balik.

## Ciri Interaction Problem yang Layak Diteliti
- Dapat diamati dan dibuktikan.
- Terkait dengan prinsip HCI tertentu.
- Dampaknya nyata: kegagalan tugas, kesalahan, frustasi, atau hilangnya kepercayaan.
- Belum terselesaikan secara memadai oleh desain atau penelitian yang ada.

---

# Slide 33 - Pertanyaan Diagnostik untuk Case Critique

Gunakan daftar berikut saat menganalisis artefak:

| Prinsip | Pertanyaan |
|---|---|
| Affordance | Apakah aksi yang diperlukan benar-benar tersedia? |
| Signifier | Apakah pengguna menemukan petunjuk aksi? |
| Mapping | Apakah hubungan kontrol-efek langsung dipahami? |
| Constraints | Apakah tindakan salah sulit dilakukan? |
| Feedback | Apakah hasil setiap aksi tampak? |
| Discoverability | Apakah fungsi penting dapat ditemukan tanpa manual? |
| Conceptual model | Apakah perilaku sistem konsisten dengan pemahaman awal pengguna? |
| Gulf | Di tahap mana pengguna berhenti: *execution* atau *evaluation*? |

---

# Slide 34 - Aktivitas Case Critique

## Bentuk
- Kerja kelompok kecil.
- Pilih salah satu artefak yang disediakan: aplikasi web, *mobile*, atau sistem fisik.
- Jalankan skenario singkat sebagai pengguna.

## Tugas
1. Identifikasi **tiga interaction problem**.
2. Untuk setiap masalah, tentukan:
   - prinsip apa yang dilanggar,
   - termasuk *gulf of execution* atau *evaluation*,
   - apakah lebih cenderung *slip* atau *mistake*.
3. Presentasikan diagnosis dengan bukti.

## Output
- Daftar masalah yang siap menjadi bahan identifikasi research gap pada pertemuan berikutnya.

---

# Slide 35 - Template Formulasi Interaction Problem

```text
Tujuan pengguna        : ...
Aksi yang dilakukan    : ...
Hasil yang tidak sesuai: ...
Penyebab desain        : ...
Prinsip yang terlibat  : ...
Jenis jurang           : ekseskusi / evaluasi / keduanya
Jenis error            : slip / mistake / bukan error pengguna
Dampak                 : ...
Bukti                  : observasi, kutipan think-aloud, atau log
```

## Contoh
- **Tujuan**: menghapus satu foto pada galeri.
- **Aksi**: menggeser foto ke kiri.
- **Hasil**: tidak ada reaksi.
- **Penyebab**: *gesture* tidak disertai *signifier*, tidak ada *feedback*.
- **Konsep**: *discoverability*, *feedback*, *gulf of execution/evaluation*.
- **Dampak**: pengguna mengulang-ulang geser dan akhirnya foto terhapus tidak disengaja.

---

# Slide 36 - Dari Interaction Problem Menuju Research Gap

Interaction problem yang ditemukan belum tentu merupakan **gap penelitian**.

Masalah menjadi *researchable gap* bila memenuhi syarat:

1. **Penting** — berdampak bagi banyak pengguna/domain.
2. **Belum terjawab** — belum ada pengetahuan yang cukup untuk menjelaskan atau menyelesaikannya.
3. **Dapat dirumuskan sebagai research question**.
4. **Dapat dipelajari secara empiris** — ada metode untuk memperoleh evidence.

## Langkah Berikutnya
- Pertemuan 4 akan membedah komponen paper untuk melihat anatomi *research problem*.
- Pertemuan 5 akan membantu membuktikan bahwa masalah tersebut belum diselesaikan literatur.

---

# Slide 37 - Kaitan dengan Pertemuan 3: Human Factors, Cognition & User Behavior

## Pertemuan Ini
- Membaca masalah interaksi dari struktur desain: tampilan, umpan balik, hubungan kontrol-efek.

## Pertemuan 3
- Membaca masalah dari sisi manusia:
  - persepsi,
  - atensi,
  - memori kerja,
  - beban kognitif,
  - pembentukan mental model,
  - jenis-jenis human error.

## Contoh Integrasi
| Interaction problem | Penjelasan kognitif yang akan datang |
|---|---|
| Discoverability rendah | Berhubungan dengan strategi *attention* dan pencarian visual |
| Feedback tidak jelas | Membebani *working memory* karena user harus mengingat status |
| Conceptual model salah | Berasal dari proses *learning* dan *mental model* yang tidak akurat |

---

# Slide 38 - Research Progress Minggu Ini

## Target
Identifikasi **interaction problem** awal.

## Tugas Eksplorasi
1. Pilih satu area minat yang telah Anda tetapkan pada pertemuan 1.
2. Amati minimal **dua contoh sistem** yang relevan dengan area tersebut.
3. Temukan **satu interaction problem yang paling kuat** pada setiap sistem.
4. Tuliskan menggunakan template pada Slide 35.

## Format Pelaporan
- Deskripsi konteks.
- Rumusan masalah interaksi.
- Prinsip/gulf/error yang terlibat.
- Bukti awal.
- Masalah yang belum dapat Anda jawab.

Hasil eksplorasi ini akan menjadi bahan diskusi pada pertemuan 3 untuk dirumuskan menjadi kandidat masalah penelitian.

---

# Slide 39 - Penutup

TERIMA KASIH

Pertemuan berikutnya

**Human Factors, Cognition & User Behavior**