# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer
Pertemuan 11
# Multimodal, Spatial & Emerging Interaction

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D
Departemen Teknik Informatika - ITS

---

# Slide 01 - Posisi Pertemuan dalam Alur Kuliah

- Pertemuan 11 membahas **medium interaksi**, bukan hanya antarmuka visual atau percakapan teks.
- Materi ini melanjutkan bahasan **Human-AI Interaction & Generative AI** pada Pertemuan 10, terutama ketika asisten AI mulai menerima suara, gesture, dan gaze.
- Pertemuan berikutnya, **Inclusive, Accessible & Responsible HCI**, akan menuntut evaluasi apakah teknologi multimodal/spatial dapat digunakan oleh semua orang secara bertanggung jawab.
- Dalam pipeline penelitian Anda, pertemuan ini bertepatan dengan tahap **data collection**.

```
P09 User Study/Evaluation
   ↓
P10 Human-AI Interaction & Generative AI
   ↓
P11 Multimodal, Spatial & Emerging Interaction   ← Anda di sini
   ↓
P12 Inclusive, Accessible & Responsible HCI
```

---

# Slide 02 - Tujuan Pembelajaran

Setelah mengikuti pertemuan ini, Anda diharapkan mampu:

1. Menjelaskan konsep **interaction modality** dan perbedaannya dengan teknologi antarmuka.
2. Menganalisis ragam modalitas interaksi: voice, gesture, gaze, touch, haptic, tangible, embodied, dan multimodal.
3. Membedakan bentuk interaksi **spatial/XR**, wearable, ubiquitous, context-aware, dan human-robot.
4. Mengidentifikasi pengaruh modalitas terhadap **usability, cognition, behavior, presence, immersion, workload, dan UX**.
5. Mengaitkan pilihan modalitas dengan **research question** dan strategi pengumpulan data.
6. Menggunakan konsep pertemuan ini untuk memperkuat **data collection** pada research project masing-masing.

---

# Slide 03 - Research Focus dan Progress Minggu Ini

| Aspek | Detail |
|---|---|
| Fokus keilmuan | Hubungan modalitas interaksi dengan pengalaman dan perilaku pengguna |
| Dominan ranah | Multimodal, spatial, extended reality, wearable, ubiquitous, HRI |
| Bukan tujuan utama | Membangun demo teknologi semata |
| Tujuan utama | Menghasilkan pemahaman berbasis bukti tentang efek modalitas pada manusia |
| Progress penelitian | **Data collection** |
| Aktivitas RPS | **Emerging HCI discussion** |

Mulai minggu ini, instrumen dan protokol studi Anda seharusnya sudah berjalan untuk menjaring data dari partisipan.

---

# Slide 04 - Interaction Modality: Konsep

**Interaction modality** adalah saluran atau cara pengguna dan sistem saling menyampaikan makna.

- Modalitas bukan sekadar perangkat keras.
- Modalitas melibatkan jalur sensorik dan motorik manusia.
- Contoh modalitas input:
  - Suara/ucapan.
  - Gerakan tangan atau tubuh.
  - Arah pandangan mata.
  - Sentuhan pada permukaan.
  - Gerakan fisik objek tangible.
- Contoh modalitas output:
  - Visual.
  - Auditorial.
  - Haptic/taktil.
  - Kinestetik/vestibular.

Ilmu HCI meneliti bagaimana kombinasi modalitas memengaruhi tugas, beban kognitif, dan pengalaman subjektif.

---

# Slide 05 - Dimensi Modalitas: Input, Output, dan Saluran

| Arah | Modalitas | Karakteristik |
|---|---|---|
| Input | Voice | Simbolik, bahasa alami, hands-free |
| Input | Gesture | Spasial, dapat berupa pointing atau command |
| Input | Gaze | Cepat, implisit, sering tidak disadari |
| Input | Touch | Direct manipulation, presisi tinggi untuk objek dekat |
| Input | Manipulasi fisik | Memanfaatkan objek tangible sebagai representasi digital |
| Output | Visual | Dominan, kapasitas informasi besar |
| Output | Auditori | Baik untuk notifikasi dan informasi temporal |
| Output | Haptic | Pribadi, tidak memerlukan mata, bandwidth rendah |

