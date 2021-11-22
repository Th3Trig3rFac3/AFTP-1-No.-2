# Rendszertervek

## 1. Rendszer célja

- A rendszer célja a művésznek való  munkájának  megkönnyítése és annak zenéit eljutatni az emberekhez ez által a művészt támogatva
- A program egy web alapú felületen fut, ami egy adatbázishoz van kapcsolva
- Navigációs menün keresztül lehet egyes pontokba eljutni a rendszerben
- A program célja, hogy a művésznek segítsünk valamiféle bevételi forráshoz

## 2. Projekt terv
Projekt szerepkörök, felelősségek

| Szerepkör | Személy|
|---|:-|
| -   Product owner:  | Tajti Tibor |
| - Senior fejlesztők: | Kurán Bertalan, Zsadányi Rózsa |
|    - Junior fejlesztők: | Farkas Bálint, Juhász Domonkos, Ardó Balázs, Bodó Zoltán |
##
|  Felelőségek  |  |
|---|:-|
| Senior fejlesztő: | A junior fejlesztők munkájának felügyelete és megkönnyítése tanácsadás által, segíthetnek kisebb projektelemek elkészítésében is. |
| Junior fejlesztő: | A projekt elkészítése. Projekt munkások és felelősségeik |

**Projekt munkások és felelősségeik**

   Webfelület:
-   Wordpress
-   php
## 3. Üzleti folyamatok modellje

## 4. Követelmények

- Funkcionális
	- Webes környezetben való működés
	- A foglalások és az ehhez tartozó adatok tárolása
        - C# környezetben való működés
	- Wordpress környezetben való működés
 - Nem funkcionális
	- Gyors működés, foglalások kilistázása
	- Egyszerű, egyértelmű kezelés
 - Törvényi előírások, szabványok
	- GDPR követelményeinek való megfelelés

## 5. Funkcionális terv

- Rendszerszereplők
  - Admin
  - User
  
- Rendszerhasználati esetek és lefutásaik:
  - Admin
    * Adatok megtekintése
    * Adatok hozzáadása, törlése, módosítása
    * A rendszerhez való teljes hozzáférés

- Menü hierarchiák
  - Kezdőlap
    * Zenék megtekintése és meghallgatása, letöltése
    * A művész által közéttet, irományok, hírek

## 6. Fizikai környezet

Kliens:
   - Eszköz: Asztali számítógép, Mobil telefon, Tablet

  -  Operációs rendszer: Windows 7 vagy nagyobb

    - Szükséges applikációk: Chrome böngésző

    - Konfiguráció: Nem specifikus.

zerver:

- Eszköz: Kliens

- Specifikáció: Klienssel ekvivalens

- Operációs rendszer: Windows 7 vagy nagyobb
 
## 7. Absztrakt domain modell
A program működése során a raktáros egy féle szerepkörben figyelhető meg. A raktáros képes polcokat foglalni, számlát kiállítani, illetve termékeket regisztrálni az adatbázisba.

## 8. Architekturális terv
- Backend
	A rendszerhez szükség van egy adatbázis szerverre, ebben az esetben MySql-t használunk.
	A kliensekkel JSON objektumokkal kommunikál.
 - Frontend
	Az alkalmazás C#-ban,windows form keret rendszerrel készül.

## 9. Adatbázis terv
A zenei szolgáltatáshoz készül egy adatbázis ahol tároljuk a felhasználok adait.

## 10. Implementációs terv
Ezeket a technológiákat amennyire csak lehet külön fájlokba írva készítjük, és úgy fogjuk egymáshoz csatolni a jobb átláthatóság, könnyebb változtathatóság, és könnyebb bővítés érdekében.

## 11. Tesztterv

A user avagy vendég teszteket a fejlesztés végén végezzük el a funkciók kipróbálásával és dokumentálásával. Konténerizált szerverrel.

## 12. Telepítési terv

- A rendszer beüzemelésekor ajánlott egy hozzá szakértő emberre bízni a beüzemelést mivel a szerver elindításához szükség van némi hozzáértéshez.
	Így elkerülve esetleges nem kívánatos hibák létre jöttét.
  Az alkalmazás futtatásához egy általános felhasználású böngészőre van szükség.
  Az alkalmazás eléréséhez regisztrációra van szükség, melybe később be kell jelentkezni, ez az adat tárolódik, a későbbi felhasználás esetére.

## 13. Karbantartási terv

-Az alkalmazás folyamatos üzemeltetése és karbantartása, mely
magában foglalja a programhibák elhárítását, a belső igények változása miatti
módosításokat, valamint a környezeti feltételek változása miatt
megfogalmazott program-, illetve állomány módosítási igényeket.

**Karbantartás:**
- Corrective Maintenance: A felhasználók által felfedezett és "user reportban"
elküldött hibák kijavítása.
- Adaptive Maintenance: A program naprakészen tartása és finomhangolása.
- Perfective Maintenance: A szoftver hosszútávú használata érdekében végzett
módosítások, új funkciók, a szoftver teljesítményének és működési
megbízhatóságának javítása.
- Preventive Maintenance: Olyan problémák elhárítása, amelyek még nem
tűnnek fontosnak, de később komoly problémákat okozhatnak.