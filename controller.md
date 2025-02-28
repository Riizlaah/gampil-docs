# Controller

Controller adalah bagian yang mengatur view dan model. Di Controller juga sebagian besar logika aplikasi berjalan.

## Cara Menambahkan Controller

Anda bisa mengetik perintah berikut di folder projek gampil bagian awal.
<br><br>
`php gampil create controller (nama controller)`
> Ingat: nama controller hanya bisa diawali dengan _ atau a-z dan diakhiri dengan _ atau a-z atau 0-9

## Method-Method
1. `view($view_name, $datas, $extend)`<br>
function `view()` menerima beberapa parameter. Yaitu:
    1. `$view_name` : lokasi file view secara relatif dari `resources/views`.
    2. `$datas`: array associative yang akan diekstrak. (mengubah setiap key-value menjadi variable di dalam view)
    3. `$extend`: lokasi file view yang akan di extend atau view template yang sebagian isinya ( di bagian `@content`) menjadi view dari `$view_name`
2. `model($model_name)`<br>
function `model()` menerima beberapa parameter. Yaitu:
    1. `$model_name` : nama model yang akan dipakai / di-return. Akan dipelajari lebih lanjut di bagian Model

## Property
1. `$rhand` : singkatan dari RequestHandler, akan dipelajari nanti di bagian input & request handling

