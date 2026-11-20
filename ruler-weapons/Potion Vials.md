# Potion Vials (Ruler Weapon)

| Weapon action | Damage | Cooldown (s) | Type | Range | AoE range |
| --- | --- | --- | --- | --- | --- |
| Auto attack: [Potion throw](#automatic-attack-potion-throw) | 0.1, 1.08 | 2 | ranged | 25 | 4, 4.87 |
| Ability: [Potion burst](#active-ability-potion-burst) | 5 | 18 | melee | 16 | 16 |

## Modifiers

| Modifier | Stat | Multiplier | Target |
| --- | --- | --- | --- |
| [Assassin's Training](../town-center/Assassin's%20Training.md) | Damage | 2.05 | Ruler attacks |
| [Royal Mastery](../town-center/Royal%20Mastery.md) | Damage | 1.75 | Ruler attacks |
| [Royal Training](../town-center/Royal%20Training.md) | Damage | 1.75 | Ruler attacks |
| [Sharper Weaponry](../royal-forge/Sharper%20Weaponry.md) | Damage | 1.5 | Ruler attacks |
| [Any Empire (Town Center IV)](../town-center/Empire%20Armor.md) | Melee damage | 1 + gold / 1,500 | Melee attacks |
| [Empire Blades](../town-center/Empire%20Blades.md) | Melee damage | 1.8 | Melee attacks, including tower oil |
| [Melee Attack](../blacksmith/Melee%20Attack.md) | Melee damage | 1.25 | Melee attacks |
| [Melee Damage](../perks/Melee%20Damage.md) | Melee damage | 1.35 | Melee-scaling attacks |
| [Any Empire (Town Center IV)](../town-center/Empire%20Armor.md) | Ranged damage | 1 + gold / 1,500 | Ranged attacks |
| [Ranged Attack](../blacksmith/Ranged%20Attack.md) | Ranged damage | 1.2 | Ranged attacks |
| [Ranged Damage](../perks/Ranged%20Damage.md) | Ranged damage | 1.25 | Ranged-scaling attacks |
| [Commander Mode](../perks/Commander%20Mode.md) | Ruler damage | 0.4 | Ruler |
| [Daredevil](../perks/Daredevil.md) | Ruler damage | (2.15 − 1.15 · HP fraction) | Ruler |
| [Glass Cannon](../perks/Glass%20Cannon.md) | Ruler damage | 1.8 | Ruler |
| [Warrior Training](../perks/Warrior%20Training.md) | Ruler damage | 2^((night − 1)/108) | Ruler |
| [Ice Magic](../perks/Ice%20Magic.md) | Slow duration | 3 | Slowed enemies |
| [Healing Spirits](../perks/Healing%20Spirits.md) | Healing received | 1.65 | Ruler, troops, heroes and owned buildings |
| [Spell Scroll](../perks/Spell%20Scroll.md) | Ability cooldown | 0.65 | Equipped ruler weapon; dagger maximum cooldown |
| [Assassin's Training](../town-center/Assassin's%20Training.md) | Active cooldown | 0.5 | Ruler |
| [Blessed Weaponry](../royal-forge/Blessed%20Weaponry.md) | Active cooldown | 0.6 | Ruler; dagger uses maximum cooldown |
| [Lighter Materials](../perks/Lighter%20Materials.md) | Auto-attack cooldown | 0.67 | Equipped ruler weapon |
| [Lighter Weaponry](../royal-forge/Lighter%20Weaponry.md) | Passive cooldown | 0.6 | Ruler |
| [Godly Curse](../town-center/Godly%20Curse.md) | Bonus damage | — | Enemy hit by ruler weapon |

## Automatic attack: Potion throw

| Stat | Value | Condition |
| --- | --- | --- |
| Attack interval | 2 s |  |
| Impact damage | 0.1 HP |  |
| Range | 25 |  |
| Target | Wounded ground ally with the lowest HP fraction, then the nearest ground enemy |  |
| Base DPS | 0.05 | Impact only |
| Burn damage | 1.08 HP/tick |  |
| Healing | 3.75 HP/tick |  |
| DPS with every burn tick | 2.75 |  |

| Stat | Value |
| --- | --- |
| Projectile speed | 18 units/s |
| Maximum chase distance | 10,000 |
| Arc factor | 0.3 |
| Arc distance offset | -4 |
| Damage radius | 4 |
| Healing radius | 4.87 |
| Ticks per patch | 5 |
| Tick interval | 0.5 s |
| Patch lifetime | 5 s |

Damage and healing each need a matching target in their radius on impact to start. Later ticks affect current occupants, including flyers in reach. Heals troops and heroes, not the ruler. Locking an enemy overrides ally priority.

### Damage multipliers

| Target | Multiplier | Applies to |
| --- | --- | --- |
| Fast-moving | 0.6 | Burn only |

### Damage by enemy

| Enemy | Patch: damage per tick (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Barrel Knight](../enemies/Barrel%20Knight.md), [Catapult](../enemies/Catapult.md), [Fire Snail](../enemies/Fire%20Snail.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Ghost](../enemies/Ghost.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Quicksling](../enemies/Quicksling.md), [Ram](../enemies/Ram.md), [Slime](../enemies/Slime.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Swordsman](../enemies/Swordsman.md), [Thing](../enemies/Thing.md), [Wasp](../enemies/Wasp.md), [Wind-Boat](../enemies/Wind-Boat.md) | 1.08 |
| [Big Spider](../enemies/Big%20Spider.md), [Bloodwing](../enemies/Bloodwing.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Exploder](../enemies/Exploder.md), [Hunterling](../enemies/Hunterling.md), [Monster Rider](../enemies/Monster%20Rider.md), [Racer](../enemies/Racer.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Wheel](../enemies/Wheel.md) | 0.64 |

## Active ability: Potion burst

| Stat | Value | Condition |
| --- | --- | --- |
| Cooldown | 18 s |  |
| Damage | 5 HP |  |
| Range | 16 |  |
| Target | Around the ruler |  |
| Healing | 50 HP | Ruler, troops and heroes |
| Enemy slow | 6 s |  |
| Damage radius | 16 |  |

Can cast without an enemy. Healing scales with ruler damage and Melee Attack, not self-healing.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Resistant to ruler damage | 0.5 |
| Boss | 2 |

### Damage by enemy

| Enemy | Burst (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Barrel Knight](../enemies/Barrel%20Knight.md), [Big Spider](../enemies/Big%20Spider.md), [Bloodwing](../enemies/Bloodwing.md), [Catapult](../enemies/Catapult.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Fire Snail](../enemies/Fire%20Snail.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Monster Rider](../enemies/Monster%20Rider.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Quicksling](../enemies/Quicksling.md), [Ram](../enemies/Ram.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Swordsman](../enemies/Swordsman.md), [Thing](../enemies/Thing.md), [Wasp](../enemies/Wasp.md), [Wheel](../enemies/Wheel.md), [Wind-Boat](../enemies/Wind-Boat.md) | 5 |
| [Exploder](../enemies/Exploder.md), [Ghost](../enemies/Ghost.md), [Racer](../enemies/Racer.md) | 2.5 |
