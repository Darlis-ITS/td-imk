# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer

Pertemuan 09

## Usability, UX & User Study Evaluation

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D

Departemen Teknik Informatika - ITS

---

# Slide 01 - Posisi Pertemuan dan Tujuan

## Posisi dalam Alur Mata Kuliah

- Sebelumnya: UTS — Research Proposal Defense.
- Sekarang: merancang **usability evaluation**, **UX evaluation**, dan **user study** sebagai bagian dari rencana penelitian.
- Berikutnya: Human-AI Interaction & Generative AI, yang akan memakai protokol studi yang sudah disiapkan.

## Tujuan Pertemuan

- Membedakan **Product Evaluation** dan **Research Evaluation**.
- Memahami metode evaluasi usability/UX: usability testing, think-aloud, heuristic evaluation, cognitive walkthrough.
- Merancang task dan scenario dengan benar.
- Memilih pengukuran objektif dan subjektif yang sesuai.
- Menuntaskan **instrument dan study protocol** sebagai progress penelitian minggu ini.

---

# Slide 02 - Pengingat Alur Penelitian Semester

Seluruh pertemuan membentuk satu pipeline penelitian:

```text
Research Interest
      ↓
Interaction Problem
      ↓
Research Gap & RQ
      ↓
Research Methodology
      ↓
Evaluation Design  ← Pertemuan 09
      ↓
User Study / Experiment
      ↓
Evidence & Contribution
```

## Milestone Pertemuan 09

- Dari proposal pada UTS, sekarang diturunkan menjadi rancangan evaluasi yang siap dijalankan.
- Fokus bukan pada “apakah sistem saya bagus”, tetapi pada **bagaimana memperoleh data yang dapat menjawab research question**.

---

# Slide 03 - Tiga Wilayah: Usability, UX, dan User Study

Ketiga istilah sering dicampuradukkan. Secara sederhana:

- **Usability evaluation** menilai apakah sistem efektif, efisien, dan memuaskan untuk tugas tertentu.
- **UX evaluation** menilai pengalaman pengguna secara lebih luas: emosi, persepsi, makna, dan nilai pengalaman.
- **User study** adalah studi empiris yang melibatkan partisipan manusia untuk mengumpulkan bukti. User study dapat digunakan untuk mengevaluasi usability maupun UX.

## Hubungan

```text
User Study
├── menilai Usability  → task, waktu, error, efektivitas
├── menilai UX         → emosi, kepuasan, makna, motivasi
└── menguji hipotesis penelitian → variabel dan perlakuan
```

Penting: **tidak semua evaluasi melibatkan pengguna**, dan **tidak semua user study bertujuan memperbaiki produk**.

---

# Slide 04 - Apa Itu Evaluation dalam HCI?

Evaluation adalah proses sistematis untuk mengumpulkan, menganalisis, dan menafsirkan data tentang kualitas interaksi manusia-komputer.

## Dua Jalur Besar

1. **Analytic evaluation / tanpa pengguna**
   - Ahli menilai antarmuka dengan inspeksi, misalnya heuristic evaluation dan cognitive walkthrough.
   - Cepat dan murah, tetapi tidak menggantikan data dari pengguna nyata.

2. **Empirical evaluation / bersama pengguna**
   - Partisipan menggunakan sistem atau melakukan tugas.
   - Menghasilkan data perilaku, persepsi, dan pengalaman.

## Empat Pertanyaan Kunci dalam Merancang Evaluasi

- Apa klaim atau research question yang hendak dijawab?
- Apa bukti yang diperlukan?
- Tugas dan instrumen apa yang dapat menghasilkan bukti tersebut?
- Bagaimana data ditafsirkan menjadi temuan?

---

# Slide 05 - Usability: Definisi dan Dimensi

## Definisi Umum

Usability mengacu pada sejauh mana suatu sistem dapat digunakan oleh pengguna tertentu untuk mencapai tujuan tertentu dengan:

- **efektivitas** — ketepatan dan kelengkapan pencapaian tujuan;
- **efisiensi** — sumber daya yang diperlukan relatif terhadap hasil;
- **kepuasan** — kenyamanan dan penerimaan pengguna.

## Dimensi yang Sering Digunakan

