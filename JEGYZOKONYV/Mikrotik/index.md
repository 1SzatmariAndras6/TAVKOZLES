# MÉRÉSI JEGYZŐKÖNYV – Hálózat tervezés

**Mérést végezte:** Snellenperger Sándor  
**Felügyelő:** Sándor Péter  
**Dátum:** 2025.01.29.  
**Helyszín:** V3 Labor  
**Csoport:** 13.E / GYAK 1  

## Cél
Komplex távközlési hálózat tervezése, telepítése és tesztelése.

## Eszközök
- Mikrotik LHG18 LTE antenna  
- 2 db Mikrotik nRay 60GHz antenna  
- 1 db SOHO router (D-LINK / TP-LINK / ASUS)  
- Hálózati topológia tervezése és kiépítése  

## IP-cím kiosztás
- **Mikrotik LHG18 LTE:** 192.168.88.1  
- **Mikrotik nRay 60GHz Master:** 192.168.88.2  
- **Mikrotik nRay 60GHz Slave:** 192.168.88.3  
- **Router (AP mód):** 192.168.88.4  
- **Switch (ha szükséges):** 192.168.88.254  
- **Kliens laptop:** 192.168.88.100-250 (DHCP)  

## Konfiguráció
- **Mikrotik LHG18 LTE** DHCP szerverként működik (192.168.88.100-250).  
- **SOHO router** WiFi beállítás: SSID: GazdaXX, Jelszó: G1234567, AP mód.  

## Hálózati tesztelés és hibakeresés
- Windows hálózati felderítés szükséges, ha a teszt nem indul.  
- **Mikrohullámú kapcsolat** beállítása és optimalizálása.  
- **Google ping teszt** sikeres, nincs csomagvesztés.  
- **Speedtest eredmények:** Ping, letöltési és feltöltési sebesség mérése.  
- **Sávszélesség teszt** iperf segítségével.  
- **Hibakeresés:** Kezdeti 100 Mb/s kapcsolat megoldása, 1000 Mb/s elérése.  

## Ping tesztek
```
Pinging 192.168.88.1 with 32 bytes of data:
Reply from 192.168.88.1: bytes=32 time<1ms TTL=64
Reply from 192.168.88.1: bytes=32 time<1ms TTL=64
Reply from 192.168.88.1: bytes=32 time<1ms TTL=64

Packets: Sent = 3, Received = 3, Lost = 0 (0% loss)
Minimum = 0ms, Maximum = 0ms, Average = 0ms
```
