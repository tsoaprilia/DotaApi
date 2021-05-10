# Dota Api Project
## Splash Screen
Splash screen adalah istilah yang diberikan pada layar pembuka setiap kali kita menjalankan sebuah aplikasi Android. Splash Screen digunakan untuk load data,  menjalankan file konfigurasi, dan proses suatu algoritma tertentu. 

## RecyclerView
RecyclerView adalah sebuah komponen tampilan (widget) yang lebih canggih ketimbang pendahulunya listview. RecyclerView bersifat lebih fleksibel. RecyclerView memiliki kemampuan untuk menampilkan data secara efisien dalam jumlah yang besar. Terlebih jika memiliki koleksi data dengan elemen yang mampu berubah-ubah sewaktu dijalankan (runtime). [ Baca Selengkapnya...](https://developer.android.com/guide/topics/ui/layout/recyclerview?hl=id#structure)

## API
API (Aplication Programming Interface) adalah antarmuka aplikasi yang memungkinkan dua atau lebih program aplikasi untuk saling berkomunikasi satu sama lain.

[] Peranan dan Kegunaan API

- API berperan sebagai perantara antar berbagai aplikasi berbeda, baik dalam satu platform yang sama atau lintas platform.
- API juga digunakan untuk komunikasi dengan berbagai bahasa pemrograman yang berbeda.
- Dengan API developer tidak perlu menyediakan semua data sendiri karena cukup mengambil data yang dibutuhkan dari platform lain melalui API.
- API juga memungkinkan untuk mengembangkan sebuah website dengan berbagai fitur yang lebih lengkap.

[] Manfaat API

- Memudahkan Membangun Aplikasi yang Fungsional.
- Meringankan Beban Server.
- Pengembangan Aplikasi Menjadi Lebih Efisien.

[] Cara Kerja API

- Aplikasi mengakses API.
- API Melakukan Request ke Server.
- Server Memberi Respon ke API.
- API Menyampaikan Respon ke Aplikasi.

[] Tujuan Utama API

Tujuan dari API adalah untuk mempercepat pembuatan suatu aplikasi karena programmer tidak perlu menulis kode dari nol. API juga disediakan oleh sebuah platform untuk dapat mengakses fitur dari platform tersebut. 
Contoh dari API yang lintas platform adalah API Twitter dan Facebook, yang memungkinkan kita untuk dapat mengakses data pengguna platform tersebut pada aplikasi kita. [ Baca Selengkapnya...](https://www.niagahoster.co.id/blog/api-adalah/?amp)
 
## REST API

REST merupakan kependekan dari Representational State Transfer. REST API merupakan salah satu dari desain arsitektur yang terdapat di dalam API itu sendiri. REST adalah salah satu implementasi dari web service sebagai sebuah standar yang digunakan untuk pertukaran data antar aplikasi atau sistem.
REST ini bersifat client dan server. Prinsip kerja dari REST API ini adalah client akan menganggap server sebagai object yang dapat dibuat, diupdate, dihapus dan juga dibaca. Jadi pada pelaksanaannya akan ada create dengan request POST, update dengan request PUT atau PATCH, hapus dengan request DELETE, dan baca dengan request GET.

[] Cara Kerja

- REST client akan mengakses data/resource ke REST server dimana masing-masing resource atau data tersebut dibedakan oleh sebuah global ID atau URIs (Universal Resource Identifiers).
- Data yang diberikan oleh REST server itu bisa berupa format text, JSON atau XML. Yang paling populer dipakai saat ini adalah format JSON.
- REST ini memiliki standarisasi dalam pemakaian yaitu mengenai URL dan HTTP verbs.

[] Standarisasi HTTP verbs

- GET: untuk membaca sebuah record atau daftar record.
- POST: untuk menambah sebuah record.
- PUT: untuk mengupdate semua field dalam sebuah record.
- PATCH: untuk mengupdate beberapa field dalam sebuah record.
- DELETE: untuk menghapus sebuah record.

[] Kelebihsan REST API

- Bisa digunakan oleh banyak bahasa pemroggraman dan banyak platform.
- Lebih simple dibandingkan dengan SOAP.
- Mudah dipelajari.
- Menggunakan protokol HTTP, dan HTTP ada dimana-mana.

## JSON

JavaScript object notation atau JSON adalah format yang digunakan untuk menyimpan dan mentransfer data. Berbeda dengan XML (extensive markup language) dan format lainnya yang memiliki fungsi serupa, JSON memiliki struktur data yang sederhana dan mudah dipahami. Itulah mengapa JSON sering digunakan pada API.

[] Keunggulan JSON

- File yang lebih ringan
- Struktur kode yang lebih sederhana
- Kode yang mudah dipahami oleh manusia

## Library

Library merupakan layer tempat fitur-fitur tambahan android berada. Pada umumnya *library *diakses untuk mempermudah atau mempercepat pembuatan suatu aplikasi.

[] kegunaan Library 
- Menyederhanakan kode program yang digunakan untuk mengakses REST API. Seperti mengakses REST API dengan proses sederhana (GET, POST, PUT, DELETE) retrofit juga.
- Mendukung berbagai macam format authentikasi via http, menambahkan header pada request, menambahkan parameter serta mengirim data berupa image ke server.
- Memudahkan untuk mengambil dan mengunggah JSON (atau struktur data lainnya) melalui webservice berbasis REST.
- Mengonfigurasi konverter mana yang digunakan untuk serialisasi data.
- Menambahkan konverter khusus untuk memproses XML atau protokol lain.

## Retrofit


Retrofit merupakan library android yang dibuat oleh Square yang digunakan sebagai REST Client pada Android, yang pasti akan memudahkan kita. Karena kita tidak perlu lagi untuk membuat method-method sendiri untuk menggunakan REST Client API dari backend. 
Library ini menyediakan framework yang powerfull untuk authenticating dan berinteraksi dengan API dengan mengirimkan request menggunakan OkHTTP.

[] Kelebihan Retrofit 

kelebihan utama dari retrofit adalah mudahnya digabung dengan library lain dan bisa di kostumisasi sesuai kebutuhan,sehingga bisa retrofit sangat membantu untuk mempercepat pembuatan project.

[] Alasan retrofit populer digunakan:

- Retrofit merupakan library yang simple untuk meng-organize API calls.
- Konsep annotation akan membuat codingan kita lebih rapih dan enak dipandang
- Retrofit bisa memakai OkHttp sebagai Http client-nya
- Retrofit men-support RxJava.
- Retrofit men-support penggunaan GSON dan Jackson.

## Volley

Volley merupakan produk yang diperkenalkan oleh Google untuk mempermudah pertukaran data tanpa harus membuat deretan kode yang sangat panjang. Secara default volley menggunakan metode singkronisasi jadi anda tidak perlu membuat sebuah method atau fungsi yang menggunakan class asynctask.

[] kelebihan dan keuntungan penggunaan volley :

- Penjadwalan otomatis permintaan jaringan.
- Beberapa koneksi jaringan serentak.
- Caching respons disk dan memori transparan dengan koherensi cache HTTP standar.
- Dukungan untuk pemrioritasan permintaan.
- API permintaan pembatalan. Anda bisa membatalkan satu permintaan, atau menetapkan blok atau cakupan permintaan untuk dibatalkan.
- Kemudahan kustomisasi, misalnya, untuk mencoba ulang dan backoff.
- Pemesanan kuat yang memudahkan pengisian UI Anda dengan benar menggunakan data yang diambil secara asinkron dari jaringan.
- Fitur proses debug dan penelusuran.

[] Fitur Android Volley :

- Automatic scheduling of network requests.
- Multiple concurrent network connections.
- Transparent disk and memory response caching with standard HTTP cache coherence.
- Support for request prioritization.
- Cancellation request API. You can cancel a single request, or you can set blocks or scopes of requests to cancel.
- Ease of customization, for example, for retry and backoff.
- Strong ordering that makes it easy to correctly populate your UI with data fetched asynchronously from the network.
- Debugging and tracing tools.

## Retrofit vs Volley, gimana perbandingannya?

- Kemudahan dalam penggunaan
  
  Retrofit: Sangat mudah digunakan, memungkinkan anda untuk memakai API ini dengan method sederhana dari Java menggunakan interface.
 
  Volley: Sedikit lebih rumit pada umumnya, Volley hanya mendukung beberapa response yaitu String, Image, JSONObject dan JSONArray.
  
- Performan dan Caching 

  Retrofit : Caching harusnya bisa berjalan jika server yang digunakaan menetapkan header control yang benar. Saat menggunakan retrofit anda hanya bisa mengubah lapisan klien Http.
                       
  Volley : Volley memiliki mekasnisme chacing yang lebih rumit dan fleksibel, memanfaatkan untuk membuat caching bitmaps yang lebih besar.
  
- POST requests + multipart uploads 

  Retrofit : Memiliki dukungan penuh untuk permintaan POST dan upload file yang multi, dengan API Sweet untuk boot.
                                      
  Volley : Support untuk POST request tetapi kamu harus melakukan convert terlebih dahulu Java objek yang kamu buat menjadi JSONObject.


## Penerapan Dan Tampilan Pada Aplikasi

![WhatsApp Image 2021-05-10 at 12 18 39 (1)](https://user-images.githubusercontent.com/60412314/117615784-6b652900-b194-11eb-91cc-0bfb1e5fbd42.jpeg)

![WhatsApp Image 2021-05-10 at 12 18 40](https://user-images.githubusercontent.com/60412314/117615772-686a3880-b194-11eb-8628-097d4b2d6825.jpeg)

![WhatsApp Image 2021-05-10 at 12 18 39](https://user-images.githubusercontent.com/60412314/117615781-6acc9280-b194-11eb-9aff-26d2be2e9ec8.jpeg)

![video_20210510_134852](https://user-images.githubusercontent.com/60412314/117617598-f810e680-b196-11eb-911a-0297b92dbbab.gif)
