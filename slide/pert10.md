# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer
Pertemuan 10
# Human-AI Interaction & Generative AI

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D
Departemen Teknik Informatika - ITS

---

# Slide 01 - Posisi Pertemuan dalam Alur Perkuliahan

| Pertemuan | Topik | Kaitannya dengan Pertemuan 10 |
|---|---|---|
| 9 | Usability, UX & User Study Evaluation | Menyediakan kemampuan merancang user study, instrumen, dan protokol evaluasi |
| **10** | **Human-AI Interaction & Generative AI** | **Menganalisis interaksi manusia dengan sistem AI serta memulai pilot study** |
| 11 | Multimodal, Spatial & Emerging Interaction | Memperluas interaksi ke modalitas lain dan lingkungan spasial/XR |

**Research progress saat ini:**  
Pilot study / initial data collection

Materi pertemuan 10 tidak berdiri sendiri. Pemahaman tentang kognisi manusia dari pertemuan 3, metode riset dari pertemuan 6–7, serta desain user study dari pertemuan 9 akan digunakan untuk membaca dan merancang penelitian Human-AI Interaction.

---

# Slide 02 - Tujuan Pembelajaran dan Capaian

Setelah mengikuti pertemuan ini, mahasiswa diharapkan mampu:

- Menjelaskan konsep dasar Human-Centered AI, Human-AI Interaction, Intelligent User Interfaces, Generative AI, LLM interfaces, conversational interfaces, AI assistants/agents, dan human-AI collaboration.
- Menganalisis bagaimana kehadiran AI memengaruhi **performance, behavior, cognition, trust, workload, agency**, dan **human capability**.
- Menghubungkan konsep explainability, transparency, dan appropriate reliance dengan desain penelitian HCI.
- Menggunakan kerangka critical paper discussion untuk menelaah paper Human-AI Interaction.
- Mengaitkan materi dengan tahap **pilot study** pada research project masing-masing.

Capaian ini mendukung CPMK-2, CPMK-6, dan CPMK-7.

---

# Slide 03 - Peta Konsep Pertemuan

```text
HCI Foundations & Research Methods
(Pertemuan 1-9)
        │
        ▼
Human-AI Interaction & Generative AI
        │
        ├── Human-Centered AI
        ├── Intelligent / Generative Interfaces
        ├── LLM, Conversational AI, Agents
        ├── Human-AI Collaboration
        ├── Trust, Reliance, Transparency
        └── AI-Mediated Communication
        │
        ▼
Multimodal, Spatial & Emerging Interaction
(Pertemuan 11)
```

Human-AI Interaction diposisikan sebagai **perkembangan mutakhir dari HCI**, bukan sekadar penambahan fitur AI pada antarmuka.

---

# Slide 04 - Mengapa Human-AI Interaction Menjadi Research Frontier

AI tidak lagi hanya berupa sistem berbasis aturan yang sepenuhnya dapat diprediksi. Perubahan utama:

- AI menghasilkan keluaran **probabilistik** dan tidak selalu deterministik.
- Pengguna tidak selalu dapat meramalkan kapan AI benar atau salah.
- Interaksi bergeser dari **command-and-control** menuju **dialog dan kolaborasi**.
- Penelitian HCI tidak cukup hanya mengukur usability; perlu memahami bagaimana manusia membangun **trust**, **reliance**, dan **mental model** terhadap AI.

Konsekuensinya, muncul banyak pertanyaan riset baru yang membutuhkan pendekatan empiris dari HCI.

---

# Slide 05 - Human-Centered AI: Prinsip Dasar

Human-Centered AI adalah pendekatan yang menempatkan kebutuhan, nilai, dan kendali manusia sebagai pusat pengembangan AI.

Prinsip utama:

- AI sebaiknya **memperluas kemampuan manusia** (augmentation), bukan menggantikan manusia secara tidak terkendali.
- Manusia memiliki **kontrol dan tanggung jawab** terhadap keputusan penting.
- Sistem AI harus **transparan** mengenai kemampuan dan keterbatasannya.
- Desain harus memperhatikan konteks sosial, etika, privasi, dan keadilan.
- Penilaian keberhasilan tidak hanya dari akurasi model, tetapi dari kualitas interaksi dan dampaknya pada manusia.

