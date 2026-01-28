---
tags:
  - moc
  - index
  - home
---

# Project Salvation

## Navigáció

| Szekció                    | Leírás                                 |
| -------------------------- | -------------------------------------- |
| [[Karakterek]]             | Főszereplők, mellékszereplők, NPC-k    |
| [[A Város]]                | Helyszínek, infrastruktúra, társadalom |
| [[Frakciók és Vállalatok]] | Korporációk, underground szervezetek   |
| [[04_Timeline]]            | Események kronológiája                 |
| [[Archívum]]               | Technológia, rendszerek, háttér        |
| [[06_Books\|Könyvek]]      | Regény fejezetek                       |
| [[08_World\|Világ]]        | Világépítés                            |

---

## Gyors statisztikák

```dataview
TABLE length(rows) AS "Elemszám"
FROM ""
WHERE !contains(file.path, "_Templates") AND !contains(file.path, ".obsidian") AND !contains(file.name, "_Index")
GROUP BY split(file.folder, "/")[0] AS "Szekció"
```

---

## Legutóbb módosított
```dataview
TABLE file.mtime AS "Módosítva"
FROM ""
WHERE !contains(file.path, "_Templates") AND !contains(file.path, ".obsidian")
SORT file.mtime DESC
LIMIT 10
```
