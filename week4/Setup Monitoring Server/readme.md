# Setup Monitoring with Promotheus

1. Pertama-tama siapkan install node-exporter tiap server disini saya menggunakkan ansible
2. untuk konfigurasi instalasi node-exporter seperti berikut
   <br>
   <img src=".image/0.PNG">
   <br>
3. kemudian jalankan `ansible-playbook node_exporter.yml`
   <br>
   <img src=".image/1.PNG">
   <br>
4. untuk hasilnya seperti ini
   <br>
   <img src=".image/3_1.PNG">
   <br>
   <br>
   <img src=".image/3_2.PNG">
   <br>
   <br>
   <img src=".image/3_2.PNG">
   <br>

# Install grafana dan prometheus

1. Disini saya juga menggunakkan ansible
2. Untuk konfigurasi instalasi grafana dan promethus seperti ini
   <br>
   <img src=".image/4_1.PNG">
   <br>
   <br>
   <img src=".image/4.PNG">
   <br>
3. siapakan reverse-proxy untuk ansible dan grafana
   <br>
   <img src=".image/4_2.PNG">
   <br>
   <br>
   <img src=".image/4_3.PNG">
   <br>
4. Hasilnya seperti berikut
   <br>
   <img src=".image/5.PNG">
   <br>
   <br>
   <img src=".image/5_1.PNG">
   <br>