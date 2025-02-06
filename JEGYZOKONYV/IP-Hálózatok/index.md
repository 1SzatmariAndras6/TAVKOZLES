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

  ![IPCONFIG](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20102628.png)

</details>

## 2. IP-cím eldobása és új IP-cím kérése  

A DHCP szerver által kiosztott IP-címek kezeléséhez először el kell dobni a jelenlegi IP-címet, majd új IP-címet kell kérni a DHCP-től.  

### IP-cím eldobása  

Parancs: `renew` 
<details>
  
![renew](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105735.png)
  
</details>

## 3. Új IP cím kérése!
Új IP-cím kérése a DHCP szervertől:

Parancs: `ipconfig /renew` 
<details>
  
![piconfig /renew](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20102628.png)
  
</details>


## 4. Jelenítse meg a számítógépén a routing táblát!
A számítógép routing táblájának megjelenítéséhez használja:

Parancs: `netstat -r`

<details>
  
![netstat -r](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105328.png)
  
</details>


##5. Tesztelje le, hogy elérhető-e a microsoft.com szerver!
A ping parancs segítségével tesztelhetjük, hogy a microsoft.com szerver elérhető-e:
Parancs: ` ping microsoft.com `

<details>
  
![ping microsoft.com](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20104727.png)
  
</details>


6. Kövesse le a www.ipon.hu szerver felé vezető útvonalat!
A következő parancs segítségével lekövethetjük a www.ipon.hu szerver felé vezető útvonalat:

Parancs : `tracert www.ipon.hu`
<details>
  
![tracert www.ipon.hu](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105100.png)
  
</details>





<details>
  7. Minden használt port listázása!
Az aktív hálózati kapcsolatokhoz és az általuk használt portok listázásához használjuk a következő parancsot:
  
Parancs: `netstat -a`


![netstat -a](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105328.png)
  
</details>


8. Jelenítse meg, milyen hálózati kapcsolatok vannak!
A hálózati kapcsolatok megjelenítéséhez használhatjuk a következő parancsot:
Parancs: `netsh interface show interface`
<details>
  
![netsh interface show interface](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105350.png)
  
</details>

9. Végezze el a DNS beállítások aktualizálását!
A DNS gyorsítótárának törléséhez és az új DNS beállítások lekéréséhez futtassa a következő parancsot:
Parancs: `ipconfig /flushdns`
<details>
  
![ipconfig /flushdns](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105406.png)
  
</details>


10. Jelenítse meg a csatolt hálózati meghajtókat!
A számítógéphez csatolt hálózati meghajtók megjelenítéséhez használd ezt a parancsot:
Parancs: `net use`

<details>
  
![net use](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105423.png)
  
</details>



11. Jelenítse meg a www.ipon.hu szerver tartománynév és IP címét!
A következő parancs segítségével megjeleníthetjük a www.ipon.hu szerver tartománynévét és IP-címét:
Parancs: `nslookup www.ipon.hu`
<details>
  
![nslookup www.ipon.hu](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105436.png)
  
</details>

12. Az idegen címek számára, FQDN megjelenítése:
Ehhez hasonlóan, egy másik domain név teljes kvalifikált domain nevének (FQDN) megjelenítésére van szükség, például:
Parancs: `nslookup www.example.com`


<details>
  
![nslookup www.example.com](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105525.png)
  
</details>




``
<details>
  
![renew](https://raw.githubusercontent.com/1SzatmariAndras6/TAVKOZLES/refs/heads/main/JEGYZOKONYV/IP-H%C3%A1l%C3%B3zatok/K%C3%A9perny%C5%91k%C3%A9p%202025-02-06%20105735.png)
  
</details>