Modalitas tertentu dapat berfungsi ganda, misalnya haptic sebagai input dan output.

---

# Slide 06 - Multimodal Interaction: Definisi dan Rasional

**Multimodal interaction** adalah interaksi yang menggunakan lebih dari satu modalitas input atau output secara terkoordinasi untuk menyampaikan satu maksud.

Contoh:

- Pengguna berkata “file ini” sambil menunjuk layar.
- Sistem VR menerima perintah suara dan gaze secara bersamaan untuk memilih objek.
- Smartwatch memberi notifikasi haptic saat pengguna tidak melihat layar.

Mengapa multimodal?

- Mengurangi ambiguitas makna.
- Memperluas ekspresi pengguna.
- Mendukung konteks tangan sibuk atau mata sibuk.
- Meningkatkan aksesibilitas.
- Meniru komunikasi manusia yang multisensori.

---

# Slide 07 - Pola Kombinasi Modalitas

| Pola | Makna | Contoh |
|---|---|---|
| Komplementer | Dua modalitas menyumbang bagian makna yang berbeda | Ucapan “objek ini” + gaze menunjuk objek tertentu |
| Redundan | Modalitas berbeda menyampaikan informasi yang sama | Ikon visual + suara peringatan yang sama |
| Ekuivalen | Setiap modalitas dapat menggantikan fungsi yang sama | Perintah “hapus” dapat diketik, diucapkan, atau digeser dengan gesture |
| Konflik | Informasi antar modalitas tidak konsisten | Ucapan menunjuk A, gaze menunjuk B |

Riset multimodal sering menguji apakah kombinasi modalitas menghasilkan **makna yang lebih pasti** dibanding modalitas tunggal.

---

# Slide 08 - Voice Interaction

- Menggunakan bahasa alami atau perintah suara.
- Sangat berguna ketika tangan atau mata pengguna sibuk.
- Potensi masalah:
  - Kebisingan lingkungan.
  - Privasi dan gangguan sosial.
  - Kesalahan recognition yang sulit diprediksi.
  - Discoverability perintah suara rendah.
- Efek kognitif:
  - Mengurangi beban motorik.
  - Dapat menambah beban kognitif karena pengguna harus mengingat perintah.

Catatan: Pertemuan 10 membahas asisten AI dan conversational agent. Fokus pertemuan ini adalah suara sebagai **modalitas** interaksi, termasuk pada sistem non-AI.

---

# Slide 09 - Gesture Interaction

- Gesture memanfaatkan gerakan tangan, lengan, kepala, atau seluruh tubuh.
- Contoh:
  - Menunjuk objek di layar.
  - Swipe untuk navigasi.
  - Gerakan tangan di udara untuk manipulasi objek virtual.
- Jenis:
  - Gesture di permukaan sentuh.
  - Gesture di udara/in-air.
  - Gesture dengan controller atau sensor tubuh.
- Tantangan riset:
  - Segmentasi awal dan akhir gesture.
  - Kelelahan otot.
  - Kemudahan dipelajari dan diingat.
  - Variasi budaya dan individu.

Gesture sering dikombinasikan dengan voice untuk memberikan referensi spasial yang jelas.

---

# Slide 10 - Gaze Interaction

- Gaze memanfaatkan posisi dan gerakan mata.
- Digunakan untuk:
  - Menunjuk objek dengan cepat.
  - Menentukan area perhatian.
  - Aksesibilitas bagi pengguna dengan keterbatasan motorik.
- Masalah utama: **Midas touch problem**.
  - Mata selalu melihat, tetapi tidak setiap melihat berarti ingin memilih.
  - Solusi: dwell time, blink, kombinasi gaze dengan tombol/voice/gesture.
- Potensi penelitian:
  - Beban kerja akibat dwell.
  - Perbedaan gaze untuk tugas seleksi vs membaca.
  - Gaze sebagai indikator attention dalam adaptive interface.

---

# Slide 11 - Touch Interaction

