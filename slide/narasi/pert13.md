# Narasi Topik Dalam Interaksi Manusia dan Komputer - Pertemuan 13

## Data Analysis & Evidence in HCI

Sumber: markdown/pert13-data-analysis-evidence-in-hci.md

---

## Slide 000 - Cover

### Narasi

Slide ini menandai transisi strategis dalam siklus penelitian HCI tingkat magister, yaitu masuknya fase Data Analysis & Evidence in HCI. Setelah menyelesaikan proses desain instrumen, pilot testing, dan pengumpulan data pada minggu-minggu sebelumnya, perhatian kini dialihkan ke tahap kritis: mengolah temuan lapangan menjadi bukti ilmiah yang valid dan dapat dipertanggungjawabkan.

Pada jenjang pascasarjana, analisis data tidak hanya bersifat teknis, tetapi juga memerlukan kedalaman interpretasi. Mahasiswa dituntut untuk memilih metode analisis yang selaras dengan research question, baik itu pendekatan kuantitatif, kualitatif, maupun mixed methods. Fokus utamanya adalah membangun rantai logika yang menghubungkan data mentah, statistical test atau coding framework, hingga claim kontribusi penelitian yang orisinal.

Sebagai gambaran arah pembahasan, slide berikutnya akan memetakan posisi Pertemuan 13 dalam alur perkuliahan secara keseluruhan. Kita akan melihat bagaimana output dari data collection di Minggu 12 berubah menjadi preliminary findings di minggu ini, dan bagaimana temuan tersebut akan divalidasi serta dibahas aspek reproducibility dan etika penelitiannya di Pertemuan 14. Silakan siapkan dataset atau catatan lapangan Anda, karena kita akan langsung membahas langkah-langkah praktis dalam mengekstrak evidence yang kuat dari data HCI.

---

## Slide 001 - Posisi Pertemuan 13 dalam Alur Perkuliahan

### Narasi

Slide ini memetakan posisi pertemuan ke-13 dalam keseluruhan alur penelitian yang telah kita susun sejak awal semester. Secara garis besar, perkembangan materi mengikuti tahapan berurutan berikut:
- Minggu 1–7: Fondasi konsep HCI hingga perumusan research problem, identification of gap, research question, dan pemilihan metodologi.
- Minggu 8: Ujian Tengah Semester berupa defense Research Proposal.
- Minggu 9–12: Perancangan user study, penyusunan instrumen, pilot study, hingga pelaksanaan data collection.
- Minggu 13: Analisis data dan pembentukan evidence (posisi Anda saat ini).
- Minggu 14: Evaluasi validitas, reproducibility, dan etika penelitian.
- Minggu 15–16: Penyusunan kontribusi ilmiah dan penulisan paper final.

Fokus transisi penelitian Anda juga tergambar jelas dalam tabel kemajuan kerja. Pada tahap sebelumnya (Minggu 12), output utama Anda adalah data mentah beserta proses quality control-nya. Di pertemuan ini, fokus bergeser sepenuhnya ke data analysis dan preliminary findings. Langkah ini merupakan jembatan kritis sebelum Anda menyusun results, mendiskusikan validitas, serta mengakui limitations pada slide berikutnya. Ketelitian dalam fase ini mutlak diperlukan karena setiap bias atau error dalam pengolahan data akan langsung merambat ke kekuatan argumen ilmiah Anda.

Setelah memahami peta perjalanan penelitian ini, kita perlu menetapkan standar kompetensi yang harus dikuasai untuk menangani data tersebut secara rigor. Pada slide berikutnya, kita akan menguraikan delapan capaian pembelajaran spesifik yang mencakup seluruh spektrum analisis, mulai dari data cleaning, statistik deskriptif dan inferensial, hingga teknik analisis kualitatif, inter-rater agreement, dan triangulasi. Penguasaan terhadap alur transformasi dari data mentah menjadi evidence dan claim ilmiah inilah yang menjadi fondasi utama penelitian tingkat magister.

---

## Slide 002 - Capaian Pembelajaran Pertemuan 13

### Narasi

Pada pertemuan ini, kita akan membahas fondasi kritis dalam penelitian HCI, yaitu bagaimana mengubah kumpulan data mentah menjadi bukti ilmiah yang valid dan dapat dipertanggungjawabkan. Setelah melalui proses perancangan penelitian, pengumpulan data, hingga quality control di pertemuan-pertemuan sebelumnya, langkah selanjutnya adalah analisis sistematis untuk menghasilkan temuan yang bermakna.

Capaian pembelajaran dirancang secara bertahap untuk membekali Anda dengan kompetensi analitik yang komprehensif:
- Menjelaskan alur transformasi dari data mentah menjadi evidence dan claim ilmiah, menekankan bahwa ini adalah proses interpretasi kontekstual khas HCI.
- Melakukan data cleaning dan pemeriksaan kualitas data, memastikan dataset layak sebelum masuk ke tahap analisis lanjutan.
- Memilih dan menerapkan statistik deskriptif yang sesuai untuk data kuantitatif HCI, seperti mean, median, deviasi standar, dan distribusi frekuensi.
- Memahami konsep statistical inference, hypothesis testing, effect size, dan confidence interval sebagai dasar pengambilan keputusan berbasis data.
- Menganalisis data eksperimen dengan membandingkan kondisi antar-partisipan dan dalam-partisipan, sesuai desain metodologi yang dipilih.
- Melakukan analisis kualitatif meliputi coding, codebook development, thematic analysis, dan inter-rater agreement untuk menjamin reliabilitas interpretasi.
- Menerapkan triangulasi untuk memperkuat evidence ketika menggabungkan temuan dari berbagai sumber atau metode penelitian.
- Menyajikan hasil melalui data visualization dan reporting yang memenuhi standar akademik dan komunikasi ilmiah.

Perhatikan rantai konseptual pada kata kunci: Data → Result → Finding → Evidence → Claim. Setiap tahap memiliki makna metodologis yang berbeda. Data adalah catatan mentah, result adalah output analisis statistik atau tema awal, finding adalah interpretasi kontekstual, evidence adalah dukungan empiris yang valid, dan claim adalah pernyataan ilmiah yang diajukan berdasarkan bukti tersebut. Memahami hierarki ini sangat krusial agar klaim penelitian Anda tidak overclaim atau underclaim.

Poin-poin ini akan menjadi panduan utama selama perkuliahan. Di slide berikutnya, kita akan mengaitkan kembali dengan proses pengumpulan data yang telah Anda lakukan, serta menjawab pertanyaan mendasar: apa yang sebenarnya dikatakan oleh data tersebut, dan seberapa kuat bukti yang bisa Anda ajukan?

---

## Slide 003 - Menghubungkan dengan Pertemuan Sebelumnya

### Narasi

Pada slide ini, kita akan mengaitkan kembali proses pengumpulan dan pembersihan data yang telah dibahas pada pertemuan-pertemuan sebelumnya dengan langkah analitis yang sedang kita masuki. Seperti yang telah kita pelajari di Pertemuan 9, evaluasi user study menghasilkan berbagai metrik kuantitatif maupun kualitatif, mulai dari task completion, completion time, error rate, hingga instrumen standar seperti SUS, UEQ, dan NASA-TLX, serta interaction logs. Kemudian, pada Pertemuan 12, kita menekankan pentingnya data quality control untuk memastikan bahwa seluruh data yang terkumpul bersih, terstruktur, dan layak untuk diproses lebih lanjut. Kini, data tersebut tidak lagi berhenti sebagai kumpulan angka atau transkrip mentah, melainkan harus ditransformasi secara metodologis menjadi temuan penelitian yang valid.

Transformasi ini sangat bergantung pada paradigma penelitian yang Anda pilih. Jika Anda mengikuti jalur penelitian kuantitatif seperti yang dibahas di Pertemuan 6, fokusnya adalah pada pengukuran variabel dalam eksperimen terkontrol dan uji statistik inferensial. Sebaliknya, jika menggunakan pendekatan kualitatif sesuai Pertemuan 7, data berasal dari wawancara mendalam, observasi, diary studies, atau think-aloud protocol yang memerlukan interpretasi tematik dan coding sistematis. Pendekatan mixed methods justru menggabungkan kekuatan keduanya, sehingga Anda dapat memvalidasi pola numerik dengan konteks perilaku dan persepsi pengguna secara bersamaan. Pemahaman ini menjadi fondasi kritis sebelum kita masuk ke teknik analisis spesifik.

Pertanyaan kunci yang perlu terus dipegang oleh peneliti HCI tingkat magister adalah: apa sebenarnya yang dikatakan oleh data tersebut, dan seberapa kuat bukti yang dapat Anda klaim? Jawaban atas pertanyaan ini tidak bisa bersifat intuitif atau sekadar asumsi. Data mentah hanya memberikan gambaran permukaan. Tugas Anda adalah membedah pola, menguji signifikansi, memeriksa konsistensi, dan menghubungkan hasil analisis dengan teori interaksi manusia dan komputer yang relevan. Kekuatan klaim ilmiah Anda berbanding lurus dengan ketelitian dalam menelusuri alur dari data mentah menuju evidence yang solid.

Untuk memperjelas mekanisme transformasi ini, pada slide berikutnya kita akan membahas secara eksplisit alur Data → Result → Finding → Evidence → Claim. Di sana akan dijabarkan perbedaan mendasar antara setiap tingkatan, disertai contoh konkret dalam konteks HCI, serta kesalahan umum yang sering dilakukan peneliti pemula ketika melompat langsung dari data mentah ke klaim tanpa melalui proses verifikasi yang ketat. Mari kita lanjutkan ke pemahaman alur tersebut agar analisis Anda memiliki landasan epistemologis dan metodologis yang kuat.

---

## Slide 004 - Fokus Utama: Alur Data → Evidence

### Narasi

Pada slide ini, kita akan membahas alur transisi sistematis dari data mentah menuju bukti ilmiah yang sah dalam penelitian HCI. Mengacu pada pertanyaan kunci di pertemuan sebelumnya mengenai apa yang dikatakan oleh data dan seberapa kuat bukti yang dapat diklaim, slide ini menegaskan bahwa proses analisis bukan sekadar pengolahan angka atau teks, melainkan konstruksi bertingkat yang memerlukan validasi ketat.

Terdapat lima tingkatan kritis yang harus dibedakan secara eksplisit agar inferensi penelitian tetap rigor:
- **Data** adalah rekaman mentah, seperti durasi penyelesaian tugas, jumlah error, atau transkrip wawancara.
- **Result** merupakan output langsung dari analisis statistik atau tematik, misalnya nilai statistik uji, koefisien korelasi, atau kode tema yang muncul.
- **Finding** adalah pola bermakna secara konseptual yang diturunkan dari hasil analisis dan dikaitkan dengan literatur atau teori.
- **Evidence** menilai kekuatan dukungan data terhadap interpretasi tersebut melalui konsistensi, ketebalan deskripsi, dan sumber ganda.
- **Claim** adalah pernyataan ilmiah final yang hanya boleh diajukan ketika evidence telah memenuhi standar validitas internal, reliabilitas, dan generalisasi.

Kesalahan umum yang sering dilakukan peneliti pemula adalah melompat langsung dari data ke klaim tanpa melalui tahap evaluasi evidence. Melihat perbedaan rata-rata waktu respons lalu langsung menyimpulkan keunggulan suatu interface, tanpa mempertimbangkan apakah efek tersebut nyata, cukup besar, konsisten, atau memiliki penjelasan alternatif, mengabaikan prinsip dasar inferensi ilmiah. Langkah ini rentan menghasilkan generalisasi prematur dan klaim yang tidak dapat direplikasi.

Pembedaan tingkat-tingkat ini menjadi fondasi penting untuk memahami peringatan utama pada slide berikutnya: signifikansi statistik tidak otomatis menjamin signifikansi ilmiah. Setelah menguasai alur data ke evidence, kita akan mendalami bagaimana mengevaluasi effect size, relevansi praktis bagi pengguna, konsistensi lintas kondisi, serta pentingnya triangulasi data sebelum merumuskan klaim penelitian yang robust dan siap dipertanggungjawabkan di forum akademik internasional.

---

## Slide 005 - Statistical Significance ≠ Scientific Significance

### Narasi

Slide ini menyoroti kesalahpahaman yang sangat umum dalam penelitian HCI, yaitu mengira bahwa signifikansi statistik sama dengan signifikansi ilmiah. Ingat kembali alur konseptual dari data menuju evidence yang telah kita bahas pada slide sebelumnya. Nilai statistik hanyalah produk dari pemrosesan data, bukan jaminan bahwa sebuah temuan memiliki bobot ilmiah atau dampak praktis yang nyata.

Peringatan utama pada slide ini menegaskan bahwa nilai p < .05 tidak otomatis membuat suatu hasil penting secara ilmiah. Nilai p hanya menginformasikan probabilitas bahwa hasil yang diamati muncul secara kebetulan di bawah asumsi hipotesis nol. Ia sama sekali tidak mengukur besarnya pengaruh, relevansi kontekstual, atau konsistensi temuan di lapangan. Peneliti pemula sering terjebak pada label "signifikan" tanpa menanyakan apakah efek tersebut benar-benar bermakna bagi pengguna.

Ilustrasi pada tabel memberikan tiga skenario empiris yang sering dihadapi. Pertama, perbedaan waktu penyelesaian tugas sebesar 0,3 detik dengan sampel besar (N = 200) dapat menghasilkan nilai p < .05. Secara matematis signifikan, namun secara praktis perubahan sepersekian detik tersebut hampir tidak pernah mengubah pengalaman atau produktivitas pengguna. Kedua, perbedaan substansial yang teramati pada kelompok kecil (N = 5) mungkin gagal mencapai signifikansi statistik karena daya uji (power) yang rendah. Pola ini justru bisa menjadi indikasi kuat adanya efek nyata yang memerlukan replikasi dengan jumlah partisipan lebih besar. Ketiga, hasil yang signifikan secara statistik tetapi hanya bertahan dalam satu konteks eksperimen yang sempit akan sulit digeneralisasi ke lingkungan penggunaan sesungguhnya.

Oleh karena itu, evaluasi temuan penelitian HCI harus mencakup empat dimensi berikut:
- **Effect size**: ukur seberapa besar pengaruh desain atau intervensi terhadap variabel dependen, misalnya menggunakan Cohen's d atau eta squared.
- **Practical importance**: tanyakan apakah perbedaan yang terukur benar-benar relevan dengan kebutuhan, kenyamanan, atau efisiensi pengguna nyata.
- **Consistency**: verifikasi apakah pola yang diamati muncul secara stabil di berbagai kondisi pengujian, lintas tugas, dan antar profil partisipan.
- **Triangulation**: gabungkan bukti statistik dengan data kualitatif, catatan observasi, atau log interaksi untuk memastikan interpretasi tidak bias oleh satu metode saja.

