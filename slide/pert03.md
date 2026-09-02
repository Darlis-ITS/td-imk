# Slide 00 - Cover

EF235131 - Topik Dalam Interaksi Manusia dan Komputer
Pertemuan 03

## Human Factors, Cognition & User Behavior

Dr. Darlis Herumurti, Hadziq Fabroyir Ph.D

Departemen Teknik Informatika - ITS

---

# Slide 01 - Mengapa Human Factors dan Perilaku Pengguna Penting?

Materi berada dalam alur perkuliahan:

**HCI Modern → Human-Centered Design → Human Factors & Cognition → HCI Research**

Pertemuan sebelumnya memberikan perangkat analisis desain: *affordance*, *signifier*, *feedback*, *mapping*, *constraint*, dan *human-centered design*.

Pertemuan ini melengkapi perangkat tersebut dengan pemahaman tentang:

- bagaimana manusia memproses informasi;
- keterbatasan kognitif;
- peran persepsi, perhatian, memori, dan beban kognitif;
- bagaimana manusia mengambil keputusan, membangun model mental, belajar, dan membuat error;
- bagaimana semua itu membentuk perilaku pengguna saat berinteraksi dengan teknologi.

Pada akhir pertemuan, Anda diharapkan mampu menjadikan fenomena kognitif dan perilaku sebagai dasar untuk merumuskan **candidate research problem** penelitian HCI.

---

# Slide 02 - Fokus Utama Pertemuan

Model hubungan inti yang menjadi lenses analisis:

```text
Human Characteristics × Task × Interface × Context
                        ↓
                Interaction Behavior
```

Artinya, perilaku interaksi tidak dapat dijelaskan hanya dari tampilan antarmuka.

| Faktor | Contoh |
|---|---|
| Karakteristik manusia | persepsi, atensi, memori, beban kognitif, pengalaman, usia, motivasi |
| Karakteristik tugas | kompleksitas, frekuensi, urgensi, risiko error |
| Karakteristik antarmuka | modality, struktur menu, feedback, default, visual layout |
| Konteks | lingkungan fisik, gangguan, tekanan waktu, setting sosial |

Fokus utama pertemuan:

**Bagaimana karakteristik manusia berinteraksi dengan faktor lain sehingga menghasilkan perilaku tertentu yang dapat diamati, diukur, dan diteliti?**

---

# Slide 03 - Human Information Processing: Manusia Sebagai Pemroses Informasi

Pendekatan klasik dalam HCI memandang manusia seperti sistem pemrosesan informasi.

```text
 Stimulus ──► Sensation ──► Perception ──► Working Memory ──► Decision ──► Action
                                  ▲            │    ▲
                                  │            │    │
                            Attention      Long-Term Memory
                                             (pengetahuan)
```

Prinsip penting:

- kanal penerimaan informasi terbatas;
- hanya sebagian stimulus yang diproses secara sadar;
- informasi diproses melalui tahapan persepsi, kognisi, dan respons;
- sumber daya kognitif seperti perhatian dan memori kerja bersifat terbatas.

Keterbatasan ini bukan “kesalahan pengguna”, melainkan karakteristik dasar manusia yang harus diakomodasi oleh desain.

Dalam penelitian, model ini membantu menjelaskan **mengapa** perilaku tertentu terjadi, bukan sekadar **apa** yang terjadi.

---

# Slide 04 - Perception: Menerima dan Menafsirkan Stimulus

Persepsi adalah proses menafsirkan informasi sensorik menjadi makna.

Persepsi bukan sekadar melihat, mendengar, atau menyentuh.

| Modalitas | Contoh dalam interaksi |
|---|---|
| Visual | warna, bentuk, ukuran, gerakan, tata letak |
| Auditori | nada notifikasi, suara konfirmasi |
| Haptik | getaran, tekstur permukaan, force feedback |
| Kinestetik | gerakan tangan/mouse, gestur |

Dalam HCI, persepsi berkaitan dengan:

- mudah tidaknya suatu objek dikenali;
- cepat tidaknya informasi ditemukan;
- benar tidaknya interpretasi terhadap status sistem.

Hubungan dengan pertemuan sebelumnya: konsep *affordance* dan *signifier* bekerja melalui persepsi. Objek harus **dipersepsikan** sebagai sesuatu yang dapat diklik, digeser, atau diinput.

---

# Slide 05 - Persepsi Visual dan Prinsip Gestalt

Manusia tidak mempersepsikan elemen visual secara terpisah, tetapi sebagai pola.

Prinsip Gestalt yang sering digunakan dalam desain antarmuka:

| Prinsip | Penjelasan | Implikasi Desain |
|---|---|---|
| Proximity | objek berdekatan dianggap satu grup | penempatan tombol atau form |
| Similarity | objek serupa dianggap satu grup | konsistensi warna/ikon |
| Continuity | bentuk yang sejajar dianggap satu alur | navigasi, alur visual |
| Closure | pola tidak lengkap dilengkapi oleh pikiran | ikon sederhana |
| Figure-ground | fokus pada objek vs latar | hierarki visual, overlay |

Persepsi visual juga dipengaruhi oleh:

- kontras dan ukuran;
- posisi pada layar (sekitar area fokus);
- motion atau perubahan yang mencolok;
- warna, terutama bagi pengguna dengan buta warna.

Persepsi yang salah terhadap antarmuka dapat menyebabkan error, kebingungan, dan beban kognitif.

---

# Slide 06 - Attention: Gerbang Pemrosesan Informasi

Attention adalah proses seleksi informasi yang akan diproses lebih lanjut.

Karena kapasitas pemrosesan terbatas, manusia tidak dapat memperhatikan semua rangsangan secara bersamaan.

| Jenis Attention | Karakteristik | Contoh dalam interaksi |
|---|---|---|
| Selective | memilih satu sumber informasi | fokus membaca artikel di tengah layout yang ramai |
| Divided | membagi perhatian ke beberapa tugas | browsing sambil mendengarkan meeting online |
| Sustained | mempertahankan perhatian dalam waktu lama | pengawasan dashboard, online exam |

Fenomena terkait yang relevan untuk HCI:

- *inattentional blindness*: objek yang jelas terlihat tetapi tidak disadari karena perhatian terarah ke hal lain;
- *change blindness*: perubahan besar pada layar tidak disadari ketika terjadi bersamaan dengan gangguan.

Pertanyaan riset yang sering muncul:

**Bagaimana desain antarmuka memengaruhi alokasi perhatian pengguna?**

---

# Slide 07 - Attention, Interruption, dan Multitasking

Interruption adalah salah satu masalah perilaku pengguna yang paling sering dijumpai.

Perhatian yang teralih dapat menyebabkan:

- waktu resume lebih lama setelah kembali ke tugas utama;
- peningkatan error;
- pengalaman yang lebih melelahkan.

Temuan umum dari penelitian HCI:

| Konsep | Dampak Desain |
|---|---|
| Notification pop-up | mengganggu alur, tetapi kadang diperlukan untuk informasi kritis |
| Interruption pada saat transisi sub-task | lebih mudah dipulihkan daripada saat fokus dalam |
| Multitasking | umumnya menurunkan akurasi dan kecepatan |
| Visual salience | menarik perhatian, tetapi belum tentu sesuai prioritas pengguna |

Pertimbangan desain:

- berapa tingkat kepentingan/urgensi pesan?
- dapatkah interupsi ditunda sampai waktu yang lebih aman?
- apakah ada mode “fokus” yang disediakan sistem?

Perilaku seperti **menunda membuka notifikasi**, **mengabaikan pop-up**, atau **keluar dari aplikasi** adalah perilaku yang dapat diamati dan diukur.

---

# Slide 08 - Memory: Sensori, Kerja, dan Jangka Panjang

Memori adalah fondasi dari hampir semua aktivitas kognitif dalam interaksi.

```text
Sensory Memory ──► Working Memory ──► Long-Term Memory
   (sangat singkat)   (aktif, terbatas)    (relatif permanen)
        ▲                    │                    │
        └──── attention ─────┴──── rehearsal ─────┘
```

| Jenis Memori | Peran dalam Interaksi |
|---|---|
| Sensory | menahan stimulus sangat singkat sebelum diproses |
| Working memory | menyimpan informasi yang sedang diproses, misalnya angka pada form |
| Long-term memory | menyimpan pengetahuan prosedur penggunaan, konsep sistem, dan pengalaman masa lalu |

Masalah muncul ketika antarmuka menuntut terlalu banyak hafalan, atau tidak konsisten dengan pengetahuan yang sudah dimiliki pengguna.

Desain yang baik seharusnya:

- tidak membebani memori yang bersifat sementara;
- memanfaatkan pengetahuan yang sudah ada;
- menyediakan petunjuk saat dibutuhkan.

---

# Slide 09 - Working Memory: Kapasitas Terbatas yang Menentukan Beban Interaksi

Working memory menyimpan dan memanipulasi informasi saat ini.

Ciri utama:

- kapasitas sangat terbatas;
- informasi mudah hilang jika tidak dipelihara;
- terganggu oleh tugas ganda.

Salah satu strategi efektif adalah **chunking**: mengelompokkan informasi menjadi unit lebih besar.

Contoh:

- nomor rekening ditampilkan sebagai `1234 5678 9012` bukan `123456789012`;
- checkout dibagi menjadi beberapa langkah pendek;
- kode error ditampilkan dengan makna, bukan sekadar angka.

Implikasi untuk penelitian dan desain:

| Jangan memaksa pengguna | Sebaiknya sistem |
|---|---|
| mengingat banyak aturan | menampilkan informasi relevan saat dibutuhkan |
| menghafal urutan panjang | menyediakan visualisasi progress |
| membandingkan informasi antar halaman | menyediakan ringkasan atau sticky summary |

Working memory yang terbebani tampak pada perilaku: ragu-ragu, membuka ulang halaman, salah input, atau menggulir bolak-balik.

---

# Slide 10 - Long-Term Memory: Recognition vs Recall

Setelah informasi dipelajari, pengetahuan disimpan dalam long-term memory.

Pengambilan kembali informasi dapat terjadi melalui dua jalur utama:

| Jalur | Contoh | Beban Kognitif |
|---|---|---|
| Recognition (mengenali) | memilih perintah dari menu | lebih rendah |
| Recall (mengingat kembali) | mengetik shortcut dari hafalan | lebih tinggi |

Desain umumnya sebaiknya mengandalkan *recognition* daripada *recall*.

Contoh:

- menu, toolbar, atau sidebar lebih mudah daripada perintah yang harus dihafal;
- label ikon membantu pengguna yang baru mengenal fungsi;
- language yang konsisten membantu pengguna menggunakan pengetahuan sebelumnya.

Akan tetapi, pengguna ahli terkadang lebih cepat menggunakan *recall*, misalnya shortcut keyboard.

Pertanyaan riset potensial:

**Kapan combobox, command palette, atau shortcut lebih menguntungkan untuk tipe pengguna dan tugas tertentu?**

---

# Slide 11 - Implikasi Desain untuk Memory

Antarmuka yang baik adalah sistem yang “ingat”, sehingga pengguna tidak perlu mengingat terlalu banyak.

| Prinsip | Implementasi |
|---|---|
| Minimalkan beban memori | sediakan pilihan yang terlihat, bukan mengandalkan hafalan |
| Konsistensi | letakkan fungsi yang sama di posisi yang sama |
| Gunakan pola yang familier | ikuti konvensi umum: ikon home, keranjang belanja |
| Sediakan external memory | riwayat pencarian, autocomplete, draft tersimpan |
| Pulihkan konteks | kembalikan posisi kursor atau halaman terakhir setelah login |

Perilaku yang mengindikasikan beban memori terlalu tinggi:

- pengguna kembali ke halaman awal berulang kali;
- pengguna menulis di kertas sebelum mengisi form;
- pengguna salah memasukkan data;
- pengguna mengeluh “saya lupa sampai mana”.

Perilaku tersebut dapat dijadikan data untuk mengidentifikasi **candidate research problem**.

---

# Slide 12 - Cognitive Load: Sumber Daya Kognitif yang Terpakai

Cognitive load adalah besarnya tuntutan pemrosesan yang dikenakan pada working memory.

Tiga jenis cognitive load:

| Jenis | Sumber | Contoh dalam antarmuka |
|---|---|---|
| Intrinsic load | kompleksitas bawaan materi/tugas | memahami hubungan antar bagian dari suatu sistem |
| Extraneous load | desain yang tidak perlu dan tidak mendukung pemahaman | layout yang membingungkan, istilah ambigu, informasi redundan |
| Germane load | upaya membangun pemahaman dan skema mental | proses belajar dari visualisasi, contoh, dan analogi |

Desain yang baik tidak selalu berarti “lebih sedikit informasi”, tetapi berusaha:

- menekan extraneous load;
- mengelola intrinsic load dengan strukturisasi;
- mendukung germane load agar pengguna belajar.

Dalam penelitian, cognitive load sering menjadi konstruk yang menjelaskan **mengapa** suatu desain lebih lambat, lebih rawan error, atau lebih sulit dipelajari.

---

# Slide 13 - Strategi Mengelola Cognitive Load

Terapkan strategi berikut untuk menurunkan beban kognitif pengguna:

| Strategi | Contoh Desain |
|---|---|
| Segmentasi | bagi proses panjang menjadi tahapan kecil |
| Reduksi informasi tidak relevan | jangan tampilkan seluruh fitur sekaligus |
| Sediakan struktur | gunakan hierarki, grouping, atau progresif disclosure |
| Gunakan contoh dan analogi | “folder”, “keranjang”, “share” membantu pemahaman |
| Berikan feedback yang informatif | jelaskan apa yang terjadi dan apa langkah berikutnya |
| Konsistensi visual dan istilah | mendukung pengenalan dan mengurangi proses ulang |

