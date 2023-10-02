# 2022C-Kelompok5

 
 
Software Requirements 
Specification 
for 
     Perancangan Website 
Crafted Merch Customized
Version 1.0 approved 
Prepared by  

22091397078 – Muhammmad Zacky Zamzamy
22091397088 - Maulana Arridho 
22091397103 - Nur Puspita Amalia
 
 1.	Pendahuluan
1.1	Tujuan Penulisan Dokumen
Dokumen ini bertujuan untuk mendefinisikan kebutuhan dan spesifikasi sistem untuk pengembangan website "Crafted Merch Customized". Website ini akan digunakan untuk memungkinkan pengguna untuk merancang dan memesan produk merchandise yang dapat disesuaikan sesuai dengan preferensi mereka. Dokumen ini akan menjadi panduan bagi tim pengembangan dalam merancang dan mengimplementasikan situs web.


1.2	Audien yang Dituju dan Pembaca yang Disarankan
Dokumen ditujukan untuk berbagai jenis pembaca dan pihak terkait yang terlibat dalam pengembangan, pengelolaan, dan penggunaan website ini. Dokumen ini dirancang untuk memberikan panduan yang komprehensif kepada semua pihak yang terlibat dalam proyek "Crafted Merch Customized" untuk mencapai kesuksesan pengembangan dan penggunaan website ini.
1.3	Batasan Produk


1.4	Definisi dan Istilah
<tulis istilah dan definisikan jika ada>

o	SRS	:	Software Requirements Specification, atau 
	   Spesifikasi Kebutuhan Perangkat Lunak (SKPL)

o	IEEE	:	Institute of Electrical and Electronics Engineering
		Standar internasional untuk pengembangan dan perancangan produk.

1.5	Refrensi

 
 
08 September 2023 
 
Daftar Isi	
1. 	Pendahuluan	2
1.1 	Tujuan Penulisan Dokumen	2
1.2 	Audien yang Dituju dan Pembaca yang Disarankan	2
1.3 	Batasan Produk	2
1.4 	Definisi dan Istilah	2
1.5   Referensi	3
2. 	Deskripsi Keseluruhan	4
2.1 	Deskripsi Produk	4
2.2 	Fungsi Produk	4
2.3 	Penggolongan Karakterik Pengguna	4
2.4 	Lingkungan Operasi	4
2.5 	Batasan Desain dan Implementasi	4
2.6 	Dokumentasi Pengguna	5
3. 	Kebutuhan Antarmuka Eksternal	5
3.1 	User Interfaces	5
3.2	Hardware Interface	5
3.3 	Software Interface	5
3.4 	Communication Interface	5
4. Kebutuhan Fungsional	5
4.1	Use Case Diagram	6
4.2    Use Case	6
4.1.2 Stimulus and Respon	6
4.1.4 Activity Diagram	6
4.3    Flowchart	7
5. Kebutuhan Non Fungsional	8

 
 
 
 
 
 
 
 
1. 	Pendahuluan 
1.1 	Tujuan Penulisan Dokumen 

1.2 	Audien yang Dituju dan Pembaca yang Disarankan 
  
1.3 	Batasan Produk 
  
1.4 	Definisi dan Istilah 
No 	Istilah 	Definisi 
1. 	SKPL 	SKPL (Spesifikasi Kebutuhan Perangkat Lunak) adalah dokumen hasil analisis yang berisi spesifikasi kebutuhan pengguna. 
2. 	IEEE 	IEEE (Institute of Electrical and Electronics Engineers) adalah sebuah organisasi yang mengurusi masalah pengembangan teknologi yang berhubungandengan keteknikan elektro dan elektronika. 
3. 	ERD 	ERD (Entities Relationship Diagram) adalah suatumodel untuk menjelaskan hubungan antar datadalam basis data berdasarkan objek-objek dasardata yang mempunyai hubungan antar relasi. 
4. 	Use Case Diagram 	Use Case Diagram adalah proses penggambaran yang dilakukan untuk menunjukkan hubungan antara pengguna dengan sistem yang dirancang. 
5. 	User 	Pengguna. 
6.	Flowchart	Flowchart adalah representasi grafis dari alur kerja atau proses yang digambarkan dengan menggunakan simbol-simbol, panah, dan bentuk-bentuk lainnya. Tujuan utama dari flowchart adalah untuk menggambarkan secara visual bagaimana suatu proses atau alur kerja berjalan, sehingga memudahkan pemahaman, analisis, dan dokumentasi.



1.5   Referensi 
2. 	Deskripsi Keseluruhan 
2.1 	Deskripsi Produk  
Website "MyFilm" adalah sumber rekomendasi film yang menghadirkan beragam pilihan kepada pembacanya. Situs ini dirancang khusus untuk membantu pembaca menemukan film-film yang sesuai dengan preferensi dan selera mereka. Pengguna dapat dengan mudah mencari rekomendasi film yang cocok dengan apa yang mereka cari.

“MyFilm” menyajikan rekomendasi film dengan detail yang informatif. Setiap film dijelaskan dengan sinopsis singkat yang memberikan gambaran tentang alur cerita dan tema film tersebut. Selain itu, situs ini juga menyediakan akses mudah ke trailer film, sehingga pembaca dapat mendapatkan gambaran visual tentang film yang direkomendasikan. Semua ini bertujuan untuk memberikan pengalaman yang lebih lengkap dan informatif kepada pengguna dalam memilih film yang akan mereka tonton. Dengan begitu, “MyFilm” menjadi sumber terpercaya untuk menemukan film-film baru yang dapat dinikmati oleh para pecinta film.

