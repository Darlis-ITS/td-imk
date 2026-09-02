# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer
Pertemuan 15
# From Results to Scientific Contribution

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D
Departemen Teknik Informatika - ITS

---

# Slide 01 - Posisi Pertemuan dalam Alur Penelitian HCI

```text
[13] Data Analysis
       ↓
[14] Validity, Reproducibility & Research Ethics
       ↓
[15] From Results to Scientific Contribution   ← Anda di sini
       ↓
[16] Final Research Presentation & Paper Defense
```

| Pertemuan Sebelumnya | Pertemuan Sekarang | Pertemuan Berikutnya |
|---|---|---|
| Hasil analisis sudah diperiksa validitasnya; limitations telah diidentifikasi | Hasil ditafsirkan menjadi temuan, lalu temuan diposisikan menjadi kontribusi ilmiah | Paper final dipresentasikan dan dipertahankan di depan penguji |

Pertemuan ini **tidak mengulang** cara melakukan uji statistik atau cara menilai validitas, melainkan menggunakannya untuk membangun narasi ilmiah.

---

# Slide 02 - Tujuan Pembelajaran dan Capaian

Setelah mengikuti pertemuan ini, mahasiswa diharapkan mampu:

- Membedakan **result**, **finding**, dan **scientific contribution**.
- Menginterpretasikan evidence secara hati-hati dalam konteks research question.
- Menyusun bagian **Discussion** yang menjawab research question dan membandingkannya dengan penelitian sebelumnya.
- Merumuskan **implications** untuk desain, teori, praktik, dan metodologi.
- Menulis **limitations** dan **future research** yang saling terhubung.
- Menulis paper HCI dengan struktur yang baik dari sudut pandang **reviewer**.
- Menentukan **publication venue** yang sesuai dan kredibel.

**Research progress minggu ini:** full paper draft, peer review, dan revisi.

---

# Slide 03 - Research Progress Minggu Ini

Posisi progress dalam satu semester:

| Minggu | Milestone |
|---|---|
| 13 | Data analysis dan preliminary findings |
| 14 | Results, threats to validity, limitations |
| **15** | **Full paper draft + peer review + revision** |
| 16 | Final paper + presentation + defense |

Format pelaporan progress:

```text
Progress → Evidence → Problem → Decision → Next Action
```

Contoh:

- **Progress:** Draft v1 paper selesai.
- **Evidence:** Draft telah dibaca oleh dua rekan peer reviewer.
- **Problem:** Review menemukan bahwa Discussion terlalu deskriptif dan klaim kontribusi belum eksplisit.
- **Decision:** Menambah sub-bagian “Scientific Contribution”, memperpendek Results, dan memperjelas jawaban terhadap RQ.
- **Next Action:** Mengirim draft v2 dan menyiapkan slide paper defense.

---

# Slide 04 - Peta Konsep: Results, Findings, Contribution

```text
+----------+   interpretasi    +----------+   synthesis     +------------+
| Results  | -----------------> | Findings | ---------------> |Contribution|
+----------+                    +----------+                 +------------+
   output                          insight                     knowledge
   analisis                        jawaban RQ                  bagi HCI
```

Dua lompatan utama yang menjadi fokus pertemuan ini:

1. **Results → Findings**  
   Apa arti hasil analisis dalam konteks research question?

2. **Findings → Contribution**  
   Mengapa pengetahuan ini penting bagi komunitas HCI?

Pertanyaan pemantik:

> *So what? Why does it matter? For whom? Compared to what? What do we now know that we did not know before?*

---

# Slide 05 - Result vs Finding

**Result** adalah keluaran langsung dari analisis data.

**Finding** adalah pernyataan pengetahuan yang diperoleh setelah hasil diinterpretasikan dalam konteks RQ, teori, dan evidence lain.

| Result | Finding |
|---|---|
| `F(1,38)=6.17, p=.018, ηp²=.14` | Ringkasan otomatis mempercepat penyelesaian tugas pencarian item di layar ponsel. |
| Tema “ragu pada penjelasan AI” muncul pada 12 dari 15 partisipan | Partisipan membutuhkan penjelasan tingkat keputusan, bukan sekadar gambaran umum cara kerja AI. |