Pemahaman ini menjadi prasyarat mutlak sebelum kita memasuki tahap pengolahan data mentah. Angka-angka yang akan dianalisis statistiknya hanya akan meaningful jika kualitas datanya terjaga. Proses inilah yang akan kita bedah pada slide berikutnya, yaitu data cleaning, mulai dari tujuan, langkah teknis, hingga prinsip transparansi yang wajib diterapkan dalam setiap keputusan pembersihan data.

---

## Slide 006 - Data Cleaning: Mengapa dan Bagaimana?

### Narasi

Setelah kita memahami bahwa signifikansi statistik tidak serta merta mencerminkan signifikansi ilmiah, langkah krusial berikutnya dalam alur penelitian HCI adalah memastikan kualitas data mentah yang akan dianalisis. Sebelum masuk ke uji hipotesis atau pemodelan statistik, peneliti wajib melakukan proses data cleaning. Tanpa fondasi data yang bersih, hasil analisis apa pun berisiko bias, tidak valid, atau bahkan menyesatkan kesimpulan ilmiah.

Tujuan utama dari aktivitas ini mencakup empat aspek fundamental. Pertama, mendeteksi data error seperti salah input, nilai yang tidak masuk akal, atau entri duplikat yang bisa menggeser mean secara artifisial. Kedua, menangani missing data yang sering muncul akibat partisipan drop-out atau kegagalan teknis pada alat ukur. Ketiga, mengidentifikasi outlier atau nilai ekstrem yang menyimpang jauh dari pola distribusi umum. Keempat, memastikan konsistensi format, baik itu penamaan variabel, skala pengukuran, maupun satuan yang seragam di seluruh dataset.

Secara praktis, langkah pembersihan data dapat diikuti melalui lima tahapan sistematis berikut:
- Lakukan inspeksi visual awal menggunakan perintah seperti `head(data)`, `str(data)`, atau `summary(data)` untuk memahami struktur dan distribusi data.
- Validasi rentang nilai agar semua entri berada dalam batas skala instrumen yang mungkin secara teoretis.
- Identifikasi pola missing data dengan menghitung jumlah NA (`summary(is.na(data))`) dan memvisualisasikan distribusinya.
- Deteksi outlier melalui boxplot atau metode statistik seperti z-score dan perhitungan IQR.
- Dokumentasikan SEMUA keputusan cleaning yang Anda ambil, termasuk alasan penghapusan atau modifikasi data.

Prinsip inti yang harus selalu diingat adalah transparansi dan replikabilitas. Jangan pernah menghapus atau mengubah data tanpa catatan yang jelas. Setiap tindakan cleaning harus dapat dijelaskan dan direplikasi oleh reviewer atau peneliti lain. Pada slide berikutnya, kita akan membahas secara mendalam bagaimana menangani missing data berdasarkan mekanisme kerjanya—MCAR, MAR, hingga MNAR—serta strategi teknis untuk mengelola outlier, termasuk implementasi kode deteksi berbasis IQR dalam Python. Pahami bahwa penanganan data bukan sekadar prosedur teknis, melainkan bagian integral dari integritas metodologis penelitian HCI tingkat magister.

---

## Slide 007 - Menangani Missing Data dan Outliers

### Narasi

Setelah pada slide sebelumnya kita membahas langkah-langkah umum dalam data cleaning, kini kita akan mendalami dua komponen paling kritis yang sering muncul saat membersihkan dataset di penelitian HCI: penanganan missing data dan deteksi outlier. Keduanya memerlukan pendekatan yang sistematis karena keputusan yang salah dapat mengancam validitas dan replikabilitas temuan penelitian Anda.

Missing data tidak selalu hilang secara acak. Kita perlu mengklasifikasikannya ke dalam tiga tipe utama berdasarkan mekanisme kehilangannya. Pertama, MCAR atau Missing Completely At Random, artinya tidak ada pola tertentu yang menyebabkan data hilang, sehingga analisis lengkap atau imputasi sederhana masih bisa dipertahankan. Kedua, MAR atau Missing At Random, di mana kemungkinan data hilang terkait dengan variabel lain yang sudah teramati, sehingga penanganannya membutuhkan imputasi yang mempertimbangkan variabel prediktor tersebut. Ketiga, MNAR atau Missing Not At Random, yang merupakan kasus tersulit karena kehilangan data justru terkait dengan nilai yang seharusnya diisi. Pada kondisi ini, kita biasanya memerlukan model statistik khusus dan wajib melaporkannya sebagai keterbatasan penelitian.

Penting untuk diingat bahwa mengganti nilai missing dengan rata-rata tanpa pertimbangan mendalam sangat berisiko. Imputasi sembarangan dapat mengurangi varians data, mendistorsi hubungan antar variabel, dan menghasilkan estimasi parameter yang bias. Selalu gunakan metode imputasi yang sesuai dengan mekanisme kehilangan data, seperti multiple imputation atau model berbasis regresi, jika pengisian nilai kosong memang diperlukan.

Beralih ke outlier, nilai ekstrem ini harus dibedakan antara kesalahan input dan fenomena nyata. Berikut adalah contoh implementasi deteksi outlier menggunakan metode IQR dalam Python:
```python
import numpy as np
Q1, Q3 = np.percentile(data, [25, 75])
IQR = Q3 - Q1
outliers = data[(data < Q1 - 1.5*IQR) | (data > Q3 + 1.5*IQR)]
```
Kode ini menghitung kuartil pertama dan ketiga, lalu menentukan batas bawah dan atas berdasarkan 1,5 kali interquartile range. Nilai di luar rentang tersebut ditandai sebagai outlier. Metode ini lebih robust dibandingkan standar deviasi karena tidak terlalu terpengaruh oleh nilai ekstrem itu sendiri, sehingga cocok untuk data perilaku pengguna yang sering kali tidak berdistribusi normal.

Saat menemukan outlier, jangan langsung menghapusnya. Verifikasi terlebih dahulu apakah itu data entry error yang bisa dikoreksi, atau benar-benar representasi dari perilaku pengguna yang ekstrem. Dalam konteks HCI, outlier sering kali mengungkap masalah usability yang serius, fitur yang disalahpahami, atau kelompok pengguna dengan kebutuhan khusus. Analisis terpisah antara data normal dan outlier justru sering memberikan insight yang lebih kaya daripada sekadar membuang nilai tersebut.

Setelah proses pembersihan data selesai dan struktur dataset sudah bersih, langkah selanjutnya adalah merangkum karakteristik data secara keseluruhan. Pada slide berikutnya, kita akan membahas descriptive statistics untuk meringkas distribusi numerik dan kategorikal, serta cara melaporkan hasil statistik secara standar dalam publikasi HCI.

---

## Slide 008 - Descriptive Statistics: Merangkum Data

### Narasi

Setelah menyelesaikan tahap pembersihan data dengan menangani missing values dan outliers pada slide sebelumnya, langkah logis berikutnya adalah merangkum informasi yang telah bersih menjadi statistik deskriptif yang bermakna. Statistik deskriptif berperan sebagai fondasi analitik untuk memahami karakteristik dasar dataset sebelum kita melangkah ke pengujian hipotesis atau model inferensial.

Untuk data numerik, pemilihan ukuran pemusatan dan sebaran harus disesuaikan dengan sifat distribusi data yang kita amati:
- **Mean** menggambarkan titik pusat data, namun perlu diingat bahwa ukuran ini sangat sensitif terhadap keberadaan outlier.
- **Median** menjadi alternatif yang lebih robust ketika data menunjukkan distribusi yang miring atau mengandung nilai ekstrem.
- **Mode** mencatat nilai yang paling sering muncul, dan umumnya lebih relevan untuk identifikasi tren pada data kategorikal.
- **Standar Deviasi (SD) dan Varians** mengukur tingkat sebaran atau variasi data; nilai yang lebih besar mengindikasikan heterogenitas respons partisipan yang lebih tinggi.
- **Range dan IQR** memberikan gambaran rentang nilai. IQR khususnya diandalkan karena ketahanannya terhadap pengaruh outlier.
- **Skewness** mengkuantifikasi tingkat kemiringan distribusi, yang menjadi indikator kritis untuk menentukan jenis uji statistik yang valid di tahap lanjutan.

Pada data kategorikal, pelaporan difokuskan pada frekuensi absolut dan persentase relatif per kategori. Jika terdapat dua variabel kategorikal yang ingin dianalisis hubungannya, tabel kontingensi dapat disusun untuk memetakan asosiasi atau pola silang antar kategori tersebut.

Dalam praktik penulisan paper HCI tingkat magister, pelaporan statistik deskriptif harus memenuhi standar transparansi akademik. Contoh pelaporan yang baku adalah menyebutkan nilai mean dan standar deviasi untuk setiap kondisi eksperimen, diikuti oleh catatan mengenai bentuk distribusi. Misalnya, ketika melaporkan waktu penyelesaian tugas, pastikan Anda menyertakan notasi statistik seperti `(M = 45.2 s, SD = 8.3)` dan menjelaskan arah kemiringan distribusi jika ada, agar reviewer dapat menilai konsistensi dan reliabilitas temuan Anda.

Poin kunci dari materi ini adalah bahwa statistik deskriptif bukan sekadar rangkuman angka, melainkan peta awal yang memandu keputusan metodologis. Pemahaman mendalam terhadap mean, median, sebaran, dan skewness akan menjadi landasan langsung untuk slide berikutnya, yaitu memahami distribusi data sebelum memilih uji statistik parametrik maupun non-parametrik. Dengan demikian, alur analisis dari pembersihan data, ringkasan deskriptif, hingga verifikasi distribusi akan berjalan secara koheren dan siap mendukung kontribusi ilmiah Anda.

---

## Slide 009 - Memahami Distribusi Data Sebelum Memilih Uji

### Narasi

Setelah pada slide sebelumnya kita membahas cara merangkum data numerik dan kategorikal menggunakan statistik deskriptif, langkah analitis berikutnya yang wajib dilakukan adalah memeriksa bentuk distribusi data sebelum memutuskan uji hipotesis apa yang akan diterapkan. Pemahaman ini menjadi gatekeeper validitas seluruh proses inferensi statistik dalam penelitian HCI tingkat magister.

Diagram pada slide ini mengilustrasikan tiga pola distribusi yang paling umum ditemui. Pada distribusi simetris atau normal, mean dan median berada di posisi yang hampir identik, menciptakan bentuk lonceng yang seimbang. Ketika data mengalami right-skewed, ekor distribusi memanjang ke arah nilai tinggi sehingga mean menjadi lebih besar daripada median. Sebaliknya, pada left-skewed, ekor memanjang ke kiri dan mean jatuh di bawah median. Dalam praktik penelitian HCI, data seperti completion time, error rate, atau SUS score sangat jarang menghasilkan distribusi normal sempurna akibat heterogenitas perilaku pengguna dan keberadaan outlier alami.

Memetakan distribusi ini bukan sekadar prosedur teknis, melainkan prasyarat metodologis. Mayoritas uji parametrik dibangun di atas asumsi dasar bahwa data sampel mewakili populasi yang berdistribusi normal. Pelanggaran asumsi ini tanpa penyesuaian metode dapat mendistorsi nilai-p, meningkatkan probabilitas kesalahan tipe satu maupun tipe dua, dan akhirnya melemahkan klaim kontribusi ilmiah Anda. Verifikasi dapat dilakukan secara visual melalui histogram dan Q-Q plot, serta secara statistik menggunakan uji Shapiro-Wilk yang direkomendasikan khusus untuk sampel berukuran kecil hingga menengah.

Berikut adalah representasi alur keputusan analisis yang sering diimplementasikan dalam pipeline pemrosesan data:

```python
if normal_distribution(data):
    gunakan uji parametrik    # t-test, ANOVA
else:
    gunakan uji non-parametrik  # Mann-Whitney, Wilcoxon, Kruskal-Wallis
```

Kode pseudocode ini menandai titik percabangan metodologis. Jika kondisi normalitas terpenuhi, peneliti dapat memanfaatkan uji parametrik seperti independent t-test atau one-way ANOVA yang menawarkan power statistik lebih tinggi. Apabila asumsi normalitas gagal dipenuhi, jalur yang aman adalah beralih ke uji non-parametrik: Mann-Whitney U test untuk perbandingan dua kelompok independen, Wilcoxon signed-rank test untuk data berpasangan, atau Kruskal-Wallis test ketika melibatkan tiga kelompok atau lebih. Transisi ini menjaga integritas bukti empiris meskipun data bersifat ordinal atau mengandung distribusi yang terdistorsi.

Dengan menyelaraskan pemilihan uji statistik terhadap karakteristik distribusi data, fondasi analisis Anda sudah siap untuk melangkah ke tahap inferensial. Pada slide berikutnya, kita akan membahas bagaimana melakukan statistical inference dari sampel terbatas menuju populasi target, serta bagaimana confidence interval dan ukuran sampel berperan menentukan kekuatan bukti yang Anda ajukan dalam paper penelitian HCI.

---

## Slide 010 - Statistical Inference: Dari Sampel ke Populasi

### Narasi

Setelah kita menyelesaikan pemeriksaan distribusi data dan memutuskan jenis uji statistik yang tepat pada slide sebelumnya, langkah analitis berikutnya adalah memahami bagaimana temuan dari sampel penelitian kita dapat digeneralisasi ke populasi yang lebih luas. Konsep ini merupakan jantung dari *statistical inference*.

Dalam penelitian HCI, skala populasi hampir selalu terlalu besar untuk diteliti secara menyeluruh. Kita bekerja dengan sampel terbatas, misalnya dua puluh hingga lima puluh partisipan dalam sebuah *user study*. Target akhir analisis kita bukan sekadar mendeskripsikan data sampel tersebut, melainkan membuat pernyataan tentang karakteristik populasi target, seperti semua pengguna potensial dari sistem interaktif yang sama. Proses penarikan kesimpulan dari sampel ke populasi inilah yang disebut sebagai *statistical inference*.

Inferensi statistik dibangun di atas dua pilar utama. Pertama adalah *point estimate*, yaitu nilai tunggal yang dihitung dari data sampel sebagai perkiraan parameter populasi. Contoh konkretnya adalah rata-rata waktu penyelesaian tugas (*mean completion time*) sebesar 45,2 detik. Kedua adalah *interval estimate*, yang memberikan rentang nilai di mana parameter populasi diperkirakan berada. Dalam literatur HCI, kita umumnya menggunakan *Confidence Interval* (CI) 95%, misalnya 42,1–48,3 detik. Interval ini jauh lebih bernilai karena secara eksplisit mengkuantifikasi batas ketidakpastian estimasi kita.

