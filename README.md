# Lab8Web

## Membuat PHP dan Database MySQL

### Langkah-Langkah Praktikum
#### Persiapan

Untuk memulai membuat aplikasi CRUD sederhana, yang perlu disiapkan adalah
database server menggunakan MySQL. Pastikan MySQL Server sudah dapat dijalankan
melalui XAMPP.

#### Menjalankan MySQL Server
Untuk menjalankan MySQL Server dari menu XAMPP Contol.

![Gambar1](screenshot/ss1.png)

#### Mengakses MySQL Client menggunakan PHP MyAdmin
Pastikan webserver Apache dan MySQL server sudah dijalankan. Kemudian buka
melalui browser: `http://localhost/phpmyadmin/`

#### Membuat Database
Pada aplikasi `phpMyAdmin` klik ikon `Baru` yang ada di sebelah kiri tampilan.

![Gambar2](screenshot/ss2.png)

Kemudian masukan nama file dan klik ikon `Buat`.

![Gambar3](screenshot/ss3.png)

#### Membuat Table
Kemudian masukan nama table yang akan dibuat dan jumlah kolom yang diinginkan dan klik `Kirim`.

![Gambar4](screenshot/ss4.png)

Akan muncul tampilan sebagai berikut.
masukan data yang diinginkan dan klik `Simpan`.

![Gambar5](screenshot/ss5.png)

Tampilan table yang kita buat seperti berikut.

![Gambar6](screenshot/ss6.png)

Langkah selanjutnya, klik pada pilihan menu `SQL` yang berada dideretan atas tampilan, dan masukan code seperti berikut.

![Gambar7](screenshot/ss7.png)

#### Menambahkan Data
Kemudian dilanjutkan untuk menambahkan data yaitu dengan klik pilihan menu `INSERT` yang ada dibagian bawah tampilan.

![Gambar8](screenshot/ss8.png)

Tambahkan data seperti berikut ini.

![Gambar9](screenshot/ss9.png)

Tampilan hasil penambahan data seperti berikut ini.

![Gambar10](screenshot/ss10.png)

![Gambar11](screenshot/ss11.png)

Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
`http://localhost/lab8_php_database/`

Tampilan pada web server seperti berikut.

![Gambar12](screenshot/ss12.png)


#### Membuat file koneksi database
Buat file baru dengan nama `koneksi.php`.
Masukan kode seperti berikut.

![Gambar13](screenshot/ss13.png)

Buka melalui browser untuk menguji koneksi database (untuk menyampilkan pesan koneksi berhasil, uncomment pada perintah echo `“koneksi berhasil”`; 

Tampilan pada web server.

![Gambar14](screenshot/ss14.png)


#### Membuat file index untuk menampilkan data (Read)
Buat file baru dengan nama `index.php`.
Masukan kode seperti berikut.

![Gambar15](screenshot/ss15.png)

Tampilan pada web server akan seperti berikut.

![Gambar16](screenshot/ss16.png)

#### Menambah Data (Create)
Buat file baru dengan nama tambah.php
Masukan kode seperti berikut.

![Gambar17](screenshot/ss19.png)

![Gambar18](screenshot/ss20.png)

Maka, apabila kita klik pilihan `Tambah Barang`, akan muncul tampilan seperti berikut ini.

![Gambar19](screenshot/ss17.png)

Masukan data yang ingin ditambahkan,contoh seperti berikut.

![Gambar20](screenshot/ss19.png)

Tampilan pada web server akan berubah seperti berikut.

![Gambar21](screenshot/ss21.png)


#### Mengubah Data (Update)
Buat file baru dengan nama `ubah.php`.
Masukan kode seperti berikut.

![Gambar22](screenshot/ss22.png)

![Gambar23](screenshot/ss23.png)

Maka apabila kita memilih pilihan ubah, tampilan akan seperti berikut. Saya mengambil contoh mengubah stok dari barang HP Iphone 14.

![Gambar24](screenshot/ss24.png)

Setelah data diubah, klik `Simpan` untuk menyimpan.
Maka tampilan stok akan update sesuai perubahan, dan hasilnya seperti berikut.

![Gambar25](screenshot/ss25.png)


#### Menghapus Data (Delete)
Buat file baru dengan nama `hapus.php`.
Masukan kode seperti berikut.

![Gambar26](screenshot/ss26.png)

Kemudian pada tampilan web serve, apabila kita klik pilihan `Hapus`, maka data akan terhapus.
Sebagai contoh, disini saya menghapus data ke 3, yaitu HP Iphone.
Maka tampilan web server akan berubah, seperti berikut.

![Gambar27](screenshot/ss27.png)

#### ~~ Demikian latihan praktikum mengenai PHP dan Database MySQL ~~
