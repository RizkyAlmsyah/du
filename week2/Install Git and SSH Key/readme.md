# Install Git and SSH Key
1. Pertama-tama `sudo apt update -y && sudo apt upgrade -y`
2. Karena biasanya git sudah terinstall maka cara mengeceknya menggunakkan git --version
    <br>
   <img src=".image/2.PNG" >
   <br>
3. Membuat sebuah ssh, untuk dapat melakukan push ke dalam github tanpa melakukan login terlebih dahulu yaitu dengan mengetikan perintah `ssh-keygen`.
   <br>
   <img src=".image/3.PNG" >
   <br>
4. Setelah membuat sebuah ssh, kita harus melakukan pemindahan atau copy paste kunci pub ssh kedalam github
   <br>
   <img src=".image/4.PNG" >
   <br>
   <br>
   <img src=".image/4_1.PNG" >
   <br>
5. Kemudian kita dapat menggunakan ssh dengan mengetikkan perintah `ssh -T git@github.com`
   <br>
   <img src=".image/5.PNG" >
   <br>
6. lalu kita lakukan git clone dengan menggunakan link yang sudah di fork, dengan perintah
   <br>
   <img src=".image/6.PNG" >
   <br>
<br>

# GIT ADD, GIT COMMIT, GIT PUSH, GIT PULL

1. Disini saya akan memindahkan file ke github dengan nama test.txt
   <br>
   <img src=".image/7.PNG" >
   <br>
   <br>
   <img src=".image/7_1.PNG" >
   <br>
   <br>
   <img src=".image/7_2.PNG" height=300>
   <br>
2. Disini saya akan mengepull repository ketika ada perubahan pada github
   <br>
   <img src=".image/8.PNG" height=300>
   <br>
   <br>
   <img src=".image/8_1.PNG">
   <br>
   