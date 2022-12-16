# HTML

## 1. __Pengenalan HTML__ <br>
HTML (Hyper Text Markup Language) adalah sebuah bahasa formatting yang digunakan
untuk membuat sebuah halaman website. Di dalam dunia pemrograman berbasis website(Web
Programming), HTML menjadi pondasi dasar pada halaman website. sebuah file HTML di di
simpan dengan ekstensi .html (dot html). dan dapat di eksekusi atau diakses menggunakan
web browser (Google Chrome, Mozilla Firefox, Opera, Safari dan lain-lain). untuk membuat
sebuah website tidak cukup hanya menggunakan HTML, kita memerlukan bantuan CSS,
JavaScript dan PHP untuk membuatsebuah website yang dinamis. jika halaman website dibuat
hanya menggunakan HTML saja maka halaman website tersebut di sebut halaman statis
karena tidak memiliki aksi atau fungsi- fungsi yang dapat mengelola website. tentu developer
akan sangat di sibukkan dengan harus mengubah lagi file HTML setiap ingin mengupdate
artikel .
## 2. __Cara Penulisan HTML__

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>judul</title>
</head>
<body>
    
</body>
</html>

```

Pada setiap dokumen HTML yang Anda buat, awali dokumen dengan penanda "document
type" atau jenis dokumen (<!DOCTYPE html>), penanda HTML (<html>), dan penanda
“BODY” atau bagian utama halaman (<body>). Anda juga harus mengakhiri dokumen
dengan penanda “BODY” penutup (<\body>) dan penanda HTML penutup (</html>) . Bagian
“kepala” atau “head” digunakan untuk menentukan teks yang ditampilkan pada tab peramban.
Sepereti contoh pada gambar diatas anda dapat mengubah “Judul Halaman” dengan judul yang
diinginkan .
## **3. Pengenalan Tag Pada HTML**
Tag merupakan kode yang digunakan untuk memperkenalkan pada web browser untuk apa
text HTML yang ditulis. HTML membutuhkan cara memperkenalkan text yang ditulis
didalamnya kepada web browser. baik text itu berupa list, paragraf, link dan sebagainya.
disinilah di gunakan tag. dalam penulisan tag, hampir semua menggunakan pembuka dan
penutup tag, dimana objek yang di maksudkan berada diantara pembuka dan penutup tag.
berikutpenulisan tag yang digunakan dalam HTML .
Perbedaan antara tag pembuka dan tag penutup yaitu, pada tag pembuka diawali kurung
sudut pembuka dan di akhiri dengan kurung sudut penutup (< >), sedangkan pada tag
```
<tag> Objek yang diisi </tag>
```
penutup, diawali dengan kurung sudut pembuka, backslash, dan diakhiri dengan penutup
kurung sudut (</>) .
berikut beberapa jenis tag yang akan sering anda jumpai kalo di web programing :

|   Tag        | Fungsi |
| ----------   | ------ |
| <!– ....–>   |     Digunakan untuk memberi sebuah komentar atau keterangan    |
DOCTYPE html | digunakan untuk Mendefinisikan tipe document HTML5 |
   a  | Mendefinisikan sebuah anchor, digunakan untuk saling menautkan antara satu dokumen HTML ke dokumen HTML yang lain (membuat link)|
b | membuat teks menjadi tebal |
p | Membuat paragraf |
H1 | Membuat Heading 1 |
H2 | Membuat Heading 2 |
H3 | Membuat Heading 3 |
H4 | Membuat Heading 4 |
H5 | Membuat Heading 5 |
H6 | Membuat Heading 6 |
body | mendefinisikan body/isi dokument html |
Head | mendefinisikan bagian kepala dokumen html|
title | mendefiniskan judul halaman |
div | Mendefinisikan generik blok konten yang digunakan sebagai kontainer (penampung) untuk meng-group beberapa elemen menjadi satu |
link | mendefinisikan hubungan antar dokumen |
script | Mendefinisikan elemen yang digunakan untuk menulis atau menyisipkan script (seperti JavaScript), ataupun sebagai sumber file external dengan attribut src |
table | mendefinisikan table |
th | Mendefinisikan sel header di dalam sebuah table |
td | Mendefinisikan sel di dalam sebuah table |
tr | Membuat baris di dalam sebuah table |
ul | Mendefinisikan daftar dalam format bullet |
li | mendefinisikan list 


## __4. Paragraf, Heading, Dan List__
 a). Paragraf
paragraf disini merupakan suatu tag untuk membuat penulisan dalam bentuk paragraf. tag paragraf ini terdapat 3 atribut/tag yang bisa dikombinasikan langsung dengan tag paragraf <'p>. atribut tag tersebut yaitu :
* Membuat paragraf rata kiri menggunakan <'p' align=”left”> .. isi paragraph <'/p'>
* Membuat paragraf rata kanan menggunakan <'p' align=”right”> .. isi paragraph </'p'>
* Membuat paragraf rata tengah menggunakan <'p align=”center”> .. isi paragraph <'/p'>
* Membuat paragraf rata kiri kanan menggunaan <'p' align=”justify”> .. isi paragraph <'/p'>

Berikut Contoh Implementasi Paragraf Dalam Document HTML :

```html
<p align=”left”> .. isi paragraph </p>
<p align=”right”> .. isi paragraph </p>
<p align=”center”> .. isi paragraph </p>
<p align=”justyfy”> .. isi paragraph </p>
```
hasil :
```html 
isi paragrph
                                            isi paragrph
                     isi paragrph
