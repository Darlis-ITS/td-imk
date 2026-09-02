# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer

Pertemuan 01

## Modern HCI & Research Landscape

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D

Departemen Teknik Informatika - ITS

---

# Slide 01 - Tujuan Pembelajaran dan Capaian

### Setelah mengikuti pertemuan ini, Anda diharapkan mampu

- Menjelaskan evolusi HCI dari sistem komputasi awal menuju interaksi modern.
- Membedakan konsep Usability, User Experience, dan Human-Centered Computing.
- Menjelaskan HCI sebagai bidang multidisiplin dan paradigma interaksi.
- Memetakan research landscape HCI modern, termasuk Human-AI Interaction dan Generative AI.
- Membedakan **interface development** dan **HCI research** beserta bentuk kontribusi ilmiahnya.

### Capaian yang terkait

- CPMK-1: menganalisis konsep, teori, dan perkembangan modern HCI.
- CPMK-7: menganalisis perkembangan mutakhir dan research frontier HCI.
- Research Progress minggu ini: menentukan **research interest**.

### Catatan alur

- Pertemuan ini menjadi fondasi untuk pertemuan 2 hingga 16.

---

# Slide 02 - Posisi Pertemuan dalam Pipeline Penelitian

- Mata kuliah ini dirancang sebagai satu pipeline penelitian:

```
[Pertemuan 1] Modern HCI & Research Landscape
      ↓
[Pertemuan 2] Human-Centered Design & Interaction Principles
      ↓
...
[Pertemuan 16] Final Research Presentation & Paper Defense
```

- Pertemuan ini: membangun pemahaman tentang posisi HCI modern dan arah riset HCI.
- Berikutnya: prinsip human-centered design akan digunakan sebagai lensa untuk melihat interaction problem.

- Keseluruhan arah course:

```
Concept → Literature → Gap → RQ → Method → Study → Evidence → Contribution
```

- Oleh karena itu, topik hari ini bukan hanya teori, tetapi juga peta perjalanan penelitian Anda.

---

# Slide 03 - Apa Itu Human-Computer Interaction?

- HCI adalah studi tentang bagaimana manusia menggunakan, memahami, merancang, dan dipengaruhi oleh sistem komputasi.
- HCI tidak hanya soal antarmuka, tetapi juga konteks, kognisi, perilaku, dan nilai-nilai manusia.

### Unit analisis HCI

| Komponen | Penjelasan |
|---|---|
| Human | pengguna dengan kemampuan, keterbatasan, kebutuhan, nilai, dan tujuan |
| Computer/Technology | sistem interaktif, aplikasi, perangkat, layanan, hingga AI |
| Task | tujuan yang ingin dicapai pengguna |
| Context | lingkungan fisik, sosial, organisasional, dan budaya |

- Interaksi terjadi ketika keempat komponen tersebut saling memengaruhi.
- Pertanyaan HCI sering muncul ketika terjadi ketidakcocokan antar komponen.

---

# Slide 04 - Evolusi HCI: Dari Mesin ke Ekosistem Digital

```
1940–1960    Batch processing, mainframe        Pakar teknis, belum ada user interface
1960–1970    Time-sharing, terminal             Perluasan akses pengguna
1970–1980    Personal computing                 Pengguna non-teknis mulai berinteraksi
1980–1990    GUI, mouse, WIMP                   Manipulasi langsung
1990–2000    Web, mobile awal                   Interaksi jarak jauh
2000–2010    Search, social, smartphone         Interaksi berbasis ekosistem digital
2010–2020    Touch, voice, wearable, cloud      Interaksi multimodal dan kontekstual
2020–        XR, Human-AI interaction, GenAI    Sistem adaptif dan generatif
```

- Setiap era melahirkan tantangan interaksi baru.
- Fokus bergeser dari perangkat keras ke perangkat lunak, lalu ke pengalaman dan konteks kehidupan manusia.

---

# Slide 05 - Pergeseran Fokus: Usability → UX → Human-Centered Computing

- **Usability** bertanya: apakah tugas dapat diselesaikan dengan efektif, efisien, dan memuaskan?
- **User Experience (UX)** bertanya: bagaimana perasaan, makna, dan penilaian pengguna terhadap keseluruhan interaksi?
- **Human-Centered Computing (HCC)** menempatkan kebutuhan, kemampuan, dan konteks manusia sebagai titik tolak pengembangan teknologi.

```
Usability ⊂ User Experience ⊂ Human-Centered Computing
```

