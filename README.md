### Nama    : Revano Arya Saputra
### NIM     : 312010461
### Kelas   : TI.20.A.1
### Matkul  : Pemograman Web

## 1. Membuat Struktur Dasar Dokumen HTML <b>

Penjelasannya sebagai berikut

Dibawah adalah contoh dari struktur Dasar Html menggunakan Framework Bootstrap Untuk menggunakan Framework bootstrap agar terhubung dengan Dokumen Html memerlukan Link yang sudah disediakan bootstrap dengan link CDN atau melalui Online link Seperti contoh salinan code dibawah

## Berikut Contoh Codingan html dan link boostrap <b>
```html
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    
    <title>Web Framework</title>
  </head>
  <body>
    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    
    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    -->
  </body>
</html>
```

## 2. Membuat Container <b>

Penjelasannya sebagai berikut

Ini adalah cara Membuat Container dengan class container container ini adalah container biasa di akan secara default hanya selebar url di atas layar atau tidak ukuran full width sementara untuk class container-fluid dia full width 100% itu perbedaan jenis container dibootstrap sudah terdesain otomatis hanya tinggal bagaiman kita membutuhkan nya,namun disini saya menggunakan container jenis biasa yang tidak full width.

## Berikut Contoh Codingan nya
```html
<!-- Container -->
    <div class="container">

    </div>
```
## 3. Membuat Card <b>

## Berikut Contoh Codingan nya
```html
<!-- Container -->
    <div class="container shadow-lg">
        <div class="card-body">
            <h1 class="text-muted py-3">Layout Sederhana</h1>
        </div>
    </div>
```

Penjelasannya sebagai berikut

