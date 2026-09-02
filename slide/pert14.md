# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer

Pertemuan 14

## Validity, Reproducibility & Research Ethics

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D

Departemen Teknik Informatika - ITS

---

# Slide 01 - Posisi Pertemuan dalam Pipeline Penelitian

## Alur Perkuliahan

```
Modern HCI Landscape
        ↓
Human-Centered Design
        ↓
Human Factors & Cognition
        ↓
Research Problem → State of the Art → Research Gap → Research Question
        ↓
Research Methodology → User Study / Experiment
        ↓
Data Analysis & Evidence  (Pertemuan 13)
        ↓
★ VALIDITY, REPRODUCIBILITY & RESEARCH ETHICS  (Pertemuan 14)
        ↓
Scientific Contribution  (Pertemuan 15)
        ↓
Final Research Paper & Defense  (Pertemuan 16)
```

---

# Slide 02 - Menghubungkan Pertemuan Sebelumnya dan Berikutnya

## Pertemuan 13: Data Analysis & Evidence

- Hasil analisis data menghasilkan **evidence** untuk menjawab research question
- Pertanyaan yang muncul: *Seberapa kuat evidence tersebut?*

## Pertemuan 14: yang sedang berlangsung

- Mengevaluasi **validitas** evidence
- Memastikan **reproducibility** penelitian
- Menerapkan **research ethics** dalam proses penelitian

## Pertemuan 15: From Results to Scientific Contribution

- Evidence yang valid dan etis menjadi fondasi untuk membangun **scientific contribution**
- Hasil penelitian + threats to validity + limitations → dikomunikasikan secara ilmiah

---

# Slide 03 - Tujuan Pembelajaran Pertemuan 14

Setelah pertemuan ini, mahasiswa diharapkan mampu:

1. Menganalisis berbagai tipe **validitas** (internal, external, construct, ecological) dalam konteks penelitian HCI
2. Mengidentifikasi **ancaman terhadap validitas** (threats to validity) yang umum muncul dalam user study dan eksperimen
3. Membedakan **reproducibility** dan **replication** serta menjelaskan perannya dalam penelitian HCI
4. Memahami prinsip **open science** dan **research transparency**
5. Menerapkan **prinsip etika penelitian** yang melibatkan partisipan manusia
6. Mengevaluasi penelitian (termasuk penelitian sendiri) dari sisi validitas dan etika

---

# Slide 04 - Research Progress Minggu Ini

## Progress yang Diharapkan

```
Results + Threats to Validity + Limitations
```

- Data analysis telah dilakukan (Pertemuan 13)
- Minggu ini: mengevaluasi **kekuatan evidence** yang diperoleh
- Mengeksplisitkan ancaman validitas dalam penelitian Anda
- Mengidentifikasi keterbatasan (limitations) penelitian

## Aktivitas: Research Critique

> Mengevaluasi **paper penelitian HCI** dari sisi validitas, reproducibility, dan etika penelitian

---

# Slide 05 - Pertanyaan Utama Pertemuan

> ## Seberapa kuat evidence yang diperoleh dan claim apa yang dapat dibuat berdasarkan study design tersebut?

- Evidence yang kuat memungkinkan claim yang kuat
- Evidence yang lemah hanya mendukung claim yang terbatas
- Setiap desain studi memiliki **trade-off** validitas

## Prinsip Kunci

```
Study Design → Evidence Strength → Claim Strength
                    ↓
         Threats to Validity & Limitations
```

---

# Slide 06 - Definisi Validitas dalam Penelitian

## Validitas = Ketepatan Inferensi

- Validitas mengacu pada sejauh mana **kesimpulan penelitian** benar dan dapat dipertanggungjawabkan
- Bukan properti tunggal — terdapat beberapa **tipe validitas** yang berbeda

## Empat Tipe Validitas Utama

| Tipe | Pertanyaan Kunci |
|---|---|
| **Internal validity** | Apakah hubungan sebab-akibat benar? |
| **External validity** | Dapatkah hasil digeneralisasi? |
| **Construct validity** | Apakah konstruk diukur dengan tepat? |
| **Ecological validity** | Apakah hasil berlaku pada konteks nyata? |

## Keterkaitan dengan Materi Sebelumnya

- Pertemuan 13: memperoleh evidence dari data
- Pertemuan 14: mengevaluasi **kualitas** evidence tersebut

---

# Slide 07 - Internal Validity: Definisi

## Internal Validity

Sejauh mana hubungan **sebab-akibat** yang diamati benar-benar disebabkan oleh variabel independen, bukan oleh variabel lain.

## Pertanyaan Kunci

