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

### 2. DVB-T jel mérés és stream ellenőrzés
- Mérni kell a következő paramétereket:
  - Jelszint (dBm): 
  - Modulation Error Ratio (MER):
  - Bitsebesség :
 
    ---

### 3. Bitsebesség és jelminőség összefüggése
- **Bitsebesség változtatása**: TV2 bitsebességének növelése 10 Mbps-ról MAXIMUM-ra.
- Mérni a jelszintet, MER-t és a vevő reakcióját.

  ---

### 4. Jegyzőkönyv készítése
A jegyzőkönyv tartalmazza:
- **RF frekvencia (MHz)**
- **Moduláció típusa**
- **Sávszélesség (MHz)**
- **Jelszint (dBm)**
- **Bitsebesség (Mbps)**
- **MER érték (dB)**

  ---

### 5. Összegzés és Kiértékelés
- **Összehasonlítás**: Melyik bitsebesség biztosította a legjobb jelminőséget mindkét program számára?
- **Optimális beállítások**: Hogyan lehet javítani a többcsatornás jelek sugárzását?

---

## Jegyzőkönyv Sablon

| Mérési paraméter   | RF frekvencia (MHz) | Program neve | Bitsebesség (Mbps) | Jelszint (dBm) | MER érték (dB) |
|--------------------|---------------------|--------------|--------------------|----------------|----------------|
| Mérési eredmény 1  |     690MHz          |   Tv2        |    12.68Mbps       |  - 35.2dBm     |     40dB       |
| Mérési eredmény 2  |     698MHz          |   Tv1        |    14.029Mbps      |  - 31.9dBm     |     34.4dB     |
| Mérési eredmény 3  |     690MHz          |   Tv2        |    18.9mBps(max)   |  - 35.2dbm     |     39.4dB     |

---
