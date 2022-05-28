# Cross The Road

## Daftar Anggota

| Nama          | NIM       |  Github                                                 |
| ------------- | ----------|---------------------------------------------------|
| Yogi Immanuel Pinem | 120140011 | YogiPinem |
| Jody Fabian Lingga | 120140035 | JodyFabianLingga-120140035 | 
| Tegar Abimanyu | 120140112 | TegarAbimanyu |
| Raja Josua Simanungkalit | 120140134 | RajaJosuaS |
| Daniel Albertus Turnip | 120140140 | DanielTurnip |
| M.Rafif | 120140148 |RafiifMhd|


## Cross The Road

|Cross The Road

Aplikasi ini merupakan permainan yang dibuat menggunakan library pygame yang bertujuan untuk mencapai kotak harta karun dengan menghindari musuh musuh yang menghalangi jalan. Pada setiap kali pemain berhasil mencapai kotak harta karun maka kesulitan permainan akan berubah setiap kali pemain berhasil mendapatkan kotak harta karun.


Langkah pertama RUN DOCKER, Lalu NYALAKAN XLauch setelah XLauch menyala Masuk ke-Program. 
#BUILD DOCKER IMAGE, dengan perintah
```
docker build -t docker-game .
```
Selanjutnya 
#RUN DOCKER CONTAINER dengan perintah 
```
docker run --rm -it -e DISPLAY=192.168.1.49:0.0 -v D:\jodi\Hands-On-4:/usr/project docker-game /bin/bash
```
Note:
1. ganti ip address sesuai ip kalian
2. ganti D:\jodi\Hands-On-4 sesuai lokasi main.py

Langkah Terakhir
#RUN GAME DI CONTAINER dengan perintah
```
python main.py
```
## VIDEO DEMO CONTAINER
[![TEKAN GAMBAR UNTUK MENAMPILKAN VIDEO](https://img.youtube.com/vi/WwipZp0RXro/0.jpg)](https://www.youtube.com/watch?v=WwipZp0RXro)

# KLIK GAMBAR UNTUK MENAMPILKAN VIDEO
