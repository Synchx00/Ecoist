# Ecoist

## Link Heroku
https://ecoist.herokuapp.com/

## Anggota

* Azmi Rahmadisha
* Bryan Tjandra
* Mazaya Nur Labiba
* Roy Maruli Tua Nababan
* Son Sulung Suryahatta Asnan

## Main Idea

Donasi dan kampanye penanaman pohon

## Deskripsi / Manfaat

Situs Ecoist adalah situs yang bertujuan untuk menyebarkan kesadaran kepada masyarakat tentang pentingnya penghijauan hutan di Indonesia. Situs Ecoist memberikan ruang bagi masyarakat untuk berpartisipasi dalam kegiatan donasi pohon dan menyebarluaskan campaign-campaign terkait penghijauan hutan yang tersedia. Melalui aplikasi ini, masyarakat dapat sadar dan turut prihatin tentang isu penghijauan hutan di Indonesia.


## Modul / Pages
1. Register - Bryan

    <img src="https://user-images.githubusercontent.com/88226713/195610008-4c8a547f-1617-4cd4-9130-0aa929dbf7d4.png" width="400" height="300"/>
    
    Register berisi form untuk membuat akun agar user dapat melakukan kegiatan dalam website. 

2. Log In & Log Out - Bryan 
    
    <img src="https://user-images.githubusercontent.com/88226713/195610461-97e441a9-3e48-4d44-b027-a0c008fdcc3c.png" width="400" height="300"/>
    
    Login dan logout berisi form untuk mengautentikasi dan membedakan antara user dan admin. Menggunakan modal untuk regist , kemudian menggunakan AJAX  POST & GET. 

3. Home Page - Roy
    
    <img src="https://user-images.githubusercontent.com/88226713/195620247-bfdba618-59b4-4bfb-a84c-166358712622.png" width="400" height="600"/>

    Merupakan page yang akan ditampilkan saat awal orang memasuki website. Melalui page ini orang dapat di-redirect menuju page lainnya sesuai kebutuhan. Dalam page ini berisi deskripsi website, perkenalan tim pembuat web, serta form FAQ (menggunakan AJAX POST) jika pengunjung ingin memberikan masukan. Dalam laman ini, akan ditampilkan jumlah kampanye yang telah dibuat, bagian ini akan menggunakan AJAX GET.

4. Create Campaign - Hatta

    <img src="https://user-images.githubusercontent.com/88226713/195621002-07959dd1-f09f-4e04-a396-45c221617061.png" width="400" height="200"/>

    Sebuah modal yang berisi form untuk mendaftarkan campaign. Di sini akan dilakukan implementasi AJAX GET

5. Campaign list - Hatta

    <img src="https://user-images.githubusercontent.com/88226713/195621319-13369e97-fd98-49d0-809d-b29a7898aab2.png" width="400" height="200"/>
    
    Berisi campaign-campaign yang dibuat oleh user. Di sini akan dilakukan implementasi AJAX POST dan AJAX GET

6. Join Campaign - Adish
    
    <img width="400" height="280" src="https://user-images.githubusercontent.com/88226713/195621494-74cff58c-d1c2-4569-8d95-6ae0e91a365d.png">

    Fitur ini digunakan untuk user yang ingin mengikuti kampanye. User dapat mengisi form yang terdaftar untuk join campaign menanam/membersihkan hutan. Ketika user submit, akan dilakukan AJAX post berupa kampanye berhasil diikuti dan detail kampanye.

7. Donate - Maza 

    <img width="400" height="410" src="https://user-images.githubusercontent.com/88226713/195622069-bec43f0c-231f-44b8-ad13-e4aea9be471c.jpg">

    Ini adalah fitur donasi untuk memfasilitasi user yang sudah login untuk berdonasi. Terdapat form untuk memasukkan input nominal donasi, jumlah pohon yang ingin didonasikan, dan catatan/pesan untuk kami serta tombol submit untuk menginput donasi. Ketika user ingin men-submit donasi, maka tombol submit tersebut akan menggunakan AJAX POST untuk menginput data yang dimasukkan user ke dalam database. Jika user belum login, maka akan di redirect ke halaman login terlebih dahulu.

8. Admin Features - Bryan

    <img width="400" height="300" src="https://user-images.githubusercontent.com/88226713/195622602-8f00c778-6eed-4d1b-a737-5100a663aaa6.png">

    Merupakan fitur / web yang khusus bisa diakses oleh admin. Fitur yang khusus ini dapat digunakan untuk melihat data tentang user. Misalnya, melihat dashboard pageview dan click, total donasi yang ada, dan total campaign yang telah diikuti.



## Role Peran Pengguna
1. User

    User memiliki otoritas untuk mengakses welcome page, membuat dan berpartisipasi dalam campaign, serta melakukan donasi. 

2. Admin

    Admin atau administrator berperan sebagai pemegang kendali website dan memiliki akses penuh untuk melihat user database melalui dashboard admin. 


