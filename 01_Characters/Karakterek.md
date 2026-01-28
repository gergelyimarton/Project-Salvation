---
tags:
  - moc
  - index
---

# Karakterek

## Főszereplők
- [[Emiko Narukami]]
- [[Jüra]]
- [[Null]]

## Mellékszereplők
- [[Mirko Stanić]]
- [[Anya]]
- [[Afar]]

## NPC-k
- [[Ivan]]

---

## Dataview lekérdezések

### Minden karakter
```dataview
TABLE status, faction, first_appearance
FROM "01_Characters"
WHERE file.name != "_Index"
SORT file.name ASC
```

### Élő karakterek
```dataview
LIST
FROM "01_Characters"
WHERE status = "alive" AND file.name != "_Index"
```
