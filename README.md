# webssh-deploy-docker-compose
Deploy webssh service dengan menggunakan docker compose 

![image](https://github.com/eprilian/webssh-deploy-docker-compose/assets/57064161/9624a7ee-ce8a-4fd1-b99f-e80b5afe9c95)

Disini, menggunakan dari https://github.com/huashengdun/webssh

Pertama adalah melakukan pull github dengan command:
- git clone https://github.com/huashengdun/webssh.git

Lalu masuk ke folder webssh:
- cd webssh

Selanjutnya lakukan build image dengan command:
- docker build -t [nama-image]:[versi-image] . 

Tunggu hingga build selesai

Setelah build image berhasil dilakukan, buat docker compose (isi sesuai dengan template / kebutuhan):
- nano compose.yml

Jalankan dengan perintah:
- docker compose up -d

Tunggu hingga selesai dan saat selesai ketikan [ip-vm]:[port-webssh] pada web browser

Proses deploy webssh telah selesai
