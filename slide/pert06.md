# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer
Pertemuan 06
# Quantitative HCI Research

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D
Departemen Teknik Informatika - ITS

---

# Slide 01 - Posisi Pertemuan dalam Alur Penelitian

## Alur Penelitian HCI

```text
Problem → Literature Review → Gap → RQ → Hypothesis → Variables → Measures
                                                  │
                                                  ▼
                              Desain Eksperimen / User Study
                                                  │
                                                  ▼
                                        Data → Evidence → Contribution
```

Pertemuan ini berada pada tahap **perumusan dan desain studi kuantitatif** setelah mahasiswa menemukan *research gap* pada pertemuan sebelumnya.

## Kaitan Antarpertemuan

| Pertemuan | Fokus | Luaran |
|---|---|---|
| 5 | Literature Review & Critical Paper Reading | State of the art, research gap |
| 6 | Quantitative HCI Research | RQ, hipotesis, variabel, measures, desain eksperimen |
| 7 | Qualitative & Mixed-Methods HCI Research | Finalisasi metode penelitian |

---

# Slide 02 - Tujuan Pembelajaran

Setelah mengikuti pertemuan ini, mahasiswa diharapkan mampu:

- Menjelaskan karakteristik *empirical research* dan *experimental research* dalam HCI.
- Membedakan jenis variabel dan ancaman terhadap kesimpulan kausal.
- Merancang eksperimen dengan *between-subject*, *within-subject*, *mixed*, atau *factorial design*.
- Menjelaskan peran randomisasi, counterbalancing, sampling, dan statistical power.
- Menentukan *objective/subjective measures* yang selaras dengan research question.
- Melakukan **experimental design critique** terhadap paper penelitian HCI.

Tujuan ini mendukung CPMK-4, CPMK-5, dan CPMK-6.

---

# Slide 03 - Fokus Pertemuan: Valid Evidence

Bukan sekadar membandingkan interface:

> Pertanyaan utama bukan "A lebih baik daripada B?", melainkan **"Mengapa A berbeda dari B, dalam kondisi apa, dan seberapa kuat buktinya?"**

## Valid Evidence

- Efek yang diamati benar-benar disebabkan oleh variabel yang dimanipulasi.
- Tidak ada penjelasan alternatif yang lebih masuk akal.
- Pengukuran sesuai dengan konstruk yang ingin diukur.
- Kesimpulan tidak melampaui partisipan, tugas, atau konteks studi.

Kemampuan merancang studi menentukan apakah hasil dapat dipercaya sebagai **evidence** atau hanya artefak prosedur.

---

# Slide 04 - Apa itu Quantitative HCI Research?

## Ciri Umum

- Menggunakan data numerik.
- Melakukan pengukuran terstruktur.
- Menganalisis pola secara statistik.
- Menguji hubungan atau perbedaan antar kondisi.

## Bentuk Quantitative Research di HCI

| Bentuk | Pertanyaan Khas |
|---|---|
| Controlled experiment | Apakah teknik X mempercepat penyelesaian tugas? |
| Quasi-experiment | Apakah pengguna dengan pengalaman tinggi berbeda perilakunya? |
| Survey kuantitatif | Bagaimana skor kepercayaan pengguna terhadap AI? |
| Interaction log analysis | Bagaimana pola gerakan kursor pada antarmuka tertentu? |

Pertemuan ini menekankan **experimental research** sebagai inti quantitative HCI research.

---

# Slide 05 - Empirical Research dan Experimental Research

## Empirical Research

- Bergantung pada observasi dan data nyata, bukan opini atau spekulasi.
- Dapat dilakukan tanpa manipulasi, misalnya studi log dan pengukuran lapangan.
- Hasilnya harus dapat direplikasi atau direproduksi.

## Experimental Research

- Merupakan subset empirical research.
- Peneliti **memanipulasi** satu atau lebih variabel.
- Peneliti **mengontrol** kondisi lain.
- Tujuan utamanya adalah menarik kesimpulan **sebab-akibat**.

```text
Empirical Research ──► Eksperimen ──► Manipulasi + Kontrol + Pengukuran
```

---

# Slide 06 - Anatomi Controlled Experiment

## Komponen Dasar

1. **Manipulasi** variabel bebas.
2. **Pengukuran** variabel terikat.
3. **Pengendalian** variabel lain yang dapat mengganggu.
4. **Penempatan partisipan** pada kondisi secara sistematis.

## Representasi Sederhana

