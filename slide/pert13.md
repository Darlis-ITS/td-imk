# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer  
Pertemuan 13

## Data Analysis & Evidence in HCI

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D  
Departemen Teknik Informatika - ITS

---

# Slide 01 - Posisi Pertemuan 13 dalam Alur Perkuliahan

## Dari Research Design ke Research Evidence

```
Minggu 1-7:  Konsep HCI → Research Problem → Gap → RQ → Methodology
Minggu 8:    UTS — Research Proposal Defense
Minggu 9-12: User Study Design → Instrumen → Pilot → Data Collection
Minggu 13:   DATA ANALYSIS & EVIDENCE  ← posisi Anda di sini
Minggu 14:   Validity, Reproducibility & Research Ethics
Minggu 15-16: Scientific Contribution & Final Paper
```

## Research Progress Anda pada Pertemuan Ini

| Sebelumnya (Minggu 12) | Sekarang (Minggu 13) | Berikutnya (Minggu 14) |
|---|---|---|
| Data collection + quality control | **Data analysis dan preliminary findings** | Results + validity + limitations |

---

# Slide 02 - Capaian Pembelajaran Pertemuan 13

## Setelah pertemuan ini, mahasiswa diharapkan mampu:

1. **Menjelaskan alur transformasi** dari data mentah menjadi evidence dan claim ilmiah
2. **Melakukan data cleaning** dan pemeriksaan kualitas data untuk penelitian HCI
3. **Memilih dan menerapkan statistik deskriptif** yang sesuai untuk data kuantitatif HCI
4. **Memahami konsep statistical inference**, hypothesis testing, effect size, dan confidence interval
5. **Menganalisis data eksperimen** dengan membandingkan kondisi antara dan dalam partisipan
6. **Melakukan analisis kualitatif**: coding, codebook, thematic analysis, inter-rater agreement
7. **Menerapkan triangulasi** untuk memperkuat evidence
8. **Menyajikan hasil** melalui data visualization dan reporting yang benar

## Kata kunci

> **Data → Result → Finding → Evidence → Claim**

---

# Slide 03 - Menghubungkan dengan Pertemuan Sebelumnya

## Dari Data Collection ke Data Analysis

- Pertemuan 9 telah membahas **user study evaluation**: task completion, completion time, error rate, SUS, UEQ, NASA-TLX, interaction logs
- Pertemuan 12 menekankan **data quality control**: memastikan data yang dikumpulkan bersih dan layak
- Sekarang data tersebut harus **dianalisis secara sistematis** menjadi temuan penelitian

## Prinsip yang Harus Diingat

- Penelitian kuantitatif Pertemuan 6: data dihasilkan dari pengukuran variabel dalam eksperimen terkontrol
- Penelitian kualitatif Pertemuan 7: data dihasilkan dari wawancara, observasi, diary, think-aloud
- Mixed methods menggabungkan keduanya untuk pemahaman yang lebih lengkap

## Pertanyaan Kunci

> Data telah Anda kumpulkan. **Apa yang data tersebut katakan?** Dan seberapa kuat bukti yang dapat Anda klaim?

---

# Slide 04 - Fokus Utama: Alur Data → Evidence

## Perbedaan Fundamental

| Level | Pertanyaan | Contoh |
|---|---|---|
| **Data** | Apa yang terekam? | Time on task: 45.2 s, 52.1 s, dll; transkrip wawancara |
| **Result** | Apa hasil analisis statistik/tekstual? | t(38) = 2.31, p = .026; muncul tema "trust" |
| **Finding** | Apa pola yang bermakna secara konseptual? | Partisipan lebih cepat menggunakan interface A karena familiar |
| **Evidence** | Seberapa kuat data mendukung interpretasi? | Didukung statistik + perilaku + pernyataan partisipan |
| **Claim** | Apa pernyataan ilmiah yang sah dibuat? | "Interface A mengurangi beban kognitif pada tugas X" |

## Kesalahan Umum Peneliti Pemula

```
Data menunjukkan perbedaan → langsung membuat claim
Tanpa mempertimbangkan: apakah efeknya nyata? cukup besar? konsisten?
apakah ada penjelasan alternatif? apakah sampel representatif?
```

---

# Slide 05 - Statistical Significance ≠ Scientific Significance

## Peringatan Utama Pertemuan 13

> **Statistical significance tidak otomatis berarti scientific significance.**

## Ilustrasi

| Situasi | Statistical significance | Scientific significance |
|---|---|---|
| Perbedaan 0.3 detik pada tugas 60 detik, p < .05, N = 200 | Ya | Dipertanyakan — apakah 0.3 detik penting secara praktis? |
| Perbedaan besar pada 5 partisipan, tidak signifikan | Tidak | Mungkin penting secara ilmiah — indikasi efek kuat, perlu N lebih besar |
| Hasil signifikan tetapi hanya pada satu konteks sempit | Ya | Terbatas — generalisasi belum sah |

## Yang Perlu Dipertimbangkan

- **Effect size**: seberapa besar pengaruh?
- **Practical importance**: apakah perbedaan itu berarti bagi pengguna nyata?
- **Consistency**: apakah pola muncul di berbagai kondisi dan partisipan?
- **Triangulation**: apakah berbagai sumber data saling mendukung?

---

# Slide 06 - Data Cleaning: Mengapa dan Bagaimana?

## Tujuan Data Cleaning

