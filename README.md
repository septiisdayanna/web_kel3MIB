
Spesifikasi Kebutuhan Perangkat
Lunak
Untuk
Website HIJABISTA INSIGHTS
Hijab Fashion and Hijab Consultation
Versi 1.0 disetujui
Disusun Oleh:
Septi Isdayanna	(22091397045)
Resti Divana Putri	(22091397060)
Eva Fitria Novianti Putri	(22091397068)
D4 Manajemen Informatika
Fakultas Vokasi
Universitas Negeri Surabaya Tahun 2023
Daftar Isi
1. Pendahuluan	2
1.1 Tujuan Penulisan Dokumen	2

1.2	Konvensi Dokumen	1
	1.3	Audien yang Dituju dan Pembaca yang Disarankan	2
	1.4	Lingkup Produk	2
	1.5	Referensi	3
Deskripsi Keseluruhan										4
Perspektif Produk										4
Fungsi Produk											4
Kelas dan Karakteristik Pengguna								4
Lingkungan Operasi										5
Kendala Desain dan Implementasi								5
Dokumentasi Pengguna										5
Asumsi dan Ketergantungan									8
Kebutuhan Antarmuka Eksternal								9
Antarmuka Pengguna										9
Antarmuka Perangkat Keras									10
Antarmuka Perangkat Lunak									10
Antarmuka Komunikasi										11
Fitur Sistem dan Kerangka Desain Fitur							12
Halaman Daftar											12
Halaman Login											13
Halaman Beranda										14
Halaman Drop Off										15
Halaman Pick Up										16
Halaman Reedem										17
Halaman Riwayat Penukaran									18
Halaman Pesan											19
Halaman Profil	20
Persyaratan Nonfungsional Lainnya	21
Persyaratan Kinerja	21
Persyaratan Keselamatan	21
Persyaratan Keamanan	22
Atribut Kualitas Perangkat Lunak	22
Atribut Bisnis	23
Persyaratan Lainnya	24
Lampiran A: Glosarium	24
Lampiran B: Analisa Model	25
Lampiran C: Daftar yang akan ditentukan	28










1.	Pendahuluan
1.1	Tujuan Penulisan Dokumen
Dokumen Spesifikasi Kebutuhan Perangkat Lunak (SKPL) ini bertujuan sebagai panduan atau acuan baik bagi pengembang sistem maupun pengguna. Bagi pihak pengembang, dokumen ini berperan sebagai pedoman dasar yang membantu dalam perencanaan dan pelaksanaan aktivitas pengujian sistem, serta memberikan arahan untuk melakukan perbaikan dan perubahan pada sistem guna memenuhi kebutuhan pengguna dan tujuan dari website itu sendiri. Sedangkan bagi pihak pengguna, dokumen ini digunakan untuk mencatat semua spesifikasi kebutuhan dari website yang dikembangkan dan harapan yang diinginkan. Dokumen ini disusun dengan tujuan untuk mendukung proses pembuatan spesifikasi sistem informasi yang berkaitan dengan rekomendasi model, warna, dan bentuk hijab yang sesuai dengan karakteristik pengguna. Pada prinsipnya, hasil analisis sistem informasi dengan rancangan ini, diuraikan sebagai sekumpulan proses yang terorganisasi secara hierarkis memberikan solusi dan menetapkan batasan masalah agar proyek tidak menyimpang terlalu jauh dari tujuan awal atau manfaat dari website yang akan dibangun.
1.2	Konvensi Dokumen
Standar penulisan dokumen ini disesuaikan dengan template yang diberikan. Pada dokumen ini terdapat beberapa kata yang dicetak miring digunakan untuk menunjukan bahwa kata tersebut berasal dari bahasa asing, sedangkan penulisan dengan cetak tebal sebagai petunjuk memasuki bab atau sub bab baru dan tidak ada format khusus untuk menandai bagian terpenting dokumen.

