# Flying Mage (Enemy)

| HP | Speed (units/s) | Attack | Base damage | Cooldown (s) | First eligible night |
| --- | --- | --- | --- | --- | --- |
| 45 | 7 | Projectile | 2 | 2 | 3 |

**Traits:** flying, humanoid.

## Modifiers

| Modifier | Stat | Multiplier | Target |
| --- | --- | --- | --- |
| [Anti-Air Telescope](../perks/Anti-Air%20Telescope.md) | Auto-attack damage | 0.75 | Flying enemies |
| [Elite group](../waves/Elite%20enemy.md) | Auto-attack damage | 3 | — |
| [Endless wave difficulty](../waves/Wave%20scaling.md) | Auto-attack damage | 0.5 · (1 + HP multiplier) | — |
| [Support Mage interception](../heroes-quarters/Support%20Mage.md) | Projectiles intercepted | — | Nearest magic projectile |
| [Ice Magic](../perks/Ice%20Magic.md) | Slow duration | 3 | Slowed enemies |
| [Potion Vials active](../ruler-weapons/Potion%20Vials.md#active-ability-potion-burst) | Slow duration | — | Enemies |
| [Ice Magic](../perks/Ice%20Magic.md) | Speed while slowed | 0.6 | Slowed enemies |
| [Anti-Air Telescope](../perks/Anti-Air%20Telescope.md) | Max HP | 0.75 | Flying enemies |
| [Elite group](../waves/Elite%20enemy.md) | Max HP | 4 | — |
| [Endless wave difficulty](../waves/Wave%20scaling.md) | Max HP | wave HP multiplier | — |

## Attack timing

| First attack delay (s) | Minimum interval (s) | Maximum interval (s) | Target check (s) |
| --- | --- | --- | --- |
| 0 | 1.8 | 2.2 | 1 |

## Projectile

| Speed (units/s) | Chase distance | Projectile type |
| --- | --- | --- |
| 15 | 22 | magic projectile |

## Damage modifiers

| Defender trait | Multiplier |
| --- | --- |
| ranged armor | 0.5 |
| ranged-vulnerable | 1.5 |
| town center | 0.5 |

## Impact pulse

One immediate hit for 3 base damage in a 3.25-unit radius. The area lasts 4 s but does not hit again. Scales with the projectile’s damage. The primary target can take both hits.

| Defender trait | Impact damage multiplier |
| --- | --- |
| siege weapon | 2 |
| building | 0.5 |
| ranged-vulnerable | 1.5 |
| ranged armor | 0.75 |
| fire/explosion resistant | 0.25 |

## Attack targets · range 17

| Priority | Target | Excludes |
| --- | --- | --- |
| 1 | Troop | — |
| 2 | Priority target | — |
| 3 | Any player target | wall |
| 4 | Any player target | — |

## Damage dealt

| Defender | Direct | Impact area |
| --- | --- | --- |
| Ruler, Longbow, Firewing | 2 | 3 |
| Knight | 1 | 2.25 |
| Hunter | 3 | 4.5 |
| Berserk | 2 | 0.75 |
| House, Blocking wall, Tower | 2 | 1.5 |
| Town center | 1 | 1.5 |

## Movement

| Stopping distance | Ruler chase after hit (s) | Path check interval (s) | Slowed speed (units/s) |
| --- | --- | --- | --- |
| 15 | 3 | 2 | 2.31 |

## Movement targets

| Priority | Target | Excludes | Range |
| --- | --- | --- | --- |
| 1 | Troop | — | 25 |
| 2 | Priority target | — | 50 |
| 3 | Any player target | ruler, wall | 100,000 |
| 4 | Any player target | ruler | 100,000 |

## Wave eligibility

| Group | Movement class | Budget cost | Investment threshold |
| --- | --- | --- | --- |
| Flying | Flying | 8.5 | 12 |

## Damage received

| Attack | Base damage |
| --- | --- |
| Longbow arrow | 3.84 |
| Crossbow bolt | 7.87 |
| Hunter arrow | 1.36 |
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
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Active | Fully charged trap | 35 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Burn tick | 1.08 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Active | Pulse | 5 |
| [Battle Axe](../ruler-weapons/Battle%20Axe.md) | Auto | Swing | 0 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Auto | Opening beam | 0.35 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Active | Initial drain hit | 20 |