| Dimensi | Pertanyaan Kunci |
|---|---|
| Learnability | Seberapa mudah pengguna baru menyelesaikan tugas pada kali pertama? |
| Efficiency | Seberapa cepat tugas diselesaikan setelah pengguna terbiasa? |
| Memorability | Apakah pengguna yang kembali masih ingat cara menggunakan? |
| Errors | Seberapa banyak kesalahan dan seberapa parah dampaknya? |
| Satisfaction | Seberapa nyaman pengguna dengan pengalaman tersebut? |

Usability selalu terkait dengan **pengguna, tugas, dan konteks penggunaan tertentu**.

---

# Slide 06 - UX: Melampaui Usability

## Pandangan UX

UX mencakup **persepsi dan respons pengguna** sebelum, selama, dan setelah menggunakan sistem.

Aspek yang termasuk:

- emosi dan perasaan;
- kepercayaan dan keyakinan;
- preferensi;
- beban kognitif;
- makna dan nilai yang dirasakan;
- respon fisik dan psikologis.

## Perbedaan Tekanan

| Fokus Usability | Fokus UX |
|---|---|
| Efektivitas tugas | Kualitas pengalaman |
| Waktu dan error | Kenyamanan, kesenangan, makna |
| Bagaimana sistem bekerja | Bagaimana pengguna merasa dan menilai |
| Lebih objektif | Lebih subjektif |

Untuk penelitian, usability dan UX bukan “pilihan salah satu”, tetapi bisa menjadi **dua konstruk yang berbeda** dan diukur dengan instrumen berbeda.

---

# Slide 07 - User Study sebagai Metode Penelitian

## Apa itu User Study?

User study adalah studi empiris yang merekrut partisipan manusia untuk menguji sistem, memahami perilaku, atau menjawab pertanyaan penelitian.

Bentuk umum user study di HCI:

- eksperimen terkontrol;
- usability testing;
- studi lapangan;
- studi survei;
- diary study;
- wawancara dan observasi.

## Posisi dalam Penelitian

```text
Research Question
      ↓
User Study / Experiment
      ↓
Data: perilaku + persepsi
      ↓
Evidence dan interpretasi
```

Di pertemuan sebelumnya, Anda telah memilih desain kuantitatif, kualitatif, atau mixed. Pertemuan ini mengarah pada **instrumentasi, task, dan protokol** dari desain tersebut.

---

# Slide 08 - Fokus Utama: Product Evaluation vs Research Evaluation

Dalam praktik, kita dapat mengevaluasi sebuah produk untuk memperbaikinya, atau melakukan evaluasi sebagai bagian dari penelitian untuk menghasilkan pengetahuan baru.

Keduanya dapat menggunakan alat yang serupa, tetapi **tujuan, klaim, dan cara melaporkannya berbeda**.

## Mengapa Membedakan?

- **Product evaluation** berkata: “temukan masalah pada sistem ini lalu perbaiki”.
- **Research evaluation** berkata: “umumkan temuan tentang fenomena interaksi manusia-komputer dan sumbangkan pengetahuan”.

Kesalahan membedakan keduanya sering membuat penelitian HCI menjadi sekadar laporan pengembangan aplikasi.

---

# Slide 09 - Apa Itu Product Evaluation?

## Karakteristik

- Bertujuan **memperbaiki atau memvalidasi produk** tertentu.
- Fokus pada keputusan desain: fitur mana yang dipakai, alur mana yang membingungkan, mana yang harus direvisi.
- Pertanyaan khas:
  - Apakah pengguna dapat menyelesaikan pembelian tanpa bantuan?
  - Di bagian mana form menyebabkan kesalahan?
  - Apakah pengguna puas dengan versi baru?
- Hasil utama: **temuan masalah usability, rekomendasi perbaikan, keputusan desain**.

## Contoh Luaran

- Daftar masalah urut berdasarkan tingkat keparahan.
- Klip video yang menunjukkan frustrasi pengguna.
- Saran prioritas untuk tim pengembang.

Dalam product evaluation, iterasi dapat dilakukan secara cepat dan protokol dapat berubah di tengah pengujian.

---

# Slide 10 - Apa Itu Research Evaluation?

## Karakteristik

