     LAPORAN KELOMPOK IX      
    MIKROTIK
















Disusun oleh :
Rahman
Shinta nurlaili
Muh. Akmal kamil
Yusuf mensano
       XI TEKNIK JARINGAN KOMPUTER DAN TELEKOMUNIKASI
SMKN 3 KENDARI
                                          2022/2023 
KATA PENGANTAR

Puji syukur kami panjatkan kehadirat Allah Swt. yang sudah melimpahkan rahmat, taufik, dan hidayah- Nya sehingga kami bisa menyusun tugas kosentrasi keahlian 1ini dengan baik serta tepat waktu. Seperti yang sudah kita tahu mikrotik  routerOS merupakan system operasi Linux base yang diperuntukkan sebagai network router.Tugas ini kami buat untuk memberikan ringkasan tentang mikrotik.Mudah-mudahan makalah yang kami buat ini bisa bermanfaat bagi semua orang. Kami menyadari kalau masih banyak kekurangan dalam menyusun makalah ini.
Oleh sebab itu, kritik serta anjuran yang sifatnya membangun sangat kami harapkan guna kesempurnaan makalah ini. Kami mengucapkan terima kasih kepada Ibu Guru mata pelajaran kosentrasi keahlian satu. Kepada teman teman yang sudah menolong turut dan dalam penyelesaian laporan ini. Atas waktunya, kami sampaikan banyak terima kasih.
 








                                                                                       Kendari,Januari 2023


                                                                                                Penyusun 


 
Daftar Isi

KATA PENGANTAR	2
Daftar Isi	3
Latar Belakang	4
BAB 1	5
PEMBAHASAN	5
A.PENGERTIAN MIKROTIK	5
B.SEJARAH MIKROTIK	5
C.JENIS-JENIS MIKROTIK	6
1. MikroTik RouterBOARD	6
2. MikroTik RouterOS	6
3. MikroTik CHR	7
D. CARA INSTAL PROGRAM MIKROTIK	7
E.KEPERLUAN YANG DI GUNAKAN DALAM MIKROTIK	7
1.Winbox	7
2.Kabel LAN	7
E.CARA INSTALASI MIKROTIK	7
F.KELEBIHAN DAN KEKURANGAN MIKROTIK	9
1.KELEBIHAN MIKROTIK	9
2.KEKURANGAN MIKROTIK	9
G.DOKUMENTASI	9
BAB 3	12
KESIMPULAN	12
DAFTAR PUSTAKA	13






Latar Belakang

Alasan kami menyusun  tugas ini adalah karena laporan ini di jadikan untuk kunci masuk lab sekaligus tugas laporan pertama “KONSENTRASI KEAHLIAN 01”.Tugas ini di berikan dengan maksud untuk mengetahui apasih mikrotik?
Kami memilih materi ini karena mikrotik sekarang menjadi salah satu alternatef dalam dunia IT. Mikrotik sendiri sekarang sudah banyak digunakan oleh ISP, provider hotspot, atau pemilik warnet. Mikrotik menjadi pilihan dalam jaringan internet karena mikrotik akan menjadikan computer router network yang handal dan dilengkapi dengan tools dan fitur-fitur yang cukup menjanjikan dalam pelayanan, mikrotik juga sangat cocok untuk beda jaringan yaitu wireless maupun jaringan kabel dan yang menjadi daya pengikatnya adalah sifatnya yang open source sehingga semua orang didunia dapat menggunakannya dan mengubahnya guna hal positif.
            Router sendiri merupakan elemen yang sangat penting dalam jaringan internet yang akan kita bangun, terutama dengan fungsinya sebagai pengatur koneksi data dari computer satu ke computer lainnya. computer yang mengatur jalur data tersebut sering kita sebut dengan router.
            Selain memiliki keunggulan yang telah disebutkan diatas masih ada kelebihan yang menjadi ujung tombak maraknya penggunaan mikrotik yaitu kebutuhan daya tamping data mikrotik sangatlah sempit ini disebabkan sifat dari mikrotik adalah DOS, pengoperasian cukup mudah untuk dilakukan, dan kebutuhan hardware yang cukup rendah.

 
BAB 1
PEMBAHASAN


