# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer
Pertemuan 05

## Literature Review & Critical Paper Reading

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D
Departemen Teknik Informatika - ITS

---

# Slide 01 - Posisi Pertemuan 05 dalam Alur Perkuliahan

## Dari Pemahaman Penelitian Menuju Peta Literatur

Pada pertemuan sebelumnya (Pertemuan 04), kita telah mempelajari anatomi paper penelitian HCI—mulai dari research topic, problem statement, state of the art, research gap, research question, hingga research contribution. Pertemuan 05 kini membawa kita melangkah lebih jauh:

**Sebelumnya (Pertemuan 04)** → *Understanding HCI Research*: bagaimana membedakan komponen-komponen penting dalam sebuah paper penelitian.

**Saat ini (Pertemuan 05)** → *Literature Review & Critical Paper Reading*: bagaimana mencari, memetakan, mensintesis, dan mengevaluasi literatur secara kritis untuk menemukan research gap dan memposisikan related work.

**Berikutnya (Pertemuan 06)** → *Quantitative HCI Research*: bagaimana merancang penelitian kuantitatif setelah problem dan gap ditemukan.

> **Alur penelitian Anda saat ini:** Candidate Problem (Pertemuan 3) → Initial Literature (Pertemuan 4) → **Literature Map + Research Gap (Pertemuan 5)** → RQ & Variables (Pertemuan 6)

---

# Slide 02 - Capaian Pembelajaran Pertemuan 05

## Yang Akan Anda Kuasai

Setelah menyelesaikan pertemuan ini, Anda diharapkan mampu:

1. **Menyusun strategi pencarian literatur** yang sistematis menggunakan keyword formulation dan academic databases (terutama Scopus dan ACM Digital Library)
2. **Melakukan backward dan forward snowballing** untuk memperluas cakupan literatur secara terarah
3. **Menerapkan inclusion/exclusion criteria** untuk menyaring paper yang relevan
4. **Membuat literature map** yang memvisualisasikan hubungan antar penelitian
5. **Melakukan research synthesis** untuk membandingkan metode dan temuan antar paper
6. **Membaca paper secara kritis**—bukan sekadar meringkas—dengan mengidentifikasi limitations dan research gap
7. **Memosisikan related work** dalam kerangka penelitian Anda

---

# Slide 03 - Mengapa Literature Review Menjadi Kritis dalam Penelitian HCI?

## Bukan Sekadar "Mengumpulkan Paper"

Literature review dalam penelitian HCI berfungsi sebagai fondasi ilmiah, bukan sekadar daftar referensi. Tanpa literature review yang baik, penelitian Anda berisiko:

| Masalah | Konsekuensi |
|---|---|
| Tidak memahami state of the art | Klaim "baru" yang sebenarnya sudah pernah diteliti |
| Research gap tidak jelas | RQ tidak terarah dan kontribusi lemah |
| Metode tidak tepat | Hasil tidak dapat dibandingkan dengan penelitian sebelumnya |
| Related work tidak terposisikan | Paper ditolak reviewer karena tidak menunjukkan kebaruan |

## Empat Fungsi Utama Literature Review

1. **Memetakan** lanskap penelitian yang sudah ada
2. **Mengidentifikasi** gap yang belum dijawab
3. **Meletakkan fondasi** untuk research question dan metodologi
4. **Memposisikan** kontribusi penelitian Anda dalam percakapan ilmiah yang lebih luas

---

# Slide 04 - Alur Kerja Literature Review: Dari Pertanyaan ke Peta

## Workflow Sistematis

Literature review yang baik mengikuti alur yang dapat diulang (*replicable*) dan transparan. Berikut adalah alur yang akan kita pelajari:

```text
Tentukan topik & cakupan
        ↓
Formulasikan keyword (termasuk sinonim & variasi)
        ↓
Cari di academic databases (Scopus, ACM DL, dll.)
        ↓
Terapkan inclusion/exclusion criteria
        ↓
Lakukan backward snowballing
        ↓
Lakukan forward snowballing
        ↓
Susun literature map (visualisasi & klasterisasi)
        ↓
Lakukan critical reading & research synthesis
        ↓
Identifikasi research gap
        ↓
Posisikan related work dalam paper Anda
```

---

# Slide 05 - Literature Search Strategy: Prinsip Dasar

## Sebelum Menekan Tombol "Search"

Strategi pencarian literatur dimulai jauh sebelum Anda membuka database. Anda perlu:

### 1. Tentukan Pertanyaan Pemandu
- Topik apa yang ingin saya pahami?
- Aspek interaksi apa yang menjadi fokus?
- Metode atau teknologi apa yang relevan?

### 2. Tentukan Batasan Cakupan
- Tahun publikasi (misal: 5-10 tahun terakhir)
- Venue (CHI, UIST, CSCW, IUI, dll.)
- Jenis paper (journal, conference, workshop)
- Bahasa (umumnya Inggris)

### 3. Dokumentasikan Proses
- Simpan keyword yang digunakan
- Catat jumlah hasil pencarian
- Catat tanggal pencarian
- Catat kriteria yang diterapkan

> **Prinsip utama:** pencarian harus *transparan dan dapat direplikasi* seperti halnya metode eksperimen.

---

# Slide 06 - Keyword Formulation: Dari Gagasan ke Istilah Pencarian

## Teknik Menyusun Keyword yang Efektif

Satu keyword tidak pernah cukup. Peneliti HCI menggunakan kombinasi istilah yang saling terkait.

### Langkah-langkah Formulasi Keyword

1. **Identifikasi konsep inti** dari topik Anda (misal: AI, trust, decision making)
2. **Cari sinonim dan variasi istilah** (misal: trust, reliance, appropriate trust)
3. **Pertimbangkan istilah teknis** (misal: LLM, explainable AI, intelligent user interface)
4. **Pertimbangkan level abstraksi** (misal: trust, trust in automation, trust in AI systems)
5. **Kombinasikan dengan operator** AND / OR / NOT

### Contoh Keyword untuk Topik "Human-AI Interaction"

