# Lab2Web

**Nama	   	: Siti Latifah** <br>
**Nim	  	  : 312010321** <br>
**Kelas	  	: TI.20.A2** <br>
**Matkul	  : Pemrograman Web** <br>

# Soal

![Screenshot (66)](https://user-images.githubusercontent.com/73010098/159030944-61f3d41c-ad66-4c23-a749-b8972dd4a6f8.png)

## CSS Dasar

1. Membuat Dokumen HTML

``` html
<!DOCTYPE html>
 <html>
 <head>
     <meta charset="utf-8">
     <meta name="viewport" content="width=device-width, initial-scale=1">
     <title>CSS Dasar</title>
 </head>
 <head>
   </head>
 <body>
 <!-- Judul -->
    <header><h1>CSS Internal Dan <i>inline CSS</i></h1></p>
</header>

<!-- Tag Navigasi -->
<nav>
    <a href="file:///D:/UNIVERSITAS%20PELITA%20BANGSA/CAMPURAN/lab%201/lab1_tag_dasar%20.html">HTML Dasar</a>
    <a href="file:///D:/UNIVERSITAS%20PELITA%20BANGSA/CAMPURAN/lab2_css_dasar.html">CSS Dasar</a>
    <a href="lab2_css_Eksternal.html">CSS Eksternal</a>
</nav>

<!-- CSS ID Selector -->
 <div id="intro">
 <h1>Hello World</h1>
<p style="text-align: center; color: #ccd8e4;"> Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman 
Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat 
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML 
dan CSS.</p>

 <!-- CSS Class Selector -->
 <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
   </div>
   </body>
 </html>
```

## OUTPUT

![Screenshot (62)](https://user-images.githubusercontent.com/73010098/159027473-9b91afb4-0189-40e0-83b2-dc2c6a613ae0.png)

2. Mendeklarasikan CSS Internal

``` html
<head>
     <style>
 body {
 font-family:'Open Sans', sans-serif;
 }
 header {
 min-height: 80px;
 border-bottom:1px solid #77CCEF;
 }
 h1 {
 font-size: 24px;
 color: #0F189F;
 text-align: center;
 padding: 20px 10px;
 }
 h1 i {
 color:#6d6a6b;
 }
 </style>
 </head>
```

## OUTPUT

![Screenshot (62)](https://user-images.githubusercontent.com/73010098/159027998-1f7de1de-a72c-47c5-abd4-c7c0c36ef8d1.png)

3. Menambahkan Inline CSS

``` html
<p style="text-align: center; color: #ccd8e4;"> Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman 
Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat 
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML 
dan CSS.</p>
```

## OUTPUT

![Screenshot (63)](https://user-images.githubusercontent.com/73010098/159028466-d900cf3b-675b-4b2f-840c-f00959829bb1.png)

4. Membuat File Baru dengan Format CSS

![Screenshot (64)](https://user-images.githubusercontent.com/73010098/159028581-bc3c8696-eb12-40ac-b437-95808f8f12dc.png)
 
 Dan membuat Deklarasi CSS
 
 ``` html
nav {
background: #20A759;
color:#fff;
padding: 10px;
}
nav a {
color: #fff;
text-decoration: none;
padding:10px 20px;
}
nav .active,
nav a:hover {
background: #0B6B3A;
}
```
Kemudian tambahkan Tag <link>

``` html
<head>
<!-- menyisipkan css eksternal -->
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
</head>
```
## OUTPUT

![Screenshot (67)](https://user-images.githubusercontent.com/73010098/159029928-e73f827d-15c7-4a11-b26a-a004d884163c.pn

5. Menambahkan CSS Selektor
``` html
/* ID Selector */
#intro {
background: #418fb1;
border: 1px solid #099249;
min-height: 100px;
padding: 10px;
}
#intro h1 {
text-align: left;
border: 0;
color: #fff;
}
/* Class Selector */
.button {
padding: 15px 20px;
background: #bebcbd;
color: #fff;
display: inline-block;
margin: 10px;
text-decoration: none;
}
.btn-primary {
background: #E42A42;
}

## OUTPUT

![Screenshot (61)](https://user-images.githubusercontent.com/73010098/159030692-eafd09b2-de11-4f0d-8747-193bed8d3f3b.png)










