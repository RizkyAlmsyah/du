# SSL Configuration

1. pertama-tama buka cloudflare dan buka api key di profile
   <br>
   <img src=".image/1.PNG" height=300>
   <br>
2. kemudian buat file pada `/root/.secrets/cloudflare.ini`
   <br>
   <img src=".image/2.PNG">
   <br>
3. kemudian lakukan langkah2 berikut ini
   
        $ sudo apt-get install certbot python3-certbot-nginx python3-certbot-dns-cloudflare
    <br>
   <img src=".image/3.PNG">
   <br>
4. kemudian tambahkan perintah ini
        
        $ sudo certbot --dns-cloudflare --dns-cloudflare-credentials /root/.secrets/cloudflare.ini -d rizky.onlinecamp.id, --preferred-challenges dns-01 -i nginx
   
   <br>
   <img src=".image/4.PNG">
   <br>

5. hasilnya seperti berikut
   <br>
   <img src=".image/5.PNG">
   <br>
   
   
   
   

