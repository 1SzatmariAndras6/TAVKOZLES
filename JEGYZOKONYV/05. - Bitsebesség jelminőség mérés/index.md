# Mérési Feladat: Bitsebesség és Jelminőség Hatása

---

- **Mérés helye**: V3 labor
- **Mérés időpontja**: 2024.12.18
- **Felelős személy**: Szatmári András
- #### Cél: A feladat célja, hogy megértsük a különböző bitsebességek hatását a DVB-T jelek minőségére a Johansson 8202 modulátor használatával, különös figyelmet fordítva a többcsatornás jelgenerálásra.
---


## Eszközök
- 2db Johansson 8202 DVB-T modulátor
- DVB-T vevő (pl. TV vagy mérőműszer)
- RF kábelek
- METEK HD spektrum/jelszint analizátor
- Laptop jegyzőkönyv készítéséhez

---

## Feladat

### 1. Modulátor konfiguráció
- **RF frekvenciák beállítása**: 698MHz és 690MHz
- **Moduláció**: 64-QAM.
- **Sávszélesség**: 8 MHz.
- **Bitsebesség beállítása**: TV1: 15 Mbps, TV2: 10 Mbps.

---


## 2. Bitsebesség és Jelminőség Összefüggése

Az alábbi mérési eredmények alapján látható, hogy a bitsebesség növekedése általában csökkenti a jelminőséget, mivel a MER (Modulation Error Ratio) értékei alacsonyabbak lesznek magasabb bitsebességnél. Ugyanakkor az RF frekvencia is befolyásolja az eredményeket, mivel a különböző frekvenciák eltérően viselkedhetnek a jelek sugárzásakor.

---


### 3. Összegzés és Kiértékelés

**Összehasonlítás**:  
  A mérési eredmények alapján a legjobb jelminőséget (MER) a **TV2 program érte el 690 MHz-en**, 12.68 Mbps bitsebességgel, ahol az MER értéke 40 dB volt.  

  A **TV1 programnál** a legjobb MER érték 34.4 dB volt 14.029 Mbps bitsebességnél és 698 MHz frekvencián.  
  Az eredmények azt mutatják, hogy az alacsonyabb bitsebesség és kedvezőbb RF környezet jelentősen hozzájárul a jobb jelminőséghez.

- **Optimális beállítások**:
  
  1. Az RF frekvenciák közötti interferencia minimalizálásához javasolt a csatornák gondos elosztása. A 690 MHz frekvencia jobb eredményeket adott, ezért előnyben részesíthető.  

  2. A jelminőség (MER) javítása érdekében érdemes alacsonyabb bitsebességet használni, különösen olyan programoknál, ahol a stabil jel elengedhetetlen.  

  3. A sugárzási teljesítményt növelni szükséges, különösen 698 MHz esetében, ahol a jelszint gyengébb volt.  

  4. Ajánlott adaptív modulációs technológiák alkalmazása, amelyek az aktuális környezeti feltételekhez igazítják a bitsebességet és a modulációt.  

# Képek:

  <details>
    <br>
    
  <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/05.%20-%20Bitsebess%C3%A9g%20jelmin%C5%91s%C3%A9g%20m%C3%A9r%C3%A9s/its_snapshot_0001%20(2).bmp">
    
  <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/05.%20-%20Bitsebess%C3%A9g%20jelmin%C5%91s%C3%A9g%20m%C3%A9r%C3%A9s/its_snapshot_0002%20(2).bmp">
    <br>
  Bitsebesség
  <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/05.%20-%20Bitsebess%C3%A9g%20jelmin%C5%91s%C3%A9g%20m%C3%A9r%C3%A9s/its_snapshot_0003%20(1).bmp">
  
  Mer,jelszint értékek:
  
  <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/05.%20-%20Bitsebess%C3%A9g%20jelmin%C5%91s%C3%A9g%20m%C3%A9r%C3%A9s/its_snapshot_0004%20(1).bmp">

  </details>
  
  Diagramm:

  <img width="200" src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/05.%20-%20Bitsebess%C3%A9g%20jelmin%C5%91s%C3%A9g%20m%C3%A9r%C3%A9s/9772640a-cde7-45e4-8f24-9ededfb55cda.png">

---

## 4. Mérési redmények

| Mérési paraméter   | RF frekvencia (MHz) | Program neve | Bitsebesség (Mbps) | Jelszint (dBm) | MER érték (dB) |
|--------------------|---------------------|--------------|--------------------|----------------|----------------|
| Mérési eredmény 1  |     690MHz          |   Tv2        |    12.68Mbps       |  - 35.2dBm     |     40dB       |
| Mérési eredmény 2  |     698MHz          |   Tv1        |    14.029Mbps      |  - 31.9dBm     |     34.4dB     |
| Mérési eredmény 3  |     690MHz          |   Tv2        |    18.9mBps(max)   |  - 35.2dbm     |     39.4dB     |

---