- Bertujuan **menjawab research question atau menguji hipotesis**.
- Fokus pada hubungan antar variabel, mekanisme interaksi, atau pemahaman mendalam tentang pengalaman manusia.
- Pertanyaan khas:
  - Apakah desain penjelasan AI yang berbeda memengaruhi kepercayaan pengguna?
  - Bagaimana gangguan visual memengaruhi performa tugas di perangkat bergerak?
  - Mengapa pengguna lebih memilih antarmuka percakapan daripada menu?
- Hasil utama: **evidence**, temuan empiris, dan kontribusi ilmiah.

## Contoh Luaran

- Uji statistik perbedaan antar kondisi.
- Tema hasil analisis kualitatif.
- Implikasi desain yang dapat digunakan peneliti lain.

Dalam research evaluation, **protokol harus stabil** agar data yang dikumpulkan dapat dibandingkan dan direplikasi.

---

# Slide 11 - Perbandingan Kedua Perspektif

| Aspek | Product Evaluation | Research Evaluation |
|---|---|---|
| Tujuan utama | Memperbaiki produk | Menghasilkan pengetahuan |
| Fokus | Masalah dan kepuasan pemakaian | Variabel, konstruk, dan fenomena |
| Pertanyaan | “Apakah sistem ini dipakai dengan baik?” | “Bagaimana manusia berinteraksi dan mengapa?” |
| Partisipan | Pengguna representatif produk | Sampel yang menjawab populasi penelitian |
| Tugas | Skenario penggunaan nyata | Operasionalisasi tugas dari RQ |
| Analisis | Masalah dan rekomendasi | Evidence statistik/tematik |
| Kontribusi | Kualitas produk | Scientific contribution |

Keduanya sah, tetapi penelitian tugas akhir perlu jelas: **kontribusi akhir bukan hanya produk yang sudah diuji**.

---

# Slide 12 - Dampak Perbedaan pada Keputusan Studi

## Jika Evaluasi Berorientasi Produk

- Boleh mengubah task ketika peserta menemui hal tak terduga.
- Cukup moderat mengarahkan partisipan.
- Melaporkan temuan secara naratif dan rekomendasi.

## Jika Evaluasi Berorientasi Penelitian

- **Task dan protokol ditetapkan sebelum pengambilan data utama**.
- Perubahan kecil dapat menjadi bias jika tidak dicatat dan dilaporkan.
- Setiap keputusan pengukuran harus dihubungkan dengan RQ.
- Hasil dianalisis dengan metode yang telah direncanakan.
- Prosedur perlu cukup rinci agar studi dapat direplikasi.

## Kesimpulan

Pertemuan ini menekankan **Research Evaluation**, karena milestone akhir Anda adalah paper penelitian. Namun, prinsip product evaluation tetap digunakan ketika melakukan iterasi desain sebelum studi final.

---

# Slide 13 - Workflow Desain Evaluasi

Tahapan penting dalam merancang user study:

```text
Research Question / Hypothesis
        ↓
Pilih jenis studi dan variabel
        ↓
Operasionalisasi variabel
        ↓
Rancang task dan scenario
        ↓
Pilih instrumen dan pengukuran
        ↓
Susun protokol, consent, prosedur
        ↓
Pilot study
        ↓
Perbaiki protokol/instrumen
        ↓
Ambil data utama
```

## Prinsip

- Setiap keputusan kembali ke RQ.
- Variabel harus terukur secara jelas.
- Task dan instrumen diuji melalui pilot.
- Protokol final bersifat eksplisit, terdokumentasi, dan dapat direplikasi.

---

# Slide 14 - Desain Task dan Scenario: Definisi

## Task

**Task** adalah aktivitas berorientasi tujuan yang harus dilakukan partisipan selama studi.

Contoh task:

- “Temukan informasi jadwal kereta dari Surabaya ke Malang besok pagi.”
- “Buat dokumen baru lalu simpan dalam format PDF.”
- “Klasifikasikan lima email ke folder yang sesuai.”

## Scenario

**Scenario** adalah narasi kontekstual yang membungkus task agar partisipan memahami situasi, motivasi, dan kondisi penggunaan.

Contoh scenario:

