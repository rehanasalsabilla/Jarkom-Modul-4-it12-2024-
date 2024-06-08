# Jarkom-Modul-4-it12-2024-

### Kelompok: it12
### Anggota: 
Nama | NRP | 
--- | --- |
Rehnana Putri Salsabilla | 5027221015 | 
Muhammad Rifqi Oktaviansyah | 5027221067 | 

## Daftar Isi
- [Topologi](#topologi)
  - [Topologi PKT CIDR](#topologi-pkt-cidr)
  - [Topologi GNS3 VLSM](#topologi-gns3-vlsm)
- [Prefix IP](#prefix-ip)
- [Rute](#rute)
- [CIDR](#cidr)
  - [Penggabungan IP](#penggabungan-ip)
  - [Tree](#tree)
  - [Pembagian IP](#pembagian-ip)
  - [Testing](#testing)
- [VLSM](#vlsm)
  - [Tree](#tree)
  - [Pembagian IP](#pembagian-ip)
  - [Konfigurasi Network](#konfigurasi-network)
  - [Routing](#routing)
  - [Testing](#testing) 

## Topologi 
### Topologi PKT CIDR
![jarkom](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/abd61386-7cb6-426f-bb46-094fe719df7d)

### Topologi GNS VLSM
<img width="640" alt="TOPOLOGI" src="https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/136863633/88583d97-c8d2-4206-867f-f03fb79f6d71">

## Prefix IP
Prefix IP Kelompok IT 12 ```192.239```

## Rute
Berikut merupakan rute dari hasil routing yang kami dapatkan
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/6bc8dfe1-40a0-4ea3-ac7f-19f43006675f)

## CIDR
### Penggabungan IP
Berikut merupakan beberapa penggabungan IP yang kami lakukan pada teknik pengelompokan CIDR yang dilakukan pada Cisco Packet Tracer (CPT)

#### Kondisi Node Awal
![Subnet 1](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/f63abdcf-ce9a-4617-8158-85e58470ea86)

#### Penggabungan Node Pertama (B)
![Subnet 2](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/32cafc17-a20a-4841-9c52-22278aac60fb)
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/876a9d9b-5064-4446-9eac-e0aeaf76a5bf)

#### Penggabungan Node Kedua (C)
![Subnet 3](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/bddc7732-a92e-45b6-befc-3a5859715682)
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/32b12c20-19c4-4530-9c7d-96685b68903f)

#### Penggabungan Node Ketiga (D)
![Subnet 4](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/d88d59cd-9a92-413d-826a-30197aec3e8e)
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/7d364daf-00d0-4642-9721-f3a3450c12f3)

#### Penggabungan Node Keempat (E)
![Subnet 5](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/ee98b303-0880-4f4d-9588-68e167b68339)
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/32098bb8-69e5-4092-ab70-afdd94c57d78)

#### Penggabungan Node Kelima (F)
![Subnet 6](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/50cd2358-b796-4425-b839-3075c46db96d)
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/acddb4a6-0729-4a79-a3c2-8bd3e332b73a)

#### Penggabungan Node Keenam (G)
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/28afb5ef-d5dd-451f-94b5-4c2df861681c)

#### Penggabungan Node Ketujuh (H)
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/408e39f3-d949-43ee-a062-7e93edfe30f7)

#### Penggabungan Node Kedelapan (I)
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/50f11998-c349-4d14-9a79-f5f301959869)

### Tree
![Treee](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/1cef1d04-188d-4014-aab2-f3e67c14c740)

### Pembagian IP
![image](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/143682058/8558988d-37b0-4311-9aab-f61c202c0260)

### Testing

## VLSM
### Tree
![VLSM](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/136863633/9659853c-c04c-4d9a-af84-d13a0d73f28e)

### Pembagian IP
![Screenshot 2024-06-08 022518](https://github.com/rehanasalsabilla/Jarkom-Modul-4-it12-2024-/assets/136863633/1eaab702-e958-4dc6-9c19-f153a9cf97e4)

### Konfigurasi Network
- JAWA
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

#A1
auto eth1
iface eth1 inet static
address 192.239.21.201
netmask 255.255.255.252

#A7
auto eth2
iface eth2 inet static
address 192.239.21.197
netmask 255.255.255.252

#A15
auto eth3
iface eth3 inet static
address 192.239.21.205
netmask 255.255.255.252
```

- SUMATERA
```
auto lo
    iface lo inet loopback

    #A15 
    auto eth0
    iface eth0 inet static
	address 192.239.21.206
	netmask 255.255.255.252
    gateway 192.239.21.204

    #A16
    auto eth1
    iface eth1 inet static
	address 192.239.21.65
	netmask 255.255.255.224
    
    #A20 
    auto eth2
    iface eth2 inet static
	address 192.239.21.193
	netmask 255.255.255.252
```

- LAMPUNG
```
auto lo
    iface lo inet loopback

    #A20
    auto eth0
    iface eth0 inet static
	address 192.239.21.194
	netmask 255.255.255.252
    gateway 192.239.21.193

    #A21
    auto eth1
    iface eth1 inet static
	address 192.239.19.1
	netmask 255.255.255.0
```

- PC-SEBUKU (188 Host)
```
    #A21 
    auto eth0
    iface eth0 inet static
	address 192.239.19.2
	netmask 255.255.255.0
    gateway 192.239.19.1
```

- SERVER-SEBESI
```
    #A21 
    auto eth0
    iface eth0 inet static
	address 192.239.19.3
	netmask 255.255.255.0
    gateway 192.239.19.1
```

- SUMATERA-UTARA
```
auto lo
    iface lo inet loopback

    #A20
    auto eth0
    iface eth0 inet static
	address 192.239.21.68
	netmask 255.255.255.224
    gateway 192.239.21.65

    #A17
    auto eth1
    iface eth1 inet static
	address 192.239.21.185
	netmask 255.255.255.252
```

- PC-SAMOSIR (14 Host)
```
    #A16 
    auto eth0
    iface eth0 inet static
	address 192.239.21.67
	netmask 255.255.255.224
    gateway 192.239.21.65
```

- PC-SIBANDANG (11 Host)
```
    #A16 
    auto eth0
    iface eth0 inet static
	address 192.239.21.66
	netmask 255.255.255.224
    gateway 192.239.21.65
```

- ACEH
```
auto lo
    iface lo inet loopback

    #A17 
    auto eth0
    iface eth0 inet static
	address 192.239.21.186
	netmask 255.255.255.252
    gateway 192.239.21.185

    #A18 
    auto eth1
    iface eth1 inet static
	address 192.239.20.1
	netmask 255.255.255.128
    
    #A19 
    auto eth2
    iface eth2 inet static
	address 192.239.21.129
	netmask 255.255.255.224
```

- PC-STARLAND (44 Host)
```
    #A17 
    auto eth0
    iface eth0 inet static
	address 192.239.20.4
	netmask 255.255.255.128
    gateway 192.239.20.1
```

- PC-ENANG-ENANG (27 Host)
```
    #A17 
    auto eth0
    iface eth0 inet static
	address 192.239.20.3
	netmask 255.255.255.128
    gateway 192.239.20.1
```

- PC-BERAWANG-TAMPU (63 Host)
```
    #A17 
    auto eth0
    iface eth0 inet static
	address 192.239.20.2
	netmask 255.255.255.128
    gateway 192.239.20.1
```

- KALIMANTAN
```
auto lo
    iface lo inet loopback

    #A7 
    auto eth0
    iface eth0 inet static
	address 192.239.21.198
	netmask 255.255.255.252
    gateway 192.239.21.197

    #A8 
    auto eth1
    iface eth1 inet static
	address 192.239.21.189
	netmask 255.255.255.252
```

- KALIMANTAN-UTARA
```
auto lo
    iface lo inet loopback

    #A8 
    auto eth0
    iface eth0 inet static
	address 192.239.21.190
	netmask 255.255.255.252
    gateway 192.239.21.189

    #A9 
    auto eth1
    iface eth1 inet static
	address 192.239.18.1
	netmask 255.255.255.0
    
    #A10
    auto eth2
    iface eth2 inet static
	address 192.239.21.181
	netmask 255.255.255.252
```

- PC-SELIMAU (200 Host)
```
    #A9 
    auto eth0
    iface eth0 inet static
	address 192.239.18.2
	netmask 255.255.255.0
    gateway 192.239.18.1
```

- KALIMANTAN-TIMUR
```
auto lo
    iface lo inet loopback

    #A10 
    auto eth0
    iface eth0 inet static
	address 192.239.21.182
	netmask 255.255.255.252
    gateway 192.239.21.181

    #A12
    auto eth1
    iface eth1 inet static
	address 192.239.21.177
	netmask 255.255.255.252
    
    #A11
    auto eth2
    iface eth2 inet static
	address 192.239.16.1
	netmask 255.255.254.0
```

- SERVER-BINGKIRAI
```
    #A11
    auto eth0
    iface eth0 inet static
	address 192.239.16.2
	netmask 255.255.254.0
    gateway 192.239.16.1
```

- PC-LAMARU (488 Host)
```
    #A11
    auto eth0
    iface eth0 inet static
	address 192.239.16.3
	netmask 255.255.254.0
    gateway 192.239.16.1
```

- KALIMANTAN-SELATAN
```
auto lo
    iface lo inet loopback

    #A12 
    auto eth0
    iface eth0 inet static
	address 192.239.21.178
	netmask 255.255.255.252
        gateway 192.239.21.177

    #A14
    auto eth1
    iface eth1 inet static
	address 192.239.0.1
	netmask 255.255.255.0
    
    #A13 
    auto eth2
    iface eth2 inet static
	address 192.239.21.97
	netmask 255.255.255.224
```

- PC-ANGSANA (16 Host)
```
    #A13
    auto eth0
    iface eth0 inet static
	address 192.239.21.98
	netmask 255.255.255.224
    gateway 192.239.21.97
```

- PC-BATAKAN (1020 Host)
```
    #A14 
    auto eth0
    iface eth0 inet static
	address 192.239.0.2
	netmask 255.255.248.0
    gateway 192.239.0.1
```

- PC-TAKSIUNG (613 Host)
```
    #A14 
    auto eth0
    iface eth0 inet static
	address 192.239.0.3
	netmask 255.255.248.0
    gateway 192.239.0.1
```

- PC-BAJUIN (611 Host)
```
    #A14
    auto eth0
    iface eth0 inet static
	address 192.239.0.4
	netmask 255.255.248.0
    gateway 192.239.0.1
```

- SULAWESI
```
auto lo
    iface lo inet loopback

    #A1 
    auto eth0
    iface eth0 inet static
	address 192.239.21.202
	netmask 255.255.255.252
    gateway 192.239.21.200

    #A2 
    auto eth1
    iface eth1 inet static
	address 192.239.20.129
	netmask 255.255.255.128
    
    #A4 
    auto eth2
    iface eth2 inet static
	address 192.239.21.161
	netmask 255.255.255.248
```

- PC-GORONTALO (32 Host)
```
    #A2 
    auto eth0
    iface eth0 inet static
	address 192.239.20.130
	netmask 255.255.255.128
    gateway 192.239.20.129
```

- PC-MARISA (30 Host )
```
    #A2
    auto eth0
    iface eth0 inet static
	address 192.239.20.131
	netmask 255.255.255.128
    gateway 192.239.20.129
```

- BELAWA
```
auto lo
    iface lo inet loopback

    #A4 
    auto eth0
    iface eth0 inet static
	address 192.239.21.163
	netmask 255.255.255.248
    gateway 192.239.21.161

    #A5 
    auto eth1
    iface eth1 inet static
	address 192.239.21.1
	netmask 255.255.255.192
```

- PC-MADINI (30 Host)
```
    #A5
    auto eth0
    iface eth0 inet static
	address 192.239.21.2
	netmask 255.255.255.192
    gateway 192.239.21.1
```
  
- PC-BARU (30 Host)
```
    #A5
    auto eth0
    iface eth0 inet static
	address 192.239.21.3
	netmask 255.255.255.192
    gateway 192.239.21.1
```

- MAKASAR
```
auto lo
    iface lo inet loopback

    #A4 SW-Sulsel - Makasar
    auto eth0
    iface eth0 inet static
	address 192.239.21.162
	netmask 255.255.255.248
    gateway 192.239.21.161

    #A6 Makasar-SW-Limbung
    auto eth1
    iface eth1 inet static
	address 192.239.21.169
	netmask 255.255.255.248
```

- SERVER-GALESONG
```
    #A6 
    auto eth0
    iface eth0 inet static
	address 192.239.21.170
	netmask 255.255.255.248
    gateway 192.239.21.169
```

- SERVER-TOPEJAWA-TAKALAR
```
    #A6
    auto eth0
    iface eth0 inet static
	address 192.239.21.171
	netmask 255.255.255.248
    gateway 192.239.21.169
```

- MALUKU-UTARA
```
auto lo
    iface lo inet loopback

    #A2 
    auto eth0
    iface eth0 inet static
	address 192.239.20.132
	netmask 255.255.255.128
    gateway 192.239.20.129

    #A3 
    auto eth1
    iface eth1 inet static
	address 192.239.8.1
	netmask 255.255.248.0
```

- PC-TOBELO (511 Host)
```
    #A3 
    auto eth0
    iface eth0 inet static
	address 192.239.8.2
	netmask 255.255.248.0
    gateway 192.239.8.1 
```

- SERVER-MOROTAI
```
    #A3
    auto eth0
    iface eth0 inet static
	address 192.239.8.3
	netmask 255.255.248.0
    gateway 192.239.8.1
```

- PC-TERNATE (511 Host)
```
    #A3
    auto eth0
    iface eth0 inet static
	address 192.239.8.4
	netmask 255.255.248.0
    gateway 192.239.8.1
```

### Routing

### Testing





