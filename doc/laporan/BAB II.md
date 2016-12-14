**BAB II**

**LANDASAN TEORI**

1.  **Sistem**

Sistem adalah suatu kesatuan usaha yang terdiri dari bagian-bagian yng berkaitan satu sama lain yang berusaha mencapai suatu tujuan dalam suatu lingkungan kompleks. Pengertian tersebut mencerminkan intedependen satu sama lain. Selain itu dapat dilihat bahwa sistem berusaha mencapai tujuan. Pencapaian tujuan ini menyebabkan timbulnya dinamika perubahan-perubahan yang terus menerus menunjukan bahwa sistem sebagai gugus dari elemen-elemen yang saling berinteraksi secara teratur dalam rangka mencapai tujuan atau sub tujuan. (Prof. Dr. Ir marimin Msc, 2006) \[1\].

1.  **Pakar**

Pakar adalah orang yang mempunyai keahlian dalam bidang tertentu, yaitu pakar yang mempunyai knowledge atau kemapuan khusus yang tidak setiap orang mengetahui atau mampu dalam bidang yang dimilikinya (muhammad arhami, 2005) \[1\].

1.  **Sistem Pakar**

Sistem pakar adalah sistem yang berusaha mengadopsi pengetahuan manusia ke komputer, agar dapat menyelesaikan masalah seperti yang bias dilakukan oleh para ahli. Sistem pakar yang baik dirancang agar dapat menyelesaikan suatu permasalahan tertentu dengan meniru kerja dari para ahli \[2\].

1.  **Struktur Sistem Pakar**

    Didalam Struktur sistem pakar terdapat dua bagian utama, yaitu lingkungan pengembangan (*development environment)* dan lingkungan konsultasi (*consultation environment).* Lingkungan pengembangan yang berisikan komponen-komponen yang digunakan pembuat sistem pakar dan digunakan pembuat sistem pakar dan digunakan untuk memperkenalkan pengetahuan pakar ke dalam *knowledge base (*basis pengetahuan), sedangkan lingkungan konsultasi berisikan komponen yang akan digunakan pengguna atau *user* untuk berkonsultasi sehingga pengguna mendapatkan pengetahuan dan nasihat sistem pakar layaknya dengan seorang pakar.

|     |
|-----|

1.  **Knowledge Base**

*Knowledge Base* berisi informasi-informasi atau pengetahuan yang diberikan oleh pakar dan diimplementasikan ke dalam sistem computer dengan menggunakan metode representasi tertentu. Metode representasi pengetahuan adalah cara untuk menstrukturkan pengetahuan yang dimiliki oleh pakar agar mudah diolah oleh computer. Pengetahuan tersebut merupakan bahan dasar dari sebuah sistem pakar karena keahlian pakar disimpan didalamnya. Informasi atau fakta yang dimasukkan oleh user selama berkonsultasi akan dicocokkan oleh mesin pengambil keputusan dengan pengetahuan yang terdapat dalam basis pengetahuan. Basis pengetahuan itu tidak statis, maka memerlukan modifikasi dan perbaikan sejalan dengan perubahan kondisi dalam problem domain \[3\].

1.  **Aplikasi **

Aplikasi adalah suatu program yang siap untuk digunakan yang dibuat untuk melaksanakan suatu fungsi bagi pengguna jasa aplikasi serta pengguna aplikasi lain yang dapat digunakan oleh suatu sasaran yang akan dituju \[4\].

1.  **Framework**

Framework adalah kerangka kerja yang terdiri dari sekumpulan prosedur, fungsi, class, dan library yang talah disusun secara terstruktur untuk memudahkan dan mempercepat pekerjaan programmer untuk membangun sebuah website ataupun aplikasi berbasis website tanpa melakukan coding dari awal \[5\].

1.  **CodeIgniter**