- “Anda sedang merencanakan perjalanan dinas. Anda ingin membandingkan jadwal kereta pagi yang paling awal dan mencatat harga tiketnya.”

Scenario membuat tugas lebih realistis dan membantu partisipan memasuki situasi yang diteliti.

---

# Slide 15 - Task Design: Prinsip Utama

| Prinsip | Penjelasan |
|---|---|
| Relevan dengan RQ | Task harus menggambarkan aktivitas yang berkaitan dengan variabel yang diteliti. |
| Representatif | Task mewakili penggunaan nyata atau aktivitas yang menjadi fokus klaim penelitian. |
| Jelas awal dan akhir | Partisipan tahu kapan tugas dimulai dan hasil akhir yang diharapkan. |
| Tingkat kesulitan sesuai | Tidak terlalu mudah sampai menimbulkan efek ceiling, atau terlalu sulit sampai semua gagal. |
| Sebanding antar partisipan | Wording dan media yang digunakan sama untuk semua kondisi. |
| Tidak membocorkan hipotesis | Instruksi tidak mengarahkan partisipan pada jawaban atau perilaku yang diharapkan. |
| Memiliki kriteria sukses | Peneliti harus mendefinisikan apa yang dihitung sebagai keberhasilan. |

## Catatan

Task dapat disusun bertingkat:

- Task utama: menyelesaikan tujuan akhir.
- Sub-task: langkah-langkah antara yang diamati untuk melihat proses.

---

# Slide 16 - Scenario Design: Struktur Narasi

Sebuah scenario yang baik biasanya memuat:

1. **Aktor dan peran**
   - “Anda adalah seorang mahasiswa magister yang sedang menyusun tinjauan pustaka.”
2. **Situasi atau konteks**
   - “Anda sedang berada di perpustakaan digital kampus.”
3. **Motivasi**
   - “Anda membutuhkan artikel tentang generative AI dan user trust.”
4. **Batasan dan sumber daya**
   - “Anda hanya dapat menggunakan basis data yang tersedia di langganan kampus.”
5. **Hasil akhir yang diharapkan**
   - “Simpan lima artikel yang paling relevan ke folder Anda.”

## Kegunaan

- Membuat task lebih alami.
- Mengurangi kebingungan partisipan: “mengapa saya melakukan ini?”
- Membantu menjaga kondisi emosi dan motivasi antar partisipan tetap sebanding.

---

# Slide 17 - Contoh Task dan Scenario dalam Satu Studi

## Contoh Konteks Riset

Meneliti pengaruh antarmuka pencarian terhadap efisiensi literature review.

## Task

“Cari artikel jurnal dari tahun 2020–2024 dengan kata kunci ‘usability evaluation’ dan ‘user experience’.”

## Scenario

“Anda sedang menulis bagian related work. Anda belum memiliki artikel yang cukup. Gunakan sistem pencarian yang tersedia untuk menemukan artikel-artikel yang relevan. Anda perlu mengumpulkan judul, penulis, dan DOI dari lima artikel paling relevan.”

## Instruksi Tambahan

- Mulailah setelah komputer menampilkan halaman awal.
- Jika Anda merasa selesai, klik tombol ‘Selesai’ pada layar.
- Tidak ada jawaban salah; kami ingin memahami cara Anda bekerja.

---

# Slide 18 - Usability Testing: Pengaturan dan Peran

## Definisi

Usability testing adalah metode empiris yang mengamati perwakilan pengguna saat menyelesaikan task pada suatu sistem atau prototipe.

## Peran yang Perlu Ditetapkan

| Peran | Tugas |
|---|---|
| Moderator/Fasilitator | Memberi instruksi, menjaga alur, tidak membantu secara berlebihan |
| Participant | Mengerjakan task dengan wajar |
| Observer/Logger | Mencatat perilaku, waktu, error, dan komentar penting |
| Sistem/Recording | Merekam layar, audio, log interaksi, atau video |

## Alur Umum

1. Sambutan dan informed consent.
2. Kuesioner awal atau data demografi.
3. Pemanasan/practice task.
4. Task utama, dengan think-aloud jika diperlukan.
5. Kuesioner setelah penggunaan.
6. Debrief dan klarifikasi.

