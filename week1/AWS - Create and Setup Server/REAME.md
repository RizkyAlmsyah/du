# Create and Setup Server

        arsitektur yang saya gunakkan di aws


<br>
   <img src=".image/1.png">
   <br>

1. Login terlebih dahulu ke aws `https://aws.amazon.com/id/education/awseducate/`
2. Kemudian cari vpc di service kemudian create vpc
   <br>
   <img src=".image/2.PNG">
   <br>
   <img src=".image/2_1.PNG">
   <br>
3. Kemudian beri nama dan isi Ipv4 CIDR block nya
   <br>
   <img src=".image/3.PNG">
   <br>
4. Kemudian tambahkana subnet untuk public subnet 10.0.1.0/24 & untuk private subnet 10.0.2.0
   <br>
   <img src=".image/4.PNG">
   <br>
5. Kemudian buat internet gateway dan attach ke dumbflix-vpc
   <br>
   <img src=".image/5.PNG">
   <br>
   <br>
   <img src=".image/5_1.PNG">
   <br>
6. sekarang buat tambahkan igw di route table ke public route dan tambahkan public subnet ke main route table
   <br>
   <img src=".image/6.PNG">
   <br>
   <br>
   <img src=".image/6_1.PNG">
   <br>
7. sekarang buat 2 elastic ip yang satu untuk reverse proxy dan yang satu untuk nat gateway
   <br>
   <img src=".image/7.PNG">
   <br>
8. Kemudian buat nat gateway
   <br>
   <img src=".image/8.PNG">
   <br>
   <br>
   <img src=".image/8_1.PNG">
   <br>
9.  Kemudian buat private route table dan tambahkan nat gw pada route
    <br>
   <img src=".image/9.PNG">
   <br>
10. Kemudian buat ec2 untuk reverse proxy dengan klik launch instance
    <br>
   <img src=".image/10.PNG">
   <br>
11. Kemudian cari ubuntu kemudian klik select
    <br>
   <img src=".image/11.PNG">
   <br>
12. pilih instance type 
    <br>
   <img src=".image/12.PNG">
   <br>
13. Lalu lakukan configurasi 
    <br>
   <img src=".image/13.PNG">
   <br>
14. Lalu disecurity group untuk `reverse proxy`
    <br>
   <img src=".image/14.PNG">
   <br>
15. Lalu klik review, jika sudah selesai klik finish
    <br>
   <img src=".image/15.PNG">
   <br>
16. Ketika kita menekan select maka akan muncul pop up untuk membuat atau memilih key pair yang sudah ada
    <br>
   <img src=".image/16.PNG">
   <br>
17. Kemudian kita masukkan ip public dengan elastic ip yang kita buat tadi ke reverse proxy
    <br>
   <img src=".image/17.PNG">
   <br>
18. Kemudian kita buat ec2 instance untuk front end sama seperti membuat reverse proxy yang membedakan pada konfigurasi dan security group
    <br>
   <img src=".image/18.PNG">
   <br>
   <br>
   <img src=".image/18_1.PNG">
   <br>
   <br>
   <img src=".image/18_2.PNG">
   <br>