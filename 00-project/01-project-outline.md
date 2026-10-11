---
name: Horváth Máté
neptun: V3ZQEC
id: 2026-SD-1
github: https://github.com/matehth/project-course
trello: 
---
# Kamerás könyvkatalogizáló mobilalkalmazás webes gyűjteménynézettel

A projekt egy helyi hálózaton futó és tárolt könyvgyűjteményt valósít meg, amivel a felhasználó a telefonjával tud könyveket beolvasni, eltárolni azokat egy adatbázisban és megtekinteni őket egy webalkalmazásban. A beolvasás a könyv ISBN-vonalkódja alapján történik, ha ez nem lehetséges, akkor kézileg vagy MI segítségével is belehet vinni a könyv adatait. A vonalkód, vagy a bevitt cím és szerző alapján kerül a könyv lekérdezésre egy nyilvános adatbázisból, majd kerül bele a saját adabázisba. A projekt backendje a python alapú FastAPI keretrendszer, amely JSON alapon kommunikál a Jetpack Compose androidos mobilalkalmazással és az Angular-os webalkalmazással.

## Célok

- **Elsődleges cél:** Mobilos beolvasás, adatbázisban tárolás, webes megjelenítés folyamata működik.
- **Célfelhasználók / érintettek:** Otthoni felhasználás.
- **Mérhető sikerkritériumok:** A felhasználó betud olvasni könyveket és egy weboldalon megtudja jeleníteni azokat.
- **Korlátok:** Angular frontend; FastAPI backend; Jetpack Compose mobilalkalmazás; PostgreSQL adatbázis; MI-alapú könyv felismerés.

## Hatókör

### Benne van a hatókörben

- Könyvek beolvasása mobilalkalmazással.
- MI-alapú adatkinyerés a könyv borítójából.
- Nyilvános adatbázisból történő lekérdezés, kiadványegyeztetés.
- PostgreSQL adatbázisban történő tárolás.
- Kereshető, rendezhető webes gyűjteménynézet.

### Nincs benne a hatókörben

- Több felhasználó kezelése.
- Teljes könyvespolc felismerése.

## Jegyzetek

Az első prototípus a fő folyamatra összpontosít: ISBN-vonalkódos beolvasás, külső adatforrásból történő lekérdezés, tárolás PostgreSQL-ben és megjelenítés az Angular webalkalmazásban. A kézi könyvfelvétel az első változattól kezdve működik, így a rendszer külső adatforrás vagy MI-szolgáltatás kiesése esetén is használható.
