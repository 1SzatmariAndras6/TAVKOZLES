# DVB-T jel fejállomásba küldése és IPTV rendszeren való kiadása

**A mérést végző neve:** Szatmári András

**A mérés tárgya és mérés száma:** IPTV

**A mérés dátuma:** 2025.02.23

**A mérést vezette:** Sándor Péter

**Évfolyam:** 13. E
**Csoport:** GYAK 2
**Helyszín:** V3 labor


## 1. Mérés célja

A mérés célja, hogy biztosítsa a megfelelő jelerősséget és jelminőséget a digitális TV vételi rendszerhez, ellenőrizze a DVB-T jel stabilitását és minőségét, valamint biztosítsa, hogy az IPTV stream zökkenőmentesen működjön a végfelhasználók számára.

## 2. Mérőeszközök és készülékek

| Eszköz típusa       | Eszköz neve                                          | Leírás                                  |
|---------------------|------------------------------------------------------|-----------------------------------------|
| **Antenna**          | ISKRA P-2845F UHF                                   | Beltéri vagy kültéri antenna            |
| **Fejállomás**       | LEMCO SCL-824CT (FTA)                               | Fejállomás a DVB-T jel fogadására és IPTV stream előállítására |
| **Set-top box**      | MAG IPTV                                            | IPTV vevőegység                         |
| **Hálózati eszköz**  | IGMP protokollt támogató és DHCP képes router       | Internet kapcsolat biztosítása         |
| **Mérőműszer**       | METEK HDD digitális TV jelmérő, koaxiális kábelek és csatlakozók | Jelméréshez szükséges műszer és kábelek |
| **Jelosztó**         | Ekselans RF-16                                      | Jelosztó a fejállomás bemeneteire érkező jelekhez, UTP kábelek az IPTV jel továbbításához |
| **Szerelési eszközök**| Csavarhúzó, villáskulcs, kábelvágó, iránytű, dőlésszögmérő | Szerelési eszközök a telepítéshez |
| **tp-link**           |            archer c7 router                        |                                   |

## 3. Mérési helyszín és környezet:
- **Irányszög Dél-nyugat:** 234°
- **Antenna magassága:** 1,5m
- **Környezet jellemzői:**
  
- **szoba környezet hőmérséklet:** 5°
- **UV:** * gyenge 2
- **páratartalom:**  68%
- **légnyomás:**  1027mBar
- **Adó távolsága:** 779,88m


 ## A feladat végrehajtási pontjai:


4. **Adótorony kiválasztása**
   - Miskolci Avasi adótorony kiválasztása a megfelelő vételi terület lefedettségéhez.
     <br>
<details>
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IPTV/K%C3%A9perny%C5%91k%C3%A9p%202025-02-03%20115932.png">
</details>

**Táblázat:**
<details> 
  
| #  | Input   | Program Title           | OriginalService ID | LCN1..1023 | Encrypted | TS Output | OutputService ID | IP Address       | IP Port | Protocol |
|----|---------|-------------------------|--------------------|------------|-----------|-----------|------------------|------------------|---------|----------|
| 1  | Input 1 | M1 HD                   | 100                | 0          | FTA       | 1         | 100              | 239.1.1.1.1      | 10001   | UDP      |
| 2  | Input 1 | M4 Sport HD             | 101                | 0          | FTA       | 1         | 101              | 239.1.1.1.1      | 10002   | UDP      |
| 3  | Input 1 | Duna HD                 | 102                | 0          | FTA       | 1         | 102              | 239.1.1.1.1      | 10003   | UDP      |
| 4  | Input 1 | DunaW/M4Sport+          | 103                | 0          | FTA       | 2         | 103              | 239.1.1.1.1      | 10004   | UDP      |
| 5  | Input 1 | Kossuth Radio           | 130                | 0          | FTA       | 4         | 130              | 239.1.1.1.1      | 10005   | UDP      |
| 6  | Input 1 | Petofi Radio            | 131                | 0          | FTA       | 4         | 131              | 239.1.1.1.1      | 10006   | UDP      |
| 7  | Input 1 | Bartok Radio            | 132                | 0          | FTA       | 4         | 132              | 239.1.1.1.1      | 10007   | UDP      |
| 8  | Input 1 | Danko Radio             | 133                | 0          | FTA       | 4         | 133              | 239.1.1.1.1      | 10008   | UDP      |
| 10 | Input 2 | M2 HD                   | 200                | 0          | FTA       | 1         | 200              | 239.1.1.1.1      | 10009   | UDP      |
| 11 | Input 2 | M5 HD                   | 201                | 0          | FTA       | 2         | 201              | 239.1.1.1.1      | 10010   | UDP      |
| 12 | Input 2 | TV2                     | 202                | 0          | FTA       | 1         | 202              | 239.1.1.1.1      | 10011   | UDP      |
| 13 | Input 2 | RTL                     | 203                | 0          | FTA       | 1         | 203              | 239.1.1.1.1      | 10012   | UDP      |
| 14 | Input 2 | MAX4                    | 206                | 0          | FTA       | 2         | 206              | 239.1.1.1.1      | 10013   | UDP      |
| 15 | Input 2 | Spektrum Home +         | 207                | 0          | FTA       | 2         | 207              | 239.1.1.1.1      | 10014   | UDP      |
| 16 | Input 2 | MinDig TV Plusz Info    | 208                | 0          | FTA       | 2         | 208              | 239.1.1.1.1      | 10015   | UDP      |
| 37 | Input 3 | HEVC teszt              | 524                | 0          | FTA       | 2         | 524              | 239.1.1.1.1      | 10016   | UDP      |
| 39 | Input 4 | Miskolc TV              | 1000               | 0          | FTA       | 2         | 1000             | 239.1.1.1.1      | 10017   | UDP      |