Pertanyaan fundamental yang harus selalu dijawab oleh peneliti adalah konsistensi dan reliabilitas perkiraan. Jika eksperimen ini diulang dengan rekrutmen partisipan yang berbeda, apakah pola hasilnya akan tetap stabil? Seberapa besar margin of error yang melekat pada perkiraan kita terhadap realitas populasi? Jawaban atas pertanyaan ini secara matematis ditentukan oleh ukuran sampel.

Ukuran sampel memiliki dampak langsung terhadap kekuatan bukti (*strength of evidence*). Sampel yang kecil menghasilkan *Confidence Interval* yang lebar, yang menandakan ketidakpastian tinggi dan bukti statistik yang lemah untuk mendukung klaim desain atau antarmuka. Sebaliknya, sampel yang memadai mempersempit *Confidence Interval*, menurunkan tingkat ketidakpastian, dan menghasilkan bukti yang lebih presisi serta dapat dipertanggungjawabkan secara ilmiah.

Penguasaan terhadap konsep inferensi statistik dan dinamika antara ukuran sampel dengan *confidence interval* ini menjadi prasyarat mutlak sebelum masuk ke prosedur pengambilan keputusan formal. Pada slide berikutnya, kita akan mengintegrasikan pemahaman ini ke dalam kerangka *hypothesis testing*, mencakup logika pembentukan hipotesis nol dan alternatif, serta interpretasi *p-value* yang akurat untuk menghindari kesalahan konseptual dalam evaluasi penelitian HCI.

---

## Slide 011 - Hypothesis Testing: Logika dan Prosedur

### Narasi

Setelah membahas bagaimana inferensi statistik menghubungkan data sampel dengan populasi melalui estimasi titik dan interval kepercayaan, kita kini masuk ke mekanisme pengambilan keputusan formal dalam pengujian hipotesis. Pada jenjang magister, pemahaman logika di balik pengujian hipotesis bukan sekadar rutinitas komputasi, melainkan fondasi kritis untuk menilai validitas bukti empiris dalam penelitian HCI.

Prosedur pengujian hipotesis mengikuti alur deduktif yang ketat:
1. Nyatakan **null hypothesis (H₀)**: asumsi dasar yang menyatakan tidak ada efek atau perbedaan. Contoh: "Tidak ada perbedaan completion time antara Interface A dan Interface B."
2. Nyatakan **alternative hypothesis (H₁)**: pernyataan yang berlawanan dengan H₀, yang menyatakan adanya efek atau perbedaan. Contoh: "Completion time Interface A berbeda dari Interface B."
3. Kumpulkan data eksperimen dan hitung statistik uji yang sesuai dengan desain penelitian.
4. Hitung **p-value**: probabilitas memperoleh hasil setidaknya se-ekstrem pengamatan kita, dengan asumsi bahwa H₀ benar.
5. Ambil **keputusan**: tolak H₀ jika p-value lebih kecil dari tingkat signifikansi α (biasanya 0,05).

Interpretasi nilai p sering kali menjadi sumber kesalahpahaman serius dalam publikasi HCI. Banyak peneliti keliru mengartikan p = 0,03 sebagai probabilitas 3% bahwa hipotesis nol benar. Padahal, interpretasi yang tepat adalah bahwa jika sebenarnya tidak ada efek sama sekali, kita hanya akan mengamati perbedaan sebesar ini atau lebih ekstrem dalam 3% eksperimen serupa yang diulang. Signifikansi statistik semata tidak serta merta menjamin signifikansi ilmiah atau praktis. Nilai p < 0,05 hanyalah pemenuhan ambang batas statistik; makna temuan tersebut tetap harus ditafsirkan dalam konteks domain, ukuran efek, dan relevansi penggunaannya.

Memahami prosedur ini mempersiapkan kita untuk menelaah konsekuensi logis dari setiap keputusan pengujian. Ketika kita menolak atau gagal menolak H₀, selalu ada kemungkinan terjadi kesalahan klasifikasi. Pada slide berikutnya, kita akan membedah dua jenis kesalahan statistik, implikasinya terhadap kredibilitas temuan HCI, serta strategi metodologis untuk meminimalkan risiko tersebut tanpa melanggar prinsip etika penelitian.

---

## Slide 012 - Kesalahan dalam Hypothesis Testing

### Narasi

Setelah memahami logika pengujian hipotesis dan interpretasi p-value pada slide sebelumnya, kini kita beralih ke aspek kritis yang sering terlewatkan dalam analisis statistik: kesalahan dalam pengambilan keputusan hipotesis. Dalam setiap pengujian statistik, meskipun prosedur diikuti dengan benar, selalu ada probabilitas kita melakukan kesalahan klasifikasi terhadap realitas data.

Kesalahan ini dibagi menjadi dua tipe berdasarkan hubungan antara keputusan peneliti dengan kebenaran hipotesis nol (H₀) maupun alternatif (H₁):
- **Type I error (kesalahan α)**: Terjadi ketika H₀ sebenarnya benar, namun kita menolak H₀. Kita mengklaim adanya efek padahal tidak ada.
- **Type II error (kesalahan β)**: Terjadi ketika H₁ sebenarnya benar, namun kita gagal menolak H₀. Efek yang nyata justru terlewatkan.

Dalam penelitian Human-Computer Interaction, kedua kesalahan ini memiliki konsekuensi metodologis yang serius. Type I error berpotensi menghasilkan publikasi temuan palsu yang menyesatkan komunitas riset dan mengarah pada pengembangan fitur antarmuka yang tidak efektif. Sebaliknya, Type II error berisiko membuat peneliti melewatkan perbaikan desain yang sebenarnya sangat signifikan bagi pengguna, sehingga inovasi terhambat oleh hasil negatif semu.

Strategi mitigasi risiko harus diterapkan secara sistematis sejak tahap perencanaan:
- **Mengontrol Type I error**: Tetapkan tingkat signifikansi α secara ketat dan gunakan koreksi multiple comparisons seperti Bonferroni atau Tukey HSD saat melakukan banyak uji statistik sekaligus.
- **Mengurangi Type II error**: Lakukan power analysis di awal desain untuk menentukan sample size yang memadai, sehingga uji memiliki sensitivitas cukup untuk mendeteksi efek yang ada.
- **Melindungi integritas umum**: Terapkan replikasi studi, lakukan pre-registration analisis, dan pastikan transparansi seluruh prosedur pengujian.

Perlu ditekankan bahwa p-hacking merupakan praktik yang sangat berbahaya dan melanggar etika penelitian. P-hacking terjadi ketika peneliti terus-menerus menggali, memfilter, atau mengubah variabel hingga akhirnya menemukan nilai p < 0,05 secara kebetulan. Praktik ini merusak kredibilitas ilmiah dan menghasilkan literatur yang penuh dengan temuan artifaktual. Sebagai peneliti tingkat magister, komitmen pada transparansi metodologis dan pelaporan sesuai rencana awal adalah kewajiban mutlak.

Memahami batasan p-value dan risiko kesalahan statistik membawa kita pada pertanyaan lanjutan: seberapa besar dampak nyata dari sebuah temuan? Di slide berikutnya, kita akan membahas effect size sebagai pelengkap esensial yang menjawab pertanyaan tentang magnitudo efek, bukan hanya keberadaannya.

---

## Slide 013 - Effect Size: Seberapa Besar Efeknya?

### Narasi

Setelah menguraikan risiko kesalahan dalam pengujian hipotesis pada slide sebelumnya, khususnya *Type I* dan *Type II* error serta peringatan ketat terhadap praktik *p-hacking*, kita kini beralih ke dimensi kuantitatif yang tak kalah krusial: seberapa besar sebenarnya efek yang teramati. Nilai *p*-value saja tidak cukup untuk menilai kualitas atau relevansi temuan penelitian Anda di bidang HCI.

Nilai *p*-value hanya menjawab pertanyaan apakah ada bukti statistik bahwa efek berbeda dari nol. Namun, dalam konteks desain dan evaluasi antarmuka, kita perlu mengetahui magnitudo dampaknya terhadap pengguna. Dua studi dapat menghasilkan nilai *p* yang sama-sama sangat kecil, misalnya *p* = ,001, namun satu studi menunjukkan perubahan perilaku yang marginal, sementara studi lainnya menunjukkan perbaikan kinerja yang substansial. Di sinilah *effect size* menjadi metrik pelengkap yang wajib dilaporkan.

Berikut adalah ukuran *effect size* yang paling umum digunakan dalam publikasi HCI, disesuaikan dengan jenis analisis statistik:
- **Cohen’s d**: Digunakan untuk perbandingan dua kelompok. Interpretasi umumnya berada di kisaran 0,2 (kecil), 0,5 (sedang), hingga 0,8 (besar). Dihitung dari selisih rata-rata dibagi standar deviasi gabungan.
- **Pearson’s r**: Mengukur kekuatan hubungan linier antara dua variabel kontinu.
- **Eta-squared (η²)**: Dipakai dalam analisis ANOVA untuk menunjukkan proporsi varians total yang dijelaskan oleh faktor eksperimen.
- **Odds ratio**: Sering diterapkan pada data kategorikal atau hasil biner, seperti tingkat keberhasilan penyelesaian tugas.

Saat menyusun laporan penelitian, pastikan Anda menyertakan *effect size* secara eksplisit dalam setiap pernyataan hasil. Contoh pelaporan yang baku adalah: terdapat perbedaan signifikan antara kedua kondisi, t(38) = 2,31, p = ,026, Cohen’s d = 0,74, menunjukkan efek dengan ukuran sedang-ke-besar. Format ini memberikan transparansi penuh kepada reviewer mengenai signifikansi statistik sekaligus besaran dampaknya.

Perlu dicatat bahwa nilai *effect size* yang kecil pun tetap dapat bermakna secara ilmiah jika dampaknya bersifat kumulatif, mengukur variabel yang sangat kritis bagi pengalaman pengguna, atau terjadi dalam konteks intervensi yang secara inheren sulit diubah. Sebaliknya, *effect size* yang tampak besar pada sampel berukuran kecil harus ditafsirkan dengan hati-hati dan memerlukan replikasi independen untuk memastikan keandalannya.

Pembahasan mengenai besaran efek ini akan berlanjut secara logis ke konsep *confidence interval* pada slide berikutnya. Jika *effect size* memberi tahu kita seberapa besar efeknya, *confidence interval* akan melengkapi gambaran tersebut dengan menyediakan rentang nilai yang masuk akal berdasarkan presisi estimasi, sehingga pelaporan data penelitian menjadi lebih robust dan siap untuk dibandingkan lintas studi.

---

## Slide 014 - Confidence Interval: Rangkaian Nilai yang Masuk Akal

### Narasi

Setelah pada slide sebelumnya kita membahas *effect size* untuk mengukur besarnya dampak suatu intervensi atau perbedaan kondisi, langkah analitis berikutnya adalah menilai seberapa akurat estimasi tersebut. Di sinilah *Confidence Interval* (CI) memegang peran krusial. Secara konseptual, *95% confidence interval* merujuk pada rentang nilai yang, jika penelitian kita diulang berkali-kali dengan prosedur sampling yang identik, akan mencakup parameter populasi sejati sebanyak 95% dari replikasi tersebut. Berbeda dengan *p-value* yang hanya memberikan indikasi biner signifikan atau tidak signifikan, CI memberikan informasi kuantitatif mengenai ketepatan estimasi kita terhadap efek yang sebenarnya terjadi di populasi target.

Dalam praktik penelitian HCI, interpretasi CI sangat bergantung pada apakah rentang tersebut memuat angka nol. Perhatikan dua skenario empiris berikut: pada skenario pertama, selisih waktu penyelesaian tugas sebesar 2,1 detik dengan 95% CI [0,3 hingga 3,9]. Karena interval ini tidak menyentuh nol, hasilnya konsisten dengan adanya efek yang signifikan secara statistik. Sebaliknya, pada skenario kedua, meskipun selisih rata-ratanya tetap 2,1 detik, 95% CI-nya adalah [-1,5 hingga 5,7]. Karena rentang ini mencakup nol, kita tidak memiliki bukti yang cukup untuk menyimpulkan adanya efek, sekaligus mengindikasikan bahwa estimasi kita sangat tidak presisi akibat variabilitas data yang tinggi atau ukuran sampel yang belum memadai.

Kegunaan utama pelaporan CI dalam literatur HCI dapat dirangkum sebagai berikut:
- Menunjukkan arah dan besarnya efek yang diamati secara eksplisit.
- Mengukur presisi estimasi; semakin sempit CI, semakin kecil ketidakpastian dan semakin kuat klaim penelitiannya.
- Memudahkan perbandingan antar studi, karena pembaca dapat menilai tumpang tindih rentang estimasi tanpa bergantung pada batas ambang *p-value* yang sering disalahartikan.

Oleh karena itu, pedoman pelaporan terkini sangat menekankan untuk selalu menyertakan *effect size* beserta CI-nya, bukan sekadar melaporkan nilai *p*. Dengan fondasi estimasi titik dan rentang kepercayaan yang telah mapan, kita kini siap beralih ke analisis hubungan antar variabel. Pada slide berikutnya, kita akan membahas korelasi sebagai alat untuk mengidentifikasi pola hubungan antara dua konstruk, sambil tetap menjaga kewaspadaan metodologis bahwa korelasi tidak serta merta membuktikan kausalitas. Mari kita telaah bersama bagaimana memilih ukuran korelasi yang tepat dan menerapkannya dalam evaluasi sistem interaktif.

---

## Slide 015 - Correlation: Menemukan Hubungan Antar Variabel

### Narasi

Setelah sebelumnya membahas confidence interval sebagai alat untuk menilai presisi estimasi parameter populasi, kita kini beralih ke analisis hubungan antar variabel melalui korelasi. Pada jenjang magister, pemahaman ini menjadi fondasi penting sebelum merancang studi komparatif atau eksperimen yang lebih kompleks.

Poin pertama yang harus selalu diingat adalah perbedaan mendasar antara korelasi dan kausalitas. Korelasi hanya menunjukkan adanya hubungan statistik di mana perubahan pada variabel X berkorespondensi dengan perubahan pada variabel Y. Namun, korelasi tidak pernah membuktikan kausalitas. Klaim bahwa X menyebabkan Y memerlukan desain penelitian yang melibatkan manipulasi variabel, kontrol terhadap confounding factors, dan mekanisme temporal yang jelas. Dalam publikasi HCI, kesalahan menyamakan korelasi dengan sebab-akibat sering menjadi kritik utama reviewer.

