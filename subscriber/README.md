# REFLEKSI MODUL 9
## What is amqp?
AMQP (Advanced Message Queuing Protocol) adalah protokol standar terbuka untuk pengiriman pesan antar aplikasi atau
middleware. Protokol ini memungkinkan pengirim (publisher) dan penerima (subscriber) berkomunikasi melalui perantara
yang disebut message broker (dalam hal ini RabbitMQ), meskipun aplikasi-aplikasi tersebut dibangun dengan teknologi atau
bahasa pemrograman yang berbeda. AMQP mengatur bagaimana pesan dikirim, diarahkan melalui antrean (queue), dan
dipastikan sampai ke tujuannya dengan aman.
## What does it mean? guest:guest@localhost:5672 , what is the fi rst guest, and what is the second guest, and what is localhost:5672 is for?
guest:guest@localhost:5672 merupakan URL koneksi yang digunakan aplikasi untuk terhubung ke RabbitMQ. Komponen-komponen
dari string tersebut terdiri dari guest pertama yang merupakan Username default untuk mengakses RabbitMQ, guest kedua
yang merupakan Password default yang digunakan bersama dengan username tersebut, localhost:5672 yang menunjukkan alamat
Host atau lokasi di mana server RabbitMQ berjalan dengan nomor Port 5672 yang digunakan oleh RabbitMQ untuk mendengarkan
komunikasi data melalui protokol AMQP.
