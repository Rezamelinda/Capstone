# Capstone
Instalasi Capstone
Capstone Project 
Capstone Project bidang Pendidikan

1. Langkah pertama yakni dengan melakukan pembuatan VM dengan create virtual machine menggunakan Azure Portal
2. Selanjutnya dapat di akses virtual machine yang telah di rancang melalui CMD/Putty atau terminal lainnya ( SSH username@ip )
3. Kemudian pilih os dan size sesuai yang diinginkan
4. Selanjutnya buatlah password administration yang digunakan untuk autorisasi virtual machine
5. Untuk setup virtual machine sesuai dengan yang diinginkan klik review dan selanjutnya klik create untuk membuat 
6. Nantinya tampilan layar akan muncul "validation passed" dan kemudian klik create
7. Ketika tahapan sebelumnya telah  berhasil deployment, kemudian klik "go to resources"
8. Bila telah terbuat virtual machine maka akan muncul bagian IP Public
9. IP Public Address dapat dilihat di atas Virtual network/subnet
10. Untuk Virtual network/subnet milik saya ialah : Meldaday-vnet/default
11. Dengan Public IP address : 13.67.116.67
12. Tahap selanjutnya copy paste IP Public dari virtual machine
13. Dan lanjut dengan membuka cmd pada windows 10 kemudian masukkan "SSH username@IPPublic"
14. Serta tidak lupa untuk lakukan login menggunakan password dan username yang telah dibuat sebelumny


Install Moodle via docker.io


1. Untuk tahap pertama ini lakukan update pada virtual machine setelah masuk ke terminal linux menggunakan cmd dengan perintah "sudo apt update"
2. Selanjutnya lakukan penginstallan pada docker dengan perintah "sudo apt install docker.io"
3. Kemudian  download file script Moode melalui perintah "curl -sSL https://raw.githubusercontent.com/bitnami/bitnami-docker-moodle/master/docker-compose.yml > docker-compose.yml"
4. Selanjutnya lakukan penginstalasian tools docker-compose dengan perintah "sudo apt install docker-compose"
5. Tahap berikutnya eksekusi script dengna perintah "sudo docker-compose up -d"
6. Setelah selesa melakukan proses eksekusi maka tunggu lah proses eksekusi hingga selesai
7. Kemudian dapat di akses pada web LMS menggunakan IP Public dari virtual machine
8. Tahap terakhir lakukan setup DNS menggunakan layanan penyedia setiap DNS sesuai pilihan
