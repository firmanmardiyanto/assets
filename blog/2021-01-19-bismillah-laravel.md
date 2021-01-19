---
slug: bismillah-laravel
title: Kenalan dan install Laravel
author: Firman Mardiyanto
author_title: Enthusiast Programmer
author_url: /
author_image_url: /img/firman.jpg
tags: [laravel, php]
---

### Tabel of Contents

- [Bissmillah](#bissmillah)
- [Laravel itu apa? dan kenapa Laravel?](#laravel-itu-apa-dan-kenapa-laravel)
- [Cara install Laravel](#cara-install-laravel)

## Bissmillah

Baik, ini mungkin jadi postingan pertama saya, `setelah welcome`. Hehe. Kali ini kita akan belajar dari awal tetang Laravel. semoga kedepanya saya dapat berkomitmen untuk kupas minimal menuju ke tuntas pemogramman web menggunakan laravel. Semangat, semangat.

_Semua praktikum yang saya lakukan mengunakan window, dan xampp, namun untuk run menggunakan artisan command. Diansumsikan bahwa teman-teman sudah mengenal php, xampp, query, dan composer, dan doakan supaya kedepanya bisa lebih baik lagi. Teman-teman juga dapat ikut memperbaiki setiap postingan dalam web ini dengan mengklik Edit this page pada setiap postingan-postingan saya :)_

## Laravel itu apa? dan kenapa Laravel?

Kalau kalian nanya ke saya, saya akan menjawab. Laravel adalah framework atau kerangka kerja php yang sangat popular.

Dan kata laravelnya begini :

_`Laravel is a web application framework with expressive, elegant syntax. We’ve already laid the foundation — freeing you to create without sweating the small things.`_

yang kalau diterjemahkan dengan Google Translate jadi begini :

_`Laravel adalah kerangka aplikasi web dengan sintaks yang ekspresif dan elegan. Kami telah meletakkan fondasinya - membebaskan Anda untuk berkreasi tanpa membuat repot hal-hal kecil.`_

Dari terjemahan sudah jelas ya, dari situ kita bisa mengartikan bahwa laravel adalah fondasi kerangka kerja aplikasi web. Disitu juga ada kata **membebaskan dari hal-hal kecil** ? dimana kita tidak perlu melakukan konfigurasi manual untuk hal-hal penting dalam membangun web, seperti contohnya konfigurasi database.

Dan untuk pertanyaan kenapa laravel? Saya pikir teman-teman semua sudah tau makanya mengunjungi postingan ini. Namun dari saya sendiri, alasanya simpel. _Karena Laravel adalah Framework PHP yang Popular_.

Jadi kelebihan dari kita mempelajari sebuah framework yang popular adalah karena sudah banyak pengguna yang pakai, jadi semakin mudah juga untuk kita menemukan solusi jika kita menemui masalah. Tapi saya tidak bilang belajar yang tidak popular juga salah ya.

Baik kita lanjut ke cara meninstall laravel.

## Cara install Laravel

Disini kita akan mengunakan composer untuk menginstall laravel, untuk menggunakan tool ini, teman-teman hanya tinggal menggunakan perintah ini pada cmd atau powershell dalam direktori yang diinginkan teman-teman :

```bash
composer create-project laravel/laravel namaProjectNya
```

Sebagai contoh kali ini kita akan membuat project dengan nama belajar_laravel pada directory Desktop, teman-teman hanya tinggal alt + shift + Klik kanan pada direktorinya, pilih buka jendela command baik powershell maupun cmd disini dan jalankan perintah :

```bash
composer create-project laravel/laravel belajar_laravel
```

Dengan begitu secara otomatis
