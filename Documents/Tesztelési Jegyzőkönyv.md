# Teszt jegyzőkönyv
### Main Project
|  Dokumentum címe: (azonosítója) |  Sziauram_team - "Musician web portal" |
|---|:-:|
| **Minősítés: (állapot)**  |  Továbbfejlesztés |
| **Verziószám:**  |  1.1 Beta |
| **Projekt név:** |  Musician web portal |
| **Készítette:** | Sziauram_team |
| **Utolsó mentés kelte:** | 2021.11.22 |
| **Dokumentum célja:** | A weboldal továbbfejlesztése

### Projektben résztvevő fejlesztők:

|  Név | Szerepkör |
|---|:-:|
| Juhász Domonkos | Adatbázis fejlesztő, Tester |
| Farkas Bálint  | Test manager, Tester |


## 1. Bevezetés

A tesztelés célja a projektben megtalálható felépítésbeli, vagy formatervezési hibák feltárása.

### 1.1 Tesztelési terv hatóköre, célja:

A tesztelési terv célja a tesztelés teljeskörűségének biztosítása, a tesztelés során alkalmazott eljárások és megoldások meghatározása.

### 1.2 Elvárások

#### A teszttervvel szemben felállított alap elvárások:

- Az olvasó ismeri az alapdokumentumokat, amelyek meghatározzák a rendszert.
- A **Sziauram_team** projektcsapat felelős a tesztadatok előállításáért.

## 2. Szükséges erőforrások
Ez a fejezet a teszteléshez szükséges erőforrásokat fejti ki.

### 2.1 Feladatkörök és felelősségek (tesztcsapat meghatározása)
| Feladatkör  |  Felelősség/tevékenység |  Személy  |
|---|---|---|
|  **Tesztelő, Teszt-koordinátor:** |  A teszt végrehajtása, észrevételek dokumentálása, teszt dokumentáció archiválása.Tesztterv készítése.  A tesztterv jóváhagyatása a projektmenedzserrel.  A teszt forgatókönyvek létrehozása  inkonzisztenciák kezelése.  Helyes és időbeni hibakezelés.  Szükség esetén problémák delegálása a projekt menedzsernek.  Végső riport készítése.  Teszt dokumentum archiválása.  Az észrevételek státuszának követése, ill. dokumentálása |  |
| **Szakértő:**  |  A szakértő az észrevételeket elemzi és megoldást javasol. |   |
|**Projektvezető:**| | |

### 2.2 Tesztadatok
A teszt végrehajtásához szükséges rekordok (tesztadatok) száma: ---
A tesztadatok elkészítéséért és feltöltéséért felelős személy: ---

A tesztadatoknak az alábbi követelményeknek kell megfelelniük:
- Az adatbázisba felvitt adatoknak csakis az UTF-8 kódtáblában található karaktereket szabad tartalmaznia.

## 3. Tesztelési terv
Ez a fejezet leírja a teszt típusát, a metodikáját és a riportkészítés módszerét. Emellett meghatározza a tesztelvárásokat, a teszt-esetek elvárt eredményeit, sikerességének kritériumait, a kockázatok kezelését és a hatáskörön kívül eseteket.

### 3.1 Fejlesztői teszt
A fejlesztői tesztelés célja a rendszer alapvető funkcióinak ellenőrzése, a hibakezelés és az alapvető funkciók működésének vizsgálata
**Módszere:**
A program SQL adatbázisa "DUMMY" (*Nem valós*) adatokkal kerül feltöltésre a tesztelés alatt.
Ezen adatok többségét úgynevett "Lorem Ipsum" típusú, véletlenül generált adat teszi ki.

### 3.2 Prototípus (modul) teszt
A prototípus tesztelés (vagy másik nevén modultesztelés) célja a rendszer már működő moduljainak önálló tesztelése, a modulon belüli hibák azonosításának és kiküszöbölésének érdekében. 
**Módszere:**
A program adatbázisába valós adatok kerülnek betöltésre.