Analisis korelasi paling tepat digunakan ketika kita mengeksplorasi hubungan antara dua variabel kontinu tanpa melakukan manipulasi eksperimental. Misalnya, peneliti mungkin ingin mengetahui apakah skor System Usability Scale (SUS) berkorelasi dengan waktu penyelesaian tugas, atau apakah beban kerja yang dilaporkan secara subjektif berkorelasi dengan tingkat kesalahan pengguna. Pendekatan ini sangat bernilai pada fase eksplorasi data awal atau saat membangun hipotesis untuk studi lanjutan.

Pemilihan ukuran korelasi bergantung pada sifat distribusi data dan bentuk hubungan yang diamati. Pearson’s r mengukur hubungan linear dan mensyaratkan data berdistribusi normal. Nilainya berkisar antara -1 hingga +1, di mana nilai dekat nol mengindikasikan tidak ada hubungan linear, sementara nilai mendekati ekstrem menunjukkan hubungan yang kuat. Jika data tidak memenuhi asumsi normalitas atau hubungannya bersifat monoton namun tidak linear, gunakan Spearman’s rho. Selain itu, point-biserial correlation diterapkan ketika salah satu variabel bersifat biner, seperti membandingkan preferensi antarmuka antara kelompok pengguna novice dan expert.

Berikut adalah implementasi praktisnya dalam bahasa pemrograman Python yang umum digunakan dalam pipeline analisis data HCI:

```python
from scipy.stats import pearsonr, spearmanr
r, p = pearsonr(x, y)        # jika normal & linear
rho, p = spearmanr(x, y)     # jika tidak normal / tidak linear
```

Kode di atas memanfaatkan modul `scipy.stats` untuk menghitung koefisien korelasi dan nilai signifikansi (p-value). Fungsi `pearsonr` dipanggil ketika asumsi parametrik terpenuhi, sedangkan `spearmanr` menjadi alternatif non-parametrik yang robust terhadap outlier dan distribusi skew. Selalu verifikasi asumsi normalitas menggunakan Shapiro-Wilk atau Q-Q plot sebelum memilih fungsi yang tepat, karena pemilihan uji yang keliru dapat menghasilkan interpretasi bias.

Memahami pola korelasi antar variabel memberikan gambaran awal tentang dinamika interaksi pengguna. Namun, jika tujuan penelitian Anda bergeser dari pengamatan hubungan menuju perbandingan efektivitas antar kondisi, kita akan melanjutkan ke slide berikutnya yang membahas desain between-subjects dan uji statistik komparatif seperti independent t-test maupun One-way ANOVA.

---

## Slide 016 - Comparing Conditions: Uji untuk Desain Antar Kelompok

### Narasi

Setelah pada slide sebelumnya membahas korelasi untuk mengidentifikasi hubungan antar variabel tanpa manipulasi eksperimen, kita kini beralih ke tahap yang lebih ketat: membandingkan kondisi atau kelompok untuk menguji perbedaan nyata. Pergeseran ini penting karena korelasi hanya menunjukkan pola asosiasi, sementara desain komparatif memungkinkan kita menarik kesimpulan mengenai dampak suatu intervensi atau variasi antarmuka.

Dalam desain *between-subjects* atau antar kelompok, setiap partisipan hanya dialokasikan ke satu kondisi eksperimen saja. Struktur alokasinya dapat digambarkan sebagai berikut:

```
Group 1 (Interface A): P1 P2 P3 P4 P5 ...
Group 2 (Interface B): P6 P7 P8 P9 P10 ...
```

Pendekatan ini sangat menguntungkan ketika kita ingin menghindari *carryover effects*, seperti efek belajar atau kelelahan, yang sering mengganggu validitas internal pada studi yang menuntut partisipan mencoba beberapa desain sekaligus. Karena setiap orang hanya mengalami satu perlakuan, data yang terkumpul murni mencerminkan respons terhadap kondisi tersebut.

Pemilihan uji statistik yang tepat bergantung pada dua parameter kunci: jumlah grup yang dibandingkan dan distribusi data. Tabel berikut merangkum panduan standarnya:

| Jumlah grup | Data normal | Data tidak normal |
|---|---|---|
| 2 grup | Independent samples t-test | Mann-Whitney U test |
| > 2 grup | One-way ANOVA | Kruskal-Wallis test |

Untuk dua grup dengan data berdistribusi normal, *Independent samples t-test* menjadi standar emas. Jika asumsi normalitas dilanggar, uji non-parametrik *Mann-Whitney U* menjadi alternatif yang robust. Ketika jumlah grup melebihi dua, analisis bergeser ke *One-way ANOVA* untuk data parametrik, atau *Kruskal-Wallis* untuk data non-parametrik. Pemilihan yang salah pada tahap ini dapat menyebabkan kesalahan Tipe I atau Tipe II yang serius.

Mari kita terapkan pada contoh pertanyaan penelitian: "Apakah ada perbedaan workload (NASA-TLX) antara pengguna pemula dan ahli dalam menggunakan generative AI chatbot?" Langkah analisisnya mengikuti struktur baku berikut:

```
H₀: μ_pemula = μ_ahli
H₁: μ_pemula ≠ μ_ahli

Uji: Independent t-test pada skor NASA-TLX
Lapor: t(df), p, Cohen's d, 95% CI
```

Hipotesis nol menetapkan kesamaan rata-rata populasi, sementara hipotesis alternatif menolak kesamaan tersebut. Setelah menjalankan *Independent t-test*, pelaporan hasil wajib menyertakan nilai statistik lengkap. Di tingkat magister, penekanan tidak hanya pada nilai-p, tetapi juga pada ukuran efek dan presisi estimasi. Format pelaporan yang disarankan adalah: nilai t beserta derajat kebebasan dalam kurung, nilai-p, Cohen's d untuk besaran dampak praktis, serta interval kepercayaan 95% yang menunjukkan rentang estimasi parameter populasi.

Konsep perbandingan kondisi ini akan berlanjut pada slide berikutnya, di mana kita akan membahas desain *within-subjects* atau pengukuran berulang. Perbedaan fundamentalnya terletak pada bagaimana partisipan berinteraksi dengan semua kondisi, yang secara otomatis mengubah matriks uji statistik dan strategi mitigasi bias eksperimen seperti counterbalancing.

---

## Slide 017 - Comparing Conditions: Uji untuk Desain Dalam Partisipan

### Narasi

Setelah membahas desain antar kelompok pada slide sebelumnya, kini kita beralih ke desain dalam partisipan atau *within-subjects design*, yang sering disebut sebagai *repeated measures*. Dalam pendekatan ini, setiap partisipan akan menjalani semua kondisi eksperimen yang diteliti. Pendekatan ini sangat kuat secara statistik karena setiap partisipan bertindak sebagai kontrol bagi dirinya sendiri, sehingga variasi antar-individu dapat dikontrol secara efektif.

Perhatikan blok kode yang menampilkan urutan penyajian kondisi. Karena setiap orang mengalami semua kondisi, urutan pemberian stimulus berpotensi menimbulkan bias sistematis. Oleh karena itu, diperlukan teknik *counterbalancing* seperti yang terlihat pada contoh P1, P2, dan P3. Penataan urutan silang ini memastikan bahwa efek pembelajaran atau kelelahan terdistribusi merata di seluruh kondisi, sehingga hasil pengukuran tetap valid dan bebas dari bias urutan.

Pemilihan uji statistik harus disesuaikan dengan jumlah kondisi dan karakteristik distribusi data:
- Untuk dua kondisi dengan data normal: gunakan *paired samples t-test*.
- Untuk dua kondisi dengan data tidak normal: gunakan *Wilcoxon signed-rank test*.
- Untuk lebih dari dua kondisi dengan data normal: gunakan *repeated measures ANOVA*.
- Untuk lebih dari dua kondisi dengan data tidak normal: gunakan *Friedman test*.

Desain ini menawarkan sejumlah keunggulan sekaligus tantangan metodologis yang perlu dikelola oleh peneliti:
- **Keunggulan**: Mengontrol perbedaan individual secara langsung, meningkatkan *statistical power*, dan membutuhkan jumlah partisipan yang lebih sedikit untuk mencapai signifikansi yang setara dengan desain antar kelompok.
- **Tantangan**: Rentan terhadap *order effects* seperti efek latihan atau kelelahan, serta memerlukan perencanaan *counterbalancing* yang matang agar tidak mengganggu alur atau kenyamanan partisipan selama studi.

Saat menyusun laporan penelitian, pelaporan statistik harus mengikuti standar akademik yang ketat dan transparan. Contoh pada slide menunjukkan format pelaporan lengkap yang mencakup jenis uji, derajat kebebasan, nilai statistik, nilai-p, ukuran efek, serta interpretasi temuan secara kontekstual. Penyebutan persentase partisipan yang menunjukkan performa lebih baik pada kondisi tertentu membantu pembaca memahami implikasi praktis dari hasil uji statistik tersebut, melampaui sekadar angka signifikansi.

Pembahasan ini menjadi fondasi penting sebelum kita masuk ke slide berikutnya. Kita akan mendalami secara spesifik prosedur *repeated measures ANOVA*, mulai dari pengujian asumsi kritis seperti sphericity, penanganan pelanggaran asumsi melalui koreksi Greenhouse-Geisser, hingga pelaksanaan uji lanjutan (*post-hoc*) untuk mengidentifikasi pasangan kondisi mana yang benar-benar berbeda secara signifikan.

---

## Slide 018 - Repeated Measures: ANOVA dan Pengujian Lanjutan

### Narasi

Pada pertemuan sebelumnya, kita telah membahas uji statistik untuk desain within-subjects ketika hanya membandingkan dua kondisi, seperti paired samples t-test atau Wilcoxon signed-rank test. Ketika jumlah kondisi eksperimen meningkat menjadi lebih dari dua, pendekatan yang tepat dan lebih efisien adalah menggunakan Repeated Measures ANOVA. Uji ini dirancang khusus untuk situasi di mana setiap partisipan menjalani semua kondisi secara berurutan, misalnya membandingkan tiga tingkat umpan balik sistem: tanpa feedback, teks, dan suara.

Alur analisis statistiknya bersifat hierarkis dan harus diikuti secara ketat. Pertama, jalankan Repeated Measures ANOVA untuk menguji signifikansi secara keseluruhan antar kondisi. Jika hasilnya signifikan, langkah selanjutnya adalah melakukan uji lanjutan atau post-hoc comparisons, seperti Bonferroni atau Tukey, untuk mengidentifikasi pasangan kondisi mana yang benar-benar berbeda. Hasilnya harus dilaporkan secara spesifik, misalnya kondisi A lebih cepat daripada B. Sebaliknya, jika ANOVA tidak menunjukkan signifikansi, Anda tetap wajib melaporkan effect size dan confidence interval, serta mendiskusikan interpretasi dari temuan nol tersebut dalam konteks penelitian HCI agar tidak dianggap sebagai kegagalan metodologis.

Sebelum menjalankan uji ini, ada beberapa asumsi kritis yang harus diverifikasi oleh peneliti. Pertama, normalitas data harus diperiksa pada masing-masing kondisi secara terpisah. Kedua, asumsi sphericity harus dipenuhi, yaitu varians perbedaan antara semua pasangan kondisi harus relatif sama. Jika asumsi ini dilanggar, hasil ANOVA akan menjadi bias dan inflasi error type I meningkat, sehingga perlu diterapkan koreksi seperti Greenhouse-Geisser untuk menyesuaikan derajat kebebasan. Ketiga, pastikan tidak ada outlier ekstrem yang mendominasi skor partisipan tertentu, karena hal ini dapat sangat mempengaruhi hasil rata-rata dalam desain berulang.

Sebagai contoh pelaporan standar dalam publikasi internasional, Anda bisa menuliskan: "RM-ANOVA menunjukkan pengaruh signifikan tipe feedback terhadap task completion, F(2, 58) = 6.21, p = .003, η² = 0.18." Perhatikan bahwa laporan ini menyertakan statistik F, derajat kebebasan, nilai-p, dan ukuran efek eta-squared. Dilanjutkan dengan hasil post-hoc Bonferroni yang menjelaskan secara detail pasangan mana yang berbeda signifikan dan mana yang tidak, lengkap dengan nilai-p koreksinya. Format ini memenuhi standar transparansi data yang diharapkan di jenjang magister.

Memahami alur, asumsi, dan tata cara pelaporan Repeated Measures ANOVA ini menjadi fondasi penting sebelum kita beralih ke alternatif yang lebih robust ketika data tidak memenuhi syarat parametrik. Pada slide berikutnya, kita akan mengeksplorasi metode non-parametrik sebagai solusi analitis yang valid ketika distribusi data miring, berskala ordinal, atau memiliki sampel kecil, termasuk panduan keputusan berbasis pseudocode untuk pemilihan uji yang tepat.

---

## Slide 019 - Non-Parametric Analysis: Alternatif yang Robust

### Narasi

Setelah membahas analisis parametrik seperti Repeated Measures ANOVA pada slide sebelumnya, kita kini beralih ke alternatif yang lebih robust ketika asumsi normalitas tidak terpenuhi. Analisis non-parametrik menjadi pilihan utama ketika data Anda menunjukkan distribusi yang miring, terbatas pada rentang tertentu, atau berskala ordinal murni seperti rating Likert tanpa jaminan interval yang setara. Kondisi ini sangat umum dalam penelitian HCI, terutama saat mengumpulkan feedback pengguna melalui skala subjektif atau ketika jumlah partisipan terbatas sehingga uji normalitas sulit dipenuhi.

Selain masalah distribusi, keberadaan outlier yang tidak dapat dinormalisasi melalui transformasi matematis juga mengindikasikan perlunya pendekatan non-parametrik. Berbeda dengan uji parametrik yang bergantung pada mean dan varians, metode ini bekerja dengan merangking data, sehingga lebih tahan terhadap nilai ekstrem yang bisa mendistorsi hasil statistik.

Berikut adalah pemetaan langsung antara uji parametrik klasik dengan padanan non-parametriknya:
- Independent t-test → Mann-Whitney U (untuk 2 kelompok independen)
- Paired t-test → Wilcoxon signed-rank (untuk 2 kondisi terkait)
- One-way ANOVA → Kruskal-Wallis (untuk >2 kelompok independen)
- Repeated Measures ANOVA → Friedman (untuk >2 kondisi terkait)

Untuk memudahkan pengambilan keputusan analitis, Anda dapat mengikuti alur logika berikut yang direpresentasikan dalam pseudocode:

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

Logika ini menekankan bahwa ukuran sampel dan pemeriksaan distribusi adalah gerbang utama pengambilan keputusan. Jika sampel cukup besar dan distribusi memenuhi asumsi normalitas per kondisi, jalur parametrik tetap diprioritaskan karena memiliki statistical power yang lebih tinggi. Namun, begitu kedua syarat tersebut tidak terpenuhi, algoritma akan secara otomatis mengarahkan Anda ke uji non-parametrik yang sesuai dengan desain eksperimen, baik itu berpasangan maupun independen.

