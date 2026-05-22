
**Keywords** для **Armour** применяются только к **Injury Rolls** для модели, носящей этот **Armour** (игнорируй их в остальное время).

> [!warning]
> Иногда **INJURY MODIFIER** для **Armour** или **Shield** указан в таблице **Injury Modifiers** в **Core Rules**, и для полноты повторяется и в **Profile** для **Armour** или **Shield**. В таких случаях будь внимателен — не применяй модификатор больше одного раза.

---
```dataview
TABLE WITHOUT ID
  file.link as "Armour",
  injury_modifier as "Injury Modifier",
  keywords as "Keywords"
FROM "Digital Rulebook/Battlekit/Armour"
WHERE file.name != "Armour"
SORT file.name ASC
```