- Level yang lebih luas tidak menghapus level sebelumnya, tetapi memperluas fokus.

### Contoh pergeseran pertanyaan

1. Apakah pengguna berhasil menyelesaikan formulir?
2. Apakah pengguna merasa nyaman dan tetap memiliki kendali?
3. Apakah teknologi ini layak digunakan dalam konteks sosial tanpa merugikan kelompok tertentu?

---

# Slide 06 - Empat Pilar HCI: Usability, UX, HCC, Interaction Design

| Konsep | Objek Perhatian | Pertanyaan Kunci |
|---|---|---|
| Usability | Kemudahan penggunaan dalam tugas | Seberapa efektif, efisien, dan memuaskan? |
| User Experience | Pengalaman subjektif pengguna | Apa yang dirasakan, dipahami, dan dihargai pengguna? |
| Interaction Design | Perilaku sistem dan bentuk dialog | Bagaimana sistem seharusnya merespons pengguna? |
| Human-Centered Computing | Integrasi manusia, teknologi, dan konteks | Bagaimana komputasi dapat melayani manusia? |

- Keempat konsep tidak selalu berdiri sendiri; dalam penelitian HCI sering digunakan secara bersama-sama.
- Pertemuan 2 akan membahas prinsip-prinsip human-centered design dan interaction design secara lebih mendalam.

---

# Slide 07 - Usability sebagai Fondasi Kualitas Interaksi

- Usability berkaitan dengan:
  - **efektivitas**: akurasi dan kelengkapan tercapainya tujuan;
  - **efisiensi**: sumber daya yang diperlukan;
  - **kepuasan**: kenyamanan dan penerimaan pengguna.
- Atribut yang sering digunakan:
  - learnability;
  - efficiency;
  - memorability;
  - errors;
  - satisfaction.
- Dalam penelitian HCI, usability diukur menggunakan data perilaku dan persepsi.

### Contoh ukuran usability

```
task completion rate
time on task
error rate
System Usability Scale (SUS)
```

- Evaluasi usability dan UX akan dibahas lebih lanjut pada pertemuan 9.

---

# Slide 08 - User Experience (UX): Melampaui Keberhasilan Tugas

- UX mencakup aspek yang lebih luas:
  - emosi: senang, frustrasi, cemas;
  - makna: mengapa produk penting bagi pengguna;
  - estetika dan kesan pertama;
  - kepercayaan dan kredibilitas;
  - identitas sosial dan nilai personal.
- UX bersifat:
  - **subjektif**: bergantung pada individu;
  - **temporal**: berubah seiring waktu penggunaan;
  - **kontekstual**: dipengaruhi situasi dan lingkungan.

### Implikasi untuk riset

- Jangan hanya mengukur kecepatan dan kesalahan.
- Gunakan instrumen self-report, observasi, dan wawancara.
- Hubungkan ukuran objektif dengan pengalaman subjektif pengguna.

---

# Slide 09 - Human-Centered Computing (HCC): Manusia sebagai Titik Pusat

- HCC lahir dari pandangan bahwa masalah komputasi pada dasarnya adalah masalah manusia.
- Manusia tidak hanya dilihat sebagai “user”, tetapi sebagai aktor yang memiliki tujuan, relasi sosial, dan konteks budaya.
- HCC menggabungkan:
  - ilmu komputer;
  - psikologi dan kognisi;
  - sosiologi dan antropologi;
  - desain;
  - human factors.

- Dari HCC muncul perhatian pada nilai-nilai manusia: aksesibilitas, privasi, keadilan, dan keberlanjutan.
- Riset HCI modern tidak berhenti pada performa sistem, tetapi mempertanyakan bagaimana teknologi hidup bersama manusia.

---

# Slide 10 - Interaction Design: Merancang Dialog, Bukan Sekadar Tampilan

- Interaction design (IxD) berfokus pada **perilaku sistem** selama berinteraksi dengan pengguna.

### Contoh keputusan interaction design

- Bagaimana sistem memberikan umpan balik?
- Bagaimana pengguna membatalkan tindakan?
- Mode input dan output apa yang tersedia?
- Bagaimana alur dialog dari satu langkah ke langkah lain?

- IxD menjembatani kebutuhan manusia dan kemungkinan teknis.
- Konsep seperti affordance, mapping, constraints, dan feedback akan dibahas sebagai prinsip analisis pada pertemuan 2.
- Dalam penelitian HCI, interaction design sering dipakai untuk membangun artifact atau prototipe eksperimen.

---

