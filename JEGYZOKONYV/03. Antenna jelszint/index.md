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
- A modulátor beállításai állandóak maradnak az egész mérés során, csak az antenna típusát változtatjuk a vételi oldalon.
- Az adóoldalon egy körsugárzó antenna (Philips SDV5228) segítségével szórjuk a DVB-T jelet.

### 5. Mérés ismétlése egy másik szabad frekvencián

- Az új frekvencián lett a 730MHz
- 
### 6. Jegyzőkönyv készítése
- Készítsenek jegyzőkönyvet a mérési eredmények alapján, amely tartalmazza a következő paramétereket minden antennára vonatkozóan:
  - Antenna típusa
  - RF frekvencia (MHz)
  - Jelszint (dBm)
  - MER érték (dB)
  - Bitsebesség (Mbps)

### 7. Kiértékelés
#### Legjobb jelminőség:

- **490 MHz frekvencián:**  
  Az **ISKRA P2845** antenna teljesített a legjobban, mivel a legnagyobb MER értéket (27,7 dB) és bitsebességet (9,5 Mbps) biztosította.

- **730 MHz frekvencián:**  
  Az **ISKRA P2845** ismét kiemelkedett (MER: 27,5 dB, bitsebesség: 9,59 Mbps), azonban az **IKUSI FLASHD C48** magasabb bitsebességet ért el (9,81 Mbps), bár a jelszint és MER értékek gyengébbek voltak.

### Környezet és frekvencia hatása:

- A 730 MHz-es frekvencián minden antenna teljesítménye kissé romlott, különösen a MER értékek csökkentek, ami az emelkedő frekvenciával járó csillapításnak tudható be.

### Tényezők, amelyek befolyásolták a teljesítményt:

- **Antennák nyeresége:**  
  Az **ISKRA P2845** nagyobb nyereséget biztosított, különösen alacsonyabb frekvenciákon.

- **Iránykarakterisztika:**  
  Az irányítottabb antennák (pl. **ISKRA P20 LOGPER**) jobb MER-t biztosítottak bizonyos körülmények között, míg a szélesebb nyalábkarakterisztikájú antennák (**IKUSI FLASHD C48**) nagyobb bitsebességet értek el.


---

## Mért Adatok - 490 MHz frekvencián

| **Antenna típusa**       | **Jelszint (dBm)**  | **Bitsebesség (Mbps)** | **MER érték (dB)**  |
|--------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER         |      -56,5dBm       |        9,2mB/s         |      27,3dB        |
| ISKRA P2845              |      -56,4dBm       |        9,5mB/s         |      27,7dB        |
| IKUSI FLASHD C48         |      -59,2dBm        |        8,7mB/s         |      26,5dB        |

---

## Mért Adatok - 730 MHz frekvencián

| **Antenna típusa**       | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER érték (dB)** |
|--------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER         |   -60,3dBm          |       9,3Mb/s          |       23 dB        |
| ISKRA P2845              |   -59,5dBm          |       9,59Mb/s         |       27,5dB       |
| IKUSI FLASHD C48         |   -62,8dBm          |       9,81Mb/s         |       23,7dB       |

--- 

## Mért képek:
<details>
  <summary>490MHz és 730MHZ-es Diagrammok</summary>

<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/refs/heads/main/JEGYZOKONYV/03.%20Antenna%20jelszint/K%C3%A9perny%C5%91k%C3%A9p%202024-11-14%20135237.png"/>
<br>
*A három antenna teljesítményének összehasonlítására a 490 MHz-es frekvencián. Az oszlopok a jelszintet (dBm) mutatják, míg a pontokkal összekötött vonalak a MER értéket (dB) és a bitsebességet (Mbps) szemléltetik. A különböző színek és vonalstílusok megkönnyítik az adatok átlátását.*
<br>
**730 MHz Diagramm:**
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/refs/heads/main/JEGYZOKONYV/03.%20Antenna%20jelszint/5124ca69-8048-4649-9063-49e4b8a9beaa.jpg"/>
<br>
- **Skyblue (kék):** Jelszint (dBm) – minél alacsonyabb az érték, annál jobb a jelszint.
  <br>
- **Orange (narancssárga):** Bitsebesség (Mbps) – az adatátvitel sebességét jelzi.
  <br>
- **Lightgreen (világoszöld):** MER (dB) – a modulációs hibaarány, a jelminőség mutatója.

  
 
 </details>
<br>
 
<details>
    <summary>Iskra P20 LOGPER</summary>
  1. kép: 490 MHz
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/refs/heads/main/JEGYZOKONYV/03.%20Antenna%20jelszint/its_snapshot_0001.bmp"/>
   730MHz : 
  <br>
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/refs/heads/main/JEGYZOKONYV/03.%20Antenna%20jelszint/its_snapshot_0051.bmp"/>

</details>
  
<br>
 
<details>
    <summary>ISKRA P2845</summary>
2.kép: 490MHz
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/refs/heads/main/JEGYZOKONYV/03.%20Antenna%20jelszint/its_snapshot_0002.bmp"/>
     730MHz :
  <br>
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/refs/heads/main/JEGYZOKONYV/03.%20Antenna%20jelszint/its_snapshot_0053.bmp"/>
    

 


 </details>
 <br>
<details>
    <summary>IKUSI FLASHD C48</summary>
   3. kép: 490MHz
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/refs/heads/main/JEGYZOKONYV/03.%20Antenna%20jelszint/its_snapshot_0003.bmp"/>
    730MHz :
  <br>
   <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES2/refs/heads/main/JEGYZOKONYV/03.%20Antenna%20jelszint/its_snapshot_0054.bmp"/>
    

 </details>
 
<br>
    
---

## Következtetések

### Ajánlások antenna kiválasztására:

1. Az **ISKRA P2845** antenna alkalmasabb a stabil és jó jelminőség biztosítására, különösen alacsonyabb frekvenciákon.
2. Ha nagyobb bitsebesség elérése a cél, és kevésbé fontos a jelszint vagy a MER, akkor az **IKUSI FLASHD C48** használata előnyös lehet.

### További szempontok:

- A különböző antennák használata során a frekvencia, a környezeti viszonyok és az antenna felszerelési magassága is jelentős hatással van az eredményekre.

### Gyakorlati tanulságok:

- Az iránykarakterisztika és a nyereség kritikus tényezők a választás során, különösen, ha adott környezetben kell optimális teljesítményt biztosítani.

---

## Mérési jegyzőkönyv lezárása

A mérések sikeresen zárultak, az eredmények alátámasztják a különböző antennák közötti teljesítménybeli eltéréseket és a frekvencia hatását a jelminőségre.

---