1.3	Audiens yang Dituju dan Pembaca yang Disarankan
Audiens: Audiens yang dituju dari website ini adalah para wanita Muslim yang menggunakan hijab atau berencana untuk memulai mengenakan hijab. Wanita yang berminat dalam fashion dan hijab. Menyesuaikan hijab dari bentuk wajah dan warna kulit dan sebagai platform secara online untuk keperluan fashion. Beberapa dari mereka memiliki berbagai latar belakang dan tingkat pengalaman dalam memilih hijab.
Saran: Dokumen SKPL Website Hijabista Insights - Hijab Fashion and Hijab Consultation ini digunakan untuk menyediakan rekomendasi hijab yang cocok berdasarkan bentuk wajah dan warna kulit pengguna. Oleh karena itu, kami menyarankan kepada pembaca untuk membaca dokumen SKPL ini dengan seksama terlebih dahulu.
1.4	Lingkup Produk
Website ini berfungsi sebagai sebuah platform yang menyediakan berbagai rekomendasi mengenai hijab, termasuk model, warna, dan jenis bahan yang dapat disesuaikan dengan kebutuhan penggunanya. Untuk mencapai hal ini, website ini harus memiliki kemampuan untuk menampilkan berbagai kemungkinan pilihan bentuk wajah dan warna kulit, sehingga pengguna dapat menyesuaikan pilihan hijab sesuai dengan bentuk wajah dan warna kulit mereka. Dengan begitu, website ini dapat memberikan beberapa rekomendasi mengenai model dan warna hijab yang sesuai dengan preferensi pengguna. Selain itu, website ini juga harus mampu mengumpulkan data dari pengguna, dimana pengguna dapat memberikan informasi mengenai penggunaan hijab dalam kehidupan sehari-hari mereka. Hal ini akan memungkinkan website untuk memberikan rekomendasi mengenai jenis bahan hijab yang cocok untuk digunakan oleh pengguna tersebut. Setelah pengguna mendapatkan model, warna, dan bahan hijab yang sesuai, website ini juga harus mampu menampilkan rekomendasi beberapa toko online yang menjual hijab tersebut dengan berbagai macam harga. Hal ini bertujuan agar pengguna dapat membeli hijab tersebut dengan mudah. 
1.5	Referensi 
Dokumen-dokumen yang digunakan sebagai referensi dalam pembuatan SKPL ini adalah sebagai berikut:
[1]	“Spesifikasi Kebutuhan Perangkat Lunak Sistem Informasi Mahasiswa Berprestasi Universitas Palangka Raya.” [Online]. Available: https://www.researchgate.net/publication/365977478
[2]	“SPESIFIKASI KEBUTUHAN PERANGKAT LUNAK.”
[3]	H. Widyastuti, J. Siregar, and R. Ishak, “RANCANG BANGUN SISTEM INFORMASI PENJUALAN BAJU BERBASIS WEB,” 2020.
[4]	A. Oktavianti, W. Sugeng, and A. Agusta, “Implementasi Aplikasi Hijab Berbasis Android dengan Metode Canny Operator dan Template Matching Correlation”, [Online]. Available: http://myweb.lmu.edu/bjohnson/cmsi641web/week02-2.html
[5]	A. T. M. Anjungan, T. Mandiri, and M. Kuliah, “SPESIFIKASI KEBUTUHAN PERANGKAT LUNAK ATM (Anjungan Tunai Mandiri) BANK-XXX,” pp. 1–24.
2.	Deskripsi Keseluruhan
2.1	Perspektif Produk
Hijabista Insights: Hijab Fashion and Hijab Consultation" adalah platform interaktif yang dirancang untuk memberikan rekomendasi hijab yang sesuai dengan bentuk wajah dan warna  kulit dari pengguna dan juga memberikan rekomendasi bahan hijab yang sesuai dengan keseharian pengguna. Dengan desain dan isi yang menarik dan informatif, website ini digunakan untuk menyediakan rekomendasi hijab yang cocok berdasarkan bentuk wajah dan warna kulit pengguna, memfasilitasi pengguna untuk memilih bahan hijab sesuai dengan keperluan (sehari-hari atau acara khusus), serta mengarahkan pengguna ke toko online yang menjual hijab dengan pilihan harga berbeda.
2.2	Fungsi Produk
Website Hijab insights memiliki beragam fungsi yang bermanfaat, khususnya bagi para wanita yang memakai hijab dikesehariannya. Berikut adalah beberapa fungsi utama dari website ini:
Website ini memberikan rekomendasi berbagai model hijab kepada pengguna. Ini akan membantu pengguna dalam memilih model hijab yang sesuai dengan preferensi mereka.
Selain model, website ini juga memberikan rekomendasi berbagai warna hijab yang dapat disesuaikan dengan kebutuhan pengguna. Pengguna dapat memilih warna hijab yang cocok dengan warna kulit mereka atau sesuai dengan acara tertentu.
Website ini memberikan rekomendasi mengenai bahan hijab yang sesuai dengan kebutuhan pengguna. Bahan hijab dapat beragam, seperti katun, satin, sutra, dll. Rekomendasi ini membantu pengguna dalam memilih bahan hijab yang nyaman dan sesuai dengan keperluan mereka.
website ini memberikan beberapa rekomendasi toko online yang menyediakan produk hijab sesuai dengan hasil analisis sistem. Beberapa di antaranya termasuk Shopee, Tokopedia, Lazada, Bukalapak, dan lainnya.

