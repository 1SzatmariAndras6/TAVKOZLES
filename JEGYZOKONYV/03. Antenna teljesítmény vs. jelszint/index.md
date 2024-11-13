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
- A modulátor beállításai állandóak maradnak az egész mérés során, csak az antenna típusát változtatják a vételi oldalon.
- Az adóoldalon egy körsugárzó antenna (Philips SDV5228) segítségével szórják a DVB-T jelet.

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

## Mért Adatok - 522 MHz frekvencián

| **Antenna típusa**       | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER érték (dB)** |
|--------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER         |                     |                        |                    |
| ISKRA P2845              |                     |                        |                    |
| IKUSI FLASHD C48         |                     |                        |                    |

---

## Mért Adatok - 610 MHz frekvencián

| **Antenna típusa**       | **Jelszint (dBm)** | **Bitsebesség (Mbps)** | **MER érték (dB)** |
|--------------------------|---------------------|------------------------|--------------------|
| ISKRA P20 LOGPER         |                     |                        |                    |
| ISKRA P2845              |                     |                        |                    |
| IKUSI FLASHD C48         |                     |                        |                    |

---

## Összegzés
A mérések alapján összehasonlíthatjuk az egyes antennák teljesítményét különböző frekvenciákon, és értékelhetjük, hogy melyik antenna biztosította a legjobb jelminőséget és jelszintet. Ezen kívül elemezhetjük a mérési környezet hatását és a különböző antennák teljesítményét befolyásoló tényezőket.

---

## Következtetések
Itt rögzíthetjük a következtetéseket, amelyek segíthetnek az antenna kiválasztásában és alkalmazásában különböző környezetekben és körülmények között.

