# Server

1. Pertama-tama buat vpc
   <br>
   <img src=".image/1.PNG">
   <br>
   <br>
   <img src=".image/1_1.PNG">
   <br>
2. Kemudian buat subnet
   <br>
   <img src=".image/2.PNG">
   <br>
   <br>
   <img src=".image/2_1.PNG">
   <br>
3. Kemudian buat internet gateway dan attach ke dumbflix-vpc
   <br>
   <img src=".image/3.PNG">
   <br>
   <br>
   <img src=".image/3_1.PNG">
   <br>
4. Kemudian buat nat gateway
   <br>
   <img src=".image/4.PNG">
   <br>
5. Kemudian tambahkan route pada route table dumbflix
   <br>
   <img src=".image/5.PNG">
   <br>
   dan tambahkan subnet public ke master
   <br>
   <img src=".image/5_1.PNG">
   <br>
   
6. kemudian buat route table untuk private
   <br>
   <img src=".image/6.PNG">
   <br>
7. tambahkan nat gateway pada route dan juga tambahkan subnet private
   <br>
   <img src=".image/7.PNG">
   <br>
   <br>
   <img src=".image/7_1.PNG">
   <br>
8. kemudian buat elastic ip untuk instance reverse-proxy
   <br>
   <img src=".image/8.PNG">
   <br>
9.  Kemudian buat instance baru untuk masing2 server
    <br>
   <img src=".image/9.PNG">
   <br>
   <br>
   <img src=".image/9_1.PNG">
   <br>