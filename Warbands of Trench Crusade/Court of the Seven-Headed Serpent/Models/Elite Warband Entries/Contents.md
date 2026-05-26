```dataview
TABLE WITHOUT ID
  file.link as "Unit",
  cost as "👑",
  limit_min + "-" + limit_max as "Limit",
  movement as "Move",
  ranged as "Ranged",
  melee as "Melee",
  armour as "Armour"
FROM "Warbands of Trench Crusade/Court of the Seven-Headed Serpent/Models/Elite Warband Entries"
WHERE type = "warband-entry"
SORT cost ASC
```