Prinsip:

> Results are reported. Findings are argued.

Result umumnya berada di bagian Results; finding dikembangkan di bagian Discussion.

---

# Slide 06 - Finding vs Contribution

**Finding** adalah insight spesifik dari studi Anda.

**Contribution** adalah pengetahuan yang dapat digunakan, diuji, atau diperdebatkan oleh komunitas HCI.

| Finding | Contribution |
|---|---|
| Pengguna lebih percaya pada AI ketika AI menampilkan confidence score. | Memberikan bukti empiris bahwa komunikasi ketidakpastian model berperan dalam kalibrasi kepercayaan pengguna. |
| Pengguna menyelesaikan tugas lebih cepat dengan ringkasan otomatis pada layar kecil. | Menghasilkan design knowledge bahwa ringkasan otomatis dapat mengurangi beban pencarian informasi pada konteks layar terbatas. |

Perbedaan kunci:

- Finding menjawab: *“Apa yang kami temukan?”*
- Contribution menjawab: *“Mengapa temuan ini berharga bagi komunitas HCI?”*

---

# Slide 07 - Dari Evidence ke Knowledge

Evidence yang baik harus melalui proses interpretasi:

```text
Evidence + Interpretation + Research Context + Relevant Literature
                  ↓
         Claim / Finding / Knowledge
```

Hal-hal yang harus dipertimbangkan:

- Seberapa kuat evidence? (validitas, bias, desain studi)
- Siapa partisipannya? Dalam konteks apa?
- Teknologi/sistem apa yang digunakan?
- Apakah ada penjelasan alternatif?
- Bagaimana temuan berhubungan dengan penelitian sebelumnya?

Peringatan dari pertemuan 14:

> Evidence yang tidak valid dapat menghasilkan finding yang menyesatkan, meskipun ditulis dengan bahasa yang meyakinkan.

---

# Slide 08 - Interpretasi Evidence: Statistik Bukan Kesimpulan

**Statistical significance bukan scientific significance.**

Contoh hasil:

```text
Antarmuka A: M = 42.1 detik
Antarmuka B: M = 44.3 detik
p = .04
```

Interpretasi yang belum memadai:

> Antarmuka A lebih baik daripada B.

Interpretasi yang lebih ilmiah perlu mempertimbangkan:

- Effect size dan confidence interval.
- Konteks tugas: apakah selisih 2,2 detik bermakna untuk penggunaan sekali-sekali atau untuk tugas berulang?
- Apakah variabel lain ikut berubah, seperti error rate dan beban kognitif.
- Apakah hasil konsisten dengan data kualitatif.

Fokus pertemuan 15 bukan pada angka, melainkan pada **makna ilmiah**.

---

# Slide 09 - Checklist Interpretasi Evidence

Gunakan checklist berikut saat menulis Discussion:

- [ ] Apakah temuan benar-benar menjawab research question?
- [ ] Apakah saya melaporkan ukuran efek, bukan hanya nilai p?
- [ ] Apakah saya menghindari frasa “tidak ada efek” ketika hasilnya hanya tidak signifikan secara statistik?
- [ ] Apakah saya mempertimbangkan penjelasan alternatif seperti learning effect, demand characteristics, atau novelty effect?
- [ ] Apakah saya membedakan antara temuan yang kuat dan temuan yang bersifat eksploratif?
- [ ] Apakah saya menyesuaikan klaim dengan desain penelitian, misalnya korelasional vs eksperimental?
- [ ] Apakah saya menghubungkan evidence dengan teori atau temuan sebelumnya?

Checklist ini membantu Anda berpindah dari hasil menjadi temuan secara bertanggung jawab.

---

# Slide 10 - Menjawab Research Questions

Research question adalah jangkar Discussion.

Untuk setiap RQ, kembangkan empat lapis jawaban:

| Pertanyaan | Penjelasan |
|---|---|
| **What?** | Ringkasan evidence utama dari data. |
| **So what?** | Apa makna temuan bagi pengguna, desain, atau teori? |
| **Why?** | Mekanisme atau kondisi apa yang menjelaskan temuan? |
| **Where next?** | Implikasi apa yang muncul untuk praktik atau penelitian lanjutan? |

