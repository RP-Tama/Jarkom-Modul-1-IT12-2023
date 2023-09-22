# Jarkom-Modul-1-IT12-2023

## Soal 6
### Screenshot
Tampilan wsl untuk mendapatkan flag
![no5 1](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/d4e95315-b398-471f-85c9-465c8d6e85d9)

Tampilan Wireshark ketika mencoba filter expression yang menjadi jawaban soal
![no6 111](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/95fc7530-460e-4a0a-9fb0-df9496ab3cc1)

### Cara Pengerjaan
* membuka soal yang tersedia pada platform serta memasukkan kode ncat pada wsl
* memasukkan filter expression tcp.stream eq 324
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
* memasukkan filter expression ip.dst untuk mendapatkan ip
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
### Kendala yang Dihadapi

## Soal 9
### Screenshot
Tampilan wsl untuk mendapatkan flag
![no9 2](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/e3aa709a-81e5-46dd-bd6b-a2f69dbf3599)

Tampilan Wireshark ketika mencoba filter expression yang menjadi jawaban soal
![no9 1](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/637a6f89-1e60-48ca-bee3-8c5b9429232c)

### Cara Pengerjaan
### Kendala yang Dihadapi

## Soal 10
### Screenshot
Tampilan wsl untuk mendapatkan flag
![no10 2](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/51b8f0b1-5370-44ba-b15f-7848d6bc78d3)

Tampilan Wireshark ketika mencoba filter expression yang menjadi jawaban soal
![no10](https://github.com/RP-Tama/Jarkom-Modul-1-IT12-2023/assets/107543354/ae7376b4-983f-46fb-8e89-39b14887bd2b)
### Cara Pengerjaan
### Kendala yang Dihadapi
* harus mencoba semua kemungkinan username dan password hingga menemukan jawaban yang benar untuk mendapat flag
