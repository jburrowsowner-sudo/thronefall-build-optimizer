# Lightning Staff (Ruler Weapon)

| Weapon action | Damage | Cooldown (s) | Type | Range | AoE range |
| --- | --- | --- | --- | --- | --- |
| Auto attack: [Lightning bolts](#automatic-attack-lightning-bolts) | 2.25 | 3 | ranged | 35 | — |
| Ability: [Lightning strike](#active-ability-lightning-strike) | 27.5 | 9 | melee | — | 2.76, 7.2 |

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

## Automatic attack: Lightning bolts

| Stat | Value |
| --- | --- |
| Attack interval | 3 s |
| Damage per bolt | 2.25 HP |
| Range | 35 |
| Target | Spaced enemies in range |
| Base DPS | 0.75 |

| Stat | Value | Condition |
| --- | --- | --- |
| Projectile speed | 60 units/s |  |
| Maximum chase distance | 10,000 |  |
| Minimum bolt spacing | 5 | Keeps the primary target |
| Bolt limit | ∞ |  |

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Resistant to ruler damage | 0.5 |
| Flying | 2 |
| Ranged armor | 0.6 |
| Boss | 2 |
| Ranged-vulnerable | 1.33 |

### Damage by enemy

| Enemy | Bolt (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Barrel Knight](../enemies/Barrel%20Knight.md), [Big Spider](../enemies/Big%20Spider.md), [Catapult](../enemies/Catapult.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Fire Snail](../enemies/Fire%20Snail.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Monster Rider](../enemies/Monster%20Rider.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Quicksling](../enemies/Quicksling.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Swordsman](../enemies/Swordsman.md), [Thing](../enemies/Thing.md), [Wheel](../enemies/Wheel.md) | 2.25 |
| [Bloodwing](../enemies/Bloodwing.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Wasp](../enemies/Wasp.md), [Wind-Boat](../enemies/Wind-Boat.md) | 4.5 |
| [Exploder](../enemies/Exploder.md), [Ghost](../enemies/Ghost.md), [Racer](../enemies/Racer.md) | 1.12 |
| [Pikes](../enemies/Pikes.md) | 2.99 |
| [Ram](../enemies/Ram.md) | 1.35 |

## Active ability: Lightning strike

| Stat | Value |
| --- | --- |
| Cooldown | 9 s |
| Damage | 27.5 HP |
| Target | Where the ruler placed the strike |
| Delay | 3 s |
| Damage radius | 2.76 |

| Stat | Value |
| --- | --- |
| Hit area: width | 7.2 |
| Hit area: height | 15.56 |
| Hit area: depth | 7.2 |
| Center offset: vertical | 4.96 |

Ruler damage is fixed at placement. Melee Attack applies at impact.

Overlapping hit areas damage each enemy once per blast.

### Damage multipliers

**Target:** Boss, Flying

**Multiplier:** 2

### Damage by enemy

| Enemy | Delayed strike (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Barrel Knight](../enemies/Barrel%20Knight.md), [Big Spider](../enemies/Big%20Spider.md), [Catapult](../enemies/Catapult.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Exploder](../enemies/Exploder.md), [Fire Snail](../enemies/Fire%20Snail.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Ghost](../enemies/Ghost.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Monster Rider](../enemies/Monster%20Rider.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Quicksling](../enemies/Quicksling.md), [Racer](../enemies/Racer.md), [Ram](../enemies/Ram.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Swordsman](../enemies/Swordsman.md), [Thing](../enemies/Thing.md), [Wheel](../enemies/Wheel.md) | 27.5 |
| [Bloodwing](../enemies/Bloodwing.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Wasp](../enemies/Wasp.md), [Wind-Boat](../enemies/Wind-Boat.md) | 55 |