| Kombinasi | Tujuan |
|---|---|
| "human-AI interaction" AND "trust" | Fokus pada trust dalam interaksi manusia-AI |
| "AI" AND "decision making" AND "user study" | Penelitian empiris tentang AI dan pengambilan keputusan |
| "generative AI" OR "LLM" AND "user experience" | Cakupan lebih luas untuk AI generatif dan UX |
| "explainable AI" AND "reliance" NOT "model development" | Menghindari paper teknis machine learning |

---

# Slide 07 - Academic Databases untuk HCI Research

## Sumber Utama Literatur HCI

Penelitian HCI tersebar di berbagai database dan digital library. Anda perlu memahami karakteristik masing-masing:

| Database | Fokus Utama | Kekuatan untuk HCI |
|---|---|---|
| **Scopus** | Multi-disiplin, abstract & citation database | Cakupan luas, tools analisis kutipan, inclusion/exclusion melalui filtering |
| **ACM Digital Library** | Publikasi ACM (CHI, UIST, CSCW, IUI, DIS, dll.) | Sumber utama venue HCI terkemuka |
| **IEEE Xplore** | Engineering, computing | Interaksi multimodal, HRI, pervasive computing |
| **ScienceDirect** | Jurnal Elsevier | Jurnal HCI seperti International Journal of Human-Computer Studies |
| **SpringerLink** | Buku & jurnal Springer | Jurnal seperti Personal and Ubiquitous Computing |
| **Google Scholar** | Multi-disiplin | Cakupan luas untuk forward citation, namun kurang presisi |

> **Rekomendasi RPS:** gunakan **Scopus** dan **ACM Digital Library** sebagai database utama. Google Scholar dapat membantu menemukan paper tambahan dan melihat siapa yang mengutip sebuah paper.

---

# Slide 08 - Scopus: Alat Utama Pencarian Literatur

## Mengapa Scopus?

Scopus adalah *abstract and citation database* yang sangat berguna untuk literature review karena:

### Fitur-Fitur Utama Scopus untuk Literature Review

1. **Boolean search** yang presisi pada judul, abstrak, dan metadata
2. **Filter** berdasarkan tahun, subjek area, dokumen type, bahasa, dan akses
3. **Citation analysis** untuk melihat dampak paper dan tren penelitian
4. **Author search** untuk menemukan peneliti kunci di bidang tertentu
5. **Export** metadata ke format CSV/BibTeX untuk literature mapping

### Strategi Pencarian di Scopus

```text
TITLE-ABS-KEY ( "human-ai interaction" AND "trust" )
AND PUBYEAR > 2018
AND SUBJAREA(COMP) OR SUBJAREA(PSYC)
```

### Langkah Praktis

1. Gunakan **TITLE-ABS-KEY** untuk mencari di judul, abstrak, dan keyword
2. Gunakan **PUBYEAR** untuk membatasi tahun
3. Gunakan **SUBJAREA** untuk memfilter ke disiplin Computer Science dan Psikologi

---

# Slide 09 - ACM Digital Library: Mendalami Venue HCI

## Mengapa ACM Digital Library Penting?

ACM Digital Library (ACM DL) adalah rumah bagi *conference proceedings* dan jurnal HCI paling bergengsi:

| Venue | Kepanjangan | Fokus |
|---|---|---|
| **CHI** | Conference on Human Factors in Computing Systems | HCI umum, flag conference |
| **UIST** | User Interface Software and Technology | Teknologi interface |
| **CSCW** | Computer-Supported Cooperative Work | Kolaborasi dan sosial |
| **IUI** | Intelligent User Interfaces | AI dan interface cerdas |
| **DIS** | Designing Interactive Systems | Desain sistem interaktif |
| **MobileHCI** | Mobile and Ubiquitous Computing | Interaksi mobile |

### Tips Pencarian di ACM DL

1. Gunakan **Advanced Search** dengan field Title, Abstract, dan Author/Editor
2. Biasanya hasil lebih sedikit namun lebih relevan dibanding Scopus
3. Perhatikan **ACM CCS Concepts** pada paper untuk menemukan paper serupa

> **Latihan:** bandingkan hasil pencarian dengan keyword yang sama di Scopus dan ACM DL. Perhatikan perbedaan jumlah dan relevansi hasil.

---

# Slide 10 - Backward Snowballing: Menelusuri Riwayat Kutipan

## Melihat ke Belakang: Daftar Referensi

**Backward snowballing** adalah teknik menemukan literatur tambahan dengan memeriksa daftar referensi dari paper yang sudah Anda temukan.

### Cara Kerja

```text
Paper utama A (ditemukan via database)
        ↓
Periksa daftar referensi paper A
        ↓
Temukan paper B, C, D yang dikutip A
        ↓
Periksa apakah B/C/D relevan dengan topik Anda
        ↓
Jika relevan, baca & tambahkan ke koleksi
        ↓
Lakukan berulang pada B/C/D
```

### Kelebihan & Risiko

| Kelebihan | Risiko |
|---|---|
| Menemukan literatur fondasi yang lebih tua | Referensi bisa usang |
| Melihat asal-usul konsep dan metode | Tidak menemukan penelitian terbaru |
| Sangat efektif untuk topik niche | Menghabiskan waktu jika tidak disaring |

> **Praktik terbaik:** gunakan backward snowballing untuk memahami *fondasi* penelitian dan melacak definisi konsep hingga sumber awalnya.

---

# Slide 11 - Forward Snowballing: Menelusuri Penelitian yang Mengutip

## Melihat ke Depan: Siapa yang Mengutip Paper Ini?

**Forward snowballing** (atau citation chasing) adalah teknik menemukan literatur dengan melihat paper *lain* yang mengutip paper yang sudah Anda temukan.

### Tools untuk Forward Citation

| Tool | Keterangan |
|---|---|
| **Scopus** | Fitur "Cited by" pada setiap paper |
| **Google Scholar** | Link "Cited by" pada hasil pencarian |
| **ACM DL** | Halaman paper menampilkan "cited by" |

### Alur Kerja

```text
Paper utama A (ditemukan via database)
        ↓
Lihat daftar paper yang MENGUTIP A
        ↓
Temukan paper E, F, G yang mengutip A
        ↓
Terapkan inclusion/exclusion criteria
        ↓
Jika relevan, baca & tambahkan ke koleksi
        ↓
Lakukan berulang pada E/F/G
```

