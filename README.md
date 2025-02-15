#Hapis note

<h3>Berikut cara kerja Perceptron pada Artificial Neural Network</h3>
[https://dicoding-web-img.sgp1.cdn.digitaloceanspaces.com/original/academy/dos-4ab7d534028a52c401998a1e8a4e6bc920240106185335.jpeg]

*Berikut adalah proses yang menjelaskan bagaimana perceptron bekerja.

-Input menerima masukan berupa angka-angka. 
-Setiap input memiliki bobot masing-masing. Bobot adalah parameter yang akan dipelajari oleh sebuah perceptron dan menunjukkan kekuatan node tertentu. 
-Selanjutnya adalah tahap penjumlahan input. Pada tahap ini, setiap input akan dikalikan dengan bobotnya masing masing, lalu hasilnya akan ditambahkan dengan bias yang merupakan sebuah konstanta atau angka. Nilai bias memungkinkan Anda untuk mengubah kurva fungsi aktivasi ke atas atau ke bawah sehingga bisa lebih fleksibel dalam meminimalisasi eror. Penjelasan lebih lanjut tentang bias dapat Anda pelajari pada tautan berikut.

*Hasil penjumlahan pada tahap ini biasanya disebut weighted sum.

-Berikutnya, aplikasikan weighted sum pada fungsi aktivasi atau disebut juga Non-Linearity Function. Fungsi aktivasi digunakan untuk memetakan nilai yang dihasilkan menjadi nilai yang diperlukan, misalnya antara (0, 1) atau (-1, 1). Fungsi ini memungkinkan perceptron dapat menyesuaikan pola untuk data yang non linier. Penjelasan lebih lanjut tentang fungsi aktivasi akan diulas pada paragraf di bawah.
-Setelah semua langkah di atas terlewati, akhirnya kita memperoleh output berupa hasil perhitungan sebuah perceptron dalam bentuk bilangan numerik.
