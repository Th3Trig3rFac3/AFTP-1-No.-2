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
| Ardó Balázs  | Vezető adatbázis fejlesztő |
| Bodó Zoltán  | Adatbázis fejlesztő |
| Zsadányi Rózsa  | Project Manager |
| Kurán Bertalan  | Project Manager |


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
| **Tesztelő, Teszt-koordinátor:** |  A teszt végrehajtása, észrevételek dokumentálása, teszt dokumentáció archiválása.Tesztterv készítése.  A tesztterv jóváhagyatása a projektmenedzserrel.  A teszt forgatókönyvek létrehozása  inkonzisztenciák kezelése.  Helyes és időbeni hibakezelés.  Szükség esetén problémák delegálása a projekt menedzsernek.  Végső riport készítése.  Teszt dokumentum archiválása.  Az észrevételek státuszának követése, ill. dokumentálása | Juhász Domonkos, Farkas Bálint |
| **Szakértő:**  |  A szakértő az észrevételeket elemzi és megoldást javasol. | Kurán Bertalan, Zsadányi Rózsa  |
|**Projektvezető:**| A projekt ellenőrzése és felügyelése | Tajti Tibor | |

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

### 3.6 Biztonsági teszt (audit):
Biztonsági tesztelésre akkor van szükség, ha a rendszer szenzitív (pl. személyes vagy pénzügyi) adatokat kezel, vagy szabadon elérhető az internetről. 
**Módszere:**
A tesztet egy megbízott külső cég végzi.

### 3.7 Go live teszt
A go-live teszt egy próbaélesítés, melynek során a korábbi rendszerek továbbra is üzemelnek annak érdekében, hogy az élesítéskor keletkező problémák ne befolyásolják a normál üzemi működést.
**Módszere:**
A próbatelepítés a megrendelő által választott webtárhelyen történik, a programot a jövőben üzemeltető adminisztrátorok közreműködésével élesítik.

### 3.8 Tesztelési feladatok, teszt-esetek leírása
A tesztelési feladat a következő teszt-eseteket foglalja magában:
- Fejlesztői teszt
- Prototípus (modul)

## 4 Tesztelési ütemterv, függőségek – tesztforgatókönyv

### 4.1 Tesztelési jelentés
A tesztelési jelentést a tesztkoordinátor készíti el. Ez egy részletes áttekintése a lefutott teszteknek, azok eredményeinek, státuszának és a megjegyzéseknek.
A tesztkoordinátor juttatja el a projektmenedzsernek a tesztelési jelentést. 

## 5. Tesztjegyzőkönyv
### 5.1 Tesztelési jegyzőkönyv - 1. Példa

|   |   |
|---|---|
| A teszt-eset leírás és célja:  | A bejelentkezés menüpont tesztelése |
| A tesztelt folyamat/funkció leírása:  | A felület viselkedése hibás felhasználónév / jelszó megadása esetén, megfelelő adatok esetén, illetve többszöri hibás bevitelekor, továbbá új felhasználói fiók regisztrálása sikeres-e.  |
| A tesztelés előfeltételei:  | A programnak rendelkeznie kell minimum egy dummy adatbázissal |
| A tesztelés dátuma és időpontja:  | 2021.11.20. 22:13 |
| A tesztet végző személy(ek):  | Juhász Domonkos |
| A tesztelt rendszer beállításai:  | A program specifikációjában szereplő alap beálítások |
| A teszt-eset elvárt eredménye:  | A specifikációban taglalt viselkedés |
| A tesztelés eredménye:  | **Megfelelt/élesíthető** |
| Megjegyzések:  | -  |

**Tesztelést elvégezte**

|   |   |
|---|---|
|  Név: | Juhász Domonkos |
|  Szervezeti egység/ beosztás: | Adatbázis fejlesztő, Tester |
|  Dátum: | 2021.11.20. 22:13 |