# Slide 11 - HCI sebagai Bidang Multidisiplin

- Masalah interaksi tidak dapat dipecahkan oleh satu disiplin saja.

| Disiplin | Sumbangan terhadap HCI |
|---|---|
| Ilmu komputer | sistem, antarmuka, AI, infrastruktur teknis |
| Psikologi / kognisi | persepsi, memori, atensi, mental model |
| Sosiologi / antropologi | konteks sosial, budaya, kolaborasi |
| Desain | visual, UX, interaction, industrial design |
| Ergonomi / human factors | aspek fisik dan lingkungan |
| Linguistik | bahasa alami, dialog, multimodal |

- Bagi peneliti magister, sifat multidisiplin berarti pertanyaan penelitian sering membutuhkan perspektif dan metode dari lebih dari satu bidang.

---

# Slide 12 - Paradigma Interaksi Manusia-Komputer

- Paradigma HCI menggambarkan asumsi dasar tentang hubungan manusia dan komputer.

| Paradigma | Karakteristik | Contoh |
|---|---|---|
| Command/console | manusia mengikuti aturan sistem | terminal, command line |
| WIMP/desktop metaphor | manipulasi langsung pada representasi | GUI, window, ikon, mouse |
| Ubiquitous/context-aware | komputasi tersebar di lingkungan | sensor, mobile, IoT |
| Agentive/AI-mediated | sistem memiliki inisiatif dan belajar | asisten AI, agen, GenAI |

- Pergeseran paradigma tidak menghapus paradigma lama.
- Paradigma baru menambah cara interaksi dan memperluas pertanyaan penelitian HCI.

---

# Slide 13 - Paradigma dan Pertanyaan Riset

| Paradigma | Fokus Riset | Contoh Pertanyaan |
|---|---|---|
| Command | syntax, model perintah | Bagaimana pengguna mempelajari perintah? |
| GUI/wimp | discoverability, efisiensi interaksi | Apakah direct manipulation menurunkan beban kognitif? |
| Ubiquitous | konteks, gangguan, perhatian | Bagaimana notifikasi memengaruhi atensi pengguna? |
| AI-mediated | kepercayaan, ketergantungan, kendali | Bagaimana kalibrasi kepercayaan pengguna terhadap AI? |

- Setiap paradigma menentukan variabel, ukuran, dan metode yang relevan.
- Contoh: penelitian GUI banyak memakai waktu dan error; penelitian AI-mediated perlu mempertimbangkan trust, reliance, dan kontrol manusia.

---

# Slide 14 - Research Landscape HCI Modern

- Area besar riset HCI yang menjadi peta eksplorasi:

### Klaster topik

- Desain dan prinsip dasar interaksi;
- Persepsi, kognisi, dan perilaku pengguna;
- Usability, UX, dan metode evaluasi;
- Kolaborasi dan komputasi sosial;
- Human-AI Interaction dan intelligent interfaces;
- Aksesibilitas dan inklusivitas;
- Interaksi multimodal, spatial, dan XR;
- Mobile, ubiquitous, dan wearable computing;
- Etika, privasi, dan responsible design;
- HCI dalam domain: pendidikan, kesehatan, kreativitas, keberlanjutan, dan lainnya.

- Peta ini menjadi titik awal untuk mencari paper dan menentukan area minat.

---

# Slide 15 - Tipe Riset HCI: Problem-Driven, Technology-Driven, Theory-Driven

| Motif | Titik Berangkat | Kontribusi yang Mungkin |
|---|---|---|
| Problem-driven | masalah praktis di lapangan | empirical findings, design implications |
| Technology-driven | teknologi atau kapabilitas baru | interaction technique, system, design guidance |
| Theory-driven | celah dalam konsep atau teori | model, framework, theory testing |

- Dalam praktik, ketiga motif dapat bergabung.
- Pada jenjang S2, penting untuk tidak berhenti pada “teknologi baru tersedia”, tetapi mengajukan pertanyaan yang dapat dijawab dengan evidence.

---

# Slide 16 - Fokus Pertemuan: Interface Development vs HCI Research

- Banyak aktivitas “membuat antarmuka” bersifat pengembangan produk.
- HCI research berusaha menghasilkan **pengetahuan baru** tentang interaksi manusia dan teknologi.

```
Development ends with a system.
Research starts with a question and ends with evidence/contribution.
```

- Prototipe atau sistem dapat menjadi bagian metode penelitian, tetapi bukan tujuan akhir penelitian.
- Pertanyaan penting dalam HCI research:

> Apa yang kita pelajari dari sistem atau studi ini, dan mengapa pengetahuan itu penting?

---

# Slide 17 - Perbandingan Interface Development dan HCI Research

| Aspek | Interface Development | HCI Research |
|---|---|---|
| Tujuan akhir | produk, fitur, sistem yang berfungsi | pengetahuan, evidence, kontribusi ilmiah |
| Pertanyaan inti | how to build? | why, when, under what condition? |
| Kriteria berhasil | kebutuhan terpenuhi | research question terjawab, evidence valid |
| Evaluasi | acceptance, usage, kepuasan pengguna | study design, validitas, generalisasi |
| Luaran | aplikasi atau prototipe | paper ilmiah |
| Kontribusi | produk digunakan | scientific contribution |

- Pemisahan ini bukan menyatakan bahwa pengembangan rendah.
- Riset HCI yang kuat sering membutuhkan pengembangan sistem sebagai instrumen penelitian.

---

# Slide 18 - Contoh Ilustrasi: Development vs Research

### Contoh interface development

- Mengembangkan dashboard AI dengan mode gelap dan fitur notifikasi.
- Keberhasilan: berjalan lancar, pengguna menyukainya, kebutuhan terpenuhi.

### Contoh HCI research

- Menguji apakah penambahan indikator keyakinan pada jawaban LLM membantu pengguna membuat keputusan yang lebih akurat.
- Keberhasilan: research question terjawab, efek diukur secara sistematis, dan hasilnya dapat digeneralisasikan.
- Evaluasi: studinya menggunakan kontrol, partisipan, instrumen, dan analisis yang dirancang sesuai pertanyaan riset.

- Masalah pada development dapat menjadi pemicu riset jika dirumuskan menjadi pertanyaan yang dapat diuji.

---

# Slide 19 - Prototipe: Research Artifact vs Produk Akhir

- Dalam riset HCI, prototipe berfungsi sebagai **research artifact** untuk menjawab research question.
- Keberadaan prototipe tidak otomatis menjadi kontribusi ilmiah.

### Prinsip penting dari RPS

```
System novelty ≠ Research novelty
Prototype ≠ Scientific contribution
Performance improvement ≠ Scientific contribution
```

- Kontribusi muncul ketika peneliti melaporkan **apa yang dipelajari** dari interaksi dengan sistem.
- Pertanyaan pemantik:

> Jika sistem ini dibuang, apakah pengetahuan dari penelitiannya masih bertahan?

---

# Slide 20 - Bentuk Scientific Contribution dalam HCI

| Bentuk Kontribusi | Contoh |
|---|---|
| Empirical evidence | hasil studi tentang fenomena interaksi |
| Interaction technique | teknik input atau umpan balik baru |
| System/tool | sistem sebagai enabler penelitian |
| Method/metrics | metode, instrumen, atau ukuran baru |
| Framework/model | struktur konseptual atau model interaksi |
| Dataset/sumber daya | data publik untuk penelitian lanjutan |
| Design implications | prinsip desain berbasis evidence |

- Satu paper biasanya memiliki satu kontribusi utama dan beberapa kontribusi pendukung.
- Kontribusi harus ditulis eksplisit pada bagian introduction paper.

---

# Slide 21 - Menghubungkan Komponen Paper dan Kontribusi Ilmiah

| Bagian Paper | Peran Terhadap Kontribusi |
|---|---|
| Introduction | merumuskan problem, gap, RQ, dan klaim kontribusi |
| Related Work | menunjukkan state of the art dan posisi penelitian |
| Method | menjelaskan bagaimana evidence diperoleh |
| Results | menyajikan evidence penelitian |
| Discussion | menginterpretasi evidence menjadi temuan dan kontribusi |
| Limitations | membatasi ruang lingkup klaim |

- Alur paper yang baik membantu peneliti membedakan data, hasil, dan kontribusi.
- Struktur dan penulisan paper akan diperdalam pada pertemuan 4 dan 15.

---

# Slide 22 - Research Venues HCI Internasional

### Konferensi utama ACM SIGCHI

- **CHI** — Human Factors in Computing Systems;
- **UIST** — User Interface Software and Technology;
- **CSCW** — Computer-Supported Cooperative Work;
- **IUI** — Intelligent User Interfaces;
- **DIS** — Designing Interactive Systems;
- **MobileHCI** — Mobile Human-Computer Interaction;
- **ASSETS** — Accessible Computing;
- **TEI** — Tangible, Embedded, Embodied Interaction.

