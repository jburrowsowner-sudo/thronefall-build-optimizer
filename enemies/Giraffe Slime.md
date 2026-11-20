# Giraffe Slime (Enemy)

| HP | Speed (units/s) | Attack | Base damage | Cooldown (s) | First eligible night |
| --- | --- | --- | --- | --- | --- |
| 30 | 5 | Projectile | 1.5 | 1 | 1 |

**Traits:** monster, natural splash target.

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

## Attack timing

| First attack delay (s) | Minimum interval (s) | Maximum interval (s) | Target check (s) |
| --- | --- | --- | --- |
| 0 | 0.9 | 1.1 | 0.4 |

## Projectile

| Speed (units/s) | Chase distance | Projectile type | Obstruction |
| --- | --- | --- | --- |
| 20 | 16 | blockable enemy projectile | Can hit intervening cover |

## Damage modifiers

| Defender trait | Multiplier |
| --- | --- |
| ranged armor | 0.33 |
| ranged-vulnerable | 1.66 |

**Attack targets:** Any player target within 15 units.

## Damage dealt

| Defender | Direct |
| --- | --- |
| Ruler, Longbow, Berserk, Firewing, House, Blocking wall, Tower, Town center | 1.5 |
| Knight | 0.49 |
| Hunter | 2.49 |

## Movement

| Stopping distance | Ruler chase after hit (s) | Path check interval (s) | Slowed speed (units/s) |
| --- | --- | --- | --- |
| 14 | 3 | 1 | 1.65 |

**Movement targets:** Any player target within 100,000 units; excludes ruler.

## Wave eligibility

| Group | Movement class | Budget cost | Investment threshold |
| --- | --- | --- | --- |
| Core | Small ground | 3.6 | 0 |

## Damage received

| Attack | Base damage |
| --- | --- |
| Spearman thrust | 1.51 |
| Longbow arrow | 4 |
| Crossbow bolt | 15.75 |
| Hunter arrow | 7 |
| Basic Defense Tower arrow | 8 |
| Fire Archer ground burn tick | 0.69 |

## Ruler damage

| Weapon | Mode | Attack | Base damage |
| --- | --- | --- | --- |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Auto | Arrow | 5 |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Active | Stab | 7.5 |
| [Light Spear](../ruler-weapons/Light%20Spear.md) | Auto | Thrust | 1.71 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Auto | Swing | 5.60 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Active | Sweep | 10.67 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Auto | Bolt | 2.25 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Active | Delayed strike | 27.5 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Dart | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Echo on prior marks | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Active | Detonate marks | 27 |
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Auto | Slash | 13.76 |
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Active | Fully charged trap | 46.55 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Impact | 0.1 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Burn tick | 1.08 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Active | Pulse | 5 |
| [Battle Axe](../ruler-weapons/Battle%20Axe.md) | Auto | Swing | 0.86 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Auto | Opening beam | 0.35 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Active | Initial drain hit | 20 |
