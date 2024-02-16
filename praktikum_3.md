# -T_praktikum-3-Basis-Data
1. Untuk menambahkan data pada tabel penjualan caranya : klik nama tabel kemudian pilih tab tambahkan, masukkan nilai pada masing-masing kolom, dan klik import
   
    ![Capture 7](https://github.com/Fanzirfan27/-T_praktikum-1-Basis-Data/assets/160199038/318ba6ab-d9c0-4ab4-8100-3b708b84aec3)
2. Tambahkan data penjualan sebagaimana berikut <SOAL 1>
    - kode_penjualan = 3 
    - tgl = 8 Februari 2021 
    - kasir = Dini 
    - total_penjualan = 10.000
      
    ![soal 1](https://github.com/Fanzirfan27/-T_praktikum-1-Basis-Data/assets/160199038/acdc0c6d-b327-4ad9-99cc-cb09c293e891)
3. Tambahkan data penjualan sebagaimana berikut <SOAL 2>
    - kode_penjualan = 2 
    - tgl = 10 Februari 2021 
    - kasir = Dini 
    - total_penjualan = 20.000 

    ![soal 2](https://github.com/Fanzirfan27/-T_praktikum-1-Basis-Data/assets/160199038/a33d0082-77a4-4cda-80d3-6b7803a13685)
4. Jelaskan bagaimana solusi agar data pada soal 2 dapat ditambahkan <SOAL 3>
    Jawab: Value yang ada di kolom kode_penjualan diganti ke nomor selain yang sudah ada di tabel detail penjualan
5. Tambahkan data detail_penjualan sebagaimana berikut <SOAL 4>
    - kode_penjualan = 2 
    - kode_barang = 3 
    - harga = 5.000 
    - jumlah = 5 

    ![soal 4](https://github.com/Fanzirfan27/-T_praktikum-1-Basis-Data/assets/160199038/50f2d7bd-68c7-43bc-8d74-8be3f4dea47d)
   Apakah data dapat ditambahkan? Jelaskan alasannya !
   Jawab: Bisa ditambahkan,karen kolom yang diisikan sudah sesuai dengan data terkait (kode_penjualan dan kode_barang) sudah tertera     ditabel penjualan dan table barang,dan belum ada di detail penjualan
6. Jelaskan bagaimana solusi agar data pada soal 4 dapat ditambahkan <SOAL 5>
   Jawab: Tidak ada solusi soalnya soal no 4 bisa di tambahkan tanpa adanya error
7. Terangkan apa yang bisa anda pahami dari soal 1-5 terkait dengan duplikasi dan inkonsisten data <SOAL 6>
   Jawab: penduplikasian pada  kode_penjualan di table penjualan maupun di table detail_penjualan tidak dapat dilakukan, hal ini untuk menghindari kesulitan kita untuk mengakses data tersebut
