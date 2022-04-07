TUGAS PERTEMUAN 5

PEMROGRAMAN WEB

TEKNIK INFORMATIKA

UNIVERSITAS PELITA BANGSA

NAMA : Nurokhim

NIM : 312010064

KELAS : TI.20.D1

DOSEN : Agung Nugroho,S.Kom.,M.Kom
Instruksi Praktikum

Persiapkan text editor misalnya VSCode.

1.Buat folder baru dengan nama Lab4Web
2.Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.
3.Lakukan validasi dokumen html dengan mengakses http://validator.w3.org
4.Langkah-langkah Praktikum

Persiapan membuat dokumen HTML dengan nama file lab4_box.html seperti berikut.
![q1](https://user-images.githubusercontent.com/101801920/162131870-7a3a3382-1ea3-4660-914b-b5c3009e03dd.PNG)

Membuat Box Element
Kemudian tambahkan kode untuk membuat box element dengan tag div seperti berikut.

<section>
 <div class="div1">Div 1</div>
 <div class="div2">Div 2</div>
 <div class="div3">Div 3</div> 
</section>

CSS Float Property

Selanjutnya tambahkan deklarasi CSS pada head untuk membuat float element, seperti berikut.

<style>
 div {
 float:left;
 padding: 10px; 
 }
 .div1 {
 background: red;
 }
 .div2 {
 background: yellow;
 }
 .div3 {
 background: green;
 }
</style>

Tampilan pada browser
![q2](https://user-images.githubusercontent.com/101801920/162132573-d146dc47-01d6-4f3a-acc0-4e45130c5687.PNG)
Gambar 01.Box Element Float

Box Element Float

Clearfix digunakan untuk mengatur element setelah float element. Property clear digunakan untuk mengaturnya.

Tambahkan element div lainnya seteleah div3 seperti berikut.

<section>
 <div class="div1">Div 1</div>
 <div class="div2">Div 2</div>
 <div class="div3">Div 3</div> 
 <div class="div4">Div 4</div> 
</section>

Kemudian atur property clear pada CSS, seperti berikut.

.div4 {
 background-color: blue;
 clear: left;
 float: none;
}

![q3](https://user-images.githubusercontent.com/101801920/162134202-9add5168-d4e1-42ec-a5fd-7870551fefb4.PNG)

Tampilan pada Browser
![q4](https://user-images.githubusercontent.com/101801920/162134151-a03067c0-ed63-48e3-9be8-3a051db1c29c.PNG)

Membuat Layout Sederhana

Buat folder baru dengan nama lab4_layout, kemudian buatlah file baru didalamnya dengan nama home.html, dan file css dengan nama style.css.

![q5](https://user-images.githubusercontent.com/101801920/162135158-63ef72cb-b796-459e-8004-3c3dfb2a0910.PNG)

Tampilan pada Browser

![q6](https://user-images.githubusercontent.com/101801920/162135144-32f2e036-55d0-48b2-887a-a415e019d489.PNG)

Kemudian tambahkan kode CSS untuk membuat layoutnya.

![q7](https://user-images.githubusercontent.com/101801920/162135486-f65f73d0-3b76-4403-8221-2fcb7f84337c.PNG)

Tampilan Pada Browser

![q8](https://user-images.githubusercontent.com/101801920/162135474-d24969f0-0e05-4d02-8b35-d193e210bd13.PNG)

Membuat Navigasi

Kemudian selanjutnya mengatur navigasi.

![q9](https://user-images.githubusercontent.com/101801920/162135940-651094cf-7158-4fd2-a6ce-81581b77b1d7.PNG)

Tampilan Pada Browser

![q10](https://user-images.githubusercontent.com/101801920/162135929-d57037c9-0975-4526-8f96-5f48c19229d7.PNG)

Membuat Hero Panel
Selanjutnya membuat hero panel. Tambahkan kode HTML dan CSS seperti berikut.

![q11a](https://user-images.githubusercontent.com/101801920/162136315-bec18f6d-5c3c-4dd5-a814-025626d2a697.PNG)

![q11b](https://user-images.githubusercontent.com/101801920/162136303-c8976375-c851-48b7-9776-62a1da733f23.PNG)

Tampilan Pada Browser

![q12](https://user-images.githubusercontent.com/101801920/162136297-d90ba785-fead-4303-b093-9d18bc53ae2c.PNG)

Mengatur Layout Main dan Sidebar
Selanjutnya mengatur main content dan sidebar, 

![q13a](https://user-images.githubusercontent.com/101801920/162137051-3aa323e7-4522-46dc-b4c6-08d8f038fb0a.PNG)

tambahkan CSS float.

![q13b](https://user-images.githubusercontent.com/101801920/162137363-edacdf53-0001-4e09-83a8-e3e8ba8ef5ac.PNG)

Tampilan Pada Browser

![q13c](https://user-images.githubusercontent.com/101801920/162137529-b12e2d67-63ad-44b5-9940-e0e6bc584182.PNG)

Mengatur Footer
Selanjutnya mengatur tampilan footer. Tambahkan CSS untuk footer.

![q14](https://user-images.githubusercontent.com/101801920/162137826-89cba3f4-72cf-4ea5-b414-f014eefb60c9.PNG)

Tampilan Pada Browser

![q15](https://user-images.githubusercontent.com/101801920/162137929-52049424-ef77-4cce-ad9c-546a08ff4bb5.PNG)

Menambahkan Elemen lainnya pada Main Content

![q16a](https://user-images.githubusercontent.com/101801920/162138133-e63cccf7-1c3c-4684-bc9d-1a34987fa154.PNG)

Kemudian tambahkan CSS.

![q16b](https://user-images.githubusercontent.com/101801920/162138238-52317089-34ec-49b2-b9bc-627a3b1ee71f.PNG)

Tampilan Pada Browser

![q16c](https://user-images.githubusercontent.com/101801920/162138366-7970c7c2-c7e8-4c20-95fd-c37e40775a17.PNG)

Menambahkan Content Artikel
Selanjutnya membuat content artikel. Tambahkan HTML berikut pada main content.

![q17a](https://user-images.githubusercontent.com/101801920/162138653-90b7c6ff-7e54-492a-89e6-44b0d53e1353.PNG)

Kemudian tambahkan CSS.

![q17b](https://user-images.githubusercontent.com/101801920/162138770-968cc393-3667-4d11-9090-bf42fd79e193.PNG)

Tampilan Pada Browser

![q17c](https://user-images.githubusercontent.com/101801920/162138848-3fd7b5cc-6950-4ce1-bed5-7d17135fb57a.PNG)

Pertanyaan dan Tugas :
1.Tambahkan Layout untuk menu About
=> buat single layout yang berisi deskripsi, portfolio, dll
Jawab: Membuat dokumen HTML dengan nama file about.html :

![Capture](https://user-images.githubusercontent.com/101801920/162139278-96768d8b-858f-4cd9-a3c6-a4e99b59b671.PNG)

Kemudian tambahkan CSS.

![layout about](https://user-images.githubusercontent.com/101801920/162141461-d4c834af-c263-4d76-9144-92f9ee19fed4.PNG)


Tampilan Pada Browser

![q18](https://user-images.githubusercontent.com/101801920/162139482-8e1c54ae-ba20-419c-b2aa-6c95ede5d94b.png)

2.Tambahkan layout untuk menu Contact
=> yang berisi form isian: nama, email, message, dll.
Jawab:

Membuat dokumen HTML dengan nama file kontak.html :

![kontak](https://user-images.githubusercontent.com/101801920/162142374-93f8dd86-3648-4063-9ebf-8c6c91a62d64.PNG)
![q18a](https://user-images.githubusercontent.com/101801920/162142538-69cee047-0329-40b3-918f-4aa0dd8bf552.PNG)

Kemudian tambahkan CSS.

![q18b](https://user-images.githubusercontent.com/101801920/162142650-04bfc3aa-2ab5-483d-a332-c1ffa3acecbd.PNG)

Tampilan Pada Browser

![q18c](https://user-images.githubusercontent.com/101801920/162142751-b38f798c-496a-4829-9ed6-f1fe3e75c40b.PNG)