Perlu ditekankan bahwa penggunaan metode non-parametrik tidak berarti Anda menerima analisis yang "lebih lemah". Justru, dalam konteks Human-Computer Interaction, pendekatan ini sering kali lebih jujur terhadap karakteristik data empiris yang dikumpulkan dari pengguna nyata. Ketika data bersifat ordinal atau sangat terdistorsi, memaksa penggunaan uji parametrik justru dapat menghasilkan kesimpulan yang menyesatkan. Ketepatan pemilihan uji statistik harus selalu didasari oleh sifat data dan desain penelitian, bukan sekadar kebiasaan.

Dengan pemahaman ini tentang bagaimana menangani data kuantitatif yang tidak memenuhi asumsi ideal, kita siap melangkah ke tahap selanjutnya. Pada slide berikutnya, kita akan mengeksplorasi bagaimana data kualitatif ditransformasi menjadi kategori bermakna melalui proses coding, melengkapi bukti empiris yang kita butuhkan dalam penelitian HCI tingkat magister.

---

## Slide 020 - Qualitative Coding: Dari Data Teks ke Kategori Bermakna

### Narasi

Setelah membahas analisis statistik non-parametrik pada slide sebelumnya sebagai alternatif robust ketika asumsi distribusi normal tidak terpenuhi, kita kini beralih ke dimensi kualitatif dalam analisis data HCI. Penelitian interaksi manusia dan komputer sering menghasilkan data tekstual berupa transkrip wawancara, catatan observasi lapangan, atau respons terbuka dari partisipan. Bagian ini akan menjelaskan bagaimana mentransformasi data teks mentah tersebut menjadi kategori analitis yang bermakna melalui proses *qualitative coding*.

*Qualitative coding* adalah proses sistematis untuk memberi label pada segmen data tertentu menggunakan kode yang merangkum makna inti dari segmen tersebut. Sebagai ilustrasi, ketika seorang partisipan mengungkapkan dalam teknik *think-aloud* bahwa “AI-nya bingung kalau saya nanya konteks yang belom pernah disebut. Kayaknya dia lupa ya,” peneliti dapat memberikan kode seperti “AI kehilangan konteks percakapan”. Kode ini bukan sekadar ringkasan naratif, melainkan representasi analitis yang memungkinkan peneliti mengidentifikasi pola perilaku, hambatan, atau persepsi pengguna terhadap sistem interaktif.

Terdapat dua pendekatan utama dalam melakukan koding, yaitu *inductive* atau *open coding*, serta *deductive* atau *closed coding*. Pendekatan induktif mengandalkan kode yang muncul langsung dari data itu sendiri, sangat berguna saat mengeksplorasi fenomena baru atau menemukan tema yang tak terduga. Sebaliknya, pendekatan deduktif memulai dengan kerangka teori atau hipotesis yang sudah ada, lalu mencari bukti empiris dalam data untuk mendukung atau menantang tema yang telah diprediksi. Pemilihan pendekatan ini biasanya bergantung pada posisi epistemologis peneliti dan kedalaman tinjauan literatur yang telah dilakukan.

Untuk memastikan rigor dan keterulangan dalam analisis kualitatif, disarankan mengikuti alur kerja yang terstruktur:
1. Familiarisasi: baca seluruh data secara menyeluruh sebelum memberi label.
2. Koding awal: identifikasi segmen relevan dan berikan label kode secara spontan.
3. Penyempurnaan: gabungkan kode yang redundan, pisahkan yang terlalu luas, atau rapikan hierarki tematik.
4. Definisi eksplisit: tuliskan makna, kriteria inklusi, dan contoh untuk setiap kode → bentuk dasar codebook.
5. Penerapan konsisten: terapkan kode yang telah didefinisikan ke seluruh dataset.
6. Validasi: hitung *inter-rater agreement* untuk mengukur konsistensi antar-peneliti dan mengurangi bias subjektif.

Proses penyempurnaan kode dan dokumentasi kriteria koding ini akan berlanjut pada pembahasan berikutnya mengenai *codebook*. *Codebook* berfungsi sebagai dokumen standar yang menjamin konsistensi koding lintas waktu dan lintas coder, meningkatkan transparansi metodologi, serta memudahkan replikasi oleh peneliti lain di komunitas HCI. Dengan menguasai langkah-langkah koding kualitatif hari ini, Anda akan lebih siap menyusun instrumen analisis yang ketat untuk studi HCI berbasis campuran atau murni kualitatif.

---

## Slide 021 - Codebook: Dokumen Panduan Koding

### Narasi

Setelah proses koding kualitatif pada slide sebelumnya, kita memiliki kumpulan label atau kode dari data mentah. Tanpa panduan baku, interpretasi kode bisa berbeda antar peneliti atau berubah seiring waktu. Di sinilah codebook berfungsi sebagai dokumen panduan koding yang sistematis dan terstruktur.

Penggunaan codebook sangat krusial dalam penelitian tingkat magister karena menjamin konsistensi antar-coder dan konsistensi temporal. Selain itu, dokumen ini meningkatkan transparansi dan reproduktibilitas penelitian, dua pilar utama dalam publikasi ilmiah berkualitas. Saat menyusun paper atau saat peneliti lain ingin mereplikasi studi Anda, codebook menjadi referensi utama untuk memahami bagaimana data ditransformasi menjadi temuan.

Sebuah codebook yang baik harus memuat struktur kolom yang jelas. Berikut adalah komponen utamanya:
- **Code name**: Label singkat yang mewakili kategori, misalnya "trust_breakdown".
- **Definition**: Makna kode yang dijelaskan secara eksplisit dan operasional.
- **Inclusion criteria**: Syarat spesifik kapan data HARUS diberi kode ini.
- **Exclusion criteria**: Batasan kapan data TIDAK boleh dikategorikan sebagai kode ini.
- **Example & Non-example**: Kutipan teks yang valid dan kasus yang tampak mirip tetapi secara konseptual berbeda. Penyertaan non-example sering kali diabaikan, padahal fungsinya sangat strategis untuk mencegah ambiguitas klasifikasi.

Sebagai ilustrasi, perhatikan contoh codebook untuk konstruk kepercayaan terhadap AI. Kode trust_breakdown didefinisikan sebagai pernyataan partisipan yang kehilangan keyakinan pada sistem, dengan inclusion criteria berupa ungkapan keraguan, ketakutan salah, atau penolakan rekomendasi. Kutipan seperti "Saya tidak yakin jawabannya benar, jadi saya cek sendiri" menjadi contoh yang tepat. Sebaliknya, trust_build menangkap peningkatan keyakinan, ditandai dengan pengalaman AI yang membantu dan akurat. Contoh kutipannya adalah "Setelah beberapa kali benar, saya mulai percaya". Perbedaan definisi dan kriteria inklusi-eksklusi inilah yang menjaga objektivitas analisis.

Dengan codebook yang telah divalidasi dan diterapkan secara konsisten, data kualitatif kita kini siap untuk dipadatkan ke dalam pola-pola yang lebih makro. Langkah selanjutnya akan membahas bagaimana mengklasterkan kode-kode tersebut menjadi tema-tema analitis melalui pendekatan thematic analysis, yang akan kita bahas pada slide berikutnya.

---

## Slide 022 - Thematic Analysis: Dari Kode ke Tema

### Narasi

Setelah kita menyusun codebook yang terstruktur pada slide sebelumnya, langkah selanjutnya adalah melakukan analisis tematik atau thematic analysis. Metode ini merupakan pendekatan sistematis untuk mengidentifikasi, menganalisis, dan melaporkan pola-pola atau tema yang muncul dalam data kualitatif. Dalam konteks penelitian Human-Computer Interaction, thematic analysis sangat efektif digunakan untuk menggali pengalaman pengguna, mengungkap kebutuhan tersirat, serta memahami hambatan dan persepsi mereka terhadap suatu sistem atau teknologi.

Proses analisis tematik yang paling banyak diadopsi dalam literatur HCI mengikuti kerangka kerja enam fase dari Braun dan Clarke:
1. Familiarisasi dengan data: membaca transkrip secara mendalam dan mencatat ide awal.
2. Generate initial codes: menandai segmen data yang menarik atau relevan.
3. Searching for themes: mengelompokkan kode-kode terkait menjadi calon tema.
4. Reviewing themes: memeriksa konsistensi tema dengan keseluruhan dataset.
5. Defining & naming themes: merumuskan definisi dan memberi nama yang deskriptif pada setiap tema.
6. Producing the report: menyusun laporan akhir yang didukung oleh kutipan data primer.

Sebagai ilustrasi konkret, kode-kode seperti trust_build, reliable_answer, dan consistency_experience dapat digabungkan menjadi satu tema besar, misalnya "Kepercayaan dibangun melalui konsistensi jawaban". Di sisi lain, kode seperti trust_breakdown, external_check, dan double_check dapat membentuk tema "Ketidakpastian AI memunculkan kebutuhan verifikasi eksternal". Pengelompokan ini menunjukkan bagaimana data mentah yang terkode akhirnya bermuara pada insight yang bermakna bagi desain interaksi.

Perlu dicatat bahwa validitas proses pengkodean ini harus diuji sebelum tema final ditetapkan. Oleh karena itu, pada slide berikutnya kita akan membahas inter-rater agreement sebagai mekanisme untuk mengukur tingkat konsistensi antar-peneliti dalam menerapkan kode dan tema tersebut. Hal ini penting untuk memastikan bahwa temuan yang dihasilkan tidak bersifat subjektif, melainkan dapat direplikasi dan dipertanggungjawabkan secara ilmiah.

---

## Slide 023 - Inter-Rater Agreement: Menguji Konsistensi Koding

### Narasi

Setelah pembahasan tentang langkah-langkah thematic analysis pada slide sebelumnya, kita sekarang memasuki tahap validasi konsistensi koding. Proses identifikasi pola dalam data kualitatif memang inherent mengandung subjektivitas peneliti. Oleh karena itu, inter-rater agreement diperlukan untuk memastikan bahwa kategori yang dihasilkan bersifat objektif dan dapat direplikasi oleh peneliti lain tanpa kehilangan makna kontekstual.

Berikut adalah ukuran statistik yang umum digunakan untuk mengukur kesepakatan antar-penilai:
- **Percentage agreement**: Menghitung persentase kesesuaian langsung. Mudah dihitung, namun tidak mengoreksi kemungkinan kesepakatan yang terjadi secara kebetulan atau acak.
- **Cohen's κ (kappa)**: Indeks yang sudah mengoreksi faktor kebetulan, sehingga lebih akurat dan banyak dipakai untuk analisis dua coder.
- **Krippendorff's α**: Lebih fleksibel untuk situasi dengan lebih dari dua coder dan mampu menangani berbagai tipe data kualitatif.

Untuk Cohen's kappa, tolak ukur interpretasinya adalah sebagai berikut:
- Nilai > 0,81: Hampir sempurna
- Rentang 0,61–0,80: Substantial (substansial)
- Rentang 0,41–0,60: Moderate (moderat)
- Nilai < 0,40: Lemah, menandakan perlunya perbaikan definisi kode atau penyempurnaan panduan koding

Penting untuk dipahami bahwa target utama dalam penelitian HCI bukanlah sekadar mengejar angka kappa yang tinggi secara matematis. Fokus sebenarnya adalah memastikan bahwa setiap kode yang kita buat benar-benar mewakili realitas data secara konsisten dan dapat dipertanggungjawabkan secara ilmiah. Angka statistik hanyalah alat bantu, bukan pengganti kedalaman interpretasi.

Dengan konsistensi koding yang teruji, fondasi data kualitatif kita menjadi lebih kokoh dan kredibel. Langkah logis berikutnya dalam membangun bukti empiris yang kuat adalah menggabungkan berbagai sumber atau perspektif analisis, yang akan kita bahas secara mendalam pada slide berikutnya mengenai triangulasi.

---

## Slide 024 - Triangulasi: Memperkuat Evidence dari Banyak Sisi

### Narasi

Setelah kita membahas inter-rater agreement pada slide sebelumnya untuk memastikan konsistensi koding antar peneliti, langkah selanjutnya dalam memperkuat validitas temuan adalah menerapkan triangulasi. Triangulasi merupakan strategi metodologis yang memanfaatkan lebih dari satu sumber data, metode, peneliti, atau kerangka teori untuk memeriksa konsistensi hasil dan meminimalkan bias subjektif.

Dalam praktik penelitian HCI, terdapat empat jenis triangulasi yang sering diadopsi. Pertama, data triangulation, yaitu menggabungkan berbagai jenis data seperti log sistem, catatan wawancara, dan observasi lapangan. Kedua, method triangulation, yang melibatkan penggunaan mixed methods, misalnya memadukan survei kuantitatif dengan wawancara mendalam kualitatif. Ketiga, investigator triangulation, di mana lebih dari satu peneliti terlibat dalam proses analisis untuk mengurangi bias individu. Keempat, theory triangulation, yang mengajak peneliti menafsirkan data melalui perspektif teori yang berbeda-beda agar tidak terjebak pada satu lensa analitis.

Ilustrasi pada slide ini menunjukkan bagaimana tiga sumber data berbeda dapat mengarah pada kesimpulan yang sama. Log sistem mencatat bahwa pengguna menekan tombol bantuan lima kali. Wawancara mengungkapkan perasaan bingung dengan urutan navigasi. Sementara itu, observasi langsung menangkap perilaku ragu-ragu dan keluhan nonverbal. Ketika ketiga sumber ini saling menguatkan, klaim penelitian menjadi jauh lebih meyakinkan dan robust.

Namun, penting untuk diingat bahwa jika data-data tersebut justru saling bertentangan, hal itu bukan alasan untuk mengabaikan atau memilih data yang paling nyaman. Justru, ketidaksesuaian tersebut menjadi peluang berharga untuk penyelidikan lebih lanjut. Discrepancy dalam data sering kali mengungkap nuansa kontekstual, keterbatasan instrumen, atau variabel tersembunyi yang perlu digali lebih dalam.

Pendekatan triangulasi ini akan semakin terstruktur ketika kita memasuki analisis mixed methods pada slide berikutnya. Di sana, kita akan melihat bagaimana integrasi antara data kuantitatif dan kualitatif dapat dirancang secara eksplanatori, eksploratori, atau konkuren, sehingga menghasilkan bukti empiris yang lebih komprehensif dan siap dipertanggungjawabkan secara ilmiah.

---