A.PENGERTIAN MIKROTIK
MikroTik adalah sistem operasi yang digunakan untuk mengubah komputer menjadi sebuah router jaringan. Dengan software tersebut, Anda jadi bisa mengelola jaringan tanpa perangkat khusus.
Sistem operasi mikrotik adalah sistem operasi dan perangkat lunak yang dapat digunakan untuk menjadikan komputer manjadi router network yang handal, mencakup berbagai fitur yang dibuat untuk ip network dan jaringan wireless, cocok digunakan oleh ISP dan provider hotspot. dalah sistem operasi dan perangkat lunakdalah sistem operasi dan perangkat lunak yang dapat digunakan untuk menjadikan komputer manjadi router network yang handal, mencakup berbagai fitur yang dibuat untuk ip network dan jaringan wireless, cocok digunakan oleh ISP dan provider hotspot.
Jaringan adalah sekelompok sel yang mempunyai bentuk dan fungsi sama. Sementara, sebetulnya sel-sel yang menyusun tubuh makhluk hidup tidaklah selalu sama atau serupa. Setiap sel mempunyai bentuk dan fungsi yang berbeda dengan yang lain
Hotspot mikrotik ini sendiri adalah sebuah sistem yang digunakan untuk memberikan fitur autentikasi pada user yang akan menggunakan jaringan internet itu sendiri.
B.SEJARAH MIKROTIK
Mikrotik sendiri merupakan nama perusahaan kecil yang berkantor di pusat negara Latvia, dan  dibentuk oleh John Trully serta Arnis Riekstins. Sekitar tahun 1966, mereka berdua memulai  dengan sistem operasi Linux dan MS DOS dan dikombinasikan dengan teknologi berbasis  wireless (nirkabel) LAN atau WLAN Aeronet yang berkecepatan hingga 2 Mbps di Moldova. 
Ketika mereka sampai di Latvia, mereka mulai melayani lima pelanggannya. Mereka memiliki  keinginan kuat untuk membuat perangkat lunak Router yang handal, dan dapat disebarkan ke  seluruh dunia. Versi Linux yang pertama kali di gunakan oleh John dan Arnis adalah Linux  yang versi Kernel 2.2. 
Mereka berdua mengembangkan versi Linux tersebut dengan dibantu oleh 5 hingga 15 orang  staf R&D, sehingga sekarang Mikrotik sudah mendominasi dunia Routing untuk negara-negara  berkembang.
Sejak awal, Mikrotik hanya fokus untuk perusahaan jasa layanan internet (PJI) atau Internet  Service Provider (ISP) yang melayani jasa servis kepada pelanggannya dengan memakai  teknologi wireless atau nirkabel. Dalam sejarah Mikrotik, pada awalnya John dan Arnis ( sang  pendiri ) hanya ingin membangun software untuk Routing, sementara kebutuhan akan  perangkat keras juga terus berkembang. 
Oleh karena itu, akhirnya mereka membuat berbagai perangkat keras yang berhubungan  dengan software yang kemudian mereka kembangkan lebih lanjut. Keunggulan Mikrotik  berada pada perangkat lunak Routernya, karena terlihat mereka berjualan perangkat W-LAN  dengan antena omni.

C.JENIS-JENIS MIKROTIK
Terdapat tiga jenis MikroTik yang bisa Anda gunakan sesuai kebutuhan, yaitu:
1. MikroTik RouterBOARD
RouterBOARD MikroTik adalah perangkat router jaringan buatan MikroTik yang terdiri dari beberapa komponen, seperti RAM, ROM, dan prosesor.
MikroTik RouterBOARD dibekali dengan RouterOS,sehingga tidak memerlukan instalasi software dulu dan bisa langsung Anda gunakan.Tak hanya itu,harga RouterBOARD cukup terjangkau dibandingkan perangkat sejenis,mulai dari ratusan ribu Rupiah saja.
2. MikroTik RouterOS
RouterOS MikroTik adalah sistem operasi yang bisa digunakan sebagai router jaringan. Baik untuk dijalankan di MikroTik RouterBOARD, atau di komputer
Pengguna tidak perlu repot memilih perangkat komputer yang tepat untuk digunakan dengan RouterOS.Sebab,sistem operasi tersebut hanya membutuhkan RAM 32MB dan ruang penyimpanan sebesar 64MB..




3. MikroTik CHR
Jenis MikroTik ini berfungsi seperti RouterOS, tetapi diinstal di perangkat komputasi virtual, misalnya hosting Virtual Private Server atau VPS. Dengan menggunakan MikroTik CHR, Anda jadi bisa mengelola jaringan tanpa harus menyediakan perangkat sendiri.
Menariknya, MikroTik CHR tidak memerlukan lisensi, sehingga bisa Anda bisa menggunakannya dengan gratis. Namun, perlu Anda catat bahwa kecepatan maksimal jenis MikroTik ini dibatasi hingga 1MB/s per VPS.

