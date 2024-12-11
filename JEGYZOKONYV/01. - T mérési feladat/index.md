# Méréstechnikai Feladat: T Ellenállás-hálózat
---

- **Mérés helye**: V3 labor,
- **Mérés időpontja**: 2024.12.11
- **Felelős személy**: Szatmári András
- **Cél**: A T ellenállás-hálózat jellemzőinek meghatározása.
- **Csoport neve**: Szatmári András, Szabó Alex
---

# 1. Eszközök

- **Multiméter**
- **Ellenállások**
- **Breadboard**
- **Jelgenerátor**
- **Oszcilloszkóp**
- vagy **NI MYDAQ**

---

# Ábra: 

<br>
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/5e951d5149058ee1226aa7e69a42019efbca4d91/JEGYZOKONYV/01%20-%20T%20m%C3%A9r%C3%A9si%20feladat/attenuator-resistive-t-section-pad.svg">

# 2. Dokumentált eredmények:

<details>
  
<br>
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/01.%20-%20T%20m%C3%A9r%C3%A9si%20feladat/K%C3%A9perny%C5%91k%C3%A9p%202024-12-11%20090144.png">
  <details/>
<details>
<br>
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/01.%20-%20T%20m%C3%A9r%C3%A9si%20feladat/K%C3%A9perny%C5%91k%C3%A9p%202024-12-11%20094633.png">

  <details/>
    
---
    
## 3. Számolások, értékek

- **Ellenállások értékei:** R1 és R2 mért értékei.
- R1, R2: 264 Ω, 264 Ω ,
- R3: 900 Ω
- Rg: 680 Ω
- **Mérési eredmények:**
 Rm=  338.4 Ω
 Rs=Rl=2045.9 Ω
- **Bemeneti impedancia**: 1784.8 Ω  
- **Kimeneti impedancia**: 1784.8 Ω  
- **Átviteli arány**: -1.33 dB  
- **Csillapítás**: 1.33 dB
  - 2045.9(2722.72384.3)≈2045.9×0.8746≈1784.8Ω
  - TdB=20log10(T)=20log10(0.8585)≈−1.33dB
  - A=−TdB =1.33dB
  
 ## T-tag Ellenállások Számítása

### Adatok
- **Impedancia (\(Z\))**: 680 Ω
- **Csillapítás (\(A\))**: 6 dB

---
    
### Eredmények összehasonlítása

- **Bemeneti és Kimeneti Impedancia**:
  - **Számított**: 1784.8 Ω
  - **Mért**: 1784.8 Ω
- **Átviteli Arány és Csillapítás**:
  - **Számított csillapítás**: 1.33 dB
  - **Mért csillapítás**: A csillapítás mért értéke kisebb eltéréseket mutathat a mérési hibák és környezeti tényezők miatt.

### Megjegyzések
- **Mérési hibák**: A mérőeszközök kalibrálása és a csatlakozások hatással lehetnek az eredményekre.
- **Alkatrész variációk**: Az ellenállások tűrései miatt az elméleti és mért értékek eltérhetnek.
- **Feszültség és áram mérések**: A mérési eszközök pontossága, mint a jelgenerátor és az oszcilloszkóp, befolyásolhatják az eredményeket.

Az eredmények összehasonlítása segít a mérési környezet és eszközök hatásainak megértésében.