Dengan fungsi-fungsi ini, website ini bertujuan untuk memberikan rekomendasi hijab yang lebih personal dan sesuai dengan preferensi serta kebutuhan pengguna.

2.3	Kelas dan Karakteristik Pengguna 
Analisis pengguna sistem dimaksudkan untuk mengetahui siapa saja aktor yang terlibat dalam menjalankan sistem. Sistem informasi aplikasi fasilitas umum ini sendiri menggunakan website. Pengguna sistem dibagi atas dua bagian, yaitu : 
1. Pengguna aplikasi fasilitas umum atau end user yaitu para pengguna website. Dalam menggunakan sistem ini, pengguna diharuskan memiliki koneksi GPRS / EDGE / UMTS / HSDPA dan fasilitas kamera untuk bisa menyesuaikan bentuk wajah mereka dengan hijab yang direkomendasikan. 
2. Admin sebagai pengelola konten secara keseluruhan memiliki fungsi- fungsi seperti menambah, mengubah dan menghapus konten informasi dalam menjalankan sistem. 

2.4	Lingkungan Operasi
Server Side
Perangkat yang kami gunakan adalah Windows sebagai Operating System (Sistem Operasi)
Client Side
Platform Pengguna
Platform ini dapat diakses melalui berbagai perangkat, termasuk komputer desktop, laptop, tablet, dan smartphone.
Browser yang Didukung
Platform akan dioptimalkan untuk berbagai browser populer termasuk Google Chrome, Mozilla Firefox, Safari, dan Microsoft Edge.
Development Tools
Perangkat yang digunakan untuk pengembangan sistem dan penyimpanan database adalah:
PhpMyAdmin sebagai sistem penyimpanan database Pengguna dan admin.
Bahasa pemrograman menggunakan PHP, JS, CSS, HTML.
Browser dan Development sebagai pengujian dan debug.
2.5	Kendala Desain dan Implementasi(belum)
Pengembangan sistem Hijab Insights ini memiliki keterbatasan-keterbatasan yaitu sebagai berikut:
Sistem yang dibangun belum terintegrasi secara utuh.
Keamanan website adalah hal yang penting. Pastikan untuk menginstal pembaruan keamanan secara berkala dan menggunakan alat keamanan yang sesuai untuk melindungi website dari serangan dan ancaman siber.
Sekalipun website telah dibangun, jika tidak dipromosikan dengan baik, mungkin akan kurang dikenal oleh masyarakat umum.

 2.6	Dokumentasi Pengguna
