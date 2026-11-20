# Dark Warrior (Enemy)

| HP | Speed (units/s) | Attack | Base damage | Cooldown (s) | First eligible night |
| --- | --- | --- | --- | --- | --- |
| 135 | 7 | Melee | 10 | 1 | 1 |

**Traits:** natural splash target, humanoid, fast-moving.

## Modifiers

| Modifier | Stat | Multiplier | Target |
| --- | --- | --- | --- |
| [Elite group](../waves/Elite%20enemy.md) | Auto-attack damage | 3 | — |
| [Endless wave difficulty](../waves/Wave%20scaling.md) | Auto-attack damage | 0.5 · (1 + HP multiplier) | — |
| [Ice Magic](../perks/Ice%20Magic.md) | Slow duration | 3 | Slowed enemies |
| [Light Spear auto](../ruler-weapons/Light%20Spear.md#automatic-attack-spear-thrust) | Slow duration | — | Fast enemies |
| [Potion Vials active](../ruler-weapons/Potion%20Vials.md#active-ability-potion-burst) | Slow duration | — | Enemies |
| [Spearman thrust](../barracks/Spearmen.md) | Slow duration | — | Fast ground enemy |
| [Ice Magic](../perks/Ice%20Magic.md) | Speed while slowed | 0.6 | Slowed enemies |
| [Elite group](../waves/Elite%20enemy.md) | Max HP | 4 | — |
| [Endless wave difficulty](../waves/Wave%20scaling.md) | Max HP | wave HP multiplier | — |

## Attack timing

| First attack delay (s) | Minimum interval (s) | Maximum interval (s) | Target check (s) |
| --- | --- | --- | --- |
| 0 | 0.9 | 1.1 | 0.5 |

## Damage modifiers

| Defender trait | Multiplier |
| --- | --- |
| melee fighter + player unit | 0.5 |

## Attack targets · range 4

| Priority | Target | Excludes |
| --- | --- | --- |
| 1 | Any player target | building, ruler, flying |
| 2 | Ruler | — |
| 3 | Any player target | flying |

## Damage dealt

| Defender | Direct |
| --- | --- |
| Ruler, Longbow, Hunter, House, Blocking wall, Tower, Town center | 10 |
| Knight, Berserk | 5 |

## Movement

| Stopping distance | Ruler chase after hit (s) | Path check interval (s) | Slowed speed (units/s) |
| --- | --- | --- | --- |
| 3.9 | 5 | 1 | 2.31 |

## Movement targets

| Priority | Target | Excludes | Range |
| --- | --- | --- | --- |
| 1 | Priority target | flying | 30 |
| 2 | Building | wall | 100 |
| 3 | Any player target | ruler, flying | 100,000 |

## Wave eligibility

| Group | Movement class | Budget cost | Investment threshold |
| --- | --- | --- | --- |
| Core | Small ground | 11.5 | 0 |

## Damage received

| Attack | Base damage |
| --- | --- |
| Spearman thrust | 4.04 |
| Longbow arrow | 3.2 |
| Crossbow bolt | 7 |
| Hunter arrow | 2.73 |
| Basic Defense Tower arrow | 8 |
| Fire Archer ground burn tick | 0.34 |

## Ruler damage

| Weapon | Mode | Attack | Base damage |
| --- | --- | --- | --- |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Auto | Arrow | 5 |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Active | Stab | 10 |
| [Light Spear](../ruler-weapons/Light%20Spear.md) | Auto | Thrust | 3.52 |
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
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Burn tick | 0.64 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Active | Pulse | 5 |
| [Battle Axe](../ruler-weapons/Battle%20Axe.md) | Auto | Swing | 1.14 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Auto | Opening beam | 0.35 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Active | Initial drain hit | 20 |
