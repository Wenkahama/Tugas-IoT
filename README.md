# Tugas-IoT Adimas Muhammad Amir (09021282126065)
1) Sejarah dan definisi IoT
   
      Istilah “internet of things” pertama kali dicetuskan pada tahun 1999 oleh Kevin Ashton saat melakukan presentasi untuk perusahaan Procter & Gamble (P&G), di mana ia menjelaskan mengenai teknologi yang menghubungkan berbagai perangkat dengan bantuan RFID (radio frequency identification) dan mengatur semuanya dengan komputer. Konsep dari teknologi internet of things itu sendiri adalah memasangkan pemancar sinyal jarak pendek yang berukuran kecil ke beragam perangkat dan keperluan sehari-hari untuk menciptakan bentuk interaksi baru antara manusia dengan perangkat hingga antara perangkat dengan perangkat lain.

      Internet of Things (IoT) merujuk pada jaringan perangkat fisik yang terhubung melalui internet, yang dapat saling berkomunikasi dan berbagi data. Perangkat IoT dapat mencakup berbagai objek, mulai dari perangkat elektronik hingga sensor, kendaraan, dan bahkan peralatan rumah tangga yang dilengkapi dengan teknologi untuk mengumpulkan dan bertukar data.

2) Referensi Model IoT
      1. Physical Devices & Controller,
Layer pertama dari referensi model IoT adalah Physical Devices & Controller. Layer ini merupakan layer terbawah dalam hierarki referensi model IoT yang bertanggung jawab untuk mengumpulkan data dari sensor atau perangkat yang terhubung ke jaringan IoT. Pada layer ini, perangkat keras seperti Raspberry Pi, Arduino, dan sensor-sensor IoT berada di dalamnya. Raspberry Pi dan Arduino sering digunakan sebagai kontroler atau gateway untuk menghubungkan beberapa sensor dan perangkat IoT ke jaringan internet.

      2. Connectivity Layer,
kedua dari referensi model IoT adalah Connectivity. Pada layer ini, perangkat IoT terhubung ke jaringan internet melalui koneksi nirkabel atau kabel. Router dan modem adalah contoh perangkat yang digunakan untuk menghubungkan perangkat IoT ke jaringan internet. Selain itu, protokol seperti Wi-Fi, Bluetooth, Zigbee, dan Z-Wave juga digunakan untuk menghubungkan perangkat IoT ke jaringan internet.

      3. Edge Computing,
Layer ketiga dari referensi model IoT adalah Edge Computing. Pada layer ini, proses komputasi dilakukan di perangkat IoT atau di tepi jaringan (edge of the network), bukan di server pusat. Edge computing memungkinkan pengolahan data secara real-time dan mengurangi beban jaringan, sehingga meningkatkan kecepatan dan efisiensi pengolahan data. Apache Kafka dan Apache Spark adalah contoh teknologi edge computing yang sering digunakan pada layer ini.

      4. Data Accumulation,
Layer keempat dari referensi model IoT adalah Data Accumulation. Pada layer ini, data yang dikumpulkan dari perangkat IoT diolah dan disimpan dalam database atau penyimpanan data. Apache Cassandra dan MongoDB adalah contoh teknologi penyimpanan data yang sering digunakan pada layer ini.

      5. Collaboration & Process,
Layer kelima dari referensi model IoT adalah Collaboration & Process. Pada layer ini, data dari perangkat IoT diolah dan dianalisis untuk menghasilkan informasi yang

      6. Application,
Layer keenam dari referensi model IoT adalah Application. Pada layer ini, data yang telah diolah dan dianalisis digunakan untuk membuat aplikasi yang dapat digunakan oleh pengguna akhir. Aplikasi tersebut dapat berupa aplikasi mobile, dashboard, atau website. Contoh teknologi yang sering digunakan pada layer ini adalah React Native, Flutter, dan AngularJS.

      7. Data Abstraction,
Layer terakhir dari referensi model IoT adalah Data Abstraction. Pada layer ini, data yang telah diolah dan dianalisis diambil dan diubah menjadi bentuk yang lebih mudah dimengerti dan diakses oleh pengguna akhir. Contoh teknologi yang sering digunakan pada layer ini adalah API dan GraphQL.

3) Macam-macam kebutuhan IoT

      Industri Retail,
IoT dapat menggabungkan data, melakukan analisa dan proses pemasaran di berbagai lokasi, sangat dibutuhkan oleh industri retail. Data yang diambil dari toko offline dan kanal digital bisa dianalisa secara realtime untuk memahami pola belanja dan preferensi konsumen. Perangkat IoT yang bisa digunakan berupa RFID chips, smartphone, sistem Wi-Fi, smart shelves (rak pintar) dan lain-lain.

      Bidang Manufaktur,
Di bidang manufaktur IoT dapat menghubungkan semua fase proses Industrial, dari rantai pasokan sampai dengan pengiriman, dengan sangat detail mulai dari produksi, proses, hingga data mengenai tiap produk. Sensor-sensor IoT di mesin pabrik maupun rak gudang dapat berguna sebagai analitik data untuk mengoptimalkan kinerja peralatan, efisiensi biaya, meningkatkan produksi hingga mencegah kerusakan, yang nantikan akan meningkatkan kualitas perusahaan secara keseluruhan.

      Bidang Kesehatan,
Teknologi IoT yang biasanya terpasang untuk bidang kesehatan berguna untuk memantau detak jantung, aktovitas fisik, kualitas tidur dan kebiasaan lainnya yang mempengaruhi kesehatan. Data-dari dari IoT ini memungkinkan diagnosa dan rencana perawatan yang tepat, meningkatkan keselamatan pasien, serta penyederhanaan tindakan medis. Teknologi IoT bekerja dengan mengambil data secara real time dari perangkat yang terhubung dengan sistem IoT.

      Industri Transportasi dan Logistik,
Teknologi IoT dan AI (artificial intelligence) sangat mendukung sistem kerja di industri transportasi dan logistik, teknologi IoT menyediakan fitur geofence yang dapat diterapkan untuk meningkatkan efisiensi dan produktivitas yang lebih besar bagi perusahaan transportasi dan logistik. Adanya IoT dapat meningkatkan kualitas layanan, efisiensi, dan meningkatkan kepuasan pelanggan.

      Bidang Pemerintahan,
Pengaplikasian IoT dapat digunakan untuk mengatasi berbagai masalah untuk suatu wilayah, seperti kemacetan lalu lintas, layanan kota, kegiatan perekonomian, ketertiban warga, serta keselamatan dan keamanan publik. Konsep smart City yang mulai diterapkan di berbagai negara memanfaatkan teknologi IoT ke dalam infrastruktur fisik, seperti: lampu jalan, meteran air, lampu lalu lintas, pemantau polusi udara dan lain-lain.

      Bidang Energi,
Teknologi IoT dapat digunakan untuk melakukan analisa dan mengintergrasikan beberapa sumber energi baru seperti matahari dan angin. Di sisi lain teknologi IoT juga membantu efisiensi penggunaan sumber energi konvensional. Kedua hal tersebut diharapkan bisa menjadi inovasi di bidang energi agar kita tidak mengalami krisis energi di masa depan.

4) Contoh Implementasi IoT

   Pada industri restoran IoT dapat digunakan untuk tracking dan recording transaksi dan pesanan makanan. Restoran tidak perlu lagi secara manual membuat catatan dalam buku karena setiap transaksi dari kasir otomatis akan langsung dihitung dan disimpan di database. Pesanan juga dapat disimpan statusnya apa sudah diselesaikan atau belum sehingga tidak pusing lagi harus mengingat.
