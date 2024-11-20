# Mérési Jegyzőkönyv

**A különböző típusú antennák teljesítménye és a vételi jelminőség összehasonlítása.**


---

- **Mérés helye**: V3 labor
- **Mérés időpontja**: 2024.11.13
- **Felelős személy**: Szatmári András
- **Csoport**: Távközlési technikus, 13/E

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

### 1. Johansson 8202 DVB-T modulátor beállítása
- **RF frekvencia:** Szabad sáv, amibe nem zavar bele az adás.
- **Moduláció:** 16-QAM
- **Sávszélesség:** 8 MHz
- **Jelszint:** -10 dBm
- **Antenna magasságai**: 1,4méter
- A modulátor beállításai állandóak maradnak az egész mérés során, csak az antenna típusát változtatjuk a vételi oldalon.
- Az adóoldalon egy körsugárzó antenna (Philips SDV5228) segítségével szórjuk a DVB-T jelet.

### 2. Mérés ismétlése egy másik szabad frekvencián

- Az új frekvenciánk lett a 730MHz
  

### 3. Kiértékelés
#### Legjobb jelminőség:

- **490 MHz frekvencián:**  
  Az **ISKRA P2845** antenna teljesített a legjobban, mivel a legnagyobb MER értéket (27,7 dB) és bitsebességet (9,5 Mbps) biztosította.

- **730 MHz frekvencián:**  
  Az **ISKRA P2845** ismét kiemelkedett (MER: 27,5 dB, bitsebesség: 9,59 Mbps), azonban az **IKUSI FLASHD C48** magasabb bitsebességet ért el (9,81 Mbps), bár a jelszint és MER értékek gyengébbek voltak.

### Környezet és frekvencia hatása:

- A 730 MHz-es frekvencián minden antenna teljesítménye kissé romlott, különösen a MER értékek csökkentek, ami az emelkedő frekvenciával járó csillapításnak tudható be.

### 4. Tényezők, amelyek befolyásolták a teljesítményt:

- **Antennák nyeresége:**  
  Az **ISKRA P2845** nagyobb nyereséget biztosított, különösen alacsonyabb frekvenciákon.

- **Iránykarakterisztika:**  
  Az irányítottabb antennák (pl. **ISKRA P20 LOGPER**) jobb MER-t biztosítottak bizonyos körülmények között, míg a szélesebb nyalábkarakterisztikájú antennák (**IKUSI FLASHD C48**) nagyobb bitsebességet értek el.


---

## Mért Adatok - 490 MHz frekvencián

| **Antenna típusa**       | **Jelszint (dBm)**  | **Bitsebesség (Mbps)** | **MER érték (dB)**  |
|--------------------------|---------------------|------------------------|---------------------|
| ISKRA P20 LOGPER         |      -56,5          |        9,2             |      27,3           |
| ISKRA P2845              |      -56,4          |        9,5             |      27,7           |
| IKUSI FLASHD C48         |      -59,2          |        8,7             |      26,5           |

---

## Mért Adatok - 730 MHz frekvencián

| **Antenna típusa**       | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER érték (dB)** |
|--------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER         |   -60,3             |       9,3              |       23           |
| ISKRA P2845              |   -59,5             |       9,59             |       27,5         |
| IKUSI FLASHD C48         |   -62,8             |       9,81             |       23,7         |

--- 

## 5. Mért képek:
<details>
  <summary>490MHz és 730MHZ-es Diagrammok</summary>

<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/K%C3%A9perny%C5%91k%C3%A9p%202024-11-14%20135237.png"/>

<br>

*A három antenna teljesítményének összehasonlítására a 490 MHz-es frekvencián. Az oszlopok a jelszintet (dBm) mutatják, míg a pontokkal összekötött vonalak a MER értéket (dB) és a bitsebességet (Mbps) szemléltetik. A különböző színek és vonalstílusok megkönnyítik az adatok átlátását.*

<br>

730 MHz Diagramm:
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/Antenna%20parame%CC%81terek%20o%CC%88sszehasonli%CC%81ta%CC%81sa%20optimaliza%CC%81lt%20ska%CC%81la%CC%81za%CC%81ssal.png"/>

<br>
Itt látható a grafikon, amely az antennák teljesítménymutatóit (jelszint, bitsebesség és MER érték) ábrázolja a 730 MHz-es frekvencián. A következő elemeket tartalmazza:
<br>
- Kék vonal (Jelszint dBm): Alacsonyabb értékek jelzik a jobb jelszintet.
  <br>
- Narancssárga vonal (Bitsebesség Mbps): Az adatátvitel sebességét mutatja.
  <br>
- Zöld vonal (MER dB): A jelminőség mutatója.

  
 
 </details>
<br>
 
<details>
    <summary>Iskra P20 LOGPER</summary>
  1. kép: 490 MHz
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/its_snapshot_0001.bmp"/>
   730MHz : 
  <br>
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/its_snapshot_0051.bmp"/>

</details>
  
<br>
 
<details>
    <summary>ISKRA P2845</summary>
2.kép: 490MHz
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/its_snapshot_0002.bmp"/>
     730MHz :
  <br>
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/its_snapshot_0053.bmp"/>
    

 


 </details>
 <br>
<details>
    <summary>IKUSI FLASHD C48</summary>
   3. kép: 490MHz
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/its_snapshot_0003.bmp"/>
    730MHz :
  <br>
   <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/its_snapshot_0054.bmp"/>
    

 </details>
 
<br>

</details>
 <br>
<details>
    <summary>Antenna képek : </summary>
 Antenna képek:
  IKUSI FLASHD C48
    <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/3913-1.png"/>
  Iskra-p2845
  <br>
   <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/iskra-p-2845_6018d271.jpg"/>
     <br>
     Iskra P20 LOGPER
   <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/06.%20Antenna%20jelszint/220318106.jpg"/>
    

 </details>
 
<br>
    
---

## 6. Következtetések

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



