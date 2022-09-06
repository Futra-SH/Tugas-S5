##### BAB 1


## Tantangan Kualitas Perangkat Lunak
---

#### 1.1 Keunikan Jaminan Kualitas Perangkat Lunak
“Lihat ini,” teriak temanku sambil menyodorkan Fitur Dagal kepadaku Pamflet Garansi Terbatas. “Bahkan Fitur Dagal tidak dapat mengatasi perangkat lunak bug." Dia menunjuk ke paragraf pendek di halaman 3 dari selebaran yang menyatakan ketentuan garansi untuk AMGAL, produk Master Perangkat Lunak terkemuka dijual di seluruh dunia. Selebaran tersebut menyatakan sebagai berikut:

> **GARANSI TERBATAS**
&nbsp;&nbsp;&nbsp;&nbsp;Fitur Dagal tidak memberikan jaminan, baik tersurat maupun tersirat, dengan sehubungan dengan kinerja, keandalan, atau kesesuaian AMGAL untuk semua yang ditentukan tujuan. Fitur Dagal tidak menjamin bahwa perangkat lunak atau dokumentasinya akan memenuhi kebutuhan Anda. meskipun Fitur Dagal memiliki melakukan pengujian perangkat lunak secara menyeluruh dan meninjau dokumentasi, Fitur Dagal tidak memberikan jaminan apa pun bahwa perangkat lunak dan dokumentasinya bebas dari kesalahan. Fitur Dagal tidak akan menjadi bertanggung jawab atas segala kerusakan, insidental, langsung, tidak langsung atau konsekuensial, timbul sebagai akibat dari data yang rusak, biaya pemulihan, kerugian laba, dan ketiga klaim pihak. perangkat lunak dilisensikan "sebagaimana adanya". pembeli mengasumsikan risiko lengkap yang berasal dari penerapan program AMGAL, kualitas dan kinerja.
&nbsp;&nbsp;&nbsp;&nbsp;Jika cacat fisik ditemukan dalam dokumentasi atau CD di yang AMGAL didistribusikan, Fitur Dagal akan menggantikan, tanpa biaya, dokumentasi atau CD dalam waktu 180 hari setelah pembelian, asalkan bukti pembelian disajikan.

“Apakah perangkat lunak AMGAL benar-benar istimewa sehingga pengembangnya tidak mampu memenuhi tantangan untuk memastikan produk bebas bug?” lanjut saya teman. “Apakah paket perangkat lunak lain membatasi jaminan mereka dengan cara yang sama?
Meskipun Fitur Dagal dan AMGAL adalah fiktif, pemeriksaan terhadap jaminan yang ditawarkan oleh pengembang perangkat lunak lain mengungkapkan pola yang sama. Tidak ada pengembang yang akan menyatakan bahwa perangkat lunaknya bebas dari cacat, seperti yang biasa dilakukan ole produsen besar perangkat keras komputer. Penolakan ini sebenarnya mencerminkan perbedaan unsur penting antara perangkat lunak dan industri lainnya produk, seperti mobil, mesin cuci atau radio. Perbedaan tersebut dapat dikategorikan sebagai berikut:

>**(1)	Kompleksitas produk.** Kompleksitas produk dapat diukur dengan jumlah mode operasional yang diizinkan produk. Sebuah produk industri, bahkan mesin canggih, tidak memungkinkan lebih dari beberapa ribu mode operasi, yang dibuat oleh kombinasi yang berbeda pengaturan mesin. Melihat paket perangkat lunak khas yang dapat ditemukan jutaan kemungkinan operasi perangkat lunak. Memastikan bahwa orang banyak kemungkinan operasional didefinisikan dengan benar dan dikembangkan adalah tantangan bagi industri perangkat lunak.