1. Mendeteksi **data error**: salah input, nilai tidak masuk akal, duplikat
2. Menangani **missing data**: data tidak terisi karena drop-out atau kegagalan teknis
3. Mengidentifikasi **outliers**: nilai ekstrem yang menyimpang dari pola umum
4. Memastikan **format konsisten**: skala, satuan, penamaan variabel

## Langkah Praktis

```
1. Inspeksi visual: head(data), str(data), summary(data)
2. Validasi rentang: cek apakah nilai dalam rentang skala yang mungkin
3. Identifikasi missing: summary(is.na(data)), visualisasi pola missing
4. Deteksi outlier: boxplot, z-score, IQR method
5. Dokumentasikan SEMUA keputusan cleaning
```

## Prinsip Penting

> **Jangan pernah menghapus data tanpa dokumentasi. Setiap keputusan cleaning harus dapat dijelaskan dan direplikasi.**

---

# Slide 07 - Menangani Missing Data dan Outliers

## Missing Data

| Tipe | Arti | Penanganan umum |
|---|---|---|
| MCAR (Missing Completely At Random) | Tidak ada pola; data hilang acak | Analisis lengkap atau imputasi |
| MAR (Missing At Random) | Kehilangan terkait variabel lain yang teramati | Imputasi bergantung variabel lain |
| MNAR (Missing Not At Random) | Kehilangan terkait nilai yang hilang itu sendiri | Model khusus; lapor sebagai limitation |

**Jangan pernah** mengganti missing dengan rata-rata tanpa pertimbangan hati-hati.

## Outliers

```python
## Deteksi outlier dengan IQR (Python)
import numpy as np
Q1, Q3 = np.percentile(data, [25, 75])
IQR = Q3 - Q1
outliers = data[(data < Q1 - 1.5*IQR) | (data > Q3 + 1.5*IQR)]
```

## Aturan Umum

- Cek apakah outlier adalah **data error** (maka koreksi) atau **nilai ekstrem asli** (maka analisis dengan dan tanpa outlier)
- Outlier dapat mengungkapkan fenomena menarik — analisis terpisah sering lebih informatif daripada sekadar membuang

---

# Slide 08 - Descriptive Statistics: Merangkum Data

## Untuk Data Numerik

| Ukuran | Fungsi | Catatan |
|---|---|---|
| Mean | Pusat data | Sensitif terhadap outlier |
| Median | Pusat data yang robust | Lebih baik jika distribusi skewed |
| Mode | Nilai paling sering | Berguna untuk data kategorikal |
| SD / Variance | Sebaran data | Semakin besar semakin bervariasi |
| Range / IQR | Rentang nilai | IQR robust terhadap outlier |
| Skewness | Simetri distribusi | Menentukan pilihan uji statistik |

## Untuk Data Kategorikal

- Frekuensi dan persentase
- Tabel kontingensi jika ada dua variabel

## Contoh Pelaporan dalam HCI

> "Rata-rata completion time pada kondisi A (M = 45.2 s, SD = 8.3) lebih rendah dibanding kondisi B (M = 52.1 s, SD = 9.7). Distribusi time pada kedua kondisi sedikit right-skewed (skewness = 0.8 dan 0.6)."

---

# Slide 09 - Memahami Distribusi Data Sebelum Memilih Uji

## Jenis Distribusi

```
Symmetric (Normal)          Right-Skewed          Left-Skewed
     /\                       |                        /|
    /  \                      |                       / |
   /    \                     |                      /  |
  /      \                    |\                    /   |
 /        \                   | \                  /    |
+----------+                  +------+           +------+
Mean ≈ Median               Mean > Median        Mean < Median
```

## Mengapa Distribusi Penting?

- Banyak uji parametrik mengasumsikan data **berdistribusi normal**
- Jika asumsi dilanggar, hasil uji dapat menyesatkan
- Cek menggunakan: histogram, Q-Q plot, Shapiro-Wilk test (untuk sampel kecil)

## Keputusan Analisis

```python
if normal_distribution(data):
    gunakan uji parametrik    # t-test, ANOVA
else:
    gunakan uji non-parametrik  # Mann-Whitney, Wilcoxon, Kruskal-Wallis
```

---

# Slide 10 - Statistical Inference: Dari Sampel ke Populasi

## Konsep Dasar

- Penelitian HCI hampir selalu menggunakan **sampel** (misal 30 partisipan)
- Kita ingin menarik kesimpulan tentang **populasi** (misal semua pengguna sistem serupa)
- **Statistical inference** adalah proses membuat kesimpulan tentang populasi berdasarkan data sampel

## Dua Pilar Inference

1. **Point estimate**: nilai tunggal dari sampel (misal rata-rata completion time = 45.2 s)
2. **Interval estimate**: rentang nilai yang mungkin memuat parameter populasi (95% CI: 42.1–48.3 s)

## Pertanyaan Kunci

> Jika saya mengulang eksperimen dengan sampel berbeda, apakah hasilnya akan konsisten? Berapa besar ketidakpastian perkiraan saya?

## Peran Sample Size

```
Sample size kecil → CI lebar → ketidakpastian tinggi → evidence lemah
Sample size besar  → CI sempit → ketidakpastian rendah → evidence lebih kuat
```

---

# Slide 11 - Hypothesis Testing: Logika dan Prosedur

## Logika Pengujian Hipotesis

1. Nyatakan **null hypothesis (H₀)**: tidak ada efek/perbedaan
   - Contoh H₀: "Tidak ada perbedaan completion time antara Interface A dan B"
