# MVC

MVC (Model-View-Controller) adalah pola arsitektur perangkat lunak yang membagi aplikasi menjadi tiga komponen utama: Model (data dan logika bisnis), View (tampilan antarmuka pengguna/GUI), dan Controller (penghubung antara Model dan View) untuk membuat kode lebih terstruktur, mudah dikelola, diuji, dan dikembangkan, terutama untuk aplikasi web

Komponen MVC
Model: Mengelola data aplikasi dan logika bisnis (aturan-aturan yang mengatur data). Bertanggung jawab untuk mengambil, menyimpan, dan memanipulasi data, biasanya berinteraksi langsung dengan database.
View: Bertanggung jawab untuk menampilkan informasi kepada pengguna dalam bentuk antarmuka (GUI). Ini adalah bagian yang dilihat dan digunakan oleh pengguna.
Controller: Bertindak sebagai perantara yang menerima input dari pengguna (melalui View), kemudian menginstruksikan Model untuk mengambil atau memodifikasi data, dan terakhir memilih View mana yang akan ditampilkan. 

Manfaat MVC
Pemisahan Tanggung Jawab (Separation of Concerns): Memisahkan logika data, logika bisnis, dan tampilan, sehingga memudahkan pengelolaan kode.
Pengembangan Lebih Cepat: Memungkinkan tim bekerja secara paralel pada bagian yang berbeda (misalnya, satu orang fokus pada data, yang lain pada tampilan).
Pemeliharaan Lebih Mudah: Perubahan pada tampilan tidak memengaruhi logika data, begitu juga sebaliknya.
Pengujian Lebih Baik: Setiap komponen dapat diuji secara independen. 

Contoh Penggunaan
MVC banyak digunakan dalam framework pengembangan web populer seperti Laravel, CodeIgniter, dan Symfony. 
