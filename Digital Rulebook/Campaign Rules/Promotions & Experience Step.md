
В этом шаге сначала ты можешь попытаться продвинуть (**Promote**) одну или несколько **Troops** в своей **Warband** до статуса **ELITE**, а затем **ELITE** модели могут использовать накопленный **Experience**, чтобы выучить новые **Skills**.

---

## Promotions
^Promotions

В кампании ты можешь продвигать **Troops** в своей **Warband** до статуса **ELITE**, используя следующие правила. **Troops** — это любые модели в твоей **Warband**, не обладающие **Keyword** [[ELITE]].

### The Promotion Pool

Чтобы определить, сколько моделей **Troops** ты можешь попытаться продвинуть, сначала собери **Promotion Dice Pool**. Кубики из этого пула назначаются моделям **Troops** в твоей **Warband**, и если хотя бы один из них выпадает «6», модель получает **Promotion** и обретает **Keyword** [[ELITE]].

Твой **Promotion Dice Pool** состоит из **1D6** плюс **1D6** за каждое **Glorious Deed**, совершённое в ходе сыгранной игры любой моделью из твоей **Warband**. Обрати внимание: **Glorious Deeds** могут быть совершены любой моделью из твоей **Warband**, а не только **Troops**. Кроме того, некоторые **Skills** и **Glory Items** позволяют добавлять дополнительные кубики в **Promotion Dice Pool**.

### Assign Promotion Dice

После того как **Promotion Dice Pool** собран, ты должен распределить кубики из пула между моделями **Troops** в своей **Warband**, которые могут быть продвинуты. Ты не можешь назначить 3-й кубик одной и той же модели, пока все **Troops** в твоей **Warband** не получат хотя бы по 2 кубика, или 4-й кубик — пока все **Troops** не получат хотя бы по 3 кубика, и так далее. Любые нераспределённые **Promotion Dice** теряются.

### Roll Promotion Dice

Затем брось назначенные моделям **Promotion Dice**. Бросай кубики, назначенные одной модели, по одному, в любом выбранном тобой порядке. Как только один из кубиков выпадает «6», прекрати бросать для этой модели и продвинь её — после чего переходи к следующей модели, которой назначены **Promotion Dice**, и так далее. Если ты бросил все назначенные модели кубики и ни один не привёл к **Promotion**, отметь в **Roster**, сколько кубиков подряд ты бросил без получения **Promotion**. Как только общее число достигает 5 кубиков, следующий бросок (6-й) автоматически считается «6».

### Promoting a Model

Когда модель **Troop** получает **Promotion**, она немедленно обретает **Keyword** [[ELITE]] и с этого момента считается **Elite** моделью — в том числе на оставшуюся часть **Promotions & Experience Step**. Вычеркни её старую запись в **Warband Roster** и впиши новую в раздел **Elite Models**. Модель начинает с **0 Experience Points**, но получит как минимум 1 благодаря тому, что пережила игру, после которой была продвинута.

### Maximum Elites

Полностью игнорируй **Promotion Step**, если в твоей **Warband** уже есть 6 или более моделей с **Keyword** [[ELITE]] на начало **Promotions & Experience Phase**, и прекращай бросать **Promotion Dice**, когда успешный **Promotion Roll** означает, что в твоей **Warband** теперь 6 моделей с **Keyword** [[ELITE]].

---

## Experience
^Expirience

После того как все **Promotions** завершены, каждая **ELITE** модель, принявшая участие в игре и пережившая её, получает **1 Experience Point** — даже если она была переведена **Out of Action**. Любая **ELITE** модель, совершившая хотя бы одно **Glorious Deed**, получает второе **Experience Point** (вне зависимости от того, сколько **Glorious Deeds** она совершила).

Записывай **Experience Points**, заработанные **ELITE** моделями твоей **Warband**, в **Roster Sheet**, отмечая по одной клетке опыта за каждое очко — слева направо, начиная с верхнего ряда; когда ты доходишь до клетки в виде круга, ты можешь совершить **Advancement Roll** для этой модели.

> [!example] Пример секции в Roster Sheet
> ```
> Abilities
> ┌──────────────────────┬─────────────────────┐
> │ Movement             │ Ranged              │
> ├──────────────────────┼─────────────────────┤
> │                      │                     │
> └──────────────────────┴─────────────────────┘
> Injuries
> ─────────────────────────────────────────────
> Experience  ☒ ☒ ☒ ◯ ☐ ☐ ☐ ◯ ☐ ☐ ☐ ◯ ☐
> ```
> Квадратные клетки — обычные **Experience Points**. Круглые клетки (◯) обозначают пороги, по достижении которых можно совершить **Advancement Roll**.

