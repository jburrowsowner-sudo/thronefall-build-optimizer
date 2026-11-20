# Core Thumper (Ruler Weapon, Craaghelm)

Unlock: beat **Widerhall**. Damage type: **ranged**.

| Action | Damage or effect | Range | Timing |
| --- | --- | --- | --- |
| Auto: grenade | 10 HP per explosion; 33 HP vs siege | 30; blast radius 4 | 4 s (2.5 base HP/s) |
| Ability: three grenades | 10 HP per blast, plus burning ground | Center and ±20°; 30 aim range | 7 s |
| Burning ground | 0.2 HP per tick per patch | Radius 6 | Every 1 s after impact; patch lasts 5 s |

The aiming check has no dead zone. Without a target, the fan aims about 30 units ahead. Each shell pushes with up to 7 force; overlapping blasts can hit the same enemy.

Ruler-resistant targets take 5 HP per blast, or 25.5 HP if also siege. The siege bonus is applied **after** ruler resistance. The burn starts on its first timer tick, not on impact.

## Affects

**When hit, before the target’s own defenses or phase effects**

| Affects | Stat | Value |
| --- | --- | --- |
| [Gear Grinder (Craaghelm)](../enemies/Gear%20Grinder.md) · [Quarry Drone (Craaghelm)](../enemies/Quarry%20Drone.md) · [Steam Burster (Craaghelm)](../enemies/Steam%20Burster.md) · [Volley Cart (Craaghelm)](../enemies/Volley%20Cart.md) | Base hit with target traits | blast per grenade: 33 HP |
| [Overloaded Boiler (Craaghelm)](../enemies/Overloaded%20Boiler.md) | Base hit with target traits | blast per grenade: 25.5 HP; burn per tick: 0.1 HP |

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
