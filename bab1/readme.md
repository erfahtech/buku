# BAB 1

## Internet of Things

Internet of Things atau IoT merupakan jaringan perangkat yang saling terhubung melalui internet dan didalam prosesnya terjadi pertukaran data antara perangkat dengan cloud atau antar perangkat IoT. Dalam sistem IoT terdapat beberapa komponen utama yaitu Perangkat IoT, IoT gateway, dan backend IoT. 

Perangkat IoT umumnya dilengkapi dengan sensor yang mampu mengubah jaringan pasif menjadi aktif yang bebas diintegrasikan dengan perangakat lain. Sensor juga menjadi pengumpul data dari lingkungan atau pengguna, sensor dapat mengenali temperatur, suara, sentuhan dan lainya lalu mengirimkan data yang sudah dikumpulkan ke cloud data center dengan internet.
IoT gateway bertugas menghubungkan sensor dan perangkat melalui internet dengan cloud. Backend dalam IoT fungsi utamanya yaitu untuk memproses data dan menyimpan data.

Dalam IoT terdapat beberapa level layer mulai dari hardware sampai dengan end-user.
-	Hardware, beberapa komponen hardware seperti sensor, processor, Os, dan lainnya
-	Komunikasi, pada level ini mencakup link protocol (range dan bandwidth), network/transport protocol (IPv4 dan IPv6), dan session protocol (MQTT, FTP, SSH).
-	Sistem, meliputi backend, IoT platform sampai visualisasi.
-	User, dibagi menjadi 2 kategori yaitu konsumen dan bisnis, bagi user konsumen IoT digunakan sebagai sarana penunjang hidup sampai dengan penunjang kehidupan dan bisnis sebagai infrastruktur public sampai pelayanan Masyarakat.

## Sejarah Internet of Things

Internet of Things merupakan pengembangan ilmu pengoptimalan kehidupan dengan sensor dan perangkat pintar yang diperantarai oleh internet. Sejak dikenalnya internet pada tahun 1989 mulai banyak hal dilakukan melalui internet. John Romkey pada tahun 1990 menciptakan alat pemanggang roti yang dapat dinyala dan matikan melalui internet.

Pada tahun 1994 WearCam diciptakan oleh Steve Mann. Lalu pada tahun 1997 penjelasan singkat tentang sensor dan masa depan dikenalkan oleh Paul Saffo. Hingga tahun 1999 The Internet of Things diciptakan oleh Kevin Ashton, mereka juga menemukan perangkat berbasis RFID (Radio Frequency Identification) pada tahun yang sama. Penemuan tersebut menjadi batu loncatan dalam komersialisasi IoT.

Pada tahun 2000 LG memamerkan kulkas pintar pertama yang memberitahukan kepada pengguna berapa banyak isi didalam kulkas. Pada tahun 2005 artikel yang diterbitkan oleh publikasi utama seperti The Guardian, Amerika ilmiah dan Boston Globe banyak mengangkat tentang IoT. Pada tahun yang sama PBB juga menerbitkan laporan pertamanya mengenai Internet of Things sebagai salah satu potensi paling global dibidang teknologi. 

Perkembangan Internet of Things (IoT) dimulai pada tahun 2008 dengan persetujuan penggunaan "white space spectrum" oleh FCC. Peluncuran IPv6 di tahun 2011 semakin memicu pertumbuhan IoT, yang didukung oleh perusahaan-perusahaan besar seperti Cisco, IBM, dan Ericsson.

Salah satu contoh penerapan IoT adalah Fitbit Original Activity Tracker yang dirilis pada tahun 2009. Fitbit merupakan perangkat pelacak aktivitas yang pertama kali dapat mengumpulkan data tentang aktivitas fisik penggunanya. Perangkat ini menjadi pembuka jalan bagi smartwatch modern, yang kini menjadi salah satu produk IoT yang paling populer.

IoT memungkinkan kita untuk mengendalikan dan memantau peralatan di kehidupan sehari-hari. Hal ini dilakukan dengan bantuan sensor yang mengubah data fisik menjadi sinyal digital. Sensor ini dapat ditempatkan di mana saja dan mengirimkan data ke pusat kontrol.

