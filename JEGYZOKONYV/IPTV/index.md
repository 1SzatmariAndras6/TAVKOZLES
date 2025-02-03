# DVB-T jel fejállomásba küldése és IPTV rendszeren való kiadása

**A mérést végző neve:** György Péter

**A mérés tárgya és mérés száma:** IPTV

**A mérés dátuma:** 2025.02.23

**A mérést vezette:** Sándor Péter

**Évfolyam:** 13. E
**Csoport:** GYAK 2
**Helyszín:** V3 labor


## 1. Mérés célja

A mérés célja, hogy biztosítsa a megfelelő jelerősséget és jelminőséget a digitális TV vételi rendszerhez, ellenőrizze a DVB-T jel stabilitását és minőségét, valamint biztosítsa, hogy az IPTV stream zökkenőmentesen működjön a végfelhasználók számára.

## 2. Mérőeszközök és készülékek

| Eszköz típusa       | Eszköz neve                                         | Leírás                                  |
|---------------------|-----------------------------------------------------|-----------------------------------------|
| **Antenna**          | ISKRA P-2845F UHF                                   | Beltéri vagy kültéri antenna            |
| **Fejállomás**       | LEMCO SCL-824CT (FTA)                               | Fejállomás a DVB-T jel fogadására és IPTV stream előállítására |
| **Set-top box**      | MAG IPTV                                            | IPTV vevőegység                         |
| **Hálózati eszköz**  | IGMP protokollt támogató és DHCP képes router       | Internet kapcsolat biztosítása         |
| **Mérőműszer**       | METEK HDD digitális TV jelmérő, koaxiális kábelek és csatlakozók | Jelméréshez szükséges műszer és kábelek |
| **Jelosztó**         | -                                                   | Jelosztó a fejállomás bemeneteire érkező jelekhez, UTP kábelek az IPTV jel továbbításához |
| **Szerelési eszközök** | Csavarhúzó, villáskulcs, kábelvágó, iránytű, dőlésszögmérő | Szerelési eszközök a telepítéshez |
| **Osztó**            | RF 16                                               | RF osztó a jel elosztására              |

## 3. Mérési helyszín és környezet:
- **Irányszög Dél-nyugat:** 234°*
- **Antenna magassága:** 1,5m*
- **Környezet jellemzői:**
  
- szoba környezet hőmérséklet: 5°
- UV: * gyenge 2*
- páratartalom: * 68%*
- légnyomás: * 1027mBar*
- **Adó távolsága:** 800m* 


 ## A feladat végrehajtási pontjai


4. **Adótorony kiválasztása**
   - Miskolci Avasi adótorony kiválasztása a megfelelő vételi terület lefedettségéhez.







5. **Jel mérés és elosztás**

   
   - A jel erősségének és minőségének mérése :
| Mérési paraméter      | Leírás            | Mért értékek               |
|-----------------------|-------------------|----------------------------|
| **Jelszint (dBm)**    |       51 db       |                            |
| **MER (dB)**          |       25 db       |                            |
| **C/N (dB)**          |                   |                            |
| **Frekvencia (MHz)**  |                   |                            |
| **QPSK**              |     84 / 1 / 32   |                            |
  
   
   
   - A jel stabilitásának biztosítása az IPTV rendszerhez.




5. **DVB-T jel bevezetése a fejállomásba**
   - A DVB-T jel átvitele a LEMCO SCL-824CT fejállomásba.
   - A fejállomás konfigurálása a digitális tartalom IPTV stream formájában történő kiadására.




6. **Multicast IP tartomány kiválasztása**
   - Az IPTV rendszerhez megfelelő Multicast IP tartomány beállítása.




7. **IPTV Set-top-box konfigurálása**
   - Az IPTV Set-top-boxok beállítása a megfelelő vételhez és stream fogadásához.







8. **Vételi terület lefedettségének értékelése**
   - A mérés alapján biztosítani, hogy az adótorony jele elérje a kívánt területet és stabil vételt biztosítson.




