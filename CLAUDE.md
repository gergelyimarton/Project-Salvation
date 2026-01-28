# Project Salvation — Claude utasítások

Ez a fájl a projekt-specifikus szabályokat tartalmazza.
**Olvasd el minden alkalommal, amikor a vault-tal dolgozol.**

---

## Alapelv

A projekt egy **cyberpunk regény** világépítési anyaga.
Minden változtatásnak **konzisztensnek** kell lennie a meglévő lore-ral, karakterekkel és idővonallal.

---

## Fejezet feldolgozás

Amikor új fejezetet írok vagy módosítok (`06_Books/`):

### 1. Karakterek
- **Új karakter** megjelenésekor:
  - Hozz létre fájlt: `01_Characters/` megfelelő almappájába
  - Használd a `_Templates/Character.md` sablont
  - Töltsd ki a frontmatter-t (tags, status, faction, first_appearance)
  - Írd le amit a fejezetből megtudtunk róla
- **Meglévő karakter** új információja esetén:
  - Frissítsd a karakter fájlját az új részletekkel

### 2. Helyszínek
- **Új helyszín** megjelenésekor:
  - Hozz létre fájlt: `02_City/Locations/`
  - Használd a `_Templates/Location.md` sablont
- **Meglévő helyszín** bővítése:
  - Frissítsd a leírást

### 3. Frakciók / Szervezetek
- **Új frakció** esetén:
  - Hozz létre fájlt: `03_Factions & Corps/`
  - Használd a `_Templates/Faction.md` sablont

### 4. Lore / Technológia
- **Új technológia, rendszer, fogalom** esetén:
  - Hozz létre fájlt: `05_Lore/`
  - Használd a `_Templates/Lore.md` sablont

### 5. Idővonal
- Ha a fejezetben **konkrét dátum vagy esemény** szerepel:
  - Ellenőrizd az `04_Timeline/` mappát
  - Szükség esetén frissítsd vagy bővítsd

### 6. Wikilinkelés
- A fejezetek prózáját **NE módosítsd** wikilink hozzáadásával
- A worldbuilding fájlokban (karakterek, helyszínek, stb.) **IGEN**

---

## Konzisztencia ellenőrzés

Minden fejezet után ellenőrizd:

| Kérdés | Teendő |
|--------|--------|
| Van új karakter? | → Új fájl + leírás |
| Van új helyszín? | → Új fájl + leírás |
| Változott egy karakter státusza? | → Frissítsd (alive/dead/unknown) |
| Ellentmondás a lore-ral? | → Jelezd nekem |

---

## Tiltott műveletek

- **NE módosítsd** a fejezetek szövegét engedély nélkül
- **NE törölj** meglévő tartalmat
- **NE találj ki** információt ami nincs a fejezetben

---

## Kérdés esetén

Ha bizonytalan vagy:
- Kérdezz inkább, minthogy hibás adatot adj hozzá
- Jelezd ha ellentmondást találsz

---

## Hasznos linkek

- [[Dashboard]] — Fő navigáció
- [[Karakterek]] — Karakter lista
- [[A Város]] — Helyszínek
- [[Frakciók és Vállalatok]] — Szervezetek
- [[Archívum]] — Lore és technológia
