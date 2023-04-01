---
title: 'Method .json()'
date: '2023-01-01'
---

json() adalah metode bawaan (built-in method) dari objek Response pada JavaScript. Metode ini digunakan untuk mengembalikan respons dari permintaan HTTP dalam bentuk objek JavaScript yang dapat digunakan di dalam kode.

Cara kerja dari metode json() adalah sebagai berikut:

    Saat permintaan HTTP telah selesai dilakukan, response akan mengandung data mentah dalam format string, yang dapat diterjemahkan menjadi objek JavaScript.

    Metode json() digunakan untuk mengekstrak dan mengembalikan respons dari response dalam bentuk objek JavaScript.

    Metode json() mengembalikan sebuah Promise yang kemudian dapat diolah menggunakan then() atau await.