```text
Kondisi A  ─────────────┐
                        ├─► Pengukuran DV
Kondisi B  ─────────────┘

Variabel pengganggu ──► DIKONTROL / DIRANDOMISASI
```

Controlled experiment di HCI bertujuan menghasilkan **perbandingan yang adil** antara kondisi, bukan hanya mengamati perilaku.

---

# Slide 07 - Contoh Eksperimen HCI

## Ilustrasi

**Research question:**  
Apakah menu yang dikelompokkan secara kategoris mempercepat pencarian perintah daripada menu linear?

## Desain Awal

| Aspek | Rincian |
|---|---|
| IV | Jenis menu: kategoris vs linear |
| DV | Waktu pencarian, jumlah kesalahan navigasi |
| Tugas | Menemukan perintah tertentu |
| Partisipan | Pengguna familiar dengan aplikasi |
| Unit analisis | Sesi pencarian, bukan keseluruhan tugas |

Hipotesis awal:

- Waktu pencarian menu kategoris lebih singkat.
- Kesalahan navigasi lebih sedikit untuk menu kategoris.

---

# Slide 08 - Independent Variable

## Definisi

Independent variable (IV) adalah variabel yang **dimanipulasi** oleh peneliti untuk melihat efeknya.

## Contoh IV dalam HCI

| Konstruk | Operasionalisasi |
|---|---|
| Jenis feedback | Visual vs haptic |
| Mode interaksi | Voice vs gesture |
| Format penjelasan AI | Teks vs grafik |
| Kompleksitas menu | Dua level vs lima level |

## Catatan

- Setiap IV memiliki minimal dua level/kondisi.
- Level harus didefinisikan secara operasional agar dapat direplikasi.
- Variabel seperti usia atau jenis kelamin tidak dimanipulasi, tetapi dapat menjadi faktor pengelompokan dalam desain faktorial.

---

# Slide 09 - Dependent Variable

## Definisi

Dependent variable (DV) adalah **hasil yang diukur** untuk melihat efek dari IV.

## Contoh DV dalam HCI

| Jenis | Contoh |
|---|---|
| Performance | Completion time, throughput, error rate |
| Perilaku | Jumlah klik, durasi pandangan, penggunaan undo |
| Responses | Skor kepercayaan, beban kerja, kepuasan |
| Fisiologis | Heart rate, pupil dilation, EEG |

## Prinsip

- DV harus berhubungan langsung dengan research question.
- Tentukan **primary DV** sebelum analisis.
- Operasionalisasi pengukuran harus konsisten untuk semua partisipan.

---

# Slide 10 - Control Variable

## Definisi

Control variable adalah kondisi yang **dibuat sama** atau **dikendalikan** agar tidak membiaskan perbandingan antar kondisi.

## Contoh Control Variable

| Level | Contoh |
|---|---|
| Lingkungan | Ruangan, pencahayaan, monitor, perangkat input |
| Tugas | Teks yang sama, skenario sama, batas waktu sama |
| Prosedur | Instruksi dibacakan dengan skrip sama |
| Partisipan | Kriteria inklusi/eksklusi |

## Fungsi

- Mengurangi noise sehingga efek IV lebih mudah terdeteksi.
- Membantu memastikan perbedaan hasil bukan karena kondisi lingkungan atau prosedur.

---

# Slide 11 - Confounding Variable

## Definisi

Confounding variable **berubah bersamaan** dengan IV dan dapat menjelaskan perbedaan DV tanpa melibatkan IV.

## Contoh Confound dalam Eksperimen HCI

| Kajian Palsu | Confound yang Mungkin |
|---|---|
| UI baru lebih cepat | Grup UI baru kebanyakan pengguna expert |
| Mode suara lebih lambat | Instruksi mode suara kurang jelas |
| Menu A lebih baik | Tugas untuk menu A lebih sederhana |
| Urutan B selalu setelah A | Ada efek belajar |

## Strategi Mengatasi

- Randomisasi alokasi partisipan.
- Memakai tugas dan prosedur yang sama.
- Counterbalancing urutan kondisi.
- Mengukur variabel pembaur dan memasukkannya dalam analisis.

---

# Slide 12 - Between-Subject Design

## Definisi

Setiap partisipan hanya berada pada **satu kondisi**.

```text
Partisipan → dibagi acak
   ├─► Kelompok A → Kondisi A
   └─► Kelompok B → Kondisi B
```

## Karakteristik

- Pengamatan antar kelompok bersifat independen.
- Cocok jika suatu kondisi membutuhkan waktu lama atau tidak dapat diulang.
- Menghindari *carryover effect* dari kondisi lain.