> Apakah perubahan pada **dependent variable** benar-benar disebabkan oleh manipulasi **independent variable**?

## Contoh dalam HCI

- Menguji apakah **interface A** menghasilkan task completion time lebih cepat daripada **interface B**
- Internal validity terjaga jika perbedaan waktu memang disebabkan oleh desain interface, bukan oleh faktor lain (misalnya kelelahan partisipan, perbedaan instruksi, atau gangguan lingkungan)

---

# Slide 08 - Ancaman terhadap Internal Validity

## Ancaman Utama

| Ancaman | Deskripsi | Contoh dalam HCI |
|---|---|---|
| **Confounding factors** | Variabel ketiga yang tidak dikontrol memengaruhi hasil | Partisipan kelompok A lebih berpengalaman daripada kelompok B |
| **Selection bias** | Perbedaan sistematis antar kelompok sebelum perlakuan | Kelompok A didominasi pengguna expert |
| **History** | Peristiwa eksternal terjadi selama penelitian | Perubahan sistem operasi saat studi berlangsung |
| **Maturation** | Perubahan alami pada partisipan selama penelitian | Partisipan menjadi lelah atau bosan |
| **Instrumentation** | Perubahan alat ukur selama penelitian | Kalibrasi alat berubah antar sesi |

---

# Slide 09 - Contoh Confounding Factors dalam HCI

## Ilustrasi

```
Penelitian: Membandingkan efisiensi Web vs Mobile app
Kondisi: Interface berbeda + Device berbeda + Konteks berbeda
         ↓
Apakah perbedaan hasil disebabkan oleh:
- Interface? (variabel yang dimanipulasi)
- Device? (confounding)
- Konteks penggunaan? (confounding)
```

## Mengendalikan Confounding

1. **Kontrol** — membuat kondisi konstan untuk semua kelompok
2. **Randomisasi** — membagi partisipan secara acak
3. **Matching** — menyamakan karakteristik penting antar kelompok
4. **Statistical control** — memasukkan confounding sebagai kovariat dalam analisis

---

# Slide 10 - External Validity: Definisi

## External Validity

Sejauh mana hasil penelitian dapat **digeneralisasi** ke populasi, setting, waktu, dan kondisi lain.

## Pertanyaan Kunci

> Apakah hasil yang diperoleh pada partisipan, konteks, dan tugas tertentu berlaku juga untuk populasi dan situasi yang lebih luas?

## Contoh dalam HCI

- Hasil studi dengan 20 mahasiswa ilmu komputer — dapatkah digeneralisasi ke pekerja kantoran?
- Hasil studi di laboratorium — dapatkah digeneralisasi ke penggunaan di rumah atau kantor?

---

# Slide 11 - Ancaman terhadap External Validity

## Ancaman Utama

| Ancaman | Deskripsi |
|---|---|
| **Sampling bias** | Sampel tidak representatif terhadap populasi |
| **Narrow sample** | Sampel terlalu homogen (misal: hanya mahasiswa S1) |
| **Artificial setting** | Lingkungan laboratorium tidak mencerminkan penggunaan nyata |
| **Specific task** | Tugas artifisial tidak mewakili penggunaan aktual |
| **Time-bound** | Hasil mungkin berubah seiring perkembangan teknologi |

## Trade-off Internal vs External Validity

```
Internal Validity ←→ External Validity
  (kontrol tinggi)    (realisme tinggi)
```

Desain eksperimen laboratorium yang ketat sering mengorbankan generalisasi ke konteks nyata.

---

# Slide 12 - Construct Validity: Definisi

## Construct Validity

Sejauh mana **variabel yang diukur atau dimanipulasi** benar-benar merepresentasikan **konstruk teoretis** yang dimaksud.

## Pertanyaan Kunci

> Apakah alat ukur kita benar-benar mengukur apa yang ingin kita ukur?

## Contoh dalam HCI

Konstruk: **Cognitive Load**

- Operationalisasi menggunakan **NASA-TLX** — apakah skor benar-benar mencerminkan beban kognitif?
- Atau juga terpengaruh oleh faktor lain (frustrasi, motivasi)?

Konstruk: **User Experience**

- Apakah mengukur kepuasan melalui kuesioner benar-benar menangkap UX secara komprehensif?

---

# Slide 13 - Ancaman terhadap Construct Validity

## Ancaman Utama