2. Nyatakan **alternative hypothesis (H₁)**: ada efek/perbedaan
   - Contoh H₁: "Completion time Interface A berbeda dari Interface B"
3. Kumpulkan data dan hitung statistik uji
4. Hitung **p-value**: probabilitas memperoleh hasil setidaknya seekstrem ini JIKA H₀ benar
5. **Keputusan**: tolak H₀ jika p-value < α (biasanya 0.05)

## Interpretasi p-value yang Benar

| Interpretasi yang SALAH | Interpretasi yang BENAR |
|---|---|
| "p = .03 berarti probabilitas H₀ benar adalah 3%" | "Jika sebenarnya tidak ada efek, kita hanya akan melihat perbedaan sebesar ini dalam 3% eksperimen serupa" |
| "p = .03 berarti efek ini signifikan secara ilmiah" | "p < .05 hanya memenuhi ambang statistik; interpretasi tetap perlu konteks" |

---

# Slide 12 - Kesalahan dalam Hypothesis Testing

## Two Types of Error

| Keputusan | H₀ benar (tidak ada efek) | H₁ benar (ada efek) |
|---|---|---|
| **Tolak H₀** (klaim ada efek) | ❌ Type I error (α) | ✅ Correct |
| **Gagal tolak H₀** (klaim tidak ada efek) | ✅ Correct | ❌ Type II error (β) |

## Implikasi untuk Penelitian HCI

- **Type I error**: mengklaim efek yang sebenarnya tidak ada → publikasi hasil palsu
- **Type II error**: gagal mendeteksi efek yang sebenarnya ada → melewatkan temuan penting

## Cara Mengurangi Risiko

| Risiko | Strategi |
|---|---|
| Type I error | Tetapkan α; gunakan koreksi multiple comparisons (Bonferroni, Tukey HSD) |
| Type II error | Tingkatkan sample size; power analysis sejak desain |
| Keduanya | Replikasi; analisis pre-registered; jangan p-hacking |

## Peringatan

> **Jangan melakukan p-hacking**: menggali data berulang kali hingga menemukan p < .05. Ini adalah praktik tidak etis yang merusak kredibilitas penelitian.

---

# Slide 13 - Effect Size: Seberapa Besar Efeknya?

## Mengapa p-value Tidak Cukup?

- p-value hanya menunjukkan **apakah** efek mungkin ada
- Effect size menunjukkan **seberapa besar** efek tersebut
- Dua studi dengan p = .001 dapat memiliki effect size sangat berbeda

## Ukuran Effect Size yang Umum

| Ukuran | Untuk | Interpretasi umum | Rumus |
|---|---|---|---|
| Cohen's d | Dua kelompok | 0.2 kecil, 0.5 sedang, 0.8 besar | (M₁-M₂) / SD_pooled |
| Pearson's r | Korelasi | 0.1 kecil, 0.3 sedang, 0.5 besar | — |
| η² (eta-squared) | ANOVA | Proporsi varians yang dijelaskan | SS_effect / SS_total |
| Odds ratio | Data kategorikal | 1 = tidak ada efek | — |

## Contoh Pelaporan

> "Terdapat perbedaan signifikan antara kedua kondisi, t(38) = 2.31, p = .026, **Cohen's d = 0.74**, menunjukkan efek dengan ukuran sedang-ke-besar."

## Nilai Effect Size dan Scientific Significance

> Effect size yang kecil tetap dapat bermakna jika: (1) dampak kumulatifnya besar, (2) mengukur variabel penting, atau (3) berada pada konteks yang sulit diubah. Sebaliknya, d besar pada N kecil tetap perlu replikasi.

---

# Slide 14 - Confidence Interval: Rangkaian Nilai yang Masuk Akal

## Definisi Konseptual

- **95% confidence interval** (CI) adalah rentang nilai yang, jika penelitian diulang berkali-kali, akan memuat parameter populasi pada 95% replikasi
- CI lebih informatif daripada p-value karena memberikan **informasi ketepatan estimasi**

## Contoh pada HCI

```
Skenario 1: Completion time difference = 2.1 s, 95% CI [0.3, 3.9]
  → CI tidak mencakup 0 → konsisten dengan efek signifikan

Skenario 2: Completion time difference = 2.1 s, 95% CI [-1.5, 5.7]
  → CI mencakup 0 → tidak cukup bukti; estimasi sangat tidak presisi
```

## Kegunaan CI

1. Menunjukkan **arah dan besarnya efek**
2. Menunjukkan **presisi estimasi** — semakin sempit CI semakin baik
3. Memudahkan perbandingan antar studi

## Pelaporan yang Direkomendasikan

> "Tuliskan effect size beserta CI-nya, bukan hanya p-value."

---

# Slide 15 - Correlation: Menemukan Hubungan Antar Variabel

## Korelasi vs Kausalitas

```
Korelasi: perubahan X berhubungan dengan perubahan Y
Kausalitas: perubahan X MENYEBABKAN perubahan Y

Korelasi TIDAK membuktikan kausalitas
```

## Kapan Menggunakan Analisis Korelasi?

- Hubungan antara **dua variabel kontinu** tanpa manipulasi
- Contoh: "Apakah skor SUS berkorelasi dengan completion time?"; "Apakah self-reported workload berkorelasi dengan error rate?"

## Jenis dan Interpretasi