Arsitektur sistem IoT bervariasi tergantung pada konteks penerapannya. Misalnya, dalam otomasi rumah, setiap kotak saklar listrik hanya membutuhkan sensor untuk menangkap sinyal dan prosesnya (kebanyakan beralih ON/OFF). Namun, dalam skenario real-time yang lebih kompleks, mungkin diperlukan prosesor dan perangkat penyimpanan di setiap perangkat IoT.

Secara umum, perkembangan IoT telah mengubah cara kita berinteraksi dengan teknologi. IoT memiliki potensi untuk mengubah berbagai bidang kehidupan, termasuk industri, kesehatan, dan transportasi.

##	Website

Website atau disebut juga web, site, situs web. Merupakan Kumpulan halaman web yang saling berhubungan serta dapat diakses dari mana saja selama terkoneksi dengan internet. Website terdiri dari Kumpulan komponen seperti teks, gambar, suara, yang berisi informasi.

Website terdiri dari dua komponen utama yaitu client-side dan server-side. Client-site website merupakan bagian situs web yang ditampilkan kepada user melalui browser. Bagian ini terdiri dari HTML, CSS, dan JavaScript untuk mendesain dan menampilkan halaman web. Sedangkan server-side website adalah bagian yang tidak terlihat oleh user, server-side berisikan file dan data yang proses oleh server web. Bagian server-side ini terdiri dari Bahasa pemrograman seperti Golang, PHP, dan python.

##	MQTT

MQTT (Message Queuing Telemetry Transport) merupakan protokol pesan yang dirancang untuk komunikasi mesin ke mesin. Protokol MQTT berjalan diatas stack TCP/IP, dan digunakan untuk mengirimkan data serta mengkomunikasikan data IoT dengan efisien. MQTT juga memfasilitasi pengiriman pesan antara Perangkat IoT dengan cloud serta sebaliknya.

System kerja MQTT menerapkan Publish dan Subscribe data. pada penggunaannya perangkat IoT akan terhubung dengan sebuah Broker dan memiliki Topic tertentu. Broker pada MQTT memiliki kegunaan untuk menangani data publish dan subscribe dari berbagai perangkat, atau dapat diumpamakan sebagai server yang memiliki Alamat Ip khusus.

Publish adalah cara perangkat mengirimkan datanya ke subscriber. Publisher biasanya berupa perangkat yang terhubung ke sensor tertentu. Subscribe adalah cara perangkap menerima berbagai jenis data dari publisher. Subscriber dapat menjadi aplikasi pemantau sensor dan lainnya. Subscriber akan meminta data dari penerbit. Topik seperti mengelompokan data ke dalam kategori tertentu. Topik wajib ada didalam system kerja protokol MQTT, setiap transaksi yang terjadi antara publisher dengan subscriber memerlukan topik tertentu. 

Protokol MQTT sudah menjadi standar untuk mengirimkan data IoT. Ada beberapa manfaat yang diberikan oleh protokol MQTT seperti:
-	Ringan dan efisien, Implementasi MQTT pada perangkat IoT membutuhkan sumber daya minimal, dapat digunakan pada mikrokontroler kecil, dengan pesan kontrol minimal dua bita data dan header pesan yang kecil untuk optimalisasi bandwidth jaringan.
-	Dapat diskalakan, MQTT membutuhkan sedikit kode dan daya, serta memiliki fitur bawaan untuk mendukung komunikasi dengan sejumlah besar perangkat IoT. Ini memungkinkan implementasi yang efisien untuk terhubung dengan jutaan perangkat.
-	Dapat diandalkan, MQTT mendukung perangkat IoT yang terhubung melalui jaringan seluler yang tidak dapat diandalkan, mengurangi waktu koneksi ulang, dan mendukung tiga tingkat kualitas layanan: paling banyak sekali (0), setidaknya sekali (1), dan tepat sekali (2).
-	Aman, MQTT menyederhanakan enkripsi pesan dan autentikasi perangkat serta pengguna dengan dukungan protokol modern seperti OAuth, TLS1.3, dan sertifikat pelanggan.
