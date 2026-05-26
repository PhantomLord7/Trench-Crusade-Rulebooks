## Warband Variants

```dataview
TABLE WITHOUT ID
  file.link as "Variant",
  starting_ducats as "Стартовые 👑",
  starting_glory as "Стартовые ☼"
FROM "Warbands of Trench Crusade/The Cult of the Black Grail/Warband Variants"
WHERE type = "warband-variant"
SORT file.name ASC
```

### Variant Battlekit

```dataview
TABLE WITHOUT ID
  file.link as "Battlekit",
  warband_variant as "Variant",
  battlekit_type as "Type",
  (ducats + " 👑") as "👑",
  glory_cost as "☼",
  keywords as "Keywords"
FROM "Warbands of Trench Crusade/The Cult of the Black Grail/Warband Variants"
WHERE type = "battlekit"
SORT warband_variant ASC, ducats ASC, glory_cost ASC
```