| Ukuran | Jenis hubungan | Rentang nilai |
|---|---|---|
| Pearson's r | Linear | -1 s.d. +1 |
| Spearman's rho | Monoton (tidak harus linear) | -1 s.d. +1 |
| Point-biserial | Satu variabel biner | -1 s.d. +1 |

## Contoh Pseudocode

```python
from scipy.stats import pearsonr, spearmanr
r, p = pearsonr(x, y)        # jika normal & linear
rho, p = spearmanr(x, y)     # jika tidak normal / tidak linear
```

---

# Slide 16 - Comparing Conditions: Uji untuk Desain Antar Kelompok

## Desain Between-Subjects

Setiap partisipan masuk ke **satu kondisi saja**

```
Group 1 (Interface A): P1 P2 P3 P4 P5 ...
Group 2 (Interface B): P6 P7 P8 P9 P10 ...
```

### Uji yang Sesuai

| Jumlah grup | Data normal | Data tidak normal |
|---|---|---|
| 2 grup | Independent samples t-test | Mann-Whitney U test |
| > 2 grup | One-way ANOVA | Kruskal-Wallis test |

## Contoh RQ dan Analisis

> RQ: "Apakah ada perbedaan workload (NASA-TLX) antara pengguna pemula dan ahli dalam menggunakan generative AI chatbot?"

```
H₀: μ_pemula = μ_ahli
H₁: μ_pemula ≠ μ_ahli

Uji: Independent t-test pada skor NASA-TLX
Lapor: t(df), p, Cohen's d, 95% CI
```

---

# Slide 17 - Comparing Conditions: Uji untuk Desain Dalam Partisipan

## Desain Within-Subjects (Repeated Measures)

Setiap partisipan mengalami **semua kondisi**

```
Partisipan P1: (A1 B1 A2 B2)   ← counterbalanced order
Partisipan P2: (B1 A1 B2 A2)
Partisipan P3: (A2 B2 A1 B1)
...
```

### Uji yang Sesuai

| Jumlah kondisi | Data normal | Data tidak normal |
|---|---|---|
| 2 kondisi | Paired samples t-test | Wilcoxon signed-rank test |
| > 2 kondisi | Repeated measures ANOVA | Friedman test |

## Keunggulan dan Tantangan

| Keunggulan | Tantangan |
|---|---|
| Mengontrol perbedaan individual antar partisipan | Order effects: belajar, kelelahan |
| Lebih powerful — butuh partisipan lebih sedikit | Butuh counterbalancing |

## Contoh Pelaporan

> "Terdapat perbedaan signifikan pada completion time antara kedua kondisi, t(29) = -3.12, p = .004, d = 0.57. Sebanyak 22 dari 30 partisipan lebih cepat pada kondisi dengan voice feedback."

---

# Slide 18 - Repeated Measures: ANOVA dan Pengujian Lanjutan

## Kapan Repeated Measures ANOVA Diperlukan?

Ketika Anda memiliki **lebih dari 2 kondisi** dan setiap partisipan menjalani semua kondisi:

```
Contoh: Membandingkan 3 tingkat feedback: none, text, voice
Setiap partisipan mencoba ketiganya
```

## Jalur Analisis

```
Repeated Measures ANOVA
        |
        +-- Signifikan? -- Ya --> Post-hoc comparisons (Bonferroni / Tukey)
        |                          Lapor: pasangan mana yang berbeda
        +-- Tidak signifikan? --> Laporkan effect size dan CI
                                   Diskusikan interpretasi null finding
```

## Asumsi yang Perlu Dicek

1. Normalitas data pada tiap kondisi
2. **Sphericity**: varians perbedaan antar kondisi relatif sama
   - Jika dilanggar: gunakan koreksi Greenhouse-Geisser
3. Tidak ada outlier ekstrem yang mendominasi

## Contoh

> "RM-ANOVA menunjukkan pengaruh signifikan tipe feedback terhadap task completion, F(2, 58) = 6.21, p = .003, η² = 0.18. Post-hoc Bonferroni menunjukkan bahwa voice feedback secara signifikan lebih cepat daripada none (p = .001), tetapi tidak berbeda signifikan dari text feedback (p = .12)."

---

# Slide 19 - Non-Parametric Analysis: Alternatif yang Robust

## Kapan Menggunakan?

- Data **tidak normal** (skewed, bounded, ordinal)
- Skala pengukuran **ordinal** (Likert, rating 1–7 tanpa asumsi interval murni)
- **Sample size kecil** tanpa jaminan normalitas
- Terdapat **outliers** yang tidak dapat ditangani transformasi

## Peta Uji Non-Parametrik

| Padanan parametrik | Non-parametrik | Fungsi |
|---|---|---|
| Independent t-test | Mann-Whitney U | 2 kelompok independen |
| Paired t-test | Wilcoxon signed-rank | 2 kondisi terkait |
| One-way ANOVA | Kruskal-Wallis | > 2 kelompok independen |
| RM-ANOVA | Friedman | > 2 kondisi terkait |

## Pseudocode Keputusan

```python
if sample_size >= 30 and normal(distribusi_per_kondisi):
    # pendekatan parametrik
    if repeated_measures:
        t-test_berpasangan() atau rm_anova()
    else:
        t-test_independen() atau anova()
else:
    if repeated_measures:
        wilcoxon() / friedman()
    else:
        mann_whitney() / kruskal_wallis()
```

