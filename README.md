# Jarkom-Modul-1-IT12-2023
Nama Anggota :
1. Raditya Pratama 	(5027211047)
2. Salmaa Satifha Dewi (5027211011)

## Soal 1
### Screenshot
### Cara Pengerjaan
### Kendala yang Dihadapi

## Soal 2
### Screenshot
### Cara Pengerjaan
### Kendala yang Dihadapi

## Soal 3
### Screenshot
### Cara Pengerjaan
### Kendala yang Dihadapi

## Soal 4
### Screenshot
### Cara Pengerjaan
### Kendala yang Dihadapi

## Soal 5
### Screenshot
### Cara Pengerjaan
### Kendala yang Dihadapi

## Soal 6
### Screenshot
Tampilan wsl untuk mendapatkan flag
![no5 1](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/d4e95315-b398-471f-85c9-465c8d6e85d9)

Tampilan Wireshark ketika mencoba filter expression yang menjadi jawaban soal
![no6 111](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/95fc7530-460e-4a0a-9fb0-df9496ab3cc1)

### Cara Pengerjaan
* membuka soal yang tersedia pada platform serta memasukkan kode ncat pada wsl
* memasukkan filter expression tcp.stream eq 324 di wireshark
* mencari nomer paket 7812, dari sini ditemukan alamat IP srcnya 104.18.14.101
* karena dilakukan substitusi maka dipisah menjadi 10 4 18 14 10 1
* kemudian dari angka tersebut di ubah dalam bentuk alphabet menjadi JDRNJA
* memasukkan jawaban "JDRNJA" ke wsl dan didapatkan flag
  
### Kendala yang Dihadapi
* harus menebak nebak dalam pengerjaan soal

## Soal 7
### Screenshot
Tampilan wsl untuk mendapatkan flag
![no6 2](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/f87f842c-a66d-4eb0-8435-c9814eb9dfa6)

Tampilan Wireshark saat mencari IP yang ditanyakan
![image](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/17336a2f-0aa1-45ee-97b0-7cc8c060f69e)
### Cara Pengerjaan
* membuka soal yang tersedia pada platform serta memasukkan kode ncat pada wsl
* memasukkan filter expression ip.dst untuk mendapatkan ip di wireshark
* mencari paket destinasi yang memiliki IP 184.87.193.88
* menghitung total alamat destinasi dengan IP 184.87.193.88 yang ada, ditemukan terdapat 6 alamat IP
* memasukkan jawaban "6" ke wsl dan didapatkan flag
  
### Kendala yang Dihadapi
* tidak ditemukan kendala
  
## Soal 8
### Screenshot
Tampilan wsl untuk mendapatkan flag
![no8 2](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/dc341042-58d0-4fde-bc48-10007f7c8374)

Tampilan Wireshark ketika mencoba filter expression yang menjadi jawaban soal
![no8 1](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/05a0a474-f0f0-4651-b3e8-47cb8cef030b)

### Cara Pengerjaan
* membuka soal yang tersedia pada platform serta memasukkan kode ncat pada wsl
* memasukkan filter expression tcp.dstport == 80 || udp.dstport == 80 di wireshark
* karena filter expression sudah sesuai maka bisa dimasukkan ke ncat untuk mendapatkan flag
* yang dimasukkan ke ncat adalah filter expression sesuai yang ditanyakan yaitu "tcp.dstport == 80 || udp.dstport == 80"
  
### Kendala yang Dihadapi
* tidak ditemukan kendala
  
## Soal 9
### Screenshot
Tampilan wsl untuk mendapatkan flag
![no9 2](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/e3aa709a-81e5-46dd-bd6b-a2f69dbf3599)

Tampilan Wireshark ketika mencoba filter expression yang menjadi jawaban soal
![no9 1](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/637a6f89-1e60-48ca-bee3-8c5b9429232c)

### Cara Pengerjaan
* membuka soal yang tersedia pada platform serta memasukkan kode ncat pada wsl
* memasukkan filter expression ip.src == 10.51.40.1 && ip.dst != 10.39.55.34 di wireshark
* karena filter expression sudah sesuai maka bisa dimasukkan ke ncat untuk mendapatkan flag
* yang dimasukkan ke ncat adalah filter expression sesuai yang ditanyakan yaitu "ip.src == 10.51.40.1 && ip.dst != 10.39.55.34"
  
### Kendala yang Dihadapi
* tidak ditemukan kendala
  
## Soal 10
### Screenshot
Tampilan wsl untuk mendapatkan flag
![no10 2](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/51b8f0b1-5370-44ba-b15f-7848d6bc78d3)

Tampilan Wireshark ketika mencoba filter expression yang menjadi jawaban soal
![no10](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/ae7376b4-983f-46fb-8e89-39b14887bd2b)
### Cara Pengerjaan
* membuka soal yang tersedia pada platform serta memasukkan kode ncat pada wsl
* memasukkan filter expression telnet di wireshark
* melakukan follow TCP Streamnya dan nanti di tcp stream akan ada username dan password dari telnet nya.
* karena ada banyak username dan password, maka dicoba satu persatu sampai ditemukan jawaban yang benar
* memasukkan username dan password ini di ncat sehingga akan menemukan flag
  
### Kendala yang Dihadapi
* harus mencoba semua kemungkinan username dan password hingga menemukan jawaban yang benar untuk mendapat flag
