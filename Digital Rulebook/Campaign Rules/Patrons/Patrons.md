

Выбери **Patron** для своего **Warband** из этого списка. Твой выбор определяет, какой навык ты можешь выбрать, если выпадет результат **Patron Skill** в любой из **Skill Tables** (▶ см. [[#Promotions and Experience|Promotions and Experience]]).

---
```dataview
TABLE WITHOUT ID
  file.link as "Patron",
  faction_restriction as "Restriction"
FROM "Digital Rulebook/Campaign Rules/Patrons"
WHERE type = "patron"
SORT file.name ASC
```