Berikut hasil atau tampilan dari Header saya yang buat dan juga menambahkan Box-Shadow-lg atau large dan juga padding atas bawah atau dalam bootstrap yaitu py dan juga beberapa class untuk membuat nya dan simpan code dalam body untuk hasil outputnya bisa disimak dibawah ini.
![ss1](https://user-images.githubusercontent.com/101621068/163946082-26700759-d4b0-4c2a-b483-97b489b213e9.png)

## Membuat Navigasi <b>

Penjelasannya sebagai berikut

Membuat Navigasi dengan class "navbar" bootstrap telah menyediakan semuanya hanya pada kita nya saja yang mendesain sesuai dengan kebutuhan,seperti di atas memakai navigasi dengan class navbar dan beberapa class lainnya untuk mendukung navigasi nya seperti contoh nav class active di dalam element html di bootstrap dapat menggunakan banyak class dalam mendesain yang tersedia di bootstrap.

## Berikut Contoh Codingan nya
```html
<nav class="navbar" style="background-color: #1f5faa;">
            <ul class="nav nav-pills">
                <li class="nav-item">
                    <a class="nav-link active text-light" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="#">Article</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="#">About</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link text-light" href="#">Contact</a>
                </li>
            </ul>
</nav>
```

Dan ini hasil outputnya
![ss2](https://user-images.githubusercontent.com/101621068/163946361-d11a4efe-7bff-4884-a043-8870619d39a1.png)

## 5. Membuat card section description <b>

Penjelasannya sebagai berikut

Selanjutnya yaitu membuat card body dengan isi section description atau isi konten deskripsi saya menggunakan div dengan class card kemudian saya tambahkan inline css untuk sedikit mengatur sesuai layout nya dan juga menggunakan beberapa class di bootstrap nya seperti contoh gambar di atas.

## Berikut Contoh Codingan nya
```html
<div class="card" style="width: 80,1rem; padding: 50px 20px; background-color: #e4e4e5; border-radius: 0;">
            <div class="card-body">
                <h1 class="card-title pb-4" style="font-weight: bold;">Hello World!</h1>
                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem saepe
                    necessitatibus aspernatur nisi autem delectus excepturi nostrum natus similique beatae
                    reiciendis, quos placeat sapiente qui sint voluptatibus, a temporibus quasi.</p>
                <a href="#" class="btn btn-primary">Learn More »</a>
            </div>
</div>
```

Dan ini hasil outputnya
![ss3](https://user-images.githubusercontent.com/101621068/163946661-f38f6b2a-100c-4e35-a013-139e53e0b04e.png)

## 6. MEMBUAT (CARD 1,CARD 2, CARD 3) DAN WIDGET DENGAN GRID ROW DAN COL <B>

Penjelasannya sebagai berikut

Menambahkan CARD 1 dengan menggunakan grid row dan col dan juga menggunakan beberapa *class dalam bootstrap.

## Berikut Contoh Codingan hmtl card 1
```html
<!-- Row Content 1 -->
        <div class="row">
            <!-- card 1 -->
            <div class="col-3">
                <div class="col mt-4">
                    <div class="card" style="width: 18rem; border: 0;">
                        <img src="https://dummyimage.com/120/db7d25/fff.png" class="card-img-top rounded-circle"
                            alt="Indira" style="width: 200px;">
                        <div class="card-body">
                            <h5 class="card-title">Heading</h5>
                            <p class="card-text">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Voluptates,
                                facere.</p>
                            <a href="#" class="btn btn-primary">View detail</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
```
### CARD 1 <b>

Dan ini hasil outputnya
![ss4](https://user-images.githubusercontent.com/101621068/163947007-6aece3aa-4ea4-409e-9f65-cc331fd37b0b.png)

Penjelasannya sebagai berikut

Sama seperti di atas ini juga masih dalan row dan cuma col yang sama serta class yang sama.

### CARD 2 <b>

## Berikut Contoh Codingan hmtl card 2
```html
<!-- card 2 -->
            <div class="col-3">
                <div class="col mt-4">
                    <div class="card" style="width: 18rem; border: 0;">
                        <img src="https://dummyimage.com/120/3e73e6/fff.png" class="card-img-top rounded-circle"
                            alt="Indira" style="width: 200px;">
                        <div class="card-body">
                            <h5 class="card-title">Heading</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Distinctio,
                                magnam?</p>
                            <a href="#" class="btn btn-primary">View detail</a>
                        </div>
                    </div>
                </div>
            </div>
```

Dan berikut hasil dari outputnya
![ss5](https://user-images.githubusercontent.com/101621068/163947325-d124876f-8336-45b3-a594-bad7b6a8fd15.png)

### CARD 3 <b>

Penjelasannya sebagai berikut

Card 3 juga sama seperti card lain nya masih dalam row dan col yang class yang sama seperti contoh gambar di atas.

## Berikut Contoh Codingan hmtl card 3
```html
<!-- card 3 -->
            <div class="col-3">
                <div class="col mt-4">
                    <div class="card" style="width: 18rem; border: 0;">
                        <img src="https://dummyimage.com/120/71e6d4/fff.png" class="card-img-top rounded-circle"
                            alt="Indira" style="width: 200px;">
                        <div class="card-body">
                            <h5 class="card-title">Heading</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Nam, neque.
                            </p>
                            <a href="#" class="btn btn-primary">View detail</a>
                        </div>
                    </div>
                </div>
            </div>
```

Berikut hasil outputnya
![ss6](https://user-images.githubusercontent.com/101621068/163947698-2581f6ea-6c48-4be5-b236-75929ef14b9c.png)

### Widger Header <b>

Penjelasannya sebagai berikut

Menambahkan Widget class list group pada bootstrap karena bootstrap sudah menyediakan nya tinggal masukan beberapa class pada elemen html untuk mendesainnya disini masih menggunakan col-3 begitu juga *widget berikut nya masih dibungkus dengan col-3 seperti contoh gambar di atas dan contoh code dibawah.

## Berikut Contoh Codingan Widger Header <b>
```html
<!-- Widget Header -->
            <div class="col-3">
                <div class="list-group my-4" style="border-radius: 0;">
                    <a href="#" class="list-group-item list-group-item-action active" aria-current="true"
                        style="font-weight: bold;">
                        Widget Header
                    </a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                    <a href="#" class="list-group-item list-group-item-action">Widget Link</a>
                </div>
```

Dan berikut hasil outputnya
![ss7](https://user-images.githubusercontent.com/101621068/163948048-be8f5c5d-d9d9-4939-b645-db77d427cebd.png)

### Widget TEXT <b>

Penjelasannya sebagai berikut

Langkah berikutnya yaitu membuat widget text pada colom yang sama dengan widget header dan menggunakan beberapa class dibootstrap dalam membuat nya secara otomatis seperti contoh gambar di atas dan code dibawah.

## Berikut Contoh Codingan Widged TEXT <b>
```html
<!-- Widget Text -->
                <div class="list-group my-4" style="border-radius: 0; border: 1px #eee;">
                    <a href="#" class="list-group-item list-group-item-action active " aria-current="true"
                        style="font-weight: bold;">
                        Widget Text
                    </a>
                    <a href="#" class="list-group-item list-group-item-action">
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Laboriosam quas natus, amet ab
                            voluptatibus beatae accusamus, quam hic veritatis ipsa, accusantium est nihil dolores minus
                            at labore sapiente autem vero.</p>
                    </a>
                </div>
            </div>
```

Dan berikut hasil outputnya
![ss8](https://user-images.githubusercontent.com/101621068/163948272-89da6904-1d68-4b4a-9833-001d492d891d.png)

### MEMBUAT ROW CONTENT 2 (SECTION 1) <b>

Penjelasannya sebagai berikut

Lalu membuat row baru dan juga col baru dengan menambahkan class dan juga inline css untuk sedikit memperindah seperti gambar di atas dan code dibawah.

## Berikut Contoh Codingan html content 2 section 1 <b>
```html
<!-- Row Content 2 -->
        <div class="row">
            <!-- Section 1 -->
            <div class="col-8-md">
                <div class="card mb-3" style="width: 900px; height: 200px;  border: 0;">
                    <div class="row g-0">
                        <div class="col-md-4">
                            <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded-start"
                                alt="...">
                        </div>
                        <div class="col-md-8">
                            <div class="card-body">
                                <h2 class="card-title" style="font-weight: bold;">First featurette heading</h2>
                                <p class="card-text" style="text-align: left;">This is a wider card with supporting text
                                    below as a
                                    natural lead-in to additional
                                    content. This content is a little bit longer. Lorem, ipsum dolor sit amet
                                    consectetur adipisicing
                                    elit. Velit animi quidem facere neque. Ea rem labore dolorum, necessitatibus quod,
                                    maiores tempore
                                    harum fugit qui accusantium iure. Dolorum illo repellat vitae?</p>
                                <p class="card-text"><small class="text-muted"></small></p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
```

Dan berikut hasil outputnya
![ss9](https://user-images.githubusercontent.com/101621068/163948770-ede7e7dc-46a6-4b4f-a0db-7f90cceb6fe1.png)

### MEMBUAT ROW CONTENT 3 (SECTION 2) <b>

Penjelasannya sebagai berikut

Kemudian menambahkan section 2 dengan dibungkus row dan col seperti hasil di atas dan code html nya dibawah.

## Berikut Contoh Codingan html content 3 section 2 <b>
```html
<!-- Row Content 3 -->
        <div class="row">
            <!-- Section 2 -->
            <div class="col-8-lg me-5">
                <div class="card mb-3" style="width: 900px; height: 200px; border: 0;">
                    <div class="row g-0">
                        <div class="col-md-8">
                            <div class="card-body">
                                <h2 class="card-title" style="font-weight: bold;">First featurette heading</h2>
                                <p class="card-text">This is a wider card with supporting text below as a natural
                                    lead-in to additional
                                    content. This content is a little bit longer. Lorem ipsum dolor sit amet consectetur
                                    adipisicing elit.
                                    Animi rerum at facilis nesciunt. Quidem, ullam quod beatae sapiente excepturi, vitae
                                    praesentium ipsa
                                    ab optio, doloribus voluptatem vel atque eveniet necessitatibus?</p>
                                <p class="card-text"><small class="text-muted"></small></p>
                            </div>
                        </div>
                        <div class="col-md-4">
                            <img src="https://dummyimage.com/150/7b8a70/fff.png" class="img-fluid rounded-start"
                                alt="picture">
                        </div>
                    </div>
                </div>
            </div>
        </div>
```

Dan berikut hasil outputnya
![ss10](https://user-images.githubusercontent.com/101621068/163949177-8076808d-1711-44d8-995b-531946ce3472.png)


### MEMBUAT CARD FOOTER <b>

Penjelasannya sebagai berikut

Terakhir yaitu membuat card-footer dengan class card yang terdapat dibootstrap seperti gambar di atas dan code di bawah.

## Berikut Contoh Codingan Card Footer <b>
```html
<div class="card-footer text-center" style=" background-color: #1d1d1d; color: #eee;">
    <p>© 2022 - Universitas Pelita Bangsa</p>
</div>
```

Dan berikut hasil outputnya
![ss11](https://user-images.githubusercontent.com/101621068/163951007-7a7f561a-b627-4968-854b-373751b684f6.png)

### Full layout <b>

Berikut adalah contoh dari Full Layout
![ss12](https://user-images.githubusercontent.com/101621068/163951222-5223adc3-d81c-4687-bfaf-00f505457c82.png)

## Terimakasih 
