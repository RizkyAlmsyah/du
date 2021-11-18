# APPLICATION AND DEPLOY

1. Pertama update dan upgrade dulu ubuntu server
        
        sudo apt update -y && sudo upgrade -y

    <br>
   <img src=".image/1.PNG">
   <br>
2. Kemudian lakukan install nodejs dan npm dengan perintah berikut :
   
   <br>
   <img src=".image/2.PNG">
   <br>

3. Kemudian cek versi
    <br>
   <img src=".image/3.PNG">
   <br>

4. Install version nodejs 10, dengan perintah sebagai berikut :
   <br>
   <img src=".image/4.PNG">
   <br>

5. lalu lakukan clone repository frontend-dumbplay dengan perintah tersebut :
   
   <br>
   <img src=".image/5.PNG">
   <br>

6. Kemudian rename folder dari `dumbplay-frontend` menjadi `frontend`
   
   <br>
   <img src=".image/6.PNG">
   <br>

7. Kemudian masuk ke direktori `frontend` dan ketik perintah `npm install`
   <br>
   <img src=".image/7.PNG">
   <br>
8. Kemudian install pm2 
      <br>
   <img src=".image/8.PNG">
   <br>

9.  Kemudian generate ecosystem dengan menggunakkan perintah `pm2 init simple`
    <br>
   <img src=".image/9.PNG">
   <br>

10. kemudian edit `ecosystem.config.js`
    <br>
   <img src=".image/10.PNG">
   <br>

11. Kemudian jalankan `pm2 start ecosystem.config.js`
    <br>
   <img src=".image/11.PNG">
   <br>
12. Hasilnya seperti berikut
    <br>
   <img src=".image/11_1.PNG">
   <br>
13. Kemudian install nginx
    <br>
   <img src=".image/13.PNG">
   <br>
14. Kemudian tambahkan buat folder pada /etc/nginx
    <br>
   <img src=".image/14.PNG">
   <br>
15. Kemudian tambahkan pada /etc/nginx/nginx.conf dan setelah itu ketik perintah `sudo nginx -t` dan `sudo systemctl reload nginx`
    <br>
   <img src=".image/15.PNG">
   <br>

16. Kemudian buat konfigurasi
    <br>
   <img src=".image/16.PNG">
   <br>
17. Dan hasilnya seperti ini
     <br>
   <img src=".image/17.PNG">
   <br>