>**(2)	Visibilitas produk.** produk industri terlihat, perangkat lunak produk tidak terlihat. Sebagian besar cacat pada produk industri dapat terdeteksi selama proses produksi. Apalagi tidak adanya bagian dalam produk industri, sebagai suatu peraturan, sangat terlihat (bayangkan sebuah pintu hilang dari mobil baru Anda). Namun, cacat pada produk perangkat lunak (apakah disimpan di disket atau CD) tidak terlihat, seperti fakta bahwa bagian-bagiannya paket perangkat lunak mungkin tidak ada sejak awal.

>**(3)	Pengembangan produk dan proses produksi.** Mari kita tinjau sekarang fase di mana kemungkinan mendeteksi cacat pada produk industri mungkin muncul:

>>**(a)	Pengembangan produk.** Pada fase ini para desainer dan staf penjaminan mutu (QA) memeriksa dan menguji prototipe produk, untuk mendeteksi cacatnya.

>>**(b)	Perencanaan produksi produk.** Selama fase ini produksi proses dan alat dirancang dan disiapkan. Di beberapa produk ada adalah kebutuhan akan jalur produksi khusus untuk dirancang dan dibangun. Fase ini memberikan peluang tambahan untuk memeriksa produk, yang dapat mengungkapkan cacat yang "lolos" dari tinjauan dan pengujian yang dilakukan selama fase pengembangan.

>>**(c)	Manufaktur.** Pada fase ini, prosedur QA diterapkan untuk mendeteksi kegagalan produk itu sendiri. Cacat pada produk terdeteksi diperiode pertama manufaktur biasanya dapat dikoreksi dengan perubahan desain produk atau bahan atau alat produksi, dengan cara yang menghilangkan cacat tersebut pada produk yang diproduksi di masa depan.

Dibandingkan dengan produk industri, produk perangkat lunak tidak menguntungkan dari peluang untuk mendeteksi cacat pada ketiga fase proses produksi. Satu-satunya fase ketika cacat dapat dideteksi adalah fase pengembangan. Mari kita tinjau apa kontribusi setiap fase terhadap deteksi cacat:

>**(a)	Pengembangan produk.** Selama fase ini, upaya pengembangan tim dan profesional jaminan kualitas perangkat lunak diarahkan untuk mendeteksi cacat produk yang melekat. Di akhir fase ini prototipe yang disetujui, siap untuk direproduksi, tersedia.

>**(b)	Perencanaan produksi produk.** Fase ini tidak diperlukan untuk proses produksi perangkat lunak, karena pembuatan salinan perangkat lunak dan pencetakan manual perangkat lunak dilakukan secara otomatis. Ini berlaku untuk produk perangkat lunak apa pun, baik jumlah salinannya kecil, seperti dalam perangkat lunak yang dibuat khusus, atau besar, seperti dalam paket perangkat lunak dijual kepada masyarakat umum.

>**(c)	Manufaktur.** Seperti disebutkan sebelumnya, pembuatan perangkat lunak terbatas untuk menyalin produk dan mencetak salinan dari manual perangkat lunak. Akibatnya, harapan untuk mendeteksi cacat sangat terbatas selama fase ini.