### Manfaat

1. Menemukan **perkembangan terbaru** dari sebuah penelitian
2. Menemukan **penelitian lanjutan** yang mengkritik atau memperluas paper awal
3. Mengikuti **perkembangan state of the art** hingga saat ini

---

# Slide 12 - Contoh Komprehensif: Snowballing dalam Praktik

## Studi Kasus: Penelitian tentang "Trust in Generative AI"

Anggap Anda menemukan paper utama berikut:

> **Paper P**: "Exploring User Trust in Generative AI Assistants" (diterbitkan tahun 2023 di CHI Extended Abstracts)

### Backward Snowballing dari Paper P

Paper P mengutip:
- Paper X (2018) tentang trust in automation — mengutip untuk mendefinisikan konsep dasar trust
- Paper Y (2020) tentang explanation in AI — mengutip untuk diskusi explainability
- Paper Z (2015) tentang trust scale — mengutip untuk instrumen pengukuran

→ Anda menemukan 3 paper utama yang menjadi fondasi penelitian P.

### Forward Snowballing dari Paper P

Anda menelusuri paper-paper yang mengutip P:
- Paper Q (2024) memperluas studi ke domain pendidikan — sangat relevan!
- Paper R (2024) mengkritik metodologi P dan mengusulkan pendekatan baru — kritis untuk gap
- Paper S (2023) hanya menyebut P sekilas — kurang relevan, dapat dilewati

→ Anda menemukan 2 paper penting yang memperbarui state of the art setelah P.

### Hasil

Dari 1 paper awal, Anda memperoleh total **6 paper tambahan** yang saling terhubung—fondasi untuk literature map Anda.

---

# Slide 13 - Inclusion/Exclusion Criteria: Menyaring Literatur yang Tepat

## Mengapa Kriteria Ini Penting?

Tanpa kriteria yang jelas, koleksi literatur Anda akan menjadi tidak fokus, terlalu besar, atau dipenuhi paper yang tidak benar-benar relevan. Kriteria ini juga membuat proses review Anda *transparan dan dapat dipertanggungjawabkan*.

### Contoh Kriteria untuk Penelitian "Human-AI Interaction"

| Inclusion (disertakan) | Exclusion (dikecualikan) |
|---|---|
| Paper membahas interaksi manusia dengan AI/LLM | Paper tentang AI tanpa perspektif pengguna/UX |
| Paper melibatkan user study atau evaluasi empiris | Paper murni teknis/teoritis tanpa evaluasi pengguna |
| Diterbitkan pada venue terindeks Scopus | Non-peer-reviewed, blog, laporan teknis tanpa review |
| Tahun 2020-2025 (mengikuti perkembangan cepat GenAI) | Paper sangat lama yang metode/AI-nya sudah usang |
| Mengukur trust, reliance, atau user experience | Paper membahas AI ethics tanpa data empiris |
| Bahasa Inggris | Bahasa lain |

### Panduan Penyaringan

1. **Tahap 1 (screening):** saring berdasarkan judul dan abstrak
2. **Tahap 2 (eligibility):** baca full text untuk memutuskan masuk/tidaknya

---

# Slide 14 - Literature Mapping: Memvisualisasikan Lanskap Penelitian

## Apa Itu Literature Map?

Literature map adalah visualisasi yang menunjukkan bagaimana paper-paper dalam koleksi Anda berhubungan satu sama lain. Peta ini membantu Anda melihat:

- **Kelompok (cluster)** penelitian yang saling terkait
- **Garis evolusi** dari penelitian awal ke penelitian terbaru
- **Area kosong** yang dapat menjadi research gap
- **Perdebatan atau kontradiksi** antar penelitian

### Jenis-Jenis Literature Map

| Jenis | Deskripsi | Ketika Digunakan |
|---|---|---|
| **Tematik** | Dikelompokkan berdasarkan topik/tema | Ketika mengeksplorasi lanskap yang luas |
| **Kronologis** | Dikelompokkan berdasarkan urutan waktu | Ketika menelusuri evolusi konsep/teknologi |
| **Metodologis** | Dikelompokkan berdasarkan metode | Ketika membandingkan pendekatan penelitian |
| **Kutipan** | Berdasarkan jaringan sitasi | Ketika memahami pengaruh antar paper |

---

# Slide 15 - Literature Map: Contoh Tematik

## Ilustrasi: Peta Literatur "Trust dalam Human-AI Interaction"

```text
┌─────────────────────────────────────────────────────────────────┐
│                TRUST IN HUMAN-AI INTERACTION                      │
├─────────────────────────────────────────────────────────────────┤
│                                                                   │
│  [KLUSTER A]                 [KLUSTER B]                        │
│  Trust in Automation         Explainable AI & Trust             │
│  • Lee & See (2004)          • Ribeiro et al. (2016)            │
│  • Muir (1994)               • Zhang et al. (2020)              │
│  • Hoff & Bashir (2015)      • Bussone et al. (2015)            │
│         │                            │                           │
│         └──────────────┬─────────────┘                           │
│                        │                                         │
│                        ▼                                         │
│             [KLUSTER C] *fusion area*                           │
│        • Yin et al. (2019) — AI explanations & user trust        │
│        • Ehsan et al. (2021) — Explainable AI in practice       │
│        • Bansal et al. (2021) — Human-AI decision making         │
│                                                                   │
│  [KLUSTER D]                    [KLUSTER E]                     │
│  Generative AI & Trust         Trust Measurement                │
│  • Evaluasi LLM interfaces     • Trust Scale                      │
│  • ChatGPT user studies        • Behavioral measures              │
│                                                                   │
└─────────────────────────────────────────────────────────────────┘
        ▲                                                           │
        │  Area yang masih belum banyak dieksplorasi:               │
        │  Trust dynamics in LONG-TERM GenAI use                    │
        └───────────────────────────────────────────────────────────┘
```

> **Catatan:** setiap kluster dapat dibedakan dengan warna berbeda saat presentasi. Garis pada peta menunjukkan hubungan sitasi atau konsep.

---

# Slide 16 - Literature Map: Contoh Kronologis

## Melihat Evolusi Penelitian

