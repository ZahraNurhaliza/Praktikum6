# Praktikum6

## Latihan
• Buat Dictionary daftar kontak
• Nama sebagai key, dan nomor sebagai value
• Tampilkan kontaknya Ari
• Tambah kontak baru dengan nama Riko, nomor 087654544
• Ubah kontak Dina dengan nomor baru 088999776
• Tampilkan semua Nama
• Tampilkan semua Nomor
• Tampilkan daftar Nama dan nomornya
• Hapus kontak Dina.

### Program
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Latihan1.1.png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Latihan1.2.png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Latihan1.3.png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Latihan1.4.png)

### RUN
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Latihan1(RUN.1).png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Latihan1(RUN.2).png)

## Praktikum
Buat program sederhana yang akan menampilkan daftar nilai
mahasiswa, dengan ketentuan
• Program dibuat dengan menggunakan Dictionary
• Tampilkan menu pilihan: (Tambah Data, Ubah Data, Hapus Data,
Tampilkan Data, Cari Data)
• Nilai Akhir diambil dari perhitungan 3 komponen nilai (tugas: 30%,
uts: 35%, uas: 35%)

### Program
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Praktikum6.1.png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Praktikum6.2.png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Praktikum6.3.png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Praktikum6.4.png)

### RUN
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Praktikum6(RUN.1).png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Praktikum6(RUN.2).png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Praktikum6(RUN.3).png)
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Praktikum6(RUN.4).png)

### Penjelasan
1. Definisikan dictionary terlebih dahulu data = {}.
2. Gunakanlah perulangan While True untuk menampilkan data sebanyak banyaknya.
3. lalu Masukan perintah g = input("(T)ambah, (U)bah, (H)apus, (L)ihat,(C)ari, (K)eluar: "),untuk mendapatkan perintah Tambah, Ubah, Hapus,Lihat,Cari,Keluar.
4. Untuk menambahkan data gunakan fungsi elif, lalu masukan nama, nim, tugas, uts, uas, nilaiakhir, nilai akhir didapat dari = ((tugas)*30/100+(uts)*35/100+(uas)*35/100).
5. Lalu jika ingin memilih "lihat" gunakan fungsi 'elif' dan gunakan fungsi 'for x in data.items():' untuk memasukan data kedalam tabel data yang kita inputkan, dengan perintah "l". jika data yang tidak terdaftar = 0.
6. Untuk menampilkan pilihan "hapus"gunakan fungsi 'elif' kemudian gunakan fungsi 'if nama in data.keys():' kemudian fungsi'del.data[nama] jika nama yang kita hapus tidak ada dalam tabel maka gunakan fungsi 'else' untuk menampilkan data tidak ada.
7. lalu untuk menampilan pilihan "cari"" gunakan fungsi 'elif' kemudian gunakan fungsi if nama in data.keys():' untuk mencari data nama kemudian gunakan fungsi 'else' untuk menampilkan data nama yang kita cari tidak ada.
8. lalu jika ingin keluar dari program gunakan fungsi 'if' kemudian gunakan fungsi break untuk keluar dari data nilai/menghentikan program.
9.Seleseai.

### Flowchart
![image](https://github.com/ZahraNurhaliza/Praktikum6/blob/main/screenshot/Flowchart%20.png)

### Commit dan push repository ke github.