Berikut panduan penggunaan aplikasi bagi pengguna tentang fitur-fitur penting pada aplikasi berbasis website Hijabista Insights: 
1. Pilih Bentuk Wajah dan Warna Kulit:
Platform akan menggunakan kamera untuk mengidentifikasi dan menganalisis bentuk wajah dan warna kulit pengguna. Informasi ini akan menjadi dasar untuk merekomendasikan hijab yang sesuai.
2. Model Hijab yang Cocok:
Berdasarkan hasil analisis wajah dan warna kulit, platform akan menggunakan algoritma rekomendasi untuk menyarankan model hijab yang paling cocok.
3. Konsultasi Pengguna:
Pengguna akan diminta untuk memberikan informasi mengenai penggunaan hijab, apakah untuk kegiatan sehari-hari atau acara khusus. Data ini akan memengaruhi rekomendasi bahan hijab.
4. Rekomendasi Toko Online:
Setelah konsultasi selesai, platform akan menampilkan berbagai toko online yang menyediakan produk hijab sesuai dengan hasil analisis. Beberapa di antaranya termasuk Shopee, Tokopedia, Lazada, Bukalapak, dan lainnya.
5. Perbandingan Harga:
Pengguna akan dapat membandingkan harga produk hijab dari berbagai toko online, memungkinkan mereka untuk membuat pilihan berdasarkan preferensi dan anggaran mereka.
6. Pengalihan ke Aplikasi Toko:
Setelah pengguna memilih produk dan toko online, mereka akan dialihkan ke aplikasi toko terkait jika mereka ingin melakukan pembelian.
2.7	Asumsi dan Ketergantungan
Dalam pengembangan website Hijabista Insights - Hijab Fashion and Hijab Consultation, terdapat beberapa asumsi dan dependensi yang perlu dipertimbangkan. Asumsi dan Ketergantungan memberikan kerangka kerja untuk memahami kondisi dan ketergantungan yang mungkin mempengaruhi pengembangan dan operasionalisasi platform "Hijabista Insights". Memahami asumsi dan ketergantungan ini adalah kunci untuk mengelola risiko dan memastikan platform berfungsi sebagaimana mestinya.
Asumsi
1. Asumsi Umum
Pengguna memiliki akses internet stabil untuk mengakses platform.
2. Data Pengguna
Pengguna memberikan informasi yang akurat tentang bentuk wajah, warna kulit, dan preferensi pribadi untuk mendapatkan rekomendasi hijab yang akurat.
3. Keamanan Data
Tindakan keamanan yang memadai akan diimplementasikan untuk melindungi data pengguna dari akses tidak sah atau kebocoran.
4. Integrasi Toko Online
Pihak yang menyediakan API toko online memiliki sistem yang dapat diakses dan dokumentasi yang memadai untuk integrasi.
5. Ketersediaan Toko Online
Toko online yang diarahkan pengguna memiliki persediaan hijab yang mencukupi dan aktual.
6. Pembaruan dan Penyelenggaraan
Platform dapat diperbarui dan diselenggarakan tanpa gangguan signifikan terhadap pengguna.
Ketergantungan
1. Ketergantungan Eksternal
Platform mengandalkan API dari toko online mitra untuk menyediakan rekomendasi produk dan harga.
2. Pengembangan Bahasa Pemrograman
Ketersediaan sumber daya dan dukungan untuk bahasa pemrograman yang digunakan dalam pengembangan (PHP, HTML, CSS, JavaScript) harus dijamin.
3. Ketersediaan Server dan Hosting
Layanan hosting dan server harus stabil dan dapat diandalkan untuk menjalankan platform secara efisien.
4. Ketersediaan Database Management System
MySQL sebagai DBMS harus berfungsi dengan baik dan memenuhi kebutuhan platform.
5. Ketersediaan Teknologi Keamanan
Teknologi keamanan seperti SSL/TLS harus tersedia dan berfungsi dengan baik untuk melindungi data pengguna.
6. Integrasi Algoritma Rekomendasi
Algoritma rekomendasi harus dapat diintegrasikan dengan platform dan berjalan dengan akurat berdasarkan data pengguna.

3.	Kebutuhan Antarmuka Eksternal
3.1	Antarmuka Pengguna
Aplikasi ini  menggunakan antarmuka berbasis web, dan pengguna mengoperasikannya dengan menggunakan keyboard dan mouse di sistem operasi windows. Pengguna utama aplikasi ini adalah semua wanita yang memakai hijab, yang memiliki tingkat kemampuan bervariasi dalam menggunakan aplikasi tersebut. oleh karena itu, aplikasi ini dirancang dengan konsep desain yang ramah untuk pengguna. Aksesnya cukup mudah dan pengguna tidak akan kesulitan dalam berpindah halaman. Warna-warna yang digunakan dalam aplikasi ini dibuat dengan hangat sehingga nyaman bagi pengguna dalam pemilihan hijab. 

