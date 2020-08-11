# NodeJS-RestAPI
Apa itu RestAPI?
![Alt Text](https://github.com/divamaretta/NodeJS-RestAPI/blob/master/Rest-API.png)
REST adalah singkatan dari Representional State Transfer, yaitu standar arsitektur web yang memakai protokol HTTP untuk komunikasi data. Untuk API sendiri, API adalah Application Protocol Interface, yaitu kumpulan subroutine, protokol, dan alat untuk komunikasi data antar aplikasi perangkat lunak.
Cara kerjanya adalah, client REST akan mengakses data ke server Rest, dimana masing data itu dibedakan oleh ID bersifat global, atau URI (Universal Resource Identifiers). Sehingga, data yang diberikan server bisa berupa format text biasa, JSON, ataupun XML.

Berikut adalah metode HTTP yang umum dipakai dalam REST API:
GET, digunakan untuk membaca data dari server REST.
POST, digunakan untuk membuat data baru di server REST.
PUT, digunakan untuk memperbarui data di server REST.
DELETE, digunakan untuk menghapus data dari server REST.
OPTIONS, digunakan untuk mendapatkan operasi yang didukung pada data dari server REST.
Mari, setelah beberapa pengertian singkat ini, kita langsung menuju coding Node.js dengan Postman!


![Alt Text](https://github.com/divamaretta/NodeJS-RestAPI/blob/master/DOWNLOAD%20POSTMAN.PNG)


Setelah proses instalasi, kitapun siap untuk melakukan coding dengan Node.js. Berikut langkah-langkahnya:
1.Silahkan buat folder baru.
2.Buka CLI/Terminal anda di folder tersebut, dan ketikkan “npm init –y” , untuk membuat file “package.json”.

Di projek ini, kita memerlukan beberapa dependencies, yaitu Express.js, dan body-parser (untuk menerima request variabel post dengan mudah sebagai suatu parameter).

3.Maka dari itu, silahkan jalankan kode ini di CLI/Terminal anda untuk menginstall dependencies yang diperlukan: “npm install express body-parser --save” *mongoose tidak perlu di-install