| Ancaman | Deskripsi | Contoh |
|---|---|---|
| **Inadequate preoperational explication** | Konstruk kurang didefinisikan dengan jelas | "Usability" tanpa definisi operasional yang spesifik |
| **Mono-operation bias** | Hanya menggunakan satu metode atau satu ukuran | Hanya mengukur task completion time, tidak mengukur error |
| **Mono-method bias** | Hanya menggunakan satu tipe pengukuran (misal: hanya self-report) | Tidak ada data objektif dari log |
| **Confounding constructs** | Konstruk lain ikut terukur tanpa disadari | Skor "engagement" sebenarnya mengukur "novelty" |
| **Evaluation apprehension** | Partisipan merasa dievaluasi sehingga berperilaku tidak natural | Social desirability bias |

---

# Slide 14 - Ecological Validity: Definisi

## Ecological Validity

Sejauh mana hasil penelitian berlaku pada **kehidupan nyata sehari-hari**.

## Perbedaan dengan External Validity

| External Validity | Ecological Validity |
|---|---|
| Apakah hasil berlaku untuk populasi/conteks lain? | Apakah hasil berlaku pada situasi nyata yang alami? |
| Menekankan generalisasi | Menekankan realisme konteks dan tugas |

## Contoh dalam HCI

- Studi laboratorium tentang **voice assistant**: partisipan diminta menggunakan perintah tertentu di ruangan sunyi
- Kondisi nyata: ada kebisingan, gangguan, percakapan, multitasking
- Ecological validity rendah jika hasil tidak merepresentasikan penggunaan nyata

---

# Slide 15 - Ancaman terhadap Ecological Validity

## Ancaman dalam Penelitian HCI

| Ancaman | Deskripsi |
|---|---|
| **Artificial task** | Tugas yang tidak mencerminkan aktivitas nyata |
| **Unnatural setting** | Ruang observasi, perekaman, atau pengawasan membuat tidak alami |
| **Time constraint** | Durasi sesi dibatasi, tidak seperti penggunaan natural |
| **Observer effect** | Kehadiran peneliti mengubah perilaku partisipan |
| **Narrow context** | Mengabaikan elemen penting dari konteks penggunaan |

## Strategi Meningkatkan Ecological Validity

- **Field study** atau **in-situ study**
- **Diary study** untuk menangkap penggunaan natural
- **Contextual inquiry** di lingkungan asli
- Menggunakan **real tasks** yang relevan dengan pengguna

---

# Slide 16 - Ringkasan Tipe Validity

## Empat Tipe Utama

| Tipe | Fokus | Pertanyaan Kunci |
|---|---|---|
| **Internal** | Sebab-akibat | Apakah IV benar-benar menyebabkan perubahan DV? |
| **External** | Generalisasi | Apakah hasil berlaku untuk popilasi/konteks lain? |
| **Construct** | Pengukuran | Apakah kita mengukur apa yang ingin diukur? |
| **Ecological** | Realisme | Apakah hasil berlaku di dunia nyata? |

## Hierarki dalam Membangun Argumen

```
Internal Validity → hubungan sebab-akibat yang kuat
Construct Validity → konstruk yang diukur valid
External & Ecological Validity → relevansi hasil ke dunia nyata
```

> Validitas tidak bersifat "ada atau tidak ada" — melainkan **derajat** yang harus diargumentasikan peneliti.

---

# Slide 17 - Bias dalam Penelitian HCI

## Definisi Bias

Deviasi sistematis dari kebenaran dalam proses pengumpulan, analisis, interpretasi, atau pelaporan data.

## Kategori Bias dalam HCI

| Kategori | Deskripsi |
|---|---|
| **Sampling bias** | Sampel tidak merepresentasikan populasi target |
| **Selection bias** | Prosedur pemilihan partisipan mengarah pada kelompok tertentu |
| **Researcher bias** | Peneliti memengaruhi hasil secara sadar/tidak sadar |
| **Demand characteristics** | Partisipan menebak tujuan penelitian dan mengubah perilaku |
| **Response bias** | Partisipan memberikan jawaban yang dianggap "benar" atau "diharapkan" |
| **Acquiescence bias** | Kecenderungan setuju dengan pernyataan kuesioner |

---

# Slide 18 - Sampling Bias vs Selection Bias

## Sampling Bias

Bias yang terjadi ketika **sampel** tidak mewakili populasi target.

```
Populasi target: seluruh pengguna aplikasi
Sampel yang diambil: hanya mahasiswa S2 TI yang melek teknologi
         ↓
Hasil mungkin tidak berlaku untuk pengguna umum
```

## Selection Bias

Bias dalam **proses penugasan** partisipan ke kelompok/kondisi.

```
Partisipan yang lebih termotivasi memilih kelompok A (interface baru)
Partisipan yang kurang termotivasi masuk kelompok B (kontrol)
         ↓
Perbedaan hasil mungkin disebabkan oleh motivasi, bukan interface
```

## Mitigasi

