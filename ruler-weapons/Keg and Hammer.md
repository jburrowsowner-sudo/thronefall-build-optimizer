# Keg and Hammer (Ruler Weapon, Craaghelm)

Unlock: beat **Grundsteg**. Damage type: **melee**.

| Action | Damage or effect | Range | Timing |
| --- | --- | --- | --- |
| Auto: 2-hit combo | 6.88 HP per hit; 13.76 HP vs monsters | Ground target within 5 | 0.6 s between hits; 2 s after the last |
| Ability: place keg | 10 HP per enemy | At the ruler; radius 10 | 4 s between placements; 3 s fuse |

The hammer favors monsters. A boss also takes double hammer damage; both bonuses stack on a monster boss. The pair averages 5.29 HP/s against an ordinary target. The keg pushes with up to 5 force and does not detonate early on contact. Ruler resistance halves either hit.

## Affects

**When hit, before the target’s own defenses or phase effects**

| Affects | Stat | Value |
| --- | --- | --- |
| [Beetles (Craaghelm)](../enemies/Beetles.md) · [Big Beetles (Craaghelm)](../enemies/Big%20Beetles.md) · [Clockwork Dragoon (Craaghelm)](../enemies/Clockwork%20Dragoon.md) · [Clockwork Oliphaunt (Craaghelm)](../enemies/Clockwork%20Oliphaunt.md) · [Fafnir the Awoken (Craaghelm)](../enemies/Fafnir%20the%20Awoken.md) · [Lava Golem (Craaghelm)](../enemies/Lava%20Golem.md) · [Leap Bot (Craaghelm)](../enemies/Leap%20Bot.md) · [Small Beetles (Craaghelm)](../enemies/Small%20Beetles.md) · [Steam Burster (Craaghelm)](../enemies/Steam%20Burster.md) · [Steam Centurion (Craaghelm)](../enemies/Steam%20Centurion.md) · [The Aegis Sentinel (Craaghelm)](../enemies/The%20Aegis%20Sentinel.md) · [The Scarab (Craaghelm)](../enemies/The%20Scarab.md) · [The Scrapper (Craaghelm)](../enemies/The%20Scrapper.md) | Base hit with target traits | hammer hit: 13.76 HP |
| [Overloaded Boiler (Craaghelm)](../enemies/Overloaded%20Boiler.md) | Base hit with target traits | keg: 5 HP |
| [The Assembler (Craaghelm)](../enemies/The%20Assembler.md) | Base hit with target traits | hammer hit: 27.52 HP |

## Modifiers

**matching damage channel**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Attack (Craaghelm)](../blacksmith/Melee%20Attack.md#craaghelm) | Melee-channel damage multiplier | 1.25 |

**equipped weapon only**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Blessed Weaponry (Craaghelm)](../royal-forge/Blessed%20Weaponry.md#craaghelm) | Equipped active cooldown multiplier | 0.6 |

**recovery after the combo, not the gap between hammer hits**

| Modifier | Stat | Value |
| --- | --- | --- |
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
