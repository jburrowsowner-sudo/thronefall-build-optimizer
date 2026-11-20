# Twin Bastions (Ruler Weapon, Craaghelm)

Unlock: beat **Myrkforst**. Damage type: **ranged**.

| Action | Damage or effect | Range | Timing |
| --- | --- | --- | --- |
| Auto: shield bash | 10 HP per enemy; 3 s slow on fast enemies | Ground target within 5; hit radius 5 | 1.67 s (5.99 base HP/s) |
| Ability: brace | Invulnerable; auto attack pauses | Ruler | 3.5 s active, then 15 s cooldown (18.5 s between casts) |
| Shield release | 10 HP–50 HP per enemy | All enemies within 10 | At the end of the shield |

While equipped, the shields reduce incoming hits to 0.5 of normal damage even between uses. Bracing slows movement to 0.3 of normal speed. Hits received **during** the shield charge the release; no hit still counts as one, and 5 hits reach the cap. Ruler resistance halves bash and release damage.

## Affects

**While equipped, outside invulnerability**

| Affects | Stat | Value |
| --- | --- | --- |
| [Ruler (Craaghelm)](Ruler.md#craaghelm) | Incoming damage multiplier | 0.5 |

**While braced**

| Affects | Stat | Value |
| --- | --- | --- |
| [Ruler (Craaghelm)](Ruler.md#craaghelm) | Invulnerability | 3.5 s |

**Caught in a shield bash**

| Affects | Stat | Value |
| --- | --- | --- |
| [Beetles (Craaghelm)](../enemies/Beetles.md) · [Big Beetles (Craaghelm)](../enemies/Big%20Beetles.md) · [Clockwork Dragoon (Craaghelm)](../enemies/Clockwork%20Dragoon.md) · [Gear Grinder (Craaghelm)](../enemies/Gear%20Grinder.md) · [Leap Bot (Craaghelm)](../enemies/Leap%20Bot.md) · [Loot Goblin (Craaghelm)](../enemies/Loot%20Goblin.md) · [Overloaded Boiler (Craaghelm)](../enemies/Overloaded%20Boiler.md) · [Quarry Drone (Craaghelm)](../enemies/Quarry%20Drone.md) · [Small Beetles (Craaghelm)](../enemies/Small%20Beetles.md) · [Steam Centurion (Craaghelm)](../enemies/Steam%20Centurion.md) | Slow duration | 3 s |

**When hit, before the target’s own defenses or phase effects**

| Affects | Stat | Value |
| --- | --- | --- |
| [Overloaded Boiler (Craaghelm)](../enemies/Overloaded%20Boiler.md) | Base hit with target traits | bash: 5 HP; release before hit-count bonus: 5 HP |

**Caught in a shield bash; only the rider released by [Bombard (Craaghelm)](../enemies/Bombard.md)**

| Affects | Stat | Value |
| --- | --- | --- |
| [Piston Lancer (Craaghelm)](../enemies/Piston%20Lancer.md) | Slow duration | 3 s |

## Modifiers

**matching damage channel**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Ranged Attack (Craaghelm)](../blacksmith/Ranged%20Attack.md#craaghelm) | Ranged-channel damage multiplier | 1.2 |

**recovery after bracing; brace duration does not change**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Blessed Weaponry (Craaghelm)](../royal-forge/Blessed%20Weaponry.md#craaghelm) | Equipped active cooldown multiplier | 0.6 |

**equipped weapon only**

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
| [Ranged Damage (Craaghelm)](../perks/Ranged%20Damage.md#craaghelm) | Ranged-channel damage multiplier | 1.25 |

**Starts at 1; damaging channels only**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Warrior Training (Craaghelm)](../perks/Warrior%20Training.md#craaghelm) | Ruler damage multiplier | 2^(completed nights / campaign length) |