## Catatan

> Non-parametrik tidak "lebih lemah" secara universal — kadang justru lebih tepat dan lebih jujur terhadap data.

---

# Slide 20 - Qualitative Coding: Dari Data Teks ke Kategori Bermakna

## Apa itu Qualitative Coding?

Proses memberi label pada segmen data (transkrip, catatan lapangan, open-ended response) dengan **kode** yang merangkum makna segmen tersebut.

```
Contoh Data (transkrip think-aloud):
"AI-nya bingung kalau saya nanya konteks yang
 belom pernah disebut. Kayaknya dia lupa ya."

→ Kode: "AI kehilangan konteks percakapan"
```

## Jenis Pendekatan Coding

| Pendekatan | Proses | Contoh |
|---|---|---|
| Inductive / Open coding | Kode muncul dari data | Menemukan kategori baru yang tak terduga |
| Deductive / Closed coding | Kode ditentukan dari teori/kerangka | Mencari bukti tema yang sudah diprediksi |

## Workflow

```
1. Familiarisasi: baca seluruh data
2. Koding awal: segmen → label kode
3. Penyempurnaan: gabung, pisah, atau rapikan kode
4. Definisikan kode secara eksplisit → codebook
5. Terapkan ke seluruh dataset secara konsisten
6. Validasi: inter-rater agreement
```

---

# Slide 21 - Codebook: Dokumen Panduan Koding

## Mengapa Codebook Penting?

- Memastikan **konsistensi** antar-coder dan antar-waktu
- Meningkatkan **transparansi dan reproduktibilitas** penelitian
- Berguna untuk pelaporan di paper dan replikasi oleh peneliti lain

## Struktur Codebook yang Baik

| Kolom | Isi |
|---|---|
| Code name | Label singkat, misal "trust_breakdown" |
| Definition | Makna kode secara jelas |
| Inclusion criteria | Kapan data HARUS diberi kode ini |
| Exclusion criteria | Kapan data TIDAK boleh diberi kode ini |
| Example | Contoh kutipan teks |
| Non-example | Kutipan yang tampak mirip tetapi bukan kode ini |

## Contoh Codebook

| Code | Definition | Inclusion | Example |
|---|---|---|---|
| trust_breakdown | Partisipan menyatakan kehilangan keyakinan pada AI | Menyebut ragu, tidak yakin, takut salah, tidak mau mengikuti rekomendasi | "Saya tidak yakin jawabannya benar, jadi saya cek sendiri" |
| trust_build | Partisipan menyatakan keyakinan meningkat | Menyebut AI membantu, jawaban tepat, merasa aman | "Setelah beberapa kali benar, saya mulai percaya" |

---

# Slide 22 - Thematic Analysis: Dari Kode ke Tema

## Definisi

- **Thematic analysis** adalah metode untuk mengidentifikasi, menganalisis, dan melaporkan **pola (tema)** dalam data kualitatif
- Umum digunakan dalam penelitian HCI untuk memahami pengalaman pengguna, kebutuhan, hambatan, dan persepsi

## Proses Menurut Braun & Clarke

```
Fase 1: Familiarisasi dengan data          → baca transkrip, catat ide awal
Fase 2: Generate initial codes             → tandai segmen menarik
Fase 3: Searching for themes               → kelompokkan kode → calon tema
Fase 4: Reviewing themes                   → cek apakah tema konsisten dengan data
Fase 5: Defining & naming themes           → tulis definisi dan nama tema
Fase 6: Producing the report               → tulis hasil dengan kutipan pendukung
```

## Contoh Hasil Tema

```
Tema 1: "Kepercayaan dibangun melalui konsistensi jawaban"
  - Kode: trust_build, reliable_answer, consistency_experience
Tema 2: "Ketidakpastian AI memunculkan kebutuhan verifikasi eksternal"
  - Kode: trust_breakdown, external_check, double_check
```

---

# Slide 23 - Inter-Rater Agreement: Menguji Konsistensi Koding

## Mengapa Diperlukan?

- Koding kualitatif mengandung **subjektivitas peneliti**
- Jika dua peneliti mengkode data yang sama dengan hasil berbeda, interpretasi mungkin bias
- Inter-rater agreement menunjukkan bahwa kategori yang dihasilkan **cukup objektif dan dapat direplikasi**

## Ukuran yang Umum Digunakan

| Ukuran | Rentang | Catatan |
|---|---|---|
| Percentage agreement | 0–100% | Mudah, tetapi tidak mengoreksi kesepakatan acak |
| Cohen's κ (kappa) | -1 s.d. +1 | Mengoreksi kesepakatan karena kebetulan |
| Krippendorff's α | 0 s.d. +1 | Bekerja untuk lebih dari 2 coder; berbagai tipe data |

## Interpretasi Cohen's Kappa (umum)

| Nilai κ | Tingkat kesepakatan |
|---|---|
| > 0.81 | Hampir sempurna |
| 0.61–0.80 | Substantial |
| 0.41–0.60 | Moderate |
| < 0.40 | Lemah — perlu perbaikan definisi kode |

> Tujuan utama bukan sekadar mencapai kappa tinggi, melainkan memastikan bahwa kode yang digunakan **mewakili realitas data** secara konsisten.

---

# Slide 24 - Triangulasi: Memperkuat Evidence dari Banyak Sisi

## Definisi

**Triangulasi** adalah penggunaan **lebih dari satu sumber data, metode, peneliti, atau teori** untuk memeriksa konsistensi temuan dan mengurangi bias.