Human-Centered AI membedakan pengembangan AI yang berpusat pada teknologi dengan pengembangan AI yang berpusat pada pengguna dan masyarakat.

---

# Slide 06 - Human-AI Interaction: Definisi dan Unit Analisis

Human-AI Interaction (HAI) mempelajari hubungan timbal balik antara manusia dan sistem AI.

| Komponen | Contoh Pertanyaan Riset |
|---|---|
| Manusia | Bagaimana persepsi, kognisi, emosi, dan trust pengguna terbentuk? |
| Sistem AI | Bagaimana AI menyajikan rekomendasi, prediksi, atau tindakan? |
| Interaksi | Bagaimana pengguna memberikan input, mengoreksi, atau mengambil alih kendali? |
| Tugas/Konteks | Bagaimana risiko, kompleksitas tugas, dan lingkungan memengaruhi interaksi? |

Unit analisisnya bukan hanya antarmuka, tetapi juga **proses kolaborasi**, **pengambilan keputusan bersama**, dan **perubahan perilaku pengguna**.

---

# Slide 07 - Intelligent User Interfaces

Intelligent User Interfaces (IUI) adalah antarmuka yang menggunakan AI untuk:

- Menyesuaikan tampilan atau konten berdasarkan konteks pengguna.
- Memberikan rekomendasi tindakan.
- Memprediksi kebutuhan pengguna.
- Menyediakan bantuan adaptif.

Perbedaan penting:

| Adaptive Interface | Adaptable Interface |
|---|---|
| Sistem menyesuaikan diri secara otomatis | Pengguna menyesuaikan pengaturan secara manual |
| Lebih efisien jika prediksi tepat | Memberi kontrol lebih besar |
| Berisiko mengurangi transparansi dan rasa kendali | Memerlukan usaha lebih dari pengguna |

Pertanyaan riset IUI: kapan adaptasi membantu, kapan mengganggu, dan bagaimana cara menyampaikan adaptasi agar tetap dipahami pengguna?

---

# Slide 08 - Generative AI dalam Perspektif Interaksi

Generative AI menghasilkan konten baru — teks, gambar, kode, audio — berdasarkan pola data latih.

Dampak pada interaksi:

- Pengguna menyampaikan **maksud/intensi**, bukan sekadar perintah yang telah ditentukan.
- AI menjadi **mitra generative** yang dapat membantu menulis, merancang, memprogram, dan mengeksplorasi ide.
- Kualitas keluaran tidak tetap; pengguna perlu mengevaluasi, merevisi, dan memverifikasi.

Tantangan HCI utama:

- Bagaimana pengguna memahami batas kemampuan model?
- Bagaimana mencegah **halusinasi** disalahartikan sebagai fakta?
- Bagaimana antarmuka membantu pengguna menyusun permintaan yang efektif?
- Bagaimana mengukur dampak Generative AI terhadap kreativitas, pembelajaran, dan produktivitas?

---

# Slide 09 - LLM Interfaces dan Perubahan Paradigma Interaksi

Large Language Model (LLM) interfaces menggunakan bahasa alami sebagai medium interaksi utama.

| Aspek | GUI Konvensional | LLM Interface |
|---|---|---|
| Perintah | Menu/ikon yang terlihat | Bahasa bebas |
| Prediktabilitas | Tinggi | Rendah, bergantung konteks |
| Mode | Tampak jelas | Tersembunyi |
| Pemulihan kesalahan | Undo/klik jelas | Bergantung pada prompt ulang |
| Kemampuan ekspresi | Terbatas fitur | Sangat luas |

Konsekuensi penting:

- Pengguna dapat melakukan banyak hal tanpa mempelajari perintah khusus.
- Sebaliknya, pengguna dapat mengalami kesulitan karena tidak memahami **mengapa model menjawab demikian**.
- Desain antarmuka LLM tidak cukup berupa kotak teks kosong; perlu contoh prompt, saran perbaikan, sumber rujukan, dan mekanisme verifikasi.

---

# Slide 10 - Conversational Interfaces

Conversational interfaces memungkinkan interaksi melalui percakapan tertulis atau lisan.

