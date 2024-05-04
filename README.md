# PRAKTIKUM-WEB-1
Pengertian website secara umum adalah kumpulan halaman web yang saling terkait dan dapat diakses melalui internet. Halaman web tersebut berisi informasi, seperti teks, gambar, video, atau animasi. Website dapat digunakan untuk berbagai keperluan, seperti bisnis, pendidikan, hiburan, dan lainnya. Dalam Praktikum Pemrograman Web 1 ini membahas tentang penggunaan HTML, CSS, dan JavaScript.
## HTML
HTML adalah singkatan dari Hyper Text Markup Language. 
HTML merupakan sebuah Bahasa markup yang digunakan untuk membuat sebuah halaman web dan menampilkan berbagai informasi di dalam sebuah Internet. HTML adalah sebuah standar yang digunakan secara luas untuk menampilkan halaman web. HTML saat ini merupakan standar Internet yang didefinisikan dan dikendalikan penggunaannya oleh World Wide Web Consortium (W3C).

<p>Struktur dasar HTML terdiri atas bagian header dan bagian body</p>
<p>•	Bagian Header atau biasa dilambangkan dengan head dalam script program HTML digunakan untuk mendeklarasikan dokumen tersebut</p>
<p>• Bagian Body atau biasa dilambangkan dengan tulisan body dalam script digunakan untuk menentukan bagaimana isi dari suatu dokumen yang akan ditampilkan pada browser.</p>
<p>A. Membuat Dokumen HTML</p>
<p>Dokumen HTML dimulai dengan perintah awal html, kemudian head dan title. Dalam bagian title berisi judul yang akan ditampilkan. Bagian kedua html dimulai dengan adanya perintah body dan diakhiri dengan body alam body berisi tentang isi yang akan ditampilkan oleh dokumen yang dibuat. Kemudian ditutup dengan perintah  pada bagian akhir.

Berikut Merupakan script program dan output dalam membuat dokumen html:</p>
![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/633949f3-6e53-4e4a-a602-b62575756f70)

Output

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/254ef3ed-83ad-434b-9133-399f44c76dfc)


<p>Menampilkan Komentar</p>
<p>Untuk menampilkan komentar agar dapat memberikan kemudahan bagi orang lain yang akan membaca script program yang telah dibuat.</p>

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/f6f5a7ab-2570-4478-9d75-cd598dcc3bfd)

Output

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/d4f9c5db-12c6-4da2-b90c-f6042e025949)



<p>Menambahkan Background</p>
<p>Pada tampilan HTML dapat ditambahkan background berupa gambar atau warna, untuk menambahkan background pada html berupa background warna dapat dilakukan dengan perintah berikut</p>

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/b71c0bff-73b3-4e99-ad0c-474615085f09)

Output

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/614dabd0-e449-4973-aef3-7f251c2decab)

<p>Selain menggunakan background warna, pada html juga dapat menambahkan background berupa gambar. Berikut merupakan script program penambahan background gambar pada html</p>

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/afbd4691-3a97-403b-8afb-e9cb4ef6e551)

Output

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/3ad5c42c-0798-4217-8aca-a57b24af50e6)

<p>Mengubah Warna Text dan Ukuran Text Judul</p>
<p>Dalam html ukuran text dan warna text dapat diganti sesuai dengan warna yang diinginkan, dengan cara sebagai berikut.</p>

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/baa78ee9-0f3a-4bc0-99c9-d32881b8e30c)

Output

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/b13b47f1-8624-4a52-90e2-49a0792d7c32)

<p>Untuk ukuran text judul dalam html terdapat dari beberapa ukuran diantaranya yaitu H1 ( merupakan ukuran yang paling besar) dan H6 ( ukuran yang paling kecil ). Berikut ini script program ukuran text judul</p>

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/8d26ff97-9445-4bcc-b983-f5230a1bcac1)

Output

![image](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/fad1be4d-7514-4116-900c-aebd1ba6ac8e)


