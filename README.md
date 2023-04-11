# Project-Basis-Data-1
~~~sh

Membuka mysql client

# mysql -u root

CREATE DATABASE (Nama_Database)

Perintah: USE

USE latihan01;

Menampilkan daftar Basis data 

SHOW DATABASE;

Membuat Tabel

CREATE TABLE biodata VARCHAR(50), alamat TEXT);

Menampilkan Sturktur Tabel

DESC (nama_tabel)

Menambah Field

ALTER TABLE Biodata ADD COLUMN id int (10) FIRST;

Mengubah Nama Field

ALTER TABLE biodata CHANGE alamat alamat_jalan VARCHAR(200);

Mengubah Tipe Data

ALTER TABLE biodata MODIFY alamat_jalan TINYTEXT;

Menghapus Field

ALTER TABLE biodata DROP alamat_text;

Menambahkan Index atau Key

ALTER TABLE biodata ADD PRIMARY KEY(id);

Menghapus Primary Key

ALTER TABLE biodata DROP PRIMARY KEY;

Mengubah nama Field

ALTER TABLE data_mhs rename biodata;


Contoh Gambar:

 1.  ![](gambar/A1.jpeg)
 2.  ![](gambar/A2.jpeg)
 3.  ![](gambar/A3.jpeg)
 4.  ![](gambar/A4.jpeg)
 5.  ![](gambar/A5.jpeg)
 6.  ![](gambar/A6.jpeg)
 7.  ![](gambar/A7.jpeg)
 8.  ![](gambar/A8.jpeg)
 9.  ![](gambar/A9.jpeg)
 10. ![](gambar/A10.jpeg)
 11. ![](gambar/A11.jpeg)

 ~~~