Contoh: chatbot layanan, voice assistant, pedagogical conversational agent.

Keunggulan:

- Hambatan awal rendah.
- Sesuai untuk tugas sederhana dan pertanyaan berbasis bahasa.
- Dapat memberikan nuansa sosial.

Kekurangan:

- Tidak selalu efisien untuk tugas visual atau data kompleks.
- Rawan salah memahami konteks.
- Pemulihan dari kesalahan bisa sulit.
- Menimbulkan kekhawatiran privasi karena percakapan terekam.

Dari sisi HCI, desain percakapan harus memperhatikan **turn-taking**, **konfirmasi**, **grounding**, dan **feedback** agar pengguna tidak tersesat.

---

# Slide 11 - AI Assistants dan AI Agents

| AI Assistant | AI Agent |
|---|---|
| Bereaksi terhadap instruksi pengguna | Dapat bekerja mengejar tujuan yang diberikan |
| Cenderung single-turn atau mengikuti percakapan | Mampu merencanakan dan mengeksekusi beberapa langkah |
| Pengguna tetap memegang inisiatif | Agent memiliki otonomi lebih besar |
| Contoh: asisten penulisan, reminder | Contoh: coding agent, research agent |

Pergeseran ini menimbulkan spektrum **agency**:

```text
Tool ──────────► Assistant ──────────► Agent
   pasif            reaktif               otonom
```

Pertanyaan HCI yang muncul:

- Bagaimana pengguna memantau tindakan agent?
- Bagaimana agent menyampaikan ketidakpastiannya?
- Bagaimana manusia dapat menginterupsi atau membatalkan rencana agent?
- Siapa yang bertanggung jawab atas kesalahan agent?

---

# Slide 12 - Human-AI Collaboration

Human-AI collaboration menempatkan AI sebagai **mitra kerja**, bukan sekadar alat.

Riset kolaborasi manusia-AI sering meminjam konsep dari teamwork:

- **Shared mental model**: manusia dan AI memiliki pemahaman yang selaras terhadap tujuan dan proses.
- **Communication**: AI perlu menjelaskan alasan dan kendalanya.
- **Trust**: kepercayaan harus dikalibrasi dengan kemampuan nyata AI.
- **Coordination**: pembagian tugas antara manusia dan AI harus jelas.

Kombinasi kekuatan ideal:

- Manusia: konteks, nilai, etika, penilaian situasional.
- AI: kecepatan, skala, konsistensi, pemrosesan informasi besar.

Riset mengukur kolaborasi melalui kualitas hasil bersama, beban kerja, kepuasan, dan kontribusi masing-masing pihak.

---

# Slide 13 - Mixed-Initiative Interaction

Mixed-initiative interaction adalah pola interaksi di mana **manusia dan AI dapat saling mengambil inisiatif** sesuai kebutuhan.

Ciri utama:

- AI dapat menawarkan saran atau melakukan tindakan.
- Manusia dapat menerima, menolak, mengubah, atau mengambil alih.
- Inisiatif bergeser secara fleksibel.

Prinsip desain umum:

- AI sebaiknya **menawarkan**, bukan selalu memutuskan.
- Tindakan AI harus mudah **diinterupsi** dan **dibatalkan**.
- AI perlu tahu kapan harus bertanya, kapan cukup memberi informasi.
- Sistem perlu menjaga **human-in-the-loop** pada keputusan berdampak besar.

Contoh: proofreading dengan saran perbaikan, penjadwalan otomatis yang dapat diedit, environment AI yang menyesuaikan namun tetap dapat dikontrol.

---

# Slide 14 - Fokus Riset 1: Performance dan Behavior

Kehadiran AI dapat mengubah hasil kerja dan cara kerja pengguna.

| Aspek | Contoh Indikator |
|---|---|
| Task performance | Akurasi keputusan, waktu penyelesaian, kualitas output |
| Behavior | Frekuensi menerima/menolak saran AI, jumlah revisi, pola klik, lama membaca saran |

Temuan umum dalam riset HAI:

- AI dapat meningkatkan performa ketika saran akurat.
- Namun pengguna dapat menjadi **lebih pasif** atau **kurang teliti** ketika mengandalkan AI.
- Karena itu, mengukur performa saja tidak cukup; pengamatan terhadap perilaku interaksi sangat penting.

