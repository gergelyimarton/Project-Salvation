---
tags:
  - moc
  - index
---

# Frakciók és Korporációk

## Korporációk
- [[AURELION]]
- [[VECTRA]]
- [[HELIXA]]
- [[NEUROX]]
- [[LUXORA]]
- [[ECHO LINE MEDIA]]
- [[CIVISYNC]]
- [[SYNDICORE]]
- [[STRATOS DEFENSE SYSTEMS]]
- [[URBITRAE]]
- [[YMANATICS]]
- [[ORIGINS]]

## Underground
- [[Umbra Collective]]
- [[Maffia]]
- [[Black_Inca]]

## Kormányzat
- [[Szenátus]]

---

## Dataview lekérdezések

### Minden frakció
```dataview
TABLE type, status, leader
FROM "03_Factions & Corps"
WHERE file.name != "_Index"
SORT file.name ASC
```

### Aktív korporációk
```dataview
LIST
FROM "03_Factions & Corps"
WHERE type = "corporation" AND status = "active"
```
