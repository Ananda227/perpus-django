**Nama    : Ananda Fajriansyah**
**NIM     : 20.01.013.044**
**Matkul  : Pemrograman Mobile**

Django merupakan salah satu web framework yang menggunakan bahasa pemrograman python, django berbasis MVT adalah kependekan dari Model, View, dan Template. 
pengertian dari MTV adalah sebagai berikut :
1. Model, merupakan bagian yang berfungsi untuk melakukan iteraksi dengan basis data.
2. View, merupakan bagian yang memuat logika biasanya digunakan untuk mengolah data dari model kemudian dapat dikirimkan ke dalam Template.
3. Template, merupakan bagian yang berfungsi untuk mengatur tampilan dalam bentuk XML atau HTML

peralatan yang dibutuhkan untuk memulai project django sebagai berikut:
1. Terminal
2. Teks editor
3. Web browser
4. Bahasa pemrograman python

langkah-langkah membuat project django :
1. Buka terminal 
2. ketikan cd desktop/, ini bertujuan untuk menyimpan project ke halaman desktop
3. Ketikan django-admin startproject perpus, ini adalah perintah untuk membuat project django baru dengan nama project perpus
4. Masuk ke folder perpus yang dibuat, kerikan cd perpus untuk melakukannya
5. Jalankan server nya untuk melihat apakah django sudah berhasil terinstall, caranya ketikan "python manage.py runserver" pada terminal
6. Masuk ke web browser dan salin link localhost pada terminal ke dalam web browser untuk melihat hasilnya
7. Kemudian untuk melanjutkan project seperti mengedit tampilan, membuat model, view, dll sebagainya dilakukan didalam teks editor

Routing 
sama seperti pada framework lainnya kita juga bisa melakukan routing pada django, contoh sederhananya, Client memberikan Request untuk mengakses Halaman Buku pada Server Django namun PAGE NOT FOUND. Karena URL Buku yang di Request belum ada di Server. Untuk dapat melayani Request dari Client, harus dibuatkan URL baruJika sudah, maka Request dari Client akan dapat terpenuhi

Apps
Jika pada framework lain folder apps sudah tersedia dan kita tinggal mengotak-atiknya, pada django kita harus membuatnya secara otomatis dengan mengetikkan perintah pada terminal "django-admin startapp namaApp"

View 
merupakan tampilan halaman yang akan ditampilkan pada web browser kita yang berisikan file-file HTML

Template
digunakan untuk mempermudah dalam membuat view dengan memisahkan bagian-bagian file html ke sebuah file baru dengan format html. File ini nantinya dapat digunakan berkali-kali dengan melakukan extend, sehingga mempersingkat penulisan script html

Static folder 
folder ini adalah tempat untuk kita menyimpan file css, java script dan gambar

Model 
Models merupakan definitive dari database atau representasi tabel pada database. Dengan menggunakan models ini, kita tidak perlu lagi menggunakan Query SQL untuk membuat tabel di database. Ketika melakukan Migrasi pada model buku, maka Django akan melakukan Create Tabel Buku sesuai dengan field – field yang ada pada model buku ini. Maka jadilah Tabel pada Database yaitu Tabel Buku.

Django admin
Django Admin merupakan salah satu fitur yang powerfull yang ada pada Django. Dikatakan Powerfull karena dapat melakukan CRUD sederhana untuk mengelola data pada model yang kita buat. Model – Model yang kita buat akan ditambahkan kedalam Django Admin. Django admin ini bersifat Private karena diperlukan Login terlebih dahulu untuk dapat mengakses nya.

Virtual environment
Pada tahap ini akan membahas tentang virtual environment atau lingkungan virtual, dalam kasus ini lingkungan virtual berguna untuk mengisolasi projek yang kita buat. Setiap kita membuat projek didalam lingkungan virtual ini, projek tersebut akan terisolasi dari direktori system dan memiliki paket python sendiri yang terinstal di lingkugan virtual tersebut.

Deployment
Pada tahap ini, kita akan mendeploymen aplikasi yang telah dibuat ke server. Dengan awalan mengcoding di local kemudian mengupload ke github setelah itu di clon atau ditarik ke computer server untuk dideploy disana. 