Prinsip penting:

> Discussion bukan mengulang tabel Results. Discussion mengintegrasikan hasil untuk menjawab RQ.

Jika penelitian Anda memiliki dua RQ, jawablah masing-masing secara eksplisit.

---

# Slide 11 - Latihan: Petakan Hasil ke Research Question

Isi tabel berikut untuk project Anda:

| Komponen | Isian |
|---|---|
| Research question utama | ... |
| Results summary | ... |
| Finding | ... |
| Kekuatan evidence | ... |
| Tentative contribution | ... |

Contoh ilustrasi:

| Komponen | Isian |
|---|---|
| RQ | Bagaimana pengguna menilai transparansi AI ketika terjadi konflik rekomendasi? |
| Results | 10 dari 14 partisipan menyebut “alasan di balik rekomendasi” sebagai faktor keputusan. |
| Finding | Pengguna lebih percaya ketika AI menjelaskan alasan, bukan hanya menampilkan skor keyakinan. |
| Kekuatan evidence | Kualitatif; perlu triangulasi dengan data perilaku. |
| Tentative contribution | Design knowledge untuk komunikasi transparansi pada AI asisten. |

Tugas mandiri: tulis jawaban RQ utama dalam 4–5 kalimat tanpa mencantumkan satu angka pun.

---

# Slide 12 - Discussion Section: Fungsi dan Isi

Fungsi Discussion:

- Menjawab research question.
- Menafsirkan evidence.
- Membandingkan dengan penelitian sebelumnya.
- Menjelaskan mekanisme atau alasan di balik temuan.
- Menyatakan implikasi dan kontribusi ilmiah.
- Menjelaskan limitations dan agenda penelitian lanjutan.

Kerangka umum:

```text
Discussion:
1. Pertanyaan penelitian dan jawaban utama
2. Perbandingan dengan prior work
3. Penjelasan pola dan mekanisme
4. Implications: design / theory / practice / method
5. Limitations
6. Future research
7. Pernyataan kontribusi ilmiah
```

Results menjelaskan *apa yang terjadi*; Discussion menjelaskan *mengapa itu terjadi dan mengapa itu penting*.

---

# Slide 13 - Pola Penalaran Discussion: What, Why, So What

Gunakan pola penalaran berikut:

```text
What    : hasil utama
   ↓
Why     : penjelasan mekanisme/kondisi
   ↓
So What : kontribusi dan implikasi
```

Contoh:

| Lapisan | Contoh narasi |
|---|---|
| **What** | Waktu penyelesaian tugas lebih cepat ketika ringkasan otomatis tersedia. |
| **Why** | Ringkasan mengurangi kebutuhan membuka banyak halaman dan menurunkan beban scanning visual. |
| **So What** | Desainer aplikasi mobile dapat menggunakan ringkasan otomatis untuk tugas pencarian item yang diketahui, tetapi perlu menguji akurasi ringkasan agar tidak menyesatkan. |

Pola ini membantu Anda menulis paragraf yang padat dan bernilai ilmiah.

---

# Slide 14 - Comparison with Previous Research

Discussion harus memosisikan temuan Anda terhadap penelitian sebelumnya.

Fungsi perbandingan:

- Menunjukkan kesinambungan dan kebaruan.
- Menjelaskan perbedaan hasil.
- Menunjukkan kontribusi terhadap state of the art.
- Mencegah klaim yang berlebihan.

Jenis perbandingan:

| Jenis | Contoh pola pikir |
|---|---|
| **Sejalan / memperluas** | Temuan kami mendukung penelitian X dan memperluasnya ke konteks ... |
| **Berbeda** | Tidak seperti penelitian X, kami tidak menemukan ... |
| **Menjelaskan perbedaan** | Perbedaan ini mungkin terjadi karena partisipan, tugas, atau teknologi yang digunakan berbeda. |
| **Memberi penjelasan alternatif** | Temuan X dapat juga dijelaskan oleh ... |

Bandingkan dengan paper yang paling dekat secara masalah, metode, atau teori, bukan semua paper di Related Work.

