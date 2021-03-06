## Anggota Kelompok
| Nama                                | NIM         |
| ------------------------------------|:-----------:|
| Muhammad Fauzan Azhim               | G64170009   |
| Fauzi Muhammad Sulaeman             | G64170095   |
| Haidar Muhammad Yasin               | G64170096   |
| Komang Elang Surya Prawira          | G64170098   |


# Clumsy Bird
<h1 align="center"><img src="https://github.com/Osisuseso/Clumsy-Bird-Komdat-2020/blob/master/Images/flappy%20bird%20icon.png" width="400"></h1>

[Sekilas Tentang](#sekilas-tentang) | [Instalasi](#instalasi) | [Pengaturan Tambahan](#pengaturan-tambahan) | [Cara Bermain](#cara-bermain) | [Pembahasan](#pembahasan) | [Referensi](#referensi)
:---:|:---:|:---:|:---:|:---:|:---:|

## Sekilas Tentang

**Clumsy Bird** merupakan sebuah *clone* dari permainan Flappy Bird yang cukup terkenal pada tahun 2013. Permainan ini mulai dibuat *clone*-nya pada tahun 2014 semenjak permainan Flappy Bird ditutup. *Clone* ini dibuat oleh kontributor [ellionsonleao](https://github.com/ellisonleao). Sampai saat ini, *clone* tersebut masih selalu diperbaharui sehingga siapapun yang ingin memainkannya bisa langsung *clone* dari github tersebut. 

## Instalasi
#### Kebutuhan Sistem :
1. Linux
2. Nodejs v8.10.0
3. Grunt v1.0.4
4. Grunt-cli v1.2.0

#### Proses Instalasi :
1. *Install* seluruh paket sistem yang dibutuhkan, seperti `Nodejs`, `Grunt`, dan `Grunt-cli`.
```
$ sudo apt update
$ sudo apt install nodejs
$ sudo apt install npm
$ sudo apt install node-grunt-cli
$ sudo apt instal grunt
```
2. *Clone* **Clumsy Bird** ke dalam direktori.
```
$ git clone https://github.com/ellisonleao/clumsy-bird
```
3. Pindahkan direktori ke dalam folder 'clumsy-bird'.
```
$ cd clumsy-bird
```
4. *Install* modul yang diperlukan dan masuk ke dalam 'grunt'.
```
$ sudo npm install grunt-contrib-uglify
$ sudo npm install grunt-contrib-connect
$ grunt connect
```
5. Setelah selesai, masuk ke alamat `http://localhost:8001/`.

## Pengaturan Tambahan
Jika ingin mengubah tampilan dari permainan **Clumsy Bird**, dapat dilakukan dengan cara :
1. *Download* gambar yang diinginkan, misal kita akan mendownload gambar untuk dijadkan background yang baru.

![](https://github.com/Osisuseso/Clumsy-Bird-Komdat-2020/blob/master/Images/New%20BG.png)

2. Masukkan gambar ke dalam file `clumsy-bird/data/img`.

![](https://github.com/Osisuseso/Clumsy-Bird-Komdat-2020/blob/master/Images/New%20BG%202.png)

3. Ubah nama gambar tersebut menjadi `bg.png`.

![](https://github.com/Osisuseso/Clumsy-Bird-Komdat-2020/blob/master/Images/New%20BG%203.png)

4. Jalankan `grunt connect` pada *command line*.
```
$ grunt connect
```
5. Setelah selesai, masuk ke alamat `http://localhost:8001/`.

![](https://github.com/Osisuseso/Clumsy-Bird-Komdat-2020/blob/master/Images/New%20Game%20Play%201.png)

![](https://github.com/Osisuseso/Clumsy-Bird-Komdat-2020/blob/master/Images/New%20Game%20Play%202.png)

6. Jika ingin mengkonfigurasi gambar lainnya, ulangi langkah yang sama dengan tidak mengubah nama dan ukuran gambar asli.

## Cara Bermain
Cara memainkan **Clumsy Bird** cukup dengan menekan tombol `Space` atau `left-click` untuk lompat dan tombol `M` untuk mematikan suara.

![](https://github.com/Osisuseso/Clumsy-Bird-Komdat-2020/blob/master/Images/Gameplay%201.png)

![](https://github.com/Osisuseso/Clumsy-Bird-Komdat-2020/blob/master/Images/Gameplay%202.png)

![](https://github.com/Osisuseso/Clumsy-Bird-Komdat-2020/blob/master/Images/Gameplay%203.png)

## Pembahasan
**Clumsy Bird** ditulis dalam bahasa pemrograman `JavaScript`. **Clumsy Bird** memiliki  beberapa kelebihan, diantaranya :
       * Permainan ini cenderung mudah untuk dimainkan karena hanya cukup menekan tombol `Space` atau `left-click`.
       * Permainan ini relatif ringan untuk dijalankan sehingga tidak membutuhkan spesifikasi *hardware* yang tinggi.
       * Permainan ini bisa dimodifikasi tampilannya sehingga tidak akan cepat bosan untuk dimainkan.

**Clumsy Bird** juga masih memiliki kekurangan, salah satu nya adalah permainan ini hanya berjalan di server lokal.  

Jika dibandingkan dengan aplikasi sejenis, yaitu Flappy Bird. **Clumsy Bird** yang hadir sebagai pengganti permainan terdahulunya, mampu membawa suasana permainan yang sama dengan tampilan dan gameplay yang sama dengan Flappy Bird. Tetapi, **Clumsy Bird** masih memiliki beberapa kekurangan, diantaranya **Clumsy Bird** memiliki pegerakan yang cenderung kaku, jika dibandingkan permainan Flappy Bird.  

## Referensi
1. [Clumsy Bird](https://github.com/ellisonleao/clumsy-bird) - Ellisonleao Github
2. [Getting Started](https://gruntjs.com/getting-started) - Grunt: The JavaScript Task Runner
3. [How to Install Node.js and NPM on Ubuntu 18.04](https://www.hostinger.com/tutorials/how-to-install-node-ubuntu) - Hostinger Tutorial

[`^ kembali ke atas ^`](#)
