# Small Spider (Enemy)

| HP | Speed (units/s) | Attack | Base damage | Cooldown (s) | First eligible night |
| --- | --- | --- | --- | --- | --- |
| 12.5 | 15 | Melee | 2.4 | 0.4 | 1 |

**Traits:** monster, natural splash target, fast-moving.

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
| 0 | 0.36 | 0.44 | 0.4 |

## Damage modifiers

| Defender trait | Multiplier |
| --- | --- |
| building | 0.05 |

## Attack targets · range 2.5

| Priority | Target | Excludes |
| --- | --- | --- |
| 1 | Any player target | building, ruler, flying |
| 2 | Ruler | — |
| 3 | Any player target | flying |

## Damage dealt

| Defender | Direct |
| --- | --- |
| Ruler, Longbow, Knight, Hunter, Berserk | 2.4 |
| House, Blocking wall, Tower, Town center | 0.12 |

## Movement

| Stopping distance | Ruler chase after hit (s) | Path check interval (s) | Slowed speed (units/s) |
| --- | --- | --- | --- |
| 2.4 | 5 | 1 | 4.95 |

## Movement targets

| Priority | Target | Excludes | Range |
| --- | --- | --- | --- |
| 1 | Troop | flying | 5 |
| 2 | Economic building | town center | 100,000 |
| 3 | Town Center | — | 100,000 |

## Wave eligibility

| Group | Movement class | Budget cost | Investment threshold |
| --- | --- | --- | --- |
| Core | Small ground | 1.2 | 0 |

## Damage received

| Attack | Base damage |
| --- | --- |
| Spearman thrust | 4.04 |
| Longbow arrow | 4 |
| Crossbow bolt | 7 |
| Hunter arrow | 7 |
| Basic Defense Tower arrow | 8 |
| Fire Archer ground burn tick | 0.34 |

## Ruler damage

| Weapon | Mode | Attack | Base damage |
| --- | --- | --- | --- |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Auto | Arrow | 5 |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Active | Stab | 7.5 |
| [Light Spear](../ruler-weapons/Light%20Spear.md) | Auto | Thrust | 3.52 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Auto | Swing | 4.00 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Active | Sweep | 7.62 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Auto | Bolt | 2.25 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Active | Delayed strike | 27.5 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Dart | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Echo on prior marks | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Active | Detonate marks | 27 |
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Auto | Slash | 13.76 |
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Active | Fully charged trap | 46.55 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Impact | 0.1 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Burn tick | 0.64 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Active | Pulse | 5 |
| [Battle Axe](../ruler-weapons/Battle%20Axe.md) | Auto | Swing | 0.86 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Auto | Opening beam | 0.35 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Active | Initial drain hit | 20 |
