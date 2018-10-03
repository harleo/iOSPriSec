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
⋅⋅⋅ [2.2 Kata Laluan & Sekuriti](#22-kata-laluan-keselamatan)  
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
⋅⋅⋅ [7.2 Analis](#72-analis)  
⋅⋅⋅ [7.3 Pengiklanan](#73-pengiklanan)  
[8. Telefon](#8-telefon)  
⋅⋅⋅ [8.1 Tunkukkan ID Pemanggil Saya](#81-tunjukkan-id-pemanggil-saya)  
⋅⋅⋅ [8.2 SIM PIN](#82-sim-pin)  
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

##### 2.2 Kata Laluan & Keselamatan
Sekarang, saya ingin mendidik anda tentang betapa pentingnya menggunakan kata laluan yang kuat untuk Apple ID anda (dan perkhidmatan apa pun sebenarnya), jadi, jika anda menggunakan kata laluan yang lemah, ubahlah ia menjadi sesuatu yang lebih rumit. Bergantung kepada perkhidmatan yang anda gunakan, mereka mungkin menyekat anda untuk keperluan kata laluan mereka. Ini tidak sesuai kerana perkhidmatan yang berbeza mempunyai keperluan kata laluan yang berbeza untuk berfungsi dengan backend mereka.

Sekiranya anda tidak pasti bagaimana untuk mencipta kata laluan yang baik, baca beberapa perkara ini
pautan (yang pertama adalah yang paling relevan kerana ia adalah Apple):
[https://support.apple.com/en-gb/HT201303](https://support.apple.com/en-gb/HT201303)
[https://support.microsoft.com/en-us/help/4026406/microsoft-account-create-a-strong-password](https://support.microsoft.com/en-us/help/4026406/ microsoft-account-create-a-strong-password)
[https://support.google.com/accounts/answer/32040?hl=en](https://support.google.com/accounts/answer/32040?hl=en)

Bergerak pada anda pasti akan membolehkan 'Pengesahan Dua Faktor'. Jika anda log masuk ke peranti Apple baru atau perkhidmatan dalam talian mereka seperti iCloud dan menggunakan ID Apple yang sama, ia akan meminta kod untuk salah satu daripada peranti yang dipercayai untuk mengesahkan identiti anda.
