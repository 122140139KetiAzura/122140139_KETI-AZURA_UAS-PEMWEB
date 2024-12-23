**1. Manipulasi DOM dengan Java Script**
Tujuan manipulasi DOM dengan JavaScript pada form input adalah untuk meningkatkan **interaktivitas**, **responsivitas**, dan **kemudahan penggunaan** pada form. Dengan manipulasi DOM, form dapat:
1) *Menyesuaikan Tampilan dan Fungsi Secara Dinamis*
   Misalnya, menambah atau menghapus elemen form berdasarkan tindakan pengguna.

2. *Memvalidasi Input Secara Real-Time* 
   Memastikan data yang dimasukkan valid sebelum dikirim ke server, sehingga mengurangi kesalahan input.

3. *Menyediakan Umpan Balik Langsung*
   Memberikan pesan error atau konfirmasi langsung setelah pengguna mengisi form.

4. *Mengotomatisasi Proses*
   Misalnya, mengisi nilai default atau melakukan kalkulasi otomatis berdasarkan input.

**2. Event handling**
Tujuan event handling pada form input adalah untuk merespons interaksi pengguna secara langsung, memvalidasi data, memberikan umpan balik real-time, mengotomatisasi proses, dan meningkatkan pengalaman pengguna dengan membuat form lebih interaktif dan responsif.

**3. Server-Side Programing**
Server-side programming adalah pemrograman yang dijalankan di sisi server untuk menangani permintaan klien, seperti pengelolaan data, validasi, dan penyimpanan ke database. PHP adalah salah satu bahasa yang umum digunakan untuk ini.
1)*pengelolaan data dengan PHP*
Dalam pengelolaan data dengan PHP, data dikirim dari klien (browser) ke server menggunakan metode HTTP POST atau GET:
- metode Post
   .> Data dikirim melalui body HTTP, sehingga tidak terlihat di URL.
   .> Digunakan untuk data sensitif (password, form pendaftaran).
- Metode Get
   .> Data dikirim melalui URL (query string), sehingga terlihat di URL.
   .> Cocok untuk data tidak sensitif atau pencarian (search).
2) *Objek PHP berbasis OOP*
**Objek PHP berbasis OOP (Object-Oriented Programming)** adalah pendekatan pemrograman yang berfokus pada penggunaan kelas dan objek untuk membuat aplikasi yang lebih modular dan terstruktur. Kelas adalah blueprint atau cetakan yang mendefinisikan properti (atribut) dan metode (fungsi) yang dapat digunakan oleh objek. Objek adalah instansiasi dari kelas yang memiliki data dan fungsi sesuai dengan definisi dalam kelas tersebut. Dalam OOP, visibilitas digunakan untuk mengatur aksesibilitas properti dan metode, seperti `public`, `protected`, dan `private`. Constructor adalah metode khusus yang otomatis dijalankan ketika sebuah objek dibuat, memudahkan inisialisasi data awal. OOP juga mendukung pewarisan (inheritance), yang memungkinkan satu kelas mewarisi properti dan metode dari kelas lain, serta polimorfisme (polymorphism), yang memungkinkan metode dengan nama yang sama memiliki perilaku berbeda di kelas turunan. Dengan OOP, pengelolaan kode menjadi lebih efisien, reusable, dan mudah untuk dikembangkan dalam skala besar.

**4. Database Management**
1) *Pembuatan tabel database*
   Pembuatan tabel database adalah proses mendefinisikan struktur tabel di dalam database untuk menyimpan data. Tabel terdiri dari kolom dengan tipe data tertentu, seperti      INT, VARCHAR, atau DATE. Setiap kolom mendeskripsikan atribut dari data, seperti ID, nama, atau tanggal. Proses ini biasanya dilakukan menggunakan perintah SQL seperti       CREATE TABLE.
2) *Konfigurasi koneksi database*
   Konfigurasi koneksi database adalah langkah menghubungkan aplikasi ke database agar dapat mengakses dan mengelola data. Ini melibatkan pengaturan host database, nama         database, username, password, dan port. Dalam PHP, koneksi sering dilakukan menggunakan ekstensi seperti mysqli atau PDO. Tujuan utamanya adalah memastikan aplikasi dapat    membaca, menulis, dan memproses data dari database.
   
**5. State Management**
1) _state statement dengan session_
   State management dengan session digunakan untuk menyimpan data pengguna sementara di sisi server selama sesi pengguna aktif di aplikasi web. Session memungkinkan aplikasi    untuk melacak aktivitas pengguna, seperti login, tanpa perlu menyimpan data di browser. Data disimpan dalam sesi server dengan ID yang dikirimkan melalui cookie. Session    berguna untuk mengelola informasi sensitif dan memastikan data tetap ada selama sesi berlangsung.
2) _Pengelolaan State dengan Cookie dan Browser Storage_
   Pengelolaan state dengan cookie dan browser storage berfokus pada penyimpanan data di sisi klien (browser).
   - Cookie adalah file kecil yang disimpan di browser dan digunakan untuk menyimpan informasi seperti preferensi pengguna, status login, atau tracking data. Cookie memiliki      batasan ukuran dan masa berlaku yang dapat disesuaikan.
   - Browser Storage terbagi menjadi dua jenis:
      - Local Storage: Menyimpan data dalam jangka panjang (permanen sampai dihapus oleh pengguna), berguna untuk menyimpan data yang tidak sensitif.
      - Session Storage: Menyimpan data hanya selama sesi browser terbuka. Data akan hilang ketika tab atau browser ditutup.