CodeIgniter adalah sebuah framework php opensource dengan menggunkan konsep MVC (Model, View, Controller) untuk membangun website dinamis atau aplikasi berbasis web. CodeIgniter ini dikembangkan oleh Rick Ellis yang di rilis pertama kali pada tanggal 28 Februari 2006. Seiring berjalan waktu framework CodeIgniter berkembang pesat karena sangat friendly bagi para programmer web. Hingga saat ini versi terakhir dari framework yang satu ini adalah CodeIgniter 3.0 yang resmi di rilis pada tanggal 30 Maret 2015 \[5\].

1.  **Basis Data**

Basis data adalah adalah kumpulan data yang disimpan secara sistematis di dalam komputer yang dapat diolah atau dimanipulasi menggunakan perangkat lunak (program aplikasi) untuk menghasilkan informasi. Pendefinisian basis data meliputi spesifikasi berupa tipe data, struktur data dan juga batasan-batasan data yang akan disimpan. Basis data merupakan aspek yang sangat penting dalam sistem informasi dimana basis data merupakan gudang penyimpanan data yang akan diolah lebih lanjut. Basis data menjadi penting karena dapat mengorganisasi data, menghidari duplikasi data, hubungan antar data yang tidak jelas dan juga update yang rumit \[6\].

1.  **MySQL**

MySQL merupakan sebuah perangkat lunak atau software sistem manajemen basis data SQL atau DBMS Multithread dan multi user. MySQl sebenarnya merupakan turunan dari salah satu konsep utama dalam database untuk pemilihan atau seleksi dan pemasukan data yang memungkinkan pengoperasian data dikerjakan secara mudah dan otomatis. MySQL diciptakan oleh Michael "Monty" Widenius pada tahun 1979, seorang programmer komputer asal Swedia yang mengembangkan sebuah sistem database sederhana yang dinamakan UNIREG yang menggunakan koneksi low-level ISAM database engine dengan indexing \[7\].

1.  **Kecerdasan Buatan**

Kecerdasan buatan (*Artificial Intelligece*) adalah “ide-ide untuk membuat suatu perangkat lunak computer yang memiliki kecerdasan sehingga perangkat lunak computer tersebut dapat melakukan suatu pekerjaan yang dilakukan oleh manusia” (Artanti, 2004), dengan kata lain membuat sebuah computer dapat berpikir dan bernalar seperti manusia. Tujuan dari kecerdasan buatan ini adalah membuat computer lebih cerdas, mengerti tentang kecerdasan, dan membuat mesin lebih berguna bagi manusia. Kecerdasan buatan dapat membantu meringankan beban kerja manusia misalnya dalam membuat keputusan, mencari informasi secara lebiha akurat, atau membuat computer lebih mudah digunakan dengan tampilan yang mudah dipahami. Cara kerja kecerdasan buatan adalah menerima input, untuk kemudian diproses dan kemudian mengeluarkan output yang berupa suatu keputusan\[8\].

1.  **Metode Forward Chaining**

    <img src="./media/image2.jpeg" width="410" height="215" />

    *Forward Chaining* adalah teknik pencarian yang dimulai dengan fakta yang diketahui, kemudian mencocokan fakta-fakta tersebut dengan bagian IF dari rules IF – THEN. Bila ada fakta yang cocok dengan bagian IF, maka rule dieksekusi, maka sebuah fakta baru (bagian THEN) ditambahkan ke dalam database.

    Langkah-langkah dalam membuat sistem pakar dengan menggunakan metode *forward chaining* yaitu:

<!-- -->

1.  Pendeskripsian masalah dimulai dengan pemilihan dengan pemilihan domain masalah akuisi pengetahuan.

2.  Pendefinisian data input untuk memulai inferensi karena diperlukan oleh sistem *forward chaining.*

3.  Pendefinisian struktur pengendalian data untuk membantu mengendalikan pengaktifan suatu aturan

4.  Perancanan antarmuka dengan basis pengetahuan

5.  Pengembangan sistem

6.  Evaluasi sistem
