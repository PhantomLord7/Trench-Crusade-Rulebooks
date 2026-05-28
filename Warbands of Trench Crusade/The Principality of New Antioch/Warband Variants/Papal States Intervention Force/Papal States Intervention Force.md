---
type: warband-variant
faction: New Antioch
parent_warband: The Principality of New Antioch
variant_name: Papal States Intervention Force
alignment: Faithful
starting_ducats: 500
starting_glory: 11
tags:
  - warbands
  - faction/new-antioch
  - warband-variant
---

# Papal States Intervention Force

*Papal States, действующие под началом Верховного Понтифика Рима (а не Герцога New Antioch), порой отправляются на передовую для исполнения особых задач: травли и уничтожения опасных предводителей еретиков или возвращения артефактов великой духовной значимости.*

*Такие warbands обычно сравнительно невелики, но имеют доступ к крайне элитным бойцам и специализированному снаряжению. Их ведут беззаветно преданные воины-монахи и священники, отобранные лично Папой.*

## Papal States Intervention Force Special Rules

К Papal States Intervention Force Warband применяются следующие особые правила.

☩ **Far from Home:** Papal States Intervention Force Warband не может включать Trench Moles.

☩ **Lector:** Papal States Intervention Force Warband обязан включать **1 Trench Cleric**, но не может включать Lieutenant. Trench Cleric в Papal States Intervention Force Warband получает Keyword **LEADER** и следующую дополнительную способность:

✦ **Arise and be Healed! ACTION:** Trench Cleric Papal States Intervention Force может совершить **Arise and be Healed! ACTION**. Если он это делает, сделай Risky Success Roll для Trench Cleric. Если бросок — Failure, ничего не происходит, и Activation Trench Cleric заканчивается. Если бросок — Success или Critical Success, выбери Trench Cleric или 1 дружественную модель в пределах **3"** от Trench Cleric. Выбранная модель может встать без затрат на перемещение, и с неё можно убрать до **D3 BLOOD MARKERS** и/или **INFECTION MARKERS**.

☩ **Specialist Force:** Чтобы набрать Papal States Intervention Force Warband для кампании, у тебя есть **500 👑** и **11 ☼** (▶ см. [[Starting a Warband]]). Papal States Intervention Force получает **4 ☼** каждый раз, когда вызывает Reinforcements. В кампании их Threshold Value снижен на **200 👑**. Когда модели набираются как latecomer для кампании или для одиночной игры — после того как согласован размер игры — уменьши количество 👑, которое Papal States Intervention Force Warband имеет на расходы, на **200 👑**, и увеличь количество ☼, которое они имеют на расходы, на **11 ☼**.

☩ **Supreme Blessing:** Когда ты набираешь Papal States Intervention Force Warband, ты должен выдать **Supreme Pontiff's Crucifix** одной модели в Warband. Supreme Pontiff's Crucifix, взятый при создании Warband, выдаётся бесплатно и не стоит никаких ☼ (если он потерян, замену придётся оплачивать обычным порядком).

☩ **Swiss Guard:** Lieutenant и до **4 моделей** в Papal States Intervention Force Warband могут получить Keyword **NEGATE FEAR** без дополнительной платы в 👑.

## Papal States Intervention Force Armoury & Battlekit

Следующие пункты Battlekit доступны Papal States Intervention Force Warband.



```dataview
TABLE WITHOUT ID
  file.link AS "Item",
  battlekit_type AS "Type",
  glory_cost AS "Cost (☼)",
  keywords AS "Keywords",
  stipulations AS "Stipulations"
FROM "Warbands of Trench Crusade/The Principality of New Antioch/Warband Variants/Papal States Intervention Force/Armoury & Battlekit"
WHERE type = "battlekit"
SORT ducats ASC, file.name ASC
```