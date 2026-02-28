Bagian index.html

Di bagian head saya namai dengan Uji Lampu Interaktif dan juga menyertaik link ke style.css nya yang nanti akan dibahas setelah index.html ini. Masuk ke bagian body saya menambahkan judul dengan h1 dan menggunakan hr sebagai garis pemisah agar lebih rapih. Kemudian masuk ke teks yang lebih kecil lagi dengan h3 itu memberi judul lampu dan juga meletakkan gambar on dan off lampu dengan id lampu1, dsb, dan juga dengan lebar 100.

Kemudian membuat button dengan p sebagai paragraf untuk teks instruksinya dan juga memanggil button dimana ada onclick yang nanti akan bersambung ke fungsi klikLampu yang dimana dinamai Lampu 1, dsb di button.

Untuk instruksi button kedua juga sama menggunakan p sebagai paragraf, dengan button dan onclick serta tersambung ke fungsi NyalaSemua atau MatiSemua.

Kemudian beralih ke rangkaian kedua, memasukkan gambar lampu yang dalam kondisi mati dengan id masing masing lampu A, B, C, dan D, serta width yang seragam yaitu 100.

Masuk ke button yang sama saja seperti penjelasan diatas, dimana button menggunakan onclick untuk tersambung ke fungsi pecetA, B, C, D serta SemuaHidup dan SemuaMati, serta pencetLampuAB dan pencetLampuCD.

Baru masuk ke fungsi, disini dimulai untuk fungsi klikLampu dimana pertama panggil dulu id diatas dan masukkan ke kondisi if ese. Di if menggunakan include untuk mengecek kondisi gambar yang terpakai, jika kondisi lampu off maka nilai true hidupkan, tapi jika nilai false yang dalam arti kondisi lampu sudah hidup maka kembalikan ke kondisi off, membuat fungsi tombol bisa bolak balik.

Untuk fungsi NyalaSemuaSoal1 tidak serumit fungsi sebelumnya, karena tidak perlu menggunakan fungsi if else dan cukup panggil saja id lampu dan dalam keadaan hidup, namun button ini tidak bisa bolak balik karena hanya akan membuat kondisi lampu tetap hidup walaupun kita klik berapa kali pun dan lampu yang semula hidup akan teteap hidup, begitu juga fungsi MatiSemua yang memanggil semua foto lampu ketika mati dan tidak akan membuat lampu hidup, jadi ketika lampu sudah dalam keadaan mati maka akan tetap mati dan jika hidup nanti akan mati.

Kemudian untuk fungsi pencetA, B, C, D dengan fungsi let dan memanggil id lampuA menjadi lA, dsb kemudian memanggil fungsi if dan juga includes untuk mengecek kondisi apabila lampu off maka true akan jadi on dan jika else atau kondisi false yang artinya lampu sudah dalam keadaan on maka false akan off.

Untuk funsgi SemuaHidup atau SemuaMati sama seperti di rangkaian satu, tidak perlu pakai if dan hanya cukup memanggil kondisi lampu sesuai dengan instruksi, apabila SemuaHidup maka panggil gambar kondisi on dan SemuaMati panggil kondisi lampu off.

Dan untuk fungsi terakhir di rangkaian kedua ini, yaitu pencetlampuAB atau CD, dimana pertama kita panggil dulu dengan nama baru dan panggil id yang dimaksud, selanjutnya dengan fungsi if dengan includes untuk mengecek kondisi kedua lampu AB atau CD apakah dalam keadaan off, jika true maka akan jadi on, dan jika false yang dalam arti lampu sudah dalam keadaan on maka akan mati, jadi buttonnya bisa bolak balik. Dan juga apabila diantara lampu sudah ada dalam keadaan hidup, maka fungsi akan membuat satu lampu yang hidup itu mati dahulu agar bisa dijalankan untuk pengecekan kondisi pertama, sehingga lampu di kondisi button ini itu seperti kembar yang pergerakan mereka itu selalu sama.


Bagian style.css
pertama itu diatur untuk bagian body, dimana diatur untuk layar yang di set 100 agar fit ke layar, kemudian bagian background dengan foto yang sudah dimasukkan ke dalam folder, yang diposisikan tengah, dan juga di set agar menutupi semuanya tanpa mengubah rasio gambar, terus tanpa perulangan gambar bg, dan membuat gambarnya terkunci agar tidak kemana mana, kemudian tata letaknya di atur block serta terletak di tengah, dengan memberi padding dan set margin ke 0 agar tidak ada celah dipinggir, yang juga terakhir di set font.

kemudian bagian h1 diatur warna, bg colornya, padding, radius border, ukuran font.

kemudian di img mengatur lampu agar berjejer ke samping dan membesar halus saat disentuh kursor.

kemudian di button membuat tombol terlihat timbul dengan bayangan dan berubah warna saat didekati kursor.

untuk h3 dan p diatur bayangan hitam pada tulisan putih agar mudah dibaca di atas gambar latar.

dan yang terakhir hr menampilkan garis tipis pendek di tengah sebagai pembatas antar bagian.
