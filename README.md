# Packet Tracer - LAN
## Popis sítě
- Switche obsahují základní nastavení a mají nastavenou IP adresu
- PC1 a PC2 jsou zapojeny do S1
- SRV1 a SRV2 jsou zapojeny do S2
- Na SRV1 běží DHCP server a DNS server, na S2 běží web server
- Všechny zařízení v síti mají kromě PC2 statickou IP adresu
- IP adresy jsou v sítí 192.168.29.0/24
## Výpočet X
| Písmeno | ASCII |
|---------|-------|
| P       | 80    |
| L       | 76    |
| E       | 69    |
| S       | 83    |
| T       | 84    |
| I       | 73    |
| L       | 76    |

80 + 76 + 69 + 83 + 84 + 73 + 76 = 541\
541 mod 256 = 29\
**X = 29**
## Snímky obrazovky
![S2 - Nastavování](./S2_config.png)
![PC1 - ipconfig](./PC1_ipconfig.png)
![PC1 - Ping na SRV2](./PC1_ping.png)
![SRV1 - Nastavení DHCP](./SRV1_DHCP.png)
![SRV1 - Nastavení DNS](./SRV1_DNS.png)
![SRV1 - Nastavení web serveru](./SRV2_HTTP.png)
## Licence
Repozitář je licencován pod MIT License