3.2	Antarmuka Perangkat Keras
Aplikasi ini dapat diakses dengan menggunakan beberapa perangkat keras seperti mouse sebagai pointer, keyboard sebagai tombol input, dan yang terpenting yaitu handphone atau laptop untuk mengakses aplikasi dengan terhubung ke internet. Kecepatan aplikasi berbasis website ini pada saat digunakan tergantung pada juga kecepatan internet yang digunakan dan kondisi perangkat. 

3.3	Antarmuka Perangkat Lunak
Aplikasi diakses menggunakan web browser.
Dikembangkan menggunakan bahasa pemrograman html, css, java script.
Database yang digunakan adalah mysql.
3.4	Antarmuka Komunikasi
website ini memerlukan perangkat berupa laptop, PC, atau smartphone yang terhubung ke jaringan internet. Aplikasi ini dapat dijalankan melalui web browser Google Chrome dan menggunakan formulir elektronik HTML untuk mengumpulkan data dari pengguna dengan batasan maksimal 1000 kata. Komunikasi data dalam proses pertukaran informasi antar perangkat yang terhubung dalam jaringan menggunakan protokol jaringan berbasis TCP/IP sebagai standar komunikasi jaringan.
Fitur Sistem dan Kerangka Desain Fitur
4.1 

Persyaratan Non Fungsional Lainnya
5.1	Persyaratan Kinerja
Persyaratan kinerja yang harus dipenuhi untuk memastikan performa dan responsivitas yang baik dari Website Hijab Insight, sebagai berikut:
Waktu Respon Halaman
Setiap halaman website harus dimuat dalam waktu maksimum 2 detik.
Waktu tunda saat menavigasi antar halaman dalam website harus kurang dari 1 detik.
Responsifitas Desain
- Website harus merespons dengan baik pada berbagai perangkat, termasuk desktop, tablet, dan ponsel.
Kecepatan Pencarian
 - Website harus menghasilkan hasil pencarian yang relevan dengan cepat.
Kecepatan Loading Gambar
- Gambar harus dikompres dengan baik untuk meminimalkan waktu pemuatan halaman.
Kapasitas Pengguna
Website harus mampu menangani jumlah pengguna yang berinteraksi secara bersamaan tanpa mengalami penurunan kinerja yang signifikan.
Kinerja pada jaringan lambat
Website harus dapat diakses dengan baik pada koneksi berkecepatan rendah tanpa mengorbankan kualitas konten.

5.2	Persyaratan Keselamatan
Website Hijabista Insights - Hijab Fashion and Hijab Consultation memberikan tindakan keamanan yang akan diimplementasikan. Keamanan data pengguna, transmisi, dan integrasi keamanan adalah prioritas utama. Perlindungan privasi dan ketersediaan layanan juga merupakan fokus penting. Pembaruan dan pemeliharaan keamanan secara teratur adalah bagian integral dari strategi keamanan keseluruhan. Dengan mengimplementasikan langkah-langkah ini, kami bertujuan untuk memberikan pengalaman pengguna yang aman dan terpercaya.
5.3	Persyaratan Keamanan
Persyaratan keamanan website hijab insights  sangat penting untuk melindungi data dari pengguna, mencegah ancaman siber, serta menjaga integritas dan ketersediaan website. Berikut adalah beberapa persyaratan keamanan yang perlu dipertimbangkan dalam pengembangan dan pengelolaan website tersebut:
Proteksi Data Pengguna
Website harus memiliki mekanisme enkripsi data (HTTPS) untuk melindungi data pribadi dan sensitif pengguna, seperti informasi penggunaan hijab untuk keseharian user yang seperti apa.
Manajemen Akses yang Tepat
Hanya pengguna yang sah dan berwenang yang harus memiliki akses ke bagian-bagian tertentu dari website, seperti data pribadi atau informasi penting lainnya.
Pemantauan Keamanan
Website harus memantau keamanan yang memungkinkan deteksi cepat terhadap aktivitas mencurigakan atau ancaman siber.
Pengelolaan Kata Sandi yang Kuat
Pengguna harus diharuskan menggunakan kata sandi yang kuat, dan website harus memiliki kebijakan perubahan kata sandi secara berkala.
Pembatasan akses
Sistem memberikan pembatasan akses berdasarkan peran atau hak pengguna, serta menggunakan token otentikasi yang aman. Sistem ini harus menyediakan tiga tingkat akses:
Tingkat operator sistem, yang memungkinkan akses tanpa batasan ke seluruh fungsionalitas sistem.
Tingkat pemberi posting, yang memberikan akses khusus kepada fungsionalitas pemberian posting.
Tingkat pengguna, yang memberikan akses untuk melihat dan menggunakan informasi yang ada."