2.2 	Fungsi Produk  
 
 
2.3 	Penggolongan Karakterik Pengguna 
 
Tabel 1 Karakteristik Pengguna 
Kategori Pengguna 	Tugas 	Hak Akses ke aplikasi 	Kemampuan yang harus dimiliki 
User 	User dapat melakukan kegiatan penting pada  website seperti membaca sinopsis film dan menonton trailer film.
 	Melihat website 	Memahami cara 
kerja website 
 
 
 
2.4 	Lingkungan Operasi  
 
 
2.5 	Batasan Desain dan Implementasi  

 
2.6 	Dokumentasi Pengguna 
 
 
3. 	Kebutuhan Antarmuka Eksternal 
3.1 	User Interfaces

	1. !DOCTYPE html, Adalah deklarasi tipe dokumen (Document Type Declaration) yg digunakan untuk membuat dan mendesain halaman web.

	2. html, Tag ini digunakan pada awal dari dokumen HTML.

	3. head, Berisi informasi metadata tentang halaman web, seperti judud yg akan ditampilkan pada tab browser.

	4. meta, Digunakan untuk metadata tambahan tentang halaman web dan untuk mengatur karakter set.

	5. link, Digunakan untuk menghubungkan dokumen HTML dengan file "style.css".

	6. title, Dalam HTML digunakan untuk menentukan judul dari halaman web.

	7. body, Digunakan untuk menampung konten utama yg akan ditampilkan di halaman web seperti teks, gambar, dan tautan.

	8. div, Tag ini digunakan untuk membuat divisi atau kontainer dalam halaman web.

	9. h1, Digunakan untuk judul utama halaman.

	10. h2, Digunakan untuk mengelompokkan konten menjadi bagian-bagian.

	11. h3, Digunakan untuk judul sub bagian.

	12. ul li, Untuk membuat daftar tanpa urutan dengan elemen-elemen daftar.

	13. a, Membuat tautan (hyperlink) ke halaman web atau sumber daya lainnya yg dapat diakses menggunakan internet.

	14. img, Digunakan untuk menampilkan gambar dalam halaman web.

	15. button, Digunakan untuk membuat tombol interaktif di halaman web seperti mengirimkan formuir, dan membuka jendela pop up.

	16. p, Untuk mengatur teks atau paragraf pada halaman web.

	17. color, tag ini digunakan untuk mengatur warna teks yang telah dimasukkan. Tag ini terdapat pada elemen ‘.navbar h1’, ‘.navbar span’, ‘.navbar ul li 	a’, ‘.hiro h2’, ‘.konten .sinopsis h3’, ‘.konten .sinopsis p’, ‘#terbaru h1’, ‘#terpopuler h1’, dan ‘#terbaik h1’.
	
	18. text-decoration, tag ini digunakan untuk mengatur dekorasi yang terdapat pada teks yang dimasukkan. Tag ini terletak pada elemen ‘.navbar ul li a’ 		dan ‘.konten button a’.
	
	19. transition, tag ini digunakan untuk mengatur efek transisi pada elemen saat pengguna melakukan interaksi dengan elemen. Tag ini digunakan pada elemen 	'.navbar ul li a', '.konten button', '.konten button a', dan '.konten button:hover.'
	
	20. flex-direction, tag ini digunakan untuk mengatur arah tata letak elemen yang ditampilkan dengan perintah display: flex. Tag ini digunakan pada 		'#terbaru', '#terpopuler', dan '#terbaik'.
	
	21. gap, tag ini difungsikan untuk mengatur jarak antar elemen yang telah dimasukkan dalam display: flex. Tag ini terdapat pada elemen '.navbar ul', 		'.daftarfilm', dan '.card'.
	
	22. border-bottom, tag ini digunakan untuk menambahkan garis bawah pada teks. Tag ini terdapat pada '#terbaru h1', '#terpopuler h1', dan '#terbaik h1'.
	
	23. max-height dan min-height, tag ini digunakan untuk mengatur tinggi elemen paling maksimum dan paling minimum. Tag ini terdapat pada elemen '.konten 	.sinopsis' dan '.konten .sinopsis p'.
	
	24. width, tag ini digunakan untuk mengatur lebar elemen pada tampilan halaman website. Tag ini terdapat pada elemen '.card', '.konten img', dan '.konten 	button'.
	
	25. border-radius, tag ini digunakan untuk mengatur radius atau lengkungan pada sudut elemen. Tag ini terdapat pada elemen '.konten button'.

       
3.2	Hardware Interface 
       	 
3.3 	Software Interface 

3.4 	Communication Interface 
 
 	 
4. Kebutuhan Fungsional 
 
 
4.1	Use Case Diagram 
![Gambar Use Case](./assets/usecase.png)

  
4.2    Use Case 
	4.1.1 	Deskripsi Use Case  
1.	User : User dapat melakukan kegiatan penting pada  website seperti membaca sinopsis film dan menonton trailer film.
 
4.1.2 Stimulus and Respon 
 
 
4.1.4 Activity Diagram 
 
 
 
 
 
4.3    Flowchart
![Gambar Flowchart](./assets/flowchart.png)
   	    
5. Kebutuhan Non Fungsional 
 
 
