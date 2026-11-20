# Heavy Sword (Ruler Weapon)

| Weapon action | Damage | Cooldown (s) | Type | Range | AoE range |
| --- | --- | --- | --- | --- | --- |
| Auto attack: [Sword swing](#automatic-attack-sword-swing) | 4.00 | 1 | melee | 4 | 2.8 |
| Ability: [Circular strike](#active-ability-circular-strike) | 7.62 | 8 | melee | 4 | 4.35 |

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

## Automatic attack: Sword swing

| Stat | Value |
| --- | --- |
| Attack interval | 1 s |
| Damage per enemy | 4.00 HP |
| Range | 4 |
| Target | Nearest ground enemy; damage in front of the ruler |
| Base DPS | 4.00 |

| Stat | Value |
| --- | --- |
| Hit area: width | 2.8 |
| Hit area: height | 2.8 |
| Hit area: depth | 5 |
| Center offset: sideways | -0.02 |
| Center offset: vertical | -0.08 |
| Center offset: forward | 1.52 |

The swing needs a ground target but can also hit flyers in the box.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Resistant to ruler damage | 0.5 |
| Boss | 3 |
| Ranged fighter | 1.4 |

### Damage by enemy

| Enemy | Sword swing (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Bloodwing](../enemies/Bloodwing.md), [Catapult](../enemies/Catapult.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Quicksling](../enemies/Quicksling.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Wasp](../enemies/Wasp.md), [Wind-Boat](../enemies/Wind-Boat.md) | 5.60 |
| [Barrel Knight](../enemies/Barrel%20Knight.md), [Big Spider](../enemies/Big%20Spider.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Fire Snail](../enemies/Fire%20Snail.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Hunterling](../enemies/Hunterling.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Monster Rider](../enemies/Monster%20Rider.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Ram](../enemies/Ram.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Swordsman](../enemies/Swordsman.md), [Thing](../enemies/Thing.md), [Wheel](../enemies/Wheel.md) | 4.00 |
| [Exploder](../enemies/Exploder.md), [Ghost](../enemies/Ghost.md), [Racer](../enemies/Racer.md) | 2.00 |

## Active ability: Circular strike

| Stat | Value |
| --- | --- |
| Cooldown | 8 s |
| Damage per enemy | 7.62 HP |
| Range | 4 |
| Target | Around the ruler |
| Damage radius | 4.35 |

Can cast without a target. The sweep can hit flying enemies.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Resistant to ruler damage | 0.5 |
| Boss | 3 |
| Ranged fighter | 1.4 |

### Damage by enemy

| Enemy | Sword sweep (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Bloodwing](../enemies/Bloodwing.md), [Catapult](../enemies/Catapult.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Quicksling](../enemies/Quicksling.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Wasp](../enemies/Wasp.md), [Wind-Boat](../enemies/Wind-Boat.md) | 10.67 |
| [Barrel Knight](../enemies/Barrel%20Knight.md), [Big Spider](../enemies/Big%20Spider.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Fire Snail](../enemies/Fire%20Snail.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Hunterling](../enemies/Hunterling.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Monster Rider](../enemies/Monster%20Rider.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Ram](../enemies/Ram.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Swordsman](../enemies/Swordsman.md), [Thing](../enemies/Thing.md), [Wheel](../enemies/Wheel.md) | 7.62 |
| [Exploder](../enemies/Exploder.md), [Ghost](../enemies/Ghost.md), [Racer](../enemies/Racer.md) | 3.81 |