isi paragrph
```

b) Heading
Heading merupakan element atau tag HTML yang berfungsi untuk menunjukkan bagian penting pada halaman web. element tag heading ini memiliki 6 tingkatan yang berurutan yaitu <'h1>,<'h2>,<'h3>,<'h4>,<'h5>,<'h6> yang bisa digunakan untuk menambah ke struktur halaman web. perbedaan masing-masing heading yaitu besar hingga kecil teks. contohnya tag/elemen <'h1> lebih besar dari element/tag <'h2> dan seterusnya .
Penggunaan masing-masing heading juga berbeda, berikut penggunaan masing-masing tag/element heading yang sering digunakan pada pengolahan halaman web :
<'h1> adalah heading yang digunakan untuk penulisan judul utama dari dokumen
<'h2> adalah heading yang digunaakan sebagai sub dari <'h1>
<'h3> adalah heading yang digunakan sebagai sub dari <'h2>
untuk penggunaan <'h4><'h4><'h5><'h6> tergantung programmer sendiri untuk memperindah halaman web sesuai keperluan.
Berikut Contoh Implementasi Heading Dalam HTML :

```html
<h1>ini adalah heading</h1>
<h2>ini adalah heading</h2>
<h3>ini adalah heading</h3>
<h4>ini adalah heading</h4>
<h5>ini adalah heading</h5>
<h6>ini adalah heading</h6>
```

hasil :
<h1>ini adalah heading</h1>
<h2>ini adalah heading</h2>
<h3>ini adalah heading</h3>
<h4>ini adalah heading</h4>
<h5>ini adalah heading</h5>
<h6>ini adalah heading</h6>
<br>




###  c) List
List atau yang kita kenal dengan daftar berurutan merupakan fungsi dalam HTML yang digunakan untuk menampilkan data secara berurutan ke bawah. Dalam HTML penulisan list menggunakan tag <'li'>. dalam membuat list pada HTML ini terdapat dua jenis tampilan list yang bisa di gunakan yaitu ordered list dan unordered list.
* Ordered list berfungsi untuk menampilkan daftar list dalam bentuk huruf atau angka. tag yang digunakan dalam ordered list ini yaitu <'ol'>.

* unordered list berfungsi untuk menampilkan daftar list dalam bentuk bulatan atau kotak di awalnya. tag yang digunakan untuk membuat unordered list yaitu <'ul'>.

Berikut Contoh Implementasi List Dalam HTML :
Berikut Hasil

```html
<ol>
    <li>belajar html</li>
    <li>belajar css</li>
    <li>belajar database</li>
</ol>
<ul>
    <li>belajar html</li>
    <li>belajar css</li>
    <li>belajar database</li>
</ul>
```

hasil :
<ol>
    <li>belajar html</li>
    <li>belajar css</li>
    <li>belajar database</li>
</ol>
<ul>
    <li>belajar html</li>
    <li>belajar css</li>
    <li>belajar database</li>
</ul>

## 5. Hyperlink
Hyperlink yang sering di kenal dengan link yaitu menghubungkan antara satu dokumen dengan dokumen yang lain pada HTML. Tujuan dari hyperlink ini membuat sebuah teks atau gambar yang ketika diklik akan di alihkan ke halaman tertentu yang sudah di tetapkan dalam penulisan hyerlink tersebut.
Hyperlink sendiri ditulis dengan menggunakan tag <'a>. tag <'a> ini selalu di ikiti oleh atribut href, dimana didalam href (hypertext reference) ini lah yang akan di isikan alamat yang dituju ketika text atau gambar di klik. berikut cara penulisan untuk membuat hyperlink :
```html
<a href=" https://www.youtube.com/">klik disini</a>
```
ketika di klik pada kata “klik disini” maka halaman akan di alihkan ke halaman www.youtube.com hal ini sesuai dengan ketentuan yang telah kita tetapkan pada atribut href .
