```dataview
TABLE WITHOUT ID
  file.link as "Item",
  glory_item_type as "Type",
  glory_cost as "☼",
  keywords as "Keywords",
  range as "Range",
  row["limit"] as "Limit",
  stipulations as "Stipulations"
FROM "Digital Rulebook/Campaign Rules/Glory Items/Items"
WHERE type = "glory-item" AND contains(faction, "Black Grail")
SORT glory_cost ASC, file.name ASC
```