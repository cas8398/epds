<h1>EPDS</h1>
<p>Ini adalah web code epds</p>

<h2>Apa itu EPDS?</h2>
EPDS adalah
Sebuah sistem yang saling berintegrasi dari proses produksi sampai proses pemuatan produk. sistem yang kami maksud adalah sistem web, dimana keleluasaan dalam pengembangan adalah nilai dasarnya. Dalam EPDS data diolah dan disajikan dalam bentuk table yang mana diharapkan mudah dalam penggunaanya.

<h2>Apa isi EPDS ?</h2>
Epds menggunakan database dan php program untuk mengelola alur sistemnya. Epds menggunakan sistem barcode untuk memudahkan dalam proses inlinenya.

<h2>Fitur apa saja di EPDS?</h2>
Didalam epds masing-masing bagian ikut andil dalam sebuah proses.
- Salah satunya, adalah line produksi akan mendapati laporan otomatis via email dengan hasil produksinya, laporan tersebut akan dikirim kebagian administrasi Produksi.
epds
- Kemudian, Penarikan GDFG juga akan otomatis mengirimkan laporan penarikannya via email ke administrasi Gudang.
epds
- kemudian lagi, Jika terjadi barang tunda baik hari ini atau kemarin, atau tanggal lama akan dengan mudah menemukan dimana pengerakan produk tersebut berada.
epds
- kemudian, tiket pengeluaran barang yang dibuat FIFO akan terintegrasi dengan checker muat, dimana jumlah karton yang dimuat akan otomatis memperbarui jumlah karton yang sudah dimuat. Dengan ini kami harap tidak ada lagi soal kurang kirim/ kelebihan kirim.
epds
- kemudian lagi, Karena menggunakan sistem barcode. Label yang berada di palet yang sudah dimuat akan dapat digunakan lagi pada bagian produksi, Sebab data yang sudah dimuat akan dipindahkan ke table lain dan data table DGFG akan dipindah kesana.
epds

<h2>Tour halaman</h2>
Saat ini tersedia 10 halaman. Dimana jumlah tersebut merupakan bagian dari produksi biscuit. Didalam halaman tersebut. Tersedia dashboard untuk menginput data. Dan table produk yang sudah diproduksi.
Semua menu baik yang ada di PC maupun di Android menggunakan KIOSK menu, dimana hanya aplikasi dijinkan yang dapat dijalankan.

<h2>Penarikan Produk</h2>
Dihalam ini tersedia 2 aplikasi. Dimana pekerja yang bertugas menarik produk dari produksi memiliki 1 aplikasi berbasis android yaitu reader barcode yang termodif untuk dapat langsung terkoneksi ke database. Dimana pekerja tersebut melakukan scan produk barcode dan data masuk dalam sistem epds.
Yang kedua adalah table penarikan dari setiap line produksi. Baik dari bisnis 1 maupun biscuit 2. Didalamnya juga tersedia form pencarian produk untuk melihatberbagai fungsi yang tersedia. Salah satunya adalah memberi label tunda pada barcode produk via database, mengecek lokasi pengerakan produk dan mengembalikan produk ke produksi. 
- Aplikasi Scan Barcode epds
- Menu Produk yang sudah ditarik

<h2>Raking Produk</h2>
Didalam pengerakan produk memiliki aplikasi berbasis android dimana aplikasi tersebut dapat melakukan read data produk yang sudah di tarik oleh bagian penarikan. Didalamnya ada menu menu dimana pengerakan produk tersebut. Bagian ini adalah bagian inti dari epds, kami harap tersedia opsi lebih tentang ini.

<h2>Halaman FIFO</h2>
Dihalaman fifo terdapat table berapa stock GDFG menurut produknya. Dan stock seluruh produk termasuk pilihan didalamnya. Tersedia juga form pencarian produk.
Dan menu tambahan untuk proses muat adalah buat tiket Pengeluaran barang. Dimana menu tersebut memilih produk apa saja yang akan dimuat dan berapa jumlahnya dan diloading berapa barang tersebut dimuat.
Dan satu menu lagi yaitu data tiket yang sudah dibuat. Data tiket tersebut akan otomatis menambah (menu capai) sesuai dengan proses checker muat lakukan

<h2>Checker Muat</h2>
Memiliki sebuah aplikasi berbasi android yang mana pekerka melakukan scan barcode dan data langsung masuk ke table baru yaitu data produk yang sudah dimuat. Dan juga melakukan input otomatis ke menu capai seperti dififo tadi.

<h2>Admin Office</h2>
Memiliki 2 table yaitu. Table pemuatan yang sedang berlangsung Dan table pemuatan yang sudah berlangsung.

<h2>Input data Produk</h2>
Yaitu sebuah form dan table yang merupak produk apa saja yang akan diproduksi saat ini.

<h2>Proses Pembuatan Barcode</h2>
Dalam membuat form barcode tentu neniliki beberapa opsi dalam pembuatannya, salah satunya yaitu dengan web barcode.tec.it dan aplikasi pdf Xchange

<h2>Potensi-potensi</h2>
Penggunaan Perangkan android maupun PC tentu dapat menimbulkan potensi-potensi baik K3 maupun keakuratan proses input data. Oleh sebab itu tentu perlu kajian tentang perihal ini.
Walaupun dengan web service semacam ini diharapkan dapat melakukan kustomisasi dengan mudah, baik rule yang digunakan dan perangkat pendukung sistem EPDS ini.

<h2>Pengembangan kedepan</h2>
Dalam sebuah fase tentu akan ada perbaikan kedepan, kami mengharapkan akan adanya prototype untuk menguji dan memperbaiki ketidaksesuian dengan lapangan.
Diharapkan dalam waktu dekat sistem untuk produksi dan penarikan candy segera terselesaikan dibuat.

<h2>Penutup kata</h2>
Kami menyadari memiliki kekurangan dalam hal ini. Pengembangan kedepan akan terus dilakukan. Saat ini sistem epds baru berjalan di area produksi biscuit. Inti dari epds adalah pengerakan produk sesuai dengan lokasi pemilihannya pada sebuah rack.
Potensi potensi mungkin saja akan terjadi mengingat sostem ini menggunakan apkikasi android untuk melakukan scan barcode dan input data. Oleh karena itu kami memodifikasi launcher agar bisa melakukan kiosk mode. Dimana hanya aplikasi yang dimasukan yang hanya dapat dipakai. Oleh sebab itu tak ada decrease dari fungsi awalnya. Namun sistem ini baru mendukung format online tentu menggunakan internet dalam penggunaanya walaupun jika dibuat offline server induk juga tidak lama .
