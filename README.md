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
