# Intent
Intent adalah mekanisme untuk melakukan sebuah action dan komunikasi antar
komponen aplikasi misal activity, services, dan broadcast receiver. Ada tiga penggunaan umum
intent dalam aplikasi Android yaitu:
- [x] Memindahkan satu activity ke activity lain dengan atau tidak membawa data.
- [x] Menjalankan background service, misalnya melakukan sinkronisasi ke server dan menjalankan proses berulang (periodic/scheduler task).
- [x] Mengirimkan obyek broadcast ke aplikasi yang membutuhkan. Misal, ketika aplikasi membutuhkan proses menjalankan sebuah background service setiap kali aplikasi selesai 
melakukan booting. Aplikasi harus bisa menerima obyek broadcast yang dikirimkan oleh
sistem Android untuk event booting tersebut.
# Intent dibagi menjadi 2 yaitu :
- [x] Explicit Intent berfungsi untuk mengaktifkan komponen-komponen dalam satu aplikasi yang sama. Misalnya seperti : Berpindah Activity.
- [x] Implicit Intent berfungsi untuk memanggil fungsi activity yang sudah ada di fungsi internal android seperti Dial Number, Open Browser dan lainnya.
# Contoh Intent :
Dibawah ini merupakan contoh Explicit Intent yang mengaktifkan komponen lain dalam satu aplikasi dengan media button.

![AltText](https://github.com/najmi10/Intent-Send-Data/blob/master/ikiIntent.png)
![AltText](https://github.com/najmi10/Intent-Send-Data/blob/master/Intent2.png)
