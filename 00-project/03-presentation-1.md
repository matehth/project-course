---
project_outline: "[[00-project/01-project-outline]]"
---

<!-- 5xl -->
# Kamerás könyvkatalogizáló mobilalkalmazás webes gyűjteménynézettel

Szerző: Horváth Máté  
Neptun: V3ZQEC  
Témavezető: Sári Dávid  
Projektazonosító: 2026-SD-01  

---

## Probléma

- Otthoni könyvgyűjtemény kézi nyilvántartása időigényes
- A gyűjtemény nehezen áttekinthető és kereshető
- Ismételt felvétel nehezen vehető észre
- Cél: gyors, ellenőrizhető felvétel a telefon kamerájával

---

## Célfelhasználók

- Nagy könyvgyűjteménnyel rendelkezők
- Otthoni felhasználás
- Egy felhasználó, egy gyűjtemény
- Könyvek rendszerezése
- Helyi hálózaton futó rendszer

---

## Tervezett hatókör

- Könyvek beolvasása Android-alkalmazással
- Adatok lekérdezése nyilvános adatbázisból
- MI-alapú adatkinyerés a borítófotóból
- Tárolás saját adatbázisban
- Kereshető, szűrhető, szerkeszthető webes gyűjteménynézet

---

## Kezdeti felhasználói utak

- **Beolvasás ISBN-vonalkóddal**
  - Beolvasás, lekérdezés, ellenőrzés, mentés
- **Ha nincs vonalkód**
  - MI-alapú beolvasás vagy kézi bevitel
- **Gyűjtemény kezelése weben**
  - Keresés, szűrés, részletek, módosítás, törlés
- **Megosztás**
  - A gyűjtemény exportálása JSON-fájlba

---

## Következő lépések

- Könyvadatforrások vizsgálata
- Adatmodell véglegesítése
- Vonalkód-beolvasás prototípusa valós készüléken
- Borítófotós MI és OCR összehasonlítása