Usability testing dapat bersifat **formative** untuk memperbaiki desain, atau **summative** untuk menilai kualitas akhir.

---

# Slide 19 - Think-Aloud dalam User Study

## Konsep

Partisipan diminta **mengungkapkan pikiran mereka secara verbal** saat mengerjakan task.

- Concurrent think-aloud: berkomentar saat bekerja.
- Retrospective think-aloud: berkomentar setelah melihat rekaman perilaku sendiri.

## Manfaat

- Mengungkap alasan di balik tindakan.
- Menemukan kebingungan yang tidak terlihat dari log.
- Memberi data kualitatif yang kaya untuk analisis.

## Perhatian

- Berbicara dapat mengubah perilaku dan memperlambat kerja.
- Jika fokus utama adalah **waktu tugas yang presisi**, gunakan retrospective think-aloud atau pisahkan sesi.
- Dalam penelitian, transkrip think-aloud adalah data kualitatif yang perlu dikodekan dengan metode sistematis, bukan sekadar catatan komentar.

---

# Slide 20 - Heuristic Evaluation

## Karakteristik

- Dilakukan oleh **evaluator ahli**, bukan pengguna.
- Antarmuka diperiksa terhadap seperangkat prinsip/heuristik usability.
- Efisien untuk menemukan potensi masalah sebelum pengujian dengan pengguna.

## Sepuluh Heuristik yang Umum Dipakai

1. Visibilitas status sistem.
2. Kecocokan sistem dengan dunia nyata.
3. User control dan kebebasan.
4. Konsistensi dan standar.
5. Pencegahan error.
6. Recognition rather than recall.
7. Fleksibilitas dan efisiensi penggunaan.
8. Desain estetis dan minimalis.
9. Membantu pengguna mengenali, mendiagnosis, dan memulihkan error.
10. Bantuan dan dokumentasi.

## Luaran

- Daftar masalah.
- Severity rating, misalnya 0–4.
- Lokasi dan penjelasan heuristik yang dilanggar.

Heuristic evaluation menghasilkan **temuan potensial**, bukan bukti perilaku pengguna nyata.

---

# Slide 21 - Cognitive Walkthrough

## Konsep

Cognitive walkthrough berfokus pada **kemudahan dipelajari** suatu sistem, terutama untuk pengguna yang baru pertama kali.

Evaluator mensimulasikan langkah demi langkah yang akan dilakukan pengguna dalam task tertentu.

## Empat Pertanyaan terhadap Setiap Langkah

1. Apakah pengguna akan mencoba mencapai efek yang benar?
2. Apakah pengguna akan menyadari bahwa kontrol/aksi yang benar tersedia?
3. Apakah pengguna akan menghubungkan kontrol tersebut dengan tujuannya?
4. Setelah aksi dilakukan, apakah pengguna mendapat umpan balik yang cukup?

## Kapan Digunakan

- Alur task sudah jelas dan berupa prosedur.
- Ingin mengevaluasi kemampuan penemuan fitur oleh pengguna baru.
- Tidak memerlukan partisipan, tetapi tetap membutuhkan pemahaman mendalam tentang pengguna dan task.

---

# Slide 22 - Perbandingan Metode Evaluasi

| Metode | Melibatkan User? | Data Utama | Kegunaan Utama |
|---|---|---|---|
| Heuristic Evaluation | Tidak | Penilaian ahli terhadap masalah potensial | Menemukan masalah lebih awal |
| Cognitive Walkthrough | Tidak | Simulasi kognitif oleh ahli | Menilai learnability alur tertentu |
| Usability Testing | Ya | Observasi, log, waktu, error, verbalisasi | Mengamati perilaku nyata |
| Think-Aloud | Ya | Data verbal selama/retrospektif | Memahami alasan dan proses berpikir |
| Kuesioner UX | Ya | Skor subjektif | Mengukur kepuasan, beban, pengalaman |
| Controlled Experiment | Ya | Data kuantitatif untuk menguji hipotesis | Menjawab RQ dengan kontrol ketat |

## Pilihan Bukan Berdasarkan “Metode Terbaik”

Pilih metode berdasarkan **jenis pertanyaan, tahap penelitian, dan bukti yang diperlukan**.

---

# Slide 23 - Pengukuran: Objective vs Subjective