## Jenis Triangulasi

| Jenis | Contoh |
|---|---|
| Data triangulation | Menggabungkan wawancara + observasi + log sistem |
| Method triangulation | Mixed methods: kuantitatif + kualitatif |
| Investigator triangulation | Lebih dari satu peneliti menganalisis data |
| Theory triangulation | Melihat data dari lensa teori yang berbeda |

## Ilustrasi Sederhana

```
         Temuan Kuat
         /    |    \
   Data      Data     Data
   Log     Wawancara  Observasi
    |          |          |
   "User      "Saya     "User terlihat
   menekan    bingung    ragu, mencoba
   tombol     dengan     beberapa kali
   help 5x"   urutan"    sambil menghela
                          napas"
```

> Jika berbagai sumber data mengarah pada kesimpulan yang sama, **claim lebih meyakinkan**. Jika berbeda, justru menjadi peluang untuk penyelidikan lebih dalam — bukan alasan memilih data yang cocok.

---

# Slide 25 - Analisis Mixed Methods: Integrasi Kuantitatif-Kualitatif

## Prinsip Integrasi

- Data kuantitatif menjawab **berapa banyak / seberapa besar / apakah signifikan?**
- Data kualitatif menjawab **mengapa dan bagaimana?**
- Integrasi terjadi pada saat: (1) analisis terpisah, lalu (2) dibandingkan/digabung

## Tiga Pola Integrasi Umum dalam HCI

| Pola | Urutan | Tujuan |
|---|---|---|
| Explanatory sequential | KUANT sampai hasil → lalu kualitatif | Menjelaskan hasil kuantitatif yang mengejutkan |
| Exploratory sequential | KUAL → identifikasi konstruk → lalu kuantitatif | Mengembangkan instrumen atau menguji temuan kualitatif |
| Concurrent | Kuantitatif dan kualitatif bersamaan | Memperkaya dan mengonfirmasi lintas data |

## Contoh dalam Studi HCI

> Kuantitatif: SUS skor tinggi (M = 82) pada aplikasi baru.
> Kualitatif: wawancara mengungkap partisipan tetap ragu karena "tidak tahu apa yang AI lakukan di balik layar".
> **Finding**: Skor tinggi mencerminkan kemudahan penggunaan permukaan; trust dan transparency tetap menjadi isu yang belum terselesaikan.

---

# Slide 26 - Data Visualization: Menyajikan Data Secara Jujur dan Informatif

## Prinsip Visualisasi untuk Penelitian

1. **Jangan menyesatkan**: jangan memotong sumbu Y tanpa memberi label yang jelas
2. **Pilih grafik sesuai data**: jangan memaksakan grafik yang cantik tetapi sulit dibaca
3. **Tampilkan sebaran dan ketidakpastian**: boxplot, error bars, violin plot
4. **Berlabel lengkap**: satuan, variabel, legenda, N

## Panduan Pemilihan Grafik

| Tujuan | Grafik yang disarankan |
|---|---|
| Distribusi satu variabel kontinu | Histogram, boxplot, violin plot |
| Perbandingan antar 2-3 kelompok | Boxplot + titik data individual; bar chart dengan error bar |
| Hubungan dua variabel | Scatterplot + garis regresi/korelasi |
| Data kategorikal | Bar chart |
| Perubahan antar kondisi (within-subject) | Spaghetti plot / paired line plot |

## Anti-Patterns

```
BURUK: Bar chart 3D yang memotong sumbu Y dari 40
BURUK: Pie chart dengan > 5 kategori
BURUK: Error bars hanya menunjukkan SEM tanpa penjelasan
BAIK:  Strip chart / beeswarm memperlihatkan seluruh titik data
```

---

# Slide 27 - Visualisasi untuk Hasil Statistik

## Menampilkan Effect dengan Benar

```
Condition A:        ● ———— [■] ———— ●
Condition B:              ● —— [■] —— ●
                        
■ = mean, ● = batas CI 95%
Jika dua CI tidak tumpang tindih (sekadar heuristic), kemungkinan
perbedaan signifikan, tetapi uji statistik tetap diperlukan.
```

## Menampilkan Data Within-Subjects

```
Partisipan 1: A ───────────── B   \
Partisipan 2:    A ───────── B    >  spaghetti plot memperlihatkan
Partisipan 3: A ───── B            /  konsistensi arah efek
```

## Catatan Penting

- Tampilkan **individual data points**, terutama untuk N kecil
- Error bar wajib diberi keterangan: apakah SD, SEM, atau CI?
- Jangan hanya menampilkan bar chart; berikan juga **gambaran sebaran**

---

# Slide 28 - Reporting Results: Bagian Hasil Kuantitatif

## Struktur Pelaporan Hasil Kuantitatif yang Disarankan

1. **Data cleaning summary** — jumlah data yang digunakan, data yang dikeluarkan dan alasannya
2. **Descriptive statistics** — M, SD/Median, IQR per kondisi; tabel ringkas
3. **Assumption checks** — normalitas, sphericity; keputusan parametrik vs non-parametrik
4. **Main analysis** — uji hipotesis utama, fokus pada RQ
5. **Additional/post-hoc analyses** — eksplorasi tambahan yang relevan

## Format Pelaporan Statistik (mengikuti APA style)

