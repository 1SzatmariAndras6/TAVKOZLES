# Gyakorlat Jegyzőkönyve: Johansson 6700 Profiler Beállítások és Mérések
- **Mérés helye**: V3 labor
- **Mérés időpontja**: 2024.11.13
- **Felelős személy**: Szatmári András
- **Csoport**: Távközlési technikus, 13/E
- **Csoport**: Távközlési technikus, 13/E
- **Mérés tárgya**: DVB-T jel generálása és mérése Johansson 8202 DVB-T modulátorral és METEK HD spektrum/jelszint analizátorral
## Szükséges eszközök
- **Johansson 6700 Profiler**: Programozható antennaerősítő-szűrő
- **FM antenna**: 88-108 MHz tartomány
- **DVB-T antenna**: UHF 470-862 MHz tartomány
- **Spektrum analizátor**
- **Koaxiális kábelek**
- **Laptop**: Beállítások elvégzéséhez és jegyzőkönyv készítéséhez

---

## Feladat leírása

### 1. Eszközök bekapcsolása és bekötése (30 perc)
1. **Spektrumanalizátor mérés**:  
   - Csatlakoztassátok az antennát a spektrumanalizátorhoz, és rögzítsétek a 400-900 MHz közötti jeleket.
2. **Johansson 6700 bekötése**:  
   - Antennát csatlakoztassátok a Johansson 6700 egyik bemenetére.
   - Csatlakoztassátok a spektrumanalizátort RF kábelekkel a Johansson 6700 Profiler kimenetére.
3. **FM és DVB-T antennák**:  
   - Kössétek az FM antennát az FM bemenetre, a DVB-T antennát pedig a VHF/UHF bemenetre.
   - Koax kábellel csatlakoztassátok a Johansson 8202 modulátort egy másik VHF/UHF bemenetre.

---

### 2. Csatornaáthelyezés és jelszint-optimalizálás (45 perc)
1. **Csatornaáthelyezés**:  
   - Használjátok a Johansson 6700 frekvenciakonverterét az FM és DVB-T jelek áthelyezésére.
   - Példa: DVB-T jeleket helyezzétek át növekvő sorrendben a 41-es csatornától kezdve.
2. **Jegyzőkönyvezés**:  
   - Dokumentáljátok az összes bejövő frekvenciát és az áthelyezett csatornák új frekvenciáit.
3. **Automatikus jelszintszabályzás**:  
   - Kapcsoljátok be az automatikus jelszintszabályzást (AGC).
   - Ha szükséges, aktiváljátok az antenna erősítő funkciót.
4. **Jelszintek ellenőrzése**:  
   - Mérjétek meg és jegyezzétek fel a bemeneti és kimeneti jelszinteket a spektrumanalizátor segítségével.

---

### 3. Szűrő beállítások és interferencia vizsgálat (15 perc)
1. **LTE szűrő ellenőrzése**:  
   - Vizsgáljátok meg, hogy az LTE szűrő megfelelően megszűri-e a 790 MHz feletti zavaró jeleket.
2. **Spektrumanalizátor mérés**:  
   - Készítsetek feljegyzéseket a bemeneti és kimeneti spektrumról, és dokumentáljátok, hogyan hatnak a szűrők a jelminőségre.

---

### 4. Jegyzőkönyv készítése (30 perc)
Készítsetek részletes jegyzőkönyvet, amely tartalmazza:
- Antennák beállításait és bemeneti jelszinteket.
- Csatornaáthelyezési beállításokat és azok hatását a kimenő jelszintekre.
- Az AGC (Automatic Gain Control) hatását a jelszintek kiegyenlítésére.
- A szűrés mérési eredményeit.

---

## Táblázat a jegyzőkönyvhöz

| **Antenna típusa**| **Eredeti csatorna** | **Áthelyezett csatorna** | **Eredeti frekvencia (MHz)** | **Áthelyezett frekvencia (MHz)** | **Bemeneti jelszint (dB)** | **Kimeneti jelszint (dB)** | **Spektrum analizátor kép neve**    |
|---------------------------|----------------------|---------------------------|------------------------------|----------------------------------|----------------------------|----------------------------|-------------------------------------|
| **FM antenna**           | 101,7 MHz           | 183,7 MHz                | 100 MHz                     | 180 MHz                         | -30 dB                    | -20 dB                    | FM_before_after.png               |
| **DVB-T antenna (VHF)**  | 5. csatorna         | 10. csatorna             | 220 MHz                     | 230 MHz                         | -40 dB                    | -30 dB                    | VHF_signal_comparison.png         |
| **DVB-T antenna (UHF)**  | 28. csatorna        | 33. csatorna             | 500 MHz                     | 600 MHz                         | -35 dB                    | -25 dB                    | UHF_signal_shift.png              |
| **Koax kábel (RF modulátor)** | KábelTV (CH22)    | KábelTV (CH23)           | 600 MHz                     | 700 MHz                         | -45 dB                    | -30 dB                    | Coax_signal_modification.png      |

---

## Jegyzőkönyv Lezárása
A jegyzőkönyvben a tanulóknak részletesen dokumentálniuk kell az eredeti és áthelyezett frekvenciákat, a bemeneti és kimeneti jelszinteket, valamint a szűrők alkalmazásának hatását. A fenti táblázat segít az eredmények rendszerezésében és áttekintésében.