- Sentuhan menjadi standar pada smartphone dan tablet.
- Sifat utama: **direct manipulation**.
  - Pengguna menyentuh objek yang terlihat langsung.
  - Hubungan antara tindakan dan hasil sangat singkat.
- Tantangan:
  - Fat finger: jari menutupi target.
  - Presisi terbatas untuk objek kecil.
  - Mode discoverability gesture multi-sentuh.
  - Tidak cocok untuk konteks mata sibuk.
- Pertimbangan desain:
  - Ukuran target.
  - Area sentuh yang efektif.
  - Feedback visual/haptic setelah sentuhan.

Konsep motor performance dari Pertemuan 3, misalnya Fitts's law, tetap relevan untuk mengevaluasi efisiensi touch.

---

# Slide 12 - Haptic Interaction

- Haptic mencakup dua saluran utama:
  - **Tactile**: informasi melalui kulit, misalnya getaran.
  - **Kinesthetic**: informasi melalui otot dan sendi, misalnya resistansi atau gaya.
- Contoh:
  - Getaran ponsel.
  - Force feedback pada controller.
  - Tekstur virtual pada permukaan sentuh.
  - Mid-air haptic tanpa kontak fisik.
- Kekuatan:
  - Privasi tinggi.
  - Tidak memerlukan perhatian visual.
  - Meningkatkan presence di lingkungan virtual.
- Keterbatasan:
  - Bandwidth informasi rendah.
  - Adaptasi sensorik.
  - Persepsi getaran berbeda antarindividu.

---

# Slide 13 - Tangible Interaction

- **Tangible User Interface** menghubungkan objek fisik dengan representasi digital.
- Pengguna memegang, memindahkan, atau mengubah objek fisik untuk mengendalikan informasi digital.
- Prinsip:
  - Informasi digital “menempel” pada objek fisik.
  - Batas input dan output menjadi kabur.
- Keunggulan:
  - Manipulasi lebih alami.
  - Mendukung memori spasial dan motorik.
  - Memfasilitasi kolaborasi tatap muka.
- Tantangan:
  - Sulit mengubah tampilan objek fisik secara dinamis.
  - Biaya dan kompleksitas perangkat keras.
  - Skalabilitas jumlah objek.

---

# Slide 14 - Embodied Interaction

- Embodied interaction menekankan bahwa makna diciptakan melalui **tubuh, gerakan, dan konteks fisik/sosial**.
- Interaksi tidak hanya terjadi di kepala atau di layar, tetapi melalui aktivitas seluruh tubuh.
- Contoh:
  - Exergame dan olahraga digital.
  - Instalasi tari interaktif.
  - Simulasi pembelajaran berbasis gerakan.
- Evaluasi tidak cukup dengan waktu tugas.
  - Perlu memperhatikan kualitas gerakan.
  - Keterlibatan tubuh.
  - Pengalaman sosial dan emosional.

Perspektif ini selaras dengan embodied cognition yang telah diperkenalkan pada Pertemuan 3.

---

# Slide 15 - Spatial Interaction dan Extended Reality

**Spatial interaction** adalah interaksi yang memanfaatkan ruang tiga dimensi sebagai tempat berlangsungnya komunikasi antara manusia dan sistem.

- Berlaku di lingkungan nyata maupun virtual.
- Tugas khas:
  - Navigasi.
  - Seleksi objek 3D.
  - Manipulasi objek.
  - Kontrol sistem.
- Extended reality (XR) mencakup:
  - Augmented reality (AR).
  - Virtual reality (VR).
  - Mixed reality (MR).
- Perangkat umum:
  - Head-mounted display.
  - Controller 6-DOF.
  - Hand tracking.
  - Spatial audio.

---

# Slide 16 - XR dan Kontinum Realitas-Virtual

Gagasan kontinum realitas membantu memosisikan teknologi XR:

```
Real environment
   |
   +---- AR: objek virtual ditambahkan ke dunia nyata
   |
   +---- Mixed Reality: dunia nyata dan virtual saling berbaur
   |
   +---- VR: dunia virtual menggantikan lingkungan nyata
   |
Virtual environment
```

