---
type: keyword
keyword_type: Effect
tags: [keyword, ammunition]
---

# AMMUNITION (KEYWORD)

**Тип:** Effect

Если у модели есть элемент **Battlekit** с этим **Keyword**, она использует его в следующей партии, в которой участвует. При развёртывании модели объяви, для какого **Ranged Weapon** будет использоваться **Battlekit**. Оружие получает (**KEYWORD**) до конца партии. Выбранный **Ranged Weapon** не должен уже иметь **Keywords** [[BLAST]], [[FIRE]], [[GAS]] или [[SHRAPNEL]], и не может иметь более одного типа **AMMUNITION**.

---

### Встречается в:
```dataview
LIST
FROM [[]]
WHERE file.folder != this.file.folder
SORT file.name ASC
```
