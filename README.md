# TugasDockerCompose
Untuk memenuhi tugas kuliah Teori Teknologi Cloud Computing

Tutorial lengkap beserta gambar ada di Tutorial.docx

1. Pertama - tama kita buat dulu sebuah folder, misal namanya Docker. Lokasi folder Docker ini saya letakkan di direktori Downloads
2. Lalu kita buka terminal (karena saya menggunakan Linux, di windows kalian bisa gunakan Docker Toolbox) dan kita masuk ke direktori folder yang telah kita buat tadi bernama Docker di Downloads dengan cara : cd Downloads/Docker
3. Seperti yang terlihat di atas saya telah masuk ke direktori Downloads/Docker. Saya mengetikkan perintah ls untuk melihat isi dari folder Docker yaitu ada docker-compose.yml lalu folder index dan file site.conf.
4. Kita ketikkan perintah docker images untuk melihat apa saja images yang sudah kita build
5. Lalu kita lakukan docker compose dengan mengetik perintah docker compose up -d 
6. Kita cek di browser apakah sudah berhasil kita up docker composenya dengan mengetik ip docker di browser kita (disini saya menggunakan Firefox ESR) 172.17.0.1:8080. Ip dapat kita cek menggunakan (ifconfig untuk linux dan di windows biasanya ada di awal saat menjalankan docker toolbox) dan 8080 adalah port public yang kita set di docker-compose.yml tadi
7. Selesai
