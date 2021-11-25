# Deployment Backend

1. Kita buat ec2 di private ip
2. lalu ubah folder menjadi backend
   <br>
   <img src=".image/2.PNG">
   <br>
   
3. Kemudian kita rubah konfigurasi `/backend/config/config.json
   <br>
   <img src=".image/3.PNG">
   <br>
   
4. install sequelize untuk mengelola database yang kita miliki.
   <br>
   <img src=".image/4.PNG">
   <br>
5. Lakukan migrate, agar database yang didalam aplikasi ter migrate kedalam sebuah database
   <br>
   <img src=".image/5.PNG">
   <br>
6. cek apakah sudah berhasil termigrasi
   <br>
   <img src=".image/6.PNG">
   <br>
7. Lalu copy ubah .env-copy menjadi .env
   <br>
   <img src=".image/7.PNG">
   <br>
8. untuk dapat melakukan crud pada aplikasi online, kita pergi ke aplikasi frontennd dan masuk ke dalam file dan folder berikut.
   <br>
   <img src=".image/8.PNG">
   <br>
9.  Kemudian jalankan pm2 untuk backend
    <br>
   <img src=".image/9.PNG">
   <br>