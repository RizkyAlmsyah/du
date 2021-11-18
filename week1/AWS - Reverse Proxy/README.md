# Reverse Proxy

1. akses ke server melalui ssh `ssh rizky@3.218.7.173`
   <br>
   <img src=".image/1.PNG">
   <br>
2. karena sudah diupdate dan upgrade maka selanjutnya install nginx
   <br>
   <img src=".image/2.PNG">
   <br>
3. Kemudian cek status nginx
   <br>
   <img src=".image/3.PNG">
   <br>
4. Kemudian buat file frontend pada `etc/nginx/` dan rubah kepimilikan
   <br>
   <img src=".image/4.PNG">
   <br>
5. kemudian buat file pada direktroi frontend `rizky.onlinecamp.id` dan tambahkan folde yang dinclude pada `etc/nginx/nginx_conf
   <br>
   <img src=".image/5.PNG">
   <br>
   <br>
   <img src=".image/5_1.PNG">
   <br>
6. kemudian cek konfigurasi apakah berhasil dan juga reload
   <br>
   <img src=".image/6.PNG">
   <br>
7. kemudian kita cek apakah berhasil
   <br>
   <img src=".image/7.PNG">
   <br>