### Jurnal terindeks Scopus

- International Journal of Human-Computer Studies;
- International Journal of Human-Computer Interaction;
- ACM Transactions on Computer-Human Interaction;
- Behaviour & Information Technology.

- Gunakan ACM Digital Library, Scopus, dan IEEE Xplore untuk mencari paper terkini.

---

# Slide 23 - Paper Exploration: Dari Venue ke Research Interest

- Pertemuan 1 menggunakan paper exploration untuk membangun kepekaan terhadap lanskap riset.

### Cara cepat menjelajah paper

1. Baca judul dan abstrak; tentukan klaster topik.
2. Baca akhir pendahuluan: apa research gap, RQ, dan kontribusi?
3. Perhatikan figure dan tabel utama: apa evidence-nya?
4. Baca hasil dan diskusi; catat keterbatasan.
5. Tanyakan: apa langkah riset berikutnya yang belum dilakukan?

- Kumpulkan 5–10 paper yang menarik untuk menjadi bahan awal literature review.
- Teknik critical paper reading akan dilatih lebih sistematis pada pertemuan 5.

---

# Slide 24 - Emerging HCI: Frontier yang Terus Bergerak

- RPS menekankan materi diperbarui mengikuti perkembangan publikasi mutakhir.

### Area emerging

- Human-AI Interaction;
- Generative AI interfaces;
- LLM-based conversational agents;
- Mixed reality dan spatial interaction;
- Multimodal interaction;
- Human-Robot Interaction;
- Ubiquitous dan wearable sensing;
- Accessibility dan inclusive AI;
- Responsible AI, privacy, dan digital well-being.

- Dua frontier yang paling berpengaruh saat ini adalah **Human-AI Interaction** dan **Generative AI**.
- Topik emerging akan dibahas lebih dalam pada pertemuan 10–12.

---

# Slide 25 - Human-AI Interaction sebagai Research Frontier

- HCI tradisional mempelajari interaksi antara manusia dan sistem yang deterministik.
- Human-AI Interaction (HAII) mempelajari interaksi dengan sistem yang:
  - dapat belajar dari data;
  - menghasilkan prediksi;
  - berkomunikasi dalam bahasa alami;
  - memiliki inisiatif atau otonomi tertentu.

### Pertanyaan yang sering muncul

- trust dan trust calibration;
- explainability dan transparency;
- appropriate reliance, over-reliance, dan under-reliance;
- human oversight dan kontrol;
- human-AI collaboration;
- agency dan perubahan peran manusia.

- Topik ini menjadi fokus utama pertemuan 10.

---

# Slide 26 - Generative AI sebagai Research Frontier

- Generative AI (GenAI) menghasilkan konten baru: teks, gambar, kode, suara, dan video.
- Contoh teknologi: Large Language Models (LLM) dan diffusion models.

### Dampak terhadap interaksi

- Prompt menjadi medium interaksi utama;
- output tidak selalu deterministik;
- pengguna perlu mengevaluasi kualitas dan kemungkinan kesalahan.

### Pertanyaan riset yang terbuka

- Bagaimana merancang interface untuk prompting?
- Bagaimana pengguna menilai kebenaran hasil GenAI?
- Kapan pengguna menjadi terlalu percaya pada AI?
- Bagaimana GenAI mengubah proses kerja kreatif?

- Detail HAII dan GenAI akan dibahas pada pertemuan 10.

---

# Slide 27 - Perubahan Ekspektasi Interaksi di Era Generative AI

| Interaksi Klasik | Interaksi Era GenAI |
|---|---|
| Input terdefinisi: klik, perintah | natural language prompt, multimodal |
| Output deterministik | output probabilistik yang perlu verifikasi |
| Kontrol penuh pada pengguna | mixed-initiative dan otonomi agen |
| Evaluasi berfokus task execution | evaluasi perlu melibatkan trust, workload, workflow |

### Konsekuensi metodologis

- Riset HCI tidak cukup hanya melakukan eksperimen laboratorium jangka pendek.
- Diperlukan studi longitudinal, field study, dan metode kualitatif untuk menangkap perubahan praktik penggunaan AI.

---

# Slide 28 - Research Opportunity di Era Human-AI Interaction

- Kemampuan AI semakin tinggi, tetapi keberhasilan di dunia nyata sangat ditentukan oleh faktor manusia.
- HCI berperan penting dalam:
  - human-centered design of AI;
  - evaluasi AI dari perspektif pengguna;
  - memahami perubahan peran dan alur kerja manusia.

