# Automaton (Heroes’ Quarters, Craaghelm)

**Maps:** Myrkforst, Brewerk, Lichtspalt, Grundsteg, Schattengrund, Tiefenlift, Zentrum

One hero per [Hero's Quarter (Craaghelm)](Hero's%20Quarter.md). **HP per unit:** 360 / 720 / 1,440. **Movement speed:** 4. HP and attack amounts are shown in tier 1 / 2 / 3 order.

| Action | Amount per target | Range | Interval |
| --- | --- | --- | --- |
| Ground slam: primary hit | 33 / 66 / 132 | 4.5 | 3 s (2.7–3.3) |
| Ground slam: splash per enemy | 5 / 10 / 20 | 4.5 | 3 s (2.7–3.3) |

The slam strikes one nearby ground enemy and hits a 9.28 by 2.6 by 8.82 box. The primary target takes both amounts if its collider is inside the box. Flyers take neither hit.

Base HP, hit damage, reach and attack interval match [Golem](Golem.md) at tier 1.

**Attack research:** [Melee Attack (Craaghelm)](../blacksmith/Melee%20Attack.md#craaghelm).

## Modifiers

**Wounded, within 15 of a Bootlegger and selected for healing.**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Bootleggers (Craaghelm)](../barracks/Bootleggers.md) | Healing received | 3.5 HP per mug |

**Within 8 of a Shield Bearer holding position; does not stack with another bearer.**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Shield Bearers (Craaghelm)](../barracks/Shield%20Bearers.md) | Incoming damage multiplier | 0.6 |

**only hits flagged for this resistance**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Armor (Craaghelm)](../blacksmith/Melee%20Armor.md#craaghelm) | Incoming melee-channel damage multiplier | 0.76 |
| [Ranged Armor (Craaghelm)](../blacksmith/Ranged%20Armor.md#craaghelm) | Incoming ranged-channel damage multiplier | 0.76 |

**per completed pick**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Attack (Craaghelm)](../blacksmith/Melee%20Attack.md#craaghelm) | Melee-channel damage multiplier | 1.25 |

**by building level; does not scale a separately spawned turret**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Hero's Quarter (Craaghelm)](Hero's%20Quarter.md) | Max HP and own attack multiplier | 1 / 2 / 4 |

**this building only, until dawn**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Boost Hero's Quarter (Craaghelm)](Boost%20Hero's%20Quarter.md) | Respawn speed multiplier | 1.5 |

**while the ruler has a target lock**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Absolute Order (Craaghelm)](../town-center/Absolute%20Order.md) | Supported attack cooldown multiplier | 0.5 |

**while commanded**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Commander (Craaghelm)](../town-center/Commander.md#craaghelm) | Following movement speed multiplier | 1.6 |

**Recruit down; recruitment building standing**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Call to Arms (Craaghelm)](../perks/Call%20to%20Arms.md) | Night replacement rate multiplier | 1.6 |

| Modifier | Stat | Value |
| --- | --- | --- |
| [Parting Gift (Craaghelm)](../perks/Parting%20Gift.md) | Damage returned on knockout | 0.4 of own max HP to the credited attacker |
| [Melee Damage (Craaghelm)](../perks/Melee%20Damage.md#craaghelm) | Melee-channel damage multiplier | 1.35 |
| [Safety Gear (Craaghelm)](../perks/Safety%20Gear.md) | Incoming damage multiplier | 0.85 |
| [Call to Arms (Craaghelm)](../perks/Call%20to%20Arms.md) | Movement speed | 1.3 times normal for 15 s after the building replaces that unit at night |
| [Cobbler (Craaghelm)](../perks/Cobbler.md#craaghelm) | Movement speed multiplier | 1.5 |
| [Safety Gear (Craaghelm)](../perks/Safety%20Gear.md) | Slow | 0.65 of lost movement speed; 0.75 of duration |
| [Commander Mode (Craaghelm)](../perks/Commander%20Mode.md#craaghelm) | Allied attack / heal multiplier | 1.4 |
| [Stronger Heroes (Craaghelm)](../perks/Stronger%20Heroes.md#craaghelm) | Attack / repair multiplier | 1.4 |
| [Hot Springs (Craaghelm)](../perks/Hot%20Springs.md) | Healing | 1.5 HP/s in combat; 4 HP/s after 10 s |
| [Elite Warriors (Craaghelm)](../perks/Elite%20Warriors.md#craaghelm) · [Stronger Heroes (Craaghelm)](../perks/Stronger%20Heroes.md#craaghelm) | Maximum HP multiplier | 1.5 |

**n successful nighttime replacements in its own group**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Experience Gain (Craaghelm)](../perks/Experience%20Gain.md#craaghelm) | Revived unit HP and automatic strength | min(3, 1.06^n) |

**Within the 5-unit search and cylinder of a standing gate**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Garrisoned Gates (Craaghelm)](../perks/Garrisoned%20Gates.md) | Incoming damage multiplier | 0.8 |

**Living and hit by an eligible heal; capped at max HP**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Healing Spirits (Craaghelm)](../perks/Healing%20Spirits.md#craaghelm) | Healing received multiplier | 1.65 |

**At night within 10 of the ruler**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Lead by Example (Craaghelm)](../perks/Lead%20by%20Example.md) | Automatic attack / heal multiplier | 1.3 |

**Hit uses the matching resistance channel**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Resistance (Craaghelm)](../perks/Melee%20Resistance.md#craaghelm) | Melee-channel incoming damage divisor | 1.3 |
| [Ranged Resistance (Craaghelm)](../perks/Ranged%20Resistance.md#craaghelm) | Ranged-channel incoming damage divisor | 1.3 |

**First timed ruler revival**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Ring of Resurrection (Craaghelm)](../perks/Ring%20of%20Resurrection.md#craaghelm) | Revival / current HP | Return at full HP, or fill a wounded survivor |

**While commanded**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Royal Protection (Craaghelm)](../perks/Royal%20Protection.md#craaghelm) | Current and maximum HP multiplier | 2.5 |

**Wounded and still standing**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Royal Spanner (Craaghelm)](../ruler-weapons/Royal%20Spanner.md) | Healing received | 15 HP per throw hit; 24 HP per aura tick |