| Istilah | Deskripsi singkat |
|---|---|
| AR | Virtual overlay pada lingkungan fisik |
| VR | Lingkungan virtual yang imersif |
| MR | Objek virtual dan fisik berinteraksi dalam satu ruang |
| Spatial computing | Konsep luas untuk komputasi yang memahami ruang dan objek |

Riset spatial interaction tidak cukup mengukur “apakah berhasil”, tetapi perlu mengukur pemahaman ruang, presence, dan workload.

---

# Slide 17 - Presence, Immersion, dan Embodiment

Konsep penting untuk mengevaluasi pengalaman XR:

| Konstruk | Penjelasan |
|---|---|
| Immersion | Sifat teknis sistem: field of view, fidelity, tracking |
| Presence | Perasaan subjektif “berada di dunia virtual” |
| Place Illusion | Ilusi bahwa Anda berada di tempat virtual tersebut |
| Plausibility | Keyakinan bahwa kejadian virtual masuk akal |
| Embodiment | Perasaan memiliki dan mengendalikan tubuh/avatar |

Immersive system tidak otomatis meningkatkan performa. Penelitian harus membedakan efek teknis dan efek pengalaman.

---

# Slide 18 - Wearable Computing

- Komputasi yang dikenakan di tubuh.
- Contoh:
  - Smartwatch.
  - Smart glasses.
  - Fitness tracker.
  - E-textile.
  - Wearable haptic.
- Keunggulan:
  - Sensor kontinu dan dekat dengan tubuh.
  - Tersedia saat dibutuhkan.
  - Mendukung micro-interaction.
- Tantangan:
  - Layar kecil.
  - Daya tahan baterai.
  - Penerimaan sosial.
  - Privasi data tubuh.
  - Interupsi notifikasi.
- Modalitas khas wearable:
  - Haptic notification.
  - Gesture tangan.
  - Voice singkat.
  - Sentuhan ringan.

---

# Slide 19 - Ubiquitous Computing dan Context-Aware Systems

**Ubiquitous computing** membayangkan komputasi tersebar di lingkungan dan menjadi bagian aktivitas sehari-hari.

**Context-aware system** menyesuaikan perilaku berdasarkan konteks:

- Lokasi.
- Waktu.
- Identitas pengguna.
- Aktivitas.
- Kondisi lingkungan.
- Perangkat terdekat.

Contoh:

- Mode senyap berubah dari notifikasi audio menjadi haptic.
- Aplikasi navigasi menyesuaikan rute berdasarkan aktivitas fisik.
- Ruang meeting menyesuaikan pencahayaan dan mikrofon.

Tantangan utama:

- Kontrol pengguna.
- Prediktabilitas.
- Privasi.
- Bias konteks yang tidak lengkap.

---

# Slide 20 - Human-Robot Interaction

- HRI adalah bidang interaksi antara manusia dan robot.
- Robot memiliki **embodiment fisik**, sehingga interaksi bersifat multimodal dan spasial.
- Modalitas yang digunakan:
  - Suara dan percakapan.
  - Gesture.
  - Sentuhan.
  - Gaze.
  - Jarak sosial/proxemics.
- Isu yang diteliti:
  - Keamanan fisik.
  - Kepercayaan dan kalibrasi kepercayaan.
  - Penerimaan sosial.
  - Kerja sama manusia-robot.
  - Otonomi dan human oversight.

Kaitan dengan Pertemuan 10: robot dapat dipandang sebagai bentuk AI agent yang memiliki tubuh dan kehadiran fisik di dunia nyata.

---

# Slide 21 - Emerging Interaction Modalities

Teknologi interaksi yang masih berkembang:

- Brain-computer interface.
- EMG untuk membaca sinyal otot.
- Eye tracking yang lebih murah dan presisi.
- Mid-air haptics.
- Umpan balik termal.
- Antarmuka penciuman dan rasa.
- Komputasi afektif berbasis fisiologi.
- Proactive/anticipatory interaction.
- Micro-interaction pada perangkat wearable.

Ciri penelitian emerging:

- Belum ada standar evaluasi yang mapan.
- Teknologi sering belum stabil.
- Perlu studi empiris untuk memahami efek nyata pada manusia.
- Perlu kehati-hatian dalam klaim performa dan UX.

---

# Slide 22 - Menyeleksi Modalitas: Task, User, Context

Pilihan modalitas tidak boleh hanya berdasarkan popularitas teknologi.

| Faktor | Pertanyaan |
|---|---|
| Task | Apakah tugas bersifat simbolik atau spasial? Kontinu atau diskret? |
| Context | Apakah tangan/mata pengguna sibuk? Lingkungan bising atau tenang? |
| User | Apakah sesuai dengan kemampuan motorik, kognitif, dan preferensi? |
| Device | Sensor apa yang tersedia dan seberapa andal? |
| Workload | Apakah modalitas menambah beban kognitif atau fisik yang tidak perlu? |

Kesesuaian modalitas dengan task dan user adalah pertanyaan penelitian yang dapat diuji secara sistematis.

---

# Slide 23 - Dampak Modalitas terhadap Usability dan Workload

| Modalitas | Potensi keunggulan usability | Potensi masalah usability/workload |
|---|---|---|
| Voice | Hands-free, alami | Noise, privasi, beban kognitif mengingat perintah |
| Gesture | Ekspresif, spasial | Kelelahan fisik, gesture sulit diingat |
| Gaze | Sangat cepat menunjuk | Midas touch, kelelahan mata |
| Touch | Langsung, mudah dipelajari | Occlusion, presisi rendah untuk target kecil |
| Haptic | Tanpa menggunakan mata | Bandwidth rendah, getaran bisa mengganggu |
| Multimodal | Mengurai ambiguitas makna | Butuh integrasi dua sumber informasi |

Usability tetap diukur dengan efektivitas, efisiensi, dan kepuasan, sebagaimana dibahas pada Pertemuan 9.

---

# Slide 24 - Dampak Modalitas terhadap Cognition dan Behavior

- Modalitas memengaruhi **cognitive load**.
  - Informasi visual dan auditori dapat saling melengkapi.
  - Tetapi dua sumber informasi pada saluran yang sama dapat membebani.
- Modalitas berdampak pada **attention**.
  - Notifikasi haptic lebih periferal daripada notifikasi visual.
  - Voice command dapat mengganggu pengguna di ruang publik.
- Modalitas mengubah **behavior**.
  - Pengguna memilih mode interaksi yang berbeda untuk tugas berbeda.
  - Terjadi modality switching, misalnya berpindah dari sentuh ke suara saat tangan kotor.
- Modalitas dapat memanfaatkan **spatial memory**.
  - Objek tangible atau lokasi virtual membantu pengguna mengingat struktur informasi.

---

# Slide 25 - Dampak Modalitas terhadap Presence, Immersion, dan UX

- Immersion adalah properti sistem; presence adalah pengalaman subjektif.
- Modalitas alami seperti gesture dan gaze dapat meningkatkan rasa kehadiran dalam VR.
- Namun, modalitas yang tidak andal justru merusak presence.
- UX tidak identik dengan fun.
  - Ukur aspek emosi, makna, nilai, dan kepuasan.
  - Pertimbangkan efek negatif seperti cybersickness, frustrasi, dan kelelahan.
- Hubungan modalitas dengan setiap konstruk perlu dinyatakan secara eksplisit dalam penelitian.

```
Modalitas → pengalaman interaksi → performa tugas & persepsi pengguna
              ↓
       presence, workload,
       emotion, trust, dsb.
```

---

# Slide 26 - Menyusun Research Question dan Hipotesis

Contoh conceptual model penelitian multimodal:

- Variabel bebas: jenis modalitas.
- Variabel terikat: performa, workload, presence, UX.
- Mediator: pemahaman pengguna, beban kognitif.
- Moderator: kompleksitas tugas, pengalaman pengguna, konteks.

Contoh RQ:

- RQ1: Apakah kombinasi voice + gaze lebih efektif daripada voice-only untuk seleksi objek dalam VR?
- RQ2: Bagaimana haptic feedback memengaruhi spatial awareness tanpa menambah workload?
- RQ3: Faktor apa yang membuat pengguna berpindah dari satu modalitas ke modalitas lain?