- **Probability sampling** (random/acak) untuk mengurangi sampling bias
- **Random assignment** untuk mengurangi selection bias
- **Stratified sampling** untuk memastikan proporsi karakteristik tertentu

---

# Slide 19 - Researcher Bias

## Researcher Bias dalam HCI

Peneliti memengaruhi hasil penelitian secara sadar atau tidak sadar.

## Bentuk-bentuk Researcher Bias

| Bentuk | Deskripsi |
|---|---|
| **Confirmation bias** | Mencari/menafsirkan data yang mendukung hipotesis |
| **Experimenter expectancy** | Harapan peneliti memengaruhi perilaku partisipan |
| **Favoritism in interaction** | Memberikan perlakuan berbeda antar kelompok |
| **Selective reporting** | Melaporkan hasil yang signifikan saja |
| **Interpretation bias** | Menafsirkan data kualitatif secara subjektif |

## Mitigasi Researcher Bias

- **Double-blind study** jika memungkinkan
- **Standardized protocol** — instruksi seragam, script dibaca sama
- **Inter-rater reliability** untuk data kualitatif
- **Pre-registered analysis** untuk mengurangi selective reporting
- **Reflexivity** — mengakui posisi dan asumsi peneliti

---

# Slide 20 - Demand Characteristics

## Definisi

- Perilaku partisipan yang berubah karena mereka **menebak tujuan penelitian** dan berusaha memenuhi (atau mematahkan) dugaan tersebut
- Istilah ini muncul dari psikologi eksperimen (Martin Orne, 1962)
- Partisipan bukan penerima pasif — mereka aktif menafsirkan situasi eksperimen

## Contoh dalam HCI

- Partisipan menebak bahwa interface baru diharapkan lebih baik → memberikan penilaian lebih positif
- Partisipan mencoba "membantu" peneliti dengan memberikan hasil yang "diinginkan"
- Partisipan menjadi lebih teliti dari biasanya karena tahu sedang diamati

## Mitigasi

- **Cover story** atau tujuan penelitian yang netral
- **Blinding** — partisipan tidak tahu kondisi yang diterima
- Tidak mengungkapkan hipotesis secara eksplisit
- Natural task dan setting

---

# Slide 21 - Learning Effect

## Definisi

Perubahan kinerja partisipan karena **peningkatan keterampilan** dari pengulangan tugas, bukan karena manipulasi eksperimen.

## Konteks dalam HCI

- Partisipan mengulang tugas yang sama dengan beberapa interface
- Kinerja pada interface kedua lebih baik karena telah belajar cara menggunakan sistem (bukan karena interface lebih baik)

## Ilustrasi

```
Trial 1: User belajar interface → waktu lebih lambat
Trial 2: User sudah terbiasa → waktu lebih cepat
         ↓
Perbedaan waktu mungkin karena learning, bukan karena design
```

## Mitigasi

| Strategi | Deskripsi |
|---|---|
| **Counterbalancing** | Mengacak urutan kondisi antar partisipan |
| **Practice session** | Memberikan sesi latihan sebelum data diambil |
| **Baseline measurement** | Mengukur sebelum intervensi |
| **Latin square design** | Mengontrol urutan secara sistematis |

---

# Slide 22 - Order Effect

## Definisi

Efek urutan kondisi terhadap hasil — kinerja/respons dipengaruhi oleh **posisi** kondisi dalam urutan, bukan hanya oleh kondisi itu sendiri.

## Jenis Order Effects

| Efek | Deskripsi |
|---|---|
| **Carry-over effect** | Pengaruh kondisi sebelumnya masih terbawa ke kondisi berikutnya |
| **Practice effect** | Kondisi yang dikerjakan lebih awal lebih lambat karena belum terbiasa |
| **Fatigue effect** | Kondisi yang dikerjakan di akhir mengalami penurunan performa karena kelelahan |
| **Boredom effect** | Kejenuhan karena tugas berulang memengaruhi motivasi |

## Mitigasi: Counterbalancing

```
Partisipan 1: Interface A → Interface B
Partisipan 2: Interface B → Interface A
Partisipan 3: Interface A → Interface B
Partisipan 4: Interface B → Interface A
```

---

# Slide 23 - Novelty Effect

## Definisi

Peningkatan kinerja atau respons yang muncul karena **kebaruan** suatu teknologi, bukan karena kualitas sebenarnya.

## Konteks dalam HCI

- Interface/system baru sering menghasilkan performa atau persepsi positif hanya karena **belum familiar**
- Pengguna merasa antusias dan termotivasi sehingga memberikan effort lebih
- Setelah kebaruan hilang, kinerja/persepsi menurun

## Dampak pada Validitas

