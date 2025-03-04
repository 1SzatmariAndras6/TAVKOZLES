#  Műholdas vételi rendszer telepítése, konfigurálása és mérése 

## Szükséges eszközök:

- **Parabolaantenna:** D80 Mesh hálós acél parabola antenna (tripodra szerelve)
- **Műholdvevő fej (LNB):** A vizsgázó maga választja ki az elérhető Inverto ULTRA vagy Ekselans SATCR LNB-k közül
- **Set-top box:** Amiko HD 8265+
- **Mérőműszer:** METEK HDD műholdas jelmérő
- **Koaxiális kábelek és csatlakozók (már előkészítve egy másik vizsgafeladat során)**
- **Jelosztó:** 2-es műholdas jelosztó a mérési pontok kialakításához
- **Szerelési eszközök:** csavarhúzó, villáskulcs, iránytű, dőlésszögmérő

## Antenna beállítása és műhold azonosítása:

- Műhold: 9.0°E		Wide	51	11958 V	DVB-S2	HD **Eutelsat 9B**
- fok : 192.05° & 35.32°
  
- 10714 HSR 22000FEC 2/3Modulation DVB-S2 8PSKSatellite Astra 1MBeam Europe Ku-band beamNID 1
  
<details>
  
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/M%C5%B1holdas%20v%C3%A9teli%20rendszer/K%C3%A9perny%C5%91k%C3%A9p%202025-03-03%20123425.png" height="500" width="800">
<br>
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/M%C5%B1holdas%20v%C3%A9teli%20rendszer/1741075035422.jpg" height="500" width="800">

</details>

## Mérések és dokumentációk:
   1.Mérések és dokumentáció – Set-Top Box:

- **Jelszintek és jelminőség:** 80.2dB, SNR:99% AGC:97%
- **Transzponder adatok ellenőrzése:**
  Transzponderek száma
Az egyes műholdak transzponderkapacitása:

Astra 2E → 60 Ku-sávos + 4 Ka-sávos transzponder
Astra 2F → 48 Ku-sávos + 6 Ka-sávos transzponder
Astra 2G → 62 Ku-sávos + 4 Ka-sávos transzponder

Összesen tehát akár 170+ transzponder is lehet aktív a 28,2°E pozícióban, de a ténylegesen használt transzponderek száma változhat az üzemeltetési igények és a műholdkapacitás alapján.

- **Kimenő feszültség az LNB-re:**  13V
- **Polarizáció:** függőleges

<details>

<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/M%C5%B1holdas%20v%C3%A9teli%20rendszer/its_snapshot_0008.bmp">
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/M%C5%B1holdas%20v%C3%A9teli%20rendszer/its_snapshot_0007.bmp">

</details>

Jelszintmérés és dokumentáció

  1.Mérési eredmények rögzítése a jegyzőkönyvben:

- **Jelerősség:** (88.0dBμV)  
- **Jel-zaj viszony (SNR):** (6.5dB)  
- **Bit Error Rate (BER)**  7.07
- **Modulation Error Ratio (MER):** (13.3dB)  
- **Csillapítás:** (dB)  
- **Lock állapot:** Nem/igen
- **Hőmérséklet és időjárási körülmények**  2 °C, Napos
- **Transzponder adatok és frekvenciák:** 1MHz

<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/M%C5%B1holdas%20v%C3%A9teli%20rendszer/its_snapshot_0009.bmp">
  
## 2.Set-top box beállítása és csatornakeresés

   Mérések és dokumentáció – Set-Top Box:


- **Jelszintek és jelminőség:** L89% Q87%
- **Transzponder adatok ellenőrzése:** 
- **Kimenő feszültség az LNB-re:** 13V 
- **Polarizáció:** függőleges


## 2.Jelszintmérés és dokumentáció

   Mérési eredmények rögzítése a jegyzőkönyvben:

- **Jelerősség:** (74.9dBμV)  
- **Jel-zaj viszony (SNR):** (5.2dB)  
- **Bit Error Rate (BER)**  2,73
- **Modulation Error Ratio (MER):** (12dB)  
- **Csillapítás:** (dB)  
- **Lock állapot:** Nem/igen
- **Hőmérséklet és időjárási körülmények**  8 °C, Napos
- **Transzponder adatok és frekvenciák:** 1358MHz


<details>
  
**Spektrum analizátor képe:** 
  
  <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/M%C5%B1holdas%20v%C3%A9teli%20rendszer/its_snapshot_0001.bmp">
  
  <br>
  
   <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/M%C5%B1holdas%20v%C3%A9teli%20rendszer/its_snapshot_0002.bmp">
   
</details>