## Slide 025 - Analisis Mixed Methods: Integrasi Kuantitatif-Kualitatif

### Narasi

Setelah membahas triangulasi pada slide sebelumnya sebagai strategi verifikasi konsistensi temuan melalui berbagai sumber atau metode, kita kini beralih ke analisis *mixed methods* sebagai kerangka integrasi yang lebih terstruktur antara data kuantitatif dan kualitatif. Dalam penelitian HCI tingkat magister, pendekatan ini menjadi standar emas karena memungkinkan peneliti menangkap baik besaran statistik maupun kedalaman pengalaman pengguna secara simultan.

Prinsip dasar integrasi *mixed methods* terletak pada pembagian fungsi yang saling melengkapi. Data kuantitatif menjawab pertanyaan mengenai seberapa besar, berapa banyak, atau apakah suatu efek bersifat signifikan secara statistik. Sebaliknya, data kualitatif menggali dimensi kognitif dan emosional pengguna dengan menjawab mengapa dan bagaimana fenomena tersebut terjadi. Integrasi keduanya umumnya dijalankan dalam dua tahap: pertama, analisis berjalan secara terpisah sesuai karakteristik metodologis masing-masing; kedua, hasil kedua analisis tersebut dibandingkan, dikombinasikan, atau saling menjelaskan selama tahap sintesis temuan.

Dalam praktik penelitian HCI, terdapat tiga pola integrasi yang paling sering diadopsi:
- **Explanatory sequential**: Penelitian dimulai dengan pengumpulan data kuantitatif. Ketika hasil kuantitatif menunjukkan pola yang mengejutkan atau memerlukan klarifikasi, peneliti kemudian mengumpulkan data kualitatif untuk menguraikan mekanisme penyebabnya.
- **Exploratory sequential**: Fase awal bersifat kualitatif untuk mengidentifikasi konstruk, kategori, atau variabel penting dari populasi target. Temuan eksploratif ini kemudian diterjemahkan menjadi instrumen atau hipotesis yang diuji secara kuantitatif.
- **Concurrent**: Kedua jenis data dikumpulkan dan dianalisis secara bersamaan. Tujuannya adalah untuk saling memperkaya perspektif (*complementarity*) sekaligus melakukan konfirmasi silang (*corroboration*) antar metode.

Mari kita telusuri contoh studi HCI yang disajikan pada slide. Sebuah aplikasi baru mencatatkan skor SUS rata-rata sebesar 82, yang secara kuantitatif mengindikasikan tingkat kepuasan atau kemudahan penggunaan yang tinggi. Namun, saat peneliti melakukan wawancara mendalam, terungkap bahwa partisipan masih merasa ragu karena mereka tidak memahami apa yang dilakukan AI di balik layar. Integrasi kedua data ini menghasilkan temuan yang lebih bernuansa: skor tinggi sebenarnya hanya mencerminkan kemudahan penggunaan permukaan (*surface usability*), sementara isu kepercayaan (*trust*) dan transparansi algoritma masih menjadi hambatan substantif yang perlu ditangani secara desain interaksi.

Pemahaman mendalam terhadap temuan campuran seperti ini akan menjadi fondasi kritis sebelum kita menerjemahkannya ke dalam bentuk presentasi ilmiah. Pada slide berikutnya, kita akan membahas prinsip-prinsip visualisasi data yang jujur dan informatif, termasuk panduan pemilihan grafik yang sesuai dengan struktur data serta *anti-patterns* yang wajib dihindari agar interpretasi hasil penelitian tetap akurat, transparan, dan bebas dari distorsi persepsi.

---

## Slide 026 - Data Visualization: Menyajikan Data Secara Jujur dan Informatif

### Narasi

Setelah membahas strategi integrasi data kuantitatif dan kualitatif dalam desain *mixed methods*, langkah kritis berikutnya adalah menerjemahkan temuan tersebut ke dalam bentuk visual yang akurat dan mudah ditafsirkan. Visualisasi data dalam penelitian HCI bukan sekadar elemen presentasi, melainkan instrumen argumentasi ilmiah yang menentukan seberapa kuat bukti yang Anda sampaikan kepada reviewer maupun komunitas akademik.

Empat prinsip fundamental harus menjadi acuan utama saat merancang grafik untuk publikasi atau laporan penelitian. Pertama, hindari manipulasi visual yang menyesatkan, seperti memotong sumbu Y tanpa penanda yang eksplisit, karena hal ini dapat mendistorsi persepsi terhadap magnitudo perbedaan antar kondisi. Kedua, sesuaikan jenis grafik dengan struktur data; jangan mengorbankan keterbacaan demi estetika semata. Ketiga, selalu komunikasikan sebaran data dan ketidakpastian statistik melalui *boxplot*, *error bars*, atau *violin plot*. Keempat, lengkapi setiap visual dengan metadata lengkap: satuan pengukuran, identitas variabel, legenda, dan jumlah partisipan (*N*).

Untuk mempercepat pengambilan keputusan teknis, berikut adalah panduan pemilihan grafik berdasarkan tujuan analisis:
- Distribusi satu variabel kontinu: histogram, *boxplot*, atau *violin plot*.
- Perbandingan antar 2–3 kelompok: *boxplot* dengan overlay titik data individu, atau *bar chart* disertai *error bar*.
- Hubungan dua variabel: *scatterplot* dengan garis regresi atau koefisien korelasi.
- Data kategorikal: *bar chart*.
- Perubahan antar kondisi dalam desain *within-subject*: *spaghetti plot* atau *paired line plot*.

Dalam eksekusi lapangan, peneliti sering terjebak pada pola visual yang justru melemahkan kredibilitas temuan. Perhatikan contoh kontras berikut:
```
BURUK: Bar chart 3D yang memotong sumbu Y dari 40
BURUK: Pie chart dengan > 5 kategori
BURUK: Error bars hanya menunjukkan SEM tanpa penjelasan
BAIK: Strip chart / beeswarm memperlihatkan seluruh titik data
```
Grafik tiga dimensi cenderung menciptakan ilusi perspektif yang mengganggu akurasi pembacaan nilai. Diagram pai juga tidak direkomendasikan ketika memiliki lebih dari lima kategori karena mata manusia sulit membandingkan sudut secara presisi. Selain itu, *error bar* yang hanya mencantumkan *Standard Error of the Mean* (SEM) tanpa keterangan metodologis dapat menimbulkan kesalahpahaman; selalu nyatakan secara eksplisit apakah yang ditampilkan adalah standar deviasi, SEM, atau *Confidence Interval* (CI). Penggunaan *strip chart* atau *beeswarm plot* sebagai alternatif sangat disarankan karena menyingkirkan agregasi berlebihan dan menampilkan heterogenitas data secara transparan.

Penerapan prinsip kejujuran visual ini akan memperkuat fondasi argumentasi Anda sebelum memasuki tahap penyajian inferensi statistik. Pada slide berikutnya, kita akan membahas teknik khusus untuk memvisualisasikan ukuran efek, interval kepercayaan, serta pola konsistensi data *within-subjects*, sehingga alur bukti penelitian Anda dapat dibaca secara logis dan meyakinkan.

---

## Slide 027 - Visualisasi untuk Hasil Statistik

### Narasi

Pada slide ini, kita beralih dari prinsip umum visualisasi data ke penerapan spesifiknya dalam menyajikan hasil statistik penelitian HCI. Setelah sebelumnya membahas bagaimana memilih grafik yang tepat dan menghindari pola penyajian yang menyesatkan, langkah selanjutnya adalah memastikan bahwa efek eksperimen dan sebaran data ditampilkan secara akurat dan transparan.

Untuk menampilkan effect atau perbedaan antar kondisi, gunakan representasi yang memisahkan nilai tengah dengan interval kepercayaan. Perhatikan skema pada slide: simbol kotak mewakili mean, sedangkan titik di ujung garis menunjukkan batas Confidence Interval (CI) 95%. Aturan heuristik menyatakan bahwa jika CI dua kelompok tidak saling tumpang tindih, kemungkinan terdapat perbedaan signifikan. Namun, perlu ditekankan bahwa aturan tumpang tindih ini hanya bersifat indikatif. Uji statistik formal seperti independent samples t-test atau ANOVA tetap wajib dilakukan untuk mengkonfirmasi signifikansi secara matematis.

Desain penelitian within-subjects memerlukan pendekatan visualisasi yang berbeda. Gunakan spaghetti plot atau paired line plot untuk menghubungkan respons setiap partisipan antar kondisi. Visualisasi ini sangat krusial karena memperlihatkan konsistensi arah efek di tingkat individu. Terkadang, rata-rata agregat mungkin tampak mirip, tetapi garis individu akan mengungkap apakah sebagian besar partisipan mengalami peningkatan, penurunan, atau justru variasi acak terhadap intervensi yang diberikan.

Terdapat beberapa catatan teknis yang harus diperhatikan saat menyusun grafik statistik:
- Selalu tampilkan titik data individual, terutama ketika ukuran sampel (N) kecil. Grafik agregat saja dapat menyembunyikan outlier atau pola heterogenitas.
- Error bar wajib disertai keterangan eksplisit mengenai metrik yang digunakan, apakah Standard Deviation (SD), Standard Error of the Mean (SEM), atau Confidence Interval (CI). Ketidakjelasan ini sering menjadi sumber kritik dalam peer review.
- Hindari ketergantungan berlebihan pada bar chart konvensional. Bar chart cenderung mengaburkan sebaran data asli. Kombinasikan selalu dengan strip chart, boxplot, atau scatter plot untuk memberikan gambaran distribusi yang utuh.

Dengan visualisasi statistik yang sudah memenuhi standar transparansi dan akurasi ini, fondasi penulisan laporan penelitian pun menjadi lebih solid. Tahap berikutnya, kita akan membahas bagaimana merangkum temuan-temuan tersebut ke dalam struktur pelaporan hasil kuantitatif yang sesuai dengan standar akademik internasional, termasuk format penulisan statistik ala APA style.

---

## Slide 028 - Reporting Results: Bagian Hasil Kuantitatif

### Narasi

Setelah pada slide sebelumnya kita membahas bagaimana memvisualisasikan hasil statistik dengan tepat, khususnya melalui plot individu, keterangan error bar, dan spaghetti plot untuk desain within-subjects, kini kita beralih ke tahap selanjutnya: pelaporan resmi hasil kuantitatif dalam penelitian HCI. Visualisasi yang akurat hanyalah fondasi; yang lebih kritis adalah cara Anda menyusun dan menyajikan temuan tersebut secara sistematis agar dapat dievaluasi oleh reviewer maupun peneliti lain.

Struktur pelaporan hasil kuantitatif yang disarankan mengikuti alur logis penelitian empiris:
1. **Data cleaning summary** — jelaskan jumlah data yang digunakan, data yang dikeluarkan, serta alasan metodologis atau teknis penghapusannya.
2. **Descriptive statistics** — sajikan M dan SD, atau Median dan IQR per kondisi, preferably dalam tabel ringkas agar mudah dibandingkan.
3. **Assumption checks** — laporkan hasil uji normalitas atau sphericity sebagai dasar pemilihan antara uji parametrik dan non-parametrik.
4. **Main analysis** — presentasikan uji hipotesis utama yang secara langsung menjawab pertanyaan penelitian (RQ).
5. **Additional/post-hoc analyses** — cantumkan analisis eksplorasi tambahan hanya jika relevan dan disertai justifikasi yang jelas.

Untuk format penulisan, ikuti pedoman APA style secara konsisten. Contoh standar pelaporan adalah: "An independent samples t-test revealed a significant difference in completion time between conditions A and B, t(38) = 2.31, p = .026, Cohen's d = 0.74, 95% CI [0.08, 1.40]." Setiap komponen wajib dicantumkan lengkap: nama uji, derajat kebebasan, nilai statistik, nilai-p, ukuran efek, dan interval kepercayaan. Hal ini menjamin transparansi dan memungkinkan pembaca menilai kekuatan bukti secara mandiri.

Terdapat beberapa kesalahan umum yang sering terlewatkan saat menulis bagian hasil. Pertama, jangan hanya mengandalkan nilai-p; selalu sertakan ukuran efek karena signifikansi statistik tidak otomatis mencerminkan signifikansi praktis. Kedua, laporkan juga hasil yang tidak signifikan, karena ketiadaan temuan tetap merupakan kontribusi ilmiah yang valid. Ketiga, hindari interpretasi keliru dengan menyimpulkan "tidak ada efek" ketika uji menunjukkan non-signifikansi; kemungkinan besar masalahnya terletak pada statistical power yang rendah atau ukuran sampel yang belum memadai.

Penerapan struktur dan kehati-hatian ini akan memastikan laporan hasil kuantitatif Anda memenuhi standar rigor akademik tingkat magister. Pada slide berikutnya, kita akan menggeser fokus ke pelaporan hasil kualitatif, yang memerlukan pendekatan berbeda dalam mendeskripsikan proses coding, menyajikan tema beserta kutipan partisipan, serta menerapkan aturan interpretasi yang ketat terhadap klaim kualitatif.

---

## Slide 029 - Reporting Results: Bagian Hasil Kualitatif

### Narasi

Setelah membahas pelaporan hasil kuantitatif pada slide sebelumnya yang menekankan presisi statistik, pemeriksaan asumsi, dan kepatuhan terhadap gaya penulisan APA, kita kini beralih ke aspek kualitatif. Pelaporan hasil kualitatif dalam penelitian HCI menuntut pendekatan berbeda, di mana fokus utamanya adalah transparansi proses analisis, jejak audit yang jelas, dan kedalaman konteks perilaku pengguna.

Struktur pelaporan hasil kualitatif yang disarankan terdiri dari empat elemen kunci:
- Deskripsi proses analisis: jabarkan secara rinci bagaimana pengkodean dilakukan, kerangka teori atau induktif yang dipakai, serta jumlah peneliti yang terlibat dalam proses tersebut.
- Inter-rater reliability: jika lebih dari satu analis melakukan coding, laporkan tingkat kesepakatan antar penilai untuk menjamin konsistensi dan objektivitas interpretasi.
- Presentasi tema: setiap tema harus disertai nama yang deskriptif, definisi operasional yang tegas, serta kutipan langsung dari partisipan sebagai bukti empiris.
- Penjelasan hubungan antar tema: jika terdapat keterkaitan konseptual, pola kausal, atau hierarki antar tema, uraikan secara eksplisit bagaimana elemen-elemen tersebut saling berinteraksi.

Perhatikan contoh tabel kutipan pada slide ini. Tema seperti ketidakpastian, beban verifikasi, dan kepercayaan bertahap masing-masing didukung oleh pernyataan partisipan yang konkret. Kutipan langsung ini berfungsi sebagai anchor empiris yang memungkinkan pembaca melacak kembali bagaimana peneliti menurunkan abstraksi teoretis dari data lapangan, sekaligus memperkuat kredibilitas temuan.

