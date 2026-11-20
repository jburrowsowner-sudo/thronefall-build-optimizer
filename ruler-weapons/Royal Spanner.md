# Royal Spanner (Ruler Weapon, Craaghelm)

Unlock: beat **Schattengrund**.

| Action | Damage or effect | Range | Timing |
| --- | --- | --- | --- |
| Auto: wrench throw | 5 HP damage (10 HP vs monsters), or 15 HP healing | 20 first throw; 10 per bounce | 1 s (5 base HP/s, first hit only) |
| Ability: stationary aura | 20 HP damage or 24 HP healing per tick | Radius 10 at cast position | 20 s; immediately, then every 1 s for about 5 s |

The first throw looks for an enemy, then checks the nearest ally. A full-health ally can block a throw to a wounded one behind it. The wrench cannot heal the ruler. Up to 2 more hits follow: a bounce can favor a wounded ally over an enemy or revisit an earlier target, but cannot hit the same recipient twice in a row.

The aura heals the ruler, troops, and structures tagged as walls or towers; it does not repair every building. Neither heal gains ruler or weapon damage bonuses. The throw deals ranged damage; the aura deals melee damage.

The throw adds its monster bonus after ruler resistance: a resistant monster takes 7.5 HP per throw hit.

## Affects

**Standing in the ability’s 10-unit radius**

| Affects | Stat | Value |
| --- | --- | --- |
| [Ruler (Craaghelm)](Ruler.md#craaghelm) | Healing | 24 HP per tick |

**Wounded and still standing**

| Affects | Stat | Value |
| --- | --- | --- |
| [Airship (Craaghelm)](../heroes-quarters/Airship.md) · [Ancestor (Craaghelm)](../ancestral-workshop/Ancestor.md) · [Ancient Cannon (Craaghelm)](../towers/Ancient%20Cannon.md) · [Automaton (Craaghelm)](../heroes-quarters/Automaton.md) · [Axe Throwers (Craaghelm)](../archery-range/Axe%20Throwers.md) · [Axe Wielders (Craaghelm)](../barracks/Axe%20Wielders.md) · [Bootleggers (Craaghelm)](../barracks/Bootleggers.md) · [Defense Tower (Craaghelm)](../towers/Defense%20Tower.md#craaghelm) · [Gate](../walls/Gate.md) · [Grenadiers (Craaghelm)](../archery-range/Grenadiers.md) · [Mad Berserker (Craaghelm)](../ancestral-workshop/Mad%20Berserker.md) · [Shield Bearers (Craaghelm)](../barracks/Shield%20Bearers.md) · [Siege Engineer (Craaghelm)](../heroes-quarters/Siege%20Engineer.md) · [Slingers (Craaghelm)](../archery-range/Slingers.md) · [Snipers (Craaghelm)](../archery-range/Snipers.md) · [Soldiers (Craaghelm)](../barracks/Soldiers.md) · [Technician (Craaghelm)](../heroes-quarters/Technician.md) · [Wall Segment](../walls/Wall%20Segment.md) · [Wide Gate (Craaghelm)](../walls/Wide%20Gate.md#craaghelm) · [Wide Wall (Craaghelm)](../walls/Wide%20Wall.md#craaghelm) | Healing received | 15 HP per throw hit; 24 HP per aura tick |
| [Ancestral Workshop (Craaghelm)](../ancestral-workshop/Ancestral%20Workshop.md) · [Barracks (Craaghelm)](../barracks/Barracks.md) · [Blacksmith (Craaghelm)](../blacksmith/Blacksmith.md#craaghelm) · [Brewery (Craaghelm)](../mills/Brewery.md) · [Castle Center (Craaghelm)](../town-center/Town%20Center.md#craaghelm) · [Dwarven Tunnel (Craaghelm)](../walls/Dwarven%20Tunnel.md) · [Energy Pole (Craaghelm)](../economy/Energy%20Pole.md) · [Hero's Quarter (Craaghelm)](../heroes-quarters/Hero's%20Quarter.md) · [House (Craaghelm)](../economy/House.md#craaghelm) · [Kegs (Craaghelm)](../economy/Kegs.md) · [Marksman's Hall (Craaghelm)](../archery-range/Marksman's%20Hall.md) · [Royal Forge (Craaghelm)](../royal-forge/Royal%20Forge.md#craaghelm) · [Siege Engineer’s Turret (Craaghelm)](../heroes-quarters/Siege%20Engineer%E2%80%99s%20Turret.md) | Healing received | 15 HP per throw hit |

**When hit, before the target’s own defenses or phase effects**

| Affects | Stat | Value |
| --- | --- | --- |
| [Beetles (Craaghelm)](../enemies/Beetles.md) · [Big Beetles (Craaghelm)](../enemies/Big%20Beetles.md) · [Clockwork Dragoon (Craaghelm)](../enemies/Clockwork%20Dragoon.md) · [Clockwork Oliphaunt (Craaghelm)](../enemies/Clockwork%20Oliphaunt.md) · [Gyro Blade (Craaghelm)](../enemies/Gyro%20Blade.md) · [Leap Bot (Craaghelm)](../enemies/Leap%20Bot.md) · [Small Beetles (Craaghelm)](../enemies/Small%20Beetles.md) · [Steam Burster (Craaghelm)](../enemies/Steam%20Burster.md) · [Steam Centurion (Craaghelm)](../enemies/Steam%20Centurion.md) · [The Aegis Sentinel (Craaghelm)](../enemies/The%20Aegis%20Sentinel.md) · [The Assembler (Craaghelm)](../enemies/The%20Assembler.md) · [The Scarab (Craaghelm)](../enemies/The%20Scarab.md) | Base hit with target traits | throw hit: 10 HP |
| [Overloaded Boiler (Craaghelm)](../enemies/Overloaded%20Boiler.md) | Base hit with target traits | throw hit: 7.5 HP; aura tick: 10 HP |

## Modifiers

**aura damage only; healing is unchanged**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Attack (Craaghelm)](../blacksmith/Melee%20Attack.md#craaghelm) | Melee-channel damage multiplier | 1.25 |

**throw damage only; healing is unchanged**

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

**Enemy hits, not healing**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Melee Damage (Craaghelm)](../perks/Melee%20Damage.md#craaghelm) | Aura damage multiplier | 1.35 |

**Enemies only**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Ranged Damage (Craaghelm)](../perks/Ranged%20Damage.md#craaghelm) | Thrown spanner damage multiplier | 1.25 |

**Starts at 1; damaging channels only**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Warrior Training (Craaghelm)](../perks/Warrior%20Training.md#craaghelm) | Ruler damage multiplier | 2^(completed nights / campaign length) |