> Hasil positif yang hanya disebabkan novelty effect dapat **menyesatkan** — teknologi tampak efektif padahal sebenarnya tidak.

## Mitigasi

| Strategi | Deskripsi |
|---|---|
| **Longitudinal study** | Mengukur dalam jangka waktu lebih lama |
| **Washout period** | Memberi jeda waktu antar kondisi |
| **Multiple measurement points** | Mengukur tidak hanya di awal penggunaan |
| **Familiarization phase** | Membiarkan pengguna melalui fase kebaruan sebelum data diambil |

---

# Slide 24 - Validitas pada Studi Kualitatif

## Berbeda dengan Kuantitatif

Studi kualitatif (interview, observasi, diary study) menggunakan istilah yang berevolusi:

| Kuantitatif | Kualitatif |
|---|---|
| Internal validity | **Credibility** — seberapa dipercaya temuan |
| External validity | **Transferability** — seberapa dapat dipindahkan ke konteks lain |
| Reliability | **Dependability** — seberapa konsisten dan dapat dilacak proses |
| Objectivity | **Confirmability** — hasil berasal dari data, bukan bias peneliti |

## Strategi Validity pada Data Kualitatif

- **Triangulation**: menggabungkan sumber/metode data
- **Member checking**: memverifikasi temuan ke partisipan
- **Audit trail**: mendokumentasikan keputusan analisis
- **Rich description**: memberikan konteks mendalam
- **Reflexivity**: merefleksikan peran peneliti

---

# Slide 25 - Triangulasi

## Definisi

Menggunakan **berbagai sumber, metode, atau peneliti** untuk memperkuat validitas temuan.

## Tipe Triangulasi

![Diagram ASCII Triangulasi]

```
          DATA
     /     |     \
  Sumber  Metode  Peneliti
     \     |     /
       TEMUAN KUAT
```

| Tipe | Deskripsi |
|---|---|
| **Data triangulation** | Berbagai sumber data (wawancara + observasi + log) |
| **Method triangulation** | Berbagai metode (kuantitatif + kualitatif) |
| **Investigator triangulation** | Berbagai peneliti menginterpretasi data |
| **Theory triangulation** | Berbagai perspektif teoretis digunakan |

## Triangulasi dalam HCI

```
Performance data (log) + Self-report (kuesioner) + Perceived experience (interview)
        ↓
Menghasilkan pemahaman yang lebih kaya dan valid
```

---

# Slide 26 - Reproducibility dan Replication

## Dua Konsep Berbeda

Setiap jenis pengulangan memiliki tujuan berbeda:

| Istilah | Deskripsi |
|---|---|
| **Reproducibility** | Mendapatkan hasil yang sama dengan **data dan kode yang sama**. Berfokus pada transparansi dan kemampuan memverifikasi analisis |
| **Replication** | Studi baru dengan prosedur yang sama (atau hampir sama) untuk menguji apakah temuan dapat **diulang** pada konteks partisipan baru |
| **Reanalysis** | Menganalisis ulang data orang lain dengan pendekatan berbeda untuk menguji kekokohan hasil |

## Reproducibility bukan Hanya "Bisa Diulang"

- Membutuhkan **dokumentasi lengkap** prosedur, instrumen, data, dan analisis
- Konteks HCI bersifat kompleks — banyak faktor contextual yang memengaruhi hasil
- Studi **tidak harus** diulang untuk menghasilkan temuan yang sama persis

---

# Slide 27 - Mengapa Reproducibility Penting dalam HCI

## Landasan Dasar: Penelitian yang Baik

Temuan yang tidak bisa direproduksi atau direplikasi lemah sebagai klaim ilmiah

## Kondisi Saat Ini: "Replication Crisis"

Banyak bidang ilmu mengalami krisis replikasi (seperti psikologi) — temuan yang awalnya tampak kuat terbukti sulit diulang

## Implikasi untuk HCI

Prinsipnya tetap transparan: apakah temuan dapat diulang adalah ujian keilmuan.

| Aspek | Mengapa Penting |
|---|---|
| **Keandalan evidence** | Temuan sejati dapat muncul kembali |
| **Kejujuran ilmiah** | Klaim yang tidak dapat direplikasi dapat menyesatkan |
| **Efisiensi penelitian** | Peneliti lain tidak perlu mengulang dari nol |
| **Akuntabilitas** | Memungkinkan audit atas proses |

---

# Slide 28 - Open Science dan Research Transparency

## Definisi Open Science

Gerakan menjadikan penelitian lebih **terbuka, transparan, dan dapat diakses** — termasuk data, kode, prosedur, dan publikasi.