> "An independent samples t-test revealed a significant difference in completion time between conditions A and B, t(38) = 2.31, p = .026, Cohen's d = 0.74, 95% CI [0.08, 1.40]."

## Hal yang Sering Terlupakan

- Tuliskan **ukuran efek** tidak hanya p
- Laporkan **hasil yang tidak signifikan** juga — jangan hanya yang signifikan
- Jangan mengubah hasil "tidak signifikan" menjadi "tidak ada efek" — bisa jadi kekuatan uji kurang

---

# Slide 29 - Reporting Results: Bagian Hasil Kualitatif

## Struktur Pelaporan Hasil Kualitatif

1. **Deskripsi proses analisis**: bagaimana coding dilakukan, berapa peneliti terlibat
2. **Inter-rater reliability** jika dilakukan
3. **Presentasi tema**: untuk setiap tema sertakan nama, definisi, dan bukti kutipan
4. **Penjelasan hubungan antar tema** jika ada

## Contoh Kutipan dalam Hasil Kualitatif

| Tema | Contoh kutipan |
|---|---|
| Ketidakpastian | "Saya tidak tahu apakah rekomendasi ini benar, jadi saya verifikasi manual" |
| Beban verifikasi | "Setiap jawaban harus saya cek ulang, itu melelahkan" |
| Kepercayaan bertahap | "Setelah tiga kali tepat, saya mulai mengandalkannya" |

## Aturan Interpretasi

> Jangan hanya menulis "banyak partisipan mengatakan..." — gunakan kata yang dapat dipertanggungjawabkan: "mayoritas partisipan (12 dari 15)..." atau "hampir semua...", atau frasa deskriptif kualitatif yang jelas. Jika mengklaim kecenderungan, setidaknya tunjukkan penyebaran.

---

# Slide 30 - Contoh Workflow Analisis Data pada Eksperimen HCI

## Skenario: Menguji efek dua desain chatbot AI terhadap completion time dan trust

```
Dataset mentah: 30 partisipan × 2 kondisi = 60 baris
Variabel: participant_id, condition, order, completion_time,
          error_count, trust_score (Likert), open_comment

STEP 1 — Data cleaning
  • Cek missing (jika ada, dokumentasikan)
  • Cek outliers pada completion_time
  • Hapus trial di mana sistem gagal (misal network timeout)

STEP 2 — Descriptive statistics
  • Hitung M/SD untuk completion_time per kondisi
  • Hitung median/IQR untuk trust_score

STEP 3 — Assumption checks
  • Shapiro-Wilk untuk normalitas
  • Karena data tidak normal → pilih Wilcoxon signed-rank test

STEP 4 — Main analysis
  • Perbandingan completion_time: Wilcoxon test, effect size r
  • Perbandingan trust: Wilcoxon test

STEP 5 — Follow-up explanation
  • Buka open_comment → thematic analysis → jelaskan MENGAPA
```

---

# Slide 31 - Contoh Workflow Analisis Data Kualitatif pada Studi HCI

## Skenario: Mengeksplorasi pengalaman pengguna terhadap AI assistant

```
Data: 12 transkrip wawancara semi-terstruktur (total 480 menit)

STEP 1 — Transkripsi → familiarisasi
  • Baca transkrip berulang kali; catat memo awal

STEP 2 — Open coding
  • Kode label muncul dari data
  • Misal: "butuh konfirmasi visual", "ragu pada jawaban",
          "perlu mengulang pertanyaan", "merasa diawasi"

STEP 3 — Kelompokkan kode → calon tema
  • Calon tema: "verifikasi eksternal", "ketidaknyamanan
    karena AI yang terlalu personal"

STEP 4 — Review tema
  • Kembali ke data; pastikan tema konsisten
  • Gabungkan tema yang tumpang tindih

STEP 5 — Inter-rater check
  • Coder kedua mengkode 20% transkrip
  • Hitung Cohen's κ; jika < 0.6, perbaiki definisi kode

STEP 6 — Tulis narasi hasil + kutipan pendukung
```

---

# Slide 32 - Mengevaluasi Kualitas Evidence Anda

## Checklist Reflektif Sebelum Membuat Claim

| Pertanyaan | Sudah terpenuhi? |
|---|---|
| Apakah data sudah bersih dan terdokumentasi? | ☐ |
| Apakah analisis sesuai dengan tipe data dan desain penelitian? | ☐ |
| Apakah uji statistik memilih asumsi yang tepat (normalitas)? | ☐ |
| Apakah effect size dan CI dilaporkan, bukan hanya p-value? | ☐ |
| Apakah hasil kualitatif didukung kutipan yang memadai? | ☐ |
| Apakah ada triangulasi untuk temuan kunci? | ☐ |
| Apakah keterbatasan analisis diakui secara jujur? | ☐ |
| Apakah claim tidak melampaui apa yang data mampu dukung? | ☐ |
| Apakah Anda dapat menjelaskan bagaimana analisis direplikasi? | ☐ |

## Pertanyaan Pemantik

```
Jika reviewer bertanya:
"Apakah ada penjelasan alternatif untuk hasil Anda?"
Apakah Anda dapat menjawab dengan meyakinkan?
```

---

# Slide 33 - Hubungan Data Analysis dengan Pertemuan 14

## Validitas dan Evidence

- Pertemuan 13 menghasilkan **hasil analisis** — pertemuan 14 menanyakan: **seberapa valid hasil tersebut**?

## Jika Analisis Hari Ini Tidak Mempertimbangkan Validitas