## Kelemahan

- Perbedaan individu antar kelompok menjadi noise.
- Umumnya membutuhkan jumlah partisipan lebih besar.

---

# Slide 13 - Within-Subject Design

## Definisi

Setiap partisipan menerima **semua kondisi**.

```text
Partisipan → Kondisi A → Kondisi B
Partisipan → Kondisi B → Kondisi A
```

## Karakteristik

- Disebut juga *repeated measures design*.
- Menghapus perbedaan individual antar kondisi.
- Lebih efisien dalam jumlah partisipan.
- Meningkatkan statistical power.

## Tantangan

- **Order effect**: urutan memengaruhi hasil.
- **Carryover effect**: keterampilan atau kelelahan dari kondisi sebelumnya terbawa.
- Solusi utama: counterbalancing.

---

# Slide 14 - Between vs Within

## Perbandingan Ringkas

| Aspek | Between-Subject | Within-Subject |
|---|---|---|
| Partisipan per kondisi | Berbeda | Sama |
| Varians personal | Tidak dikontrol | Dikontrol |
| Jumlah partisipan | Lebih besar | Lebih hemat |
| Order effect | Tidak ada | Ada, perlu counterbalance |
| Durasi sesi | Pendek | Bisa panjang |
| Risiko drop-out | Berdampak satu kelompok | Dapat kehilangan data satu partisipan |

## Kapan Memilih?

- Pilih *between* jika manipulasi sulit diulang, misalnya pelatihan panjang.
- Pilih *within* jika perbedaan individu besar dan carryover dapat dikendalikan.

---

# Slide 15 - Mixed Design dalam Eksperimen

## Definisi

Mixed design menggabungkan setidaknya satu **between-subject factor** dan satu **within-subject factor**.

## Contoh

| Faktor | Jenis | Level |
|---|---|---|
| Kelompok pengguna | Between | Novice vs Expert |
| Jenis antarmuka | Within | A vs B |

Dengan desain ini:

- Setiap partisipan hanya menjadi novice/expert.
- Setiap partisipan mencoba antarmuka A dan B.
- Peneliti dapat melihat interaksi antara keahlian dan antarmuka.

## Catatan Penting

Mixed design dalam bahasa Inggris eksperimen **tidak sama** dengan mixed methods yang akan dibahas pada pertemuan 7.

---

# Slide 16 - Factorial Design

## Definisi

Factorial design menggunakan **dua atau lebih IV** dan seluruh kombinasinya diuji.

## Notasi

| Notasi | Jumlah Kondisi |
|---|---|
| 2 × 2 | 4 kondisi |
| 2 × 3 | 6 kondisi |
| 2 × 2 × 3 | 12 kondisi |

## Contoh Desain 2 × 2

| | Task Rendah | Task Tinggi |
|---|---|---|
| **Menu** | Menu + Rendah | Menu + Tinggi |
| **Command** | Command + Rendah | Command + Tinggi |

Factorial design memungkinkan analisis **efek utama** dan **interaksi**.

---

# Slide 17 - Main Effect dan Interaction

## Efek Utama

Rata-rata perbedaan pengaruh satu IV terhadap DV, tanpa melihat level IV lain.

## Interaksi

Efek satu IV **berbeda tergantung level** IV lain.

## Contoh Interpretasi

- Shortcuts lebih cepat daripada menu untuk perintah yang sering dipakai.
- Untuk perintah yang jarang dipakai, shortcuts justru lebih lambat karena sulit diingat.

Kesimpulan sederhana "shortcuts lebih cepat" tidak cukup akurat. Kehadiran interaksi menunjukkan generalisasi perlu bersyarat.

## Manfaat

Hasil faktorial menghasilkan **pengetahuan yang lebih kaya** daripada perbandingan dua kondisi sederhana.

---

# Slide 18 - Randomization

## Definisi

Randomization adalah penempatan partisipan, tugas, atau stimulus ke kondisi secara **acak**.

## Tujuan

- Mencegah bias alokasi.
- Menyeimbangkan faktor yang diketahui maupun tidak diketahui.
- Membuat kelompok pembanding sebanding secara probabilistik.

## Ilustrasi

```text
Partisipan 01–20 → diacak
Kelompok A = 10 partisipan pertama hasil acak
Kelompok B = 10 partisipan sisanya
```

## Catatan Praktik