Peta kronologis membantu Anda menjelaskan bagaimana penelitian di bidang Anda berkembang.

```text
2015                    2020                      2025
  │                       │                         │
  ▼                       ▼                         ▼

[Trust dalam       [Human-AI            [Generative AI
 automation]  ───► [Interaction]  ───► [ & Trust]
 • Model trust      • AI sebagai      • LLM-based
   pada sistem        partner vs         assistants
   otomatis           tool              • Halusinasi
 • Kalibrasi        • XAI & trust       • Over-reliance
   trust saat         • User study      • Trust repair
   kegagalan          pada AI           • Longitudinal
   sistem             decision-           studies?
                       making            ← GAP: sebagian
                                            besar masih
                                            cross-sectional
```

### Pertanyaan yang Dapat Dijawab dari Map Kronologis

1. Kapan konsep/topik mulai muncul dan berkembang?
2. Apa trigger yang menyebabkan lompatan penelitian?
3. Metode apa yang mendominasi pada periode tertentu?
4. Mengapa terjadi pergeseran fokus?

---

# Slide 17 - Langkah-Langkah Membangun Literature Map Anda

## Workflow Praktis

### Langkah 1: Kumpulkan Metadata Paper
Export dari Scopus ke format CSV/BibTeX, termasuk judul, abstrak, tahun, keyword, dan reference.

### Langkah 2: Klasifikasikan Paper
Baca abstrak paper, lalu berikan label tematik untuk setiap paper (contoh: "trust measurement", "XAI", "genAI evaluation").

### Langkah 3: Identifikasi Hubungan
Untuk setiap paper, catat:
- Paper mana yang menjadi *pondasi konseptualnya*
- Paper mana yang dikutipnya untuk metode
- Paper mana yang menjadi *pembanding* atau *yang mengkritik*

### Langkah 4: Gambar Peta
Gunakan tools seperti Miro, FigJam, draw.io, atau kertas. Buat node untuk setiap klaster, lalu hubungkan dengan garis.

### Langkah 5: Identifikasi Area Kosong
Lihat area pada peta yang tidak memiliki klaster atau paper—area inilah yang berpotensi menjadi research gap.

### Langkah 6: Iterasi
Perbarui peta setiap kali menemukan paper baru.

---

# Slide 18 - Research Synthesis: Dari Sekadar Review ke Sintesis

## Apa Perbedaan Review dan Synthesis?

| Review/Survey | Research Synthesis |
|---|---|
| Meringkas paper satu per satu | Menggabungkan temuan antar paper |
| "Paper A menemukan X, Paper B menemukan Y" | "Beberapa paper menunjukkan X, namun paper B yang menggunakan metode berbeda menemukan Y, yang menunjukkan bahwa konteks berperan penting" |
| Deskriptif | Analitis |
| Berhenti pada rangkuman | Bergerak menuju pemahaman baru tentang lanskap penelitian |

### Pertanyaan Sintesis yang Harus Diajukan

1. **Apa yang sudah terbukti konsisten** di berbagai paper?
2. **Apa temuan yang saling bertentangan** antar paper?
3. **Apa yang masih belum diukur** atau belum dieksplorasi?
4. **Metode apa yang menghasilkan temuan berbeda** untuk pertanyaan yang sama?

---

# Slide 19 - Research Synthesis: Membandingkan Metode dan Temuan

## Matriks Sintesis: Membandingkan Paper secara Sistematis

Salah satu alat paling efektif untuk research synthesis adalah **matriks sintesis** (synthesis matrix). Buat tabel yang membandingkan paper berdasarkan dimensi penting:

| Paper | Metode | Partisipan | Konteks | Temuan Utama | Limitasi |
|---|---|---|---|---|---|
| Zhang (2020) | Kontrolled lab experiment | 40 mahasiswa | AI recommendation | Trust dipengaruhi oleh explainability | Setting tidak natural |
| Ehsan (2021) | Qualitative interview | 18 profesional | AI dalam pekerjaan | Explainability penting namun tidak cukup untuk trust | Sampel kecil |
| Bansal (2021) | Online experiment | 200 crowdworkers | AI decision support | Over-reliance terjadi ketika AI sering benar | Task sederhana |
| Palanica (2023) | Survey | 150 pengguna ChatGPT | Penggunaan harian | Trust bervariasi dengan familiarity | Self-report |

### Manfaat Matriks Sintesis

- Melihat **pola** temuan antar paper
- Menemukan **kontradiksi** yang menunjukkan peluang riset
- Membandingkan **kekuatan metode** antar paper
- Menyediakan bahan untuk penulisan related work yang sintetik

---

# Slide 20 - Level Kedalaman: Ringkasan vs Critical Review

## Dua Cara Membaca Paper yang Berbeda

### Ringkasan (Summary) — Reader
- Menyebutkan topik paper
- Menyebutkan metode yang digunakan
- Menyebutkan hasil utama
- Berhenti pada "paper ini melakukan X dan menemukan Y"

### Critical Review — Critical Reader
- Menilai **apakah research problem penting dan jelas**
- Memeriksa **apakah metode benar-benar menjawab RQ**
- Mengevaluasi **apakah bukti mendukung klaim**
- Mengidentifikasi **keterbatasan** dan **ancaman validitas**
- Menanyakan **apa yang bisa dilakukan berbeda**

> Dalam critical paper reading, Anda bukan konsumen pasif informasi. Anda adalah *evaluator* yang menilai kekuatan dan kelemahan argumen ilmiah.

---

# Slide 21 - Framework Critical Paper Reading: Pertanyaan Kunci

## Tujuh Pertanyaan Kritis untuk Setiap Paper

Gunakan kerangka ini saat membaca setiap paper:

### 1. Problem
- Apa research problem yang diangkat?
- Mengapa masalah ini penting?

### 2. State of the Art & Gap
- Apa yang sudah diketahui sebelumnya?
- Apa gap yang diklaim penulis?

### 3. Research Question
- Apa RQ/hypothesis-nya?
- Apakah RQ sejalan dengan problem?

### 4. Methods
- Metode apa yang dipilih?
- Apakah metode sesuai dengan RQ?
- Bagaimana partisipan dipilih? Berapa jumlahnya?

