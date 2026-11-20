# Wide Gate (Walls and gates)

A gate can stand alone or be linked to a second gate and a solid wall. Linked pieces upgrade together but have separate HP.

| Tier | HP | HP with Blueprints | Explosive Walls damage |
| --- | --- | --- | --- |
| 1 | 240 | 360 | 30 |
| 2 | 640 | 960 | 60 |
| 3 | 3,140 | 4,710 | 60 |

## Modifiers

| Modifier | Stat | Multiplier | Target |
| --- | --- | --- | --- |
| [Explosive Walls](../perks/Explosive%20Walls.md) | Knockout blast damage | — | Walls and gates |
| [Any Empire (Town Center IV)](../town-center/Empire%20Armor.md) | Melee damage | 1 + gold / 1,500 | Explosive Walls blast |
| [Empire Blades](../town-center/Empire%20Blades.md) | Melee damage | 1.8 | Explosive Walls blast |
| [Melee Attack](../blacksmith/Melee%20Attack.md) | Melee damage | 1.25 | Explosive Walls blast |
| [Melee Damage](../perks/Melee%20Damage.md) | Melee damage | 1.35 | Explosive Walls blast |
| [Any Empire (Town Center IV)](../town-center/Empire%20Armor.md) | Incoming melee damage | 1,500 / (1,500 + gold) | Targets of melee attacks |
| [Empire Armor](../town-center/Empire%20Armor.md) | Incoming melee damage | 0.66 | Targets of melee attacks |
| [Melee Armor](../blacksmith/Melee%20Armor.md) | Incoming melee damage | 0.76 | Targets of melee attacks |
| [Any Empire (Town Center IV)](../town-center/Empire%20Armor.md) | Incoming ranged damage | 1,500 / (1,500 + gold) | Targets of ranged attacks |
| [Empire Armor](../town-center/Empire%20Armor.md) | Incoming ranged damage | 0.66 | Targets of ranged attacks |
| [Ranged Armor](../blacksmith/Ranged%20Armor.md) | Incoming ranged damage | 0.76 | Targets of ranged attacks |
| [Melee Resistance](../perks/Melee%20Resistance.md) | Melee damage received | 0.76 | Attacks reduced by melee resistance |
| [Ranged Resistance](../perks/Ranged%20Resistance.md) | Ranged damage received | 0.76 | Attacks reduced by ranged resistance |
| [Emergency Repairs](../perks/Emergency%20Repairs.md) | Current HP | — | Living walls and gates |
| [Healing Spirits](../perks/Healing%20Spirits.md) | Healing received | 1.65 | Ruler, troops, heroes and owned buildings |
| [Castle Blueprints](../perks/Castle%20Blueprints.md) | Max HP | 1.5 | Defense Towers, walls and gates |
| [Wall and gate upgrades](Wide%20Gate%20%E2%80%94%20level%202.md) | Max HP | — | — |
| [Explosive Walls](../perks/Explosive%20Walls.md) | Blast radius | — | Walls and gates |
| [Architect's Council](../perks/Architect's%20Council.md) | Town Center unlock tier | — | Dependent Barricades, Heroes’ Quarters, Defense Towers, Mines and gates |

Tier 2 requires Town Center 3; tier 3 requires Town Center 4.

Opens within 5 units for a living ruler or active troop away from home. Clearance 5, check interval 0.33 s, opening time 0.3 s. Tier 1 uses doors; tiers 2 and 3 use bars.

Explosive Walls hits ground and air enemies within 8.5 units of each knocked-out piece. Separate blasts can overlap.

## Craaghelm

**Maps:** Lichtspalt, Grundsteg, Schattengrund, Tiefenlift, Zentrum

Gates open for a living ruler or an allied unit away from home within **5** units, and close when the way clears. The opening animation takes **0.3 s**.

| Level | Health |
| --- | --- |
| I | 240 |
| II | 640 |

Some gates control a group of pieces; interacting with a linked gate upgrades its controlling gate and the attached sections together. Level II is the last upgrade here.

### Modifiers

**only hits flagged for this resistance**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Armor (Craaghelm)](../blacksmith/Melee%20Armor.md#craaghelm) | Incoming melee-channel damage multiplier | 0.76 |
| [Ranged Armor (Craaghelm)](../blacksmith/Ranged%20Armor.md#craaghelm) | Incoming ranged-channel damage multiplier | 0.76 |

**Living, knockback-capable ground enemies on the facing side**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Bunker Mentality (Craaghelm)](../perks/Bunker%20Mentality.md) | Knockout push | Force limit 20; 12 wide, 7 deep |

**Built, living wall or gate**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Emergency Repairs (Craaghelm)](../perks/Emergency%20Repairs.md#craaghelm) | Missing HP transfer | 0.25 of difference from mean every 2 s |

| Modifier | Stat | Value |
| --- | --- | --- |
| [Masonic Secrets (Craaghelm)](../perks/Masonic%20Secrets.md) | Maximum HP per credited day | +0.05 of starting max HP; refill to new max |
| [Garrisoned Gates (Craaghelm)](../perks/Garrisoned%20Gates.md) | Protection radius | 5 units for the initial target search |

**Living and hit by an eligible heal; capped at max HP**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Healing Spirits (Craaghelm)](../perks/Healing%20Spirits.md#craaghelm) | Healing received multiplier | 1.65 |

**Hit uses the matching resistance channel**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Resistance (Craaghelm)](../perks/Melee%20Resistance.md#craaghelm) | Melee-channel incoming damage divisor | 1.3 |
| [Ranged Resistance (Craaghelm)](../perks/Ranged%20Resistance.md#craaghelm) | Ranged-channel incoming damage divisor | 1.3 |

**Survives an attributed hit from a melee-tagged enemy**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Spike Fences (Craaghelm)](../perks/Spike%20Fences.md) | Melee retaliation | 2 direct damage |

**Wounded and still standing**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Royal Spanner (Craaghelm)](../ruler-weapons/Royal%20Spanner.md) | Healing received | 15 HP per throw hit; 24 HP per aura tick |