## Objective Measurement

- Data yang dapat diamati dan direkam secara langsung.
- Contoh:
  - waktu penyelesaian task;
  - tingkat keberhasilan;
  - jumlah error;
  - jumlah klik;
  - interaction logs.

## Subjective Measurement

- Data yang dilaporkan sendiri oleh partisipan.
- Contoh:
  - System Usability Scale (SUS);
  - User Experience Questionnaire (UEQ);
  - NASA-TLX;
  - pertanyaan trust atau emotion;
  - wawancara.

## Prinsip

- Subjective bukan berarti kurang ilmiah.
- Objektivitas terletak pada **definisi operasional, prosedur, dan skoring yang jelas**.
- Peneliti harus memilih ukuran yang memang merepresentasikan konstruk pada RQ.

---

# Slide 24 - Behavioral Measures: Completion, Time, Error

## Task Completion / Success

- Apakah partisipan mencapai hasil yang benar?
- Perlu kriteria sukses yang dapat diverifikasi sebelum studi.

```text
Task success = 1 jika outcome mencukupi kriteria
               0 jika tidak selesai / salah
Partial success = hasil sebagian tercapai
```

## Completion Time

- Waktu dari mulai task hingga task selesai atau dihentikan.
- Tentukan aturan:
  - apakah task gagal tetap dihitung?
  - berapa batas maksimum?
- Hati-hati dengan outliers dan partisipan yang menyerah.

## Error Rate

- Jumlah kesalahan langkah atau kesalahan hasil.
- Dapat dihitung dari observasi dan log interaksi.
- Error perlu didefinisikan terlebih dahulu agar antar penilai sama.

---

# Slide 25 - Interaction Logs

## Definisi

Log interaksi adalah data otomatis yang berisi jejak aktivitas pengguna saat berinteraksi dengan sistem.

Contoh event yang dapat dicatat:

- klik;
- penekanan tombol;
- scroll;
- perpindahan halaman;
- penggunaan perintah;
- waktu setiap aksi.

## Keunggulan

- Presisi waktu tinggi.
- Tidak terlalu bergantung pada ingatan partisipan.
- Mendukung analisis proses, bukan hanya hasil akhir.
- Dapat menghitung completion time dan error secara objektif.

## Kelemahan

- Log tidak menjelaskan alasan atau motivasi.
- Tindakan yang sama dapat memiliki makna berbeda.
- Perlu sinkronisasi dengan task dan system time.

Dalam research evaluation, log harus dirancang bersama sistem eksperimen sebelum data diambil.

---

# Slide 26 - Kuesioner Standar: SUS

## System Usability Scale

- Terdiri dari 10 pernyataan, respon 1–5.
- Mengukur **perceived usability** secara cepat.
- Pernyataan bergantian positif dan negatif.

## Cara Skoring

```text
Untuk item ganjil (1,3,5,7,9):
    kontribusi = skala - 1
Untuk item genap (2,4,6,8,10):
    kontribusi = 5 - skala

Total SUS = jumlah kontribusi × 2,5
```

## Interpretasi

- Skor berada pada rentang 0–100.
- **SUS bukan persentase**.
- Interpretasi lebih baik dilakukan dengan membandingkan konteks dan literatur.

---

# Slide 27 - Kuesioner Standar: UEQ

## User Experience Questionnaire

- Mengukur pengalaman pengguna melalui 26 pasang kata yang berlawanan.
- Respon partisipan diletakkan pada skala semantik 1–7.

## Skala UEQ

| Skala | Jenis | Contoh Pasangan Kata |
|---|---|---|
| Attractiveness | Overall impression | menyenangkan / tidak menyenangkan |
| Perspicuity | Kemudahan dipahami | jelas / membingungkan |
| Efficiency | Efisiensi | cepat / lambat |
| Dependability | Kontrol dan prediktabilitas | dapat diprediksi / tidak dapat diprediksi |
| Stimulation | Motivasi | menarik / membosankan |
| Novelty | Kebaruan | inovatif / konvensional |

## Interpretasi

- Jangan menjumlahkan seluruh skala menjadi satu skor tunggal.
- Laporkan per skala.
- Skala pragmatis: Perspicuity, Efficiency, Dependability.
- Skala hedonis: Stimulation, Novelty.

