# Summary of All Materials – How to be an Ideal Top Search React JS Front-End Engineer
- [Git](#2-version-control-and-branch-management-git)
- [UI UX](#3-introduction-ui-dan-ux)
- [Figma](#4-figma)
- [HTML](#5-html)
- [CSS](#6-css)
- [Bootstrap](#7-bootstrap)
- [Javascript Refreshment](#8-javascript-refreshment)
- [Clean Code](#9-clean-code)
- [Introduction React](#10-introduction-react)
- [React Fundamental](#11-react-fundamental)
- [React Routing](#12-react-routing)
- [Event Handling](#13-event-handling)
- [React Hook](#14-react-hook)
- [React Form](#15-react-form)
- [Global State Management and Data Fetching](#16-global-state-management-and-data-fetching)
- [Testing](#17-testing)
- [Deployment](#18-deployment)
- [Introduction Algorithm](#19-introduction-algorithm)
- [GraphQL - Basic](#20-graphql---basic)
- [Relational Database](#21-relational-database)
- [GraphQL - Query and Apollo Client](#22-graphql---query-and-apollo-client)
- [GraphQL - Mutation](#23-graphql---mutation)
- [GraphQL - Subscription](#24-graphql---subscription)


# (2) Version Control and Branch Management (Git)
1. Versioning merupakan tindakan untuk mengatur versi dari source code program yang dibuat. 
2. Salah satu tools yang digunakan yaitu Version Control System. VCS yang sering digunakan adalah git yang menggunakan sistem terdistribusi
3. Aturan dalam belkolaborasi adalah pada branch master hanya akan dipakai sebagai branch develop yang dapat diperbarui ketika ada pull request dari branch feature. Pull request sendiri dilakukan ketika feature sudah fix.

# (3) Introduction UI dan UX
## User Experience (UX)
UX merupakan segala sesuatu yang dirasakan oleh user saat memakai produk. UX sendiri memiliki 5 tahapan yakni :
### 1. Emphatize
Memahami apa yang akan dirasakan user saat memakai produk. Penerapan dari emphatize ini adalah dengan user persona yang dapat berisi tentang ekspektasi, kebutuhan, tujuan, dan kebiasaan dari user. User persona sendiri bisa lebih dari satu.
### 2. Define 
Mengidentifikasi informasi yang telah didapat dari tahap emphatize sehingga dapat dkerucutkan menjadi suatu masalah inti yang akan digunakan sebagai tujuan utama dari produk yang dibuat.
### 3. Ideate
Membuat gambaran berupa flow dari setiap task/fitur yang ada dalam produk. Misalnya ada proses pembelian barang pada online shop, alurnya adalah memilih barang -> mengisi formulir pembelian (nama tujuan, alamat tujuan, jumlah barang, pengiriman, pembayaran, dll) -> melakukan pembayaran -> menunggu pengiriman -> barang sampai ke pembeli.
### 4. Prototype
Membuat simulasi final produk untuk pengetesan awal sebelum develop produk. Prototype ini bisa diklik dan berpindah page sesuai flow yang telah dibuat pada proses ideate.
### 5. Validate
Memvalidasi prototype yang telah dibuat kepada user sasaran, stakeholder, dan team untuk diberikan feedback sehingga dapat diperbaiki lagi pada prototypenya. Alur prototype dan validate dapat dilakukan pengulangan sampai prototype yang telah dibuat telah sesuai.

## User Interface (UI)
UI merupakan visual yang digunakan user untuk berinteraksi dengan produk. Berikut merupakan 4 pilar UI : 
### 1. Consistency
Pola dari produk harus sama, supaya user terbiasa dan mudah dalam menggunakan produk. Contoh sederhana peletakan tombol YES dan NO. Jika YES di kanan, maka setiap ada validasi YES dan NO, YES harus selalu di kanan.
### 2. Keep the Interface Simple
Tampilan dari produk simpel, namun jelas sehingga tidak ada elemen-elemen yang tidak penting dan malah mengganggu.
### 3. Good Typography
Tata letak dan penulisan menggunakan pola yang sama dengan menyesuaikan font, ukuran, spasi, dan sebagainya.
### 4. Offer Informative Feedback
Informasi yang ditampilkan dapat dipahami oleh user. Contohnya ada instruksi WAIT, nah itu harus dijelaskan menunggu untuk apa.

# (4) Figma
- [Apa itu Figma ?](#Apa-Itu-Figma-?)
- [Apa Saja yang Dapat Dilakukan di Figma ?](#Apa-Saja-yang-Dapat-Dilakukan-di-Figma-?)
- [Prototyping](#Prototyping)

## Apa Itu Figma?
[Figma](https://www.figma.com/about/) merupakan alat untuk mengedit grafis berupa vektor dan prototyping. Figma biasanya dipakai untuk mendesain mock-up dari suatu project. Figma dapat digunakan secara bersama-sama dengan membuat team secara real time.

## Apa Saja yang Dapat Dilakukan di Figma ?
### 1. Membuat Frame atau Artboard
Kita dapat membuat frame baru dengan klik tombol di bawah ini dan menyesuaikan ukurannya sesuai yang kita butuhkan. <br>
![image](https://user-images.githubusercontent.com/72771774/155835375-81e1afdd-bd00-410b-a98e-bb389d364781.png)<br><br>
![image](https://user-images.githubusercontent.com/72771774/155835392-a3d9a296-eb22-4771-901d-b9b78432d07b.png)

### 2. Grid dan Layout Columns
Biasanya digunakan untuk bantuan jarak atau layouting pada satu frame. Untuk bentuknya sendiri dapat diatur sesuai keinginan, ketebalan grid, vertikal/horizontal, jumlah grid, warnanya, dsb.
![image](https://user-images.githubusercontent.com/72771774/155835436-397a079f-dc41-4e8d-abff-e21e040e981c.png)

### 3. Layers and Groups
Kita dapat melihat layer dan grouping pada samping kiri layar. Berikut contohnya : <br>
![image](https://user-images.githubusercontent.com/72771774/155835482-26fc3cb9-508c-48b0-90f8-d21049f7895d.png)

### 4. Images
Kita dapat menambahkan image dan mengeditnya dengan tools yang tersedia.<br>
![image](https://user-images.githubusercontent.com/72771774/155835558-bbe02a72-5b13-42fe-91de-4465eb9c7b7c.png)

### 5. Typography
Kita juga bisa menambah dan mengedit suatu teks baik ukuran, alignment, leading , kerning, tracking, warna, dsb.<br>
![image](https://user-images.githubusercontent.com/72771774/155835596-8eccf46f-c8e1-4574-8f21-ace685199f83.png)

## Prototyping
[Prototype](https://en.wikipedia.org/wiki/Prototype) berfungsi sebagai gambaran dari bentuk produk yang akan dikembangkan. Pada pembuatan prototype pada figma kita bisa menghubungkan frame, mengatur scrolling, mengatur animasi, hover, dan masih banyak lagi.
![image](https://user-images.githubusercontent.com/72771774/155835691-3aa012d2-7fcd-40bf-88d1-de4d97b811b4.png)


# (5) HTML
- [Apa itu Frontend ?](#frontend)
- [Apa itu HTML ?](#html)
- [Apa Saja yang Ada di HTML ?](#inside)
- [Lebih Banyak](#lebih-banyak)

<a name="frontend"></a>
## Apa itu Frontend ?
[Front-end](https://en.wikipedia.org/wiki/Front-end_web_development) merupakan bagian dari web yang membuat tampilan web menarik. Seorang Front-End Web Developer bertanggung jawab langsung kepada pengalaman pengguna dengan merancang aplikasi web agar responsif, interaktif, dan juga user friendly.
Front-end sendiri disusun menggunakan <img alt="HTML" width="25px" src="https://cdn-icons-png.flaticon.com/512/919/919827.png" /> HTML(The HyperText Markup Language), <img alt="HTML" width="25px" src="https://cdn-icons-png.flaticon.com/512/919/919826.png" /> CSS(Cascading Style Sheets), dan <img alt="HTML" width="25px" src="https://cdn.iconscout.com/icon/free/png-256/javascript-2038874-1720087.png" /> JS(JavaScript)

<a name="html"></a>
## Apa itu HTML ?
HTML merupakan standar yang digunakan secara luas untuk menampilkan halaman web. Kegunaanya sendiri adalah untuk menambahkan isi atau konten dari website yang dibuat.

<a name="inside"></a>
## Apa Saja yang Ada di HTML ?
- [Struktur](#struktur)
- [Elemen](#elemen)
- [Panulisan Text](#penulisan-text)
- [Tag Link dan Embedding Media](#tag-link-dan-embedding-media)
- [Form](#form)
- [Tabel](#tabel)

### Struktur
| Tag | Fungsi |
| --- | --- |
| `<html>` | Elemen Root HTML |
| `<head>` | Informasi Meta tentang Dokumen |
| `<title>` | Judul Dokumen yang Muncul pada Browser |
| `<body>` | Konten Web Page |

### Elemen
| Tag | Fungsi |
| --- | --- |
| `<div>` | Elemen Pembungkus Suatu Bagian |
| `<ol>` | Membuat List Berurutan |
| `<ul>` | Membuat List Tidak Berurutan |
| `<li>` | List Item |
| `<br>` | Menambahkan Enter |

### Penulisan Text
| Tag | Fungsi |
| --- | --- |
| `<h1>` - `<h6>` | Merupakan Teks Heading Terbesar-Terkecil |
| `<p>` | Merupakan Teks Paragraf |
| `<strong>` | Membuat Teks Tebal |
| `<em>` | Membuat Teks Miring |
| `<s>` | Membuat Teks Tercoret |

### Tag Link dan Embedding Media
| Tag | Fungsi |
| --- | --- |
| `<a href = [link]>` | Mengarah ke Link |
| `<image src = [link]>` | Menambahkan Gambar |
| `<video src = [link]>` | Menambahkan Video |
| `<audio src = [link]>` | Implemen Audio |
| `<embed src = [link]>` | Implemen Media dengan Tipe Apapun |

### Form
| Tag | Fungsi |
| --- | --- |
| `<form>` (elemen) | Membuat Form pada HTML |
| `<textarea>` (elemen) | Membuat Input Teks Panjang |
| `<select>` (elemen) | Membuat Input Pilihan Berupa Dropdown |
| `<datalist>` (elemen) | Membuat Tabel pada HTML |
| `<label>` (elemen) | Membuat Labeling dari ID Input yang Sama |
| `<input>` `name` (elemen) | Merupakan Kata Kunci dengan Value = Input |
| `<input>` tipe : `text` | Input Berupa Text |
| `<input>` tipe : `checkbox` | Input Berupa Checkbox |
| `<input>` tipe : `number` | Input Berupa Angka |
| `<input>` tipe : `range` | Input Berupa Range |
| `<input>` tipe : `radio` | Input Berupa Pilihan Berbentuk Radio Button |
| `<input>` tipe : `password` | Input Berupa Password (hidden) |

Selain itu, berikut atribut yang biasa digunakan dalam form : <br>
| Atribut | Fungsi |
| --- | --- |
| `max` | Parameter Maksimal dari Input |
| `min` | Parameter Minimal dari Input |
| `maxlength` | Panjang Maksimal dari Input |
| `minlength` | Panjang Minimal dari Input |
| `pattern` | Syarat Pattern agar Input Tervalidasi |
| `required` | Harus Diisi |


### Tabel
| Tag / Atribut | Fungsi |
| --- | --- |
| `<table>` | Membuat Tabel pada HTML |
| `<thead>` | Heading dari kolom yang dibuat dengan row |
| `<tbody>` | Memuat data tabel selain heading dan footer |
| `<th>` | Menandakan judul kepada baris/kolom |
| `<tr>` | Manandakan Baris |
| `<td>` | Menandakan Kolom |
| `<tfoot>` | Membuat Konten Footer |
| `rowspan` (atribut) | Span Baris |
| `colspan` (atribut) | Span Kolom |

### Lebih Banyak
Jika ingin tahu lebih banyak mengenai HTML beserta contohnya dapat mengakses link berikut :
- https://www.codecademy.com/learn/learn-html
- https://www.w3schools.com/html/
- https://www.tutorialspoint.com/html/index.htm
- https://www.petanikode.com/tutorial/html/

# (6) CSS
- [Apa Itu CSS ?](#css)
- [3 Cara menambahkan CSS](#metode)
- [Syntax pada CSS](#syntax)
- [About Bootstrap](#about-bootstrap)

<a name="css"></a>
## Apa Itu CSS
CSS (Cascading Style Sheet) digunakan untuk styling pada website. Kita dapat menghias website dengan mengubah warna, ukuran, font, background. panjang, lebar, dll. Selian itu kita juga dapat mengatur peletakan suatu komponen dengan float, align, display, position, dll.

<a name="metode"></a>
## 3 Cara menambahkan CSS
### 1. External CSS
Pada External CSS, CSS diletakkan pada file lain berekstensi .css. Lalu supaya CSS dapat terapply pada website, harus menambahkan syntax `<link rel="stylesheet" href="[namafile].css">`pada bagian `<head>` file HTML.
### 2. Internal CSS
Pada Internal CSS, CSS dapat diletakkan pada file HTML baik di dalam `<head>` maupun `<body>`. Syntax CSS akan dibungkus dengan `<style>.
```html
<style>
body {
  background-color: #19355f;
}
h1 {
  color: #f47523;
  margin-left: 40px;
}
</style>
```
### 3. Inline CSS
Pada Inline CSS, CSS dapat diletakkan pada suatu elemen tunggal dalam file HTML. Metode ini diprioritaskan untuk menerapkan style yang unik pada elemen tersebut.
```html
<h1 style=”color: #19355f;”>Hello World</h1>
``` 
<a name="syntax"></a>
## Syntax pada CSS
### 1. Syntax Umum
Contoh : <br>
```css
.komponen1{
    background-color:beige;
    color: #000;
}```
Pada syntax di atas dapat didefinisikan :
- `.komponen1` merupakan **class**
- Syntax di dalam tanda kurung merupakan **deklarasi**
- `background color` dan color` merupakan **property**
- `beige`, `#000` merupakan **value**

### 2. CSS Selector
- ID(#)
ID dapat digunakan pada elemen yang unik dan setiap elemen hanya memiliki satu tag ID
- Class(.)
Class dapat dipakai berulang-ulang pada halaman yang sama dan satu elemen boleh memiliki lebih dari satu class.

### 3. CSS Grouping
Satu bundle styling, dapat digunakan oleh lebih dari satu id/class.
```css
.menu,
.list{ 
    background-color: brown;
    color: #fff;
}
```

### 4. CSS Fonts
| Syntax | Fungsi |
| --- | --- |
| `font` | Menetapkan semua property font dalam satu deklarasi |
| `font-family` | Menentukan kelompok font teks |
| `font-size` | Menentukan ukuran font teks |
| `<body>` | Konten Web Page |
| `font-size` | Menentukan ukuran font teks |
| `font-weight` | Menentukan ketebalan font teks |
| `font-style` | Menentukan kemiringan font teks |

### 5. CSS Margin dan Padding 
Amati gambar berikut untuk memahami mengenai margin dan padding <br>
![mp](https://user-images.githubusercontent.com/72771774/156723382-2364fbf2-ab50-4301-9111-b514a48d63e4.PNG)

### 6. CSS Background
| Syntax | Fungsi |
| --- | --- |
| `background-color` | Menetapkan warna background pada suatu elemen |
| `background-image` | Menentukan gambar background pada suatu elemen |
| `background-repeat` | Menentukan gambar background untuk di ulang |
| `background-size` | Menentukan ukuran gambar untuk background |
| `background-position` | Mengatur posisi awal gambar background |

### 7. CSS Link
- `:hover` merupakan kondisi ketika pointer berada di atas suatu elemen
- `:active` merupakan kondisi ketika elemen diklik
- `:visited` merupakan kondisi ketika suatu elemen link telah dikunjungi

### 8. CSS Transition
Memberikan waktu saat terjadi perubahan sehingga perubahan bergerak secara mulus.
Contoh : 
```css
.teks{
    transition: color 0.3s ease;
}
.teks{
    color: #fff;
}
```
### 9. CSS Display 
| Syntax | Fungsi |
| --- | --- |
| `block` | Elemen block selalu dimulai pada baris baru. (dimulai dari kiri ke kanan). |
| `inline-block` | Elemen inline-block membutuhkan lebar sesuai yang diperlukan |
| `none` | Elemen tidak tampil |

## About Bootstrap
[Bootstrap](https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)) merupakan suatu framework CSS gratis yang responsif. Di dalamnya terdapat CSS dan JavaScript template. Penggunaan framework ini mempermudah kita untuk membangun front-end dari website dengan responsive. Adapun cara penggunaannya dapat dengan mendownload asset dari bootstrap atau dengan menyalin link yang ada di sini : [Link Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/). 

## More Info
https://www.w3schools.com/css/

# (7) Bootstrap
- [Apa Itu Bootstrap ?](#pengertian)
- [Font Awesome](#font-awesome)
- [Penggunaan Bootstrap](#penggunaan-bootstrap)

<a name="pengertian"></a>
## About Bootstrap
[Bootstrap](https://en.wikipedia.org/wiki/Bootstrap_(front-end_framework)) merupakan suatu framework CSS gratis yang responsif. Di dalamnya terdapat CSS dan JavaScript template. Penggunaan framework ini mempermudah kita untuk membangun front-end dari website dengan responsive. Adapun cara penggunaannya dapat dengan mendownload asset dari bootstrap atau dengan menyalin link yang ada di sini : [Link Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/).

## Font Awesome
[Font Awesome](https://en.wikipedia.org/wiki/Font_Awesome) merupakan *toolkit* font dan icon yang berbasis CSS. Font Awesome biasanya dipakai untuk memudahkan pembuatan icon dan styling font pada website. Penggunaannya cukup mudah, yakni dengan menambahkan `<script>` dari font awesome di dalam `<head>` atau dengan mendownload assetnya. Setelah itu, ketika ingin menambahkan icon, kita tinggal mencarinya di [Web Font Awesome](https://fontawesome.com/) lalu meng*copy* syntax HTML-nya.

## Penggunaan Bootstrap
Bootstrap memiliki banyak fitur yang dapat digunakan diantaranya : 
- Layout
	-Breakpoint
	Bootstrap memiliki 6 deafult breakpoints, yaitu :
		- x-small(`None`)
		- small(`sm`)
		- medium(`md`)
		- large(`lg`)
		- extra large(`xl`)
		- extra extra large(`xxl`).
	- Botstrap memiliki 3 container default, yaitu :
		- `.container` yang mempunyai setting lebar `max-width` 
		- `.container-fluid` yang mempunyai setting lebar `width:100%`
		- .container-[breakpoint] yang mempunyai setting lebar `width:100%` sampai breakpoint yang dituliskan
	- Grid dan column
		grid sistem di bootstrap daat mengadaptasi 6 breakpoint yang ada atau dapat dicustom. Jumlah kolom dalam grid adalah 12 kolom. Default penggunaannya adalah dengan `.row` dan `col-[jml column]`
- Content
	- Typography
		- `h1` - `h6`
		- Display
			Penggunaannya adalah dengan `display-1` -`display-6`. Adapun ukuran default dari bootstrap adalah sebagai berikut:
			```js
				$display-font-sizes: (
				1: 5rem,
				2: 4.5rem,
				3: 4rem,
				4: 3.5rem,
				5: 3rem,
				6: 2.5rem
				);

				$display-font-weight: 300;
				$display-line-height: $headings-line-height;
			```
		- Lead
			Untuk membuat paragraf stand out dengan `.lead`
		- Inline text elemen
			Styling teks pada umumnya dengan `.mark`, `.small`, `.text-decoration-underline`, dan lain-lainaccordion-item`, `accor
		- Alignment
			Digunakan untuk mengatur posisi teks, contohnya dengan `text-center` untul menengahkan teks, `text-end` untuk membuat posisi teks di kanan.
		- Unstyled list
			Dengan `list-unstyled`, style defaul list yang berbentuk bulat akan dihilangkan
		- Inline
			Kita dapat membuat suatu list menjadi satu line dengan `.list-inline` dan `.list-inline-item`
	- Image
		- Responsive Image
			Dengan menggunakan `.img-fluid` yang mengaplikasikan `max-width: 100%;` dan `height: auto;`
		- Image thumbnail
			Gambar dapat diberi border dengan `.img-thumbnail`
		- Aligning Image
			Untuk mengatur posisi image digunakan `.float-start` dan `.float-end`. Selain itu, untuk membuat image round, maka digunakan `.rounded`
	- Table
		- Menggunakan `.table`
		- Terdapat beberapa tema, seperti primary, secondary, success, danger, warning, info, light, dan dark
		- Dapat membuat tabel berstyle zebra dengan `.table-striped`
		- Dapat membuat baris dihover dengan `.table-hover`
- Forms
	- Menggunakan `.form-control`
	- Membuat select menu dengan `.form-select`. Dapat juga diresize dengan `.form-select[breakpoints] 
	- Disable dengan menggunakan `.disabled`
	- Membuat form yang dapat dicentang dengan `.form-check` dengan bermacam tipe, contohnya checkbox, radio, dan switch
	- Dapat membuat form berupa range dengan `.form-range` dan dapat diedit dengan `min` dan `max`
	- Dapat membuat label menjadi mengambang di atas ketika sedang mengisi form dengan `form-floating`
	- Form juga dapat mengimpelemntasi class untuk layout dengan `row` dan `col`
- Components
	- Accordion
		Fitur ini untuk membuat accordion item berupa header dan juga konten di dalamnya. Penggunaannya dengan `accordion`, `accordion-header`, dan `accordion-body`. contohnya adalah sebagai berikut : 
		```html
			<div class="accordion" id="accordionExample">
			<div class="accordion-item">
				<h2 class="accordion-header" id="headingOne">
				<button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
					Accordion Item #1
				</button>
				</h2>
				<div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
				<div class="accordion-body">
					<strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
				</div>
				</div>
			</div>
		```
	- Dapat membuat alert dengan `alert-[tema-warna]`
	- Badge yang biasanya dibuat untuk notifikasi kecil di dekat icon, sehingga menggunakan `.badge`, `rounded-pills`, dan dapat diposisikan sesuai keinginan.
	- Breadcrumb yang biasanya ada di atas page yang menunjukkan direktori saat ini dengan menggunakan `.breadcrumb` dan `active`
	- Button `.btn` dapat dikombinasikan dengan class lain untuk styling baik warna, posisi, dan bentuknya
	- Card dapat diimplementasikan dengan menggunakan satu atau beberapa class berikut : `.card`, `.card-img`, `card-header`, `.card-title`, `.card-subtitle`, `.card-body`, `.card-text`, `.card-link`, dan dapat juga dikombinasikan dengan list, ataupun yang lain.
	### Other
	Selain yang suda ada di atas, terdapat Carousel, Collapse, Dropdowns, Modal, Navbar, dan lain-lain yang dapat dilihat lebih lengkapnya di [Dokumentasi Bootstrap](https://getbootstrap.com/docs/5.1/getting-started/introduction/).

# (8) Javascript Refreshment
- [Apa Itu Javascript ?](#pengertian)
- [In Javacript](#in-javascript)
  - [Perbedaan Var, Let dan Const](#perbedaan)
  - [Values and References](#values-and-references)
  - [Destructuring](#destructuring)
  - [Spread](#spread)
  - [Method](#method)
  - [Control Flow](#control-flow)
  - [Function](#function)
  - [Async - Await](#async)
  - [Class](#class)
  - [Document Object Model](#dom)
- [Referensi](#referensi)

<a name="pengertian"></a>
## Apa Itu Javascript ?
<img alt="HTML" width="25px" src="https://cdn.iconscout.com/icon/free/png-256/javascript-2038874-1720087.png" />[Javascript](https://en.wikipedia.org/wiki/JavaScript) merupakan bahasa pemrograman populer untuk membangun web yang **high level** (yang dapat dibaca oleh manusia), scripting, untyped, dan intrepeted.

## In Javascript
<a name="perbedaan"></a>
### Perbedaan Var, Let dan Const
| Jenis | Declaration | Redeclaration | Reassignment | Hoisting |
| --- | --- | --- | --- | --- |
| Var | V | V | V | V | V |
| Let | V | | V | |
| Const | | | | |

- Pada declaration, kita harus memberikan value pada `const`. Deklarasi sendiri merupakan proses pembuatan variabel untuk menyimpan data. Contoh `var num`, `let name`
- Hanya `var` yang dapat dideclare ulang.
- Reasignment merupakan proses mengganti value. `const` tidak dapat diganti valuenya, dengan kata lain akan selalu sama valuenya sampai akhir.
- Hoisted merupakan pemanggilan sebelum deklarasi. Yang dapat menerapkan hoisted adalah `var` dan `function`

### Values and References
Nilai primitif (string, boolean, number, bigint, undefined, null, dan symbol) dapat diteruskan atau dipassing nilainya antar variabel. Sedangkan nilai reference hanya dapat dipakai oleh satu variabel

### Destructuring
Fungsi dari destructuring adalah untuk **menyalin nilai array atau properti objek** ke dalam variabel yang berbeda.
Catatan : menggunakan const ketika nilai kosong atau undefined tidak akan error.<br>
Contoh : 
```js
const foo = ['Budi', 'Sita', 'Ayu'];
const [A, B, C] = foo;

console.log("a adalah " + A);
console.log("b adalah " + B);
console.log("c adalah " + C);
```

### Spread
Spread digunakan ketika **semua elemen** dalam array atau object perlu dimasukkan ke dalam daftar.<br>
Note : ketika menyalin lebih dari satu object, dan saat property object ada yang sama, maka diambil yang terakhir.

### Method
Merupakan sebuah fungsi yang terkait dengan object yang memiliki kegunaan tertentu.
- Concat = Menggabungkan 2 atau lebih array
- Map = Membuat array baru dengan hasil memanggil fungsi untuk setiap elemen array
- Foreach = Memanggil fungsi untuk setiap elemen array
- Slice = Memilih bagian array dan mengembalikan array baru
- Filter = Membuat array baru dengan suatu syarat
- Reduce = Melakukan operasi pada setiap elemen menjadi nilai tunggal (kiri ke kanan)

### Control Flow
- Loop/Iterasi contohnya : for, while, do while
- Percabangan contohnya : if else, switch, block, try, catch, throw, break, continue

### Function 
Function merupakan sebuah objek yang memiliki properti dan method. Fungsi melakukan serangkaian prosedur yang dapat digunakan berulang kali hanya degan memanggilnya setiap dibutuhkan. Function dapat digantikan dengan arrow (=>).<br>
Contoh : 
```js
let bdays = ['10-17', '05-19', '20-19'];
console.log("Nilai bdays adalah : " + bdays);

let bdaysMod = bdays.map(x => x.replace('-', '/'));
console.log("Nilai bdays setelah dimodifikasi adalah : " + bdaysMod);
```

<a name="async"></a>
### Async - Await
- Synchronous = Mengeksekusi program sesuai urutan.
- Asynchrounous = Mengeksekusi program berdasarkan waktu proses. Di sini kita dapat menunda eksekusi dengan menambahkan `setTimeout(()=>{}, [waktu ms])
- Callback = Fungsi yang dijadikan parameter ada fungsi lain.
- Promise = Objek yang merepresentasikan keberhasilan/kegagalan suatu proses.
- Await = Menghentikan eksekusi untuk menunggu promise selesai

### Class
Prototype dari suatu objek yang akan dibuat. Class memiliki nama, constructor, attributes, dan method.
- Constructor = Method di dalam class yang akan terpanggil pertama kali saat membuat object
- Method =  Fungsi yang berada dalam class
- Attributes = Kumpulan variabel yang membentuk object pada class
- Extends = Membuat class anak. Class anak akan mewarisi semua atribut dan method class induk

<a name="dom"></a>
### Document Object Model (DOM)
API untuk HTML yang merepresentasikan webpage pada dokumen menjadi object
#### DOM Selection
- getElementById()
- getElementsBtTagName()
- getElementsByClassName()
- querySelector()
- querySelectorAll()
#### DOM Manipulation
| Event | Kegunaan |
| --- | --- |
| element.innerHTML | Merubah isi dari tag yang sudah diseleksi |
| element.style<propertyCSS> | Merubah style dari tag yang sudah diseleksi |
| element.setAttribute() | Mengelola/memanipulasi attribut yang sudah diseleksi | 
| element.classList.add() | Mengelola/memanipulasi class yang sudah diseleksi | 

#### DOM Event
| Event | Kegunaan | 
| --- | --- |
| onclick | Ketika diklik |
| onchange | Digunakan dalam kombinasi dengan validasi bidang input | 
| onblur | Ketika meninggalkan kolom input | 
| onmouseover | Ketika hover | 
| onmouseout | Ketika mengarahkan mouse keluar object |
| oncopy | Ketika mengcopy object |
 
## Referensi
- https://www.w3schools.com/js/
- https://www.w3schools.com/js/js_htmldom.asp
- https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction

# (9) Clean Code
- [About Clean Code](#about-clean-code)
- [Karakteristik Clean Code](#karakteristik-clean-code)
- [Clean Code Principle](#clean-code-principle)

## About Clean Code
Clean code diperlukan dengan tujuan membuat kode rapi dan baik. Setiap potongan kode memiliki arti dan fungsi sesuai dengan tugasnya. Clean code akan sangat berguna ketika project dikerjakan secara kolaborasi dimana akan memudahkan developer saling memahami code yang telah dibuat. Clean code juga penting untuk maintenance project kedepannya, developer yang akan datang dapat memperbaiki kode yang telah dibuat masa lalu tanpa mengulanginya kembali.

## Karakteristik Clean Code
### 1. Mudah Dipahami
Dalam hal ini, penamaan variabel, class, fungsi, dll harus mudah dipahami dengan menamai sesuai tugasnya.
### 2. Mudah Dieja dan Dicari
Penamaan harus mudah dieja. Misalkan penamaan dengan '_' atau menggunakan camelCase ketika menamai fungsi dan PacalCase ketika menamai class.
### 3. Singkat namun Jelas
Penamaan harus singkat namun juga jelas. Contonya kita mau membuat fname, langsung saja pakai fullName.
### 4. Konsisten
Konsistensi itu penting supaya kode mudah dibaca. Misal kalau lowercase lowercase semua pada tipe itu.
### 5.Hindari Penamahan Konteks yang Tidak Perlu
Penamaan harus jelas tidak berbelit. Contohnya ada class `Car` di dalamnya ada `carColor`. Kita langsung saja pakai `color`.
### 6. Komentar
Komentar ada, namun jangan terlalu banyak (setiap block).
### 7. Good Function
Contoh dari kasus ini adalah parameter yang digunakan function lebih baik dijadikan sebuah object ketika terdapat banyak parameter yang saling berhubungan
### 8. Gunakan Konvensi 
Style Guide :
- [airbnb Javascript Style Guide](https://github.com/airbnb/javascript)
- [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)
### 9. Formatting
Format-format yang berhubungan dengan typography pengetikan kode. Disarankan menggunakan `prettier`, `formatter`, `beautify`, atau yang lainnya.

## Clean Code Principle
- **KISS (Keep It So Simple)** Hindari membuat satu fungsi untuk melakukan banyak perkerjaan.
- **DRY (Don't Repeat Yourself)** Hindari duplikasi kode


# (10) Introduction React
- [Mengenal React](#mengenal-react)
- [Kelebihan React](#kelebihan-react)
- [DOM dan VDOM](#dom-dan-vdom)
## Mengenal React
Library javascript untuk membuat UI yang interaktif dan cepat baik pada web maupun mobile.

## Kelebihan React
1. React bersifat deklaratif, yakni berfokus kepada apa tujuannya.
2. React berasis kepada komponen, setiap komponen memiliki tugas yang spesifik masing-masing.
3. React merupakan library yang populer dan konsep penggunaannya mirip dengan ios dan android sehingga layak untuk dipelajari.

## DOM dan VDOM
Manipulasi dom merupakan kunci dari web yg modern dan interaktif. Namun, manipulasi DOM secara manual memiliki kekurangan seperti berikut : 
1. Manipulasi dom manual dapat membuat kode berantakan
2. Sulit mengigat DOM state sebelumnya
3. Jauh lebih lambat daripada operasi JS pada umumya
Maka dari itu, digunakan VDOM yang merupakan representasi dari UI yang berbentuk Javascript Object yang tersimpan di dalam memori.

# (11) React Fundamental
- [Javascript XML](#javascript-xml)
- [React Component](#react-component)
- [React Lifecycle](#react=lifecycle)
- [More About Rendering](#more-about-rendering)

## Javascript XML
JSX merupakan ekstensi dalam javascript dengan dasar fakta bahwa logika rendering terikat dengan logic dasi UI.

## React Component
Komponen react merupakan bagian kode yang digunakan untuk menentukan suatu tampilan, behavior, ataupun state dalam UI.
Dalam satu page website dapat dibagi menjadi dalam beberapa komponen, misalnya ada header, footer, title, dan description.

## React Lifecycle
- render() = merupakan lifecycle method yang digunakan di seluruh class react karena render() merupakan metode yang diperlukan dalam komponen class pada react.
- componentDidMount() = Dipanggil ketika komponen sudah dirender untuk pertama kali
- componentDidUpdate() = Dipanggil ketika terjadi update baik di props maupun state
- componentWillUnmount() = Dipanggil ketika komponen akan dihancurkan

## More About Rendering
### Render Bersyarat
Dengan ini, kita dapat merender sebagian kode berdasarkan state. Penggunaannya biasanya menggunakan if else, ternary operator, dll. Kita juga dapat mencegah komponen untuk dirender dengan mengembalikan nilai null.
Contoh :
```jsx
export default function MainPage({lists}){
    return(
        <>
            {lists.map((list)=> <TodoList key={list.id} list={list}/>)}
        </>
    );
} 
```
### Render List
Kita dapat merender item pada setiap list dengan menggunakan tanda kurung kurawal {}. Penerapannya adalah dengan menggunakan map.
Contoh  : 
```jsx
export default function TodoList({list}){
    const isCompleted  = list.completed;
    return(
        <div className="task">{
            isCompleted ? 
            <s>{list.title}</s> : {list.title}
        }
        </div>
    )
}
```

# (12) React Routing
- [Router](#router)
- [URL Parameter](#url-parameter)
- [Hook Routing](#hook-routing)
## Router
### Router adalah modul dalam react yang bertugas melakukan proses navigasi pada single page application. Cara kerjanya adalah dengan mererender konten yang ada pada web app. <br>
cara install router : `npm install react-router-dom` <br>
contoh router pada v6
```
<Router>
      <Header kiri="ToDo" kanan="List"/>
      <Routes>
        <Route
          path="/"
          element={lists.map((list) => (
            <TodoList key={list.id} list={list} />
          ))}
        />
        <Route path="/about/about-app" element={<AboutApp />}/> 
        <Route path="/about/about-author" element={<AboutAuthor />}/>
        <Route path="*" element={<NoMatch />} />
      </Routes>
    </Router>
```
### URL Parameter 
URL Parameter adalah parameter yang nilainya ditetapkan secara dinamis di URL halaman. Sehingga memungkinkan rute untuk merender komponen yang sama dan dapat mengubah datanya berdasarkan parameter.
Link VS Redirect
| Link | Redirect |
| --- | --- |
| Dapat digunakan pada kondisi apapun | Lebih sering digunakan pada halaman 404 |
| Memberikan history baru pada browser | Menimpa history browser |
| Bereaksi dengan 'click' seperti `a href` | Bereaksi dengan suatu kondisi |

### Hook Routing
#### useHistory
Memudahkan untuk navigasi instance riwayat. Contoh : length, go, goBack, goForard, Push, dll
#### useParams 
Mengembalikan objek pasangan (kunci dan nilai parameter) url. Digunakan untuk mengakses match.params dari <Route> saat ini.
#### useRouteMatch
useRouteMatch mencocokkan URL sama seperti <Route> namun tidak benar-benar merender <Route>

# (13) Event Handling
- [Apa Itu State?](#apa-itu-state?)
- [Statefull VS Stateless](#statefull-vs-stateless)
- [Event Handling](#event-handling)

## Apa Itu State?
State merupakan suatu data pada sebuah komponen yang bersifat private sehingga tidak bisa diakses pada komponen lainnya. Modifikasi state dapat menggunakan `setState`. Setiap trjadi modifikasi, komponne akan dirender ulang.

## Statefull VS Stateless
Statefull component adalah komponen yang memiliki state, sedangkan stateless component tidak memiliki state.
Statefull component digunakan saat ada interaksi data dalam suatu komponen dimana akan ada data yang dapat dimodifikasi pada komponen tersebut, sedangkan stateless component tidak menerapkan interaksi data yang tujuannya memang untuk visualisasi. 

## Event Handling
Event handling akan terjadi ketika pengguna memberikan aksi pada suatu komponen. Adapun contoh dari event handling adalah sebagai berikut : 
- Clipboard Events = ketika promise terpenuhi
- Form Events = onChange, onSubmit
- Mouse Events = onClick, onDoubleClick, onMouseOver
- GenericEvents = onError, onLoad 

# (14) React Hook
- [Apa Itu Hooks?](#apa-itu-hooks?)
- [useState](#usestate)
- [useEffect](#useeffect)

## Apa Itu Hooks?
Hooks membuat kita dapat mengakses state dan beberapa fitur lain melalui function, sehingga kita tidak perlu menggunakan class lagi.
### Hooks pada react :
- useState
- useEffect
- useContext
- useReducer
- useCallback
- useMemo
- useRef
- etc
### Aturan Pada Hooks
1. Hooks hanya dipanggil di top level (jangan dipanggil di dalam loops, condition, atau nested function)
2. Panggil hooks dari fungsi react baikd dari komponen fungsi react atau custom

## useState
Merupakan state yang digunakan dalam function, untuk syntaxnya adalah sebagai berikut : 
`const [state, setState] = useState(0)`
Pada syntax di atas, 
1. `state` menunjukkan variabel state.
2. `setState` merupakan fungsi yang akan dipanggil ketika akan mengubah state
3. `0` merupakan nilai awal dari sebuah state
**Note : perlu diketahui, bahwa `state` dan `setState` dapat diubah namanya, nilai `0` juga dapat diubah baik berubah nilai maupun tipe data**

## useEffect
Dengan useEffect, kita dapat melakukan side effect di dalam function component. useEffect sendiri merepresentasikan componentDidMount, componentDidUpdate, dan componentWillUnmount yang ada di dalam class component.
### Ada dua jenis useEffect : 
#### Butuh pembersihan
- Mengatur subscription ke beberapa eksternal data
#### Tidak butuh pembersihan
- Memperbarui dom
- Permintaan jaringan
- Mutasi DOM secara manual
- Pencatatan 


# (15) React Form
- [Form](#form)
- [Controlled Component vs Uncontrolled Component](#controlled-component-vs-uncontrolled-component)
- [Basic Validation](#basic-validation)

## Form
Saat kita mengembangkan aplikasi website yang interaktif, peran form sangat diperlukan. Form dapat menghandle inputan yang diberikan oleh user. Contoh yang sering kita jumpai adalah form registrasi/login.

## Controlled Component vs Uncontrolled Component
### Controlled Component
Di sini, kita memanfaatkan state yang ada pada react. Komponen react yang merender form akan mengontrol kegiatan yang terjadi pada form pada masukan user selanjutnya.

### Uncontrolled Component
Di sini, data form akan ditangani oleh DOMnya. Untuk mendapatkan nilai form dari DOM, kita dapat menggunakan `ref`. Jika di controlled component menggunakan state, di sini kita menggunakan `defaultValue`

### Controlled vs Uncontrolled
| Fitur | Controlled | Uncontrolled |
| --- | --- | --- |
| Pengambilan value di satu waktu | V | V |
| Validating on Submit | V | V |
| Instant field validation | X | V |
| Several inputs for one piece data | X | V |
| Dynamic inputs | X | V |
| Enforcing input format | X | V |
| Conditionally disabling submit button | X | V |

## Basic Validation
### Manfaat validasi
- Menyaring input data yang benar agar aplikasi berjalan dengan lancar
- Melindungi akun user, contohnya pada pembuatan password
- Melindungi sistem aplikasi

### Tipe Validasi
#### 1. Client-side
Validasi yang dilakukan pada sisi klien (browser). Validasi ini dilakukan saat data belum dikirim ke server, sehingga pengguna tidak perlu menunggu respon dari server.
#### 2. Server-side
Validasi yang dilakukan pada sisi server. Setelah user submit inputannya, server memvalidasi inputan dari user sebelum dikirim ke database, setelah itu baru mengirim respon ke user. 

### Built-in Form Validation
- type = menentukan bentuk data
- required = harus diisi
- min & max = batasan untuk input tipe number
- minlength & maxlength = batasan untuk input tipe text
- pattern = batasan yang mendefinisikan pola data yang boleh dimasukkan

### Menggunakan Javascript
- onChange = validasi akan dilakukan setiap ada perubahan
- onSubmit = validasi dilakukan setiap submit inputan

# (16) Global State Management and Data Fetching
- [Global State Management](#global-state-management)
- [Redux Thunk](#redux-libraries-and-tools)
- [Menyimpan State ke Storage](#menyimpan-data-ke-storage)
- [Data Fetching](#data-fetching)

## Global State Management
### Kapan Menggunakan Redux ?
1. Banyak state yang tersebar ke banyak tempat
2. State sering berubah
3. Logic perubahan state kompleks
4. Ukuran codebase yang menengah keatasdan sedang dikerjakan oleh banyak orang
5. Perlu mengetahui bagaimana state diubah seiring waktu

### Redux Libraries and Tools
1. React-Redux
2. Redux Toolkit
3. Redux DevTools Extension

### Komponen Redux
1. Actions = Memberikan informasi dari aplikasi ke store
2. Reducer = Fungsi javascript yang mengambil input berupa state saat ini dan action objek dan output state baru
3. Store = Objek sentral yang menyimpan state pada aplikasi

### Memakai dan Mengubah State 
1. Hooks = Menggunakan `useSelector` dan `useDispatch`
2. Connect = Menggunakan fungsi `mapStateToProps`, fungsi/ objek mapDispatchToProps`, fungsi `mergeProps, dan objek `options`

## Redux Thunk
Thunk Middleware memungkinkan untuk membuat action creator yang mengembalikan fungsi. Redux Thunk digunakan untuk menghandle side effect logic seperti logic sync kompleks yang perlu mengakses store dan logic async seperti request data
Cara install = `npm install redux-thunk`

## Menyimpan Data ke Storage 
Menggunakan redux persist untuk digunakan pada store. Cara install = `npm install redux-persist`

## Data Fetching
Cara-cara fetching data di react
1. Fetch API
2. Axios
3. React Query Library

**Pada fetch API, terdapat :**
- method : GET, POST, PUT, DELETE, HEAD
- URL : URL dari request
- body : body dari request
- headers : header dari objek
- dll


**Sedangkan response build dari server yang didapat adalah :**
- type - basic, cors
- url
- useFinalURL
- status - status code(200,204,etc)
- ok - bool (success status 200-299)
- statusText - status code
- headers - header dari objek


**Response method :**
- clone()
- error()
- redirect()
- arrayBuffer()
- blob()
- formData()
- json()
- text()
 

# (17) Testing
- [Apa Itu Testing ?](#apa-itu-testing)
- [React Testing Library](#react-testing-library)
- [Testing Custom Hooks](#testing-custom-hooks)

## Apa itu Testing ? 
Proses verifikasi bahwa test assertions dan code benar sepanjang masa aplikasi. Nilai returnnya adalah boolean dimana akan mengembalikan false ketika ada bug.

### Manfaat Testing : 
1. Akan mengetahui bagian lain yang broken ketika mengubah suatu bagian code ketika aplikasi mempunyai coverage yang baik.
2. Mengurangi bug

## React Testing Library
### Render dan Debug
fungsi `render` pada RTL akan merender file JSX setelah itu, kita baru memiliki akses ke komponen yang dibutuhkan. Sedangkan fungsi `debug` pada RTL berfungsi untuk mengetes apakah file JSX sudah terender.
syntax render : `render(fileJSX)` -> `render(<App />)`
syntax debug : `screen.debug()`

### Memilih elemen
getByText : Memilih teks dari elemen yang dipilih
getByLabelText : Memilih berdasarkan label
getPlaceholderText : Memilih berdasarkan placeholder
getByAltText : Memilih berdasarkan img, area, input, dan jenis custom elemen lain
getByRole : Memilih berdasarkan role, contoh : button, textbox, spinbutton
getByTestId : Memilih berdasarkan data-testid
getByTitle : Memilih berdasarkan judul atribut

### Handle Event
Menggunakan firebase dengan target dan value yang ditentukan. 
```jsx
render(<NameForm/>)
        const inputElement = screen.getByTestId("nama")
        fireEvent.change(inputElement, {target: {value: "nama"}})
        expect(inputElement.value).toBe("nama")
```

### Handle Asynchronous
Digunakan ketika mengetes fetch sebuah API. Perlu membaut mock untuk **axios**. Setelah itu, membuat mock promise untuk keadaan berhasil dan gagal yang akan dikembalikan ke skenario yang ada.

## Testing Custom Hooks
Menggunakan React Hooks Testing Library yang akan mengetes hooks tanpa merender satu komponen. Cara install : `npm install -D @testing-library/react-hooks`

# (18) Deployment
- [Build React App](#build-react-app)
- [Deployment](#deployment)
- [Layanan Deploy](#layanan-deploy)

## Build React App
Build ini berfungsi untuk mengubah versi aplikasi menjadi production. Hal-hal yang hanya diperlukan saat pengembangan akan dihapus sehingga performa aplikasi menjadi ringan dan cepat. Cara penggunaannya cukup mudah hanya dengan menjalankan `npm run build`

Untuk menjalankan aplikasi yang sudah dioptimalisasi secara lokal bisa menggunakan `serve` dengan menginstall `npm install -g serve` dan menjalankannya `serve -s build`

## Deployment
Deployment ini adalah hosting aplikasi ke server tertentu yang bertujuan untuk menyebarkan aplikasi yang sudah dibuat sehingga bisa diakses oleh orang lain.

## Layanan Deploy
### Surge
- Dapat untuk mendeploy website statis untuk Front-End
- Subdomainnya *surge.sh
- Dapat menerima file HTML, CSS, dan JS
Step : 
1. install dengan `npm install --global surge`
2. Deploy dengan `surge`
3. `surge teardown [nama].surge.sh`

### Netlify CLI
- Platform penyedia layanan build tools sekaligus Continous Deployment
- Dapat untuk mendeploy website statis
- Sudah terintegrasi dengan Git Host popular seperti Github, Gitlab dan Bitbucket

Step : 
1. Membuat akun di [Netlify](www.netlify.com)
1. Install dengan `npm install netlify-cli -g`
2. Deploy dengan `netlify deploy`
3. Verify akun melalui browser
4. Create & configure a new site
5. Pilih lokasi file yang akan di deploy. Pilih ./build

# (19) Introduction Algorithm
- [Algoritma](#algoritma)
- [Algoritma Dasar](#algoritma-dasar)
- [Contoh Implementasi](#contoh-penggunaan)

## Algoritma
Prosedur komputasi atau instruksi yang diberikan kepada mesin yang mengambil nilai input dan meghasilkan output.

### Mengapa programmer/software engineer harus memahami algoritma?
- Memiliki tanggung jawab membuat aplikasi
- Memberikan instruksi tertentu saat membuat coding dengan menyusun algoritma untuk menyelesaikan masalah tertentu

### Contoh Algoritma : 
- Mencari bilangan prima (the sieve of Eratosthenes)
- Sorting (Selection Sort, Bubble Sort, Insertion Sort, Heap Sort, Quick Sort, Merge Sort, Bucket Sort, Radix Sort, Count Sort)
- Searching (Linear Search, Binary Search)
- dll

### Karakteristik algoritma 
1. Memiliki batas (awal dan akhir). Misal untuk sum counter biasanya set nilai awalnya = 0. Contoh lain, pada looping biasanya diberikan statement batas akhir nilai (<100) atau memberikan perintah `break` ketika looping telah mencapai hasil.
2. Instruksi terdefinisi dengan baik, urutannya jelas
3. Efektif dan efisien, dapat menghasilkan output yang diharapkan dengan kompleksitas waktu seminimal mungkin. Misal untuk kasus shortest path tertentu digunakan algoritma greedy(Dijkstra’s shortest path) dibandingkan dynamic programming(Bellman Ford), dikarenakan greedy menemukan solusi terbaik dengan kompleksitas waktu yang relatif cepat dengan O(ELogV + VLogV) time. Sedangkan untuk DP memerlukan kompleksitas waktu O(VE) time

## Algoritma dasar : 
1. Sequential
2. Branching (if, else)
3. looping (while, for)

### Cara menuliskan algoritma
1. Pseudocode (kerangka code)
2. Flowchart (menggambarkan urutan antar proses)

### Simbol Flowchart
- Round Rectangle = Mulai/Selesai
- Rectangle = Proses
- Parallelogram = Input/Output
- Rhombus = Branching
- Hexagon = Looping

## Contoh Penggunaan
### Pseudocode
Check whether the enteren number is even or odd
```
begin
    numeric nNum
    display "ENTER A NUMBER : "
    accept nNum
    if(nNum%2==0)
    begin 
        display "EVEN"
    end
    else
    begin
        display "ODD"
    end
end
```
### Flowchart
Check whether the enteren number is even or odd


![image](https://user-images.githubusercontent.com/72771774/163657460-ce0039f3-ac01-440c-8c08-6f7392a9d01e.png)


# (20) GraphQL - Basic
- [GraphQL](#graphql)
- [Fitur GraphQL](#fitur-graphql)
- [Why GraphQL?](#mengapa-menggunakan-graph-ql)
- [Hasura dan Heroku](#hasura-dan-heroku)

## GraphQL 
Query language untuk API dimana kita mendefine schema dari data yang diinginkan yang dikirim antar network.

## Fitur GraphQL
1. Query = cara untuk mendapat data(get)
2. Mutation = manipulasi data (insert, update, delete)
3. Subscription = (mendapatkan data yg terupdate - realtime - menggunakan WebSockets)

## Mengapa Menggunakan Graph QL?
- Graph QL dapat menyaring untuk mengeksekusi field data yang diperlukan saja, sedangkan pada rest semua field data akan ikut dieksekusi
- Pada graph ql dapat menggunakan multiple collection (nested)
- Dapat menggunakan mendapatkan multiple data yang tidak berelasi
- Adanya Graphql fragment yaitu logika yang dapat digunakan untuk beberapa query dan mutasi. Digunakan untuk menyimpelkan query/mutasi - fungsinya seperti - variabel sehingga tidak perlu menuliskan hal yang sama berkali-kali.

## Hasura dan Heroku
- [Hasura](https://hasura.io/about/) adalah sebuah layanan yang menyediakan graphql dan rest API. Klik [di sini]((https://hasura.io/)) untuk menuju Hasura
- [Heroku](https://en.wikipedia.org/wiki/Heroku) adalah cloud platform sebagai layanan support untuk beberapa bahasa programming. Heroku juga menyediakan postgres database secara gratis. Klik [di sini](https://www.heroku.com) untuk menuju Heroku.


# (21) Relational Database
- [Introduction Database](#introduction-database)
- [Database Relationship](#database-relationship)
- [Jenis Perintah SQL](#jenis-perintah-sql)
    - [Data Definition Language(DDL)](#data-definition-languageddl)
    - [Data Manipulation Language(DML)](#data-manipulation-languagedml)
        - [DML Operation](#dml-operation)
        - [DML Statement](#dml-statement)
        - [Join](#join)
        - [Union](#union)
        - [Agregation](#agregation)
    - [Data Control Language(DCL)](#data-control-languagedcl)
## Introduction Database
Database merupakan umpulan informasi atau data yang terstruktur yang biasanya disimpan dalam sistem komputer. Database biasa dihandle oleh Database Management System(DBMS)

## Database Relationship

### One to One
Hubungan antara 2 tabel/entitas dimana : 
- Satu baris di tabel a hanya berhubungan dengan 1 baris di tabel b
- Satu baris di tabel b hanya berhubungan dengan 1 baris di tabel a 

Contoh : 1 negara mempunyai 1 ibukota, 1 ibukota dipunyai oleh 1 negara

### One to Many
Hubungan antara 2 tabel/entitas dimana :
- Satu baris di tabel a dapat berhubungan dengan 1 atau lebih baris di tabel b
- Satu baris di tabel b hanya berhubungan dengan 1 baris di tabel a 

Contoh : 1 mahasiswa hanya memiliki 1 dosen wali, 1 dosen wali bisa menjadi wali untuk 1 atau lebih mahasiswa

### Many to Many
Hubungan antara 2 tabel/entitas dimana : 
- Satu baris di tabel a dapat berhubungan dengan 1 atau lebih baris di tabel b
- Satu baris di tabel b dapat berhubungan dengan 1 atau lebih baris di tabel a

Contoh : seorang youtuber bisa mempunyai 1 atau lebih orang yang subscribe, seseorang bisa melakukan subscribe ke 1 atau lebih youtuber

## Jenis Perintah SQL

### Data Definition Language(DDL)
- Create
- Drop
- Rename
- Alter
- Truncate
- Comment

### Data Manipulation Language(DML)

#### DML Operation
- Insert
```sql
INSERT INTO table_name (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);
```
- Select
```sql
SELECT column1, column2, ...
FROM table_name;
```
- Update
```sql
UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
```
- Delete
```sql
DELETE FROM table_name WHERE condition;
```

#### DML Statement
- Like
```sql
SELECT column1, column2, ...
FROM table_name
WHERE columnN LIKE pattern;
```
- Between
```sql
SELECT column_name(s)
FROM table_name
WHERE column_name BETWEEN value1 AND value2;
```
- And
```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition1 AND condition2 AND condition3 ...;
```
- OR
```sql
SELECT column1, column2, ...
FROM table_name
WHERE condition1 OR condition2 OR condition3 ...;
```
- Not
```sql
SELECT column1, column2, ...
FROM table_name
WHERE NOT condition;
```
- In
```sql
SELECT column_name(s)
FROM table_name
WHERE column_name IN (value1, value2, ...);
```
- Order By
```sql
SELECT column1, column2, ...
FROM table_name
ORDER BY column1, column2, ... ASC|DESC;
```
- Limit
```sql
SELECT column_name(s)
FROM table_name
WHERE condition
LIMIT <how much?>
```

#### Join
- (INNER) JOIN: Return data record yang cocok dari tabel kiri dan kanan
- LEFT (OUTER) JOIN: Return semua data record dari tabel kiri, dan data record pasangan dari tabel kanan(bisa null)
- RIGHT (OUTER) JOIN: Return semua data record dari tabel kanan, dan data record pasangan dari tabel kiri(bisa null)
- FULL (OUTER) JOIN: Return semua data record yang cocok dari tabel kiri atau kanan
```sql
SELECT column_name(s)
FROM table1
<JOIN TYPE> table2
ON table1.column_name = table2.column_name;
```

#### Union
Operator union digunakan untuk mengombinasikan set hasil dari 2 atau lebih SELECT statement dengan syarat (identik):
- Setiap SELECT statement harus memiliki jumlah kolom yang sama
- Kolom harus sama tipe datanya
- Kolom harus sama urutannya
```sql
SELECT column_name(s) FROM table1
UNION
SELECT column_name(s) FROM table2;
```

#### Agregation
- MIN/MAX
- SUM
- AVG
- COUNT
```sql
SELECT <Agregation>(column_name)
FROM table_name
WHERE condition;
```

##### Group By and Having
```sql
SELECT column_name(s)
FROM table_name
WHERE condition
GROUP BY column_name(s)
HAVING condition
ORDER BY column_name(s);
```

### Data Control Language(DCL)
- Grant - This command gives users access privileges to the database
- Revoke - This command withdraws the user’s access privileges given by using the GRANT command

# (22) GraphQL - Query and Apollo Client
- [Import `gql` dan `useQuery` dari `@apollo/client`](#import-gql-dan-usequery-dari-apolloclient)
- [inisialisasi data, loading, dan server](#inisialisasi-data-loading-dan-server-dalam-sebuah-objek-dengan-memanggil-usequery)
- [Penggunaan Data](#penggunaan-data-pada-kode-jsx)
- [Lazy Query](#lazy-query)
- [Refetch](#refetch)
- [Inisialisasi multiple query](#)

## Import `gql` dan `useQuery` dari `@apollo/client`
gql sendiri berisikan query yang dapat dijalankan pada API
useQuery digunakan untuk menjalankan query
```
import { gql , useQuery} from '@apollo/client';
```

## inisialisasi data, loading, dan server dalam sebuah objek dengan memanggil `useQuery`
- data = objek yang berisi hasil dari hasil query graphQL
- error = Jika query mengalami error, maka akan berisikan array berisi error
- loading = jika true, maka query sedang berjalan dan belum tampil hasilnya
```
const {data, loading, error} = useQuery(getData);
```

## Penggunaan data pada kode jsx. 
### Note : request data sebelum query adalah null, sehingga perlu menggunakan optional chaining untuk menghindari error
```
datalist?.daftar_pengunjung.map(item => (
    <ListItem
    key={item.id}
    data={item}
    hapusPengunjung={props.hapusPengunjung}
    />
))
```

## Lazy query
useLazyQuery digunakan ketika query dijalankan hanya pada saat tertentu, misalnya query untuk searching, filtering, dan lainnya
karena query ini memerlukan variabel, hook ini memerlukan sebuah fungsi untuk memasukkan variabel dari input pengguna. Selain itu, untuk menyimpan input pengguna, juga diperlukan variabel/state baru.
```
const [getPengunjungbyId, {data : pengunjung, loading : loadingPengunjung, error : errorPengunjung}] = useLazyQuery(getPengunjung)
```

## Refetch
Refetch berfungsi untuk merefresh hasil query setiap action dari user. Pada refetch, user dapat membuat variabel baru. Jika tidak ada variabel baru, maka query akan menggunakan variabel yang sama dengan yang digunakan sebelumnya.
```
const [getPengunjungbyId, {data, loading, error, refetch}] = useLazyQuery(getPengunjung)
```

## Inisialisasi Multiple Query
Barikut adalah salah satu cara inisialisasi dari 2 query. Pemanggilan dilakukan dengan memanggil inisial di kanan titik dua.
```
const {data : datalist, loading : loadingData, error : errorData} = useQuery(getData);
const [getPengunjungbyId, {data : pengunjung, loading : loadingPengunjung, error : errorPengunjung}] = useLazyQuery(getPengunjung)
```

# (23) GraphQL - Mutation
- [Mutation?](#mutation)
- [Import `useMutation` dari `@apollo/client`](#import-usemutation-dari-apolloclient)
- [Inisialisasi Handler](#inisialisasi-handler)
- [Pemanggilan untuk Sinkronisasi Variabel Input Pengguna dan Mutation](#pemanggilan-untuk-sinkronisasi-variabel-input-pengguna-dan-mutation)

## Mutation?
Mutasi merupakan fungsi untuk insert, update, dan delete. Pada mutasi kita perlu mendefinisikan operasi apa yang ingin kita lakukan beserta return datanya. Contoh :
```
const addData = gql`
    mutation MyMutation($object: daftar_pengunjung_insert_input!) {
        insert_daftar_pengunjung_one(object: $object) {
            id
            nama
            umur
            jenisKelamin
        }
    }
`
```

## Import `useMutation` dari `@apollo/client`
```
import { gql, useQuery, useMutation } from '@apollo/client'
```

## Inisialisasi Handler 
Handler berupa array yang berisi function dan object loading dengan `useMutation` untuk menjalankan mutasi. `refetchQueries` akan me-return array yang menjalankan query setelah mutasi.
```
const [addPengunjung, {loading: loadingAdd}] = useMutation(addData, {refetchQueries: [getData]})
```

## Pemanggilan untuk Sinkronisasi Variabel Input Pengguna dan Mutation
```
const onTambahPengunjung = (newUser) => {
    addPengunjung({variables: {
        object: {
            nama: newUser.nama,
            umur: newUser.umur,
            jenisKelamin: newUser.jenisKelamin
        }
    }})
};
```

# (24) GraphQL - Subscription
- [Subscription](#subscrioption)
- [Langkah-Langkah](#langkah-langkah)
    - [Install Library](#install-library-yang-diperlukan)
    - [Inisialisasi GraphQLWsLink dan Split Communication](#inisialisasi-graphqlwslink-dan-split-communication)
    - [Import `useSubscription` dan Buat Subscription](#import-usesubscription-dari-apollo-client-dan-buat-subscription)
    - [Penggunaan Subscription](#penggunaan-subscription)
- [Tentang `subscribeToMore`](#tentang-subscribetomore)

## Subscrioption ?
Subscription merupakan proses di mana bisa mendapatkn data yang terbaru dari graphql, ketika ada mutation, client yang subscribe akan mendapat data terbaru

## Langkah-Langkah

### Install library yang diperlukan
`npm install graphql-ws`

### Inisialisasi GraphQLWsLink dan Split Communication
Penggunaan split communication adalah ketika tidak memerlukan subscription(query dan mutation), maka client menggunakan url di `httpLink` dan ketika menggunakan subscription menggunakan url di `wsLink`
```
import { ApolloClient, InMemoryCache } from "@apollo/client";
import { GraphQLWsLink } from '@apollo/client/link/subscriptions';
import { createClient } from 'graphql-ws';
import { split, HttpLink } from '@apollo/client';
import { getMainDefinition } from '@apollo/client/utilities';

const httpLink = new HttpLink({
    url: 'http://localhost:4000/subscriptions',
    authToken: user.authToken
});

const wsLink = new GraphQLWsLink(createClient({
    url: 'wss://localhost:4000/subscriptions',
    connectionParams: {
        authToken: user.authToken,
    },
}));

const splitLink = split(
    ({ query }) => {
        const definition = getMainDefinition(query);
        return (
        definition.kind === 'OperationDefinition' &&
        definition.operation === 'subscription'
        );
    },
    wsLink,
    httpLink,
);

const client = new ApolloClient({
    link: splitLink,
    cache: new InMemoryCache()
});

export default client
```

### Import `useSubscription` dari apollo client dan buat subscription
```
import { gql } from "@apollo/client";

export const SubscribeData = gql`
    subscription subscribeDataSubscription {
        daftar_pengunjung {
            id
            nama
            umur
            jenisKelamin
        }
    }
`
```

### Penggunaan Subscription
```
const {data: dataSub, loading: loadingSub, error: errorSub} = useSubscription(SubscribeData)
```
```
{dataSub?.daftar_pengunjung.map(item => (
    <ListItem
    key={item.id}
    data={item}
    hapusPengunjung={props.hapusPengunjung}
    />
))}
```

## Tentang `subscribeToMore`
```
const {data , loading : loadingData, error : errorData, subscribeToMore} = useQuery(GetData);

useEffect(() => {
    subscribeToMore({
        document: SubscribeData,
        updateQuery: (prev, {subscriptionData : {data}}) => {
            return data
        }
    })
}, []);
```

### Kapan Menggunakan `subscribeToMore`?
Sebelum menentukan, kita harus tau kembalian data graphql
- Jika mengembalikan array, kita bisa pake yg biasa
- Jika kembaliannya satu data yg berubah kita harus pakai `subscribeToMore` sehingga perlu update isi prev 
