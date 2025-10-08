# Modul Praktikum Pemrograman Web

Nama : ANDREAN PUTRA ARYA

NIM : 312410341

KELAS : TI.24.4.3

# Langkah-langkah Praktikum
1. Persiapan membuat dokumen HTML dengan nama file lab3_list.html seperti berikut. Membuat Ordered List. 
Kemudian tambahkan kode untuk membuat Ordered List seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>
    <section id="order-list">
        <h2>Ordered List</h2>
        <ol>
            <li>Pemrograman Web</li>
            <li>Sistem Informasi</li>
            <li>Basis Data 2</li>
        </ol>
    </section>
</body>
</html>
```

Hasilnya : 

![gambar](https://github.com/andreanbadeh/Lab3Web/blob/a99bd2d7c0e05b556371c98bc0833851fe9697e8/images/Screenshot%20from%202025-10-08%2018-52-09.png)

2. Membuat Unorderd List
Kemudian tambakan kode untuk membuat Unordered List, setelah deklarasi ordered list pada section unordered-list, seperti berikut.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>
    <section id="order-list">
        <h2>Ordered List</h2>
        <ol>
            <li>Pemrograman Web</li>
            <li>Sistem Informasi</li>
            <li>Basis Data 2</li>
        </ol>
    </section>

    <section id="unorder-list">
        <h2>Unordered List</h2>
        <ul type="square">
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma &amp; Pemrograman</li>
        </ul>
    </section>
</body>
</html>
```
Lalu buktikan hasilnya :

![gambar](https://github.com/andreanbadeh/Lab3Web/blob/e72ac7e50c0592869dee2b59d7152a506de32133/images/Screenshot%20from%202025-10-08%2018-56-13.png)

3. Membuat Description List
Kemudian tambahkan kode untuk membuat description list setelah deklarasi unorderd-list.
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat List</h1>
    </header>

    <section id="order-list">
        <h2>Ordered List</h2>
        <ol>
            <li>Pemrograman Web</li>
            <li>Sistem Informasi</li>
            <li>Basis Data 2</li>
        </ol>
    </section>

    <section id="unorder-list">
        <h2>Unordered List</h2>
        <ul type="square">
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma &amp; Pemrograman</li>
        </ul>
    </section>

    <section id="unorder-list">
        <h2>Description List</h2>
        <dl>
            <dt>Fakultas Teknik</dt>
            <dd>Teknik Industri</dd>
            <dd>Teknik Informatika</dd>
            <dd>Teknik Lingkungan</dd>
            <dt>Fakultas Ekonomi dan Bisnis</dt>
            <dd>Akuntansi</dd>
            <dd>Manajemen</dd>
            <dd>Bisnis Digital</dd>
        </dl>
    </section>
</body>
</html>
```
Kemudian lihat hasilnya :

![gambar](https://github.com/andreanbadeh/Lab3Web/blob/4ad7c16e91b190f22b2725d2f9520d5aef010f2e/images/Screenshot%20from%202025-10-08%2018-59-26.png)

# MEMBUAT TABEL
4. Membuat Tabel
Buat file baru dengan nama lab3_tabel.html seperti berikut.
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Table</h1>
    </header>

    <table border="1" cellpadding="4" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td>Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
Llau lihat hasilnya :

![gambar](https://github.com/andreanbadeh/Lab3Web/blob/fbe072587b640e1dbdd45cf128caa1cb738e3756/images/Screenshot%20from%202025-10-08%2019-03-17.png)

5. Menggabungkan Sel Data
Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut rowspan untuk menggabungkan baris (secara vertikal) dan colspan untuk menggabungkan kolom (secara horizontal).
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Table</h1>
    </header>

    <table border="1" cellpadding="6" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td rowspan="3">Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
Kemudian lihat hasilnya :

![gambar](https://github.com/andreanbadeh/Lab3Web/blob/cf7b81ea8edb83524ba2e091905c813d4c449c43/images/Screenshot%20from%202025-10-08%2019-06-05.png)

# MEMBUAT FORM
6. Buat file baru dengan nama lab3_form.html seperti berikut.
Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut :
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Lanjutan</title>
</head>
<body>
    <header>
        <h1>Membuat Form</h1>
    </header>

    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Pelanggan</legend>

            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama">
            </p>

            <p>
                <label for="alamat">Alamat</label>
                <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
            </p>

            <p>
                <label>Jenis Kelamin</label>
                <input id="jk_l" type="radio" name="kelamin" value="L">
                <label for="jk_l">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="P">
                <label for="jk_p">Perempuan</label>
            </p>

            <p>
                <input type="submit" value="Login">
            </p>
        </fieldset>
    </form>
</body>
</html>
```
Lalu lihat hasilnya :

![gambar](https://github.com/andreanbadeh/Lab3Web/blob/3c1a9b7148d02b3c9c95b8b5dff9760716d2861a/images/Screenshot%20from%202025-10-08%2019-09-14.png)

7. Menambahkan Style pada Form
Agar tampilan form lebih menarik, bisa ditambahkan CSS seperti berikut.

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab3Web/15495b9cd4463061509713d55bfa78f791029493/2.2png.png)

Kemudian, lihat hasilnya :

![gambar](https://raw.githubusercontent.com/M-Rakha/Lab3Web/15495b9cd4463061509713d55bfa78f791029493/Cuplikan%20layar%202025-10-07%20111205.png)

