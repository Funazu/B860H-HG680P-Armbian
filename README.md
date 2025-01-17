# B860H-HG680P-Armbian
User Default : root  
Password : 1234  

## DOWNLOAD ISO
[Download here](https://github.com/hafidhh/B860H-HG680P-Armbian/releases/download/Armbian_22.08.0_Aml_s905x_bullseye/Armbian_22.08.0_Aml_s905x_bullseye_5.10.123_server_2022.06.17.img.gz)

## Buat Bootable  
Extract  
Buat bootable dengan bootable maker ([Rufus](https://rufus.ie/) atau [balenaEtcher](https://www.balena.io/etcher/))  
Copy file dtb ke /dtb/armbian  

note : dtb sudah disesuaikan untuk RAM 2gb, untuk ram 1gb tidak perlu copy dtb

## Setting Armbian  
Setting WiFi, jam dll  
Login Armbian -> input command
```yaml
armbian-config
```

## Maximize penggunaan SDcard atau Flashdisk  
Perinatah ini bertujuan untuk menggunakan seluruh kapasitas yang tersedia sebagai ROOT  
Login Armbian -> input command
```yaml
armbian-tf
```

## Docker
Install Docker   
Login Armbian -> input command
```yaml
armbian-docker
```
  
  
Terimakasih untuk [ophub](https://github.com/ophub) yang telah menyediakan file iso armbian untuk amlogic s905x
