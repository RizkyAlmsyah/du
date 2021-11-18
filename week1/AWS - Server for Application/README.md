# Server For Application

Karena saya windows langsung saja

1. masuk ke server dengan perintah `ssh -i bootcamp.pem ubuntu@3.128.7.173`
   <br>
   <img src=".image/1.PNG">
   <br>
2. lakukan update & upgrade server
   <br>
   <img src=".image/2.PNG">
   <br>
3. Kemudian buat user dan beri hak akses sudo
   <br>
   <img src=".image/3.PNG">
   <br>
4. Kemudian edit config ssh `etc/ssh/sshd_config` kemudian reload ssh
   <br>
   <img src=".image/4.PNG">
   <br>
5. untuk masuk ke frontend kita melewati reverse proxy
   <br>
   <img src=".image/5.PNG">
   <br>
6. Sama seperti direverse proxy kita update buat user dan konfigurasi ssh
   <br>
   <img src=".image/6.PNG">
   <br>
   <br>
   <img src=".image/4.PNG">
   <br>
7. Kita install nvm dan cek versinya
   <br>
   <img src=".image/7.PNG">
   <br>
8. Kemudian install node 10
   <br>
   <img src=".image/8.PNG">
   <br>
9.  Kemudian clone repository
    <br>
   <img src=".image/9.PNG">
   <br>
10. ubah nama `dumbflix-frontend` menjadi `frontend`
    <br>
   <img src=".image/10.PNG">
   <br>
11. lalu install dependecies yang diperlukan
    <br>
   <img src=".image/11.PNG">
   <br>
12. Kemudian kita install pm2
    <br>
   <img src=".image/12.PNG">
   <br>
13. Kemudian jalankan dengan perintah `pm2 start ecosystem.config.js`
    <br>
   <img src=".image/13.PNG">
   <br>