---

# Slide 15 - Matriks Perbandingan Penelitian

Gunakan tabel untuk memetakan prior work secara ringkas sebelum menulis Discussion:

| Aspek | Prior Work P1 | Prior Work P2 | Studi Anda |
|---|---|---|---|
| Konteks/tugas | Chatbot customer service | Voice assistant | AI asisten pada dashboard |
| Metode | Eksperimen | Studi wawancara | Mixed-methods |
| Temuan utama | Kecepatan respons meningkatkan kepuasan | Kejelasan suara memengaruhi kepercayaan | Penjelasan alasan memengaruhi trust |
| Hubungan dengan studi Anda | Sejalan, tapi belum pada AI asisten | Berbeda metode, hasil konsisten | Mengisi gap pada konteks AI asisten |

Tabel ini membantu Anda menemukan posisi studi Anda secara visual.

Setelah tabel tersusun, tulis paragraf sintesis yang menjelaskan posisi penelitian dalam beberapa kalimat.

---

# Slide 16 - Implications for Design

**Implication for design** adalah rekomendasi desain yang didukung langsung oleh evidence.

Rumus penulisan:

> Ketika kondisi X, perancang sebaiknya mempertimbangkan Y, karena Z.

Contoh ilustrasi:

- **Kondisi:** AI menunjukkan keyakinan rendah terhadap jawabannya.
- **Rekomendasi:** Tampilkan opsi untuk meminta klarifikasi, bukan hanya probabilitas.
- **Alasan:** Pengguna dapat menghindari kepercayaan berlebih dan tahu kapan harus campur tangan.

Implication for design yang baik:

- Bersifat actionable.
- Berasal dari finding, bukan opini umum.
- Dapat diterapkan oleh desainer atau pengembang.
- Menyebutkan batas kondisi ketika rekomendasi berlaku.

---

# Slide 17 - Implications for Theory

**Implication for theory** menjelaskan bagaimana temuan memperkaya, merevisi, atau menantang konsep teoretis dalam HCI.

Contoh bentuk kontribusi teoretis:

- Memperluas model trust calibration ke konteks chat AI.
- Memberikan bukti bahwa konstruk *explainability* berbeda dengan *transparency* dalam persepsi pengguna.
- Menantang asumsi bahwa feedback visual selalu cukup untuk membangun mental model.
- Memberikan proposisi baru tentang kapan *automation bias* muncul.

Contoh kalimat:

> Temuan kami menambah nuansa pada teori beban kognitif dengan menunjukkan bahwa ringkasan otomatis mengurangi eksternal load, tetapi hanya jika ringkasan akurat.

Hindari klaim berlebihan seperti *“teori ini terbukti”*. Gunakan: *“mendukung”, “memperluas”, “menantang”*.

---

# Slide 18 - Practical Implications

**Practical implications** berfokus pada kebijakan, proses, atau praktik profesional di luar penelitian.

Contoh audiens:

- Product manager.
- UX researcher di industri.
- Developer AI.
- Pengambil kebijakan.

Contoh ilustrasi:

| Temuan | Practical implication |
|---|---|
| Pengguna ragu ketika AI memberikan jawaban tanpa alasan. | Perusahaan chatbot sebaiknya menyediakan mekanisme transfer ke manusia setelah beberapa kali jawaban tidak memuaskan. |
| Pengguna lansia kesulitan dengan gesture kompleks. | Pedoman QA aplikasi sebaiknya mencakup uji aksesibilitas dengan pengguna lansia, bukan hanya pengguna muda. |

Practical implication harus tetap berakar pada evidence dan tidak berubah menjadi saran manajemen umum.

---

# Slide 19 - Methodological Implications

**Methodological implications** memberi tahu peneliti HCI cara meningkatkan penelitian berikutnya.

Contoh:

- Skala self-report trust tunggal kurang sensitif; gunakan kombinasi subjective rating dan behavioral measure.
- Think-aloud dapat mengganggu performa pada tugas berbasis waktu; pertimbangkan retrospective think-aloud.
- Prosedur counterbalancing perlu mempertimbangkan efek latihan pada tugas AI yang kompleks.
- Instrumen, dataset, atau analysis script dapat dibagikan peneliti lain untuk replikasi.

