# Dwarven Axe (Ruler Weapon, Craaghelm)

Available from the start. Damage type: **melee**.

| Action | Damage or effect | Range | Timing |
| --- | --- | --- | --- |
| Auto: axe swing | 6 HP; 12 HP vs bosses, 13.5 HP vs siege | Ground target within 4; hit radius 3.63 | 0.6 s (10 base HP/s) |
| Ability: charge | Push; take 0.2 of normal damage | 35 units at 30 units/s | 8 s from activation; dash lasts about 1.17 s |
| Counter during charge | 5 HP if the ruler loses HP | Ground enemies within 6 | At most once per 0.5 s |
| Finishing blow | 8 HP–24 HP per ground enemy | Radius 6–12 | At the end of the charge |

Every 0.25 s the charge pushes ground enemies in a 270° arc (radius 10, up to 8 force). Repeat contacts count. The finisher’s multiplier is 0.25 times the contact count, with a minimum of 1. Radius caps at 8 contacts; damage caps at 12.

The auto attack stops during the charge, and slows cannot interrupt it. Flying enemies take no damage from either action. Ruler resistance halves the damage.

## Affects

**During the 1.17 s charge**

| Affects | Stat | Value |
| --- | --- | --- |
| [Ruler (Craaghelm)](Ruler.md#craaghelm) | Incoming damage multiplier | 0.2 |

**When hit, before the target’s own defenses or phase effects**

| Affects | Stat | Value |
| --- | --- | --- |
| [Fafnir the Awoken (Craaghelm)](../enemies/Fafnir%20the%20Awoken.md) · [Lava Golem (Craaghelm)](../enemies/Lava%20Golem.md) · [The Assembler (Craaghelm)](../enemies/The%20Assembler.md) · [The Scrapper (Craaghelm)](../enemies/The%20Scrapper.md) | Base hit with target traits | swing: 12 HP |
| [Gear Grinder (Craaghelm)](../enemies/Gear%20Grinder.md) · [Steam Burster (Craaghelm)](../enemies/Steam%20Burster.md) · [Volley Cart (Craaghelm)](../enemies/Volley%20Cart.md) | Base hit with target traits | swing: 13.5 HP |
| [Overloaded Boiler (Craaghelm)](../enemies/Overloaded%20Boiler.md) | Base hit with target traits | swing: 6.75 HP; counter: 2.5 HP; finisher before contact bonus: 4 HP |

**After the drone starts landing at or below 0.5 of max HP, until it starts taking off**

| Affects | Stat | Value |
| --- | --- | --- |
| [Quarry Drone (Craaghelm)](../enemies/Quarry%20Drone.md) | Axe swing damage | 13.5 HP |

## Modifiers

**matching damage channel**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Attack (Craaghelm)](../blacksmith/Melee%20Attack.md#craaghelm) | Melee-channel damage multiplier | 1.25 |

**equipped weapon only**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Blessed Weaponry (Craaghelm)](../royal-forge/Blessed%20Weaponry.md#craaghelm) | Equipped active cooldown multiplier | 0.6 |
| [Lighter Weaponry (Craaghelm)](../royal-forge/Lighter%20Weaponry.md#craaghelm) | Equipped passive cooldown multiplier | 0.6 |

**ruler-scaled damage, not fixed healing**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Sharper Weaponry (Craaghelm)](../royal-forge/Sharper%20Weaponry.md#craaghelm) | Ruler-scaled damage multiplier | 1.5 |
| [Dwarven Nobility (Craaghelm)](../town-center/Dwarven%20Nobility.md) | Attack amount multiplier | 1.6 |

**Damaging channels; not healing**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Commander Mode (Craaghelm)](../perks/Commander%20Mode.md#craaghelm) | Ruler damage multiplier | 0.4 |

**Damage only; evaluated when the channel reads ruler damage**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Daredevil (Craaghelm)](../perks/Daredevil.md#craaghelm) | Ruler damage multiplier | 1 + 1.15 times missing HP fraction |

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Damage (Craaghelm)](../perks/Melee%20Damage.md#craaghelm) | Melee-channel damage multiplier | 1.35 |

**Starts at 1; damaging channels only**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Warrior Training (Craaghelm)](../perks/Warrior%20Training.md#craaghelm) | Ruler damage multiplier | 2^(completed nights / campaign length) |
