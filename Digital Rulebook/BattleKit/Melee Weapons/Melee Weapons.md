

**Melee Weapons** можно использовать для совершения **Melee Attack** (▶ см. [[#MELEE ATTACKS|Melee Attack]]). **Melee Weapons** нельзя использовать для совершения **Ranged Attack** — за исключением случаев, когда в их **Profile** под полем **Range** указано значение в дюймах.

![[63.png]]

---

```dataview
TABLE WITHOUT ID
  file.link as "Weapon",
  keywords as "Keywords",
  hands as "Hands"
FROM "Digital Rulebook/Battlekit/Melee Weapons"
WHERE type = "battlekit"
SORT file.name ASC
```