### 5. Results
- Temuan apa yang diperoleh?
- Bagaimana data dianalisis?

### 6. Evidence & Claim
- Apakah evidence cukup kuat untuk mendukung klaim?
- Apakah interpretasi penulis melebihi bukti yang ada?

### 7. Limitations & Future Work
- Apa threat to validity?
- Apa pertanyaan lanjutan yang belum terjawab?
- Apa limitasi yang penulis akui, dan apa yang tidak diakui?

---

# Slide 22 - Critical Reading Tahap 1: Membaca Cepat dan Membaca Dalam

## Two-Pass Reading Strategy

Untuk paper yang panjang, gunakan dua tahap membaca:

### Pass 1: Scan (10-15 menit)
1. Baca **judul, abstrak, dan keyword**
2. Lihat struktur section headings (Introduction, Method, Results, Discussion)
3. Baca **gambar dan tabel** utama
4. Baca **kesimpulan** dan **highlight klaim utama**

Hasilnya: Anda dapat memutuskan apakah paper benar-benar relevan dengan topik Anda.

### Pass 2: Deep Reading (1-2 jam)

| Bagian | Pertanyaan yang Dibawa |
|---|---|
| Introduction | Mengapa problem penting? Apa claim utama? |
| Related Work | Bagaimana penulis memposisikan diri? Apa yang dikatakan belum ada? |
| Method | Siapa partisipannya? Apa instrumennya? Bagaimana analisis? |
| Results | Apakah data mendukung temuan? Apakah ada data yang tidak dilaporkan? |
| Discussion | Apakah interpretasi melebihi data? Apakah penulis membahas alternatif? |

---

# Slide 23 - Critical Reading Tahap 2: Evaluasi Metode dan Partisipan

## Memeriksa Kesesuaian Metode dengan Research Question

### Checklist Penilaian Metode

**RQ Anda: "Paper ini meneliti apa, dan metode apa yang seharusnya digunakan?"**

| Aspek | Pertanyaan Kritis |
|---|---|
| **Partisipan** | Siapa? Berapa banyak? Bagaimana merekrut? Apakah representatif? Apakah sesuai dengan target population? |
| **Task** | Apakah tugas yang diberikan sesuai dengan penggunaan nyata? Apakah terlalu mudah/sulit? Apakah durasi cukup? |
| **Instrumen** | Apakah alat ukur sudah divalidasi? Apakah kuesioner sudah teruji reliabilitasnya? |
| **Procedure** | Apakah urutan kondisi dikontrol (counterbalancing)? Apakah ada learning effect? |
| **Analisis** | Apakah teknik statistik sesuai dengan desain dan jenis data? Apakah effect size dilaporkan? |

### Yang Sering Menjadi Kelemahan Paper HCI

- Sampel terlalu kecil dan homogen (hanya mahasiswa)
- Task artificial yang tidak mencerminkan kegiatan nyata
- Tidak ada manipulasi check
- Tidak melaporkan mengapa analisis tertentu dipilih

---

# Slide 24 - Critical Reading Tahap 3: Evaluasi Evidence dan Klaim

## Apakah Klaim Sesuai dengan Bukti?

Kesalahan yang umum terjadi adalah **overclaiming**: interpretasi penulis melebihi bukti yang sebenarnya dapat didukung oleh data.

### Pertanyaan Kritis untuk Mengevaluasi Evidence

1. **Apakah skala atau instrumen benar-benar mengukur yang diklaim?**
   - Contoh: mengklaim mengukur "trust" tetapi hanya menggunakan satu pertanyaan self-report tanpa validasi.

2. **Apakah temuan signifikan secara statistik, praktis, dan ilmiah?**
   - p < 0,05 ≠ temuan penting. Lihat effect size dan confidence interval.

3. **Apakah desain penelitian memungkinkan hubungan kausal atau hanya korelasional?**
   - Jika tidak ada random assignment, berhati-hatilah pada klaim sebab-akibat.

4. **Apakah penulis mempertimbangkan penjelasan alternatif?**
   - Jika tidak, paper mungkin bias dalam interpretasinya.

### Cara mengecek overclaiming

Bandingkan **klaim pada bagian Abstract/Discussion** dengan **apa yang benar-benar diukur dan ditemukan pada Results**. Jika klaim jauh lebih luas daripada metode dan data, paper tersebut overclaiming.

---

# Slide 25 - Identifikasi Limitations: Yang Ditulis dan Yang Tidak Ditulis

## Dua Jenis Limitations

### 1. Limitations yang Diakui Penulis
Biasanya di bagian akhir Discussion atau sebelum Conclusion. Umumnya berupa:

- Keterbatasan generalisasi (sampel, setting)
- Keterbatasan instrumen
- Keterbatasan waktu pengamatan

### 2. Limitations yang *Tidak* Diakui Penulis
Bagian ini yang perlu Anda temukan secara kritis:

| Pertanyaan | Kemungkinan Missing Limitation |
|---|---|
| Apakah sampel terlalu homogen tanpa dibahas? | Selection bias pada rekrutmen |
| Apakah task hanya dilakukan sekali? | Tidak melihat efek jangka panjang/learning |
| Apakah HCI paper dalam waktu singkat? | Kondisi tidak natural |
| Apakah hanya self-report tanpa data objektif? | Social desirability bias |
| Apakah analisis menggunakan group-level tanpa memperhatikan individu? | Individual differences terabaikan |

### Bagaimana Menemukan Hidden Limitations?

1. Lihat kembali **operational definition** variabel
2. Bandingkan dengan metode standar di paper lain
3. Tanyakan: "Apa yang akan terjadi jika konteksnya berbeda?"

---

# Slide 26 - Research Gap: Menemukan Ruang untuk Kontribusi

## Dari Limitations Menuju Research Gap

Research gap adalah pertanyaan atau aspek yang belum dijawab oleh penelitian sebelumnya. Gap dapat diidentifikasi dari:

### 1. Gap dalam Cakupan / Konteks
- Penelitian dilakukan di negara/kultur tertentu—belum diuji di konteks lain
- Penelitian menggunakan populasi tertentu—belum diuji pada populasi berbeda