## Bentuk Implementasi dalam Penelitian HCI

| Praktik | Deskripsi |
|---|---|
| **Open data** | Data penelitian (anonim) dapat diakses publik |
| **Open code** | Skrip analisis data dipublikasikan |
| **Open materials** | Kuesioner, protokol, stimulus dapat diakses |
| **Pre-registration** | Mendaftarkan rencana studi sebelum data dikumpulkan |
| **Open access** | Paper dapat diakses tanpa paywall |

## Research Transparency = Transparansi Proses Penelitian

Mendokumentasikan dan membuka akses terhadap keputusan desain, alasan pemilihan metode, dan batasan penelitian — bukan hanya melaporkan hasil akhir.

---

# Slide 29 - Pre-registration dan Registered Report

## Pre-registration

- Mendokumentasikan rencana penelitian **sebelum** pengumpulan data
- Mencakup: research question, hipotesis, desain, variabel, sample size, rencana analisis
- Mengurangi **publication bias** dan **selective reporting**

## Alur Pre-registration

```
Research Question → Hipotesis → Desain → Analisis Plan
        ↓
      VERSI AKHIR DIDAFTARKAN (waktu tercatat)
        ↓
Data Collection → Data Analysis → Pelaporan
```

## Registered Report

- Paper di-review **sebelum** hasil penelitian diketahui
- Keputusan penerimaan berdasarkan pertanyaan penelitian dan metode (bukan hasil)
- Mencegah bias publikasi terhadap hasil yang signifikan saja

## Platform Pre-registration

- **OSF (Open Science Framework)**
- **AsPredicted**
- Journal/conference dengan format registered report

---

# Slide 30 - Research Ethics: Dasar

## Mengapa Etika Penting dalam HCI Research

- Penelitian HCI melibatkan **manusia** sebagai partisipan
- Manusia bukan sekadar sumber data — mereka memiliki hak dan kesejahteraan
- Teknologi yang diteliti dapat memengaruhi orang secara langsung

## Sumber Kerangka Etika dalam HCI

- Belum ada satu standar tunggal — namun banyak panduan yang serupa
- HCI biasanya mengikuti prinsip pada riset partisipan manusia
- Penelitian lintas bidang: **HCI + psikologi + sosiologi + interaksi sosial**
- Periksa apakah penelitian Anda memerlukan **ethical clearance** di institusi masing-masing

## Norma Umum dalam HCI Research

1. **Informed consent** — partisipan setuju dengan pemahaman penuh
2. **Privacy dan anonimitas** — data partisipan dilindungi
3. **Hak untuk menarik diri** — partisipan dapat berhenti kapan saja
4. **Manfaat dan tidak membahayakan** — risiko diminimalkan

---

# Slide 31 - Prinsip Etika Fundamental

## Empat Prinsip Etika yang Mendasari Penelitian dengan Partisipan

| Prinsip | Deskripsi | Implementasi |
|---|---|---|
| **Respect for persons** | Partisipan adalah agen otonom yang berhak menentukan pilihan | Informed consent, sukarela, transparansi |
| **Beneficence** | Memaksimalkan manfaat dan meminimalkan bahaya | Risiko rendah, monitoring efek negatif |
| **Justice** | Distribusi manfaat dan beban penelitian secara adil | Pemilihan partisipan yang tidak eksploitatif |
| **Integrity** | Kejujuran dan tanpa penipuan pada partisipan | Klarifikasi, tidak ada kebohongan |

## Prinsip Tambahan dalam HCI

- **Kesejahteraan partisipan** — termasuk kesejahteraan psikologis saat berinteraksi dengan teknologi
- **Privasi digital** — data perilaku dan data pribadi partisipan
- **Penggunaan teknologi yang bertanggung jawab**

---

# Slide 32 - Informed Consent

## Definisi

Proses memberikan informasi lengkap kepada partisipan dan mendapatkan **persetujuan sukarela** sebelum penelitian dimulai.

## Informasi yang Wajib Diberikan

1. **Tujuan penelitian** dan prosedur yang akan dilakukan
2. **Durasi** dan tempat penelitian
3. **Risiko dan manfaat** yang mungkin timbul
4. **Hak untuk menolak atau menarik diri** kapan saja tanpa sanksi
5. **Cara data akan digunakan dan dilindungi**
6. **Kontak peneliti** untuk pertanyaan

## Elemen Kunci

| Elemen | Deskripsi |
|---|---|
| **Kesukarelaan** | Tidak ada paksaan atau imbalan berlebihan |
| **Understanding** | Informasi disampaikan dengan bahasa yang dipahami |
| **Capacity** | Partisipan mampu mengambil keputusan |
| **Documentation** | Persetujuan didokumentasikan (form/suara) |
| **Ongoing consent** | Persetujuan dievaluasi ulang selama penelitian |

