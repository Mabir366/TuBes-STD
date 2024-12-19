A. DESKRIPSI TOPIK 

Dalam manajemen proyek, seringkali terjadi masalah dalam mengelola dan memantau proyek yang jumlahnya mungkin tidak sedikit. Setiap proyek memiliki beberapa sub-proyek atau tugas dengan tenggat waktu tertentu. Pengelolaan seperti penambahan, penghapusan, pencarian, atau lamanya durasi waktu pengerjaannya sering kali menjadi hambatan saat menangani data dalam jumlah besar.
Oleh karena itu, untuk memecahkan masalah ini, diperlukan struktur data Multi Linked List dengan pemodelan hubungan 1-N antara proyek dan daftar tugas yang ada di dalam suatu proyek. Setiap node proyek (parent) memiliki daftar tugas (child), dan setiap tugas menyimpan informasi nama tugas serta deadline waktu yang akan dibuat. Solusi yang bisa kami lakukan adalah membuat aplikasi NodeWorker yang dimana bisa membuat proyek yang diinginkan yang bisa diisi dengan banyak tugas-tugas yang ingin dikerjakan. Selain itu, fitur-fitur tambahan seperti banyak Tugas dan Koordinator (Manajer) pada proyek memudahkan pengerjaan proyek untuk tertata lebih baik dan teratur.

B. FITUR-FITUR PROGRAM 
Insert Data : 
1. Menambahkan proyek baru ke dalam list (parent)
2. Menambahkan tugas baru ke dalam proyek (child)

Delete Data : 
1. Menghapus parent beserta child-nya
2. Menghapus child dari parent

	Data Searching :
1. Mencari proyek (parent) berdasarkan nama
2. Mencari tugas (child) dalam suatu proyek (parent)

	Edit Data : 
1. Mengubah nama proyek (parent)
2. Mengubah nama dan durasi dari suatu tugas (child)

Show Data : 
1. Menampilkan daftar proyek (parent)
2. Menampilkan daftar proyek (parent) beserta tugas-tugasnya (child) 

	Kalkulasi Durasi Proyek : 
1. Menghitung lama durasi pengerjaan suatu proyek
 
Banyak Tugas dalam satu Proyek: 
2. Menampilkan banyaknya tugas-tugas yang tersedia dalam satu proyek

Manajer (Coordinator) Proyek : 
1. Menampilkan koordinator/manajer dari pengembangan proyek yang akan dirancang

Status Pengerjaan Tugas : 
1. Menampilkan status tugas yang dikerjakan dalam proyek tersebut, apakah masih dalam progress, done,batal, dan lain sebagainya.

C.  KENDALA  
1. Pembuatan kodingan yang lebih kompleks karena tidak hanya melibatkan output proyek beserta isinya, melainkan juga membuat durasi waktu dari waktu yang diinput sampai deadline waktu tugas tersebut.
2. Pembagian tugas yang diberikan menjadi tantangan karena diharuskan untuk siap kodingannya secara keseluruhan terlebih dahulu, baru dieksekusi di main program.
3. Kasus yang mungkin belum diketahui, seperti menitnya > 60, atau kasus jika di menu langsung dipilih nomor 2 yang seharusnya harus dipilih 1
4. Program lamaDurasi belum terprediksi jika penginputan waktu melebihi/mengurangi waktu yang seharusnya (sesuai kriteria waktu dunia)

D. PEMBAGIAN TUGAS 
Anggota 1 : Muhammad Fazlur Rahman
Tugas : 
1. Merancang fitur insert proyek (parent) dari belakang 
2. Membuat fungsi pencarian pada data proyek (parent) 
3. Merancang fitur update data proyek (parent) beserta tugas-tugasnya (child) 
4. Merancang fitur delete data proyek (parent) beserta tugas-tugasnya (child) 
5. Merancang fitur show all data proyek (parent) 

Anggota 2 : Bill Stephen Sembiring
Tugas : 
1. Implementasi dalam perancangan menu pada halaman utama (main.cpp) 
2. Membuat perhitungan untuk durasi deadline tugas pada suatu proyek (hasilnya ada pada show proyek beserta tugas-tugasnya) 
3. Merancang fitur insert data tugas (child) yang berhubungan dengan proyek 
4. Membuat fitur show all data proyek (parent) beserta data tugas-tugasnya (child) 
5. Merancang fitur delete data tugas-tugas (child) dari proyek tertentu 
6. Membuat fitur mencari data tugas (child) pada suatu proyek tertentu 