5.4	Atribut Kualitas Perangkat Lunak
Berikut adalah contoh atribut kualitas perangkat lunak dalam konteks sebuah website Hijabista Insights:
Keandalan 
Aplikasi harus memberikan hasil yang akurat dan dapat diandalkan dalam menampilkan pilihan bentuk wajah dan warna kulit, dan informasi lainnya kepada pengguna. 
Ketersediaan
Website harus tersedia selama minimal 99,9% waktu dalam setahun, kecuali untuk pemeliharaan yang dijadwalkan.
Kemampuan pemulihan cepat (failover) harus ada jika terjadi gangguan pada server atau jaringan.
Scalability
- Website harus mampu menangani lonjakan lalu lintas pengguna tanpa mengalami penurunan drastis dalam kinerja.
- Kemampuan skalabilitas harus diuji hingga minimal 1000 pengguna bersamaan tanpa mengurangi performa.
Kinerja
Website memiliki waktu muat halaman yang cepat sehingga pengguna tidak mengalami penundaan saat mengakses informasi atau rekomendasi hijab.
Usability
Antarmuka pengguna website dirancang dengan baik, dengan menu navigasi yang jelas dan instruksi yang mudah dipahami untuk memudahkan anggota menemukan informasi.
Keamanan 
Website harus mampu menangani serangan siber seperti DDoS dengan mengimplementasikan firewalls dan deteksi intrusi.
Semua data pengguna harus disandikan (encrypted) menggunakan protokol HTTPS.
Perlindungan terhadap serangan SQL Injection, Cross-Site Scripting (XSS), dan serangan umum lainnya harus ada.
5.5	Atribut Bisnis
Mengoptimalisasi Pengalaman Pengguna:
Platform bertujuan untuk memberikan pengalaman pengguna yang intuitif dan memuaskan dalam memilih hijab sesuai dengan preferensi dan karakteristik fisik pengguna.
Meningkatkan Keterlibatan Pengguna:
Melalui rekomendasi personalisasi dan interaksi yang mudah diikuti, platform bertujuan untuk meningkatkan keterlibatan pengguna dan mempertahankan pengguna aktif.
3. Memfasilitasi Keputusan Pembelian:
Dengan memberikan rekomendasi model hijab dan perbandingan harga dari berbagai toko online, platform membantu pengguna dalam mengambil keputusan pembelian yang cerdas.
4. Kolaborasi dengan Toko Online:
Platform berusaha untuk memperluas jangkauan dan mendukung industri hijab dengan mengarahkan pengguna ke toko online mitra.
II. Metrik Kinerja Utama
1. Peningkatan Pengguna Aktif:
Tujuan untuk meningkatkan jumlah dan tingkat keterlibatan pengguna aktif setiap bulannya.
2. Konversi ke Transaksi Pembelian:
Memonitor tingkat konversi dari pengguna yang menggunakan platform menjadi pembeli aktif di toko online mitra.
3. Tingkat Kepuasan Pengguna:
Melakukan survei kepuasan pengguna untuk memantau tingkat kepuasan dan menerima umpan balik untuk perbaikan.
4. Waktu Respons Server:
Memantau dan memastikan bahwa platform memberikan waktu respons yang cepat untuk mempertahankan pengalaman pengguna yang mulus.
III. Model Bisnis
1. Kerjasama dengan Toko Online:
Platform dapat memperoleh pendapatan dari kemitraan dengan toko online melalui program afiliasi atau model pembagian keuntungan.
2. Berbasis Iklan:
Menyediakan ruang iklan untuk merek hijab atau produk terkait di platform.
6.	Persyaratan Lainnya
User : 


Lampiran B: Analisa Model
Flowchart

Entity Relationship Diagram

Use Case

CDM dan PDM