### 2. Gap dalam Waktu / Perubahan Teknologi
- Penelitian dilakukan sebelum teknologi AI generatif muncul—validitasnya perlu diuji ulang
- Interaksi dengan teknologi berubah drastis sehingga temuan lama perlu diperbarui

### 3. Gap dalam Metode
- Mayoritas paper menggunakan survey—belum cukup eksperimen
- Belum ada studi longitudinal padahal trust bersifat dinamis

### 4. Gap dalam Kontradiksi Temuan
- Paper A menemukan X, paper B menemukan tidak-X
- Belum ada penjelasan yang memadai atas perbedaan tersebut

### 5. Gap dalam Variabel yang Belum Dipertimbangkan
- Belum ada paper yang mengukur moderasi usia/modalitas terhadap trust

---

# Slide 27 - Contoh Identifikasi Research Gap dari Paper

## Ilustrasi Konkret: Proses Bernalar

Anggap Anda membaca 5 paper tentang "User Trust dalam ChatGPT"

| Paper | Temuan | Limitasi/Aspek yang tidak dibahas |
|---|---|---|
| A (2023) | Pengguna cenderung over-rely pada jawaban ChatGPT | Hanya mengukur dalam satu sesi singkat |
| B (2023) | Explanations meningkatkan trust | Hanya mahasiswa sebagai partisipan |
| C (2024) | Trust menurun ketika ditemukan hallucination | Tidak menguji recovery trust setelah error |
| D (2024) | Familiarity berhubungan dengan trust | Korelasional, tidak memanipulasi variabel |
| E (2024) | Interface AI chatbot meningkatkan trust | Tidak membandingkan modality berbeda |

### Sintesis Temuan
- **Konsisten:** trust dipengaruhi oleh error AI dan kemampuan AI.
- **Kontradiksi/inconclusive:** apakah trust bersifat stabil atau berfluktuasi? Apakah trust bisa pulih setelah error?
- **Belum dieksplorasi:** tidak ada studi **longitudinal multi-sesi**, tidak ada eksperimen yang menguji **trust repair strategies**, tidak ada studi dengan **populasi non-mahasiswa**, tidak ada perbandingan antarmuka yang berbeda.

### Research Gap yang Dapat Dirumuskan

> "Penelitian tentang trust pada AI generatif masih bersifat cross-sectional dan menggunakan satu antarmuka. Belum diketahui bagaimana trust berkembang, menurun, dan pulih dalam penggunaan jangka panjang, serta bagaimana desain antarmuka yang berbedaa memengaruhi trajectory trust."

---

# Slide 28 - Menyusun Research Gap Statement

## Dari Temuan Menuju Pernyataan Gap

Gap statement yang baik tidak berbunyi "belum ada penelitian tentang X". Ia menjelaskan *mengapa* ketiadaan itu menjadi masalah dan *apa konsekuensinya* bila tidak diteliti.

### Formula Menyusun Gap Statement

```text
1. Penelitian-penelitian sebelumnya telah menunjukkan [temuan konsisten/inkonsisten]
2. Namun, [aspek/aspek tertentu] belum diuji/dipeksplorasi dalam [konteks/populasi/
   metode/waktu tertentu]
3. Padahal, [pentingnya aspek tersebut] justru menjadi semakin relevan karena
   [alasan: perkembangan teknologi/perubahan konteks/tuntutan praktis]
```

### Contoh Gap Statement yang Kuat

> "Penelitian sebelumnya telah menunjukkan bahwa explainable AI dapat memengaruhi trust pengguna (Zhang et al., 2020; Ehsan et al., 2021). Namun, sebagian besar penelitian dilakukan pada sistem AI tradisional dengan antarmuka statis, dan belum banyak yang meneliti bagaimana kepercayaan pengguna terbentuk dan berubah ketika berinteraksi dengan antarmuka chatbot berbasis generative AI dalam penggunaan berulang. Padahal, penggunaan harian terhadap asisten AI generatif meningkat pesat, sehingga pemahaman tentang dinamika trust jangka panjang menjadi semakin penting untuk merancang AI yang mendukung *appropriate reliance*."

---

# Slide 29 - Related Work Positioning: Bukan Sekadar Daftar Paper

## Prinsip Menulis Related Work yang Kuat

### Kesalahan Umum

- "Paper ini membahas...; paper itu membahas..." → **seperti bibliografi beranotasi**
- Mengutip puluhan paper tanpa analisis
- Related work hanya berada di satu section dan tidak terhubung dengan argumen paper

### Ciri Related Work yang Baik

1. **Sintetis** — mengelompokkan literatur berdasarkan tema/perspektif, bukan per-paper
2. **Kritis** — menunjukkan kekuatan dan keterbatasan penelitian sebelumnya
3. **Terarah** — setiap paragraf mengarah pada pemosisian kontribusi Anda
4. **Struktural** — Memberikan struktur untuk memahami sub-bidang yang berbeda

### Struktur Komunikasi yang Efektif

```text
[Klaim tentang area penelitian] → [Paper yang mendukung]
→ [Apa yang masih kurang]      → [Posisi paper Anda]
```

---

# Slide 30 - Related Work Positioning: Cara Kerja

## Empat Strategi Memposisikan Research

### 1. Positioning dengan Membangun-Bekisting (Bridging)
Tunjukkan bahwa dua area penelitian yang sebelumnya terpisah (misal: explainable AI dan conversational interface) kini perlu dipertemukan.

### 2. Positioning dengan Memanfaatkan Teknologi Baru
Tunjukkan bahwa temuan lama perlu diuji ulang karena teknologi telah berubah secara fundamental. Contoh: trust pada AI harus dipelajari lagi di era generative AI.

### 3. Positioning dengan Mengisi Kekosongan
Tunjukkan ruang kosong yang belum diisi, misalnya: "penelitian tentang AI trust sebagian besar menggunakan populasi Barat, belum ada studi dengan pengguna Indonesia."

### 4. Positioning dengan Menyelesaikan Inkonsistensi
Tunjukkan bahwa paper A dan B menghasilkan temuan yang bertentangan, lalu jelaskan bahwa penelitian Anda akan memberikan penjelasan.

### Kesimpulan dari Setiap Positioning

