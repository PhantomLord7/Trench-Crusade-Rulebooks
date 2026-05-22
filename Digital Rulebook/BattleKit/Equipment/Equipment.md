# Equipment

Если не указано иное, модель может иметь любое количество элементов **Equipment**, но не может иметь один и тот же элемент **Equipment** более одного раза. Например, у модели может быть **Iron Capirote** и **Medi-kit**, но не могут быть два **Iron Capirotes** или два **Medi-kits**.

---
```dataview
TABLE WITHOUT ID
  file.link as "Equipment",
  keywords as "Keywords"
FROM "Digital Rulebook/Battlekit/Equipment"
WHERE type = "battlekit" AND battlekit_type = "equipment"
SORT file.name ASC
```