---

# Slide 28 - Kuesioner Standar: NASA-TLX

## NASA Task Load Index

- Mengukur **beban kerja yang dirasakan** selama menyelesaikan task.
- Cocok untuk studi yang membandingkan antarmuka atau interaksi yang membutuhkan usaha kognitif/fisik.

## Enam Dimensi

1. Mental demand
2. Physical demand
3. Temporal demand
4. Performance
5. Effort
6. Frustration

## Varian

- **Raw TLX**: partisipan langsung memberi skor pada tiap dimensi.
- **Weighted TLX**: partisipan membandingkan dimensi secara berpasangan, kemudian skor diberi bobot.

NASA-TLX sering digunakan bersama ukuran performa objektif seperti waktu dan error.

---

# Slide 29 - Memilih Instrumen Berdasarkan Konstruk

Instrumen bukan sekadar “formulir yang biasa dipakai”. Ia harus merepresentasikan konstruk yang ingin diukur.

| Konstruk yang Diukur | Instrumen Umum |
|---|---|
| Perceived usability | SUS |
| Pengalaman pengguna luas | UEQ |
| Beban kerja | NASA-TLX |
| Kepuasan | Likert/pertanyaan khusus, sesuai konstruk |
| Trust, emosi, atau motivasi | Skala yang divalidasi sesuai topik |
| Perilaku dan proses | Interaction logs, observasi, video |

## Kriteria Pemilihan

- Apakah instrumen mengukur aspek yang sama dengan definisi konstruk?
- Apakah sudah ada bukti reliabilitas dan validitas untuk konteks yang serupa?
- Apakah instrumen dapat diisi dalam durasi yang wajar?
- Bagaimana cara analisis data setelah instrumen digunakan?

---

# Slide 30 - Contoh Hubungan RQ-Variabel-Instrumen

## Ilustrasi RQ

“Apakah saran AI yang proaktif memengaruhi efisiensi penyelesaian email dibandingkan antarmuka tanpa saran AI?”

## Tabel Operasionalisasi

| Komponen | Rincian |
|---|---|
| Independent variable | Kehadiran saran AI: tersedia vs tidak tersedia |
| Dependent variable | Completion time, completion rate, jumlah klik |
| Subjective measure | NASA-TLX, pertanyaan trust |
| Task | Memproses 8 email ke folder prioritas |
| Instrumen/log | Log klik + timestamp, kuesioner digital |
| Analisis | Uji beda antar kondisi (lihat pertemuan 13) |

## Prinsip

Setiap variabel harus memiliki:

- definisi konseptual;
- definisi operasional;
- cara pengukuran;
- rencana analisis.

---

# Slide 31 - Pilot Study: Uji Coba Sebelum Data Utama

## Mengapa Pilot?

- Mengetahui apakah instruksi dapat dipahami.
- Mengetahui apakah task dapat diselesaikan dalam waktu yang wajar.
- Menguji skenario, urutan, dan sistem logging.
- Menemukan masalah teknis.
- Menyesuaikan tingkat kesulitan task.

## Langkah Praktis

1. Rekrut 2–5 partisipan yang mirip populasi target.
2. Jalankan protokol persis seperti studi final.
3. Catat durasi, kebingungan, error sistem, dan komentar.
4. Revisi task, instrumen, atau prosedur.
5. Jika revisi besar, lakukan pilot kedua.

## Catatan

- Data pilot biasanya tidak digabung ke data utama.
- Keputusan ini sebaiknya ditulis dalam protokol sebelum pengambilan data.

---

# Slide 32 - Komponen Study Protocol

Study protocol adalah dokumen yang menjelaskan secara rinci bagaimana studi dilaksanakan.

## Komponen Utama

| Bagian | Isi |
|---|---|
| Ringkasan penelitian | RQ, hipotesis, dan variabel utama |
| Partisipan | Kriteria inklusi/eksklusi, jumlah, rekrutmen |
| Bahan dan alat | Sistem, perangkat, kuesioner, log, rekaman |
| Lingkungan | Lokasi, pencahayaan, gangguan, perangkat |
| Prosedur | Langkah demi langkah, script moderator |
| Task dan hitungan waktu | Deskripsi task, batas waktu, urutan |
| Pengukuran | Definition success, time, error, instrumen |
| Pengelolaan data | Anonimisasi, penyimpanan, consent |
| Analisis rencana | Statistik/tematik yang akan digunakan |
| Kriteria penghentian | Kapan sesi dihentikan |