Contoh kalimat:

> Penelitian selanjutnya sebaiknya mengukur kepercayaan tidak hanya melalui kuesioner, tetapi juga melalui perilaku pengguna ketika mengikuti atau menolak rekomendasi AI.

Kontribusi metodologis tidak harus selalu berupa metode baru; bisa berupa prosedur adaptasi dari metode yang sudah ada.

---

# Slide 20 - Scientific Contribution: Definisi dan Kriteria

**Scientific contribution** adalah pengetahuan baru yang valid, eksplisit, dan berguna bagi komunitas HCI.

Kriteria kontribusi ilmiah:

1. **Novelty**  
   Pengetahuan belum diketahui atau belum dibuktikan sebelumnya.

2. **Evidential basis**  
   Klaim didukung oleh data dan desain studi yang valid.

3. **Significance**  
   Pengetahuan menarik bagi komunitas peneliti, desainer, atau praktisi.

4. **Generality**  
   Meskipun terikat konteks, kontribusi memiliki daya jelaskan di luar satu sistem tertentu.

5. **Clarity**  
   Pembaca dapat menyatakan kontribusi dalam satu atau dua kalimat.

Kontribusi bukan:

- “Sistem kami bekerja.”
- “Skor akurasi model lebih tinggi.”
- “Pengguna lebih suka sistem kami.”

Kontribusi adalah **pengetahuan yang dihasilkan dari sistem/studi tersebut**.

---

# Slide 21 - Bentuk Kontribusi Ilmiah dalam HCI

Kontribusi dapat berwujud beragam:

| Bentuk Kontribusi | Pertanyaan kunci |
|---|---|
| New understanding | Apa yang sekarang lebih kita pahami? |
| Empirical evidence | Data apa yang dapat digunakan peneliti lain? |
| Interaction technique | Teknik interaksi baru seperti apa yang valid dan berguna? |
| Design knowledge / implications | Prinsip desain apa yang dapat diadopsi? |
| Method | Metode penelitian atau instrumen apa yang dapat digunakan ulang? |
| System / tool | Artefak apa yang membuka riset atau praktik baru? |
| Dataset | Data apa yang dapat direplikasi/dianalisis ulang? |
| Framework / model | Kerangka konseptual apa yang menjelaskan fenomena? |
| Theory | Teori mana yang diperluas atau direvisi? |

Prototype adalah sarana penelitian, bukan otomatis kontribusi ilmiah.

---

# Slide 22 - Peringatan Kunci

> **System Novelty ≠ Research Novelty**

> **Prototype ≠ Scientific Contribution**

> **Performance Improvement ≠ Scientific Contribution**

Penjelasan:

- Sistem baru yang belum pernah ada mungkin menarik secara engineering, tetapi kontribusi HCI harus menjelaskan apa yang dipelajari tentang interaksi manusia-komputer.
- Prototype perlu diartikulasikan sebagai teknik, design knowledge, atau bukti empiris.
- “Model AI lebih akurat 5%” tidak otomatis menjadi temuan HCI.  
  Pertanyaan HCI muncul ketika perubahan akurasi memengaruhi kepercayaan, perilaku, beban kerja, atau keputusan pengguna.

Gunakan sistem sebagai *research instrument*, bukan sebagai tujuan akhir.

---

# Slide 23 - Menulis Klaim Kontribusi yang Dapat Dipertahankan

Tulis klaim kontribusi secara eksplisit di dalam paper.

Formula:

> Penelitian ini memberikan kontribusi berupa **[bentuk kontribusi]** berupa **[isi kontribusi]**, yang ditunjukkan oleh **[evidence]**, dan berguna untuk **[audiens/konteks]**.

Contoh:

> Penelitian ini memberikan kontribusi berupa design knowledge untuk antarmuka AI asisten. Berdasarkan studi eksperimental dengan 40 pengguna, kami menunjukkan bahwa menampilkan alasan keputusan — bukan hanya skor keyakinan — meningkatkan kalibrasi kepercayaan saat rekomendasi AI tidak akurat. Pengetahuan ini dapat digunakan oleh perancang sistem conversational AI dan peneliti human-AI interaction.