> "Beberapa penelitian telah mengkaji A, namun belum ada yang melihat B dalam konteks C. Studi ini mengisi celah tersebut dengan D."

---

# Slide 31 - Related Work: Contoh Penulisan

## Contoh Perbandingan: Kurang Sintetis vs Sintetis

### ❌ Kurang Sintetis (seperti daftar ringkasan)

> "Smith et al. (2022) melakukan studi tentang trust pada AI chatbot dan menemukan bahwa pengguna lebih mempercayai chatbot yang memberikan penjelasan. Jones et al. (2023) juga melakukan studi tentang trust pada AI generatif dan menemukan bahwa pengguna lebih percaya pada sistem yang akurat. Chen et al. (2024) meneliti pengaruh hallucinations terhadap kepercayaan..."

### ✅ Sintetis: Pengelompokan & Pemosisian

> "Tiga jalur penelitian telah membentuk pemahaman kita tentang interaksi manusia dengan sistem AI. Pertama, studi tentang **trust dalam AI decision support** menunjukkan bahwa transparansi dan akurasi merupakan determinan penting kepercayaan (Smith et al., 2022; Bansal et al., 2021). Kedua, studi tentang **komunikasi dalam antarmuka percakapan** menekankan bahwa gaya bahasa dan interaktivitas memengaruhi persepsi pengguna (Jones et al., 2023). Ketiga, studi yang lebih baru tentang **limitations AI generatif** menunjukkan bahwa error dan hallucination secara signifikan menurunkan kepercayaan (Chen et al., 2024). Namun, studi-studi tersebut meneliti interaksi dalam satu sesi; dinamika kepercayaan dalam penggunaan jangka panjang serta strategi pemulihan kepercayaan pasca-error masih jarang dieksplorasi. Paper ini berupaya mengisi kesenjangan tersebut."

---

# Slide 32 - Workflow Praktis: Menemukan Paper untuk Critical Review

## Panduan Menjalankan Tugas Pertemuan 05

Tugas Anda pada pertemuan ini adalah melakukan **Critical Review terhadap International Scopus Paper**. Susun langkah Anda:

### Langkah 1: Pilih Paper

1. Cari paper pada **Scopus/ACM DL** yang relevan dengan research interest Anda
2. Gunakan keyword yang telah diformulasikan
3. Pilih paper **terindeks Scopus** (dapat tampil di Scopus)
4. Fokus pada paper mutakhir (tahun 2020-2025) namun fundamental paper juga diperbolehkan

### Langkah 2: Baca dan Analisis

1. Baca paper pada **Pass 1: Scan**, lalu **Pass 2: Deep Reading**
2. Gunakan **tujuh pertanyaan kritis** untuk mengevaluasi:
   - Problem → Gap → RQ → Method → Results → Evidence → Limitation

### Langkah 3: Tulis Critical Review

1. Bukan ringkasan
2. Harus mengandung penilaian Anda terhadap kekuatan dan kelemahan paper
3. Identifikasi limitation dan potensi research gap lanjutan

### Langkah 4: Kaitkan dengan Literature Map Anda
Tambahkan paper tersebut ke dalam peta literatur Anda dan hubungkan dengan paper lainnya.

---

# Slide 33 - Menyusun Literature Map: Petunjuk Praktis dan Panduan Tugas

### Research Progress minggu ini

Hasil yang diharapkan adalah **literature map + research gap**.

### Opsi visualisasi dengan tools sederhana

Tabel atau bagan sederhana dapat dibuat dalam Markdown/dokumen Anda. Contoh tabel untuk memulai:

| Klaster | Paper kunci | Tahun | Metode | Temuan utama | Celah yang tersisa |
|---|---|---|---|---|---|
| Trust in automation | Lee & See (2004) | 2004 | Kajian konsep | Trust bersifat multidimensi | Melihat kerangka tersebut dalam konteks AI modern |
| Human-AI decision making | Bansal et al. (2021) | 2021 | Online experiment | Over-reliance pada AI akurat | Belum memakai interaksi multimodal |
| New GenAI Interaction | Palanica & Fossat (2023) | 2023 | Survey | Persepsi manfaat & risiko | belum melihat perilaku aktual, bukan sekadar opini |

### Kriteria literature map yang baik

- Memiliki **klaster yang jelas** sesuai topik yang Anda teliti
- Ada **label hubungan** antar klaster (contoh: *melandasi*, *mengkritik*, *memperluas*)
- Ada **keterangan area gap** yang berpotensi untuk riset Anda

---

# Slide 34 - Contoh Critical Review: Memilih Paper

## Studi Kasus Singkat

Perhatikan potongan abstrak paper berikut:

> "Abstract: This study investigated user trust and reliance on a generative AI assistant for medical information retrieval. Forty participants interacted with either a standard chatbot interface or an empathetic chatbot interface for five medical queries. Results showed that users in the empathetic condition reported significantly higher trust (p < .05) and were more likely to follow incorrect AI recommendations. We discuss implications for designing conversational agents in healthcare."

### Pertanyaan Kritis Awal (Pass 1)

1. Apa problema? Trust users pada AI untuk topik medis yang berisiko tinggi.
2. RQ implisit? Apakah gaya empatik meningkatkan/berpengaruh terhadap trust & reliance?
3. Desain? 2 conditions, between-subject, n=40.
4. Hasil? Empathetic chatbot meningkatkan trust — dan meningkatkan kepatuhan pada rekomendasi yang salah!
5. Kekhawatiran langsung: ukuran sampel kecil untuk between-subject, apakah alat ukur trust valid?, apakah skenario medis cukup realistik?

---

# Slide 35 - Contoh Critical Review: Evaluasi Mendalam (Pass 2)

## Pertanyaan Kritis Lanjutan

### Evaluasi Metode

| Aspek | Pertanyaan | Catatan untuk Paper Tersebut |
|---|---|---|
| Partisipan | Seberapa representatif? 40 partisipan dari mana? | Perlu dilihat pada detail rekrutmen |
| Material | Apakah pertanyaan medis dan jawaban AI sudah divalidasi? | Cek apakah para ahli medis dilibatkan — jika tidak, klaim untuk aplikasi medis nyata terlalu luas |
| Manipulation check | Apakah peneliti mengukur bahwa interaksi yang bersifat empatik memang dirasakan lebih empatik oleh partisipan? | Bila tidak ada, perubahan outcome tidak dapat diklaim karena gaya empatik |
| Alat ukur | Trust diukur dengan apa? Suhu? Validitasnya? | Perlu dilihat; penggunaan skala satu item dapat menjadi threat |