Protokol yang baik membuat **orang lain dapat mereplikasi studi** Anda.

---

# Slide 33 - Menulis Instruksi dan Skenario Partisipan

## Hal yang Harus Dihindari

- Menyebutkan hipotesis penelitian.
- Mengarahkan partisipan ke fitur tertentu.
- Memberi petunjuk jawaban.
- Menggunakan bahasa teknis yang tidak dipahami partisipan.

## Hal yang Harus Jelas

- Tujuan task.
- Batas waktu.
- Cara menyatakan selesai.
- Perlakukan jika menemui masalah.
- Data apa yang akan direkam.

## Contoh Script Moderator

```text
“Saya akan memberikan beberapa tugas. Silakan kerjakan sealami mungkin.
Tidak ada evaluasi terhadap Anda sebagai pribadi; yang dinilai adalah sistem.
Jika ada sesuatu yang tidak berfungsi, silakan lanjutkan atau ceritakan apa yang Anda pikirkan.”
```

Script yang seragam mengurangi perbedaan perlakuan antar partisipan.

---

# Slide 34 - Counterbalancing dan Pengendalian Bias

## Urutan Task dan Kondisi

Dalam within-subject design, setiap partisipan dapat mengalami lebih dari satu kondisi. Urutan harus dikontrol agar efek pembelajaran dan kelelahan tidak mengacaukan hasil.

Contoh sederhana untuk 2 kondisi:

```text
Kelompok A: Kondisi 1 → Kondisi 2
Kelompok B: Kondisi 2 → Kondisi 1
```

## Prinsip

- Gunakan **counterbalancing** atau **latin square** jika jumlah kondisi banyak.
- Beri latihan secukupnya sebelum pengukuran.
- Jangan memberi bantuan selama task yang diukur.
- Jangan mengubah instruksi di tengah studi.
- Catat semua kejadian tidak biasa sebagai data proses.

Pengendalian ini adalah penerapan langsung dari konsep validitas yang dibahas lebih lanjut pada pertemuan 14.

---

# Slide 35 - Checklist Finalisasi Instrumen dan Study Protocol

Gunakan checklist ini sebagai progress minggu ini:

```text
[ ] RQ/hypothesis tertulis jelas
[ ] Variabel dikonsep dan dioperasionalkan
[ ] Metode evaluasi dipilih (usability test/eksperimen/UX)
[ ] Task dirancang dengan kriteria sukses
[ ] Scenario ditulis untuk setiap task
[ ] Urutan task/kondisi di-counterbalance
[ ] Instrumen subjektif dipilih sesuai konstruk
[ ] Sistem logging siap diverifikasi
[ ] Informed consent dan debrief disiapkan
[ ] Kriteria partisipan ditetapkan
[ ] Pilot study telah dijalankan
[ ] Protokol direvisi dan dikunci
```

Jika semua tercentang, Anda siap memasuki **pengumpulan data awal** pada pertemuan berikutnya.

---

# Slide 36 - Kaitan dengan Pertemuan Selanjutnya

## Dari Protokol ke Data dan Kontribusi

- Pertemuan 10 akan membahas **Human-AI Interaction & Generative AI** sekaligus menjadi titik mulai **pilot study / initial data collection**.
- Data yang diperoleh dari user study akan dianalisis pada pertemuan 13.
- Batasan validitas dan etika akan diuji pada pertemuan 14.
- Interpretasi hasil menjadi kontribusi ilmiah dibahas pada pertemuan 15.

## Pesan Kunci

Rancangan evaluasi yang baik adalah fondasi dari semua bukti yang akan Anda laporkan.

> Sebuah user study yang tidak dirancang dengan jelas akan menghasilkan data yang sulit ditafsirkan, apa pun metode analisisnya.

---

# Slide 37 - Penutup

TERIMA KASIH

Pertemuan berikutnya

**Human-AI Interaction & Generative AI**