Perhatikan bahwa cognitive load tidak selalu teramati langsung.

Kita perlu mengukurnya melalui:

- waktu dan akurasi;
- subjektif setelah penggunaan;
- perilaku seperti mengulang langkah, menggulir, atau berhenti lama;
- pengukuran fisiologis jika memungkinkan.

Cognitive load menjadi jembatan antara **desain antarmuka** dan **perilaku pengguna**.

---

# Slide 14 - Decision Making dalam Interaksi

Pengguna tidak selalu membuat keputusan secara rasional dan optimal.

Konsep penting:

- rasionalitas terbatas;
- pengguna mencari solusi yang “cukup baik”, bukan optimal;
- pengguna sering menggunakan jalan pintas mental atau heuristics.

| Heuristik | Contoh Perilaku |
|---|---|
| Availability | memilih opsi paling mudah diingat |
| Anchoring | keputusan dipengaruhi nilai awal yang ditampilkan |
| Status quo | cenderung mempertahankan pilihan default |
| Framing | respons berbeda terhadap informasi dengan cara penyajian berbeda |
| Satisficing | berhenti mencari setelah menemukan pilihan yang cukup memadai |

Keputusan muncul dalam berbagai konteks:

- memilih paket layanan;
- menilai kredibilitas hasil pencarian;
- mempercayai rekomendasi sistem;
- menetapkan pengaturan privasi.

Desain harus memperhitungkan bahwa keputusan pengguna dipengaruhi oleh bagaimana pilihan ditampilkan, bukan hanya apa pilihannya.

---

# Slide 15 - Choice Architecture dan Desain Keputusan

Dengan memahami decision making, desain dapat membantu pengguna mengambil keputusan yang lebih baik.

| Teknik | Penjelasan | Contoh |
|---|---|---|
| Default yang bijak | pilihan awal mengurangi usaha | default privasi ketat |
| Feedback terhadap konsekuensi | pengguna melihat dampak | ringkasan biaya sebelum checkout |
| Penyederhanaan pilihan | mengurangi beban perbandingan | batasi jumlah opsi pada satu layar |
| Framing yang transparan | sampaikan risiko dan manfaat secara jujur | notifikasi risiko keamanan |
| Sediakan alas untuk menunda | mencegah keputusan impulsif | tombol “tinjau lagi” |

Namun, teknik yang sama dapat disalahgunakan menjadi **dark patterns**, misalnya:

- memilih opt-out yang sulit;
- menampilkan opsi menyesatkan;
- memperbesar tombol yang menguntungkan sistem;
- menyembunyikan biaya tambahan.

Ini membuka peluang riset:

**Bagaimana pengguna mengambil keputusan ketika antarmuka menggunakan taktik yang sebagian menyesatkan?**

---

# Slide 16 - Mental Models: Bagaimana Pengguna Memahami Sistem

Mental model adalah representasi internal pengguna tentang cara kerja suatu sistem.

| Konsep | Penjelasan |
|---|---|
| Mental model pengguna | apa yang user percaya tentang bagaimana sistem bekerja |
| Conceptual model | model yang dirancang oleh perancang/sistem |
| System image | apa yang dapat dilihat, didengar, dan dialami dari sistem |
| Discoverability | sejauh mana model sistem dapat dipelajari |

Interaksi yang baik terjadi ketika:

```text
Conceptual Model ──► System Image ──► User Mental Model
      (desainer)      (produk/UI)      (dalam pikiran user)
```

Ketidakcocokan antara model mental dan perilaku sistem menghasilkan:

- kebingungan;
- tebakan yang salah;
- error yang sebenarnya bukan kesalahan user.

Contoh:

- pengguna mengira file sudah terhapus permanen padahal ada di recycle bin;
- pengguna mengira semua data lokal otomatis tersinkron;
- pengguna mengira AI chatbot memahami konteks percakapan sebagai manusia.

---

# Slide 17 - Membangun Mental Model yang Tepat Melalui Desain

Antarmuka dapat membantu pengguna membangun mental model yang benar.

| Cara | Contoh |
|---|---|
| Gunakan metafora yang konsisten | folder, file, halaman, kirim |
| Tampilkan status sistem | “Menyimpan...”, “Sinkron”, “Draft” |
| Berikan visualisasi struktur | breadcrumb, timeline, peta situs |
| Beri feedback langsung | aksi segera menunjukkan akibat |
| Jangan mengubah aturan di tengah jalan | mode yang tidak terlihat → mode error |

Perilaku yang menunjukkan mental model salah:

- user mencari fitur di tempat yang menurutnya logis, bukan tempat sistem menyediakannya;
- user melakukan aksi yang percaya akan menyelesaikan tugas, tetapi gagal;
- user mengulangi kesalahan yang sama karena memahami sistem secara keliru.

Dalam penelitian, kita dapat mengungkap mental model melalui:

- think-aloud;
- wawancara;
- prediksi user terhadap hasil aksi;
- analisis error.

---

# Slide 18 - Learning: Bagaimana Pengguna Mempelajari Teknologi

Dalam interaksi, pengguna terus belajar:

- belajar menggunakan fitur;
- belajar dari error;
- belajar dari umpan balik sistem;
- belajar dari tutorial atau bantuan.

Karakteristik belajar pengguna:

- sering dilakukan dengan mencoba-coba;
- dipengaruhi analogi dari pengalaman sistem lain;
- diperkuat oleh feedback yang segera dan jelas;
- dipengaruhi desain yang mendukung kepercayaan diri.

Desain untuk belajar:

| Prinsip | Implementasi |
|---|---|
| Onboarding singkat | demonstrasi tanpa menghalangi tugas utama |
| Progressive disclosure | tampilkan fitur lanjutan setelah kebutuhan muncul |
| Undo dan coba-coba yang aman | mendorong eksplorasi tanpa takut konsekuensi |
| Feedback berbasis langkah | bantu user memahami hasil tindakannya |

Learning dapat diukur dari peningkatan kecepatan antar percobaan, penurunan error, atau kemampuan menyelesaikan tugas baru.

---

# Slide 19 - Pengguna: Dari Novice Hingga Expert

Kebutuhan dan perilaku pengguna berubah seiring pengalaman.

| Level | Kebutuhan | Perilaku Umum |
|---|---|---|
| Novice | petunjuk, kejelasan, keamanan | lambat, membaca label, sering meminta bantuan |
| Intermediate | efisiensi sedang, fitur navigasi | hafal sebagian perintah, menggunakan menu |
| Expert | akses cepat, personalisasi | menggunakan shortcut, eksplorasi fitur dalam |

Kesalahan umum desain:

- dirancang hanya untuk novice → pengguna ahli menjadi lambat;
- dirancang hanya untuk expert → pengguna baru tersesat;
- berasumsi “average user” yang sebenarnya tidak ada.

Lingkungan belajar yang baik memungkinkan pengguna berpindah level:

- menu dapat dipercepat dengan shortcut;
- shortcut ditampilkan beriringan dengan label;
- sistem mempelajari frekuensi penggunaan fitur.

Dalam riset, tanyakan:

**Apakah efek suatu desain berbeda antara pengguna baru dan pengguna berpengalaman?**

---

# Slide 20 - Human Error: Sumber dan Jenis Error

Error adalah perilaku yang tidak sesuai dengan tujuan.

Error bukan sekadar “kesalahan manusia” — sering kali desainlah yang memicunya.

| Jenis Error | Penjelasan | Contoh |
|---|---|---|
| Slip | tahu tujuannya, tetapi eksekusi salah | salah klik tombol sebelah |
| Mistake | salah memahami situasi/tujuan | memilih menu yang salah karena label ambigu |
| Lapse | lupa melakukan langkah | tidak menekan Save |
| Violation | sengaja menyimpang dari prosedur | melewati proses konfirmasi karena terlalu sering |

Konsep terkait:

- *mode error*: user melakukan aksi sesuai model yang salah karena sistem berada dalam mode berbeda;
- *design error*: struktur antarmuka mendorong user melakukan kesalahan.

Data error dapat dikumpulkan dari:

- log sistem;
- pengamatan;
- think-aloud;
- studi usability.

---

# Slide 21 - Desain yang Mencegah dan Mengatasi Error

Prinsip desain untuk error:

1. **Cegah sebelum terjadi**
   - gunakan constraints dan forcing function;
   - matikan tombol yang tidak valid;
   - buat label yang jelas.

2. **Buat error mudah dikenali**
   - feedback segera;
   - pesan error yang menjelaskan penyebab dan solusi;
   - hindari pesan ambigu seperti “Error 500”.

3. **Buat error mudah diperbaiki**
   - undo;
   - simpan draft;
   - konfirmasi hanya untuk aksi berisiko tinggi.

4. **Jangan menghukum user**
   - hindari mengosongkan form karena satu field salah;
   - hindari modal yang tidak bisa ditutup.

Pertanyaan riset:

**Bagaimana jenis umpan balik error memengaruhi kecepatan pemulihan, frustrasi, dan kepercayaan pengguna?**

---

# Slide 22 - Individual Differences: Satu Desain Tidak Cocok untuk Semua