Pertanyaan riset: apakah peningkatan performa disertai perubahan strategi kognitif yang sehat atau malah ketergantungan?

---

# Slide 15 - Fokus Riset 2: Cognition dan Workload

Berinteraksi dengan AI melibatkan proses kognitif:

- Memahami keluaran AI.
- Membandingkannya dengan pengetahuan sendiri.
- Memutuskan apakah akan mempercayai, mengoreksi, atau mengabaikan.

Workload dapat menurun ketika AI menangani tugas rutin.

Workload dapat meningkat ketika pengguna harus **memverifikasi** keluaran AI, terutama jika AI tidak transparan.

| Kondisi | Potensi Dampak Kognitif |
|---|---|
| Saran AI akurat + transparan | Beban verifikasi menurun |
| Saran AI sering salah | Beban kognitif meningkat, trust menurun |
| AI terlalu otonom | Risiko kehilangan kesadaran situasi |
| AI memberi terlalu banyak penjelasan | Information overload |

Instrumen umum untuk mengukur workload antara lain NASA-TLX dan pengukuran beban kognitif subjektif.

---

# Slide 16 - Fokus Riset 3: Trust, Agency, dan Human Capability

| Konsep | Fokus Analisis |
|---|---|
| Trust | Keyakinan pengguna bahwa AI dapat diandalkan dalam konteks tertentu |
| Agency | Rasa kendali, otonomi, dan tanggung jawab pengguna |
| Human Capability | Pengaruh AI terhadap keterampilan, learning, dan kemandirian pengguna |

Pertanyaan penting:

- Apakah pengguna percaya karena AI memang dapat dipercaya, atau karena familiaritas?
- Apakah pengguna merasa masih memegang kendali ketika AI bekerja secara otonom?
- Apakah penggunaan AI meningkatkan keterampilan, atau menyebabkan **deskilling**?

Ketiga konsep ini saling terkait. Rasa kehilangan kendali dapat menurunkan trust, sedangkan kepercayaan berlebihan dapat mengurangi kesiapan pengguna untuk belajar.

---

# Slide 17 - Explainability dalam Human-AI Interaction

Explainability adalah kemampuan sistem AI untuk memberikan penjelasan yang dapat dipahami manusia.

Tujuan explainability:

- Membantu pengguna membentuk mental model yang akurat.
- Mendukung keputusan untuk menerima atau menolak keluaran AI.
- Memudahkan debugging dan perbaikan.
- Meningkatkan akuntabilitas sistem.

Jenis penjelasan:

- **Global explanation**: menjelaskan cara kerja model secara umum.
- **Local explanation**: menjelaskan mengapa satu keputusan tertentu dihasilkan.
- **Example-based**: menampilkan contoh yang menjadi dasar keputusan.

Catatan penting:

- Penjelasan yang terlalu teknis tidak selalu membantu.
- Efektivitas penjelasan harus diuji terhadap pemahaman, trust, dan perilaku pengguna, bukan hanya keberadaan fitur penjelasan.

---

# Slide 18 - Transparency

Transparency berkaitan dengan sejauh mana sistem membuka informasi tentang cara kerja, tujuan, data, dan keterbatasannya.

Elemen transparansi yang relevan:

- Mengungkapkan bahwa pengguna sedang berinteraksi dengan AI.
- Menjelaskan sumber data dan kemungkinan bias.
- Menyatakan tingkat ketidakpastian keluaran.
- Menampilkan batas tanggung jawab sistem.
- Memberi tahu ketika konten dihasilkan atau dimodifikasi AI.

Transparansi tidak selalu semakin banyak semakin baik.

Terlalu banyak informasi dapat membebani pengguna.

Desain transparansi harus mempertimbangkan:

- Kebutuhan pengguna.
- Risiko tugas.
- Waktu dan konteks penggunaan.

---

# Slide 19 - Trust dan Appropriate Reliance

**Trust** adalah sikap pengguna terhadap keandalan AI.

**Appropriate reliance** adalah kecocokan antara keputusan pengguna untuk mengikuti AI dengan kondisi sebenarnya apakah AI benar atau salah.

