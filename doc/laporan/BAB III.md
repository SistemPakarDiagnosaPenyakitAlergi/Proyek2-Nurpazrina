**BAB III
ANALISIS DAN PERANCANGAN**

1.  **Analisis Sistem (Proses Bisnis)**

Analisis merupakan penelaahan atau penelitian dengan melakukan suatu percobaan yang menghasilkan kesimpulan dari penguraian suatu sistem informasi yang utuh kedalam bagian–bagian komponennya dengan maksud untuk mengidentifikasi dan mengevaluasi segala permasalahan yang timbul, hambatan yang terjadi serta kemampuan dan kebutuhan yang diharapkan sehingga dapat diusulkan perbaikan–perbaikan yang dapat membangan dan mempertinggi sistem yang dibuat ini.

Sebelum merancang sebuah aplikasi yang akan dibangun, factor yang harus diperhatikan yaitu adalah tahap analisis. Namun sebelum kita melakukan analisis kita harus memilih domain masalah akuisisi pengetahuan. Pada aplikasi sistem pakar ini menggunakan metode forward chaining. Dari masalah yang timbul kita harus mengetahui pengetahuan apa saja yang ada pada sistem pakar tersebut. Dalam aplikasi ini kami menggunakan metode forward chaining pada bagian interaksi antara user. Antar muka adalah perangkat lunak yang menyediakan media komnikasi antara pengguna dengan system. Dalam metode forward chaining yaitu teknik pencarian yang dimulai dengan fakta yang diketahui kemudian mencocokan fakta-fakta tesebut dengan bagian IF dari rules IF – THEN. Bila ada fakta yang cocok dengan bagian IF, maka rule dieksekusi, maka sebuah fakta baru (bagian THEN) ditambahkan kedalam database. Interaksi user ini hanya menyediakan media komunikasi antara pengguna dengan system. Data bagian pengetahuan tentang sistem pakar itu diambil dari database. Fakta, situasi masalah dan teori yang terkait. Heuristik khusus atau rules, yang langsung menggunakan pengetahuan untuk menyelesaikan masalah khusus. Pengetahuan ini dapat berasal dari pakar, jurnal, majalah, dan sumber pengetahuan lain.

Mekanisme Inferensi Merupakan perangkat lunak yang melakukan penalaran dengan menggunakan pengetahuan yang ada untuk menghasilkan suatu kesimpulan atau hasil akhir. Dalam komponen ini di lakukan pemodelan proses berfikir manusia. Pendefinisian struktur pengendalian data terletak pada fasilitas penjelasan Fasilitas penjelasan berguna dalam memberikan penjelasan kepada pengguna mengapa computer meminta suatu informasi tertentu dari pengguna dan dasar apa yang di gunakan computer sehingga dapat menyimpulkan suatu kondisi.

Ada 4 Tipe penjelasan yang digunakan dalam system pakar:

1. Penjelasan mengenai jejak aturan yang menunjukan status konsultasi

2. Penjelasan mengenai bagaimana sebuah keputusan di peroleh

3. penjelasan mengapa system menanyakan suatu pertanyaan

4. penjelasan mengapa system tidak memberikan keputusan seperti yang dikehendaki pengguna.

Lalu orang yang terlibat Untuk memahami perancangan system pakar, perlu di pahami mengenai siapa saja yang berinteraksi dengan system. Mereka adalah:

a. Pakar (domain expert): seorang ahli yang dapat menyelesaikan masalah yang sedang di usahakan untuk dipecahkan oleh system

b. Pembangun Pengetahuan (knowledge engineer) : seseorang yang menerjemahkan pengetahuan seorang pakar dalam bentuk deklaratif sehingga dapat digunakan oleh system pakar.

c. Pengguna (user) : seseorang yang berkonsultasi dengan system untuk mendapatkan saran yang di sediakan oleh pakar

d. Pembangun Sistem (System Engineer) : seseorang yang membuat antarmuka pengguna, merancang bentuk basis pengetahuan secara deklaratif dan mengimplementasikan mesin inferensi

Lalu berikutnya adalah tahap analisis. Tahap analisis merupakan tahap pemahaman kebutuhan fungsional, skenario alir proses dan kamus data. Tahap analisis bertujuan untuk mengetahui mekanisme sistem, proses–proses yang terlihat dalam sistem serta hubungan antar proses tersebut, sehingga akan membantu para pemakai informasi dalam mengidentifikasi informasi yang diperlukan oleh pemakai untuk melakukan pekerjaannya.

1.  **Analisis Sistem yang sedang Berjalan (*Current System*)**

Diagnosa Penyakit sangat dibutuhkan oleh pasien yang mengalami gejala penyakit untuk mengetahui penyakit yang diderita. Sistem yang berjalan terdiri dari beberapa prosedur yaitu datang kerumah sakit daftar ke petugas untuk mengambil antrian lalu menemui dokter ahli untuk konsultasi mengenai penyakit yang sedang diderita.

1.  **Analisis Prosedur/*Flow Map* yang Berjalan**

<!-- -->

1.  **Analisis Sistem Yang Sedang Berjalan Pada Pendaftaran Pasien**

*Gambar 3. 1 Flowmap Yang Sedang Berjalan Pada Pendaftaran Pasien*

Keterangan:

A1: Arsip data pasien

Skenario flowmap diagnosa penyakit alergi makanan pada manusia yang sedang berjalan:

1.  Pasien datang ke rumah sakit

2.  Pasien mendaftar dan mengambil no antrian

3.  Petugas Mendaftarkan Pasien

4.  Petugas menuli data pasien yang ingin mendaftar

5.  Petugas mengecek status pasien apa bisa untuk diperiksa atau tidak

6.  Jika sudah terdaftar maka Petugas akan memasukan data pasien jika tidak terdaftar petugas akan menuliskan kembali data pasien yang lengkap

7.  Petugas menulis data pasien yang lengkap lalu dimsukan kedalam laporan data pasien

8.  Petugas memberikan no antrian

9.  Pasien Menunggu antrian untuk dipanggil.

<!-- -->

1.  **Analisi Yang Sedang Berjalan Pada Diagnosa**

*Gambar 3.2 Flowmap Yang Sedang Berjalan Pada Diagnosa Pasien*

Keterangan:

A2: Arsip data diagnosa pasien

Skenario flowmap diagnosa penyakit alergi makanan pada manusia yang sedang berjalan:

1.  Dokter Memanggil Pasien

2.  Dokter menanyakan keluhan yang diderita pasien

3.  Dokter memeriksa Pasien

4.  Dokter mencatat keluhan pasien dan data tersebut akan masuk kedalam laporan data diagnosa pasien

5.  Dokter melanjutkan memeriksa pasien dan memberikan solusinya

6.  Dokter membuatkan resep

7.  Dokter memberikan resep kepada pasien

8.  Pasien menerima resep obat.

<!-- -->

1.  **Analisis Yang Sedang Berjalan Pada Laporan**

*Gambar 3.3 Flowmap Yang Sedang Berjalan Pada Laporan*

Keterangan:

A1: Arsip Data Pasien

A2: Arsip Data Diagnosa Pasien

Skenario flowmap diagnosa penyakit alergi makanan pada manusia yang sedang berjalan:

1.  Semua arsip disatukan

2.  Pengumpulan Semua Data

3.  Rekap Data Laporan

4.  Data laporan data pasien dan diagnosa pasien
