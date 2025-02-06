# Hálózati konfiguráció és tesztelés

**A mérést végző neve:** Szatmári András

**A mérés tárgya és mérés száma:** 

**A mérés dátuma:** 2025.02.6

**A mérést vezette:** Csontos Dénes

- **Évfolyam:** 13. E

- **Csoport:** GYAK 2

- **Helyszín:** Fizikai


## Eszközök

A tesztelés során az alábbi eszközöket használtam:

- **Catalyst 2950 switch** – A hálózati eszközök közötti kapcsolat biztosítására.  
- **** – A hálózat központi vezérlőjeként működött.  
- **ThinkPad laptop** – Ezen futtattam a ping teszteket és egyéb parancsokat a hálózat ellenőrzéséhez.  
- **Mobiltelefon** – A Linksys routerhez csatlakozva lehetővé tette a laptop és más eszközök közötti kapcsolat tesztelését.

## Leírás

Ez a jegyzőkönyv a Linksys router beállítását és a hozzá kapcsolódó hálózati eszközök tesztelését dokumentálja. A feladat során IP-címek kezelése, routing tábla megtekintése, ping tesztek és egyéb hálózati parancsok alkalmazása történt.

## 1. A számítógép IP beállításainak lekérdezése:

Parancs: `ipconfig`

<details>
  <summary>Kép megtekintése</summary>

  ![IPCONFIG]()

</details>

## 2. IP-cím eldobása és új IP-cím kérése  

A DHCP szerver által kiosztott IP-címek kezeléséhez először el kell dobni a jelenlegi IP-címet, majd új IP-címet kell kérni a DHCP-től.  

### IP-cím eldobása  
Parancs:  
```sh
ipconfig /release

