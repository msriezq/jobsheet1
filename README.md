# jobsheet1
tugas praktikum basis data jobsheet 1

-praktikum 1

1.	Jalankan Apache dan MySQL pada XAMPP Control Panel.
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/ff4d8621-7b91-404c-bec7-a05d80f2b38f)
 
2.	Jalankan aplikasi phpMyAdmin pada web browser Anda, ketik pada url browser http://localhost/phpmyadmin2
 
3.	Buatlah basis data baru dengan cara klik menu new yang ada di pojok kiri, atau klik tab databases. Kemudian klik Create database. Tulis di text box database name dengan kata penjualan_produk. Kemudian klik create. Maka akan akan muncul database dengan nama penjualan_produk.

    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/69b64248-649d-4c35-a269-6a264ce3e50d)

5.	Restore basis data penjualan_produk dari file penjualan_produk.sql. caranya : klik tab import, kemudian klik tombol choose file, pilih file penjualan_produk.sql yang diberikan bersamaan dengan jobsheet ini. Kemudian klik tobol Go yang ada di bagian bawah halaman
   
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/4926f843-4a5d-481e-924b-3d6088896577)

7.	Jika sudah berhasil maka nama basis data penjualan_produk akan muncul di daftar basis data yang ada disebelah kiri lengkap dengan nama-nama tabel yang ada didalamnya.
   
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/fb048b36-38dd-4dad-b9c5-a59dc6a72251)

-praktikum 2

1.	Untuk menampilkan diagram dari basis data caranya : klik nama basis data kemudian pilih tab more, pilih menu designer
   
   ![image](https://github.com/msriezq/jobsheet1/assets/146205529/14cacdcb-2a0a-4efd-be1b-2ef5bd031523)

3.	Untuk melihat isi dari tabel caranya klik nama tabel. Maka data yang ada di dalam tabel akan muncul disisi kanan
   
   ![image](https://github.com/msriezq/jobsheet1/assets/146205529/4b1c3f9d-383b-4dcb-bc6f-1c07e027aa1a)

-praktikum 3

1.	Untuk menambahkan data pada tabel penjualan caranya : klik nama tabel kemudian pilih tab insert, masukkan nilai pada masing-masing kolom, dan klik go
   
   ![image](https://github.com/msriezq/jobsheet1/assets/146205529/72aba865-e135-4d33-ad2b-b471e80a0c14)

2.	Untuk mengecek apakah data yang ditambahkan sudah masuk ke basis data caranya : pilih nama tabel dan cek nilai yang ada di baris paling akhir.

3.	Soal 1: 
Tambahkan data penjualan sebagaimana berikut 
- kode_penjualan = 3 
- tgl = 8 Februari 2021 
- kasir = Dini 
- total_penjualan = 10.000
  
  ![image](https://github.com/msriezq/jobsheet1/assets/146205529/ca32c4e4-63e3-4fbe-b03a-b6ec2f5e9537)
  ![image](https://github.com/msriezq/jobsheet1/assets/146205529/910b6514-8cf4-417f-98ac-d8d738f9f80a)

4.	Soal 2:
Tambahkan data penjualan sebagaimana berikut 
- kode_penjualan = 2 
- tgl = 10 Februari 2021 
- kasir = Dini 
- total_penjualan = 20.000
  
  ![image](https://github.com/msriezq/jobsheet1/assets/146205529/3cdb1a5e-19b0-45de-b0f3-f33fe795d90e)
  ![image](https://github.com/msriezq/jobsheet1/assets/146205529/fcaf02e0-a422-4512-9ee2-71e58281c6f8)

5. Soal 3:
   Jelaskan bagaimana solusi agar data pada soal 2 dapat ditambahkan
   
   ![image](https://github.com/msriezq/jobsheet1/assets/146205529/bdc7f04d-2dfe-4ae0-bfdd-d9d708077e3f)
   ![image](https://github.com/msriezq/jobsheet1/assets/146205529/5512f917-e4d1-405c-bf81-199e7e51d985)

6.	Soal 4:
Tambahkan data detail_penjualan sebagaimana berikut
- kode_penjualan = 2
- kode_barang = 3
- harga = 5.000
- jumlah = 5
Apakah data dapat ditambahkan? Jelaskan alasannya !

    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/cced2f3f-2d52-432a-842a-aea9670f81ef)
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/72a2be1d-b80c-4d3b-9ea3-5eb528683718)
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/2deea7c3-525b-4bfd-a927-5828b7f2b679)

7. Soal 5: 
   Jelaskan bagaimana solusi agar data pada soal 4 dapat ditambahkan
   
8. Soal 6:
   Terangkan apa yang bisa anda pahami dari soal 1-5 terkait dengan duplikasi dan inkonsisten data

-praktikum 4

1.	Soal 7: 
Tambahkan data detail_penjualan sebagaimana berikut
- kode_penjualan = 2
- kode_barang = 3
- harga = 5.000
- jumlah = 5
Apakah data dapat ditambahkan? Jelaskan alasannya !

    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/ddc02677-e05f-4db0-bb8d-a2bdd452e76e)
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/adc5cfbe-4a30-450c-b7f4-5c7b8da7695e)

2.	Tampilkan struktur dari basis data dan hapus garis hubung antara tabel penjualan dan detail_penjualan caranya klik tanda lingkaran pada ujung garis antara tabel penjualan dan detail_penjualan, kemudian pilih delete.

    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/d4139b66-81ab-448b-bfbb-62f42de7aec7)
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/51ef673a-292d-49d8-8e62-dd324b309f76)


3.	Ulangi kembali langkah ke-1 pada praktikum 4. Apakah data dapat ditambahkan? jelaskan alasannya!

   ![image](https://github.com/msriezq/jobsheet1/assets/146205529/6a02094f-08d2-4758-b1df-3bd08597cf4a)


