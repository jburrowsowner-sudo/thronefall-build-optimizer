# Dragon’s Roar (Ruler Weapon, Craaghelm)

Unlock: beat **Brewerk**. Damage type: **ranged**.

| Action | Damage or effect | Range | Timing |
| --- | --- | --- | --- |
| Auto: shot | 15 HP | 25 | 2 s (7.5 base HP/s) |
| Ability: knockback cone | 15 HP close; 3 HP at the edge | 110° in front, range 15 | 8 s |

The blast works without a target. Its 7-unit aim check is **not** its damage range. Targets close to the muzzle take up to 3.5 s of stun and 15 knockback force; both taper toward the edge on enemies that can be pushed. Ruler resistance halves both shot and blast damage.

## Affects

**When hit, before the target’s own defenses or phase effects**

| Affects | Stat | Value |
| --- | --- | --- |
| [Overloaded Boiler (Craaghelm)](../enemies/Overloaded%20Boiler.md) | Base hit with target traits | shot: 7.5 HP; blast at close range: 7.5 HP |

## Modifiers

**matching damage channel**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Ranged Attack (Craaghelm)](../blacksmith/Ranged%20Attack.md#craaghelm) | Ranged-channel damage multiplier | 1.2 |

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
| [Ranged Damage (Craaghelm)](../perks/Ranged%20Damage.md#craaghelm) | Ranged-channel damage multiplier | 1.25 |

**Starts at 1; damaging channels only**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Warrior Training (Craaghelm)](../perks/Warrior%20Training.md#craaghelm) | Ruler damage multiplier | 2^(completed nights / campaign length) |