Pada bagian aturan interpretasi, terdapat pedoman ketat mengenai pemilihan diksi. Hindari frasa umum seperti "banyak partisipan mengatakan..." karena klaim tersebut sulit diverifikasi secara metodologis. Ganti dengan bahasa yang dapat dipertanggungjawabkan, misalnya "mayoritas partisipan (12 dari 15) melaporkan...", "hampir semua responden menyebutkan...", atau gunakan frasa deskriptif kualitatif yang spesifik. Jika Anda mengklaim adanya kecenderungan tertentu, pastikan untuk menyertakan gambaran penyebaran atau frekuensi relatifnya. Prinsip ini menjaga integritas akademik sekaligus menghindari generalisasi yang berlebihan.

Poin-poin pelaporan kualitatif ini akan terintegrasi secara utuh ketika kita meninjau alur kerja analisis data gabungan pada slide berikutnya. Di sana, kita akan melihat bagaimana tahap follow-up explanation menggunakan thematic analysis untuk menjawab pertanyaan "mengapa" setelah uji statistik kuantitatif selesai, sehingga menghasilkan evidensi yang komprehensif, triangulasi, dan siap menjadi kontribusi ilmiah pada jenjang magister.

---

## Slide 030 - Contoh Workflow Analisis Data pada Eksperimen HCI

### Narasi

Slide ini menyajikan contoh alur kerja analisis data kuantitatif yang dirancang khusus untuk eksperimen Human-Computer Interaction. Skenario yang diambil adalah pengujian efek dua desain chatbot AI terhadap dua metrik utama: waktu penyelesaian tugas (*completion time*) dan tingkat kepercayaan pengguna (*trust_score*). Struktur dataset mentah terdiri dari 30 partisipan yang masing-masing menjalani dua kondisi eksperimen, menghasilkan total 60 baris data. Variabel yang tercatat meliputi *participant_id*, *condition*, *order*, *completion_time*, *error_count*, *trust_score* berskala Likert, serta *open_comment* sebagai pendamping kontekstual.

Alur kerja dimulai dengan **Step 1 — Data cleaning**. Peneliti wajib memeriksa adanya nilai hilang (*missing values*) dan mendokumentasikannya secara transparan. Deteksi outlier pada *completion_time* juga diperlukan karena nilai ekstrem dapat mendistorsi hasil statistik. Selain itu, trial yang mengalami kegagalan sistem seperti jaringan timeout harus dihapus atau diberi flag khusus agar tidak mencemari validitas eksperimen.

Setelah data bersih, proses berlanjut ke **Step 2 — Descriptive statistics**. Untuk *completion_time* yang biasanya mengikuti distribusi normal, perhitungan mean dan standar deviasi per kondisi menjadi pilihan utama. Sebaliknya, *trust_score* berskala ordinal cenderung tidak normal, sehingga median dan interquartile range (IQR) dipilih sebagai ukuran pemusatan dan dispersi yang lebih robust.

**Step 3 — Assumption checks** menjadi gerbang kritis sebelum pengujian hipotesis. Uji Shapiro-Wilk dijalankan untuk memverifikasi normalitas data. Ketika hasil uji menunjukkan pelanggaran asumsi normalitas, peneliti tidak memaksakan uji parametrik seperti paired t-test. Sebagai gantinya, alur ini mengarahkan pemilihan uji non-parametrik Wilcoxon signed-rank test yang sesuai untuk data berpasangan dengan distribusi tidak normal.

Pada **Step 4 — Main analysis**, perbandingan *completion_time* antar kondisi dievaluasi menggunakan Wilcoxon test, dilengkapi dengan perhitungan effect size (r) untuk mengukur magnitudo perbedaan secara praktis. Evaluasi identik diterapkan pada *trust_score*. Penggunaan effect size sangat krusial dalam penelitian tingkat magister karena melampaui sekadar signifikansi statistik dan memberikan bukti empiris yang bermakna.

Langkah penutup adalah **Step 5 — Follow-up explanation**. Kolom *open_comment* dibuka untuk dianalisis secara tematik guna menjawab pertanyaan “mengapa” di balik angka statistik. Pendekatan campuran (*mixed-methods*) ini memastikan temuan kuantitatif tidak berdiri sendiri, melainkan diperkuat oleh narasi pengalaman pengguna.

Alur kerja kuantitatif ini melengkapi struktur pelaporan hasil kualitatif pada slide sebelumnya, sekaligus menyiapkan transisi logis menuju slide berikutnya yang akan membedah workflow analisis data kualitatif murni. Dengan menguasai kedua pipeline ini, mahasiswa dapat merancang studi HCI yang rigor, transparan, dan memenuhi standar publikasi konferensi internasional terindeks Scopus.

---

## Slide 031 - Contoh Workflow Analisis Data Kualitatif pada Studi HCI

### Narasi

Setelah menelusuri alur kerja analisis kuantitatif pada slide sebelumnya, kita kini beralih ke pendekatan kualitatif. Dalam penelitian HCI tingkat magister, data kualitatif sering kali menjadi kunci untuk memahami nuansa pengalaman pengguna yang tidak mudah diukur secara numerik. Sebagai ilustrasi, mari kita perhatikan skenario mengeksplorasi pengalaman pengguna terhadap AI assistant berdasarkan dua belas transkrip wawancara semi-terstruktur dengan durasi total empat ratus delapan puluh menit.

Tahap pertama dimulai dari transkripsi dan familiarisasi. Anda tidak boleh langsung melakukan pengkodean begitu rekaman selesai. Baca setiap transkrip berulang kali sambil mencatat memo awal mengenai kesan umum, pola menarik, atau pertanyaan yang muncul. Proses ini membangun pemahaman kontekstual yang mendalam sebelum masuk ke tahap analisis sistematis.

Pada tahap open coding, label atau kode muncul langsung dari data, bukan dari kerangka teori yang sudah ditetapkan sebelumnya. Misalnya, Anda mungkin menemukan kode seperti "butuh konfirmasi visual", "ragu pada jawaban AI", "perlu mengulang pertanyaan", atau "merasa diawasi". Kode-kode ini bersifat deskriptif dan menangkap fenomena yang dilaporkan langsung oleh partisipan tanpa bias teoritis.

Setelah kode terkumpul, langkah selanjutnya adalah mengelompokkannya menjadi calon tema. Dari contoh kode di atas, Anda bisa menyatukannya ke dalam kategori lebih tinggi seperti "verifikasi eksternal" atau "ketidaknyamanan karena AI yang terlalu personal". Tahap ini membutuhkan keseimbangan antara intuisi analitis dan disiplin untuk menjaga keterkaitan erat dengan data asli.

Review tema merupakan fase kritis untuk memastikan validitas internal. Kembalikan perhatian Anda ke transkrip mentah; verifikasi apakah setiap tema benar-benar konsisten dengan kutipan partisipan. Jika ada tema yang tumpang tindih atau kurang kuat, gabungkan atau hapus. Hindari memaksakan struktur yang rapi hanya demi kepentingan presentasi, karena keakuratan interpretasi harus tetap menjadi prioritas.

Untuk meningkatkan reliabilitas, lakukan inter-rater check. Minta rekan peneliti atau coder kedua untuk mengkode sekitar dua puluh persen dari seluruh transkrip secara independen. Hitung koefisien Cohen’s kappa untuk mengukur kesepakatan antar-coder. Jika nilai kappa berada di bawah nol enam, definisi kode perlu diperjelas dan proses pengkodean diulang hingga mencapai konsistensi yang memadai.

Langkah terakhir adalah menulis narasi hasil analisis disertai kutipan pendukung yang relevan. Kutipan bukan sekadar pelengkap, melainkan bukti empiris yang memperkuat klaim temuan Anda. Pastikan setiap pernyataan analitis diimbangi dengan data konkret dari partisipan, sehingga reviewer dapat melacak jejak logika Anda dari data mentah hingga kesimpulan akhir.

Alur kerja kualitatif ini melengkapi pendekatan kuantitatif yang telah kita bahas sebelumnya. Keduanya memiliki kekuatan masing-masing dalam menjawab pertanyaan penelitian HCI yang kompleks. Selanjutnya, kita akan membahas bagaimana mengevaluasi kualitas evidence yang dihasilkan dari kedua metode tersebut, termasuk penggunaan checklist reflektif untuk memastikan klaim penelitian Anda solid, transparan, dan siap menghadapi tinjauan akademik.

---

## Slide 032 - Mengevaluasi Kualitas Evidence Anda

### Narasi

Setelah menelusuri contoh alur kerja analisis kualitatif pada slide sebelumnya, langkah kritis berikutnya adalah menghentikan proses penulisan sejenak untuk mengevaluasi kualitas evidence yang telah dihasilkan. Prosedur analisis yang sistematis tidak otomatis menjamin bahwa temuan penelitian layak dijadikan klaim ilmiah. Anda perlu memastikan bahwa bukti tersebut benar-benar solid, transparan, dan siap menghadapi scrutiny akademis sebelum masuk ke tahap penyusunan paper.

Gunakan checklist reflektif berikut sebagai filter akhir sebelum mengajukan kesimpulan:
• Verifikasi kebersihan dan dokumentasi data, termasuk jejak proses pembersihan dan transformasi data.
• Pastikan konsistensi mutlak antara teknik analisis, tipe data, dan desain penelitian yang dirumuskan di awal.
• Cek kepatuhan terhadap asumsi statistik, khususnya uji normalitas, homogenitas varians, dan independensi observasi.
• Utamakan pelaporan effect size dan confidence interval alongside p-value untuk menggambarkan besaran dampak praktis.
• Dukung setiap kategori kualitatif dengan kutipan primer yang memadai, representatif, dan tidak cherry-picking.
• Terapkan triangulasi metodologis atau sumber data untuk memperkuat temuan inti.
• Tuliskan keterbatasan analisis secara eksplisit dan jujur sesuai standar akademik S2.
• Batasi klaim agar tidak melampaui kapasitas dukungan data (hindari overclaiming).
• Dokumentasikan setiap langkah analisis sedemikian rupa sehingga replikasi oleh peneliti lain memungkinkan.

Pada jenjang magister, standar pelaporan menuntut pergeseran paradigma dari sekadar signifikansi statistik menuju estimasi presisi dan reprodusibilitas. Nilai p-value saja tidak cukup menggambarkan makna empiris dari suatu pola interaksi manusia-komputer. Demikian pula, dalam studi kualitatif, kutipan harus mencerminkan variasi dalam dataset dan secara proporsional mendukung kode tematik yang telah dikembangkan. Triangulasi menjadi mekanisme utama untuk meminimalkan researcher bias dan meningkatkan kredibilitas interpretasi kontekstual.

Pertanyaan pemantik pada slide ini dirancang untuk melatih mentalitas reviewer dan sikap skeptis ilmiah. Ketika ditanya, "Apakah ada penjelasan alternatif untuk hasil Anda?", respons Anda harus didasarkan pada analisis sensitivitas, kontrol variabel, atau data tambahan yang telah Anda siapkan. Kemampuan menjawab pertanyaan ini secara meyakinkan menunjukkan kedalaman pemahaman Anda terhadap batasan dan kekuatan evidence yang dihasilkan.

Evaluasi kualitas evidence ini merupakan fondasi langsung menuju pembahasan validitas pada pertemuan berikutnya. Tanpa pemeriksaan rigor melalui checklist ini, hasil analisis yang tampak signifikan berisiko rapuh ketika diuji terhadap ancaman internal validity, construct validity, hingga sampling bias. Pertemuan 13 dan 14 sesungguhnya membentuk satu kesatuan logis: Anda perlu menguasai bagaimana evidence terbentuk, sekaligus menyadari faktor-faktor struktural yang dapat melemahkannya. Persiapkan diri untuk mendalami kerangka validitas, bias, dan etika penelitian pada sesi mendatang.

---

## Slide 033 - Hubungan Data Analysis dengan Pertemuan 14

### Narasi

Pada slide sebelumnya, kita telah menyusun checklist reflektif untuk memastikan bahwa setiap claim penelitian didukung oleh data yang bersih, analisis yang tepat, dan pelaporan effect size yang memadai. Hari ini, kita akan mengintegrasikan hasil analisis tersebut ke dalam kerangka evaluasi bukti ilmiah. Proses analisis data memang menghasilkan angka atau tema, namun nilai ilmiahnya baru terlihat ketika kita secara kritis memeriksa apakah hasil tersebut benar-benah mencerminkan realitas yang diteliti.

Perhatikan struktur logika pada blok teks berikut:
```
Hasil signifikan yang tampak kuat
        ↓
ditinjau dari internal validity: mungkin ada order effect
ditinjau dari construct validity: instrumen mungkin tidak mengukur
apa yang dimaksud
ditinjau dari sampling bias: partisipan tidak representatif
→ kesimpulan yang prematur
```
Alur ini menegaskan bahwa signifikansi statistik semata tidak cukup. Sebuah temuan yang tampak kuat harus diuji ketahanannya melalui berbagai lensa validitas. Jika diabaikan, hasil penelitian mudah rapuh: internal validity yang lemah akibat order effect dapat memutarbalikkan hubungan sebab-akibat, construct validity yang buruk menunjukkan instrumen tidak menangkap konstruk teoritis, dan sampling bias membuat generalisasi menjadi mustahil. Akibatnya, peneliti terjebak pada kesimpulan prematur yang tidak tahan uji peer-review.

Oleh karena itu, Pertemuan 13 dan Pertemuan 14 dirancang sebagai satu kesatuan metodologis. Anda tidak boleh memisahkan teknik analisis dari pertanyaan tentang kekuatan bukti. Memahami jenis analisis yang membentuk evidence sama pentingnya dengan mengidentifikasi ancaman yang dapat melemahkannya, mulai dari masalah validitas, bias seleksi, reproducibility, hingga implikasi etika. Kesadaran ganda inilah yang membedakan praktik penelitian magister dari sekadar pengerjaan tugas teknis.

Menghubungkannya dengan slide berikutnya, pertemuan 14 akan membedah secara sistematis dimensi-dimensi validitas dan prinsip reproducible research. Kita akan membahas internal validity, external validity, construct validity, hingga ecological validity, disertai strategi mengontrol confounding factors, mengenali berbagai bias, serta menerapkan standar research ethics seperti informed consent dan perlindungan subjek manusia. Jika analisis data hari ini menjawab pertanyaan tentang bagaimana proses pengolahan dilakukan, maka pertemuan berikutnya akan menjawab sejauh mana hasil tersebut dapat dipercaya, direplikasi, dan dipertanggungjawabkan secara ilmiah.