Klaim seperti ini lebih mudah dinilai kebenarannya oleh reviewer dibandingkan *“kami membangun aplikasi X.”*

---

# Slide 24 - Limitations: Batas Klaim

Limitations menjelaskan **sejauh mana** temuan dan kontribusi berlaku.

Fungsi limitations:

- Membantu pembaca menilai generalisasi.
- Menjaga kejujuran ilmiah.
- Memberikan dasar untuk future research.
- Menunjukkan bahwa peneliti memahami keterbatasan desain studinya.

Referensi kategori dari pertemuan 14:

| Jenis | Fokus |
|---|---|
| Internal validity | Apakah hubungan sebab-akibat kuat? |
| External validity | Apakah hasil dapat digeneralisasi ke populasi/konteks lain? |
| Construct validity | Apakah instrumen benar-benar mengukur konstruk yang dimaksud? |
| Ecological validity | Apakah kondisi studi mewakili penggunaan nyata? |

Limitations dipilih yang paling relevan terhadap RQ, bukan semua kelemahan yang mungkin ada.

---

# Slide 25 - Menulis Limitations yang Jujur dan Informatif

| Lemah | Lebih informatif |
|---|---|
| Jumlah sampel kecil. | Dengan jumlah partisipan 24 dan effect size sebesar ini, studi memiliki keterbatasan untuk mendeteksi efek kecil. Hasil utama perlu direplikasi pada sampel yang lebih beragam. |
| Studi dilakukan di laboratorium. | Tugas yang diberikan bersifat artifisial; perilaku pengguna di lapangan mungkin berbeda karena motivasi dan gangguan yang nyata. |
| Partisipan adalah mahasiswa. | Kontribusi dibatasi pada pengguna dewasa muda yang terbiasa dengan teknologi; belum dapat digeneralisasi ke lansia tanpa studi lanjutan. |

Prinsip:

> Limitations tidak membatalkan kontribusi. Limitations membatasi klaim dengan jujur sehingga kontribusi tetap dapat dipercaya.

---

# Slide 26 - Future Research: Dari Limitasi ke Agenda

Future research harus berhubungan langsung dengan limitations atau temuan yang tidak terduga.

Rumus penulisan:

> Penelitian selanjutnya dapat **[tindakan]** karena **[alasan dari studi ini]**.

Contoh:

- Karena partisipan studi ini adalah pengguna dewasa muda, penelitian lanjutan dapat menguji desain yang sama pada pengguna lansia.
- Karena temuan kualitatif menunjukkan pentingnya alasan, studi kuantitatif berikutnya dapat mengukur efek jenis penjelasan terhadap trust calibration.
- Karena efek baru terlihat pada tugas kompleks, studi longitudinal di lapangan diperlukan untuk memahami adaptasi jangka pendek dan jangka panjang.

Hindari:

> *“Perlu penelitian lebih lanjut.”*

Tuliskan arah, alasan, dan desain yang mungkin.

---

# Slide 27 - Academic Writing: Prinsip Dasar

Prinsip utama penulisan akademik:

- **Clear** — pembaca tidak perlu menebak makna kalimat.
- **Precise** — gunakan angka, konteks, dan istilah yang tepat.
- **Coherent** — setiap paragraf terhubung secara logis.
- **Critical** — klaim sesuai kekuatan evidence.
- **Honest** — akui keterbatasan dan alternatif penjelasan.

Struktur paragraf argumentatif:

```text
1. Topic sentence  : pernyataan utama.
2. Evidence        : data atau hasil yang mendukung.
3. Warrant         : penjelasan hubungan evidence dan klaim.
4. Link            : keterkaitan dengan RQ, literature, atau paragraf berikutnya.
```

Tulis draft pertama untuk berpikir, lalu revisi untuk berkomunikasi.

---

# Slide 28 - Menghindari Overclaim dan Bahasa Ambigu

Contoh perbaikan bahasa:

| Hindari | Gunakan |
|---|---|
| The experiment proved that ... | The results suggest that ... in the context of ... |
| System A is better than System B. | In this study, System A led to fewer errors under time pressure. |
| Users liked the AI. | Participants reported higher satisfaction when the AI explained its reasoning. |
| There was no effect. | We did not detect a statistically significant difference with the current sample size. |
| The system is user-friendly. | Participants completed all tasks without external assistance. |

Kata *significant* bermakna ganda:

- statistical significance
- practical / scientific significance

Jelaskan makna yang Anda maksud secara eksplisit.

---

# Slide 29 - HCI Paper Structure

Struktur umum paper HCI yang banyak digunakan:

| Section | Pertanyaan yang dijawab |
|---|---|
| Abstract | Apa masalah, metode, hasil utama, dan kontribusi? |
| Introduction | Mengapa masalah penting? Apa gap dan RQ? Apa kontribusi? |
| Related Work | Apa yang sudah diketahui? Bagaimana paper memposisikan diri? |
| Method | Bagaimana evidence dikumpulkan? |
| Results | Apa yang diamati/ditemukan secara langsung? |
| Discussion | Apa makna hasil? Mengapa penting? |
| Limitations & Future Work | Apa batas klaim? Ke mana penelitian berlanjut? |
| Conclusion | Pesan utama yang ingin diingat pembaca? |

Abstract dan introduction umumnya ditulis setelah bagian inti selesai.

---

# Slide 30 - Di Mana Kontribusi Dibangun di Setiap Bagian

| Section | Peran terhadap kontribusi |
|---|---|
| Introduction | Menjanjikan kontribusi dan menunjukkan gap. |
| Related Work | Menunjukkan bahwa kontribusi belum ada. |
| Method | Menjelaskan bagaimana kontribusi diperoleh secara valid. |
| Results | Menyediakan evidence mentah. |
| Discussion | Menafsirkan evidence dan menyatakan kontribusi secara eksplisit. |
| Conclusion | Menyampaikan kontribusi secara ringkas. |

Reviewer akan mengecek:

> Apakah kontribusi yang dijanjikan di introduction benar-benar dibuktikan di Discussion?

Pastikan tidak ada janji kontribusi yang tidak dipenuhi.

---

# Slide 31 - Reviewer Perspective

Reviewer membaca paper dengan pertanyaan besar:

> *“What do we learn from this study and why does it matter for HCI?”*

Pertanyaan rinci yang sering digunakan reviewer:

- Apakah research problem jelas dan penting?
- Apakah state of the art dipahami dengan baik?
- Apakah research gap benar-benar ada dan bukan buatan?
- Apakah research question terjawab?
- Apakah metode sesuai untuk pertanyaan tersebut?
- Apakah evidence cukup kuat untuk klaim?
- Apakah kontribusi dinyatakan dengan jelas dan tidak berlebihan?
- Apakah penulisan mudah diikuti?

Reviewer bukan hanya menilai benar-salah, tetapi menilai **nilai ilmiah** dan **ketelitian**.

---

# Slide 32 - Rubrik Menilai Manuscript

Gunakan rubrik berikut untuk self-review atau peer review:

| Aspek | Pertanyaan |
|---|---|
| Research problem | Apakah masalah penting bagi HCI? |
| Related work | Apakah gap diposisikan secara kritis? |
| RQ | Apakah RQ spesifik dan dapat dijawab? |
| Method | Apakah desain studi sesuai dengan RQ? |
| Evidence | Apakah data dan analisis mendukung klaim? |
| Discussion | Apakah interpretasi menjawab RQ dan membandingkan dengan prior work? |
| Contribution | Apakah kontribusi ilmiah dinyatakan dan dipertahankan? |
| Writing | Apakah struktur dan bahasa jelas? |

Jika salah satu aspek lemah, revisi sebelum mengirim ke venue.

---

# Slide 33 - Peer Review dan Proses Revisi

Langkah peer review yang dilakukan di kelas:

1. Baca paper dua kali: pertama untuk kesan umum, kedua untuk detail.
2. Tulis ringkasan satu paragraf: apa masalah, gap, metode, hasil, dan kontribusi.
3. Identifikasi major issues: masalah pada RQ, metodologi, evidence, atau klaim.
4. Identifikasi minor issues: kejelasan, struktur, gaya, referensi.
5. Berikan saran perbaikan yang spesifik dan konstruktif.

