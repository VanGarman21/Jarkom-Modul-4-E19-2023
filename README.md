# Jarkom-Modul-3-E19-2023
Laporan Resmi Praktikum Modul 3 Kelompok E19
| Nama               |  NRP       | 
|--------------------|-------------|
| M. Armand Giovani | 5025211054  |
| Afiq Fawwaz Haidar | 5025211246  |

# VLSM

## Topologi GNS3 VLSM

![topo gns3](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/100523471/a6b40833-0c03-43ea-9217-1115e5f3f747)

![xslm drawio](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/100523471/587211ff-3d0e-4b74-aa63-5b42e0e18869)

## Pembagian IP

![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/100523471/cd3b4456-b9d3-4fa4-a0ae-a510a6bf92bc)

## VLSM Tree

![VLSM E19 drawio](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/100523471/48c396fe-ad78-4498-973e-8789c9553080)

## Konfigurasi Network

- Aura
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

auto eth1
iface eth1 inet static
address 10.46.24.113
netmask 255.255.255.252

auto eth2
iface eth2 inet static
address 10.46.24.129
netmask 255.255.255.252

auto eth3
iface eth3 inet static
address 10.46.24.149
netmask 255.255.255.252
```

- Denken
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.150
netmask 255.255.255.252
gateway 10.46.24.149

auto eth1
iface eth1 inet static
address 10.46.23.1
netmask 255.255.255.0
```

- Frieren
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.114
netmask 255.255.255.252
gateway 10.46.24.113

auto eth1
iface eth1 inet static
address 10.46.24.117
netmask 255.255.255.252
gateway 10.46.24.118

auto eth2
iface eth2 inet static
address 10.46.24.65
netmask 255.255.255.224
```

- Flamme
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.118
netmask 255.255.255.252
gateway 10.46.24.117

auto eth1
iface eth1 inet static
address 10.46.24.125
netmask 255.255.255.252
gateway 10.46.24.126

auto eth2
iface eth2 inet static
address 10.46.8.1
netmask 255.255.252.0

auto eth3
iface eth3 inet static
address 10.46.24.121
netmask 255.255.255.252
gateway 10.46.24.122
```

- Fern
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.122
netmask 255.255.255.252
gateway 10.46.24.121

auto eth1
iface eth1 inet static
address 10.46.0.1
netmask 255.255.248.0
```

- Himmel
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.126
netmask 255.255.255.252
gateway 10.46.24.125

auto eth1
iface eth1 inet static
address 10.46.24.97
netmask 255.255.255.248
```

- Eisen
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.130
netmask 255.255.255.252
gateway 10.46.24.129

auto eth1
iface eth1 inet static
address 10.46.24.105
netmask 255.255.255.248

auto eth2
iface eth2 inet static
address 10.46.24.141
netmask 255.255.255.252
gateway 10.46.24.142

auto eth3
iface eth3 inet static
address 10.46.24.137
netmask 255.255.255.252
gateway 10.46.24.138

auto eth4
iface eth4 inet static
address 10.46.24.133
netmask 255.255.255.252
```

- Linie
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.142
netmask 255.255.255.252
gateway 10.46.24.141

auto eth1
iface eth1 inet static
address 10.46.24.145
netmask 255.255.255.252
gateway 10.46.24.146

auto eth2
iface eth2 inet static
address 10.46.20.1
netmask 255.255.254.0
```

- Lawine
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.146
netmask 255.255.255.252
gateway 10.46.24.145

auto eth1
iface eth1 inet static
address 10.46.24.1
netmask 255.255.255.192
gateway 10.46.24.3
```

- Heiter
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.3
netmask 255.255.255.192
gateway 10.46.24.1

auto eth1
iface eth1 inet static
address 10.46.16.1
netmask 255.255.252.0
```

- Lugner
```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet static
address 10.46.24.138
netmask 255.255.255.252
gateway 10.46.24.137

auto eth1
iface eth1 inet static
address 10.46.22.1
netmask 255.255.255.0

auto eth2
iface eth2 inet static
address 10.46.12.1
netmask 255.255.252.0
```

- Richter
```
auto eth0
iface eth0 inet static
address 10.46.24.107
netmask 255.255.255.248
gateway 10.46.24.105
```

- Revolte
```
auto eth0
iface eth0 inet static
address 10.46.24.106
netmask 255.255.255.248
gateway 10.46.24.105
```

- Sein
```
auto eth0
iface eth0 inet static
address 10.46.16.2
netmask 255.255.252.0
gateway 10.46.16.1
```

- Stark
```
auto eth0
iface eth0 inet static
address 10.46.24.134
netmask 255.255.255.252
gateway 10.46.24.133
```

- RoyalCapital(63Host)
``` 
auto eth0
iface eth0 inet static
address 10.46.23.3
netmask 255.255.255.0
gateway 10.46.23.1
```

