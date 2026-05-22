Здесь перечислены правила, регулирующие все **Keywords** в игре. Модель, элемент **Battlekit**, **Marker** или **terrain piece** могут иметь 1 или более **Keywords**. Они определяют основные способности, правила, типы войск и категории урона в игре. **Keywords** появляются в правилах **ЗАГЛАВНЫМИ БУКВАМИ**, чтобы их было легко заметить.

---
```dataview
TABLE WITHOUT ID
  file.link as "Keywords",
  keyword_type as "Keyword Type"
FROM "Digital Rulebook/Keywords Glossary/Keywords"
WHERE type = "keyword"
SORT file.name ASC
```