- Randomisasi alokasi tidak berarti sampel diambil secara acak dari populasi.
- Untuk sampel kecil, gunakan *block randomization* agar jumlah kelompok seimbang.
- Untuk karakteristik penting yang diketahui, gunakan *stratified randomization*.

---

# Slide 19 - Counterbalancing

## Definisi

Counterbalancing mengatur urutan kondisi agar **order effect** tidak selalu berpihak pada satu kondisi.

## Contoh Sederhana

```text
Separuh partisipan: A → B
Separuh partisipan: B → A
```

## Latin Square

Untuk lebih dari dua kondisi:

```text
A B C D
B C D A
C D A B
D A B C
```

Setiap kondisi muncul sekali pada setiap posisi.

## Tujuan

- Mengubah kebingungan antara efek kondisi dan efek urutan.
- Counterbalancing tidak menghilangkan order effect, tetapi membuatnya dapat diperhitungkan.

---

# Slide 20 - Sampling

## Target Populasi dan Sampel

- **Target population**: populasi yang ingin digeneralisasi.
- **Sampling frame**: daftar orang yang dapat diakses.
- **Sample**: bagian populasi yang benar-benar berpartisipasi.

## Strategi Sampling

| Strategi | Contoh |
|---|---|
| Convenience | Mahasiswa kampus yang mudah direkrut |
| Purposive | Pengguna dengan pengalaman tertentu |
| Snowball | Rekrut melalui partisipan awal |
| Quota | Sesuai proporsi usia/jenis kelamin |

## Dalam Eksperimen HCI

- Sampel convenience umum digunakan pada studi terkontrol.
- Batas generalisasi harus diakui dan didiskusikan.
- Kriteria inklusi/eksklusi harus dilaporkan agar studi dapat direplikasi.

---

# Slide 21 - Sample Size

## Prinsip Umum

- Sampel terlalu kecil → hasil tidak stabil.
- Sampel terlalu besar → sumber daya tidak efisien.
- Jumlah partisipan ditentukan sebelum pengumpulan data.

## Faktor Penentu

| Faktor | Arah |
|---|---|
| Effect size yang diharapkan | Semakin kecil efek, semakin besar sampel dibutuhkan |
| Variabilitas data | Semakin bervariasi, semakin besar sampel |
| Tingkat signifikansi α | Semakin kecil α, semakin besar sampel |
| Statistical power | Semakin tinggi power, semakin besar sampel |
| Desain | Within-subject umumnya membutuhkan sampel lebih kecil |

## Perhatian

Tidak ada angka universal seperti "n = 30 selalu cukup". Justifikasi diperlukan berdasarkan desain dan target deteksi efek.

---

# Slide 22 - Statistical Power

## Definisi

Statistical power adalah probabilitas sebuah studi **menemukan efek yang benar-benar ada**.

```text
Power = 1 − β
β = peluang false negative / lolos efek yang nyata
```

## Nilai yang Lazim

- Power minimal umumnya **0.80**.
- Artinya, bila efek benar-benar ada, studi memiliki peluang 80% untuk mendeteksinya.

## Mengapa Penting

- Studi *underpowered* sering menghasilkan hasil non-signifikan yang menyesatkan.
- Perencanaan power dilakukan saat menentukan sample size.
- Peneliti HCI perlu melaporkan power atau setidaknya alasannya.

Power bukan jaminan kebenaran, tetapi meningkatkan kualitas evidence.

---

# Slide 23 - Objective vs Subjective Measures

## Perbandingan

| Aspek | Objective Measures | Subjective Measures |
|---|---|---|
| Sumber | Log, sensor, hasil tugas | Self-report partisipan |
| Contoh | Waktu, error, jumlah klik | Kuesioner, rating, skala |
| Kelebihan | Relatif bebas dari penilaian peneliti | Menangkap pengalaman |
| Keterbatasan | Tidak menjelaskan alasan | Dipengaruhi persepsi dan konteks |

## Contoh

- Kecepatan menyelesaikan tugas disebut **objective**.
- Persepsi kemudahan penggunaan disebut **subjective**.
- Keduanya dapat bertentangan: sistem lebih cepat tetapi dianggap lebih sulit.

Pengukuran terbaik disesuaikan dengan konstruk dalam research question.

---

# Slide 24 - Hypothesis dalam Quantitative HCI

## Definisi

Hipotesis adalah pernyataan yang dapat diuji mengenai hubungan yang diharapkan antar variabel.

## Syarat Hipotesis

- Berasal dari research question.
- Dinyatakan secara operasional.
- Dapat ditolak atau tidak didukung oleh data.
- Menghubungkan IV dan DV.