```text
Trust tinggi + AI benar  -> appropriate reliance
Trust tinggi + AI salah  -> over-reliance
Trust rendah + AI benar  -> under-reliance
Trust rendah + AI salah  -> appropriate rejection
```

Tujuan desain bukan trust setinggi mungkin, melainkan **trust calibration**:

- Pengguna perlu tahu kapan AI dapat dipercaya.
- Pengguna perlu tahu kapan AI perlu diverifikasi.
- Antarmuka dapat membantu dengan menampilkan confidence, batas kemampuan, atau bukti pendukung.

---

# Slide 20 - Over-reliance dan Under-reliance

**Over-reliance** terjadi ketika pengguna terlalu sering menerima keluaran AI meskipun AI salah.

**Under-reliance** terjadi ketika pengguna mengabaikan keluaran AI meskipun AI sebenarnya benar.

Penyebab umum:

- Over-reliance: automation bias, kelelahan, kepercayaan tinggi yang tidak terkoreksi.
- Under-reliance: pengalaman buruk sebelumnya, kurang paham, alarm fatigue, kepercayaan rendah.

Pengukuran dapat dilakukan dengan:

| Metrik | Cara Menghitung |
|---|---|
| Acceptance rate | Proporsi saran AI yang diterima |
| Reliance when AI correct | Keputusan benar jika mengikuti AI |
| Reliance when AI wrong | Kesalahan karena mengikuti AI |
| Switch rate | Frekuensi mengubah jawaban setelah melihat AI |

Intervensi desain antara lain: menampilkan uncertainty, meminta konfirmasi, menyediakan penjelasan, dan merancang feedback setelah kesalahan.

---

# Slide 21 - Automation Bias

Automation bias adalah kecenderungan manusia untuk lebih mempercayai keluaran otomatisasi/AI daripada informasi lain yang bertentangan.

Bentuk umum:

- **Commission error**: mengikuti saran AI yang salah.
- **Omission error**: tidak melakukan pemeriksaan karena menganggap AI telah menangani tugas.

Konteks risiko:

- Diagnosis medis.
- Keputusan finansial.
- Moderasi konten.
- Kendali kendaraan atau sistem industri.
- Penilaian akademik.

Mitigasi:

- Menampilkan ketidakpastian AI.
- Mendorong verifikasi aktif.
- Menyediakan alternatif sebelum keputusan final.
- Membatasi kecepatan kerja otomatis pada tugas kritis.
- Menetapkan akuntabilitas manusia secara eksplisit.

Automation bias penting dipelajari karena berhubungan dengan **safety**, **etika**, dan **kualitas keputusan**.

---

# Slide 22 - AI Uncertainty

Sistem AI seharusnya dapat menyampaikan seberapa yakin terhadap keluarannya.

Bentuk sajian uncertainty:

- Confidence score numerik, misalnya 85%.
- Label verbal, misalnya “keyakinan tinggi”, “keyakinan rendah”.
- Visual, misalnya warna atau tebal tipis indikator.
- Alternatif jawaban beserta kemungkinannya.

Masalah yang sering muncul:

- Pengguna tidak memahami makna confidence.
- Confidence display diabaikan ketika tugas mudah.
- Confidence yang salah justru merusak trust.

Riset diperlukan untuk menjawab:

- Format uncertainty apa yang paling efektif untuk tugas tertentu?
- Bagaimana uncertainty memengaruhi keputusan pengguna?
- Bagaimana menampilkan uncertainty tanpa menambah beban kognitif?

AI yang tidak mengakui ketidaktahuannya dapat dianggap terlalu yakin dan mendorong over-reliance.

---

# Slide 23 - Human Oversight

Human oversight adalah mekanisme agar manusia tetap dapat memantau dan mengendalikan AI.

Tingkat keterlibatan manusia:

| Level | Deskripsi |
|---|---|
| Human-in-the-loop | Manusia terlibat pada setiap keputusan penting |
| Human-on-the-loop | Manusia memantau dan dapat campur tangan |
| Human-in-command | Manusia menetapkan tujuan dan batas, AI menjalankan |

Desain oversight perlu menjawab:

