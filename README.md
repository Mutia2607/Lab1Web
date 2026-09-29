# Jawaban Pertanyaan Dasar HTML

### 1. Apa fungsi deklarasi `<!DOCTYPE html>` pada dokumen HTML?

`<!DOCTYPE html>` berfungsi untuk memberi tahu browser bahwa dokumen yang dibuat menggunakan **HTML5**. Deklarasi ini membantu browser menampilkan halaman sesuai standar HTML yang berlaku.

### 2. Apa perbedaan antara tag, elemen, dan atribut pada HTML?

* **Tag** adalah penanda yang digunakan untuk membuat struktur HTML, contohnya `<p>` dan `</p>`.
* **Elemen** adalah keseluruhan bagian HTML yang terdiri dari tag pembuka, isi, dan tag penutup. Contohnya `<p>Hello World</p>`.
* **Atribut** adalah informasi tambahan yang diberikan pada sebuah tag untuk mengatur atau menjelaskan elemen. Contohnya `href` pada `<a href="https://google.com">Google</a>`.

### 3. Apa perbedaan `<p>` dengan `<br>`? Jelaskan penggunaannya.

`<p>` digunakan untuk membuat **paragraf**, sedangkan `<br>` digunakan untuk membuat **pindah baris** tanpa membuat paragraf baru.

Contoh:

```html
<p>Ini adalah paragraf pertama.</p>
<p>Ini adalah paragraf kedua.</p>
```

Sedangkan:

```html
Nama: Mutia<br>
Kelas: Teknik Informatika
```

### 4. Apa fungsi atribut `href` pada tag `<a>`?

Atribut `href` berfungsi untuk menentukan **alamat atau tujuan yang akan dibuka** ketika pengguna mengklik hyperlink.

Contoh:

```html
<a href="https://www.google.com">Google</a>
```

### 5. Apa perbedaan hyperlink ke halaman internal dengan hyperlink ke website eksternal?

* **Hyperlink internal** mengarah ke halaman atau file yang masih berada dalam website/proyek yang sama. Contohnya:

```html
<a href="about.html">About</a>
```

* **Hyperlink eksternal** mengarah ke website lain di luar proyek. Contohnya:

```html
<a href="https://www.google.com">Google</a>
```

### 6. Apa fungsi atribut `src` dan `alt` pada tag `<img>`?

* `src` berfungsi untuk menentukan **lokasi atau path gambar** yang akan ditampilkan.
* `alt` berfungsi memberikan **teks alternatif** apabila gambar tidak dapat ditampilkan serta membantu aksesibilitas.

Contoh:

```html
<img src="foto.jpg" alt="Foto Profil">
```

### 7. Apa perbedaan penggunaan `<ul>` dan `<ol>`?

`<ul>` digunakan untuk membuat **daftar yang tidak berurutan**, biasanya menggunakan tanda bullet.

Contoh:

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
</ul>
```

Sedangkan `<ol>` digunakan untuk membuat **daftar yang berurutan**, biasanya menggunakan angka.

Contoh:

```html
<ol>
    <li>HTML</li>
    <li>CSS</li>
</ol>
```

### 8. Apa yang terjadi jika path gambar pada atribut `src` salah?

Jika path pada `src` salah, browser **tidak dapat menemukan atau menampilkan gambar**. Biasanya akan muncul ikon gambar rusak dan teks dari atribut `alt` dapat ditampilkan sebagai pengganti.

Contoh:

```html
<img src="foto-salah.jpg" alt="Foto Profil">
```

Jika file `foto-salah.jpg` tidak ada di lokasi tersebut, gambar tidak akan tampil.

### 9. Mengapa struktur heading `h1` sampai `h6` perlu digunakan secara terstruktur?

Heading digunakan untuk menunjukkan **tingkatan dan struktur informasi** pada halaman HTML.

* `<h1>` digunakan untuk judul utama.
* `<h2>` digunakan untuk subjudul.
* `<h3>` digunakan untuk bagian di bawah `<h2>`.
* Dan seterusnya sampai `<h6>`.

Penggunaan heading yang terstruktur membuat halaman lebih mudah dibaca oleh pengguna dan membantu mesin pencari serta teknologi pembaca layar memahami struktur halaman.

### 10. Apa fungsi komentar `<!-- ... -->` dalam kode HTML?

Komentar digunakan untuk memberikan **catatan atau keterangan pada kode** yang tidak akan ditampilkan pada halaman website.

Contoh:

```html
<!-- Ini adalah komentar -->
<p>Selamat datang di website saya.</p>
```

Komentar dapat digunakan untuk menjelaskan bagian kode atau memberikan catatan kepada orang yang sedang mengembangkan website.


## Hasil Coding

Berikut adalah screenshot hasil coding HTML yang telah dibuat.

![Hasil Coding HTML](hasil-coding.png)