---

# Slide 33 - Persetujuan untuk Studi HCI: Contoh

## Format Sederhana

```
INFORMED CONSENT

Saya memahami bahwa:
1. Penelitian ini bertujuan menguji interface sistem pencarian dengan AI.
2. Saya akan diminta menyelesaikan 8 tugas pencarian (± 45 menit).
3. Penggunaan layar dan klik saya akan direkam.
4. Data saya akan dianonimkan dan disimpan aman.
5. Saya dapat berhenti kapan saja tanpa konsekuensi apa pun.

□ Saya setuju untuk berpartisipasi.

Nama Tanda Tangan: ____________
Tanggal: ____________
```

## Jenis Persetujuan

| Jenis | Deskripsi |
|---|---|
| **Kontrak (signed)** | Form tertulis ditandatangani |
| **Hak untuk menolak** | menolak tanpa alasan |
| **Opt-in** | Aktif mendaftarkan diri |
| **Opt-out** | Dianggap ikut kecuali menyatakan menolak |
| **Verbal** | Persetujuan lisan yang tercatat |

## Imbalan Partisipan

- Kompensasi wajar yang tidak bersifat memaksa
- Boleh diberikan untuk menghargai waktu dan tenaga partisipan
- Hindari imbalan yang membuat partisipan merasa tidak bebas

---

# Slide 34 - Privacy dan Perlindungan Data

## Privacy Research dalam HCI

- Data pengguna sangat sensitif: **perilaku digital, lokasi, komunikasi, kesehatan**
- Melindungi data sama dengan menghormati privasi partisipan

## Jenis Data dalam Penelitian HCI

| Jenis | Contoh | Risiko |
|---|---|---|
| **Data identitas** | Nama, email, alamat | Identifikasi langsung |
| **Data perilaku** | Log klik, waktu tugas | Profiling |
| **Data interaksi** | Chat dengan AI, voice | Kebocoran informasi pribadi |
| **Data kesehatan** | Detak jantung, pola tidur | Diskriminasi asuransi/dll |

## Dampak yang Diperhatikan

Pelanggaran privasi dapat menimbulkan dampak bagi partisipan. Di banyak yurisdiksi, ada **kewajiban hukum** untuk melindungi data pribadi (contoh: GDPR, UU Perlindungan Data Pribadi di Indonesia).

---

# Slide 35 - Strategi Privasi dan Anonimisasi

## Strategi yang Diterapkan pada Data Partisipan

| Strategi | Deskripsi | Contoh |
|---|---|---|
| **Anonimisasi** | Menghapus data yang dapat mengidentifikasi partisipan | Tidak menyimpan nama, hanya ID |
| **Pseudonimisasi** | Mengganti identitas dengan kode | Partisipan 01, 02, ... |
| **Agregasi** | Hanya melaporkan statistik agregat, bukan data individual | Rata-rata, standar deviasi |
| **Access control** | Membatasi siapa yang dapat mengakses data | Data hanya di tim peneliti |
| **Data minimization** | Mengumpulkan data seminimal mungkin | Tidak mengumpulkan data yang tidak perlu |

## Menyiapkan Data untuk Open Science

Seimbangkan transparansi dan perlindungan:

```
Privacy Protection + Data Usefulness
        ↓
Data anonim dengan metadata lengkap
```

## Kasus Kualitatif yang Memerlukan Perhatian

- Kutipan verbatim dari wawancara dapat mengungkap identitas narasumber
- Gunakan generalisasi yang hati-hati, misal: *"Pengguna berusia 65 tahun..."*

---

# Slide 36 - Etika Penelitian yang Melibatkan AI

## Tantangan Kekinian dalam HCI Research

Pertemuan 10-12 telah membahas **Human-AI Interaction**, **responsible AI**, dan **AI ethics**. Tema lebih lanjut mencakup:

## Isu Etika yang Muncul

- **Transparansi**: Apakah partisipan/sistem yang diteliti berbasis AI? Apakah tahu sedang berinteraksi dengan AI/chatbot?
- **Konsen atas data**: Apakah data interaksi dengan model AI digunakan untuk melatih ulang model tanpa izin?
- **Efek pada partisipan**: Apakah partisipan mengalami kecemasan, frustrasi, atau ketergantungan?
- **Kelekatan emosional**: Studi tentang AI companion dapat menimbulkan implikasi psikologis
- **Penggunaan AI dalam analisis data**: apakah transparan dan dapat dipertanggungjawabkan?

## Prinsip AI-Assisted Research Ethics

