# Mérési Feladat Jegyzőkönyv

**A különböző típusú antennák teljesítménye és a vételi jelminőség összehasonlítása.**

Ez a mérési feladat lehetővé teszi a hallgatók számára, hogy megismerjék és összehasonlítsák három különböző antenna teljesítményét ugyanazon jel sugárzásával. A feladat célja, hogy megvizsgálják, hogyan befolyásolja az antenna típusa a jelminőséget és a nyereséget különböző környezetekben.

---

## Cél
A hallgatók ismerjék meg a különböző antennák jellemzőit, és mérjék a sugárzott DVB-T jel minőségét a Johansson 8202 DVB-T modulátorral. Az ISKRA P2845, ISKRA P20 LOGPER és IKUSI FLASHD C48 antennákat használva a jelminőség és jelszint értékek változását vizsgálják különböző körülmények között.

---

- **Mérés helye**: V3 labor
- **Mérés időpontja**: 2024.11.13
- **Felelős személy**: Szatmári András

---

## Eszközök
- **Johansson 8202 DVB-T modulátor**
- **ISKRA P20 LOGPER antenna** (vételre)
- **ISKRA P2845 antenna** (vételre)
- **IKUSI FLASHD C48 antenna** (vételre)
- **Philips SDV5228** (adó oldalra)
- **RF kábelek**
- **DVB-T vevő** (pl. TV vagy mérőműszer)
- **METEK HD spektrum/jelszint analizátor**
- **Laptop a jegyzőkönyv készítéséhez**

---

## Feladatok

### 1. Johansson 8202 DVB-T modulátor beállítása
- **RF frekvencia:** Szabad sáv, amibe nem zavar bele az adás.
- **Moduláció:** 16-QAM
- **Sávszélesség:** 8 MHz
- **Jelszint:** -10 dBm
- **Antenna magasságai**: 1,4méter
- A modulátor beállításai állandóak maradnak az egész mérés során, csak az antenna típusát változtatják a vételi oldalon.
- Az adóoldalon egy körsugárzó antenna (Philips SDV5228) segítségével szórjuk a DVB-T jelet.

### 2. Jelátvitel és mérés az ISKRA P20 LOGPER antennával
- Csatlakoztassák az ISKRA P20 LOGPER antennát a DVB-T vevőhöz.
- Mérjék meg a következő paramétereket:
  - Jelszint (dBm)
  - Modulation Error Ratio (MER)
  - Bitsebesség (Mbps)
- Rögzítsék az eredményeket.

### 3. Jelátvitel és mérés az ISKRA P2845 antennával
- Csatlakoztassák az ISKRA P2845 antennát a DVB-T vevőhöz.
- Mérjék meg a jelszintet, a MER-t és a bitsebességet.
- Rögzítsék az eredményeket.

### 4. Jelátvitel és mérés az IKUSI FLASHD C48 antennával
- Csatlakoztassák az IKUSI FLASHD C48 antennát a DVB-T vevőhöz.
- Mérjék meg a jelszintet, a MER-t és a bitsebességet.
- Rögzítsék az eredményeket.

### 5. Mérés ismétlése egy másik szabad frekvencián
- Ismételjék meg a méréseket mindegyik antennatípussal egy másik szabad csatornán.
- Az új frekvencia térjen el legalább 80-100 MHz-től az előző mérésekhez képest.

### 6. Jegyzőkönyv készítése
- Készítsenek jegyzőkönyvet a mérési eredmények alapján, amely tartalmazza a következő paramétereket minden antennára vonatkozóan:
  - Antenna típusa
  - RF frekvencia (MHz)
  - Jelszint (dBm)
  - MER érték (dB)
  - Bitsebesség (Mbps)

### 7. Kiértékelés
- Elemezzék, melyik antenna biztosította a legjobb jelminőséget és jelszintet.
- Ismertessék, hogy milyen tényezők befolyásolhatják a különböző antennák teljesítményét (pl. antenna típus, nyereség, iránykarakterisztika).

---

## Mért Adatok - 490 MHz frekvencián

| **Antenna típusa**       | **Jelszint (dBm)**  | **Bitsebesség (Mbps)** | **MER érték (dB)**  |
|--------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER         |      -56,5dBm       |        9,2mB/s         |      27,3dB        |
| ISKRA P2845              |      -56,4dBm       |        9,5mB/s         |      27,7dB        |
| IKUSI FLASHD C48         |      -59,2dB        |        8,7mB/s         |      26,5dB        |

---

## Mért Adatok - 610 MHz frekvencián

| **Antenna típusa**       | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER érték (dB)** |
|--------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER         |                     |                        |                    |
| ISKRA P2845              |                     |                        |                    |
| IKUSI FLASHD C48         |                     |                        |                    |

--- 

## Mért képek:
<details>
  <summary>490 MHz-es Diagramm</summary>
A három antenna teljesítményének összehasonlítására a 490 MHz-es frekvencián. Az oszlopok a jelszintet (dBm) mutatják, míg a pontokkal összekötött vonalak a MER értéket (dB) és a bitsebességet (Mbps) szemléltetik. A különböző színek és vonalstílusok megkönnyítik az adatok átlátását.
  
![3631d983-5604-44ef-b7c4-bf85c53a5553](https://github.com/user-attachments/assets/4661331f-361e-49c6-b8c2-8acec3644071)
![image](https://github.com/user-attachments/assets/2e638800-cfaa-49b4-9b94-9d3c6e5ef4ae)

</details>0

<details>
    <summary>Iskra P20 LOGPER:</summary>
  1. kép: 490 MHz
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/its_snapshot_0005.bmp"/>
    
</details>

<br>

<details>
    <summary>ISKRA P2845:</summary>
2.kép: 490MHz
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/refs/heads/main/JEGYZOKONYV/03.%20Antenna%20teljes%C3%ADtm%C3%A9ny%20vs.%20jelszint/its_snapshot_0002.bmp"/>
    
</details>

<br>

<details>
    <summary>IKUSI FLASHD C48 :</summary>
   3. kép: 490MHz
    <img src="https://github.com/1SzatmariAndras6/TAVKOZLES2/blob/main/JEGYZOKONYV/03.%20Antenna%20teljes%C3%ADtm%C3%A9ny%20vs.%20jelszint/its_snapshot_0003.bmp"/>
    
</details>

<br>
    
  
---

## Összegzés
A mérések alapján összehasonlíthatjuk az egyes antennák teljesítményét különböző frekvenciákon, és értékelhetjük, hogy melyik antenna biztosította a legjobb jelminőséget és jelszintet. Ezen kívül elemezhetjük a mérési környezet hatását és a különböző antennák teljesítményét befolyásoló tényezőket.

---

## Következtetések
Itt rögzíthetjük a következtetéseket, amelyek segíthetnek az antenna kiválasztásában és alkalmazásában különböző környezetekben és körülmények között.