---

## Advancement Rolls

Чтобы совершить **Advancement Roll** для модели, выполни следующее:

1. Выбери две из **Skill Tables**, по которым будешь бросать.
2. Брось **2D6** для каждой из выбранных таблиц и сверься с результатом, чтобы узнать, какие **Skills** доступны модели для изучения (▸ см. [[#Skills Tables|Skills Tables]]).
   - a. Если выпадает **Skill**, который у модели уже есть, используй вместо него ближайший по списку **Skill** ниже, которого у модели ещё нет. Если у модели есть все нижние **Skills** из таблицы, используй ближайший выше.
   - b. Если выпадает **Patron Skill**, используй один из **Patron Skills** того **Patron**, которого ты выбрал для своей **Warband** (▸ см. [[Patrons|Patrons]]).
1. Выбери один из двух выпавших **Skills**, который модель выучит, и запиши его за моделью в **Warband Roster**.

> [!warning] Models That Cannot Be Promoted
> Не все модели в твоей **Warband** могут быть продвинуты. Это может быть связано с их природными ограничениями, тем, что они являются машинами, отсутствием доступа к обучению и/или необходимому снаряжению, и так далее.
> Следующие модели не могут быть продвинуты до статуса **ELITE**:
>
> **The Principality of New Antioch**
> —
>
> **Trench Pilgrims**
> Ecclesiastic Prisoners, Anchorite Shrine
>
> **The Sultanate of the Iron Wall**
> —
>
> **Heretic Legions**
> War Wolf Assault Beast, Wretched
>
> **The Cult of the Black Grail**
> Grail Thralls, Fly Thralls, Hounds of the Black Grail, Amalgam
>
> **The Court of the Seven-Headed Serpent**
> Wretched, Yoke Fiends
> ^models-that-cannot-be-promoted


## Melee & Strength Skills Table
^MeleeAndStrengthSkillsTable

| 2D6 | Skill |
|---|---|
| **2** | **Patron Skill:** Выбери один из **Skills**, предлагаемых твоим **Patron**. |
| **3** | **Stand Firm:** Когда модель с этим **Skill** впервые получает результат **Down** в **Injury Table**, он считается результатом **Minor Hit**. |
| **4** | **Parry:** Добавь [[+- DICE\|-1 DICE]] к **Success Rolls** для **Melee Attacks**, нацеленных на модель с этим **Skill**. |
| **5** | **Close Quarters Combat:** Добавь [[+- DICE\|+1 DICE]] и [[+- INJURY DICE\|+1 INJURY DICE]] к броскам **Melee Attacks**, совершаемым моделью с этим **Skill**, если она находится **In Contact** с элементом местности. |
| **6** | **Relentless Charge:** Добавь [[+- DICE\|+1 DICE]] к броскам **Melee Attacks**, совершаемым моделью с этим **Skill**, если она успешно совершила **Charge** ранее в той же **Activation**. |
| **7** | **Melee Proficiency:** Добавь **+1 DICE** к **Melee Characteristic** модели с этим **Skill**. |
| **8** | **Strength of Samson:** Добавь [[+- INJURY DICE\|+1 INJURY DICE]] к броскам **Melee Attacks**, совершаемым моделью с этим **Skill** с использованием **Melee Weapon**. Кроме того, модель с этим **Skill** получает **Keyword** [[STRONG]]. |
| **9** | **Hard as Nails:** Когда модель с этим **Skill** впервые получает результат **Down** в **Injury Table**, он считается результатом **No Effect**. |
| **10** | **Surgical Strike:** Один раз за **Activation**, перед тем как совершить **Injury Roll** для **Melee Attack** моделью с этим **Skill**, ты можешь объявить, что бросок имеет **Keyword** [[IGNORE ARMOUR]]. |
| **11** | **Champion:** **Melee Weapons**, не имеющие **Keyword** [[CLEAVE]], которые используются моделью с этим **Skill**, получают **Keyword** **CLEAVE 2**. Кроме того, добавь [[+- DICE\|-1 DICE]] к **Success Roll** для второй **Melee Attack**, совершённой каждым **Melee Weapon**, получившим **Keyword** [[CLEAVE]]. |
| **12** | **Patron Skill:** Выбери один из **Skills**, предлагаемых твоим **Patron**. |

---

## Ranged Skills Table
^RangedSkillsTable

| 2D6 | Skill |
|---|---|
| **2** | **Patron Skill:** Выбери один из **Skills**, предлагаемых твоим **Patron**. |
| **3** | **Hunter:** **Ranged Attacks**, совершаемые моделью с этим **Skill**, имеют **Keyword** [[IGNORE [MODIFIER]\|IGNORE]] [[COVER]]. |
| **4** | **Gunslinger:** Следующие правила применяются к модели с этим **Skill**, если она вооружена **Ranged Weapons** с **Keyword** [[Digital Rulebook/Battlekit/Ranged Weapons/Pistol]]:<br>✦ Если она вооружена 2 оружиями с **Keyword** [[Digital Rulebook/Battlekit/Ranged Weapons/Pistol]], она может совершить **Shoot** **ACTION** одним из них и сразу же совершить **Shoot** **ACTION** другим.<br>✦ Добавь **Keywords** [[ASSAULT]] и **IGNORE OFF-HAND WEAPON** ко всем оружиям с **Keyword** [[Digital Rulebook/Battlekit/Ranged Weapons/Pistol]] (если у них этих **Keywords** ещё нет). |
| **5** | **Far Shot:** Добавь **6"** к **Range** следующих оружий, когда они используются моделью с этим **Skill**:<br>✦ Любое оружие с **Keyword** [[Digital Rulebook/Battlekit/Ranged Weapons/Pistol]].<br>✦ Любое оружие, в названии которого присутствует слово «**Rifle**» (например, **Bolt-Action Rifle**, **Assault Rifle** и т.д.).<br>✦ Любое оружие, в названии которого присутствует слово «**Jezzail**» или «**Arquebus**». |
| **6** | **Sharp Eyes:** **Ranged Attacks**, совершаемые моделью с этим **Skill**, имеют **Keyword** **IGNORE LONG RANGE**. |
| **7** | **Ranged Proficiency:** Добавь **+1 DICE** к **Ranged Characteristic** модели с этим **Skill**. |
| **8** | **Sniper's Nest:** Добавь [[+- DICE\|+2 DICE]] к броскам **Ranged Attacks**, совершаемых моделью с этим **Skill** с модификатором **Elevated Position**, вместо **+1 DICE**. |
| **9** | **Point Blank:** Когда модель с этим **Skill** совершает **Melee Attack**, она может использовать **Ranged Weapon** и её **Ranged Attack Characteristic** вместо **Melee Weapon** и её **Melee Attack Characteristic**. Для совершения атаки модель по-прежнему должна находиться в пределах **1"** от целевой модели. Кроме того, она может использовать это **Ranged Weapon** для совершения **Ranged Attack** в ту же **Activation**, если у оружия есть **Keyword** [[ASSAULT]]. |
| **10** | **Hip Shot:** **Ranged Weapons**, используемые моделью с этим **Skill**, считаются обладающими **Keyword** [[ASSAULT]], если у них его ещё нет. |
| **11** | **Headshot:** **Ranged Attacks**, совершаемые моделью с этим **Skill**, имеют **Keyword** [[IGNORE ARMOUR]], если атака была **Critical Success**. |
| **12** | **Patron Skill:** Выбери один из **Skills**, предлагаемых твоим **Patron**. |

---

## Stealth & Speed Skills Table
^StealthAndSpeedSkillsTable

| 2D6 | Skill |
|---|---|
| **2** | **Patron Skill:** Выбери один из **Skills**, предлагаемых твоим **Patron**. |
| **3** | **Sixth Sense:** Если модель с этим **Skill** получает результат **Down** в **Injury Table**, он считается результатом **Minor Hit**, при условии что у модели нет ни одного [[BLOOD MARKER\|BLOOD MARKERS]]. Если у модели также есть **Keyword** [[TOUGH]], она может один раз за игру использовать этот **Keyword**, чтобы изменить результат **Out of Action** на результат **Down**, и затем использовать этот **Skill**, чтобы изменить результат **Down** на **No Effect**. |
| **4** | **Assassinate:** Добавь [[+- DICE\|+1 DICE]] к броскам атак, совершаемых моделью с этим **Skill**, если цель ещё не была **Activated** в этот **Turn**. |
| **5** | **Shadow Walker:** Добавь [[+- DICE\|-2 DICE]] к броскам **Ranged Attacks**, нацеленных на модель с этим **Skill** на **Long Range**, вместо **-1 DICE**. |
| **6** | **Athletic:** Добавь [[+- DICE\|+1 DICE]] к **Risky Success Rolls** модели с этим **Skill**, когда она совершает **Climbs**, **Jumps** или **Diving Charge**, и добавь [[+- INJURY DICE\|-1 INJURY DICE]] к **Injury Rolls**, если она совершает **Falls**. |
| **7** | **Sprinter:** Добавь [[+- DICE\|+1 DICE]] к **Risky Success Roll** модели с этим **Skill**, когда она совершает **Dash** **ACTION**. |
| **8** | **Disengage:** Вражеские модели не могут совершать **Melee Attack** против модели с этим **Skill**, когда она совершает **Retreat**. |
| **9** | **Incoming:** Когда ты бросаешь **Charge Bonus** для модели с этим **Skill**, брось **1 дополнительный D6** и используй один наивысший кубик для определения бонуса. |
| **10** | **Nimble:** Не дели на 2 **Movement Characteristic** модели с этим **Skill**, когда она встаёт. |
| **11** | **Dodge:** Добавь [[+- DICE\|-1 DICE]] к броскам **Ranged Attacks**, нацеленных на модель с этим **Skill**. |
| **12** | **Patron Skill:** Выбери один из **Skills**, предлагаемых твоим **Patron**. |

---

## Wildcard Skills Table
^WildcardSkillsTable

| 2D6    | Skill                                                                                                                                                                                                                                                                                                                                                                        |
| ------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **2**  | **Patron Skill:** Выбери один из **Skills**, предлагаемых твоим **Patron**.                                                                                                                                                                                                                                                                                                  |
| **3**  | **War-Luck:** Модель с этим **Skill** может получить 1 дополнительный **Battle Scar** прежде, чем будет признана **Unfit for Duty**.                                                                                                                                                                                                                                         |
| **4**  | **'Tis But a Scratch:** Ты можешь перебросить результат в **Trauma Table** (▸ см. [[Trauma Step]]) для модели с этим **Skill**.                                                                                                                                                                                                                                              |
| **5**  | **Bad Company:** Модель с этим **Skill** не учитывается в количестве моделей с **Keyword** [[ELITE]] в твоей **Warband** на начало **Promotion Step**.                                                                                                                                                                                                                       |
| **6**  | **Scavenger:** Модель с этим **Skill** обладает **Exploration Skill** **Extra Dice** (▸ см. [[Exploration Skills]]).                                                                                                                                                                                                                                                         |
| **7**  | **Skill & Expertise:** Когда ты даёшь модели этот **Skill**, выбери **1 ACTION** из **Warband Entry** этой модели или **1 Common ACTION**, отличную от **Fight** или **Shoot** **ACTIONS**, и запиши её в **Warband Roster**. Добавь [[+- DICE\|+1 DICE]] к броскам, совершаемым в рамках выбранной **ACTION**, когда её предпринимает эта модель.                           |
| **8**  | **Show Off:** Добавь 1 кубик в **Promotion Pool** во время **Promotion Step** за каждую модель в твоей **Warband** с этим **Skill** (▸ см. [[#Promotions\|Promotions]]).                                                                                                                                                                                                     |
| **9**  | **Friends In High Places:** Модель с этим **Skill** обладает **Exploration Skill** **Re-roll Dice** (▸ см. [[Exploration Skills]]).                                                                                                                                                                                                                                          |
| **10** | **Glory Hound:** В конце каждой игры твоя **Warband** получает 1 дополнительное ☼ за каждую модель с этим **Skill**, находящуюся на поле боя.                                                                                                                                                                                                                                |
| **11** | **War Stories:** Когда ты записываешь **Experience Points**, заработанные моделями твоей **Warband** в **Campaign Phase**, ты можешь дать каждой модели с **Keyword** [[ELITE]], у которой нет этого **Skill**, **+1** дополнительное **Experience Point**. Ты не можешь выбрать саму модель с этим **Skill**. В **Warband** может быть только одна модель с этим **Skill**. |
| **12** | **Patron Skill:** Выбери один из **Skills**, предлагаемых твоим **Patron**.                                                                                                                                                                                                                                                                                                  |

> [!warning] Limited Potential
> У некоторых моделей ограниченная способность получать **Experience** и изучать новые **Skills**. Они могут быть слишком звероподобны, обладать ограниченным разумом или иметь сверхъестественно ограниченный предел возможностей. Следующие модели не могут иметь более **7 Experience Points**.
>
> **The Principality of New Antioch**
> —
>
> **Trench Pilgrims**
> Communicant
>
> **The Sultanate of the Iron Wall**
> Lion of Jabir, Brazen Bull, Homunculi (House of Wisdom)
>
> **Heretic Legions**
> Artillery Witch
>
> **The Cult of the Black Grail**
> —
>
> **The Court of the Seven-Headed Serpent**
> Pit Locust, Desecrated Saint
> ^limited-potential