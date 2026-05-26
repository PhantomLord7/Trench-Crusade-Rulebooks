---
type: warband-entry
faction: New Antioch
unit_category: Troops
unit_subcategory: The Soldiery of New Antioch
limit_min: 0
limit_max: 2
mandatory: false
cost: 80
movement: 6"/Infantry
ranged: "+0 DICE"
melee: "+1 DICE"
armour: -2
base: 25 мм
keywords:
  - NEW ANTIOCH
  - NEGATE MINED
tags:
  - warband-entry
  - faction/new-antioch
  - troops
---

# Combat Engineers

> [!info] 0-2 Combat Engineers — Cost: 80 👑

*Combat Engineers специализируются на разрушении бункеров, обнаружении минных полей и сооружении полевых укреплений. Облачённые в стальную броню и вооружённые для ближнего боя, они отважно идут на самые опасные участки фронта. Потери среди них исключительно высоки — но они почитают за честь сражаться и гибнуть за New Antioch и Церковь.*

## Profile

| Movement | Ranged | Melee | Armour | Base |
|---|---|---|---|---|
| 6"/Infantry | +0 DICE | +1 DICE | -2 | 25 мм |

## Battlekit

Combat Engineer всегда имеет [[Engineer Body Armour]] (▶ см. [[New Antioch Battlekit]]) и Shovel. Этот Battlekit не может быть снят или потерян в ходе кампании ни по какой причине. Injury Modifier этой Armour уже включён в Profile модели выше. Combat Engineer может брать любой другой Battlekit из New Antioch Armoury Tables, **за исключением Armour**.

## Abilities

☩ **Battlefield Demolition:** Ты можешь игнорировать Effect Keyword **HEAVY** для **1 Satchel Charge**, имеющегося у Combat Engineer. Combat Engineer всё равно не может иметь более **1 Weapon** (любого типа) с Keyword **HEAVY**.

☩ **Set Mine ACTION:** Combat Engineer может совершить **Set Mine ACTION**, если находится в контакте с terrain piece размером до **8" × 8"**, у которого нет Keyword **MINED**. Если он это делает, сделай Success Roll для модели и добавь **+2 DICE** к броску. Если бросок — Failure, ничего не происходит. Если бросок — Success или Critical Success, terrain piece получает Keyword **MINED**.

☩ **Defuse Mine:** Когда ты перемещаешь Combat Engineer в контакт с Marker или terrain piece с Keyword **MINED**, ты можешь объявить, что Combat Engineer пытается обезвредить мину до того, как она детонирует (▶ см. **MINED**). Если ты это делаешь, сделай Risky Success Roll для модели. Если бросок — Failure, мина детонирует, и Activation Combat Engineer заканчивается. Если бросок — Success или Critical Success, мина не детонирует, и Marker или terrain piece теряет Keyword **MINED**. Модель, которая сама установила мину на terrain piece, может обезвредить её автоматически, если переместится в контакт с этим terrain piece (Risky Success Roll не требуется).

☩ **Fortify ACTION:** Combat Engineer может совершить **Fortify ACTION**. Если он это делает, сделай Risky Success Roll для Combat Engineer. Если бросок — Failure, Activation Combat Engineer заканчивается. Если бросок — Success или Critical Success, Combat Engineer получает Keyword **COVER** до тех пор, пока не уйдёт со своей текущей позиции.

## Keywords

NEW ANTIOCH, NEGATE MINED