## Contoh

Hipotesis:

> Pengguna yang menerima penjelasan AI interaktif menyelesaikan tugas debugging lebih cepat daripada pengguna yang hanya menerima jawaban AI.

Hipotesis nol yang bersesuaian:

> Tidak ada perbedaan waktu debugging antara kedua kelompok.

---

# Slide 25 - Logika Hypothesis Testing

## Alur Berpikir

```text
Jika H0 benar ──► data seperti apa yang diharapkan?
Bandingkan data aktual ──► hitung p-value
p kecil ──► data tidak sejalan dengan H0
```

## Interpretasi

- p < α sering digunakan sebagai bukti bahwa hasil tidak mungkin terjadi jika hipotesis nol benar.
- p > α **bukan** bukti bahwa hipotesis nol benar.
- Hasil non-signifikan dapat terjadi karena efek kecil, variabilitas tinggi, atau sampel kurang.

## Catatan

Pertemuan 13 akan membahas pelaksanaan uji statistik. Pada pertemuan ini, logika hipotesis penting untuk menentukan desain dan ukuran sampel sejak awal.

---

# Slide 26 - Effect Size

## Definisi

Effect size mengukur **seberapa besar** perbedaan atau hubungan antar kondisi, tanpa terlalu bergantung pada ukuran sampel.

## Contoh Indeks

- Cohen’s d untuk perbedaan rata-rata dua kelompok.
- Correlation coefficient r untuk hubungan.
- Eta squared η² untuk analysis of variance.

## Mengapa Perlu

- Hasil signifikan secara statistik belum tentu bermakna secara praktis.
- Effect size memungkinkan perbandingan dengan penelitian lain.
- Bermanfaat untuk meta-analisis dan perencanaan studi baru.

## Catatan

Batasan kecil/sedang/besar hanyalah heuristik, sedangkan makna efek harus dinilai dalam konteks HCI.

---

# Slide 27 - Confidence Interval

## Definisi

Confidence interval (CI) adalah rentang nilai yang masuk akal untuk parameter populasi berdasarkan sampel.

## Contoh

Jika rata-rata perbedaan waktu adalah 2,1 detik dengan 95% CI [0,8; 3,4], artinya rentang estimasi efek tidak terlalu sempit dan seluruh interval berada di atas nol.

## Fungsi

- Menunjukkan tingkat ketidakpastian estimasi.
- Menyampaikan besaran efek sekaligus presisi.
- Lebih informatif daripada hanya menyatakan signifikan/tidak signifikan.

## Kesalahan Interpretasi yang Harus Dihindari

CI 95% **bukan** berarti terdapat 95% peluang parameter berada dalam interval tersebut.

---

# Slide 28 - Valid Evidence dalam Eksperimen HCI

## Pertanyaan Uji untuk Sebuah Desain

| Dimensi | Pertanyaan |
|---|---|
| Internal validity | Apakah IV benar-benar penyebab perubahan DV? |
| Construct validity | Apakah pengukuran benar-benar mencerminkan konsep? |
| External validity | Apakah hasil dapat bertahan pada populasi/konteks lain? |
| Conclusion validity | Apakah analisis sesuai dengan pola data? |

## Prinsip

- Desain eksperimen ditentukan oleh kebutuhan akan **bukti kausal yang valid**.
- Setiap keputusan desain—kondisi, tugas, partisipan, urutan—berpotensi menjadi *threat to validity*.
- Perancang eksperimen harus mampu menjelaskan mengapa ancaman tersebut sudah dikendalikan.

---

# Slide 29 - Experimental Design Critique

Aktivitas utama pertemuan ini adalah mengkritisi desain eksperimen pada paper HCI.

## Langkah Kritik

1. Temukan research question dan hipotesis.
2. Identifikasi IV, level, dan DV.
3. Sebutkan desain penelitian: between, within, mixed, atau factorial.
4. Periksa jumlah partisipan dan justifikasi sample size.
5. Cek prosedur randomisasi dan counterbalancing.
6. Temukan control variables yang dilaporkan.
7. Cari kemungkinan confounding variables yang belum dikendalikan.
8. Nilai kesesuaian measures dengan research question.

Kritik berfokus pada **kekuatan evidence**, bukan sekadar mengomentari kelemahan kecil paper.

---

# Slide 30 - Latihan Identifikasi Confound

## Studi Ilustrasi

Sebuah paper mengklaim:

> Antarmuka baru berbasis AI mengurangi waktu penyelesaian tugas dibanding antarmuka lama.