<p>Menambahkan Link Tautan</p>
<p>Link atau Hyperlink merupakan elemen dalam suatu HTML yang berfungsi untuk menghubungkan suatu halaman web ke halaman web yang lain. Ketika elemen link di klik maka nanti akan membuka halaman lain sesuai alamat URL yang diberikan.</p>

![Screenshot 2024-05-04 125442](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/f2846a2a-5f21-48df-9b57-ab49692a9330)

Output

![Screenshot 2024-05-04 125531](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/99a748ec-f574-4314-973d-be09ba53e1ae)


##CSS
<p>CSS (Cascading Style Sheet) dapat menerapkan suatu format ketika lebih
dari satu style berlaku. Misalkan kita menginginkan semua paragraph harus memiliki font biru, namun secara khusus menginginkan satu kata agar berwarna
merah./p>
 <p>CSS dapat ditautkan dengan beberapa cara</p>
<p>1. CSS Style Internal diload setiap kali website di-refresh, dan kekurangannya adalah waktu loading semakin lama. CSS style yang sama pun tidak dapat digunakan di halaman lain karena sudah aktif terlebih dulu di suatu halaman.</p>
<p>2. External merupakan CSS style yang paling mudah dan tidak menyulitkan. Semuanya dilakukan secara eksternal pada file .css. Styling dilakukan di file terpisah, lalu terapkan CSS ke halaman mana pun yang Anda inginkan. Sayangnya, CSS Style External juga memperlama waktu loading.</p>
<p>3. SS Style Inline menggunakan elemen spesifik yang memuat tag <style>. Karena setiap komponen harus di-stylize, maka Inline bukan metode yang tepat jika Anda ingin menggunakan CSS dengan cepat.</p>
 
<p>Mengubah Warna Font dengan CSS</p>
<p>Dengan menggunakan CSS kita dapat mengubah warna suatu font, selain menggubah warna kita juga dapat mengubah ukuran dari sebuatu font, dan jenis font yang akan digunakan</p>

![Screenshot 2024-05-04 125714](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/9ff16507-a42e-451f-b6ae-e2ce166b5204)

 Output
 
 ![Screenshot 2024-05-04 125726](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/ef649d09-a1f5-4e9e-9788-b87855b824bd)

<p>Membuat Tombol dengan CSS</p>
<p>Dengan menggunakan CSS kita dapat membuat sebuat tombol yang akan mengarahkan ke halaman lain dengan style yang akan dibuat</p>

![Screenshot 2024-05-04 125739](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/6ecaa4fd-b0ee-4ff8-aac2-c868991e6fc3)

Output

![Screenshot 2024-05-04 125752](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/7c79367e-6b5d-446f-951b-8e452188ea06)

<p>Menambah Background CSS</p>
<p>Dengan menggunakan CC kita dapat mengatur penggunaan gambar sebagai background pada halaman suatu web</p>

![Screenshot 2024-05-04 125822](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/2244cd8e-68a8-4f7f-9c02-26b9aea1cbbc)

Output

![Screenshot 2024-05-04 125834](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/95321cee-f941-4485-93db-09a5a34ac9a1)

##JavaScript
<p>JavaScript adalah bahasa pemrograman yang digunakan developer untuk membuat halaman web yang interaktif.Fungsi utama JavaScript untuk membuat website terlihat menarik dengan konten-kontennya yang dinamis. Konten website yang bisa bergerak dengan otomatis tanpa perlu direload berkali-kali adalah salah satu pengaplikasian JavaScript.</p>

<p>Aritmathic</p>

![Screenshot 2024-05-04 130149](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/cd76f593-1397-47b4-9cfa-aaae5f2b412f)
Output
![Screenshot 2024-05-04 130204](https://github.com/yunisetianingsih/PRAKTIKUM-WEB-1/assets/168643303/1f447a86-e5ee-4bc2-8c86-3c955353f65f)








   