### 5.2 Tesztelési jelentés - 2. Példa
|   |   |
|---|---|
| A hivatkozott tesztjegyzőkönyvek rövid leírása és eredménye:  | Jogosultság tesztelése |
| A tesztelt folyamatok/funkciók/modulok leírása: | Az alkalmazás Jogosultság funkció tesztelése |
| A tesztadatok típusa:  | A programnak rendelkeznie kell minimum egy dummy adatbázissal |
| A tesztelés eredménye:  | Megfelelt/élesíthető |
| Megjegyzések:  | - |

**Tesztelést elvégezte**

|   |   |
|---|---|
|  Név: | Farkas Bálint |
|  Szervezeti egység/ beosztás: | Test manager, Tester |
|  Dátum: | 2021.11.21. 22:05 |

### 5.3 Jóváhagyások

|   |   |
|---|---|
|  Név: | Kurán Bertalan |
|  Szervezeti egység/ beosztás: | Project Manager |
|  Dátum: | 2021.22. 22:13 |

### 6. Unit tesztek



| Sorszám                  |    Név                   |  Dátum     | Funkció leírás  	| Vizsgálat módja/eszköze,részletes leírása	|Elvárt eredmény	|Verzió	|
|----------------|-------------------------------|-----------------------------|-----------------------------|-----------------------------|-----------------------------|-----------------------------|
|T1|Ardó Balázs|2021.10.18|Donate rendszer|Wordpress donate rendszer tesztelése,gomb megnyomása|Az adott illető támogatás összege befolyik a számlára|1.0|
|T2|Farkas Bálint|2021.10.19|Weboldal design|Wordpress weboldal megnyitása|Letisztult oldal megjelenítés|1.0|
|T3|Bodó Zoltán|2021.10.20|Github műkődése|Gitkraken által|Működő képes|1.0|
|T4|Juhász Domonkos|2021.11.21|Adatbázis tesztelése|PHPMYADMIN által|XAMPP által tesztelve|1.0|
|T5|Ardó Balázs|2021.11.22|Adatbázis tesztelése|Függvények tesztelése|Sikeres lefutása a függvénynek|1.0|
|T6|Farkas Bálint|2021.10.23|Donate rendszer|Műküdő képes gombok mellett a paypal rendszer is lefut|Sikeres teljesítés|1.0|
|T7|Juhász Domonkos|2021.11.26|Általános hiba keresés a kódban|Wordpress segítségével|Hibátlan kód|1.0|
|T8|Bodó Zoltán|2021.11.28|Témák kezelése|Wordpress segítségével|Megjelenítése hibátlan|1.0|
|T9|Ardó Balázs|2021.11.01|Admin felület kezelése|Wordpress segítéségével|Működő képes admin felület|1.0|
|T10|Farkas Bálint|2021.11.03|Jogosultsági szintek kezelése|PHPMYADMIN által|Összes jogosultsági szint működő képes|1.0|

### 7.Teszt


|Modul|Név|Időpont|Működik?|
|Bejelentkezés|Ardó Balázs|2021.12.11.|Igen|
|Regisztráció|Ardó Balázs|2021.12.11.|Igen|
|Jogosultsági szint|Ardó Balázs|2021.12.11.|Igen|
|Felhasználó módosítása|Ardó Balázs|2021.12.11.|Igen|
|Jelszó módosítása|Ardó Balázs|2021.12.11.|Igen|
|Elfelejtett felhasználónév/jelszó|Ardó Balázs|2021.12.11.|Igen|
|Profil|Ardó Balázs|2021.12.11.|Igen|
|Donate rendszer|Ardó Balázs|2021.12.11.|Igen|
|Hozzászólások|Ardó Balázs|2021.12.11.|Igen|
|Admin felületek|Ardó Balázs|2021.12.11.|Igen|
|Adatbázis rendszer|Ardó Balázs|2021.12.11.|Igen|