D. CARA INSTAL PROGRAM MIKROTIK
Berikut adalah langkah-langkah untuk melakukan Netinstall Mikrotik, yaitu:
1.	Buka pengaturan Internet di Control Panel.
2.	Setting IP di koneksi Ethernet.
3.	Setting Netbooting.
4.	Ekstract dan buka Aplikasi Netinstall.
5.	Hubungkan Mikrotik.
6.	Pilih OS yang Ingin Diinstall.
7.	Lakukan Install.

E.KEPERLUAN YANG DI GUNAKAN DALAM MIKROTIK
1.Winbox
Winbox adalah salah satu aplikasi untuk konfigurasi Mikrotik RouterOS menggunakan GUI. Aplikasi Winbox bisa berjalan pada windows berbentuk portable binary, tapi bisa juga berjalan pada Linux dan MACOS (OSX) menggunakan Wine. Semua fungsi pada aplikasi Winbox hampir sama persis dengan fungsi konsol (command line).
2.Kabel LAN
Kabel pasangan berpilin/berbelit adalah sebuah bentuk kabel yang dua konduktornya digabungkan dengan tujuan untuk mengurangi atau meniadakan gangguan elektromagnetik dari luar seperti radiasi elektromagnetik dari kabel pasangan berbelit tak terlindung, dan wicara silang di antara pasangan kabel yang berdekatan.
E.CARA INSTALASI MIKROTIK

Berikut cara instalasi mikrotik :
•  Masuk ke winbox,klik 2x  tulisan C4.AD.34.B3.FB.58 (MAC Adress) lalu connect
 • Masuk ke IP > DHCP Client > Klik +,  di Interface pilih ehter 1 , centang semua opsi di bawahnya lalu ok dan apply.
•Tunggu sampai  ehter tersebut bound.
• Masuk ke IP>Address>klik + ,setting ip address di ether 2 dengan IP 192.168.12.1/24 klik apply lalu ok.
• Masuk ke IP>Dns masuk ke server dengan 8.8.8.8 dan 8.8.4.4 centang  Allow Remote Request klik apply lalu ok.
• Masuk ke IP>firewall>NAT>klik tanda +,di general lalu isi chain dengan scrnat,out interface isi dengan  ether 1 lalu masuk ke action  lalu isi action dengan masquerade.klik aplly lalu ok
•Masuk ke  IP>DHCP Server > DHCP Interface  lalu klik  DHCP setup  
Dhcp interface : ether 2,next
Dhcp address space : 192.168.12.0/24,next
Gateway for dhcp network : 192.168.12.1,next
Addresses to give out : 68.12.2-192.168.12.254,nextDns server : 192.168.1.1,next
Lease time :  00:10:00,next

Lalu muncul dialog setup has completed successfully klik ok
 • Setelah itu,buka  terminal lalu ketik ping google.com lalu enter,
• Setelah itu pc akan terkoneksi ke internet,jadi pastikan di sudut kanan sudah bergambar kotak putih,jika bergambar bola dunia cabut kabel di port dua lalu colok kembali dan tunggu.
                                                                        






F.KELEBIHAN DAN KEKURANGAN MIKROTIK
1.KELEBIHAN MIKROTIK
•	Memiliki banyak fitur canggih.
•	Tampilan program yang user friendly.
•	Tidak membutuhkan banyak tempat dan praktis.
•	Mendukung banyak model ethernet dan port jaringan.
•	Garansi terjamin apabila terjadi kerusakan pada RouterBoard.

2.KEKURANGAN MIKROTIK

•	Untuk penggunaan dalam skala besar perlu keahlian khusus. 
•	Slot ethernet yang cukup terbatas, sehingga perlu menambahnya dengan hub atau   switch. 
•	Kurang cocok digunakan untuk web proxy internal.

