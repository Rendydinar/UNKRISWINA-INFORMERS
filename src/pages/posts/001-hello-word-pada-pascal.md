---
title: 'Hello Word Pada Pascal'
date: 'Jumat 29 Desember 2019 13:06 Pm'
author: 'Umbu Rambu'
image: ../../images/javascript.jpg
tags:
  - pascal
  - programming
---
<br><br>
<h3>Membuat Program Hello Word Pada Pascal</h3>

<p>Hallo sobat coding sekarang kita akan belajar membuat program sederhana menggunakan bahasa pemprograman pascal</p>
<p>Kita akan membuat program yang mencatak kalimat "Hello Word", yups seperti umumnya, ketika seorang programmer hendak ingin mempelajari suatu bahasa program, yang harus dilakukan pertama kali yaitu membuat program hello word</p>
<p>Oke kali ini saya akan membuat program menggunakan</p> 
<ol>
  <b><li>laptop</li></b>
  <b><li>handphone android</li></b>
</ol>


<p>Di laptop saya menggunakan sistem operasi linux (ubuntu) dan pada handphone saya menggunakan applikasi <a href="https://play.google.com/store/apps/details?id=com.duy.pascal.compiler&hl=in">Pascal N-IDE</a>. Oke sekarang kita masuk pada bagian codingnya. Buat file dengan nama "helloWord.pas" (tanpa tanda kutip)
Tuliskan semua kode kedalam file tersebut.</p>

<h4>Langkah-langkah</h4>
<ul>
  <b><li>1. Membuat judul program</li></b>
  <p>Judul program ini digunakan untuk memberi nama program dan sifatnya
optional. Jika ditulis harus terletak pada awal dari program dan diakhiri dengan titik
koma (;)</p>

``` pascal
PROGRAM helloWord
```  
  <b><li>2. Membuat Bagian Pernyataan/Terproses (Badan Program)</li></b>
  <p>Bagian ini adalah bagian yang akan terproses dan terdapat dalam suatu blok yang diawali dengan BEGIN dan diakhiri dengan END (penulisan END diikuti dengan tanda titik). Bagian ini berisi pernyataan / statamen yang merupakan instruksi program. Setiap statemen diakhiri dengan tanda titik koma (;).</p>

```pascal
BEGIN
...
statemen;
statemen;
...
END.
```

  <b><li>3. Menambahkan Statemen Untuk Mencatak  (Writeln/Write)</li></b>
  <p>Statemen Writeln digunakan untuk menampilkan isi dari suatu nilai variabel di layar. pada statemen ini posisi kursor akan pindah ke baris selanjutnya
setelah di cetak. Sedangkan Write tidak memindahkan posisi krusor ke baris selanjutnya setelah di cetak..</p>

```pascal
WRITELN('Hello Word');
```
  <b><li>4. Kode Lengkap</li></b>
  <p>Jadi ini kode lengkapnya</p>

  ```pascal
  PROGRAM helloWord;

  BEGIN
    WRITELN('Hello Word');
  END.
  ```
</ul>

<p>Selanjutnya kita tinggal mengcompile file ini. Karna saya menggunakan linux, saya langsung mengcompile lewat terminal.</p> 
<ul>
  <li>
    <b>Compile programnya</b>
    <img src="https://firebasestorage.googleapis.com/v0/b/unkriswina-informers.appspot.com/o/assets%2Fimg%2FScreenshot%20from%202020-01-07%2021-42-15.png?alt=media&token=254e4e69-fd05-48ba-b3dc-1687de753f4a" alt="image" class="img-fluid" />      
  </li>
  <li>
    <b>Compile sukses, tidak ada yang error</b>
    <img src="https://firebasestorage.googleapis.com/v0/b/unkriswina-informers.appspot.com/o/assets%2Fimg%2FScreenshot%20from%202020-01-07%2021-42-27.png?alt=media&token=ec60137e-e48c-43db-9849-162d3d09b6db" alt="image" class="img-fluid" />      
  </li>
  <li>
    <b>Jalankan program</b>
    <img src="https://firebasestorage.googleapis.com/v0/b/unkriswina-informers.appspot.com/o/assets%2Fimg%2FScreenshot%20from%202020-01-07%2021-42-57.png?alt=media&token=862b46fc-dc61-400d-b916-eea75ea3547f" alt="image" class="img-fluid" />        
  </li>
</ul>

<p>Mantap program hello word kita sekarang sudah berjalan dengan benar, Selamat.</p>
<br><br>
<p>Oke itu saja tutorial dari saya kali ini mengenai pemprograman pascal, semoga kalian menyukainya.</p>
<p>Maaf saya lupa untuk membuat programnya menggunakan Handphone Adroid, tutorialnya next time saja yah 😁</p>
