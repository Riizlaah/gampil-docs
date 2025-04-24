# Apa itu 'Gampil Framework'
Gampil Framework adalah framework php dengan struktur MVC yang sederhana dan ringan. Framework ini dirancang untuk memudahkan pengembangan aplikasi web dengan membungkus dan meringkas penulisan code pada saat pengembangan. dengan Gampil Framework, Anda dapat dengan cepat membangun aplikas web yang efisien dan sederhana, tanpa perlu konfigurasi yang rumit

# Fitur-Fitur
- **Sederhana dan Ringan** <br>Struktur folder yang mudah dipahami dan proses pengembangan yang tidak terlalu kompleks serta ukuran framework yang relatif kecil membuat `Gampil` menjadi sederhana dan ringan

- **MVC Yang Dipermudah** <br>`Gampil` dilengkapi dengan query builder yang ada di class `Model` dan juga memiliki templating engine yaitu `Pring`. untuk proses routing `Gampil` memakai array associative supaya lebih ringan

- **Dengan CLI** <br>`Gampil` juga dilengkapi dengan CLI yang berguna untuk membuat file controller, model, dan tabel, serta dapat menjalankan server lokal dengan server built-in PHP

# Keunggulan
- Ukurannya kurang dari 10 MB
- Dilengkapi dengan class berguna seperti CSRFToken, SessionManager, FileSystem.
- Menggunakan SQLite secara default agar tidak perlu menginstal driver tambahan
- `Model` yang dilengkapi query builder.
- `Pring` templating engine untuk mempercepat pembuatan view.

# Instalasi
1. Instal [composer](https://getcomposer.org/download/) jika belum ada.
2. Jalankan `composer create-project gampil/gampil (nama-folder)`
3. Tunggu proses instalasi selesai, kemudian mulailah mengoding.

# Apa Selanjutnya?
1. [Alur kerja framework ini](how-it-work.md)
2. [Format routing](routing.md)
4. [Controller](controller.md)
3. [View templating](view.md)
4. Request Handling
4. Model query builder
5. Tools-tools lain.