### Evaluasi Evidence vs Klaim

- **Klaim paper:** Empathetic chatbot meningkatkan trust.
- **Data:** Self-report dan perilaku mengikuti rekomendasi.
- **Kemungkinan ancaman:** Jika tidak ada *actual* empathy yang teramati, perbedaan mungkin berasal dari persepsi kualitas lain. Apakah semua AI response identical antara kedua kondisi?

### Limitation yang mungkin tidak disebutkan penulis

- tidak ada skenario follow-up setelah kejadian salah
- tidak mengukur *trust calibration* — trust tinggi justru menjadi berbahaya karena diikuti tindakan salah

---

# Slide 36 - Dari Critical Review Menuju Gap: Aktivitas Kelas

## Latihan Bersama: Menemukan Gap

### Soal Diskusi

Berdasarkan paper pada slide sebelumnya, diskusikan dalam kelompok Anda:

1. Menurut Anda, **apa contribution utama** yang diklaim oleh paper?
2. **Apa kelemahan studi** yang dapat memengaruhi keklaiman tersebut?
3. **Rancangan apa** yang lebih baik untuk menjawab RQ yang sama?
4. **Apa research gap** yang belum terjawab hingga setelah paper tersebut?

### Contoh Sumbangan Pemikiran untuk Gap

- Apakah pengaruh empati pada trust berbeda pada domain non-medis (pendidikan, keuangan)?
- Bagaimana perilaku trust setelah pengguna menyadari AI memberikan rekomendasi salah dalam jangka waktu lebih lama?
- Bagaimana mengukur trust secara objektif, bukan hanya self-report?
- Apakah empati dari AI dianggap etis? Apakah menyesatkan pengguna agar lebih patuh?

Jika pertanyaan seperti ini Anda ajukan, Anda sedang berpikir seperti **peneliti HCI** — bukan sekadar pembaca.

---

# Slide 37 - Common Pitfalls dalam Literature Review

## Kesalahan yang Harus Dihindari

### 1. Google Scholar Saja
Scholar luas namun tidak menyediakan fasilitas filter yang andal untuk discipline tertentu. Gunakan Scopus dan ACM DL untuk mencari sumber primer HCI.

### 2. Berhenti pada Sumber Sekunder
Mengutip paper yang mengutip paper lain tanpa membaca paper asalnya dapat menghasilkan kesalahan interpretasi dan klaim palsu. Selalu merujuk pada sumber utama.

### 3. Tidak Mencatat Proses

Akibat yang muncul:
- Tidak tahu keyword apa yang sudah digunakan
- Tidak dapat meyakinkan reviewer bahwa pencarian literatur Anda sistematis

### 4. Overclaiming Gap

Pernyataan "no research has been done on..." sangat berisiko. Anda harus lebih spesifik: "to the best of our knowledge, belum ada penelitian yang mengkaji ... dengan ... dalam populasi ...".

### 5. Menganggap Semua Hasil Sama Valid
Paper di jurnal dan konferensi dengan peer review yang ketat umumnya lebih kuat buktinya daripada preprint atau *extended abstract*. Namun paper di CHI juga dapat memiliki masalah metodologis—justru itu tugas Anda untuk menilainya secara kritis.

---

# Slide 38 - Memublikasikan Literature Review? Perbedaan antara Literatur Review untuk Proposal vs Systematic Review untuk Paper

## Dua Jenis Kebutuhan Komunikasi Ilmiah

### Literature review sebagai bagian proposal tesis
- Tujuan: Mempersempit topik dan menunjukkan bahwa riset Anda layak
- Bentuk: sintesis terkait work, gap, dan positioning pada proposal
- Cakupan: cukup mendalam untuk ranah riset yang dipilih

### Literature review untuk paper penelitian
- Tidak perlu menulis "tinjauan pustaka" lengkap seperti bab buku.
- Reviewer paper HCI umumnya menilai apakah **state-of-the-art dipahami dengan benar**, bukan sekadar berapa banyak referensi.
- Jika Anda akan melakukan sebuah riset yang memang menuntut *systematic review* sebagai kontribusi tersendiri, gunakan metode seperti PRISMA bila relevan. Untuk target umum conference HCI, litreview terfokus jauh lebih penting daripada perluasan cakupan yang dangkal.

### Pedoman efisiensi waktu
1. Sisihkan waktu 2-3 minggu untuk literatur
2. Update hingga menjelang submit paper
3. Sisipkan pencarian baru untuk topik yang berkembang cepat (AI, GenAI)

---

# Slide 39 - Ringkasan Pertemuan 05: Literature Review & Critical Paper Reading

## Peta Kompetensi yang Sudah Anda Latih

Dari pertemuan ini, kemampuan utama yang Anda miliki:

| No | Kemampuan Utama | Tools/teknik yang andalkan |
|---|---|---|
| 1 | Pencarian literatur yang sistematis | Keyword, Scopus, ACM DL, inklusi/eksklusi |
| 2 | Perluasan literatur via snowballing | backward & forward snowballing |
| 3 | Memetakan literatur | Literature map (tematik/kronologis/metodologis) |
| 4 | Sintesis riset | Matriks sintesis, perbandingan antar paper |
| 5 | Membaca paper secara kritis | 7 pertanyaan kritis, mengevaluasi evidence |
| 6 | Identifikasi gap | Analsis limitasi, kontradiksi, kekosongan konteks |
| 7 | Positioning related work | Menulis related work yang sintetis dan terarah |

### Progress Anda saat ini (Research Progress di Pertemuan 05)

Kumpulkan **literature map + research gap** yang menjadi dasar perumusan research question pada pertemuan berikutnya (Pertemuan 06) tentang quantitative HCI research.

---

# Slide 40 - TERIMA KASIH

Pertemuan berikutnya

**Quantitative HCI Research**