</details>

5. **Jel mérés és elosztás**

   
   - A jel erősségének és minőségének mérése :
     
| Mérési paraméter      | Leírás            | Mért értékek               |
|-----------------------|-------------------|----------------------------|
| **Jelszint (dBm)**    |       51 db       |                            |
| **MER (dB)**          |       25 db       |                            |
| **Frekvencia (MHz)**  |       634         |                            |
| **QPSK**              |     84 / 1 / 32   |                            |
  
   
   
   - A jel stabilitásának biztosítása az IPTV rendszerhez.




5. **DVB-T jel bevezetése a fejállomásba**
   A DVB-T jel átvitele a LEMCO SCL-824CT fejállomásba:
   
     - Csatlakoztattuk a kontroll portjára itt lehet konfigurálni
     -Lemco Ip címe: 192.168.1.200
   
   - A fejállomás konfigurálása a digitális tartalom IPTV stream formájában történő kiadására.




5. **Multicast IP tartomány kiválasztása**
   - Az IPTV rendszerhez megfelelő Multicast IP tartomány beállítása.
  <details>
    
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IPTV/41-48ch.png">

<br>

<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IPTV/K%C3%A9perny%C5%91k%C3%A9p%202025-02-03%20123233.png">

  </details>

  **Input ípcímek :** 224.0.0.1
  
|Input 1        | Leírás            |     
|---------------|-------------------|
| **Tunner**    |   DVB-T/T2        |
| **Frequency** |    666            |  
|   **Channel** |    45             |  
|  **Bandwith** |   8MHz            |  


|Input 2        | Leírás            |
|---------------|-------------------|
| **Tunner**    |   DVB-T/T2        |
| **Frequency** |    586 MHz        |  
|   **Channel** |      35           |  
|  **Bandwith** |     8MHz          |  


|Input 3        | Leírás            |     
|---------------|-------------------|
| **Tunner**    |   DVB-T/T2        |
| **Frequency** |     690           |  
|   **Channel** |     48            |  
|  **Bandwith** |     8MHz          |  


|Input 4        | Leírás            |     
|---------------|-------------------|
| **Tunner**    |   DVB-T/T2        |
| **Frequency** |     634           |  
|   **Channel** |     41            |  
|  **Bandwith** |     8MHz          |  


**TS OUT 1:** 76%
**TS OUT 2:** 81%
**TS OUT 3:** 
**TS OUT 4:** 



6. **IPTV Set-top-box konfigurálása**
   - Az IPTV Set-top-boxok beállítása a megfelelő vételhez és stream fogadásához.

*Router config:*
- IGMP Snooping IPTV/VLAN version V2, bridge módba álítottuk
- Set-top-box LAN3 fogadja
- Ip address Pool : 192.168.1.100- 192.168.1.249
- default gateway: 192.168.1.1
Pendrivval átmásoljuk az IPTV-channeleket amit lementettünk M3U formában.


<details>
<img src="  ">
</details>

7. **Vételi terület lefedettségének értékelése**




