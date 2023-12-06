# Jarkom-Modul-4-F12-2023

| Nama | NRP |
| ----------- | ----------- |
| Aurelio Killian Lexi Verrill | 5025211126 |
| Rano Noumi Sulistyo | 5025211185 | 

## Daftar Isi

- [Topologi](#topologi)
- [VLSM](#vlsm)
- [CIDR](#cidr)

## Topologi

<p align="center">
  <img src="https://github.com/aurelioklv/Jarkom-Modul-4-F12-2023/assets/87407047/3a7fb85a-3719-4e22-ab73-e7275c4e3f0b" alt='Topologi' />
</p>

## Rute

| Nama Subnet | Rute                                            | Jumlah IP | Netmask |
| ----------- | ----------------------------------------------- | --------- | ------- |
| A1          | Aura-Frieren                                    | 2         | /30     |
| A2          | Frieren-Switch3-LakeKorridor                    | 25        | /27     |
| A3          | Frieren-Flamme                                  | 2         | /30     |
| A4          | Flamme-Fern                                     | 2         | /30     |
| A5          | Fern-Switch4-AppetitRegion-Switch4-LaubHills    | 1023      | /21     |
| A6          | Flamme-Switch5-RohrRoad                         | 1001      | /22     |
| A7          | Flamme-Himmel                                   | 2         | /30     |
| A8          | Himmel-Switch6-SchwerMountains                  | 6         | /29     |
| A9          | Aura-Denken                                     | 2         | /30     |
| A10         | Denken-Switch2-RoyalCapital-Switch2-WilleRegion | 127       | /24     |
| A11         | Aura-Eisen                                      | 2         | /30     |
| A12         | Eisen-Switch1-Richter-Switch1-Revolte           | 3         | /29     |
| A13         | Eisen-Switch0-Stark                             | 2         | /30     |
| A14         | Eisen-Lugner                                    | 2         | /30     |
| A15         | Lugner-Switch10-TurkRegion                      | 1001      | /22     |
| A16         | Lugner-Switch9-GrobeForest                      | 251       | /24     |
| A17         | Eisen-Linie                                     | 2         | /30     |
| A18         | Linie-Switch11-GranzChannel                     | 255       | /23     |
| A19         | Linie-Lawine                                    | 2         | /30     |
| A20         | Lawine-Switch7-BredtRegion-Switch7-Heiter       | 31        | /26     |
| A21         | Heiter-Switch8-Sein-Switch8-RiegelCanyon        | 512       | /22     |
| Total       | -                                               | 4255      | /19     |

## VLSM

### Pembagian IP

| Subnet | Network ID     | Netmask         | Broadcast      | Rute                                            | Jumlah IP | Netmask |
| ------ | -------------- | --------------- | -------------- | ----------------------------------------------- | --------- | ------- |
| A1     | 192.227.24.112 | 255.255.255.252 | 192.227.24.115 | Aura-Frieren                                    | 2         | /30     |
| A2     | 192.227.24.64  | 255.255.255.224 | 192.227.24.95  | Frieren-Switch3-LakeKorridor                    | 25        | /27     |
| A3     | 192.227.24.116 | 255.255.255.252 | 192.227.24.119 | Frieren-Flamme                                  | 2         | /30     |
| A4     | 192.227.24.120 | 255.255.255.252 | 192.227.24.123 | Flamme-Fern                                     | 2         | /30     |
| A5     | 192.227.0.0    | 255.255.248.0   | 192.227.7.255  | Fern-Switch4-AppetitRegion-Switch4-LaubHills    | 1023      | /21     |
| A6     | 192.227.8.0    | 255.255.252.0   | 192.227.11.255 | Flamme-Switch5-RohrRoad                         | 1001      | /22     |
| A7     | 192.227.24.124 | 255.255.255.252 | 192.227.24.127 | Flamme-Himmel                                   | 2         | /30     |
| A8     | 192.227.24.96  | 255.255.255.248 | 192.227.24.103 | Himmel-Switch6-SchwerMountains                  | 6         | /29     |
| A9     | 192.227.24.128 | 255.255.255.252 | 192.227.24.131 | Aura-Denken                                     | 2         | /30     |
| A10    | 192.227.22.0   | 255.255.255.0   | 192.227.22.255 | Denken-Switch2-RoyalCapital-Switch2-WilleRegion | 127       | /24     |
| A11    | 192.227.24.132 | 255.255.255.252 | 192.227.24.135 | Aura-Eisen                                      | 2         | /30     |
| A12    | 192.227.24.104 | 255.255.255.248 | 192.227.24.111 | Eisen-Switch1-Richter-Switch1-Revolte           | 3         | /29     |
| A13    | 192.227.24.136 | 255.255.255.252 | 192.227.24.139 | Eisen-Switch0-Stark                             | 2         | /30     |
| A14    | 192.227.24.140 | 255.255.255.252 | 192.227.24.143 | Eisen-Lugner                                    | 2         | /30     |
| A15    | 192.227.12.0   | 255.255.252.0   | 192.227.15.255 | Lugner-Switch10-TurkRegion                      | 1001      | /22     |
| A16    | 192.227.23.0   | 255.255.255.0   | 192.227.23.255 | Lugner-Switch9-GrobeForest                      | 251       | /24     |
| A17    | 192.227.24.144 | 255.255.255.252 | 192.227.24.147 | Eisen-Linie                                     | 2         | /30     |
| A18    | 192.227.20.0   | 255.255.254.0   | 192.227.21.255 | Linie-Switch11-GranzChannel                     | 255       | /23     |
| A19    | 192.227.24.148 | 255.255.255.252 | 192.227.24.151 | Linie-Lawine                                    | 2         | /30     |
| A20    | 192.227.24.0   | 255.255.255.192 | 192.227.24.63  | Lawine-Switch7-BredtRegion-Switch7-Heiter       | 31        | /26     |
| A21    | 192.227.16.0   | 255.255.252.0   | 192.227.19.255 | Heiter-Switch8-Sein-Switch8-RiegelCanyon        | 512       | /22     |

### Tree

<p align="center">
  <img src="https://github.com/aurelioklv/Jarkom-Modul-4-F12-2023/assets/87407047/222c9410-2e2c-4776-a96e-b2a160c0d1f9" alt='VLSM Tree' />
</p>

## CIDR
### Penggabungan
![image](https://github.com/aurelioklv/Jarkom-Modul-4-F12-2023/assets/114126015/3d612c4f-049c-4746-85ef-c7a6710a80d1)
![image](https://github.com/aurelioklv/Jarkom-Modul-4-F12-2023/assets/114126015/3141c4f7-067e-4af6-a32f-cb983358b9d1)
### Tree 
![image](https://github.com/aurelioklv/Jarkom-Modul-4-F12-2023/assets/114126015/34ec724b-29a7-4deb-9632-d50042a919e3)
### Pembagian IP gns3
![image](https://github.com/aurelioklv/Jarkom-Modul-4-F12-2023/assets/114126015/b31d7984-be2c-4b33-ba79-2ea1aa9944b7)

Aura 
```

auto eth0
iface eth0 inet dhcp

#A9
auto eth1
iface eth1 inet static
address 192.225.1.1
netmask 255.255.255.252
#A1
auto eth2
iface eth2 inet static
address 192.226.128.1
netmask 255.255.255.252

#A11
auto eth3
iface eth3 inet static
address 192.224.32.1
netmask 255.255.255.252
```
Frieren
```
#A1
auto eth0
iface eth0 inet static
address 192.226.128.2
netmask 255.255.255.252
gateway 192.226.128.1
#A3
auto eth1
iface eth1 inet static
address 192.226.32.1
netmask 255.255.255.252

#A2
auto eth2
iface eth2 inet static
address 192.226.64.1
netmask 255.255.255.224
```
LakeKorridor
```
#A2
auto eth0
iface eth0 inet static
address 192.226.64.2
netmask 255.255.255.224
gateway 192.226.64.1
```
Flamme
```

#A3
auto eth0
iface eth0 inet static
address 192.226.32.2
netmask 255.255.255.252
gateway 192.226.32.1

#A4
auto eth1
iface eth1 inet static
	address 192.226.8.1
	netmask 255.255.255.252

#A6
auto eth2
iface eth2 inet static
	address 192.226.16.1
	netmask 255.255.252.0

#a7
auto eth3
iface eth3 inet static
	address 192.226.20.9
	netmask 255.255.255.252
```
Fern
```
#A4
auto eth0
iface eth0 inet static
	address 192.226.8.2
	netmask 255.255.255.0
	gateway 192.226.8.1

#A5
auto eth1
iface eth1 inet static
	address 192.226.0.1
	netmask 255.255.248.0
```
LaubHills
```

#A5
auto eth0
iface eth0 inet static
	address 192.226.0.2
	netmask 255.255.248.0
	gateway 192.226.0.1
```
AppetitRegion
```
#A5
auto eth0
iface eth0 inet static
	address 192.226.0.3
	netmask 255.255.248.0
	gateway 192.226.0.1
```
RohrRoad
```
#A6
auto eth0
iface eth0 inet static
	address 192.226.16.2
	netmask 255.255.252.0
	gateway 192.226.16.1
```
Himmel
```

#A7
auto eth0
iface eth0 inet static
	address 192.226.20.10
	netmask 255.255.255.252
	gateway 192.226.20.9


#A8
auto eth1
iface eth1 inet static
	address 192.226.20.1
	netmask 255.255.255.248
```
SchwerMountains
```
#A8
auto eth0
iface eth0 inet static
	address 192.226.20.2
	netmask 255.255.255.248
	gateway 192.226.20.1
```
Denken
```

#A9
auto eth0
iface eth0 inet static
	address 192.225.1.2
	netmask 255.255.255.252
	gateway 192.225.1.1


#a10
auto eth1
iface eth1 inet static
	address 192.225.0.1
	netmask 255.255.255.0
```
RoyalCapital
```

#a10
auto eth0
iface eth0 inet static
	address 192.225.0.2
	netmask 255.255.255.0
gateway 192.225.0.1
```
WilleRegion
```
#a10
auto eth0
iface eth0 inet static
	address 192.225.0.3
	netmask 255.255.255.0
gateway 192.225.0.1
```
Eisen
```

#A11
auto eth0
iface eth0 inet static
address 192.224.32.2
netmask 255.255.255.252
gateway 192.224.32.1
#A13
auto eth1
iface eth1 inet static
address 192.224.16.1
netmask 255.255.255.252

#A14
auto eth2
iface eth2 inet static
address 192.224.8.1
netmask 255.255.255.252

#A12
auto eth3
iface eth3 inet static
address 192.224.64.1
netmask 255.255.255.248

#A17
auto eth4
iface eth4 inet static
address 192.224.160.1
netmask 255.255.255.252
```
Richter
```
#A12
auto eth0
iface eth0 inet static
address 192.224.64.2
netmask 255.255.255.248
gateway 192.224.64.1

```
Revolte
```
#A12
auto eth0
iface eth0 inet static
address 192.224.64.3
netmask 255.255.255.248
gateway 192.224.64.1
```
Stark
```
#A13
auto eth0
iface eth0 inet static
address 192.224.16.2
netmask 255.255.255.252
gateway 192.224.16.1
```
Lugner
```

#A14
auto eth0
iface eth0 inet static
address 192.224.8.2
netmask 255.255.255.252
gateway 192.224.8.1


#A15
auto eth1
iface eth1 inet static
address 192.224.0.1
netmask 255.255.252.0

#A16
auto eth2
iface eth2 inet static
address 192.224.4.1
netmask 255.255.255.0
```
TurkRegion
```
#A15
auto eth0
iface eth0 inet static
address 192.224.0.2
netmask 255.255.252.0
gateway 192.224.0.1
```
GrobeForest
```
#A16
auto eth0
iface eth0 inet static
address 192.224.4.2
netmask 255.255.252.0
gateway 192.224.4.1
```
Linie
```

#A17
auto eth0
iface eth0 inet static
address 192.224.160.2
netmask 255.255.255.252
gateway 192.224.160.1
#A18
auto eth1
iface eth1 inet static
address 192.224.144.1
netmask 255.255.254.0

#A19
auto eth2
iface eth2 inet static
address  192.224.136.1
netmask 255.255.255.252
```
GranzChannel
```
#A18
auto eth0
iface eth0 inet static
address 192.224.144.2
netmask 255.255.254.0
gateway 192.224.144.1
```
Lawine
```

#A19
auto eth0
iface eth0 inet static
address  192.224.136.2
netmask 255.255.255.252
gateway  192.224.136.1

#A20
auto eth1
iface eth1 inet static
address 192.224.132.1
netmask 255.255.255.192
```
BredtRegion
```
#A20
auto eth0
iface eth0 inet static
address 192.224.132.2
netmask 255.255.255.192
gateway 192.224.132.1
```
Heiter
```
#A20
auto eth0
iface eth0 inet static
address 192.224.132.3
netmask 255.255.255.192
gateway 192.224.132.1

#A21
auto eth1
iface eth1 inet static
address 192.224.128.1
netmask 255.255.255.0
```
Sein
```
#A21
auto eth0
iface eth0 inet static
address 192.224.128.2
netmask 255.255.255.0
gateway 192.224.128.1
```
RiegelCanyon
```
#A21
auto eth0
iface eth0 inet static
address 192.224.128.3
netmask 255.255.255.0
gateway 192.224.128.1
```
### Routing

Aura
```
#denken
route add -net 192.225.0.0 netmask 255.255.255.0 gw 192.225.1.2
#eisen
route add -net 192.224.64.0 netmask 255.255.255.248 gw 192.224.32.2
route add -net 192.224.16.0 netmask 255.255.255.252 gw 192.224.32.2
route add -net 192.224.8.0 netmask 255.255.255.252 gw 192.224.32.2
route add -net 192.224.4.0 netmask 255.255.255.0 gw 192.224.32.2
route add -net 192.224.0.0 netmask 255.255.252.0 gw 192.224.32.2
route add -net 192.224.160.0 netmask 255.255.255.252 gw 192.224.32.2
route add -net 192.224.144.0 netmask 255.255.254.0 gw 192.224.32.2
route add -net  192.224.136.0 netmask 255.255.255.252 gw 192.224.32.2
route add -net 192.224.132.0 netmask 255.255.255.192 gw 192.224.32.2
route add -net 192.224.128.0 netmask 255.255.252.0 gw 192.224.32.2

#freiren
route add -net 192.226.64.0 netmask 255.255.255.224 gw 192.226.128.2
route add -net 192.226.32.0 netmask 255.255.255.252 gw 192.226.128.2
route add -net 192.226.8.0 netmask 255.255.255.252 gw 192.226.128.2
route add -net 192.226.0.0 netmask 255.255.248.0 gw 192.226.128.2
route add -net 192.226.16.0 netmask 255.255.252.0 gw 192.226.128.2
route add -net 192.226.20.8 netmask 255.255.255.252 gw 192.226.128.2
route add -net 192.226.20.0 netmask 255.255.255.248 gw 192.226.128.2
```
Freiren
```
route add -net 192.226.8.0 netmask 255.255.255.252 gw 192.226.32.2
route add -net 192.226.0.0 netmask 255.255.248.0 gw 192.226.32.2
route add -net 192.226.16.0 netmask 255.255.252.0 gw 192.226.32.2
route add -net 192.226.20.8 netmask 255.255.255.252 gw 192.226.32.2
route add -net 192.226.20.0 netmask 255.255.255.248 gw 192.226.32.2
```
Flamme
```
route add -net 192.226.0.0 netmask 255.255.248.0 gw 192.226.8.2
route add -net 192.226.20.0 netmask 255.255.255.248 gw 192.226.20.10
```
Fern
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.226.8.1
```
Himmel
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.226.20.9
```
Denken
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.225.1.1
```
Eisen
```
#lugner
route add -net 192.224.0.0 netmask 255.255.252.0 gw 192.224.8.2
route add -net 192.224.4.0 netmask 255.255.255.0 gw 192.224.8.2
#linie
route add -net 192.224.144.0 netmask 255.255.254.0 gw 192.224.160.2
route add -net  192.224.136.0 netmask 255.255.255.252 gw 192.224.160.2
route add -net 192.224.132.0 netmask 255.255.255.192 gw 192.224.160.2
route add -net 192.224.128.0 netmask 255.255.252.0 gw 192.224.160.2
```
Lugner
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.224.8.1
```
Linie
```
route add -net 192.224.132.0 netmask 255.255.255.192 gw 192.224.136.2
route add -net 192.224.128.0 netmask 255.255.252.0 gw 192.224.136.2
```
Lawine
```
route add -net 192.224.128.0 netmask 255.255.252.0 gw 192.224.132.3
```
Heiter
```
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.224.132.1
```