- Bagaimana AI memberi sinyal ketika membutuhkan persetujuan?
- Bagaimana pengguna dapat melihat riwayat tindakan AI?
- Bagaimana interupsi dilakukan dengan cepat dan mudah?
- Bagaimana mencegah pengawasan menjadi pekerjaan tambahan yang melelahkan?

Oversight tidak berarti manusia harus memeriksa setiap detail, tetapi harus dimungkinkan pada titik yang tepat.

---

# Slide 24 - AI-Mediated Communication

AI-mediated communication (AI-MC) terjadi ketika AI ikut mengubah, menyusun, atau menafsirkan komunikasi antar manusia.

Contoh:

- Smart reply pada email atau pesan.
- Penerjemahan otomatis secara real-time.
- Ringkasan otomatis rapat.
- AI moderation untuk menjaga percakapan sehat.
- AI yang menyunting nada pesan sebelum dikirim.

Dampak yang diteliti:

- Sejauh mana pesan dianggap berasal dari pengirim asli?
- Bagaimana gaya bahasa AI mengubah persepsi penerima?
- Bagaimana AI memengaruhi ekspresi emosi dan identitas?
- Apakah pengguna kehilangan keterampilan komunikasi?

AI-MC membuka isu **autentisitas**, **kepemilikan pesan**, dan **etika media sosial**.

---

# Slide 25 - Merancang Riset Human-AI Interaction

Pertanyaan riset HAI dapat dikelompokkan menjadi:

1. **Efek kehadiran AI**  
   Misalnya: apakah keputusan dengan bantuan AI lebih baik daripada tanpa AI?

2. **Efek karakteristik AI**  
   Misalnya: apakah penjelasan, uncertainty display, atau tingkat otonomi mengubah trust dan perilaku?

3. **Efek moderasi**  
   Misalnya: apakah efek AI berbeda pada pengguna berpengalaman vs pemula, atau pada tugas berisiko tinggi vs rendah?

Prinsip dari pertemuan 6 tetap berlaku:

- Tentukan variabel bebas dan terikat secara operasional.
- Gunakan randomisasi atau counterbalancing.
- Kendalikan faktor konfunder seperti tingkat kesulitan tugas dan familiaritas AI.
- Pilih kondisi yang memungkinkan AI benar dan salah agar reliance dapat diukur.

---

# Slide 26 - Contoh Kerangka Eksperimen Human-AI

Ilustrasi desain sederhana:

```text
Research Question:
  Apakah format explanation memengaruhi appropriate reliance?

Design:
  Between-subjects / within-subjects
  Independent Variable:
    1. Tanpa explanation
    2. Local explanation
    3. Explanation + uncertainty

Task:
  Memberikan prediksi/diagnosis sederhana dengan bantuan AI.

Ground truth:
  Jawaban benar sudah ditentukan peneliti.

Dependent Variables:
  - Akurasi keputusan final
  - Acceptance rate saat AI benar dan saat AI salah
  - Trust score (kuesioner)
  - Workload (NASA-TLX)
  - Waktu pengerjaan
```

Eksperimen perlu diuji coba sebelum data utama dikumpulkan. Inilah peran **pilot study** pada research progress minggu ini.

---

# Slide 27 - Instrumen dan Pengukuran yang Sering Digunakan

| Konstruk | Contoh Pengukuran |
|---|---|
| Performance | Akurasi, waktu, error rate, kualitas hasil |
| Trust | Kuesioner trust, skala keyakinan, behavioral reliance |
| Workload | NASA-TLX |
| Cognitive load | Secondary task, subjective rating, physiological measure |
| User experience | UEQ, SUS, AttrakDiff |
| Agency | Persepsi kontrol, kuesioner autonomy, tindakan override |
| Reliance | Acceptance rate, kecepatan menerima saran, pola revisi |
| Pemahaman | Mental model test, comprehension questions |

Validitas instrumen perlu diuji pada pilot study. Skala yang tidak sensitif dapat menyebabkan hasil non-signifikan meskipun efek sebenarnya ada.

---

# Slide 28 - Contoh Workflow Pengumpulan Data Interaksi dengan AI

Pseudocode sederhana untuk logging interaksi:

