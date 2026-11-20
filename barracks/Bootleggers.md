# Bootleggers (Barracks, Craaghelm)

[Barracks (Craaghelm)](Barracks.md) fields **4 / 8 / 12** at tiers 1–3. **HP per unit:** 60. **Movement speed:** 5. Upgrades add fighters, not damage per fighter.

| Action | Amount per target | Range | Interval |
| --- | --- | --- | --- |
| Ground strike | 3.5 | 3.5 | 1 s (0.9–1.1) |
| Mead: healing per ally | 3.5 | 15 | 1 s (0.6–1.4) |

The mug and melee strike have separate cooldowns. Mead goes to the nearest wounded ally in the first eligible group: ruler, then heroes, then other troops. Healers and buildings are excluded. Only the strike benefits from attack research.

**Attack research:** [Melee Attack (Craaghelm)](../blacksmith/Melee%20Attack.md#craaghelm).

## Affects

**Wounded, within 15 of a Bootlegger and selected for healing.**

| Affects | Stat | Value |
| --- | --- | --- |
| [Airship (Craaghelm)](../heroes-quarters/Airship.md) · [Ancestor (Craaghelm)](../ancestral-workshop/Ancestor.md) · [Automaton (Craaghelm)](../heroes-quarters/Automaton.md) · [Axe Throwers (Craaghelm)](../archery-range/Axe%20Throwers.md) · [Axe Wielders (Craaghelm)](Axe%20Wielders.md) · [Grenadiers (Craaghelm)](../archery-range/Grenadiers.md) · [Mad Berserker (Craaghelm)](../ancestral-workshop/Mad%20Berserker.md) · [Ruler (Craaghelm)](../ruler-weapons/Ruler.md#craaghelm) · [Shield Bearers (Craaghelm)](Shield%20Bearers.md) · [Siege Engineer (Craaghelm)](../heroes-quarters/Siege%20Engineer.md) · [Slingers (Craaghelm)](../archery-range/Slingers.md) · [Snipers (Craaghelm)](../archery-range/Snipers.md) · [Soldiers (Craaghelm)](Soldiers.md) · [Technician (Craaghelm)](../heroes-quarters/Technician.md) | Healing received | 3.5 HP per mug |

## Modifiers

**Within 8 of a Shield Bearer holding position; does not stack with another bearer.**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Shield Bearers (Craaghelm)](Shield%20Bearers.md) | Incoming damage multiplier | 0.6 |

**strike only; not healing**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Attack (Craaghelm)](../blacksmith/Melee%20Attack.md#craaghelm) | Melee-channel damage multiplier | 1.25 |
| [Melee Armor (Craaghelm)](../blacksmith/Melee%20Armor.md#craaghelm) | Incoming melee-channel damage multiplier | 0.76 |
| [Ranged Armor (Craaghelm)](../blacksmith/Ranged%20Armor.md#craaghelm) | Incoming ranged-channel damage multiplier | 0.76 |

**while the ruler has a target lock**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Absolute Order (Craaghelm)](../town-center/Absolute%20Order.md) | Supported attack cooldown multiplier | 0.5 |

**while commanded**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Commander (Craaghelm)](../town-center/Commander.md#craaghelm) | Following movement speed multiplier | 1.6 |

**Travelling shots only**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Firearm Drills (Craaghelm)](../perks/Archery%20Skills.md#craaghelm) | Projectile speed multiplier | 1.6 |

**Recruit down; recruitment building standing**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Call to Arms (Craaghelm)](../perks/Call%20to%20Arms.md) | Night replacement rate multiplier | 1.6 |

| Modifier | Stat | Value |
| --- | --- | --- |
| [Pristine Warriors (Craaghelm)](../perks/Pristine%20Warriors.md#craaghelm) | Attack strength multiplier | 1.75 |
| [Parting Gift (Craaghelm)](../perks/Parting%20Gift.md) | Damage returned on knockout | 0.4 of own max HP to the credited attacker |
| [Melee Damage (Craaghelm)](../perks/Melee%20Damage.md#craaghelm) | Melee-channel damage multiplier | 1.35 |
| [Safety Gear (Craaghelm)](../perks/Safety%20Gear.md) | Incoming damage multiplier | 0.85 |
| [Call to Arms (Craaghelm)](../perks/Call%20to%20Arms.md) | Movement speed | 1.3 times normal for 15 s after the building replaces that unit at night |
| [Cobbler (Craaghelm)](../perks/Cobbler.md#craaghelm) | Movement speed multiplier | 1.5 |
| [Safety Gear (Craaghelm)](../perks/Safety%20Gear.md) | Slow | 0.65 of lost movement speed; 0.75 of duration |
| [Commander Mode (Craaghelm)](../perks/Commander%20Mode.md#craaghelm) | Allied attack / heal multiplier | 1.4 |
| [Hot Springs (Craaghelm)](../perks/Hot%20Springs.md) | Healing | 1.5 HP/s in combat; 4 HP/s after 10 s |
| [Elite Warriors (Craaghelm)](../perks/Elite%20Warriors.md#craaghelm) | Maximum HP multiplier | 1.5 |

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

**While holding a veteran title**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Veteran (Craaghelm)](../perks/Veteran.md) | Movement speed multiplier | 1.3 |
| [Veteran (Craaghelm)](../perks/Veteran.md) | Current and maximum HP | +0.7 of recorded starting max HP |

**Wounded and still standing**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Royal Spanner (Craaghelm)](../ruler-weapons/Royal%20Spanner.md) | Healing received | 15 HP per throw hit; 24 HP per aura tick |