- Menggunakan model/layanan AI untuk analisis data harus **dinyatakan secara eksplisit**
- Jangan memasukkan data partisipan yang identitasnya jelas ke alat AI publik tanpa persetujuan
- Mahasiswa wajib memahami bahwa **AI adalah alat bantu, bukan pengganti tanggung jawab manusia**

---

# Slide 37 - Research Ethics dalam Publikasi

## Bidang yang Terkadang Terlewat tapi Krusial

Selain etika saat mengumpulkan data, terdapat etika dalam proses publikasi:

| Pelanggaran | Deskripsi |
|---|---|
| **Plagiarisme** | Mengambil tulisan/ide orang lain tanpa atribusi |
| **Self-plagiarism** | Menggunakan ulang materi milik sendiri secara berlebihan tanpa sitasi |
| **Fabrikasi** | Membuat data yang tidak pernah ada |
| **Falsifikasi** | Memanipulasi data agar sesuai hipotesis |
| **Selective reporting** | Hanya melaporkan hasil yang mendukung hipotesis |
| **Duplicate submission** | Mengirim paper yang sama ke lebih dari satu venue |

## Prinsip Penulisan Etis

- **Transparansi** terhadap proses dan data
- **Kepengarangan** (authorship) yang adil — semua kontributor tercantum
- **Rujukan yang akurat** — tidak mengutip tanpa membaca
- **Memperoleh izin reproduksi** jika menggunakan materi berhak cipta

---

# Slide 38 - Menulis Bagian Threats to Validity dan Limitations

## Struktur Bagian Limitations dalam Paper

Bagian ini adalah bagian dari **refleksi kritis** terhadap hasil penelitian. Tidak perlu bersikap menghindar atau berlebihan — cukup jujur dan terukur.

## Kerangka Penulisan yang Berguna

| Aspek | Pertanyaan yang Dijawab |
|---|---|
| **Participant-related** | Siapa partisipan? Apakah sampel homogen? |
| **Setting-related** | Di mana studi dilakukan, laboratorium vs lapangan? |
| **Task-related** | Apakah tugas mencerminkan penggunaan nyata? |
| **Measure-related** | Alat ukur yang dipakai valid dan andal? |
| **Analysis-related** | Asumsi statistik/kualitatif terpenuhi? |
| **Generalizability** | Apa batasan generalisasi temuan? |

> "The results of this study should be interpreted with caution because..." — tanpa penjelasan tidak membantu. Yang penting adalah **penjelasan mengapa dan bagaimana hal itu memengaruhi interpretasi**.

---

# Slide 39 - Menerapkan Validity Assessment untuk Penelitian Anda

## Workflow Mengevaluasi Penelitian Anda Sendiri

```
Step 1: Identifikasi tipe studi (eksperimen/kualitatif/mixed)
        ↓
Step 2: Tanyakan tiap tipe validitas:
        - Internal: apakah ada confounding, selection bias?
        - External: apakah sampel representatif?
        - Construct: apakah alat ukur mengukur konstruk?
        - Ecological: apakah setting/task realistis?
        ↓
Step 3: Identifikasi efek yang mungkin muncul:
        learning effect? order effect? novelty effect?
        demand characteristics? researcher bias?
        ↓
Step 4: Dokumentasikan sebagai Threats to Validity
        ↓
Step 5: Pertimbangkan langkah mitigasi yang mungkin atau di masa depan
```

## Pertanyaan Kunci

- Seberapa besar pengaruh ancaman tersebut terhadap evidence?
- Apakah ada alternatif penjelasan yang lebih masuk akal?
- Judul, klaim dan interpretasi umum apa yang tetap valid meskipun ada keterbatasan?

---

# Slide 40 - Penutup dan Aktivitas Tindak Lanjut

## Pesan Utama Pertemuan 14

1. **Evidence** hanya sekuat validitas studi yang menghasilkannya
2. **Threats to validity** bukan kegagalan penelitian — justru bagian yang harus dilaporkan dengan jujur
3. **Reproducibility dan transparansi** memperkuat kontribusi ilmiah
4. **Etika** adalah fondasi penelitian HCI dengan partisipan manusia

## Aktivitas setelah pertemuan ini

- **Research critique**: evaluasi paper dari sisi validitas, bias, dan etika
- Periksa kembali **hasil penelitian Anda** dan identifikasi threats to validity
- Dokumentasikan **limitations** untuk paper Anda

## Menuju Pertemuan 15

> Hasil yang valid akan diubah menjadi **scientific contribution**

---

# Slide 41 - TERIMA KASIH

Pertemuan berikutnya

**From Results to Scientific Contribution**

---