- WilleRegion(63host)
``` 
auto eth0
iface eth0 inet static
address 10.46.23.2
netmask 255.255.255.0
gateway 10.46.23.1
```

- LakeKorridor(24Host)
```
auto eth0
iface eth0 inet static
address 10.46.24.66
netmask 255.255.255.224
gateway 10.46.24.65
```

- LaubHiils(397Host)
```
auto eth0
iface eth0 inet static
address 10.46.0.3
netmask 255.255.248.0
gateway 10.46.0.1
```

- AppetitRegion(625Host)
```
auto eth0
iface eth0 inet static
address 10.46.0.2
netmask 255.255.248.0
gateway 10.46.0.1
```

- RohrRoad(1000host)
```
auto eth0
iface eth0 inet static
address 10.46.8.2
netmask 255.255.252.0
gateway 10.46.8.1
```

- SchwerMountains(5Host)
```
auto eth0
iface eth0 inet static
address 10.46.24.98
netmask 255.255.255.248
gateway 10.46.24.97
```

- BredtRegion(29host)
```
auto eth0
iface eth0 inet static
address 10.46.24.2
netmask 255.255.255.192
gateway 10.46.24.1
```

- RiegelCanyon(510host)
```
auto eth0
iface eth0 inet static
address 10.46.16.3
netmask 255.255.252.0
gateway 10.46.16.1
```

- GranzChannel(254Host)
```
auto eth0
iface eth0 inet static
address 10.46.20.2
netmask 255.255.254.0
gateway 10.46.20.1
```

- GrobeForest(250Host)
```
auto eth0
iface eth0 inet static
address 10.46.22.2
netmask 255.255.255.0
gateway 10.46.22.1
```

- TurkRegion(1000Host)
```
auto eth0
iface eth0 inet static
address 10.46.12.2
netmask 255.255.255.0
gateway 10.46.12.1
```

## Routing

- Aura
```sh
# Denken
route add -net 10.46.23.0 netmask 255.255.255.252 gw 10.46.24.150
route add -net 10.46.24.148 netmask 255.255.255.252 gw 10.46.24.150
 
#Frieren
route add -net 10.46.24.116 netmask 255.255.255.252 gw 10.46.24.114
route add -net 10.46.24.64 netmask 255.255.255.224 gw 10.46.24.114
route add -net 10.46.24.124 netmask 255.255.255.252 gw 10.46.24.114
route add -net 10.46.8.0 netmask 255.255.252.0 gw 10.46.24.114
route add -net 10.46.24.120 netmask 255.255.255.252 gw 10.46.24.114
route add -net 10.46.0.0 netmask 255.255.248.0 gw 10.46.24.114
route add -net 10.46.24.96 netmask 255.255.255.248 gw 10.46.24.114
route add -net 10.46.24.112 netmask 255.255.255.252 gw 10.46.24.114

# Eisen
route add -net 10.46.24.104 netmask 255.255.255.248 gw 10.46.24.130
route add -net 10.46.24.140 netmask 255.255.255.252 gw 10.46.24.130
route add -net 10.46.24.136 netmask 255.255.255.252 gw 10.46.24.130
route add -net 10.46.24.132 netmask 255.255.255.252 gw 10.46.24.130
route add -net 10.46.22.0 netmask 255.255.255.0 gw 10.46.24.130
route add -net 10.46.12.0 netmask 255.255.252.0 gw 10.46.24.130
route add -net 10.46.24.144 netmask 255.255.255.252 gw 10.46.24.130
route add -net 10.46.20.0 netmask 255.255.254.0 gw 10.46.24.130
route add -net 10.46.24.0 netmask 255.255.255.192 gw 10.46.24.130
route add -net 10.46.16.0 netmask 255.255.252.0 gw 10.46.24.130
route add -net 10.46.24.128 netmask 255.255.255.252 gw 10.46.24.130
```

- Denken
```sh
route add -net 10.46.23.0 netmask 255.255.255.0 gw 10.46.23.1
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.46.24.149
```

- Frieren
```sh
# Kiri
route add -net 10.46.24.124 netmask 255.255.255.252 gw 10.46.24.118
route add -net 10.46.8.0 netmask 255.255.252.0 gw 10.46.24.118
route add -net 10.46.24.120 netmask 255.255.255.252 gw 10.46.24.118
route add -net 10.46.0.0 netmask 255.255.248.0 gw 10.46.24.118
route add -net 10.46.24.96 netmask 255.255.255.248 gw 10.46.24.118
route add -net 10.46.24.116 netmask 255.255.255.252 gw 10.46.24.118

# Atas
route add -net 10.46.24.64 netmask 255.255.255.224 gw 10.46.24.66
```

