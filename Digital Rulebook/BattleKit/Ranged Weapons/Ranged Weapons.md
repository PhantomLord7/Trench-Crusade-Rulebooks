**Ranged Weapons** можно использовать для совершения **Ranged Attack** (▶ см. [[Combat#^RangedAttacks|Ranged Attacks]]). **Ranged Weapons** нельзя использовать для совершения **Melee Attack** — за исключением случаев, когда в их **Profile** под полем **Range** указано слово **«Melee»**.

![[62.png]]

---

```dataview
TABLE WITHOUT ID
  file.link as "Weapon",
  range as "Range",
  hands as "Hands",
  keywords as "Keywords"
FROM "Digital Rulebook/Battlekit/Ranged Weapons"
WHERE type = "battlekit"
SORT file.name ASC
```
