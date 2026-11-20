# Wasp (Enemy)

| HP | Speed (units/s) | Attack | Base damage | Cooldown (s) | First eligible night |
| --- | --- | --- | --- | --- | --- |
| 25 | 8 | Projectile | 2.5 | 1 | 3 |

**Traits:** flying, monster.

## Modifiers

| Modifier | Stat | Multiplier | Target |
| --- | --- | --- | --- |
| [Anti-Air Telescope](../perks/Anti-Air%20Telescope.md) | Auto-attack damage | 0.75 | Flying enemies |
| [Elite group](../waves/Elite%20enemy.md) | Auto-attack damage | 3 | — |
| [Endless wave difficulty](../waves/Wave%20scaling.md) | Auto-attack damage | 0.5 · (1 + HP multiplier) | — |
| [Ice Magic](../perks/Ice%20Magic.md) | Slow duration | 3 | Slowed enemies |
| [Potion Vials active](../ruler-weapons/Potion%20Vials.md#active-ability-potion-burst) | Slow duration | — | Enemies |
| [Ice Magic](../perks/Ice%20Magic.md) | Speed while slowed | 0.6 | Slowed enemies |
| [Anti-Air Telescope](../perks/Anti-Air%20Telescope.md) | Max HP | 0.75 | Flying enemies |
| [Elite group](../waves/Elite%20enemy.md) | Max HP | 4 | — |
| [Endless wave difficulty](../waves/Wave%20scaling.md) | Max HP | wave HP multiplier | — |

## Attack timing

| First attack delay (s) | Minimum interval (s) | Maximum interval (s) | Target check (s) |
| --- | --- | --- | --- |
| 0 | 0.9 | 1.1 | 0.5 |

## Projectile

| Speed (units/s) | Chase distance |
| --- | --- |
| 20 | 12 |

## Damage modifiers

| Defender trait | Multiplier |
| --- | --- |
| ranged armor | 0.4 |

## Attack targets

| Priority | Target | Excludes | Range |
| --- | --- | --- | --- |
| 1 | Economic building | — | 9 |
| 2 | Any player target | wall | 9 |
| 3 | Any player target | — | 13 |

## Damage dealt

| Defender | Direct |
| --- | --- |
| Ruler, Longbow, Hunter, Berserk, Firewing, House, Blocking wall, Tower, Town center | 2.5 |
| Knight | 1 |

## Movement

| Stopping distance | Ruler chase after hit (s) | Path check interval (s) | Slowed speed (units/s) |
| --- | --- | --- | --- |
| 8 | 3 | 2 | 2.64 |

## Movement targets · range 100,000

| Priority | Target | Excludes |
| --- | --- | --- |
| 1 | Economic building | — |
| 2 | Any player target | ruler |

## Wave eligibility

| Group | Movement class | Budget cost | Investment threshold |
| --- | --- | --- | --- |
| Flying | Flying | 5 | 12 |

## Damage received

| Attack | Base damage |
| --- | --- |
| Longbow arrow | 4.8 |
| Crossbow bolt | 7.87 |
| Hunter arrow | 7 |
| Basic Defense Tower arrow | 9.2 |

## Ruler damage

| Weapon | Mode | Attack | Base damage |
| --- | --- | --- | --- |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Auto | Arrow | 10.8 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Auto | Swing | 5.60 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Active | Sweep | 10.67 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Auto | Bolt | 4.5 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Active | Delayed strike | 55 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Dart | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Echo on prior marks | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Active | Detonate marks | 27 |
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Active | Fully charged trap | 46.55 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Burn tick | 1.08 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Active | Pulse | 5 |
| [Battle Axe](../ruler-weapons/Battle%20Axe.md) | Auto | Swing | 0 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Auto | Opening beam | 0.35 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Active | Initial drain hit | 20 |