Ketika menerima review:

- Jawab per poin secara profesional.
- “Kami setuju; kami menambahkan ...” atau “Kami kurang setuju karena ...; untuk memperjelas, kami menulis ulang ...”
- Jangan bersikap defensif.
- Gunakan review untuk memperkuat argumentasi ilmiah.

---

# Slide 34 - Selecting Publication Venue

Sebelum submit, evaluasi kecocokan venue:

| Pertimbangan | Pertanyaan |
|---|---|
| Scope | Apakah topik paper sesuai dengan area venue? |
| Audience | Siapa peserta/ pembaca venue tersebut? |
| Type | Conference, journal, atau workshop? |
| Review process | Apakah peer review jelas dan ketat? |
| Timeline | Apakah deadline sesuai dengan jadwal Anda? |
| Indexing | Apakah proceeding/jurnal terindeks Scopus atau database bereputasi? |

Venue HCI internasional yang relevan antara lain konferensi ACM SIGCHI seperti CHI, CSCW, IUI, DIS, MobileHCI, dan UIST, serta jurnal HCI terindeks.

Pilih venue berdasarkan topik, bukan hanya popularitas.

---

# Slide 35 - Menilai Kredibilitas Venue

Indikator venue yang sehat:

- Memiliki program committee/editorial board yang jelas.
- Melakukan peer review dengan proses yang transparan.
- Memberikan DOI pada paper.
- Proceeding/jurnal tersedia secara arsip.
- Biaya publikasi dijelaskan secara terbuka.
- Memiliki reputasi baik di komunitas HCI.

Alat bantu yang dapat digunakan:

| Alat | Fungsi |
|---|---|
| CORE ranking | Peringkat konferensi ilmu komputer. |
| Scopus / ScienceDirect | Cakupan dan kualitas jurnal/proceeding. |
| Daftar ACM/IEEE | Kredibilitas publisher. |

Hati-hati terhadap venue predator yang menjanjikan publikasi cepat tanpa review yang bermakna.

---

# Slide 36 - Checklist Akhir Draft Paper

Sebelum mengirim draft untuk presentasi pertemuan 16, pastikan:

```text
[ ] Judul mencerminkan isi dan kontribusi.
[ ] Abstrak menyatakan masalah, gap, RQ, metode, hasil utama, dan kontribusi.
[ ] Introduction berakhir dengan kontribusi eksplisit.
[ ] Related Work memposisikan gap penelitian.
[ ] Method cukup rinci untuk direplikasi.
[ ] Results menyajikan evidence, bukan hanya output statistik.
[ ] Discussion menjawab RQ dan membahas makna.
[ ] Implikasi (design/theory/practice/method) ditulis dengan jelas.
[ ] Limitations dan future research saling terhubung.
[ ] Referensi konsisten dan relevan.
[ ] Paper telah dibaca ulang dan mendapat peer review.
[ ] Klaim kontribusi tidak melebihi evidence.
```

Gunakan checklist ini sebagai alat self-review akhir.

---

# Slide 37 - Rangkuman: Dari Results Menuju Scientific Contribution

Perjalanan intellectual pertemuan 15:

```text
Results      → output analisis
   ↓
Evidence     → results yang valid dan dapat diandalkan
   ↓
Findings     → interpretasi evidence dalam konteks RQ
   ↓
Discussion   → menjawab RQ, membandingkan, menjelaskan
   ↓
Implications → design, theory, practice, method
   ↓
Contribution → pengetahuan baru bagi komunitas HCI
```

Pertemuan 15 adalah jembatan antara penelitian yang dilakukan dan paper yang akan dipertahankan.

Pada pertemuan 16, Anda akan diminta mempertanggungjawabkan tidak hanya hasil, tetapi juga **interpretasi, kontribusi, dan keterbatasannya**.

---

# Slide 38 - Penutup

TERIMA KASIH

Pertemuan berikutnya

**Final Research Presentation & Paper Defense**