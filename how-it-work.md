# Pemahaman singkat tentang MVC
MVC atau Model View Controller secara singkat adalah pola desain arsitektur yang memisahkan aplikasi menjadi tiga komponen utama: Model (logika data), View (tampilan antarmuka pengguna), dan Controller (penghubung antara Model dan View untuk mengelola alur aplikasi).

# Bagaimana Framework ini bekerja
Bayangkan ada sebuah request, yang terjadi ialah:
1. Request diterima oleh `Core` atau Inti, kemudian akan dicari route yang sesuai dengan request. Jika ada, maka request akan diteruskan ke controller yang dipasangkan dengan route tersebut. Jika route yang diminta tidak ada, maka akan muncul halaman 404.
2. Setelah request diterima oleh controller, controller akan menjalankan method tertentu yang nantinya akan menjadi sebuah view/response code/redirect.
3. Jika di dalam method tersebut ada view, maka `Pring` akan 'me-render' view tersebut.
4. Jika di dalam method tersebut ada model, maka `Model` tersebut akan mencoba terhubung ke database sesuai pengaturan yang ada, lalu `Model` akan mengolah method-method query builder menjadi sebuah query yang akan dieksekusi. Setelah dieksekusi, `Model` akan mengembalikan hasilnya.

<br><br>

[Selanjutnya](routing.md)