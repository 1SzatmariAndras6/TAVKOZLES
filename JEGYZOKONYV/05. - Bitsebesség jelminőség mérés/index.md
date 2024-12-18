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


## 3. Bitsebesség és Jelminőség Összefüggése

Az alábbi mérési eredmények alapján látható, hogy a bitsebesség növekedése általában csökkenti a jelminőséget, mivel a MER (Modulation Error Ratio) értékei alacsonyabbak lesznek magasabb bitsebességnél. Ugyanakkor az RF frekvencia is befolyásolja az eredményeket, mivel a különböző frekvenciák eltérően viselkedhetnek a jelek sugárzásakor.

---


### 5. Összegzés és Kiértékelés

**Összehasonlítás**:  
  A mérési eredmények alapján a legjobb jelminőséget (MER) a **TV2 program érte el 690 MHz-en**, 12.68 Mbps bitsebességgel, ahol az MER értéke 40 dB volt.  
  A **TV1 programnál** a legjobb MER érték 34.4 dB volt 14.029 Mbps bitsebességnél és 698 MHz frekvencián.  
  Az eredmények azt mutatják, hogy az alacsonyabb bitsebesség és kedvezőbb RF környezet jelentősen hozzájárul a jobb jelminőséghez.

- **Optimális beállítások**:  
  1. **Frekvenciaoptimalizálás**: Az RF frekvenciák közötti interferencia minimalizálása érdekében érdemes gondosan megválasztani a csatornák elosztását. A 690 MHz frekvencia jobb eredményeket mutatott, ezért ez előnyben részesíthető.  
  2. **Bitsebesség szabályozása**: Magasabb MER értékek érdekében érdemes alacsonyabb bitsebességet alkalmazni, különösen olyan programoknál, ahol a jel stabilitása kritikus.  
  3. **Sugárzási teljesítmény növelése**: A jelszint javítása érdekében szükséges lehet nagyobb sugárzási teljesítményt biztosítani, különösen 698 MHz-en, ahol a jelminőség gyengébb volt.  
  4. **Adaptív modulációs technológia**: A különböző csatornák számára érdemes adaptív modulációs technológiát alkalmazni, amely automatikusan az optimális bitsebességet és modulációs formát választja ki a jelminőség fenntartásához.  

---

## Mérési redmények

| Mérési paraméter   | RF frekvencia (MHz) | Program neve | Bitsebesség (Mbps) | Jelszint (dBm) | MER érték (dB) |
|--------------------|---------------------|--------------|--------------------|----------------|----------------|
| Mérési eredmény 1  |     690MHz          |   Tv2        |    12.68Mbps       |  - 35.2dBm     |     40dB       |
| Mérési eredmény 2  |     698MHz          |   Tv1        |    14.029Mbps      |  - 31.9dBm     |     34.4dB     |
| Mérési eredmény 3  |     690MHz          |   Tv2        |    18.9mBps(max)   |  - 35.2dbm     |     39.4dB     |

---
