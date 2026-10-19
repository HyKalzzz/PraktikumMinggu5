# Modul 5 - Bootstrap

## 1. Pengertian Bootstrap

Bootstrap adalah framework CSS yang digunakan untuk mempermudah pembuatan tampilan website agar lebih menarik dan responsif. Bootstrap menyediakan class siap pakai untuk membuat berbagai komponen seperti navbar, tombol, form, dan layout.

## 2. Cara Menggunakan Bootstrap

Bootstrap dapat digunakan melalui CDN, mengunduh file Bootstrap, atau menggunakan package manager seperti npm. Pada praktikum ini, Bootstrap digunakan melalui CDN dengan menambahkan link CSS di dalam bagian head dan JavaScript sebelum penutup body pada file HTML.

## 3. Grid System dan Breakpoints

Grid System adalah sistem tata letak Bootstrap yang membagi halaman menjadi 12 kolom agar elemen website dapat disusun secara fleksibel.

Breakpoints adalah batas ukuran layar yang digunakan untuk menyesuaikan tampilan website pada berbagai perangkat, seperti smartphone, tablet, dan komputer.

## 4. Lima Class Bootstrap

1. `container` digunakan untuk mengatur wadah konten.
2. `row` digunakan untuk membuat baris pada layout.
3. `btn btn-primary` digunakan untuk membuat tombol berwarna biru.
4. `text-center` digunakan untuk membuat teks rata tengah.
5. `form-control` digunakan untuk mengatur tampilan kolom input.

## 5. Membuat Gambar Responsif

Gambar dapat dibuat responsif dengan menggunakan class `img-fluid` pada elemen gambar HTML. Class ini membuat gambar menyesuaikan lebar wadahnya tanpa mengubah rasio gambar.

Contoh penggunaan:

`<img src="gambar.jpg" class="img-fluid" alt="Contoh gambar">`