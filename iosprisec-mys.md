![iOSPriSec](https://cdn.rawgit.com/harleo/assets-repo/5f922f40/iOSPriSec/iosprisec_github_repo_logo.svg)  

📱 Nasihat untuk memaksimumkan dan mengimbangkan pengaturan keselamatan dan privasi di dalam iOS

## Preface

Panduan ini akan memberi tumpuan kepada aspek keselamatan dan privasi di dalam platform IOS. Walaupun Apple mengambil perhatian besar terhadap aspek tersebut untuk kedua-duanya, peranti mereka dan pelanggannya, adalah penting untuk melalui langkah tambahan kerana Apple memberi anda banyak pilihan.

Untuk maklumat lanjut mengenai bagaimana Apple mengendalikan keselamatan dan privasi, lawati:
[https://www.apple.com/business/docs/iOS_Security_Guide.pdf](https://www.apple.com/business/docs/iOS_Security_Guide.pdf)  
[https://www.apple.com/lae/privacy/approach-to-privacy/](https://www.apple.com/lae/privacy/approach-to-privacy/)

---

### Contents
[1. Introduksi](#1-introduksi)  
[2. Apple ID](#2-apple-id)  
⋅⋅⋅ [2.1 Name, Nombor Telefon, E-mel](#21-nama-nombor-telefon-e-mel)  
⋅⋅⋅ [2.2 Kata Laluan & Sekuriti](#22-kata-laluan--sekuriti)  
⋅⋅⋅ [2.3 iCloud](#23-icloud)  
⋅⋅⋅ [2.4 iTunes & App Store](#24-itunes--app-store)  
[3. Umum](#3-umum)  
⋅⋅⋅ [3.1 Kemas Kini Perisian](#31-kemas-kini-perisian)  
⋅⋅⋅ [3.2 AirDrop](#32-airdrop)  
⋅⋅⋅ [3.3 Kebolehcapaian](#33-kebolehcapaian)  
⋅⋅⋅⋅⋅⋅ [3.3.1 Face ID & Perhatian](#331-face-id--perhatian)  
[4. Siri & Carian](#4-siri--carian)  
[5. Touch ID/Face ID & Kod Laluan](#5-touch-idface-id--kod-laluan)  
[6. Kecemasan SOS](#6-kecemasan-sos)  
[7. Privasi](#7-privasi)  
⋅⋅⋅ [7.1 Perkhidmatan Lokasi](#71-perkhidmatan-lokasi)  
⋅⋅⋅⋅⋅⋅ [7.1.1 Perkhidmatan Sistem](#711-perkhidmatan-sistem)  
⋅⋅⋅⋅⋅⋅⋅⋅⋅ [7.1.1.1 Lokasi Penting](#7111-lokasi-penting)  
⋅⋅⋅ [7.2 Analitis](#72-analitis)  
⋅⋅⋅ [7.3 Pengiklanan](#73-pengiklanan)  
[8. Telefon](#8-telefon)  
⋅⋅⋅ [8.1 Tunkukkan ID Pemanggil Saya](#81-tunjukkan-id-pemanggil-saya)  
⋅⋅⋅ [8.2 PIN SIM](#82-pin-sim)  
[9. Safari](#9-safari)  
⋅⋅⋅ [9.1 Enjin Carian](#91-enjin-carian)

#### 1. Introduksi
Pada masa kini, kata-kata seperti privasi dan keselamatan telah semakin relevan seperti sebelum ini. Ini bermakna mengambil langkah tambahan mengenai bagaimana peranti anda berinteraksi dan mengendalikan data dengan pihak ketiga adalah sangat penting.

Peranti dan pihak ketiga yang anda gunakan, menjana jejak digital yang besar setiap hari, yang mungkin anda tidak menyedari. Oleh kerana data itu milik anda, saya percaya ia sepatutnya menjadi milik anda.

Menjadi secara semula jadi ingin tahu saya telah menetapkan tetapan pada dasarnya setiap peranti saya sendiri. Walaupun saya telah melakukan ini selama bertahun-tahun untuk keluarga dan rakan-rakan, saya berada di bawah anggapan bahawa semua orang melakukan ini. Tetapi saya salah. Masalah yang saya telah perhatikan adalah bahawa kebanyakan orang tidak memberi pemikiran kedua tentang pergi ke tetapan, mereka hanya mahu menggunakan peranti itu. Apa yang mengejutkan, adalah bahawa walaupun orang dalam bidang berkaitan sains komputer tertakluk untuk tidak mengubah tetapan semasa mereka seharusnya melakukannya.

Oleh itu saya membuat keputusan untuk menulis ringkas untuk membantu anda mengambil langkah-langkah yang diperlukan pada iOS (seberapa banyak yang boleh anda lakukan dengan pilihan yang disediakan).

#### 2. Apple ID
Semasa membuka aplikasi tetapan pada iOS, anda harus melihat nama anda dikaitkan dengan ID Apple peranti anda di bahagian paling atas senarai. Ketik padanya dan anda juga harus melihat e-mel yang dikaitkan dengannya, serta pelbagai pilihan mengenai akaun anda.

##### 2.1 Nama, Nombor Telefon, E-mel
Memilih sama ada untuk meletakkan nama sebenar atau palsu anda di sini adalah topik yang kontroversial dalam dan dari dirinya sendiri. Sekiranya anda menggunakan sebarang perkhidmatan Apple tambahan yang disambungkan ke Apple ID ini, nama anda jelas akan dikaitkan dengannya.

Di bawah bahagian 'SUBSCRIPTIONS' lumpuhkan 'Pengumuman' dan 'Aplikasi, muzik, filem dan banyak lagi'. Ini akan membantu anda menyingkirkan e-mel pemasaran yang berkaitan dengan alamat e-mel di bawah bahagian 'CONTACTABLE AT'.

##### 2.2 Kata Laluan & Sekuriti
Sekarang, saya ingin mendidik anda tentang betapa pentingnya menggunakan kata laluan yang kuat untuk Apple ID anda (dan perkhidmatan apa pun sebenarnya), jadi, jika anda menggunakan kata laluan yang lemah, ubahlah ia menjadi sesuatu yang lebih rumit. Bergantung kepada perkhidmatan yang anda gunakan, mereka mungkin menyekat anda untuk keperluan kata laluan mereka. Ini tidak sesuai kerana perkhidmatan yang berbeza mempunyai keperluan kata laluan yang berbeza untuk berfungsi dengan backend mereka.

Sekiranya anda tidak pasti bagaimana untuk mencipta kata laluan yang baik, baca beberapa perkara ini
pautan (yang pertama adalah yang paling relevan kerana ia adalah Apple):
[https://support.apple.com/en-gb/HT201303](https://support.apple.com/en-gb/HT201303)  
[https://support.microsoft.com/en-us/help/4026406/microsoft-account-create-a-strong-password](https://support.microsoft.com/en-us/help/4026406/microsoft-account-create-a-strong-password)  
[https://support.google.com/accounts/answer/32040?hl=en](https://support.google.com/accounts/answer/32040?hl=en)  

Pastikan anda membolehkan 'Pengesahan Dua Faktor'. Jika anda log masuk ke peranti Apple baru atau perkhidmatan dalam talian mereka seperti iCloud dan menggunakan ID Apple yang sama, ia akan meminta kod untuk salah satu daripada peranti yang dipercayai untuk mengesahkan identiti anda.

##### 2.3 iCloud
Perkhidmatan iCloud adalah satu cara untuk anda menyimpan perkara seperti foto dan data lain dari aplikasi untuk mengimbangi penyimpanan atau data sandaran ke awan. Bergantung kepada sama ada anda mahukan data tersebut pada peranti anda disegerakkan dengan peranti Apple lain yang anda miliki, anda boleh mengambil tetapan yang sesuai. Sekiranya anda ingin mengambil sedikit perkara lagi, dan anda ingin tahu di mana dan bagaimana data itu disimpan, anda boleh membaca tentangnya di dalam 'Panduan Keselamatan-Kertas Putih iOS' pada halaman 53 dan seterusnya: [https://www.apple.com/business/docs/iOS_Security_Guide.pdf](https://www.apple.com/business/docs/iOS_Security_Guide.pdf).

Sesuatu yang penting untuk diperhatikan adalah bahawa Apple baru-baru ini mengumumkan bahawa ia sebahagiannya menyimpan data iCloud di datacenters Google, yang tidak mengejutkan, kerana ia juga telah menyimpan data pada perkhidmatan lain seperti AWS, perkhidmatan awan Amazon. Anda boleh membaca lebih lanjut mengenainya di sini: 
[https://arstechnica.com/gadgets/2018/02/your-apple-icloud-data-is-now-stored-on-google-servers-surprised/](https://arstechnica.com/gadgets/2018/02/your-apple-icloud-data-is-now-stored-on-google-servers-surprised/)

Tetapan menarik yang lebih menarik ialah ciri 'Find My iPhone' / 'Find My iPad'. Jika peranti anda berlaku untuk dicuri, anda akan dapat melakukan tindakan tertentu dari laman web iCloud, seperti mengelap, memainkan bunyi atau meletakkannya dalam mod yang hilang. Selain itu, anda juga akan dapat melihat lokasi peranti.

Jalan di bawah terdapat 'Look Me Up' dan 'Kongsi Lokasi Saya'. Sekiranya anda ingin melakukan salah satu daripada yang dinyatakan dalam tetapan masing-masing, anda boleh melakukannya.

##### 2.4 iTunes & App Store
Bahagian ini kebanyakannya mengandungi perkara yang dapat anda setujui dengan keinginan anda, bergantung pada pelan data mudah alih anda dan topi data bulanannya.

#### 3. Umum

##### 3.1 Kemas Kini Perisian
Ini harus menjadi perkara yang jelas untuk dilakukan. Sila simpan peranti anda sehingga kini. Mereka bukan sahaja menyediakan ciri-ciri baru, tetapi yang paling penting adalah kemas kini keselamatan.

##### 3.2 AirDrop
AirDrop harus dimatikan dengan ideal, atau menghidupkan hanya untuk kenalan. Ini akan menghalang orang lain melihat peranti anda apabila berdekatan dengannya (walaupun ini juga akan terjadi dengan Bluetooth dihidupkan).

##### 3.3 Kebolehcapaian
##### 3.3.1 Face ID & Perhatian
ID Face ID hanya tersedia di iPhone X. Jika anda menggunakan ID Wajah di tempat pertama, aktifkan tetapan 'Memerlukan Perhatian untuk ID Wajah' yang akan memastikan bahawa anda secara aktif melihat peranti itu, dengan mata anda terbuka, sebelum cuba membuka kunci.

#### 4. Siri & Carian
Bergantung kepada jika anda berhasrat untuk menggunakan Siri, ada perkara-perkara tertentu yang perlu diperhatikan. Contohnya 'Allow Siri Apabila Dikunci' akan membuat Siri diakses oleh orang lain semasa anda tidak berada di sekelilingnya. Siri akan melaksanakan tugas tertentu, seperti menghantar mesej bagi pihak anda, membuat entri kalendar atau tetapkan masa (lebih lanjut mengenai ini dalam bahagian 5.).

#### 5. Touch ID/Face ID & Kod Laluan
Ini satu lagi topik kontroversi. Sekiranya anda menggunakan ID ID / Face Touch untuk kemudahan atau kod laluan alfanumerik yang kuat? Sekali lagi, ini terpulang kepada anda. Tetapi ambil perhatian bahawa sekiranya berlaku tindakan ganas terhadap anda, lebih mudah untuk masuk ke dalam peranti anda dengan sentuhan mudah atau buka kunci daripada menyediakan kod laluan. Juga sekiranya anda melakukan perjalanan ke A.S., kes telah menunjukkan bahawa pegawai peronda sempadan dibenarkan menuntut bahawa anda membuka kunci peranti anda dengan ID Sentuhan tetapi tidak melalui kod laluan. Sekiranya anda ingin membaca lebih lanjut mengenai topik ini, inilah panduan mendalam yang sangat baik oleh Yayasan Frontier Elektronik: [https://www.eff.org/wp/digital-privacy-us-border-2017](https://www.eff.org/wp/digital-privacy-us-border-2017).

Di bawah seksyen 'AKAN MENDAPATKAN AKSES KELOMPOK', anda boleh menggabungkan perkara dengan keinginan anda, idealnya dengan beberapa ciri yang boleh diakses.

Terdapat pilihan yang agak menarik sepanjang jalan di bahagian bawah. Jika anda atau orang lain gagal membuka kunci peranti anda selepas 10 kali cuba, ia akan menghapus sepenuhnya. Sekarang implikasinya adalah bahawa masa antara anda berinteraksi dengan peranti anda satu masa dan masa lain harus kurang dari satu jam. Ini kerana jika seseorang gagal untuk membuka kunci peranti anda sebanyak 9 kali, kelewatan antara cubaan membuka kunci akan ditambah, dan dengan 9 cuba kelewatan ini adalah sejam. Bergantung kepada bagaimana sensitif data pada peranti anda, anda mahu mengambil pilihan yang sesuai.

#### 6. Kecemasan SOS
Diperkenalkan dalam IOS 11, ciri dalam keadaan kecemasan, di mana jika anda memegang butang kunci dan salah satu butang kelantangan cukup lama, perkhidmatan kecemasan akan dipanggil dari peranti anda. Walaupun ciri ini telah menyelamatkan banyak nyawa sejak pengenalannya adalah penting untuk mengetahui bahawa ini termasuk ID Perubatan, ciri yang anda boleh aktifkan jika anda ingin berbuat demikian. ID Perubatan adalah ciri di mana seseorang boleh melihat maklumat asas seperti nama, berat, ketinggian, kenalan kecemasan (anda boleh mengatasinya) dan lain-lain semasa peranti anda dikunci. Ini bertujuan untuk keadaan di mana seorang profesional perubatan dapat dengan cepat mendapatkan maklumat mengenai anda di tempat, sekiranya anda tidak dapat berkomunikasi.

#### 7. Privasi
##### 7.1 Perkhidmatan Lokasi
Bahagian perkhidmatan lokasi adalah penting untuk melihat kerana anda boleh mematikannya sepenuhnya atau menapisnya untuk membenarkan aplikasi tertentu mengakses data lokasi anda. Lakukan demikian.

##### 7.1.1 Perkhidmatan Sistem
Lumpuhkan 'Makluman Berbasis Lokasi' (jika tidak, Apple mungkin memberikan cadangan aplikasi berdasarkan lokasi anda), 'Iklan Berasaskan Lokasi' dan 'Cadangan Berasaskan Lokasi', selebihnya terpulang kepada anda.

Dalam seksyen 'PENINGKATAN PRODUK' melumpuhkan semua empat tetapan, kerana mereka akan terus menggunakan data lokasi anda untuk memperbaiki perkara seperti data lalu lintas Peta Apple.

Jalan di bahagian bawah adalah tetapan yang membolehkan anda melihat ikon dalam bar status anda, setiap kali perkhidmatan meminta lokasi anda. Ini tidak hanya itu, ia hanya sekadar maklumat yang menarik untuk anda lihat.

Jika anda ingin membaca lebih lanjut tentang perkhidmatan lokasi, lawati:
[https://support.apple.com/en-us/HT207056](https://support.apple.com/en-us/HT207056)

##### 7.1.1.1 Lokasi Penting
Bahagian ini akan membolehkan peranti anda mengingati tempat penting berdasarkan lokasi anda untuk memberi anda maklumat berasaskan lokasi. Anda mahu mematikan ini.

##### 7.2 Analitis
Lumpuhkan 'Analitis Saham iPhone' / 'Analis Kongsi iPhone & Analitik' / 'Analis iPad Kongsi' dan 'Kongsi Analitik iCloud'. Biasanya ini akan membantu menghantar data diagnostik harian ke Apple supaya mereka dapat meningkatkan perkhidmatan mereka, tetapi kerana ini mungkin termasuk data sensitif seperti lokasi, anda ingin mematikannya.

Jika anda ingin mendayakannya, sila baca dua pautan yang diserlahkan di dalam halaman tetapan itu, agar anda dapat menilai kepentingannya.

##### 7.3 Pengiklanan
Dayakan 'Penjejakan Iklan Had' dan ketik 'Pengecam Pengiklanan Pengiklanan ...'. Sekarang seperti yang dinyatakan di bawah tetapan itu, ini mungkin masih bermakna bahawa anda akan disiarkan iklan, tetapi tidak seperti yang relevan lagi, yang bermaksud ia kurang khusus disesuaikan dengan minat anda.

#### 8. Telefon
##### 8.1 Tunjukkan ID pemanggil saya
Di sini anda akan dapat menyembunyikan nombor telefon anda daripada dipaparkan pada telefon penerima. Sila ambil perhatian bahawa ini kemungkinan besar tidak akan menyembunyikannya jika anda cuba membuat panggilan prank perkhidmatan kecemasan.

##### 8.2 PIN SIM
Sekiranya anda belum mempunyai set PIN SIM, ini akan menambah lapisan keselamatan tambahan untuk kad SIM anda.

#### 9. Safari
Bahagian ini hanya akan terpakai kepada anda jika anda aktif menggunakan Safari sebagai pilihan pelayar iOS anda. Sekiranya anda tidak, anda perlu mula menggunakan Berani (lihat lebih lanjut di sini: [https://brave.com](https://brave.com)).

Lumpuhkan 'Cadangan Engine Search', 'Cadangan Safari', dan 'Preload Top Hit'. Tetapan tersebut akan disegerakkan (disulitkan dari hujung ke hujung) dengan peranti Apple anda yang lain, atau tanpa nama dan dihantar ke Apple untuk dianalisis. Lihat pautan yang diserlahkan di bahagian itu, jika anda mahu membaca lebih lanjut.

Dayakan 'Block Pop-ups'.

Di bawah seksyen 'PRIVASI & KEAMANAN' membolehkan 'Mencegah Pelacakan Cross-Site', 'Block All Cookies', 'Tanyakan Laman Web Tidak Jejak Saya' dan 'Amaran Laman Web Fraud'. Ambil perhatian bahawa menyekat kuki mungkin mengehadkan beberapa ciri di laman web. Teruskan melumpuhkan 'Akses Kamera & Mikrofon' dan 'Semak untuk Apple Pay'.

Juga, tolonglah sendiri dan ketik 'Hapuskan Data Sejarah dan Laman Web' sekali-sekala (pastikan anda tidak mempunyai tab penting terbuka, mereka akan dipadam).

##### 9.1 Enjin Carian
Jika anda ingin menggunakan enjin carian yang menghormati privasi anda, sila gunakan DuckDuckGo sebagai lalai. DuckDuckGo bahkan akan membenarkan anda untuk proksi permintaan carian anda dengan menambah '! G' di hadapan pertanyaan anda kepada Google, untuk mendapatkan hasil carian Google. Untuk maklumat lanjut mengenai mengapa anda perlu menggunakannya, lawati: [https://duckduckgo.com/privacy](https://duckduckgo.com/privacy)

---

## Tutup
Tahniah, inilah pengakhiran panduan ini!
Ini akan menyimpulkan panduan ini tentang cara mengambil langkah-langkah yang diperlukan untuk meningkatkan keselamatan dan privasi peranti iOS anda.

Jika anda ingin membantu keluarga atau rakan-rakan anda, kongsikan panduan ini!

[> Tweet](http://twitter.com/share?text=Useful+tips+on+how+to+maximize+and+balance+security+and+privacy+on+iOS&url=https://github.com/harleo/iOSPriSec/blob/master/README.md)

---

oleh [@_harleo](https://twitter.com/_harleo)

_versi iOS pada masa tulisan: 11.2.6 (15D100)_

_12th Mac 2018_
