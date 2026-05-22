---
type: keyword
keyword_type: Effect
tags: [keyword]
---

# NEGATE [KEYWORD]

**Тип:** Effect

Модель с **NEGATE** **Keyword** не подвержена эффекту указанного **Keyword**. Например, модель с **NEGATE SHRAPNEL** игнорирует эффект **Keyword** [[SHRAPNEL]].

---

### Встречается в:
```dataview
LIST
FROM [[]]
WHERE file.folder != this.file.folder
SORT file.name ASC
```