Rumuskan hipotesis berdasarkan teori atau temuan empiris, bukan berdasarkan asumsi bahwa teknologi baru pasti unggul.

---

# Slide 27 - Contoh Desain Eksperimen: 3 × 2

Ilustrasi rancangan within-subject untuk studi multimodal:

| Aspek | Rancangan |
|---|---|
| Faktor A | Modalitas: voice-only, gaze-only, voice+gaze |
| Faktor B | Kompleksitas tugas: rendah, tinggi |
| Desain | Within-subject dengan counterbalancing |
| Partisipan | 24–30 orang, direkrut berdasarkan kriteria |
| Prosedur | Training, kalibrasi, tugas per kondisi, kuesioner |
| Variabel terikat | Waktu penyelesaian, error, task load, preference |
| Kontrol | Urutan antar kondisi diacak, instruksi seragam |

Penting:

- Tetapkan effect size yang diharapkan.
- Justifikasi jumlah partisipan.
- Dokumentasikan protokol secara lengkap agar dapat direplikasi.

---

# Slide 28 - Workflow Pengumpulan Data

Research progress minggu ini: **data collection**.

Langkah umum studi multimodal/spatial:

1. Siapkan perangkat dan lingkungan.
2. Lakukan pilot singkat.
3. Minta informed consent.
4. Kumpulkan data demografi dan pengalaman partisipan.
5. Kalibrasi sensor: gaze, mikrofon, controller, atau kamera.
6. Berikan training tugas.
7. Jalankan tiap kondisi secara terkontrol.
8. Log data otomatis dan rekam observasi.
9. Beri kuesioner setelah tiap kondisi.
10. Lakukan debrief dan simpan data anonim.

Catatan: data yang tidak terdokumentasi baik tidak dapat menjadi evidence yang sah.

---

# Slide 29 - Pencatatan dan Sinkronisasi Data Multimodal

Data multimodal harus memiliki **timestamp yang dapat disinkronkan**.

Contoh log peristiwa voice dan gaze:

| time_ms | participant | condition | modality | event | value |
|---:|---|---|---|---|---|
| 1020 | P01 | vg | speech | referent | "file" |
| 1065 | P01 | vg | gaze | target | "A" |
| 1070 | P01 | vg | system | selected | "fileA" |

Untuk analisis multimodal fusion:

- Gunakan satu sumber jam.
- Catat raw sensor dan hasil interpretasi.
- Simpan data dictionary untuk setiap event.
- Tandai kondisi dan trial.
- Lakukan video recording sebagai backup untuk labeling manual.

---

# Slide 30 - Pseudocode Analisis Sederhana

Berikut contoh kerangka analisis untuk membandingkan kondisi modalitas.

```
for condition in [voice, gaze, voice_gaze]:
    trials = load_trials(condition)

    for trial in trials:
        trial.time = trial.end_time - trial.start_time
        trial.correct = is_selection_correct(trial)

    report.time_avg = mean(trials.time)
    report.error_rate = mean(not trial.correct)
    report.workload = mean(trials.nasa_tlx)

compare(report.voice, report.gaze, report.voice_gaze)
```

Catatan:

- Gunakan metode statistik dari Pertemuan 13 setelah data terkumpul.
- Jangan hanya membandingkan rata-rata tanpa memeriksa distribusi dan asumsi.

---

# Slide 31 - Instrumen Evaluasi untuk Studi Multimodal/Spatial

| Jenis | Contoh |
|---|---|
| Performa tugas | Completion time, error rate, task success, path efficiency |
| Gerakan | Trajectory tangan/kepala, jumlah gesture, arah pandangan |
| Beban kerja | NASA-TLX |
| UX/usability | System Usability Scale, UEQ |
| Presence | Kuesioner presence yang sudah divalidasi |
| Preferensi | Ranking modalitas, pilihan akhir pengguna |
| Data kualitatif | Think-aloud, wawancara singkat, observasi video |

