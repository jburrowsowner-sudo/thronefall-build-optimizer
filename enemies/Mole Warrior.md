# Mole Warrior (Enemy)

| HP | Speed (units/s) | Attack | Base damage | Cooldown (s) | First eligible night |
| --- | --- | --- | --- | --- | --- |
| 60 | 5 | Melee | 5 | 1 | 1 |

**Traits:** tower-vulnerable, humanoid.

## Modifiers

| Modifier | Stat | Multiplier | Target |
| --- | --- | --- | --- |
| [Elite group](../waves/Elite%20enemy.md) | Auto-attack damage | 3 | — |
| [Endless wave difficulty](../waves/Wave%20scaling.md) | Auto-attack damage | 0.5 · (1 + HP multiplier) | — |
| [Ice Magic](../perks/Ice%20Magic.md) | Slow duration | 3 | Slowed enemies |
| [Potion Vials active](../ruler-weapons/Potion%20Vials.md#active-ability-potion-burst) | Slow duration | — | Enemies |
| [Ice Magic](../perks/Ice%20Magic.md) | Speed while slowed | 0.6 | Slowed enemies |
| [Elite group](../waves/Elite%20enemy.md) | Max HP | 4 | — |
| [Endless wave difficulty](../waves/Wave%20scaling.md) | Max HP | wave HP multiplier | — |

## Tunnel

Attacks pause underground. The next tunnel timer starts after emergence.

| Stat | Value |
| --- | --- |
| First tunnel | 3 s |
| Minimum interval | 8 s |
| Maximum interval | 16 s |
| Maximum travel | 30 units |
| Travel speed | 20 units/s |
| Fraction of distance to target | 0.9 |
| Minimum offset | 0 units |
| Maximum offset | 5 units |
| Dig time per end | 0.5 s |

## Attack timing

| First attack delay (s) | Minimum interval (s) | Maximum interval (s) | Target check (s) |
| --- | --- | --- | --- |
| 0 | 0.9 | 1.1 | 0.5 |

## Damage modifiers

| Defender trait | Multiplier |
| --- | --- |
| town center | 0.25 |
| tower | 0.5 |

## Attack targets · range 3

| Priority | Target | Excludes |
| --- | --- | --- |
| 1 | Any player target | building, ruler, flying |
| 2 | Ruler | — |
| 3 | Any player target | flying |

## Damage dealt

| Defender | Direct |
| --- | --- |
| Ruler, Longbow, Knight, Hunter, Berserk, House, Blocking wall | 5 |
| Tower | 2.5 |
| Town center | 1.25 |

## Movement

| Stopping distance | Ruler chase after hit (s) | Path check interval (s) | Slowed speed (units/s) |
| --- | --- | --- | --- |
| 2.9 | 5 | 1 | 1.65 |

## Movement targets

| Priority | Target | Excludes | Range |
| --- | --- | --- | --- |
| 1 | Priority target | flying | 30 |
| 2 | Building | wall | 100 |
| 3 | Any player target | ruler, flying | 100,000 |

## Wave eligibility

| Group | Movement class | Budget cost | Investment threshold |
| --- | --- | --- | --- |
| Flavour | Small ground | 6.33 | 0 |

## Damage received

| Attack | Base damage |
| --- | --- |
| Spearman thrust | 2.02 |
| Longbow arrow | 3.2 |
| Crossbow bolt | 7 |
| Hunter arrow | 2.73 |
| Basic Defense Tower arrow | 16 |
| Fire Archer ground burn tick | 0.69 |

## Ruler damage

| Weapon | Mode | Attack | Base damage |
| --- | --- | --- | --- |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Auto | Arrow | 5 |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Active | Stab | 10 |
| [Light Spear](../ruler-weapons/Light%20Spear.md) | Auto | Thrust | 1.71 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Auto | Swing | 4.00 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Active | Sweep | 7.62 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Auto | Bolt | 2.25 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Active | Delayed strike | 27.5 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Dart | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Echo on prior marks | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Active | Detonate marks | 27 |
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Auto | Slash | 6.88 |
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Active | Fully charged trap | 35 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Impact | 0.1 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Burn tick | 1.08 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Active | Pulse | 5 |
| [Battle Axe](../ruler-weapons/Battle%20Axe.md) | Auto | Swing | 1.14 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Auto | Opening beam | 0.35 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Active | Initial drain hit | 20 |
