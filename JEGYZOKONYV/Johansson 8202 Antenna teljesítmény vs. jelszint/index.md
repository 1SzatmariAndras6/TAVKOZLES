# Mérési Jegyzőkönyv - Antenna Teljesítmény és Jelminőség Összehasonlítása
---
- **Mérés helye**: V3 labor, belső udvar, hátsó udvar
- **Mérés időpontja**: 2024.10.09
- **Mérő műszerek**:  METEK HDD
- **Felelős személy**: Szatmári András
---

## 1. Mérési Feladat Célja

A mérési feladat célja, hogy összehasonlítsuk három különböző antenna teljesítményét ugyanazon DVB-T jel sugárzásával, és meghatározzuk, hogyan befolyásolja az antenna típusa a jelminőséget és a nyereséget különböző környezetekben.

## 2. Eszközök

- **Johansson 8202 DVB-T modulátor**
- **ISKRA P20 LOGPER antenna (vételre)**
- **ISKRA P2845 antenna (vételre)**
- **IKUSI FLASHD C48 antenna (vételre)**
- **Philips SDV5228 (adó oldalra)**
- **RF kábelek**
- **DVB-T vevő (pl. TV vagy mérőműszer)**
- **METEK HD spektrum/jelszint analizátor**
- **Laptop (jegyzőkönyv készítése)**

## 3. Mérés Lépései

### 3.1. Johansson 8202 DVB-T Modulátor Beállítása

Állítsák be a modulátort a következő paraméterekkel:
- **RF frekvencia:** Szabad sáv, amibe nem zavar bele az adás
- **Moduláció:** 16-QAM
- **Sávszélesség:** 8 MHz
- **Jelszint:** -10 dBm

A modulátor beállításai állandóak maradnak az egész mérés során, csak az antenna típusát változtatják a vételi oldalon.

### 3.2. Jelátvitel és Mérési Eredmények

#### 3.2.1. ISKRA P20 LOGPER Antenna
- Csatlakoztassák az **ISKRA P20 LOGPER** antennát a DVB-T vevőhöz.
- Mérés: Jelszint (dBm), MER (dB), Bitsebesség (Mbps)
- Használják a **METEK HD spektrum/jelszint analizátort** az adatok mérésére.

#### 3.2.2. ISKRA P2845 Antenna
- Csatlakoztassák az **ISKRA P2845** antennát.
- Mérés: Jelszint (dBm), MER (dB), Bitsebesség (Mbps)
- Használják a **METEK HD spektrum/jelszint analizátort** az adatok mérésére.

#### 3.2.3. IKUSI FLASHD C48 Antenna
- Csatlakoztassák az **IKUSI FLASHD C48** antennát.
- Mérés: Jelszint (dBm), MER (dB), Bitsebesség (Mbps)
- Használják a **METEK HD spektrum/jelszint analizátort** az adatok mérésére.

### 3.3. Mérés Ismétlése Egy Másik Szabad Frekvencián

Ismételjék meg a méréseket mindegyik antennatípussal egy másik szabad csatornán, minimum 80-100 MHz eltéréssel az előző frekvenciához képest.

## 4. Jegyzőkönyv

| **Antenna típusa**   | **RF frekvencia (MHz)** | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER érték (dB)** |
|----------------------|-------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER     | 522                     | [érték]             | [érték]                | [érték]            |
| ISKRA P2845          | 522                     | [érték]             | [érték]                | [érték]            |
| IKUSI FLASHD C48     | 522                     | [érték]             | [érték]                | [érték]            |
| ISKRA P20 LOGPER     | 610                     | [érték]             | [érték]                | [érték]            |
| ISKRA P2845          | 610                     | [érték]             | [érték]                | [érték]            |
| IKUSI FLASHD C48     | 610                     | [érték]             | [érték]                | [érték]            |

## 5. Kiértékelés

Elemezzük, hogy melyik antenna biztosította a legjobb jelminőséget és jelszintet az adott frekvencián. A következő tényezők befolyásolhatják az antennák teljesítményét:
- **Antenna típusa**: Különböző típusok eltérő sugárzási karakterisztikákkal rendelkeznek.
- **Nyereség**: Az antenna nyeresége befolyásolja a jel erősségét.
- **Iránykarakterisztika**: Az antennák iránykarakterisztikája hatással van a vételi és sugárzási teljesítményre különböző környezetekben.

## 6. Időtartam

- **Modulátor beállítása, antennák felszerelése:**   
- **Mérések a három antennával:** 
- **Jegyzőkönyv készítése és kiértékelés:** 