```text
for each task in tasks:
    tampilkan task ke partisipan

    ai_suggestion = system_ai.get_suggestion(task)
    tampilkan ai_suggestion + tombol "lihat penjelasan"

    catat waktu_melihat_saran
    catat apakah penjelasan dibuka
    catat jawaban_user sebelum dan sesudah melihat saran

    if jawaban_user == ai_suggestion:
        catat "accept"
    elif jawaban_user == jawaban_awal:
        catat "reject"
    else:
        catat "modify"

    if ground_truth tersedia:
        catat apakah ai_suggestion benar

setelah semua task selesai:
    hitung acceptance rate
    hitung reliance saat AI benar
    hitung reliance saat AI salah
    berikan kuesioner trust dan workload
```

Log seperti ini memungkinkan peneliti membedakan perilaku nyata dan persepsi subjektif.

---

# Slide 29 - Analisis Data: Memisahkan Persepsi dan Perilaku

Dalam studi Human-AI Interaction, data subjektif dan perilaku sering kali berbeda.

Contoh:

- Partisipan menyatakan **tingkat kepercayaan tinggi** pada kuesioner.
- Namun pada data log, partisipan **jarang mengikuti saran AI**.

Kemungkinan sebab:

- Pertanyaan kuesioner tidak mengukur trust dengan tepat.
- Partisipan memberikan jawaban sosial yang diinginkan.
- Konteks tugas membuat keputusan tidak mengikuti trust secara langsung.

Karena itu:

- Gunakan **multiple measures**.
- Bandingkan subjective scale dengan behavioral data.
- Gunakan think-aloud atau wawancara singkat untuk memahami alasan.
- Laporkan kedua jenis hasil secara terpisah.

Pilot study membantu mendeteksi ketidaksesuaian ini sejak awal.

---

# Slide 30 - Research Gap dan Open Problems dalam Human-AI Interaction

Beberapa topik yang masih terbuka untuk penelitian:

- Pedoman desain antarmuka LLM yang berbasis bukti, bukan hanya praktik industri.
- Cara mengukur **appropriate reliance** secara valid dan konsisten.
- Desain explanation yang efektif tanpa meningkatkan beban kognitif.
- Interaksi dengan AI agent yang otonom namun tetap dapat diawasi.
- Dampak jangka panjang AI terhadap keterampilan dan kemandirian manusia.
- Studi Human-AI Interaction pada konteks nyata dan kelompok pengguna beragam.
- Peran budaya, bahasa, dan norma sosial dalam trust dan penggunaan AI.

Mahasiswa dapat memanfaatkan gap ini untuk memperkuat **positioning penelitian** pada paper akhir.

---

# Slide 31 - Contemporary Paper Discussion: Kerangka Critical Review

Ketika mendiskusikan paper Human-AI Interaction, gunakan pertanyaan kunci berikut:

- Apa research question utama paper?
- Konstruk apa yang diteliti: trust, reliance, workload, agency, performance, atau lainnya?
- Bagaimana konstruk tersebut diukur? Apakah menggunakan alat ukur yang valid?
- Apakah kondisi eksperimen memungkinkan AI untuk **salah**? Mengapa penting?
- Bagaimana partisipan direkrut dan berapa jumlahnya?
- Apakah temuan berdasarkan persepsi, perilaku, atau keduanya?
- Apakah kesimpulan paper didukung oleh data?
- Apa keterbatasan studi dan peluang riset lanjutannya?

Pendekatan ini melatih kemampuan membaca paper secara kritis, bukan sekadar meringkas.

---

# Slide 32 - Contoh Tabel Analisis Paper Human-AI

| Aspek | Pertanyaan Pemandu | Catatan Paper yang Dibahas |
|---|---|---|
| Research question | Masalah apa yang dijawab? | Tulis di sini |
| Konstruk | Apa variabel utama? | Tulis di sini |
| Manipulasi | Bagaimana AI dibuat berbeda antar kondisi? | Tulis di sini |
| Pengukuran | Apa instrumen dan metriknya? | Tulis di sini |
| Partisipan | Siapa dan berapa banyak? | Tulis di sini |
| Temuan | Apa hasil utama? | Tulis di sini |
| Keterbatasan | Apa threat to validity? | Tulis di sini |
| Peluang riset | Apa lanjutan yang mungkin? | Tulis di sini |