Gunakan instrumen **sesuai dengan konstruk** yang ingin diukur. Jangan mencampur pengukuran performa dengan pendapat subjektif tanpa pelabelan yang jelas.

---

# Slide 32 - Multimodal Tidak Selalu Lebih Baik

Klaim umum: “multimodal lebih baik daripada single-modal” harus dikritisi.

- Multimodal dapat mempercepat interaksi jika modalitas saling melengkapi.
- Multimodal dapat memperlambat interaksi jika pengguna harus mengoordinasikan dua sumber informasi.
- Redundansi dapat membantu akurasi, tetapi dapat menambah kebisingan dan beban kognitif.
- Efek multimodal bergantung pada:
  - Jenis tugas.
  - Kemampuan pengguna.
  - Kualitas pengenalan teknologi.
  - Konteks penggunaan.

Kontribusi ilmiah muncul ketika penelitian menjelaskan **kapan dan mengapa** suatu kombinasi modalitas lebih baik.

---

# Slide 33 - Peluang Riset: Multimodal, Spatial, Emerging

Beberapa peluang penelitian yang relevan dengan state of the art HCI:

- Seleksi objek multimodal di VR dengan voice + gaze + hand tracking.
- Haptic feedback untuk membantu navigasi pengguna dengan kebutuhan aksesibilitas.
- Adaptive modality suggestion berdasarkan konteks pengguna.
- Multimodal interaction dengan LLM atau generative AI.
- Pengaruh presence terhadap trust pada robot kolaboratif.
- Evaluasi workload pada wearable micro-interaction.
- Studi longitudinal pengguna ubiquitous computing.

Peluang riset harus dikaitkan dengan **research gap**, bukan hanya rasa ingin tahu terhadap teknologi baru.

---

# Slide 34 - Aktivitas: Emerging HCI Discussion

Diskusi dirancang untuk mengasah critical thinking terhadap paper multimodal/spatial.

Pertanyaan diskusi:

1. Apa interaction problem yang ditangani oleh modalitas pada paper tersebut?
2. Konstruk apa yang diukur: usability, workload, presence, behavior, atau UX?
3. Apakah instrumen dan desain studi sesuai dengan research question?
4. Bagaimana penulis memastikan bahwa efek yang diamati berasal dari modalitas, bukan dari teknologi lain?
5. Apakah solusi multimodal dapat diakses oleh pengguna dengan kemampuan beragam?

Sistematika: identifikasi klaim paper, kaji evidence, lalu rumuskan threat to validity.

---

# Slide 35 - Jembatan ke Pertemuan 12: Inclusive, Accessible & Responsible HCI

- Modalitas yang baik untuk rata-rata pengguna belum tentu baik untuk semua orang.
- Gesture membebani pengguna dengan keterbatasan motorik.
- Voice kurang dapat diandalkan bagi pengguna dengan gangguan bicara.
- Gaze memerlukan kalibrasi yang mungkin tidak berhasil pada sebagian kondisi mata.
- VR dan spatial interaction dapat menimbulkan cybersickness.
- Wearable dan ubiquitous computing menimbulkan risiko privasi.

Pertemuan 12 akan membahas inclusive design, accessibility, assistive technology, serta responsible HCI.

---

# Slide 36 - Simpulan Pertemuan 11

- Modalitas adalah **variabel desain dan variabel penelitian**, bukan sekadar teknologi.
- Multimodal interaction menggabungkan beberapa saluran untuk menciptakan makna yang lebih kaya.
- Spatial dan emerging interaction menuntut evaluasi yang tidak hanya mengukur performa, tetapi juga presence, workload, kenyamanan, dan pengalaman subjektif.
- Pemilihan modalitas harus berdasar pada tugas, pengguna, dan konteks.
- Saat ini progress penelitian Anda berada pada tahap **data collection**.

Pastikan data yang dikumpulkan bersih, tersinkronisasi, terdokumentasi, dan siap dianalisis pada pertemuan berikutnya.

---

# Slide 37 - Penutup

TERIMA KASIH

Pertemuan berikutnya

**Inclusive, Accessible & Responsible HCI**