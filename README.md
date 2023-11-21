# TUGAS AKHIR PBO
<h2>Sistem Perpustkaakaan Menggunakan Laravel 8</h2> 
<h3>Kelompok Perpustakaan XII RPL 2</h3>

<h4>Rekayasa Perangkat Lunak</h4>


# Cara Menjalankan Aplikasi Web :

<ol>
<li>git clone https://github.com/PowerGabb/perpustakaan-laravel-pbo.git</li>
<li>cd perpustakaan-laravel-pbo</li>
<li>composer update / composer install</li>
<li>php artisan key:generate</li>
<li>php artisan storage:link</li>
<li>buat database perpustakaan</li>
<li>ubah nama database sesuai dengan yang sudah di buat di file .env pada project laravel</li>
<li>php artisan migrate:fresh --seed</li>
<li>php artisan serve</li>
<li>Login Sebagai Admin email:griyagpm@gmail.com password:123123123</li>
</ol>

# Fitur Yang Kita Buat :
<ol>
<li>Ada 2 jenis Anggota yaitu Admin dan Anggota</li>
<li>Setiap User Harus Melakukan Login Untuk Dapat Mengakses Web</li>
<li>user harus terdaftar sebagai anggota untuk meminjam buku</li>
<li>Satu user hanya dapat memiliki satu profile</li>
<li>setiap user dapat mengubah profilenya masing"</li>
<li>Setiap Buku dapat memiliki multiple kategori</li>
<li>Judul buku dapat berjumlah lebih dari 1 (dapat dibedakan melalui kode buku)</li>
<li>Bisa melakukan pencaharian buku melalui judul buku</li>
<li>Admin bisa menambah,mengupdate,dan menghapus: data buku,kategori dan user</li>
<li>Setiap Anggota hanya dapat meminjam maksimal 3 buku</li>
<li>Peminjaman maksimal 7 hari. Jika peminjaman lebih dari 7 hari maka akan dikenakan denda</li>
<li>Hanya Admin yang dapat melakukan pengembalian buku, jadi setiap anggota harus menghubungi admin jika ingin mengembalikan buku.</li>
<li>Admin dapat melihat list buku yang dipinjam, sedangkan Anggota hanya dapat melihat list buku yang dipinjam olehnya</li>
<li>Admin dapat melihat dan mencetak riwayat peminjaman buku, sedangkan Anggota hanya dapat melihat list buku yang dipinjam olehnya</li>
</ol>



</ul>

