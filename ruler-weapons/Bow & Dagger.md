# Bow & Dagger (Ruler Weapon)

| Weapon action | Damage | Cooldown (s) | Type | Range |
| --- | --- | --- | --- | --- |
| Auto attack: [Arrow](#automatic-attack-arrow) | 5 | 0.95 | ranged | 30, 37.5 |
| Ability: [Dagger stab](#active-ability-dagger-stab) | 10 | 0.6–6 | melee | 6 |

Stab cooldown depends on the target’s HP before the hit.

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
| [Spell Scroll](../perks/Spell%20Scroll.md) | Ability cooldown | 0.65 | Equipped ruler weapon; dagger maximum cooldown |
| [Assassin's Training](../town-center/Assassin's%20Training.md) | Active cooldown | 0.5 | Ruler |
| [Blessed Weaponry](../royal-forge/Blessed%20Weaponry.md) | Active cooldown | 0.6 | Ruler; dagger uses maximum cooldown |
| [Lighter Materials](../perks/Lighter%20Materials.md) | Auto-attack cooldown | 0.67 | Equipped ruler weapon |
| [Lighter Weaponry](../royal-forge/Lighter%20Weaponry.md) | Passive cooldown | 0.6 | Ruler |
| [Godly Curse](../town-center/Godly%20Curse.md) | Bonus damage | — | Enemy hit by ruler weapon |

## Automatic attack: Arrow

| Stat | Value |
| --- | --- |
| Attack interval | 0.95 s |
| Damage | 5 HP |
| Range | 30 |
| Flying range | 37.5 |
| Target | Nearest enemy |
| Base DPS | 5.26 |

| Stat | Value |
| --- | --- |
| Projectile speed | 30 units/s |
| Maximum chase distance | 10,000 |
| Arc factor | 0.2 |
| Arc distance offset | -4 |

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Resistant to ruler damage | 0.5 |
| Siege | 0.5 |
| Flying | 2.16 |
| Ranged armor | 0.6 |
| Boss | 2 |
| Ranged-vulnerable | 1.5 |

### Damage by enemy

| Enemy | Arrow (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Big Spider](../enemies/Big%20Spider.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Fire Snail](../enemies/Fire%20Snail.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Monster Rider](../enemies/Monster%20Rider.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Swordsman](../enemies/Swordsman.md), [Thing](../enemies/Thing.md) | 5 |
| [Barrel Knight](../enemies/Barrel%20Knight.md), [Catapult](../enemies/Catapult.md), [Ghost](../enemies/Ghost.md), [Iron Tower](../enemies/Iron%20Tower.md), [Quicksling](../enemies/Quicksling.md), [Racer](../enemies/Racer.md), [Wheel](../enemies/Wheel.md) | 2.5 |
| [Bloodwing](../enemies/Bloodwing.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Wasp](../enemies/Wasp.md) | 10.8 |
| [Exploder](../enemies/Exploder.md) | 1.25 |
| [Pikes](../enemies/Pikes.md) | 7.5 |
| [Ram](../enemies/Ram.md) | 1.5 |
| [Wind-Boat](../enemies/Wind-Boat.md) | 5.4 |

## Active ability: Dagger stab

| Stat | Value | Condition |
| --- | --- | --- |
| Cooldown | 6 s | Target at full HP |
| Damage | 10 HP |  |
| Range | 6 |  |
| Target | Ground enemy with the lowest HP fraction |  |
| Minimum cooldown | 0.6 s | Target near zero HP |

Cooldown = maximum · (0.10 + 0.90 · target HP fraction before the stab). A miss spends the last cooldown.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Resistant to ruler damage | 0.5 |
| Siege | 0.6 |
| Monster | 0.75 |
| Boss | 3 |

### Damage by enemy

| Enemy | Dagger stab (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Swordsman](../enemies/Swordsman.md) | 10 |
| [Barrel Knight](../enemies/Barrel%20Knight.md), [Catapult](../enemies/Catapult.md), [Iron Tower](../enemies/Iron%20Tower.md), [Quicksling](../enemies/Quicksling.md), [Ram](../enemies/Ram.md), [Wheel](../enemies/Wheel.md) | 6 |
| [Big Spider](../enemies/Big%20Spider.md), [Fire Snail](../enemies/Fire%20Snail.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Monster Rider](../enemies/Monster%20Rider.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Thing](../enemies/Thing.md) | 7.5 |
| [Bloodwing](../enemies/Bloodwing.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Wasp](../enemies/Wasp.md), [Wind-Boat](../enemies/Wind-Boat.md) | — |
| [Exploder](../enemies/Exploder.md) | 2.25 |
| [Ghost](../enemies/Ghost.md) | 5 |
| [Racer](../enemies/Racer.md) | 3.75 |
