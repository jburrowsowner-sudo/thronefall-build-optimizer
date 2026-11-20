# Stormcoil (Ruler Weapon, Craaghelm)

Unlock: beat **Lichtspalt**. Damage type: **ranged**.

| Action | Damage or effect | Range | Timing |
| --- | --- | --- | --- |
| Auto: bolt | 5 HP to the target, 2 HP to each previous mark | 17; flyers 20; bosses 26 | 1.5 s (3.33 base HP/s, first hit only) |
| Ability: discharge all marks | 10 HP–30 HP **per mark** | All marked enemies; no distance check | 10 s |

An unmarked enemy is preferred. Each shot damages prior marks before adding its new mark, so hitting the same target again deals 7 HP before resistances. The echo alone deals 4 HP to bosses.

One mark deals 10 HP on discharge; two deal 20 HP each; three or more deal 30 HP each. The discharge clears all marks. Casting with none still spends the cooldown. Ruler resistance halves all three hits.

## Affects

**When hit, before the target’s own defenses or phase effects**

| Affects | Stat | Value |
| --- | --- | --- |
| [Fafnir the Awoken (Craaghelm)](../enemies/Fafnir%20the%20Awoken.md) · [Lava Golem (Craaghelm)](../enemies/Lava%20Golem.md) · [The Assembler (Craaghelm)](../enemies/The%20Assembler.md) · [The Scrapper (Craaghelm)](../enemies/The%20Scrapper.md) | Base hit with target traits | echo: 4 HP |
| [Overloaded Boiler (Craaghelm)](../enemies/Overloaded%20Boiler.md) | Base hit with target traits | bolt: 2.5 HP; echo: 1 HP; discharge per mark before count bonus: 5 HP |

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
