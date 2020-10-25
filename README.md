
**nama :owenhutajulu** <br>
**nim  :312010155** <br>
**kelas:TI.20.A1** <br>

# Langkah-langkah penggunaan git
* Download Git terlebih dahulu, dengan link berikut ini :[click here](https://git-scm.com/)
![git](ttr/git.png)

* Setelah file terdownload, silahkan lakukan instalasi dengan referensi berikut ini :

![installing](ttr/installing.png)

`git --version` <br>

![version](ttr/version.png)

* Jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisa digunakan. Langkah pertama kita harus mengkonfigurasi user nama dan email di Git, dengan mengetikkan syntax berikut : <br>

`git config --global user.name "masukan nama anda"` <br>
`git config --global user.email "masukan email anda"` <br>

![membuat user](ttr/user.png)

* Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut : <br>

`git config --global user.name` <br>
`git config --global user.email` <br>


![setelah membuat user](ttr/name.png)


* Buat akun di GitHub,seperti contoh dibawah ini.Dan lakukan Verifikasi akun melalui email yang sudah terdaftar.


* Jika akun GitHub sudah selesai dibuat dan di verifikasi,proses selanjutnya silahkan buat Repository seperti gambar dibawah ini: Penjelasan

> * `Repository Name : (Silahkan isi nama repository yang diinginkan, seperti contoh saya ingin membuat repository LatihanVCS)`
> * `Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)`
> * `Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)`
> * `Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda`
> * `Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.`
> * `Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan`

![membuat nama repositori](ttr/latihan.png)


* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :

![hasil pembuatan repositori](ttr/hasilbuat.png)

* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk me-remote repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link URL git kita di Github, dengan cara tekan tombol Code lalu klik Copy. <br>


![code](ttr/kode.png) <br>

* Setelah Link URL git kita tercopy, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan mendownload Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih Git Bash Here.

![gitbash](ttr/GitBash.png)


* Pop Up Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut :


`git clone [URL] pada contohnya, saya akan memasukan git clone` <br>

https://github.com/owenmanis123/latihan-vcs1.git

