### 3.3 Integrációs teszt
Az integrációs teszt célja a rendszer más rendszerekhez történő illesztésének vizsgálata, a több rendszeren keresztül átívelő funkciók tesztelésének érdekében. Az adatmigrációs tesztelés az integrációs teszteléshez tartozik, ennek lényege, hogy a bevezetendő rendszerbe áttöltik azokat az adatokat, amelyekkel a rendszer dolgozni fog, és letesztelik a betöltött adatok, illetve az adatokat kezelő funkciók helyességét. 
**Módszere:**
A program adatbázisába valós adatok kerülnek betöltésre.

### 3.4 Elfogadási teszt
Az elfogadási teszt (angolul User Acceptance Test) célja a rendszer teljes funkcionalitásának vizsgálata a felhasználók szemszögéből
**Módszere:**
A teszt egy kontroll csoporttal zajlik, egy külső cégen keresztül.

### 3.5 Terheléses teszt
A terheléses teszt célja a tervezett kapacitások, valamint a rendelkezésre álló növekedési potenciál meghatározása.
**Módszere:**
A próba telepítést követően egy meghívott tesztközönséggel zajlik, szimulálva egy átlagos napi használatot.

## 4 Tesztelési ütemterv, függőségek – tesztforgatókönyv

### 4.1 Tesztelési jelentés
A tesztelési jelentést a tesztkoordinátor készíti el. Ez egy részletes áttekintése a lefutott teszteknek, azok eredményeinek, státuszának és a megjegyzéseknek.
A tesztkoordinátor juttatja el a projektmenedzsernek a tesztelési jelentést. 

## 5. Tesztjegyzőkönyv
### 5.1 Tesztelési jegyzőkönyv - 1. Példa

|   |   |
|---|---|
| A teszt-eset leírás és célja:  |  |
| A tesztelt folyamat/funkció leírása:  |   |
| A tesztelés előfeltételei:  |  |
| A tesztelés dátuma és időpontja:  |  |
| A tesztet végző személy(ek):  |   |
| A tesztelt rendszer beállításai:  |  |
| A teszt-eset elvárt eredménye:  |  |
| A tesztelés eredménye:  |  |
| Megjegyzések:  | -  |

**Tesztelést elvégezte**

|   |   |
|---|---|
|  Név: |   |
|  Szervezeti egység/ beosztás: |   |
|  Dátum: | 

### 5.2 Tesztelési jelentés - 2. Példa
|   |   |
|---|---|
| A hivatkozott tesztjegyzőkönyvek rövid leírása és eredménye:  | |
| A tesztelt folyamatok/funkciók/modulok leírása: | |
| A tesztadatok típusa:  |  |
| A tesztelt rendszer beállításai:  |  |
| A tesztelés eredménye:  | |
| Megjegyzések:  | |

**Tesztelést elvégezte**

|   |   |
|---|---|
|  Név: | |
|  Szervezeti egység/ beosztás: |  |
|  Dátum: |   |

### 5.3 Jóváhagyások

|   |   |
|---|---|
|  Név: |   |
|  Szervezeti egység/ beosztás: |  |
|  Dátum: |    |

### 6. Unit tesztek

| Sorszám                  |    Név                   |  Dátum     | Funkció leírás  	| Vizsgálat módja/eszköze,részletes leírása	|Elvárt eredmény	|Verzió	|
|----------------|-------------------------------|-----------------------------|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T1|Ardó Balázs|2021.10.02|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T2|Farkas Bálint|2021.10.19|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T3|Bodó Zoltán|2021.10.20|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T4|Juhász Domonkos|2021.10.21|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T5|Ardó Balázs|2021.10.22|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T6|Farkas Bálint|2021.10.24|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T7|Juhász Domonkos|2021.11.03|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T8|Bodó Zoltán|2021.11.12|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T9|Ardó Balázs|2021.11.16|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T10|Farkas Bálint|2021.11.20|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
