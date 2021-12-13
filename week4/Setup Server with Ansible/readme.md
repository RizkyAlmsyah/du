# Setup Server with Ansible

# install ansible
1. konfigurasi PPA
   ```
   sudo apt update
   sudo apt install software-properties-common
   sudo add-apt-repository --yes --update ppa:ansible/ansible
    ```
2. kemudian install apt ansible
<br>
   <img src=".image/1.PNG">
   <br>
    <br>

# Define host server

1. Buat directory ansible dan buat hosts untuk menyimpan konfigurasi host
<br>
   <img src=".image/2.PNG">
   <br>
   <br>
   <img src=".image/3.PNG">
   <br>
2. kemudian cek ping
    <br>
   <img src=".image/4.PNG">
   <br>

# Setup User

1. Disini saya menggunakkan ansible-playbook
2. Siapkan konfigurasi untuk membuat user
    <br>
   <img src=".image/5.PNG">
   <br>
3. Kemudian jalankan `ansible-playbook user.yml`
     <br>

# Setup Nginx
1. Siapkan konfigurasi untuk nginx dan kemudian jalankan `ansible-playbook nginx.yml`
    <br>
   <img src=".image/6.PNG">
   <br>

# Setup CICD
1. Siapkan konfigurasi untuk jenkins dan kemudian jalankan `ansible-playbook jenkins.yml`

    <br>
   <img src=".image/7.PNG">
   <br>

# Setup Database


1. Siapkan konfigurasi untuk database dan kemudian jalankan `ansible-playbook db.yml`

    <br>
   <img src=".image/8.PNG">
   <br>


# Setup Backend

1. siapkan konfigurasi untuk be dan kemudian jalankan `ansible-playbook be.yml`
    <br>
   <img src=".image/9.PNG">
   <br>

# Setup Frontend

1. siapkan konfigurasi untuk be dan kemudian jalankan `ansible-playbook fe.yml`

    <br>
   <img src=".image/10.PNG">
   <br>

Hasilnya seperti berikut

<br>
   <img src=".image/11.PNG">
   <br>
    <br>
   <img src=".image/12.PNG">
   <br>
    <br>
   <img src=".image/13.PNG">
   <br>

