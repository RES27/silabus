# HTML

## 1. __Pengenalan HTML__ <br>
HTML (Hyper Text Markup Language) adalah sebuah bahasa formatting yang digunakan
untuk membuat sebuah halaman website.
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


## **3. Pengenalan Tag Pada HTML**
Tag merupakan kode yang digunakan untuk memperkenalkan pada web browser untuk apa
text HTML yang ditulis. 
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
paragraf disini merupakan suatu tag untuk membuat penulisan dalam bentuk paragraf. 
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
 dalam membuat list pada HTML ini terdapat dua jenis tampilan list yang bisa di gunakan yaitu ordered list dan unordered list.
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
Hyperlink yang sering di kenal dengan link yaitu menghubungkan antara satu dokumen dengan dokumen yang lain pada HTML. berikut cara penulisan untuk membuat hyperlink :
```html
<a href=" https://www.youtube.com/">klik disini</a>
```
## 6. Image
Untuk menampilkan gambar dengan HTML, anda bisa menggunakan tag <img>. kemudian masukkan atribut “src=” pada tag <img>.

```html
<img src="nama gambar">
```