---

## Slide 034 - Pertemuan Berikutnya: Validity, Reproducibility & Research Ethics

### Narasi

Slide ini berfungsi sebagai peta jalan menuju materi pertemuan berikutnya. Setelah hari ini kita mendalami teknik analisis data untuk menghasilkan bukti empiris, fokus kita akan bergeser ke evaluasi kualitas dan integritas dari bukti tersebut. Pertemuan selanjutnya akan membahas tiga pilar utama yang menentukan kredibilitas penelitian HCI: validitas, reproduktibilitas, dan etika penelitian.

Kita akan menguraikan empat jenis validitas yang harus Anda pertimbangkan saat menafsirkan hasil analisis:
- **Internal validity**: Menjamin bahwa hubungan sebab-akibat yang ditemukan benar-benar disebabkan oleh manipulasi variabel, bukan oleh faktor lain.
- **External validity**: Menilai batas kemampuan hasil penelitian untuk digeneralisasi ke konteks, populasi, atau setting yang berbeda.
- **Construct validity**: Memastikan bahwa instrumen atau metrik yang digunakan benar-benar mengukur konstruk teoretis yang dimaksudkan.
- **Ecological validity**: Mengevaluasi apakah kondisi eksperimen mencerminkan kompleksitas dan dinamika penggunaan teknologi di dunia nyata.

Selain itu, kita akan membahas ancaman metodologis seperti confounding factors dan berbagai bentuk bias, termasuk sampling bias, selection bias, dan researcher bias. Faktor-faktor ini sering kali secara halus menggeser interpretasi data jika tidak dikontrol sejak tahap desain penelitian.

Di ranah metodologi kontemporer, reproducibility akan menjadi standar ketat. Kita akan mempelajari bagaimana merancang protokol penelitian dan dokumentasi kode yang memungkinkan peneliti lain mengulang prosedur Anda dan memperoleh hasil serupa. Tanpa reproduktibilitas, temuan dalam HCI sulit diterima sebagai kontribusi ilmiah yang solid.

Aspek terakhir yang tak kalah krusial adalah research ethics. Informed consent, perlindungan privasi data partisipan, dan mekanisme human-subject protection akan menjadi kerangka non-negosiable dalam setiap studi HCI tingkat magister.

Perhatikan pertanyaan penghubung pada slide ini: jika analisis data hari ini menjawab bagaimana cara Anda memproses data, maka pertemuan berikutnya akan menjawab sejauh mana hasil tersebut dapat dipercaya dan dipertanggungjawabkan secara ilmiah maupun etis. Keduanya adalah dua sisi mata uang yang saling melengkapi, sebagaimana ditegaskan pada slide sebelumnya bahwa pertemuan 13 dan 14 membentuk satu kesatuan logis.

Pemahaman terhadap poin-poin ini akan langsung Anda terapkan pada sesi review progress penelitian minggu depan. Ketika Anda menyiapkan materi untuk slide berikutnya, pastikan Anda tidak hanya menyajikan output statistik atau tema kualitatif, tetapi juga secara kritis mengidentifikasi potensi ancaman validitas, langkah mitigasi bias, serta kepatuhan terhadap prinsip etika selama proses pengumpulan dan analisis data berlangsung.

---

## Slide 035 - Research Progress: Data Analysis dan Preliminary Findings

### Narasi

Slide ini mengatur format dan prinsip penyampaian *research progress* khusus mengenai analisis data dan temuan awal (*preliminary findings*), sebagaimana diwajibkan dalam RPS. Setiap mahasiswa atau kelompok wajib melaporkan perkembangan analisis data pada minggu ini. Laporan ini berfungsi sebagai titik kontrol akademis untuk memastikan bahwa proses penelitian berjalan sesuai jalur metodologis yang telah direncanakan.

Struktur laporan yang disarankan terdiri dari enam komponen inti:
- **Dataset status**: cantumkan jumlah partisipan awal, jumlah data yang dinyatakan valid, serta data yang dikeluarkan beserta alasan metodologisnya.
- **Analisis yang dilakukan**: jabarkan uji statistik atau teknik analisis kualitatif yang digunakan, lengkap dengan justifikasi mengapa metode tersebut paling relevan untuk menjawab pertanyaan penelitian.
- **Preliminary findings**: sampaikan hasil awal yang mulai terbentuk. Tekankan bahwa ini masih bersifat provisional dan belum final.
- **Kendala**: identifikasi hambatan teknis dalam pemrosesan data, keterbatasan sampel, atau temuan yang muncul di luar ekspektasi.
- **Keputusan**: nyatakan apakah ada penyesuaian arah analisis berdasarkan kendala atau indikasi awal yang teramati.
- **Next action**: rencanakan langkah konkret berikutnya, seperti menjalankan analisis lanjutan, meminta pendampingan dosen, atau menyiapkan instrumen validasi tambahan.

Prinsip utama presentasi progress ini adalah transparansi dan interpretasi aktif. Hindari kebiasaan hanya memaparkan output statistik, grafik, atau kodek transkripsi tanpa konteks. Dosen dan rekan diskusi membutuhkan pemahaman tentang apa yang sebenarnya telah Anda analisis, masalah apa yang dihadapi selama proses tersebut, serta strategi apa yang Anda usulkan untuk mengatasi hambatan itu. Pendekatan ini akan memudahkan pemberian umpan balik yang konstruktif dan tepat sasaran.

Sebagai jembatan dengan slide sebelumnya, pertemuan 14 akan membahas validitas internal, eksternal, konstruk, ekologis, serta isu reproduktibilitas dan etika penelitian. Pelaporan progress hari ini merupakan latihan praktis untuk memastikan bahwa setiap keputusan analitis yang Anda ambil memiliki landasan yang kuat, sehingga ketika kita memasuki pembahasan validitas, argumen Anda sudah siap dipertanggungjawabkan secara ilmiah.

Menyongsong pertemuan 15 tentang kontribusi ilmiah, alur logis penelitian Anda akan terus diperkuat. Hasil mentah (*result*) yang Andaolah hari ini akan bertransformasi menjadi *finding*, kemudian menjadi *evidence*, yang selanjutnya mendukung *claim* akademik, dan akhirnya menghasilkan kontribusi nyata bagi bidang HCI. Dengan menyusun laporan progress secara sistematis dan kritis sekarang, Anda sedang membangun fondasi empiris yang diperlukan untuk merumuskan kontribusi penelitian berkualitas tinggi di akhir semester.

---

## Slide 036 - Kaitan dengan Pertemuan 15: Dari Hasil ke Scientific Contribution

### Narasi

Setelah kita membahas format pelaporan progress pada slide sebelumnya, di mana Anda mencatat status dataset, teknik analisis yang dipilih, serta kendala teknis yang dihadapi, kini saatnya menggeser fokus dari sekadar pelaksanaan teknis menuju pemaknaan ilmiah. Analisis data bukanlah tujuan akhir, melainkan fondasi untuk membangun argumen penelitian yang berdampak.

Perhatikan alur konseptual yang menghubungkan Pertemuan 13 dengan Pertemuan 15. Proses dimulai dari pengolahan data mentah menjadi result, yang kemudian diinterpretasikan menjadi finding. Temuan ini harus diverifikasi sebagai evidence yang valid, sebelum akhirnya dirumuskan menjadi claim ilmiah. Claim inilah yang akan diolah lebih lanjut menjadi scientific contribution pada pertemuan mendatang. Alur ini menegaskan bahwa setiap transisi antar tahap memerlukan justifikasi metodologis yang ketat dan transparan.

Untuk mempersiapkan diri menuju sesi kontribusi ilmiah, mulailah berpikir strategis sejak fase analisis saat ini. Identifikasi finding utama yang paling konsisten muncul dari data Anda. Evaluasi apakah temuan tersebut cukup robust untuk menjawab research question secara meyakinkan, atau masih memerlukan analisis tambahan. Pertimbangkan juga siapa audiens utama yang akan mendapat manfaat: apakah desainer sistem, peneliti HCI lanjutan, atau pengguna akhir. Terakhir, renungkan arti temuan Anda terhadap perkembangan teori atau praktik desain interaktif.

Dalam konteks penelitian tingkat magister, kontribusi ilmiah tidak harus bersifat revolusioner. Terdapat empat bentuk kontribusi yang sangat dihargai dalam komunitas HCI:
1. **Empirical evidence**: penyediaan data kuantitatif atau kualitatif baru yang mengisi kesenjangan literatur yang ada.
2. **Design knowledge**: pemahaman mendalam mengenai mekanisme mengapa suatu teknik interaksi berhasil atau justru gagal diterapkan.
3. **Methodological insight**: pelajaran berharga tentang efektivitas atau keterbatasan penggunaan metode tertentu ketika diaplikasikan pada konteks spesifik.
4. **Implications for design**: rekomendasi praktis yang dapat langsung diadopsi oleh perancang sistem untuk meningkatkan kualitas interaksi.

Dengan menempatkan analisis data sebagai batu loncatan menuju kontribusi ilmiah, Anda telah menyiapkan landasan argumentasi yang kuat. Pada slide berikutnya, kita akan menutup pertemuan ini dengan ringkasan komprehensif atas seluruh konsep kunci Pertemuan 13, mencakup prinsip validitas statistik, strategi coding kualitatif, serta pentingnya triangulasi dan visualisasi data yang bertanggung jawab.

---

## Slide 037 - Ringkasan Materi Pertemuan 13

### Narasi

Slide ini menyajikan rangkuman sistematis dari seluruh konsep kunci yang telah kita diskusikan dalam Pertemuan 13 mengenai analisis data dan pembentukan bukti dalam penelitian HCI. Mari kita telusuri kembali alur logika penelitian yang menjadi tulang punggung sesi ini.

Alur evidence berjalan secara linear dan kumulatif: data mentah diproses menjadi result, diinterpretasikan menjadi finding, dikonsolidasikan menjadi evidence, dan akhirnya digunakan untuk menopang claim ilmiah. Setiap transisi dalam alur ini memerlukan transparansi metodologis agar temuan Anda dapat diaudit dan direplikasi oleh peneliti lain.

Dalam praktik pembersihan data, dokumentasi setiap keputusan filtering atau transformasi adalah kewajiban mutlak. Menghilangkan titik data tanpa justifikasi yang tercatat dapat mengancam validitas internal dan menimbulkan bias seleksi. Pemilihan statistik deskriptif juga harus responsif terhadap karakteristik data. Mean dan standar deviasi ideal untuk distribusi simetris, sedangkan median dan IQR lebih tahan terhadap outlier pada data yang mengalami skewness.

Ketika memasuki tahap inferensi, p-value semata tidak lagi memadai untuk standar publikasi tingkat magister. Laporan penelitian harus menyertakan effect size dan confidence interval guna menunjukkan besaran dampak praktis dan presisi estimasi. Pemilihan uji statistik komparatif pun harus selaras dengan desain eksperimen between-subjects atau within-subjects, serta memenuhi asumsi normalitas dan homoskedastisitas yang relevan.

Untuk pendekatan kualitatif, rigoritas dicapai melalui proses coding iteratif, pengembangan codebook yang terstruktur, thematic analysis yang koheren, serta pengujian inter-rater agreement untuk memastikan reliabilitas kode. Triangulasi lintas sumber, metode, atau peneliti akan semakin mengunci konsistensi evidence Anda. Visualisasi data harus menghindari manipulasi skala atau pemotongan sumbu, serta selalu menyertakan indikator sebaran dan ketidakpastian seperti error bars atau interval kredibel.

Prinsip penutup yang perlu Anda pegang erat adalah bahwa signifikansi statistik hanyalah pintu masuk, bukan tujuan akhir. Signifikansi ilmiah sesungguhnya dibangun dari effect size yang bermakna secara kontekstual, replikasi hasil yang konsisten, penolakan terhadap penjelasan alternatif melalui kontrol variabel yang ketat, serta keterkaitan temuan dengan kebutuhan komunitas peneliti maupun praktisi desain interaktif.

Rangkuman ini merupakan jembatan langsung menuju diskusi di slide 36, di mana kita mulai mengkonversi evidence yang telah diverifikasi menjadi scientific contribution. Dengan menguasai prinsip-prinsip analisis ini, Anda telah memiliki fondasi kokoh untuk merumuskan claim yang tajam sebelum melangkah ke tahap perumusan kontribusi ilmiah.

Di slide berikutnya, kita akan menutup pertemuan ini dan menyiapkan mental serta metodologis untuk topik Pertemuan 15 mengenai validitas, reproduktibilitas, dan etika penelitian. Penguatan terhadap standar analisis hari ini akan menjadi landasan kritis ketika kita membahas bagaimana menjaga integritas data, transparansi prosedur, dan tanggung jawab akademik di tahap penelitian selanjutnya.

---

## Slide 038 - Penutup

### Narasi

Kita telah menyelesaikan rangkaian pembahasan mengenai analisis data dan penyusunan bukti dalam penelitian Human-Computer Interaction. Sesi ini menyoroti alur kritis dari data mentah menuju klaim ilmiah, menekankan bahwa setiap keputusan pembersihan data harus didokumentasikan secara transparan, pemilihan statistik deskriptif disesuaikan dengan karakteristik distribusi, dan uji inferensial tidak boleh bergantung semata pada nilai-p.

Signifikansi statistik hanyalah langkah pertama. Dalam penelitian tingkat magister, kekuatan bukti justru ditentukan oleh besaran efek yang substantif, konsistensi temuan, eliminasi penjelasan alternatif, serta keterkaitan langsung dengan masalah desain interaksi. Penggunaan triangulasi sumber data dan visualisasi yang menyajikan sebaran serta interval kepercayaan merupakan praktik wajib untuk menghindari interpretasi yang bias atau menyesatkan.

Penutupan pertemuan ke-13 ini menandai transisi dari tahap pengumpulan dan pengolahan data menuju evaluasi ketat terhadap kualitas penelitian itu sendiri. Pertemuan berikutnya akan membahas topik Validity, Reproducibility & Research Ethics. Pembahasan ini akan mengupas bagaimana merancang instrumen dan prosedur yang benar-benar mengukur konstruk yang dimaksud, standar yang diperlukan agar sebuah user study dapat direplikasi secara independen, serta kerangka etika yang melindungi partisipan dan menjaga integritas akademik.

Terima kasih atas kontribusi dan diskusi yang sangat produktif sepanjang sesi hari ini. Mohon persiapkan diri Anda untuk mendalami literatur tentang krisis replikasi dalam ilmu perilaku terapan dan pedoman etika penelitian HCI kontemporer, karena kita akan langsung menerapkannya dalam konteks perancangan eksperimen dan critical review paper di kelas berikutnya.
