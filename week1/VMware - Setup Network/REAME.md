# Setup Network

1. Saat setup customize hardware pilih network connection dengan Bridged
   <br>
   <img src=".image/1.PNG" height=300>
   <br>

2. Kemudian masuk ubuntu server kemudian edit `sudo nano /etc/netplan/00-installer-config.yaml`
   <br>
   <img src=".image/2.PNG">
   <br>
   
3. kemudian ketikkan perintah
   
         sudo netplan --debug apply
   <br>
   <img src=".image/3.PNG">
   <br>
   
4. kemudian kita coba ping google
   <br>
   <img src=".image/4.PNG">
   <br>
   