### Pertanyaan pemantik untuk penelitian

- Di mana AI gagal karena masalah manusia, bukan karena masalah model?
- Bagaimana mengukur pengalaman manusia saat berinteraksi dengan AI?
- Intervensi desain apa yang dapat meningkatkan kolaborasi manusia-AI?

- Celah seperti ini menjadi peluang kontribusi penelitian HCI di jenjang magister.

---

# Slide 29 - Research Interest dan Alur Project Semester

- Seluruh pertemuan bermuara pada project penelitian akhir.

```
Research interest → candidate problem → literature review → gap
→ RQ → methodology → user study → data → evidence → paper
```

- Pekan ini Anda hanya perlu menentukan **research interest**, bukan judul penelitian final.
- Research interest adalah area luas yang menarik minat Anda dan dapat dieksplorasi lebih lanjut.
- Pertemuan 2 akan membantu Anda memeriksa minat tersebut menggunakan prinsip human-centered design.

---

# Slide 30 - Weekly Progress: Menentukan Research Interest

### Target progress pekan ini

- Rumusan research interest yang singkat dan jelas.

### Format sederhana

```
Saya tertarik pada interaksi antara [kelompok pengguna] dan [teknologi]
dalam [konteks penggunaan].
```

### Contoh

```
Saya tertarik pada interaksi antara lansia dan conversational AI
dalam konteks monitoring kesehatan di rumah.
```

### Alternatif yang lebih spesifik tetapi tetap luas

```
Saya tertarik pada kepercayaan dan reliance pada asisten menulis
berbasis LLM di kalangan mahasiswa pascasarjana.
```

- Catat juga motivasi Anda: mengapa topik ini penting?

---

# Slide 31 - Dari Research Interest ke Research Problem

| Tahap | Output | Contoh |
|---|---|---|
| Research interest | area luas | AI assistant dalam pendidikan tinggi |
| Interaction problem | fenomena yang dapat diamati | mahasiswa kesulitan mengevaluasi hasil jawaban AI |
| Research question | pertanyaan why/how/when yang dapat diuji | faktor apa yang memengaruhi evaluasi hasil AI? |

- Untuk pekan ini, Anda belum harus sampai pada research question.
- Kumpulkan hasil observasi dan paper exploration.
- Proses penyempitan masalah akan difasilitasi pada pertemuan 2 dan 3.

---

# Slide 32 - Aktivitas Kelas: Diskusi dan Paper Exploration

Setelah paparan materi, lakukan diskusi kecil:

1. Pilih salah satu area interest dari research landscape.
2. Temukan 1 paper dari venue HCI internasional yang relevan.
3. Identifikasi secara singkat: research question, metode, dan kontribusi.
4. Presentasikan dalam 2 menit: judul, topik, dan alasan paper menarik.

### Luaran yang diharapkan

- Daftar calon topik/minat.
- Pemahaman awal tentang bentuk paper HCI.
- Bekal untuk progress mingguan research interest.

---

# Slide 33 - Ringkasan Kompetensi Pertemuan 1

- HCI berevolusi dari fokus usability, UX, hingga human-centered computing.
- HCI bersifat multidisiplin dan memiliki banyak paradigma interaksi.
- Riset HCI modern diwarnai oleh Human-AI Interaction dan Generative AI.
- Perbedaan inti:
  - interface development = menghasilkan sistem;
  - HCI research = menghasilkan pengetahuan dan evidence.
- Kontribusi ilmiah HCI tidak selalu berupa sistem, tetapi dapat berupa empirical evidence, methodology, framework, dataset, dan lainnya.
- Progress pekan ini: research interest harus mulai dirumuskan.

---

# Slide 34 - Pertanyaan Refleksi untuk Penguatan Pemahaman

Refleksi individual:

1. Dari lanskap HCI yang dipaparkan, area mana yang paling ingin Anda eksplorasi?
2. Tuliskan satu fenomena interaksi yang pernah Anda alami dan menurut Anda layak diteliti.
3. Jika Anda memperbaiki form login aplikasi, bagian mana yang bersifat development dan bagian mana yang dapat menjadi research?
4. Untuk fenomena tersebut, kontribusi ilmiah apakah yang paling mungkin: empirical, artifact, framework, atau metodologi?

Jawaban dapat menjadi dasar diskusi asynchronous maupun progress mingguan Anda.

---

# Slide 35 - Penutup

TERIMA KASIH

Pertemuan berikutnya

**Human-Centered Design & Interaction Principles**