```
Hasil signifikan yang tampak kuat
        ↓
ditinjau dari internal validity: mungkin ada order effect
ditinjau dari construct validity: instrumen mungkin tidak mengukur
apa yang dimaksud
ditinjau dari sampling bias: partisipan tidak representatif
→ kesimpulan yang prematur
```

## Oleh Karena Itu

> Pertemuan 13 dan 14 adalah **satu kesatuan**. Anda perlu memahami jenis analisis yang membentuk evidence dan sekaligus menyadari ancaman yang dapat melemahkan evidence tersebut (validity, bias, reproducibility, ethics). Ini akan dibahas lebih mendalam pada pertemuan berikutnya.

---

# Slide 34 - Pertemuan Berikutnya: Validity, Reproducibility & Research Ethics

## Yang Akan Dibahas pada Pertemuan 14

| Topik | Fokus |
|---|---|
| **Internal validity** | Apakah hubungan sebab-akibat benar-benar dapat diandalkan? |
| **External validity** | Apakah hasil dapat digeneralisasi? |
| **Construct validity** | Apakah instrumen mengukur konsep yang dimaksudkan? |
| **Ecological validity** | Apakah konteks penelitian mencerminkan dunia nyata? |
| **Confounding factors** | Variabel lain yang mengacaukan hasil |
| **Bias** | Sampling bias, selection bias, researcher bias |
| **Reproducibility** | Dapatkah orang lain mengulang prosedur Anda dan memperoleh hasil serupa? |
| **Research ethics** | Informed consent, privacy, human-subject protection |

## Pertanyaan Penghubung

> Jika data analysis hari ini adalah tentang **bagaimana** Anda menganalisis, pertemuan 14 adalah tentang **sejauh mana hasilnya dapat dipercaya** dan **dapat dipertanggungjawabkan** secara ilmiah dan etis.

---

# Slide 35 - Research Progress: Data Analysis dan Preliminary Findings

## Yang Perlu Anda Siapkan pada Minggu Ini

Sesuai RPS, setiap mahasiswa/kelompok menyampaikan **data analysis dan preliminary findings**.

## Format Progress yang Disarankan

| Komponen | Isi yang diharapkan |
|---|---|
| **Dataset status** | Jumlah partisipan, data yang valid, data yang dikeluarkan dan alasannya |
| **Analisis yang dilakukan** | Uji statistik / metode kualitatif yang dipilih dan alasan pemilihan |
| **Preliminary findings** | Hasil awal yang muncul (belum final) |
| **Kendala** | Kesulitan teknik analisis, kekurangan data, temuan tak terduga |
| **Keputusan** | Apakah analisis perlu diubah? Arah new analysis? |
| **Next action** | Langkah berikutnya: analisis lanjutan, konsultasi dosen, dsb. |

## Prinsip Presentasi Progress

> Sampaikan apa yang sudah Anda analisis, masalah yang ditemui, dan bagaimana Anda berencana menyelesaikannya. Bukan hanya menampilkan output statistik tanpa interpretasi.

---

# Slide 36 - Kaitan dengan Pertemuan 15: Dari Hasil ke Scientific Contribution

## Mengantisipasi Bagaimana Hasil Ini Menjadi Kontribusi

```
Pertemuan 13                    Pertemuan 15
Data Analysis                   Scientific Contribution
    ↓                                ↑
Result → Finding → Evidence → Claim → Contribution
```

## Berpikir Maju Sekarang

- **Apa finding utama yang nampak dari analisis Anda?**
- **Apakah finding tersebut cukup kuat untuk menjadi jawaban RQ?**
- **Kepada siapa finding itu berguna?** Desainer sistem? Peneliti HCI? Pengguna?
- **Apa arti temuan Anda bagi teori atau praktik desain?**

## Contoh Bentuk Kontribusi

1. **Empirical evidence**: data kuantitatif baru yang memperkaya literatur
2. **Design knowledge**: pemahaman tentang mengapa suatu teknik berhasil/gagal
3. **Methodological insight**: pelajaran tentang penggunaan metode di konteks tertentu
4. **Implications for design**: rekomendasi nyata bagi perancang sistem interaktif

---

# Slide 37 - Ringkasan Materi Pertemuan 13

## Konsep Kunci

| Area | Poin Utama |
|---|---|
| Alur evidence | Data → Result → Finding → Evidence → Claim |
| Data cleaning | Dokumentasikan setiap keputusan; jangan buang data tanpa alasan |
| Statistik deskriptif | M, median, SD, IQR — pilih sesuai distribusi dan skala |
| Inferensi | p-value saja tidak cukup; laporkan effect size dan CI |
| Uji komparasi | Sesuaikan uji dengan desain between/within dan normalitas |
| Kualitatif | Coding, codebook, thematic analysis, inter-rater agreement |
| Triangulasi | Semakin banyak sumber yang konvergen, semakin kuat evidence |
| Visualisasi | Jangan menyesatkan; tampilkan sebaran dan ketidakpastian |

## Prinsip Penutup

> Significance secara statistik adalah langkah pertama, bukan akhir. **Scientific significance dibangun oleh effect size yang bermakna, hasil yang konsisten, penjelasan alternatif yang telah disingkirkan, dan makna bagi komunitas.**

---

# Slide 38 - Penutup

TERIMA KASIH

Pertemuan berikutnya

**Validity, Reproducibility & Research Ethics**