# UAS ERD

01. Seorang mahasiswa ingin membuat sebuah aplikasi todo app dimana dengan menggunakan aplikasi ini mahasiswa tersebut dapat melakukan management terhadap tugas tugas yang harus dilaukaannya dalam sebuah aplikasi web.
Aplikasi ini mengharuskan user melakukan login dengan menggunakan username dan password, username pada aplikasi ini harus unique dan tidakboleh sama dengan username dari user lain. password pada aplikasi ini harus di enkripsi dan memiliki panjang minimal 8 karakter terdiri dari angka dan huruf serta minimal satu simbol.
seorang user boleh membuat banyak todo item setiap todo item memiliki todo item id yang unik serta mempunyai task description yang berupa text panjang serta memiliki attribut attribut ini harus dipilih salah satu di antara 3 status yaitu “planned”,“ongoing”, dan “done”.
Sebelum membuat sebuah todo user harus membuat minimal satu atau lebih category, kategory ini mempunyai category id yang unik dan info mengenai category name yang memiliki panjang minimal 5 karakter dan maksimal 20 karakter.
Sebuah category dapat digunakan pada banyak todo item dan satu todo item wajib memiliki satu kategory, tidak ada todo item yang tidak memiliki kategori.

# Konsep ERD nya
![Screenshot 2024-06-15 114545](https://github.com/Fanzirfan27/Learn_MyPHP-Admin/assets/160199038/fd2655da-554f-423a-b71e-e82375c60ae4)

02. Seorang content creator membutuhkan bantuan anda untuk membuatkan platform publikasi kontent kontennya.
Platform ini berbentuk sebuah website dimana konten creator tersebut dapat mempublikasikan karya karyanya dalam bentuk sebuah berita secara online di internet.
Untuk masuk ke sistem berita online ini seorang user harus melakukan login dengan menggunakan email dan password yang sudah di tentukan sebelumnya. selain nama dan password perlu juga diketahui nama user untuk ditampilkan pada halaman profile nya serta ditambahkan pencatatan kapan tanggal daftar dan kapan tanggal login terakhir dari user tersebut, selain itu user juga memiliki user id yang unik untuk membedakan user yang satu dengan yang lain. User boleh memiliki nama yang sama tetapi tidak boleh memiliki email yang sama.
Seorang user diperbolehkan menulis banyak berita dimana sebuah berita memiliki judul dan isi berita, judul berita berupa sebuah text yang panjang maksimalnya 255 karakter serta isi berita merupakan sebuah text yang panjang nya bebas sesuai kebutuhan. Selain judul dan isi berita juga perlu diberikan informasi mengenai tanggal berita dimana tanggal tersebut berisi tanggal kapan ditulisnya berita. Tentu saja berita memiliki id berita yang unik untuk membedakan satu berita dengan berita lainnya.
Untuk mempermudah seorang pembaca berita membaca dan menavigasikan berita berita berita ini dikelompokkan dalam sebuah kategori, sebuah berita hanya boleh memiliki satu kategori tetapi sebuah kategori boleh dipakai pada lebih dari satu berita.
Data yang disimpan pada kategori adalah nama kategori yang berupa sebuah text panjang yang maksimal 100 karakter dan sebuah category id yang unik.
Selain menggunakan kategori sebuah berita juga dapat dikelompokkan berdasarkan sebuah tag/topik dimana sebuah berita boleh mempunyai banyak tag dan sebuah tag dapat dipasang pada lebih dari satu berita. Data yang disimpan pada tag adalah isi tag yang panjangnya maksimal 20 karakter dan id tag yang unik.
Untuk mempermudah interaksi antara pembaca dan penulis di sistem berita ini setiap berita yang dibuat dapat diberi komentar sebuah berita dapat dikomentari lebih dari satu kali oleh pembaca data yang dicatat pada komentar adalah komentar id komentar id ini bersifat unik kemudian isi komentar berupa text panjang maksimal 255 karakter nama pemberi komentar dan email pemberi komentar email harus dalam format email yang benar serta dicatat juga tanggal komentarnya.

# Konsep ERD nya
![Screenshot 2024-06-15 115200](https://github.com/Fanzirfan27/Learn_MyPHP-Admin/assets/160199038/e5a11026-99f1-4fe5-850c-bfafafbbaa69)
![Screenshot 2024-06-15 115244](https://github.com/Fanzirfan27/Learn_MyPHP-Admin/assets/160199038/82e63e7f-8d5d-4dd0-8bd4-862448842c0c)

03. Sebuah perusahaan ingin membuat aplikasi ramalan cuaca, aplikasi ini mewajibkan usernya untuk login menggunakan username dan password, user juga wajib memiliki user id yang unik untuk setiap usernya selain itu username harus unik dan tidak boleh ada user yang memiliki username yang sama.
Untuk melihat prakiraan cuaca seorang user dapat menambahkan minimal satu atau lebih kota yang ingin dilihat prakiraan cuacanya. Di aplikasi ini suatu kota juga dapat ditambahkan oleh user lain yang ingin mengetahui prakiraan cuaca di kota tersebut.
Kota memiliki identifier yang unik bernama kota id, kota id tidak boleh sama antara satu kota dengan kota lain kota juga menyimpan informasi mengenai nama kota yang berisi text dengan maksimal panjang karakter 50.
Sebuah kota terkelompokkan dalam sebuah negara dimana sebuah negara memiliki beberapa kota. data yang diperlukan untuk negara adalah negara id yang bersifat unik dan nama negara yang berisi text dengan maksimal panjang karakter 55.
sebuah kota dapat memiliki banyak prakiraan cuaca, dimana prakiraan cuaca ini disimpan dengan data prakiraan id yang unik, tanggal prakiraan cuaca, temperatur terendah dan temperatur tertinggi.
Setiap prakiraan cuaca memiliki maksimal satu kondisi cuaca dimana kondisi cuaca ini bersifat dinamis dapat ditambahkan secara mandiri oleh admin aplikasi, kondisi cuaca memiliki kondisi id yang bersifat unik dan nama kondisi yang berupa sebuah text dengan panjang maksimal 30 karakter. Kondisi cuaca ini dapat dipakai oleh lebih dari satu prakiraan cuaca.

# Konsep ERD nya
![Screenshot 2024-06-15 115720](https://github.com/Fanzirfan27/Learn_MyPHP-Admin/assets/160199038/42ea58f9-52bf-4a36-b8a1-3c1c039ee0eb)
