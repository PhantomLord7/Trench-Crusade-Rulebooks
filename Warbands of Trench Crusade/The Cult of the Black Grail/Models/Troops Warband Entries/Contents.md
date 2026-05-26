```dataview
TABLE WITHOUT ID
  file.link as "Unit",
  cost as "👑",
  limit_min + "-" + limit_max as "Limit",
  movement as "Move",
  ranged as "Ranged",
  melee as "Melee",
  armour as "Armour"
FROM "Warbands of Trench Crusade/The Cult of the Black Grail/Models/Troops Warband Entries"
WHERE type = "warband-entry"
SORT cost ASC
```