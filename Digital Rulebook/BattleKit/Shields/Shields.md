

**Keywords** для **Shields** применяются только к **Injury Rolls** для модели, использующей этот **Shield** (игнорируй их в остальное время). Эффект **Shield** можно сочетать с эффектом комплекта **Armour**, если не указано иное. **Shield** не блокирует **Line of Sight** к модели, которая его несёт.

---

```dataview
TABLE WITHOUT ID
  file.link as "Shield",
  injury_modifier as "Injury Modifier",
  keywords as "Keywords"
FROM "Digital Rulebook/Battlekit/Shields"
WHERE type = "battlekit"
SORT file.name ASC
```