Perlu dicatat bahwa bagian penting dari mesin canggih juga pada mesin rumah tangga dan produk lainnya termasuk perangkat lunak tertanam komponen (biasanya disebut "firmware") yang terintegrasi ke dalam produk. Komponen perangkat lunak ini (firmware) berbagi hal yang sama karakteristik produk perangkat lunak yang disebutkan di atas. Oleh karena itu, perbandingan yang ditunjukkan di atas sebenarnya adalah produk perangkat lunak versus produk industri lainnya dan komponen non-perangkat lunak industry produk yang menyertakan firmware. Selanjutnya, ketika menyebutkan perangkat lunak, maksud kami produk perangkat lunak serta firmware.
Perbedaan mendasar antara pengembangan dan produksi proses yang terkait dengan produk perangkat lunak dan produk industri lainnya menjamin pembuatan metodologi SQA yang berbeda untuk perangkat lunak. Kebutuhan untuk alat dan metode khusus untuk industri perangkat lunak tercermin dalam publikasi profesional serta dalam standar khusus yang ditujukan untuk SQA, seperti ISO 9000-3, “Pedoman penerapan ISO 9001 untuk pengembangan, penyediaan dan pemeliharaan perangkat lunak”. Poin ini didukung oleh fakta bahwa pedoman yang ditargetkan belum disiapkan oleh ISO untuk industri lain, dan satu-satunya pedoman yang ditargetkan lainnya telah disiapkan untuk layanan (ISO9004-2, “Manajemen mutu dan elemen sistem mutu: Pedoman untukpelayanan").
Kompleksitas besar serta ketidaktampakan perangkat lunak, antara lain karakteristik produk, membuat pengembangan metodologi SQA dan keberhasilan implementasi tantangan yang sangat profesional.

**1.2	Lingkungan di mana metode SQA dikembangkan**
Perangkat lunak yang dikembangkan oleh banyak individu dan dalam situasi yang berbeda memenuhi berbagai kebutuhan:
>•	Murid dan siswa mengembangkan perangkat lunak sebagai bagian dari pendidikan mereka.
•	Amatir perangkat lunak mengembangkan perangkat lunak sebagai hobi.
•	Profesional di bidang teknik, ekonomi, manajemen, dan bidang lainnya mengembangkan perangkat lunak untuk membantu mereka dalam pekerjaan mereka, untuk melakukan perhitungan, merangkum kegiatan penelitian dan survei, dan sebagainya.
•	Pengembang perangkat lunak profesional (analis sistem dan pemrogram) mengembangkan produk perangkat lunak atau firmware sebagai tujuan karir professional saat bekerja di rumah perangkat lunak atau dengan pengembangan perangkat lunak dan unit pemeliharaan (tim, departemen, dll.) besar dan kecil industri, keuangan dan organisasi lainnya.

Semua orang yang berpartisipasi dalam kegiatan ini diharuskan untuk menangani masalah kualitas perangkat lunak (“bug”). Namun, masalah kualitas di sebagian besar mereka bentuk parah mengatur pengembangan perangkat lunak profesional.
Oleh karena itu, buku ini dikhususkan untuk mendefinisikan dan memecahkan banyak masalah jaminan kualitas perangkat lunak (SQA) yang dihadapi oleh pengembangan perangkat lunak. dan profesional pemeliharaan. Namun, semua jenis pengembang perangkat lunak lainnya dapat menemukan bagian dari buku yang berlaku dan direkomendasikan untuk mereka upaya pengembangan perangkat lunak sendiri.
Mari kita mulai dengan pemeriksaan lingkungan pengembangan dan pemeliharaan perangkat lunak profesional (selanjutnya disebut "lingkungan SQA"), karena adalah pertimbangan utama dalam pengembangan metodologi SQA dan penerapan. Ciri-ciri utama dari lingkungan ini adalah sebagai berikut:
>**(1)	Kondisi kontrak.** Sebagai hasil dari komitmen dan kondisi didefinisikan dalam kontrak antara pengembang perangkat lunak dan pelanggan, kegiatan pengembangan dan pemeliharaan perangkat lunak perlu mengatasi:
>>•	Daftar persyaratan fungsional yang ditentukan oleh perangkat lunak yang dikembangkan dan pemeliharaannya harus dipenuhi.
•	Anggaran proyek.
•	Jadwal proyek.
Manajer proyek pengembangan dan pemeliharaan perangkat lunak membutuhkan untuk menginvestasikan sejumlah besar upaya dalam pengawasan kegiatan di dalam untuk memenuhi persyaratan kontrak.

>**(2)	Tunduk pada hubungan pelanggan-pemasok.** Sepanjang proses pengembangan dan pemeliharaan perangkat lunak, aktivitas berada di bawah pengawasan pelanggan. Tim proyek harus bekerja sama terus menerus dengan pelanggan: untuk mempertimbangkan permintaannya untuk perubahan, untuk mendiskusikan kritiknya tentang berbagai aspek proyek, dan untuk mendapatkan persetujuannya untuk perubahan yang diprakarsai oleh tim pengembangan. Hubungan seperti itu tidak biasanya ada ketika perangkat lunak dikembangkan oleh profesional non-perangkat lunak.

>**(3)	Diperlukan kerja tim.** Tiga faktor biasanya memotivasi pembentukan tim proyek daripada menugaskan proyek ke satu profesional:
>>•	Persyaratan jadwal. Dengan kata lain, beban kerja yang dilakukan selama periode proyek membutuhkan partisipasi lebih dari satu orang jika proyek harus diselesaikan tepat waktu.
•	Kebutuhan akan berbagai spesialisasi untuk melaksanakan proyek.
•	Keinginan untuk mendapatkan manfaat dari saling mendukung dan meninjau secara profesional untuk peningkatan kualitas proyek

>**(4)	Kerjasama dan koordinasi dengan tim perangkat lunak lain.** Pelaksanaan proyek, terutama proyek skala besar, oleh lebih dari satu tim adalah peristiwa yang sangat umum di industri perangkat lunak. Dalam kasus ini, kerjasama mungkin diperlukan dengan:
>>•	Tim pengembangan perangkat lunak lain dalam organisasi yang sama.
•	Tim pengembangan perangkat keras dalam organisasi yang sama.
•	Tim pengembangan perangkat lunak dan perangkat keras dari pemasok lain.
•	Tim pengembangan perangkat lunak dan perangkat keras pelanggan yang ambil bagian dalam pengembangan proyek.

>**(5)	Antarmuka dengan sistem perangkat lunak lain.** Saat ini, sebagian besar sistem perangkat lunak menyertakan antarmuka dengan paket perangkat lunak lain. Antarmuka ini memungkinkan data dalam bentuk elektronik mengalir di antara sistem perangkat lunak, gratis dari memasukkan data yang diproses oleh sistem perangkat lunak lain. Satu bias mengidentifikasi jenis antarmuka utama berikut:
>>•	Antarmuka input, di mana sistem perangkat lunak lain mengirimkan data ke sistem perangkat lunak.
•	Antarmuka keluaran, tempat sistem perangkat lunak Anda mentransmisikan proses data ke sistem perangkat lunak lain. 
•	Antarmuka input dan output ke papan kontrol mesin, seperti pada sistem kontrol medis dan laboratorium, peralatan pemrosesan logam, dll.

>**(6)	Kebutuhan untuk terus melaksanakan proyek meskipun anggota tim perubahan.** Sangat umum bagi anggota tim untuk meninggalkan tim selama periode pengembangan proyek, baik karena promosi ke yang lebih tinggi pekerjaan tingkat, beralih majikan, transfer ke kota lain, dan sebagainya. Pemimpin tim kemudian harus mengganti anggota tim yang pergi juga oleh karyawan lain atau oleh karyawan yang baru direkrut. Bagaimanapun caranya banyak upaya diinvestasikan dalam melatih anggota tim baru, "pertunjukan" harus dilanjutkan”, yang berarti jadwal kontrak proyek asli tidak akan berubah.

>**(7)	Kebutuhan untuk terus melakukan pemeliharaan perangkat lunak untuk waktu yang lama.** Pelanggan yang mengembangkan atau membeli sistem perangkat lunak mengharapkan untuk terus menggunakannya untuk waktu yang lama, biasanya selama 5-10 tahun. Selama masa layanan, kebutuhan akan pemeliharaan pada akhirnya akan muncul. Di kebanyakan kasus, pengembang diharuskan untuk menyediakan layanan ini secara langsung. “Pelanggan” internal, dalam kasus di mana perangkat lunak telah dikembangkan in-house, berbagi harapan yang sama mengenai pemeliharaan perangkat lunak selama periode layanan sistem perangkat lunak.

Karakteristik lingkungan menciptakan kebutuhan yang intensif dan berkesinambungan upaya manajerial sejajar dengan upaya profesional yang harus diinvestasikan untuk menjamin kualitas proyek, dengan kata lain untuk menjamin keberhasilan proyek.
Sejumlah besar perangkat lunak serta pengembangan firmware tidak dilakukan dengan tunduk pada kontrak formal atau hubungan formal pelanggan-pemasok, sebagaimana disebutkan dalam dua karakteristik lingkungan SQA pertama. Ini Jenis kegiatan biasanya menyangkut perangkat lunak yang dikembangkan sendiri untuk penggunaan internal atau untuk pemasaran sebagai paket perangkat lunak dan pengembangan perangkat lunak internal. Hubungan antara departemen pemasaran yang memulai dan mendefinisikan kualifikasi produk baru dan departemen pengembangan perangkat lunak internal masing-masing sering menyerupai kontrak dan hubungan pelanggan-pemasok. Hal yang sama berlaku untuk permintaan internal untuk sistem perangkat lunak baru atau untuk meningkatkan perangkat lunak atau firmware saat ini menjadi diimplementasikan oleh departemen perangkat lunak organisasi. Hubungan aktual antara "pelanggan" internal dan departemen pengembangan ditemukan sangat bervariasi ketika diukur dengan skala formal-informal. Beberapa manajer mengklaim bahwa semakin dekat hubungan dengan bentuk formal, semakin besar prospek keberhasilan proyek.

#### Ringkasan
>**(1)	Keunikan jaminan kualitas perangkat lunak.**
Perbedaan mendasar antara produk perangkat lunak (termasuk firmware) dan produk lain disebabkan oleh kompleksitas produk yang lebih tinggi, oleh tembus pandang perangkat lunak dan oleh sifat pengembangan produk dan proses produksi. Perbedaan ini menciptakan kebutuhan akan metodologi dan alat SQA untuk SQA yang akan memenuhi tantangan khusus dan berbeda untuk pengembangan dan pengoperasian jaminan kualitas untuk perangkat lunak.
**(2)	Lingkungan di mana metode SQA dikembangkan.**
Metode dan alat SQA yang dibahas dalam buku ini secara khusus ditujukan untuk kebutuhan pengembangan dan pemeliharaan perangkat lunak profesional, aktivitas di mana kualitas masalah muncul dalam bentuk yang paling parah, dan di mana kerugian yang paling menyakitkan adalah mengharapkan. Oleh karena itu setiap metode atau alat yang akan diterapkan tunduk pada karakteristik lingkungan kegiatannya, yaitu:
>>•	Kondisi kontrak dan komitmen yang menentukan isi dan jadwal.
•	Kondisi hubungan pelanggan-pemasok, sebagaimana diwujudkan oleh kebutuhan untuk konsultasi dengan pelanggan dan perolehan persetujuannya.
•	Persyaratan untuk kerja tim
•	Perlu kerjasama dan koordinasi dengan tim pengembangan lainnya
•	Kebutuhan akan antarmuka dengan sistem perangkat lunak lain
•	Perlu terus menjalankan proyek saat tim berubah
•	Perlu terus memelihara sistem perangkat lunak selama bertahun-tahun
Karakteristik lingkungan ini juga berlaku untuk pengembangan internal perangkat lunak dan firmware, meskipun hanya kontrak informal atau hubungan pelanggan-pemasok informal yang ada dalam kasus ini. Sifat-sifat ini menuntut bahwa intensif dan upaya manajerial yang berkelanjutan dikeluarkan secara paralel dengan upaya professional yang harus diinvestasikan untuk memastikan kualitas proyek atau, dengan kata lain, untuk memastikan keberhasilan proyek.