G.DOKUMENTASI
1.GAMBAR: https://drive.google.com/file/d/1BjEEOqM8uRcZqFSK6upFLd9ebCP0DYVt/view?usp=share_link
LOKASI : XI BUSANA 1
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : TIDAK TERHUBUNG
2.GAMBAR: https://drive.google.com/file/d/1U2Ygsh5bcwe2I62a51kMZP82hJFbyBGZ/view?usp=share_link
  LOKASI : KANTIN DEKAT X BG 2
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : TIDAK TERHUBUNG
3.GAMBAR: https://drive.google.com/file/d/1WKYwBZn17tbn0k9pyGi0YAMnfU5XCJmU/view?usp=share_link
   LOKASI : PARKIRAN
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : TIDAK TERHUBUNG
4.GAMBAR: https://drive.google.com/file/d/1QXKOZ8HMrW6yB0tacOj6HU2ycMolBYqm/view?usp=share_link
   LOKASI : XII BS 3
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : 1 BAR
5.GAMBAR: 
https://drive.google.com/file/d/1SzkhcdBuUn429m4IeAB-KPl1KwERQWtq/view?usp=share_link
LOKASI : MUSHOLAH
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : 1 BAR
6.GAMBAR: 
https://drive.google.com/file/d/1wfcvCDai9GnxUML1qQ556rB2sthb2Ryh/view?usp=share_   link
LOKASI : SANGGAR BUSANA
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : 1 BAR
7.GAMBAR: 
https://drive.google.com/file/d/1hh_797XfKX8S3YgaNoSGudn-lKs0MlRZ/view?usp=share_link
LOKASI : X TJKT
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : 2 BAR
8.GAMBAR: 
https://drive.google.com/file/d/1Zr73wQqIfOHL674932Tl7eTzl_dIg7GA/view?usp=share_link
LOKASI : PERPUSTAKAAN
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : 2 BAR
9.GAMBAR: 
https://drive.google.com/file/d/1iU5q7kbyrz4C0jY3PwVxdw8HIPUR_tJF/view?usp=share_link 
LOKASI : KAZEBO
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : 3 BAR
10.GAMBAR: 
https://drive.google.com/file/d/1wcQh3sRDwiHn3pfBignaYJbRXyMPeYV0/view?usp=share_link
LOKASI : KANTIN KAK RAHMA
TEMPAT MIKROTIK : LAB TKJ
JANGKAUAN SINYAL : 3 BAR

11.GAMBAR: 
https://drive.google.com/file/d/1wW9ZLR4WIaAJSPnDE_aUMh3AcbwUM8U4/view?usp=share_link
LOKASI : LAB TKJ
TEMPAT MIKROTIK : LAB TKJ
     JANGKAUAN SINYAL : 3 BAR


BAB 3
KESIMPULAN

Mikrotik RouterOS adalah sebuah mesin linux yang dirancang secara khusus untuk keperluan networking. Mikrotik ini begitu menarik saat ini, karena dengan fiturnya yang begitu lengkap serta kemudahan dalam penggunaanya dan juga harganya relatif lebih murah. Jika kita sudah memahami konsep jaringan dengan baik maka akan begitu mudah menerapkan di MikroTik dengan tool GUI-nya (winbox), sehingga kita tak perlu menghafal command untuk melakukan setting atau pengaturannya. Untuk negara berkembang, solusi MikroTik sangat membantu ISP atau perusahaan-perusahaan kecil yang ingin bergabung dengan internet. Walaupun sudah banyak tersedia perangkat router mini semacam NAT. MikroTik merupakan solusi terbaik dalam beberapa kondisi penggunaan komputer dan perangkat lunak. Mikrotik bisa disebut juga adalah salah satu distro linux yang berguna untuk jaringan komputer karena mikrotik sangat tangguh dalam masalah jaringan.
Dari dokumentasi kami semakin banyak dinding yang dilewati router makan kecepatan wifi akan melemah. Jarak antar router dengan perangkat yang digunakan terlalu jauh. Penyebab sinyal WiFi lemah tapi dekat bisa terjadi karena beberapa hal, misalnya saja perangkat yang digunakan tidak support pada jaringan WiFi, koneksi WiFi yang terganggu, hingga gangguan kabel WiFi pada tower pemancar utama. Material dinding yang tebal ternyata mampu menahan sinyal Wi-Fi sehingga koneksi internet akan terasa lambat. Mulai dari dinding berbahan beton, bata, marmer, plester, hingga semen merupakan jenis yang paling mengganggu koneksi Wi-Fi. 
DAFTAR PUSTAKA


http://septia-lutfi-1102412069-03.blogspot.com/2013/12/makalah-mikrotik.html
https://www.dewaweb.com/blog/apa-itu-mikrotik/
https://www.pinhome.id/blog/cara-netinstall-di-mikrotik/
http://sistem-komputer-s1.stekom.ac.id/informasi/baca/Apa-Itu-MikroTik-Pengertian- Kelebihan-dan-Fungsi-MikroTik/4b9cbc68e66e853c0b76063ae56dd94494f8cb1c
https://www.idn.id/sejarah-mikrotik-diciptakan/
https://inixindojogja.co.id/fungsi-mikrotik-pengelolaan-jaringan/
http://sistem-komputer-s1.stekom.ac.id/informasi/baca/Apa-Itu-MikroTik-Pengertian-Kelebihan-dan-Fungsi-MikroTik/4b9cbc68e66e853c0b76063ae56dd94494f8cb1c
