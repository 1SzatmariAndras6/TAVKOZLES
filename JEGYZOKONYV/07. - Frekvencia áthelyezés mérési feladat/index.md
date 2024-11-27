# Gyakorlat Jegyzőkönyve: Johansson 6700 Profiler Beállítások és Mérések
---

- **Mérés helye**: V3 labor
- **Mérés időpontja**: 2024.11.13
- **Felelős személy**: Szatmári András
- **Csoport**: Távközlési technikus, 13/E
- **Mérés tárgya**: DVB-T jel generálása és mérése Johansson 8202 DVB-T modulátorral és METEK HD spektrum/jelszint analizátorral

---
## Szükséges eszközök
- **Johansson 6700 Profiler**: Programozható antennaerősítő-szűrő
- **FM antenna**: 88-108 MHz tartomány
- **DVB-T antenna**: UHF 470-862 MHz tartomány
- **Spektrum analizátor**
- **Koaxiális kábelek**
- **Laptop**: Beállítások elvégzéséhez és jegyzőkönyv készítéséhez

---

## Feladat leírása

### 1.  Eszközök bekapcsolása és bekötése

0.1 **Antenna csatlakoztatása a spektrumanalizátorhoz:**
   - Az antennát csatlakoztattuk a spektrumanalizátor bemenetére.
   - A spektrumanalizátort 45 MHz és 1000 MHz közötti frekvenciaablakra állítottuk.
   - Megfigyeltük és elmentettük az érkező jeleket ezen a frekvenciatartományban.

0.2 **Antenna csatlakoztatása a Johansson 6700 Profilerhez:**
   - Az antennát áthelyeztük a Johansson 6700 Profiler egyik illeszkedő bemenetére.
   - A spektrumanalizátort RF kábeleken keresztül csatlakoztattuk a Johansson 6700 Profilerhez, hogy mérjük az érkező jeleket.

0.3 **Antennák csatlakoztatása a megfelelő bemenetekhez:**
   - **FM antenna** csatlakoztatása az FM bemenetre.
   - **DVB-T antenna** csatlakoztatása a VHF/UHF bemenetre.
   - **Koax kábel** csatlakoztatása egy másik VHF/UHF bemenetre (például a Johansson 8202 modulátorhoz).

0.4 **Spektrumanalizátor csatlakoztatása a Johansson 6700 Profiler kimenetéhez:**
   - A spektrumanalizátort csatlakoztattuk a Johansson 6700 Profiler kimenetére a kimenő jelek méréséhez.

A fentiekben leírt lépések mindegyikét végrehajtottuk a megadott utasítások szerint.
<details>
   <br>
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/07.%20-%20Frekvencia%20%C3%A1thelyez%C3%A9s%20m%C3%A9r%C3%A9si%20feladat/its_snapshot_0005.bmp">
<br>
   <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/07.%20-%20Frekvencia%20%C3%A1thelyez%C3%A9s%20m%C3%A9r%C3%A9si%20feladat/its_snapshot_0006.bmp">
</details>

---

### 2. Csatornaáthelyezés és jelszint-optimalizálás 

**Automatikus szintszabályozás és erősítő beállítása:**
   - Aktiváltuk az automatikus csatornánkénti szintszabályzást (AGC) az eszköz menüjében.
   - Szükség esetén bekapcsoltuk az antenna erősítőt.

0.1 **Kimeneti jelszintek beállítása:**
   - A kimenő jelszinteket 100 dBu-ra állítottuk, függetlenül a bejövő jelek eltérő szintjétől.
   - A bemeneti és kimeneti jelszinteket spektrumanalizátor segítségével mértük és rögzítettük.

A fentieket az előírt módon végrehajtottuk, és minden adatot megfelelően feljegyeztünk.

<details>
   <br>
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/07.%20-%20Frekvencia%20%C3%A1thelyez%C3%A9s%20m%C3%A9r%C3%A9si%20feladat/its_snapshot_0007.bmp">
<br>
   <img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/07.%20-%20Frekvencia%20%C3%A1thelyez%C3%A9s%20m%C3%A9r%C3%A9si%20feladat/its_snapshot_0008.bmp">
</details>

---

### 3. Szűrő beállítások és interferencia vizsgálat 

 A szűrő beállításokat és interferencia vizsgálatot az alábbiak szerint végeztük el:

0.1 **LTE szűrő ellenőrzése:**
   - Ellenőriztük, hogy az eszközben található LTE szűrő megfelelően megszűri-e a 790 MHz feletti zavaró jeleket.

0.2 **Jelek vizsgálata a spektrumanalizátorral:**
   - A spektrumanalizátor segítségével figyeltük meg, hogyan változnak a jelek a kimeneten, amikor a szűrő aktiválva van.
0.3 **Jegyzőkönyv készítése:**
   - A bemeneti és kimeneti spektrum különbségeit rögzítettük.
   - Feljegyeztük, hogy a szűrő hogyan befolyásolja a jelminőséget és a jelszintet.

A vizsgálatokat a megadott módon elvégeztük, és az adatokat megfelelően dokumentáltuk.

---

### 4. 

---

## Táblázat a jegyzőkönyvhöz

| Antenna típusa | Eredeti csatorna | Áthelyezett csatorna | Eredeti frekvencia | Áthelyezett frekvencia | Bemeneti jelszint (dB) | Kimeneti jelszint (dB) |
|----------------|------------------|----------------------|--------------------|------------------------|------------------------|------------------------|
|                |       E28        |       CH 41          |      530MHz        |        634MHz          |     63 dBu             |        173.8dBu        |
|     FM Atenna  |       E31        |       CH 42          |      554MHz        |        642MHz          |     64 dBu             |        174.9dBu        |
|                |       E35        |       CH 43          |      586MHz        |        650MHZ          |     61 dBu             |        174.6dBu        |
|                |       E41        |       CH 44          |      634MHz        |        658MHz          |     48 dBu             |        169.7dBu        |
|     HDD 550    |       E45        |       CH 45          |      666MHz        |        666MHz          |     59 dBu             |        175.7dBu        |
|                |       E48        |       CH 46          |      690MHz        |        674MHz          |     56 dBu             |        174.8dBu        |

---

## Jegyzőkönyv Lezárása