Metode yang dilaporkan:

- Grup AI: mahasiswa S2 yang diundang pagi hari.
- Grup kontrol: data pengujian lama dari forum online.
- Grup AI mendapatkan tutorial selama 10 menit.
- Grup kontrol tidak mendapatkan tutorial.

## Tugas

- Sebutkan variabel yang menjadi confound.
- Desain ulang studi agar klaim tersebut dapat diuji secara valid.

---

# Slide 31 - Workflow Merancang Eksperimen Kuantitatif

## Langkah Praktis

```text
RQ → Hipotesis → IV/DV → Measures → Selection of design
     → Randomisasi/counterbalancing → Sample size/power
     → Control procedure → Data analysis plan → Report
```

## Definisi yang Dicatat Sebelum Studi

| Elemen | Contoh Catatan |
|---|---|
| RQ | Apakah format penjelasan AI memengaruhi keputusan? |
| H | Format teks+visual meningkatkan akurasi keputusan |
| IV | Format penjelasan: teks, visual, teks+visual |
| DV | Akurasi, waktu, kepercayaan |
| Control | Task sama, interface sama |
| Design | Within-subject dengan counterbalancing Latin square |
| N | Target 24 berdasarkan power analysis |

---

# Slide 32 - Research Progress: RQ → Hypothesis → Variables → Measures

Progress penelitian minggu ini harus menunjukkan rangkaian logis tersebut.

## Format Deliverable

| Bagian | Contoh Isi |
|---|---|
| Research question | Pertanyaan yang dapat diuji secara empiris |
| Hypothesis | Prediksi hubungan antar variabel |
| Variables | IV, level, DV, control variables |
| Measures | Operasionalisasi setiap variabel |
| Design options | Between/within/mixed/factorial yang mungkin |

## Weekly Progress

Gunakan format:

```text
Progress → Evidence → Problem → Decision → Next Action
```

Lampirkan satu halaman ringkasan desain eksperimen sebagai bukti kemajuan.

---

# Slide 33 - Menuju Pertemuan 7: Qualitative & Mixed Methods

## Pertanyaan Penentu Metode

| Research Question | Metode yang Lebih Sesuai |
|---|---|
| Apakah perbedaan waktu antar kondisi signifikan? | Kuantitatif |
| Bagaimana pengguna memahami hasil AI? | Kualitatif |
| Mengapa teknik tertentu efektif pada kelompok tertentu? | Mixed methods |

## Refleksi

- Metode dipilih berdasarkan research question, bukan prestise.
- Hasil kuantitatif dapat menjelaskan *apa*, sedangkan hasil kualitatif dapat menjelaskan *mengapa*.
- Pada pertemuan 7, mahasiswa akan mempertimbangkan interview, observation, dan mixed methods.

Pertemuan berikutnya: **Qualitative & Mixed-Methods HCI Research**.

---

# Slide 34 - Rangkuman Pertemuan 06

## Konsep Utama

- Quantitative HCI research menuntut perumusan variabel dan desain yang dapat menghasilkan evidence.
- Controlled experiment memerlukan manipulasi IV, pengukuran DV, dan pengendalian variabel lain.
- Desain between/within/mixed/factorial harus dipilih sesuai karakteristik penelitian.
- Randomisasi dan counterbalancing melindungi kesimpulan dari bias.
- Sampling dan sample size menentukan kekuatan evidence.
- Objective dan subjective measures harus sesuai dengan konstruk.
- Effect size dan confidence interval lebih informatif daripada p-value saja.

Inti pertemuan:

> **Evidence yang valid tidak lahir dari alat statistik, tetapi dari desain penelitian yang cermat.**

---

# Slide 35 - Pertanyaan Refleksi dan Tugas

## Refleksi

1. Jika dua antarmuka dibandingkan tanpa randomisasi, klaim apa yang tidak dapat dibuat?
2. Mengapa hasil signifikan secara statistik belum tentu bermakna penting?
3. Kapan peneliti memilih within-subject dibanding between-subject?
4. Apa perbedaan confounding variable dengan control variable?

## Tugas/Bukti Belajar

- **Experimental design critique** terhadap paper kuantitatif pilihan.
- Siapkan draft research progress:

```text
RQ → Hypothesis → Variables → Measures
```

Tugas ini menjadi dasar metodologi untuk Research Proposal Defense pada pertemuan 8.

---

# Slide 36 - Penutup

TERIMA KASIH

Pertemuan berikutnya

**Qualitative & Mixed-Methods HCI Research**