Pengguna berbeda dalam banyak dimensi yang memengaruhi interaksi.

| Dimensi | Contoh Variasi |
|---|---|
| Usia | anak-anak, dewasa muda, lansia |
| Pengalaman teknologi | digital native, pengguna baru |
| Kemampuan kognitif | memori, kecepatan persepsi, literasi |
| Kemampuan sensorimotor | penglihatan, pendengaran, motorik |
| Bahasa dan budaya | arah baca, makna simbol, norma sosial |
| Motivasi dan emosi | terpaksa vs sukarela, cemas vs tenang |

Implikasi:

- kecepatan dan akurasi bukan semata akibat desain, tetapi juga siapa penggunanya;
- agregasi rata-rata dapat menutupi kelompok yang tertinggal;
- desain adaptif atau personalisasi muncul dari pemahaman perbedaan ini.

Pertemuan 12 akan membahas inklusivitas dan aksesibilitas secara lebih mendalam.

Pada pertemuan ini, ingatlah:

> Variasi antar individu adalah sumber utama variansi dalam data perilaku.

---

# Slide 23 - Context of Use: Lingkungan Membentuk Perilaku

Perilaku interaksi tidak terjadi dalam ruang hampa.

| Konteks | Efek pada Perilaku |
|---|---|
| Fisik | layar kecil, cahaya terang, posisi berdiri memengaruhi perhatian dan input |
| Sosial | pengguna menjaga privasi, atau menunjukkan aktivitas pada orang lain |
| Temporal | singkat dan tergesa vs lama dan santai |
| Tugas | risiko tinggi membuat user lebih berhati-hati |
| Organisasi/kultural | norma penggunaan teknologi berbeda antar institusi |

Contoh kasus:

- aplikasi mobile banking saat mengantre dapat menyebabkan lebih banyak typo;
- voice assistant di ruang publik jarang digunakan untuk informasi privat;
- dashboard klinis digunakan di bawah tekanan waktu dan gangguan;
- aplikasi belajar digunakan dalam sesi singkat saat istirahat.

Konteks menjelaskan mengapa hasil penelitian di satu setting belum tentu tergeneralisasi ke setting lain.

External validity dan ecological validity akan dibahas lebih lanjut pada pertemuan 14.

---

# Slide 24 - User Behavior: Perilaku Interaksi yang Dapat Diamati

User behavior adalah manifestasi nyata dari proses kognitif, tujuan, dan konteks.

Yang termasuk perilaku:

- mengklik, mengetik, menggulir, menyeret;
- membuka atau menutup aplikasi;
- mencari bantuan;
- mengulang langkah;
- meninggalkan halaman;
- mengubah pengaturan;
- menyetujui atau menolak permintaan sistem.

| Pola Perilaku | Indikasi Kognitif |
|---|---|
| Menjelajah dengan cepat | eksplorasi, impulsif, atau kebingungan |
| Berhenti lama sebelum tindakan | pengambilan keputusan, beban kognitif |
| Backtracking | model mental tidak sesuai |
| Menggunakan menu bantuan | pengetahuan belum terbentuk |
| Mengabaikan informasi peringatan | habituation, kelelahan peringatan |

Perilaku adalah jendela menuju kognisi.

Namun, jangan asumsikan: perilaku yang sama dapat berasal dari proses kognitif yang berbeda.

---

# Slide 25 - Behavioral Data: Data yang Mungkin Dikumpulkan dalam Penelitian

Data perilaku berbeda dari data opini.

Data perilaku merekam apa yang pengguna lakukan, bukan apa yang ia katakan.

| Jenis Data | Contoh Instrumen |
|---|---|
| Interaction log | timestamp setiap klik, fokus field, scroll |
| Clickstream | urutan halaman yang dikunjungi |
| Eye tracking | durasi fiksasi, jumlah saccade, area yang dilihat |
| Mouse tracking | gerakan kursor, kecepatan, jejak |
| Keyboard dynamics | jeda antar penekanan tombol |
| Screen atau audio recording | video sesi, think-aloud |
| Sensor | akselerometer, proximity, lokasi |

Data subjektif tetap penting, tetapi tidak menggantikan data perilaku.

Perbedaan utama:

| Self-report | Behavioral data |
|---|---|
| “Saya merasa mudah” | waktu penyelesaian aktual lebih lama |
| Bias sosial dan ingatan | lebih langsung merekam kejadian |
| mudah dikumpulkan | memerlukan instrumentasi dan etika |

---

# Slide 26 - Behavioral Measures yang Umum Digunakan

Ukuran perilaku membantu menjawab pertanyaan riset secara kuantitatif.