- Flamme
```sh
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.46.24.117

# Atas
route add -net 10.46.0.0 netmask 255.255.248.0 gw 10.46.24.122
route add -net 10.46.24.120 netmask 255.255.255.252 gw 10.46.24.122

# Kiri
route add -net 10.46.8.0 netmask 255.255.252.0 gw 10.46.8.1

# Bawah
route add -net 10.46.24.96 netmask 255.255.255.248 gw 10.46.24.126
route add -net 10.46.24.124 netmask 255.255.255.252 gw 10.46.24.126
```

- Fern
```sh
route add -net 0.0.0.0 netmask 0.0.0.0 gw 10.46.24.121
route add -net 10.46.0.0 netmask 255.255.248.0 gw 10.46.0.1
```

- Himmel
```sh
route add -net 10.46.24.96 netmask 255.255.255.248 gw 10.46.24.97
```

- Eisen
```sh
# Kiri
route add -net 10.46.24.104 netmask 255.255.255.248 gw 10.46.24.105

# Bawah
route add -net 10.46.24.140 netmask 255.255.255.252 gw 10.46.24.142
route add -net 10.46.24.144 netmask 255.255.255.252 gw 10.46.24.142
route add -net 10.46.20.0 netmask 255.255.254.0 gw 10.46.24.142
route add -net 10.46.24.0 netmask 255.255.255.192 gw 10.46.24.142
route add -net 10.46.16.0 netmask 255.255.252.0 gw 10.46.24.142

# Kanan
route add -net 10.46.24.136 netmask 255.255.255.252 gw 10.46.24.138
route add -net 10.46.12.0 netmask 255.255.252.0 gw 10.46.24.138
route add -net 10.46.22.0 netmask 255.255.255.0 gw 10.46.24.138

# Kanan Atas
route add -net 10.46.24.132 netmask 255.255.255.252 gw 10.46.24.133
```

- Linie
```sh
# Kiri
route add -net 10.46.24.144 netmask 255.255.255.252 gw 10.46.24.146
route add -net 10.46.24.0 netmask 255.255.255.192 gw 10.46.24.146
route add -net 10.46.16.0 netmask 255.255.252.0 gw 10.46.24.146

# bawah
route add -net 10.46.20.0 netmask 255.255.254.0 gw 10.46.20.1
```

- Lawine
```sh
route add -net 10.46.24.0 netmask 255.255.255.192 gw 10.46.24.1
route add -net 10.46.16.0 netmask 255.255.252.0 gw 10.46.24.3
```

- Heiter
```sh
route add -net 10.46.16.0 netmask 255.255.252.0 gw 10.46.16.1
```

- Lugner
```sh
route add -net 10.46.12.0 netmask 255.255.252.0 gw 10.46.12.1
route add -net 10.46.22.0 netmask 255.255.255.0 gw 10.46.22.1
```

## Testing


# CIDR

## Topologi PKT CIDR

![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/0e36c3bb-cd4f-46f4-a145-bdf4bf52bd20)

## Penggabungan IP

### Kondisi Awal Node

Berikut merupakan kondisi awal untuk pembagian subnet.

![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/adb1ddb5-06b4-4d7a-a4d2-db0baf66065f)

![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/570e8c0f-f6b2-4446-a85d-0a066a818287)

### Penggabungan I
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/22aa0878-2aec-4967-8221-63b450b0459d)


### Penggabungan II
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/e7088afa-3ab9-4dc6-b859-a064fa6699df)


### Penggabungan III
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/aac2fad9-1217-4bcf-9359-584d3826f312)


### Penggabungan IV
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/07679d3c-7dc7-437e-a194-f3078065e1de)


### Penggabungan V
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/b4e07ecd-5335-4ad1-9e1a-d8f49cc6da01)


### Penggabungan VI
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/e3534cbf-9cc6-42e0-af3c-537730213035)


### Penggabungan VII
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/18d7116f-eeef-4692-b78a-21c1920d2d90)


### Penggabungan VIII
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/7a1c82d5-6a5c-4d48-aea8-8eb481e831b6)


### Penggabungan IX
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/00e85845-16db-48fb-aca7-6f903382c2f6)


### Penggabungan X
![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/029812b6-afd1-4fd1-a248-88ae15f7cb0f)

## Pembagian IP

### Tree

Berdasarkan hasil penggabungan tersebut, sekarang dapat dilakukan perhitungan IP untuk setiap subnet dengan membuat tree.

![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/fe67a729-bfba-41d7-8fe1-4dfe6b92b255)

### Hasil Pembagian IP

Didapatkan hasil Perhitungan untuk pembagian IP tiap Subnet.

![image](https://github.com/VanGarman21/Jarkom-Modul-4-E19-2023/assets/70834506/24e9ddcf-3595-41db-9125-055a04e12672)





