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
   jawaban: data kode_penjualan "2" sudah ada pada data penjualan, sehingga tidak bisa diinputkan kembali ada 2 cara yang dapat dilakukan, yaitu dengan mengedit kode_penjualan 2 atau menambahkan kode_penjualan baru seperti berikut:
    
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/bdc7f04d-2dfe-4ae0-bfdd-d9d708077e3f)
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/5512f917-e4d1-405c-bf81-199e7e51d985)

6.	Soal 4:
Tambahkan data detail_penjualan sebagaimana berikut
- kode_penjualan = 2
- kode_barang = 3
- harga = 5.000
- jumlah = 5
Apakah data dapat ditambahkan? Jelaskan alasannya !
    jawaban: Ya, data dapat ditambahkan, karena data yang diinsert merupakan data baru yang belum ada pada data detail-penjualan.
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/cced2f3f-2d52-432a-842a-aea9670f81ef)
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/72a2be1d-b80c-4d3b-9ea3-5eb528683718)
    ![image](https://github.com/msriezq/jobsheet1/assets/146205529/2deea7c3-525b-4bfd-a927-5828b7f2b679)

7. Soal 5: 
   Jelaskan bagaimana solusi agar data pada soal 4 dapat ditambahkan
   jawaban: data dapat ditambahkan dengan cara melihat di browse apakah ada data yang sama, jika ada kesamaan data maka tidak bisa ditambahkan, data hanya dapat ditambahkan apabila tidak ada data yang sama pada data detail_penjualan.
   
8. Soal 6:
   Terangkan apa yang bisa anda pahami dari soal 1-5 terkait dengan duplikasi dan inkonsisten data
    jawaban: duplikasi dan inkonsisten data tidak dapat dilakukan dalam basis data, cara mengatasinya adalah mengelompokkan data yang sama, kemudian baru menggabungkannya menggunakan kode, seperti dalam soal nomor 1-5 data barang dan data penjual dikelompokkan sendiri-sendiri, kemudian digabungkan pada data detail_penjualan dengan cara memasukkan kode_penjualan dan kode_barang
