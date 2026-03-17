# Secure-Application-Design
<img width="1554" height="379" alt="image" src="https://github.com/user-attachments/assets/7b3188dc-df56-4ed0-b954-1dad773dce9b" />
- Apache
  <img width="1669" height="1014" alt="image" src="https://github.com/user-attachments/assets/fd295837-8c3c-46d4-9b25-edbc6885c5c8" />
  sudo dnf update -y
  <img width="1023" height="969" alt="image" src="https://github.com/user-attachments/assets/9dcafc08-8c08-403e-bd1d-e64f7e896e00" />
sudo dnf install httpd -y
<img width="930" height="276" alt="image" src="https://github.com/user-attachments/assets/d9dc855b-704d-4a2e-9799-b31994a7ac00" />

sudo systemctl start httpd
sudo systemctl status httpd
<img width="1576" height="949" alt="image" src="https://github.com/user-attachments/assets/9fc61713-5910-41bd-8a05-813d6628d24f" />
<img width="1689" height="780" alt="image" src="https://github.com/user-attachments/assets/05fddf72-1c2a-4795-bba3-2f3910d63da4" />
http://ec2-34-226-202-73.compute-1.amazonaws.com
<img width="1919" height="800" alt="image" src="https://github.com/user-attachments/assets/d39cccc6-696e-426f-a0b9-ed98e0c4690d" />

- sprint

<img width="1917" height="704" alt="image" src="https://github.com/user-attachments/assets/f97efd5e-4101-4017-858a-9a5b3ccafa78" />

sudo dnf install java-17-amazon-corretto -y

<img width="1868" height="965" alt="image" src="https://github.com/user-attachments/assets/3d607711-c2ab-4bcf-8ac8-6b7e0f347bb7" />

<img width="1388" height="181" alt="image" src="https://github.com/user-attachments/assets/82983a38-4063-4885-877b-ce6cfc0e140c" />

<img width="762" height="100" alt="image" src="https://github.com/user-attachments/assets/db4e2e18-a3a4-4c17-afb5-b311af818e93" />
nano App.java
<img width="1614" height="943" alt="image" src="https://github.com/user-attachments/assets/2ef7d723-3ad1-49c8-a48c-54735723d599" />
<img width="882" height="79" alt="image" src="https://github.com/user-attachments/assets/3efdf97a-b0f4-4612-aff2-745ef9c61d62" />
<img width="735" height="156" alt="image" src="https://github.com/user-attachments/assets/a59d42eb-cc1f-40b6-be96-9d788c962959" />
http://ec2-54-234-204-24.compute-1.amazonaws.com:8080/hello
<img width="1385" height="595" alt="image" src="https://github.com/user-attachments/assets/24a0db22-b253-4928-a299-a0cae603bd04" />
- apache
  
<img width="1243" height="908" alt="image" src="https://github.com/user-attachments/assets/015532f5-def2-4b4c-be20-96bcd3c027e9" />

http://ec2-34-226-202-73.compute-1.amazonaws.com/

<img width="1323" height="569" alt="image" src="https://github.com/user-attachments/assets/14a00b29-17bb-4829-8328-bf826ebda82b" />

- sprint
  <img width="1313" height="925" alt="image" src="https://github.com/user-attachments/assets/7e1e11c1-3488-442c-8176-dea6f09fdc3f" />

  - apache
    <img width="1865" height="822" alt="image" src="https://github.com/user-attachments/assets/f6b80048-8c56-4ed8-b5f3-b75d5c6406c0" />


    <img width="411" height="537" alt="image" src="https://github.com/user-attachments/assets/fd84f568-aec3-464b-b36d-5d041eb5716d" />

- 2
- Let’s Encrypt
  34-226-202-73.nip.io
  sudo dnf install certbot python3-certbot-apache -y
  <img width="1864" height="860" alt="image" src="https://github.com/user-attachments/assets/d579a167-5221-4bb4-9809-fecfac44d6b9" />

<img width="1902" height="948" alt="image" src="https://github.com/user-attachments/assets/4233d8ad-1208-4b38-9209-7ff8391b543e" />
sudo certbot --apache -d 34-226-202-73.nip.io

<img width="1289" height="137" alt="image" src="https://github.com/user-attachments/assets/06706c72-1df6-48ed-8482-9ecea939a7dd" />


sudo nano /etc/httpd/conf.d/mi-sitio.conf
<img width="1214" height="481" alt="image" src="https://github.com/user-attachments/assets/539103c8-19d5-4a1a-a55c-c37bb90c9874" />

<img width="1498" height="647" alt="image" src="https://github.com/user-attachments/assets/b883eb65-fbee-441c-b5e7-031fafa17781" />


- https://34-226-202-73.nip.io
  <img width="1232" height="558" alt="image" src="https://github.com/user-attachments/assets/87fcac84-83f4-476d-9eb5-eaf1a5c27a3a" />
<img width="1511" height="759" alt="image" src="https://github.com/user-attachments/assets/ce0956cf-4d08-44f6-b428-60630f8e7a05" />

- sprint
  sudo dnf install nginx -y
sudo systemctl start nginx
sudo systemctl enable nginx
  <img width="1909" height="888" alt="image" src="https://github.com/user-attachments/assets/084a542c-16d3-410c-849f-788ef8e646fc" />
  <img width="1724" height="344" alt="image" src="https://github.com/user-attachments/assets/bafed597-a07c-4d49-ba6d-64e123ad7c20" />
sudo dnf install certbot python3-certbot-nginx -y


  <img width="1916" height="926" alt="image" src="https://github.com/user-attachments/assets/3a8df26f-a2c1-4eb8-a9ee-bd1e0a4d1f67" />
certbot --version
certbot 2.6.0

<img width="975" height="158" alt="image" src="https://github.com/user-attachments/assets/80423bf2-119d-4f65-a93a-360ce1247109" />