Tabel ini dapat digunakan sebagai alat kerja selama diskusi kelas dan sebagai bahan critical review daring.

---

# Slide 33 - Kaitan dengan Research Project: Pilot Study

Research progress pada pertemuan 10 adalah **pilot study / initial data collection**.

Pilot study bertujuan untuk:

- Menguji kelayakan protokol user study.
- Mengidentifikasi masalah pada task, instrumen, atau sistem.
- Mendapatkan estimasi awal efek dan variance.
- Memberi pengalaman peneliti dalam menjalankan studi.

Checklist pilot untuk studi Human-AI:

- Apakah partisipan memahami peran AI dalam tugas?
- Apakah manipulasi kondisi berjalan seperti yang direncanakan?
- Apakah data log terekam dengan benar?
- Apakah kuesioner dipahami tanpa ambiguitas?
- Apakah durasi studi masuk akal?

Temuan pilot digunakan untuk memperbaiki desain sebelum pengumpulan data utama.

---

# Slide 34 - Menghubungkan ke Pertemuan 11: Multimodal, Spatial & Emerging Interaction

Pertemuan berikutnya akan membahas interaksi multimodal, spatial, dan emerging technology seperti AR/VR/XR, gesture, gaze, dan wearable.

Keterkaitan dengan Human-AI Interaction:

- AI dapat hadir dalam berbagai modalitas: suara, gerakan, tatapan, sentuhan.
- Lingkungan spasial/XR menambah kompleksitas konteks dan kehadiran agen AI.
- Interaksi multimodal berpotensi meningkatkan naturalness tetapi juga menambah tantangan desain dan evaluasi.

Pertanyaan untuk direnungkan sebelum pertemuan 11:

- Bagaimana prinsip trust dan transparency berlaku pada agen AI di lingkungan AR/VR?
- Bagaimana multimodal input digunakan untuk mengontrol agent atau berkolaborasi dengan AI?
- Bagaimana mengukur workload dan user experience pada interaksi yang melibatkan banyak modalitas sekaligus?

---

# Slide 35 - Rangkuman Poin Kunci Pertemuan 10

- Human-AI Interaction adalah area riset HCI yang memperlakukan AI sebagai entitas interaktif yang memengaruhi persepsi, keputusan, dan perilaku manusia.
- Human-Centered AI menekankan kontrol manusia, transparansi, akuntabilitas, dan dampak etis.
- Generative AI, LLM interfaces, conversational interfaces, AI assistants, dan AI agents mengubah cara manusia berkomunikasi dengan sistem.
- Konsep kunci: explainability, transparency, trust, appropriate reliance, over-reliance/under-reliance, automation bias, AI uncertainty, human oversight, dan AI-mediated communication.
- Riset HAI perlu mengukur dampak pada performance, behavior, cognition, trust, workload, agency, dan human capability.
- Peneliti harus menggunakan studi empiris yang hati-hati, tidak hanya membangun demonstrasi AI.

---

# Slide 36 - Refleksi dan Pertanyaan Kunci untuk Diskusi

Sebelum pertemuan ditutup, renungkan pertanyaan berikut:

1. Apakah kehadiran AI selalu mengurangi rasa kendali pengguna? Berikan contoh yang tidak.
2. Bagaimana Anda akan membedakan **kepercayaan yang sehat** dan **kepercayaan berlebihan** pada pengguna?
3. Apakah menjelaskan cara kerja AI selalu bermanfaat? Dalam kondisi apa penjelasan dapat menjadi kontraproduktif?
4. Jika penelitian Anda melibatkan AI, konstruk apa yang paling relevan untuk diukur: trust, reliance, workload, agency, atau human capability?
5. Jika penelitian Anda tidak berfokus pada AI, bagaimana AI dapat menjadi alat dalam user study atau instrumen penelitian?

Jawaban atas pertanyaan-pertanyaan ini menjadi jembatan menuju tahap analisis dan penulisan hasil penelitian.

---

# Slide 37 - Penutup

TERIMA KASIH

Pertemuan berikutnya

**Multimodal, Spatial & Emerging Interaction**