# Exploder (Enemy)

| HP | Speed (units/s) | Attack | Base damage | Cooldown (s) | First eligible night |
| --- | --- | --- | --- | --- | --- |
| 65 | 9 | Melee | 3.5 | 1 | 1 |

**Traits:** fast-moving, reduced ruler damage, monster, siege weapon, exploding.

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

## Proximity detonation

Detonates within 3.5 units of a living player building. Checks every 0.5 s.

## Attack timing

| First attack delay (s) | Minimum interval (s) | Maximum interval (s) | Target check (s) |
| --- | --- | --- | --- |
| 0 | 0.9 | 1.1 | 0.5 |

## Death blast

Radius 6.5; 90 base damage to defenders, 9 to other enemies. One hit per target; wave and elite attack bonuses do not apply.

| Target trait | Blast damage multiplier |
| --- | --- |
| building | 2 |
| ruler | 0.5 |
| town center | 0.5 |
| fire/explosion resistant | 0.33 |

## Attack targets · range 4

| Priority | Target | Excludes |
| --- | --- | --- |
| 1 | Town Center | — |
| 2 | Ruler | — |
| 3 | Any player target | building, ruler, flying |
| 4 | Any player target | flying |

## Damage dealt

| Defender | Direct | Death blast |
| --- | --- | --- |
| Ruler | 3.5 | 45 |
| Longbow, Knight, Hunter, Town center | 3.5 | 90 |
| Berserk | 3.5 | 29.7 |
| Firewing | — | 90 |
| House, Blocking wall, Tower | 3.5 | 180 |

## Movement

| Stopping distance | Ruler chase after hit (s) | Path check interval (s) | Slowed speed (units/s) |
| --- | --- | --- | --- |
| 2 | 0 | 0.5 | 2.97 |

**Movement targets:** Building within 1,000,000 units.

## Wave eligibility

| Group | Movement class | Budget cost | Investment threshold |
| --- | --- | --- | --- |
| Flavour | Small ground | 18 | 0 |

## Damage received

| Attack | Base damage |
| --- | --- |
| Spearman thrust | 4.04 |
| Longbow arrow | 4 |
| Crossbow bolt | 7 |
| Hunter arrow | 7 |
| Basic Defense Tower arrow | 8 |
| Fire Archer ground burn tick | 1.04 |

## Ruler damage

| Weapon | Mode | Attack | Base damage |
| --- | --- | --- | --- |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Auto | Arrow | 1.25 |
| [Bow & Dagger](../ruler-weapons/Bow%20%26%20Dagger.md) | Active | Stab | 2.25 |
| [Light Spear](../ruler-weapons/Light%20Spear.md) | Auto | Thrust | 1.76 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Auto | Swing | 2.00 |
| [Heavy Sword](../ruler-weapons/Heavy%20Sword.md) | Active | Sweep | 3.81 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Auto | Bolt | 1.12 |
| [Lightning Staff](../ruler-weapons/Lightning%20Staff.md) | Active | Delayed strike | 27.5 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Dart | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Auto | Echo on prior marks | 1 |
| [Shadow Codex](../ruler-weapons/Shadow%20Codex.md) | Active | Detonate marks | 27 |
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Auto | Slash | 6.88 |
| [Falchion & Traps](../ruler-weapons/Falchion%20%26%20Traps.md) | Active | Fully charged trap | 34.91 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Impact | 0.1 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Auto | Burn tick | 0.64 |
| [Potion Vials](../ruler-weapons/Potion%20Vials.md) | Active | Pulse | 2.5 |
| [Battle Axe](../ruler-weapons/Battle%20Axe.md) | Auto | Swing | 0.96 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Auto | Opening beam | 0.17 |
| [Blood Wand](../ruler-weapons/Blood%20Wand.md) | Active | Initial drain hit | 10 |