| Dimensi | Contoh Measure |
|---|---|
| Outcome tugas | successful completion, task time, error rate |
| Efisiensi | jumlah langkah, waktu per langkah |
| Proses | path analysis, order of actions, revisits |
| Engagement | dwell time, session length, return visits |
| Cognitive indicator | hesitation, backtracking, repeated reading, gaze fixation |
| Recovery | lama waktu setelah error, jumlah percobaan ulang |

Contoh operasionalisasi:

- perturbasi kecil pada mouse movement dapat mengindikasikan kebingungan;
- penurunan kecepatan setelah gangguan dapat mengindikasikan interupsi;
- kegagalan menemukan menu meskipun tersedia dapat mengindikasikan masalah discoverability.

Ukuran yang baik harus:

- valid: benar-benar mengukur konsep yang dimaksud;
- reliabel: stabil dalam kondisi yang sama;
- sensitif: dapat menangkap perbedaan yang penting;
- etis: tidak menyesatkan atau merugikan partisipan.

---

# Slide 27 - Workflow dari Human Factors ke Penelitian

Pemahaman human factors digunakan dalam alur kerja berikut:

```text
Observasi masalah interaksi
            │
            ▼
Kerangka teoretis: persepsi, attention, memory, load,
mental model, decision, error, individual differences
            │
            ▼
Hipotesis/prediksi perilaku
            │
            ▼
Desain atau modifikasi antarmuka / kondisi
            │
            ▼
Pengumpulan behavioral data
            │
            ▼
Analisis: performa, proses, error, self-report
            │
            ▼
Interpretasi / temuan
            │
            ▼
Research problem / implikasi desain / kontribusi ilmiah
```

Pola ini menghubungkan teori kognitif dengan metodologi penelitian yang akan dibahas pada pertemuan 4–7.

---

# Slide 28 - Contoh Studi Mini: Struktur Menu dan Cognitive Load

Ilustrasi bagaimana human factors menjadi penelitian HCI.

Masalah yang diamati:

- pengguna sering salah memilih menu;
- pengguna terlihat bingung setelah berpindah halaman.

Konstruk teoretis: working memory, cognitive load, mental model.

Pertanyaan riset awal:

- Apakah struktur menu yang lebih datar mengurangi beban kognitif dibandingkan menu bertingkat dalam menyelesaikan tugas?

Desain sederhana:

| Aspek | Rencana |
|---|---|
| Manipulasi | struktur menu: flat vs hierarchical |
| Tugas | menemukan fungsi tertentu |
| Dependent variable | task completion time, error, number of visits, NASA-TLX (sebagai pelengkap) |
| Partisipan | dibagi kelompok atau within-subject |
| Kontrol | urutan tugas, kompleksitas label, ukuran layar |

Hasil yang diharapkan:

- menjelaskan hubungan struktur informasi dengan perilaku;
- memberikan dasar untuk kandidat research problem dan pertanyaan riset yang lebih tajam.

---

# Slide 29 - Menuju Candidate Research Problem

Setelah memahami human factors dan user behavior, langkah berikutnya dalam research progress adalah **merumuskan candidate research problem**.

Candidate research problem adalah pernyataan awal tentang:

- adanya masalah interaksi yang nyata;
- siapa yang mengalaminya;
- dalam konteks apa;
- mengapa masalah itu terjadi;
- mengapa masalah itu penting.

Contoh candidate problem dari sudut human factors:

| Lensa | Fenomena |
|---|---|
| Attention | notifikasi membuat pengguna lama kembali ke tugas utama |
| Memory | pengguna lupa langkah di tengah proses multi-step |
| Cognitive load | dashboard kompleks memperlambat keputusan profesional |
| Mental model | pengguna salah memahami cara kerja fitur privasi |
| Human error | error serius terjadi karena mode yang tidak terlihat |
| Decision bias | pengguna selalu memilih default meskipun kurang menguntungkan |

---

# Slide 30 - Kriteria Candidate Research Problem yang Baik

Sebuah candidate problem perlu diuji kelayakannya.

| Kriteria | Pertanyaan Pemantik |
|---|---|
| Significance | Apakah masalah ini berdampak nyata bagi pengguna atau kelompok tertentu? |
| Novelty potensial | Apakah pemahaman kita tentang masalah ini belum lengkap? |
| Grounded in theory | Dapatkah masalah dijelaskan dengan konsep human factors/cognition? |
| Observable/measurable | Dapatkah perilaku atau dampaknya diamati dan diukur? |
| Researchable | Adakah peluang untuk merancang studi yang menjawabnya? |
| Feasible | Tersedia partisipan, waktu, instrumen, dan akses yang memadai? |

Hindari masalah yang hanya berbunyi:

- “aplikasi ini jelek”;
- “pengguna tidak suka tampilan baru”;
- “desain harus lebih user friendly”.

Masalah tersebut belum menyatakan **mengapa**, **bagaimana**, dan **mengapa penting**.

---

# Slide 31 - Merumuskan Problem Statement dari Perilaku

Template sederhana:

```text
Dalam [konteks], ketika [tipe pengguna] melakukan [tugas]
menggunakan [tipe sistem], terjadi [perilaku/outcome negatif],
yang diduga berhubungan dengan [human factor],
namun penjelasan/penanganannya belum memadai.
```

Contoh:

- Dalam perkantoran digital, ketika pekerja berpengalaman menerima banyak notifikasi saat menyelesaikan laporan, mereka menunjukkan peningkatan waktu resume dan error, yang diduga berkaitan dengan batas kapasitas perhatian;
- masih belum jelas bagaimana kebijakan penundaan notifikasi memengaruhi kualitas kerja jangka pendek.

Atau:

- Pada aplikasi kesehatan bagi lansia, ketika pengguna mengisi jadwal obat, banyak terjadi kesalahan input, yang diduga dipicu oleh beban memori kerja dan struktur form yang terdiri dari banyak langkah;
- belum ada desain alternatif yang secara sistematis dievaluasi.

---

# Slide 32 - Latihan Analisis Kasus Kecil

Pilih salah satu sistem yang dikenal: aplikasi bank, e-commerce, portal akademik, atau aplikasi kesehatan.

Gunakan lensa pertemuan ini:

| Lensa | Pertanyaan untuk Kasus |
|---|---|
| Perception | Apakah elemen penting mudah dikenali? |
| Attention | Di bagian mana perhatian pengguna teralih? |
| Memory | Apa yang harus diingat pengguna? |
| Cognitive load | Apakah terlalu banyak informasi tambahan? |
| Mental model | Apakah perilaku sistem sesuai dugaan pengguna? |
| Learning | Apakah pengguna baru dapat belajar dengan cepat? |
| Error | Kesalahan apa yang paling mungkin terjadi? |
| Context | Bagaimana kondisi nyata penggunaan sistem? |

Tugas Anda:

1. Identifikasi 1 perilaku bermasalah yang dapat diamati.
2. Jelaskan keterkaitannya dengan minimal satu konsep human factors.
3. Tuliskan candidate research problem dalam satu paragraf.
4. Sebutkan data perilaku apa yang dapat dikumpulkan untuk mendukung masalah itu.

---

# Slide 33 - Diskusi Kelas: Pertanyaan Pemantik

Diskusikan dalam kelompok, kemudian sampaikan argumentasi Anda.

1. Ketika pengguna bekerja lebih lambat, apakah selalu berarti cognitive load-nya tinggi?
   - Apa alternatif penjelasan lain?
   - Data apa yang diperlukan untuk membedakan penjelasan tersebut?

2. Kapan interupsi dapat diterima dalam desain?
   - Bagaimana menentukan bahwa suatu notifikasi layak mengalihkan perhatian?
   - Bagaimana efek interupsi berbeda menurut tipe tugas?

3. Apakah perilaku yang teramati cukup untuk menyusun research problem?
   - Mengapa kita perlu teori kognitif dalam analisis?
   - Apa akibatnya bila masalah dirumuskan tanpa teori?

4. Dalam studi Anda, faktor individual differences apa yang paling mungkin memengaruhi hasil?

Aktivitas ini melatih kemampuan analisis dan diskusi yang akan digunakan dalam critical paper review.

---

# Slide 34 - Ringkasan dan Jembatan ke Pertemuan Berikutnya

Poin utama pertemuan 03:

1. Perilaku interaksi adalah hasil interaksi karakteristik manusia, tugas, antarmuka, dan konteks.
2. Manusia memiliki keterbatasan dalam persepsi, perhatian, memori, dan sumber daya kognitif.
3. Proses kognitif tidak dapat diamati langsung, tetapi tercermin dalam perilaku.
4. Behavioral data adalah sumber evidence yang penting untuk penelitian HCI.
5. Pemahaman human factors memungkinkan kita mengidentifikasi masalah interaksi yang lebih dalam daripada sekadar penilaian subjektif.

Setelah pertemuan ini, Anda seharusnya memiliki **candidate research problem** yang akan diuji dalam alur:

```text
problem → literature → gap → research question
```

Pertemuan berikutnya, **Understanding HCI Research**, akan membedah struktur paper penelitian serta menjelaskan cara membangun research problem menjadi research question yang dapat diteliti.

---

# Slide 35 - Penutup

TERIMA KASIH

Pertemuan berikutnya
**Understanding HCI Research**