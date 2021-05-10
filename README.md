# API
adalah singkatan dari Application Programming Interface yaitu sebuah software
yang memungkinkan para developer untuk mengintegrasikan dan mengizinkan dua aplikasi yang
berbeda secara bersamaan untuk saling terhubung satu sama lain.

# Rest API
merupakan salah satu dari desain arsitektur yang terdapat di dalam API itu
sendiri. Dan cara kerja dari RESTful API yaitu REST client akan Melakukan akses pada
data/resource pada REST server dimana masing-masing resource. Atau data/resource tersebut
akan dibedakan oleh sebuah global ID atau URIs (Universal Resource Identifiers).
Jadi, Nantinya data yang diberikan oleh REST server itu bisa berupa format text, JSON atau
XML. Dan saat ini format yang paling populer dan paling banyak digunakan adalah format
JSON.

## Metode  HTTP yang digunakan Rest API
- [x] GET, berfungsi untuk membaca data/resource dari REST server
- [x] POST, berfungsi untuk membuat sebuah data/resource baru di REST server
- [x] PUT, berfungsi untuk memperbaharui data/resource di REST server
- [x] DELETE, berfungsi untuk menghapus data/resource dari REST serve
- [x] OPTIONS, berfungsi untuk mendapatkan operasi yang disupport pada resource dari REST server

# Perbedaan Retrofit dan Volley
- [x] Retrofit : 
Retrofit ini merupakan Library turunan dari OkHTTP yang dibuat oleh Square yang digunakan sebagai REST Client pada Android, 
yang pasti akan memudahkan kita. Karena kita tidak perlu lagi untuk membuat Method sendiri untuk menggunakan REST Client API dari Backend. 
Library ini menyediakan framework yang powerfull untuk authenticating dan berinteraksi dengan API dengan mengirimkan request menggunakan OkHTTP.
retrofit juga mendukung berbagai macam format authentikasi via http, menambahkan header pada request,
menambahkan parameter serta mengirim data berupa image ke server.

- [x] Volley :
Volley adalah library HTTP yang mempermudah dan yang terpenting mempercepat networking untuk aplikasi Android. Tetapi Library buatan Google ini
kurang populer dibanding kedua Library sebelumnya, karena fitur yang dimilikinya pun sedikit. Secara default, Volley menggunakan metode sinkronisas Jadi 
kalian tidak perlu membuat sebuah Method atau fungsi yang menggunake Class Asynctask. Dalam penggunaannya memang 'sedikit' sulit.
Volley tidak cocok untuk operasi download atau streaming yang besar karena Volley menyimpan semua respons dalam memori selama mengambil data API.

# Hasil
![d1](https://user-images.githubusercontent.com/63852448/117602522-1963d980-b17b-11eb-826e-9f268c83a4a4.jpg)
![d2](https://user-images.githubusercontent.com/63852448/117602527-1bc63380-b17b-11eb-9723-97f623d30882.jpg)
