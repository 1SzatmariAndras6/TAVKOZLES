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

<br>
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/01.%20-%20T%20m%C3%A9r%C3%A9si%20feladat/K%C3%A9perny%C5%91k%C3%A9p%202024-12-11%20090144.png">

<br>
<img src="https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/01.%20-%20T%20m%C3%A9r%C3%A9si%20feladat/K%C3%A9perny%C5%91k%C3%A9p%202024-12-11%20094633.png">
  
##3. Számolások, értékek

- **Ellenállások értékei:** R1 és R2 mért értékei.
- R1, R2: 264 Ω, 264 Ω ,
- R3: 900 Ω
- Rg: 680 Ω
- **Mérési eredmények:**
  - Bemeneti impedancia (Ω)
  - Kimeneti impedancia (Ω)
  - Átviteli arány (dB)
  - Csillapítás (dB)

 ## T-tag Ellenállások Számítása (6 dB Csillapítás és 680 Ohm Impedancia)

### Adatok
- **Impedancia (\(Z\))**: 680 Ω
- **Csillapítás (\(A\))**: 6 dB

### Képletek
1. **Csillapítás lineáris aránya (\(K\)):**
   \[
   K = 10^{\frac{\text{Csillapítás (dB)}}{20}}
   \]
2. **Oldalsó ellenállások (\(R_s\) és \(R_l\)):**
   \[
   R_s = R_l = Z \cdot \frac{K + 1}{K - 1}
   \]
3. **Középső ellenállás (\(R_m\)):**
   \[
   R_m = \frac{Z}{2} \cdot (K - 1)
   \]

### Számítás
1. **Csillapítás lineáris aránya (\(K\)):**
   \[
   K = 10^{\frac{6}{20}} \approx 1.9953
   \]

2. **Oldalsó ellenállások (\(R_s\) és \(R_l\)):**
   \[
   R_s = R_l = 680 \cdot \frac{1.9953 + 1}{1.9953 - 1}
   \]
   \[
   R_s = R_l \approx 680 \cdot \frac{2.9953}{0.9953} \approx 2045.9 \, \Omega
   \]

3. **Középső ellenállás (\(R_m\)):**
   \[
   R_m = \frac{680}{2} \cdot (1.9953 - 1)
   \]
   \[
   R_m \approx 340 \cdot 0.9953 \approx 338.4 \, \Omega
   \]

### Eredmények
- **\(R_m\)**: 338.4 Ω
- **\(R_s = R_l\)**: 2045.9 Ω
---
    
- **Eredmények összehasonlítása:**


- **Megjegyzések:**
 
 
    ---
    
A **T ellenállás-hálózat** egy egyszerű, de hatékony módja az impedancia illesztésének és a jel csillapításának. Az **R1** és **R2** ellenállások közötti viszonyok meghatározzák a hálózat teljesítményét és a kimeneti jelet.
