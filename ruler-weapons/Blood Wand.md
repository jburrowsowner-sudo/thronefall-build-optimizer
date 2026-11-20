# Blood Wand (Ruler Weapon)

| Weapon action | Damage | Cooldown (s) | Type | Range |
| --- | --- | --- | --- | --- |
| Auto attack: [Blood beam](#automatic-attack-blood-beam) | 0.35 | 0.2, 0.4 | ranged | 23, 28.75 |
| Ability: [Blood sacrifice](#active-ability-blood-sacrifice) | 20 | 9 | ranged | 23, 28.75 |

## Modifiers

| Modifier | Stat | Multiplier | Target |
| --- | --- | --- | --- |
| [Assassin's Training](../town-center/Assassin's%20Training.md) | Damage | 2.05 | Ruler attacks |
| [Royal Mastery](../town-center/Royal%20Mastery.md) | Damage | 1.75 | Ruler attacks |
| [Royal Training](../town-center/Royal%20Training.md) | Damage | 1.75 | Ruler attacks |
| [Sharper Weaponry](../royal-forge/Sharper%20Weaponry.md) | Damage | 1.5 | Ruler attacks |
| [Any Empire (Town Center IV)](../town-center/Empire%20Armor.md) | Ranged damage | 1 + gold / 1,500 | Ranged attacks |
| [Ranged Attack](../blacksmith/Ranged%20Attack.md) | Ranged damage | 1.2 | Ranged attacks |
| [Ranged Damage](../perks/Ranged%20Damage.md) | Ranged damage | 1.25 | Ranged-scaling attacks |
| [Commander Mode](../perks/Commander%20Mode.md) | Ruler damage | 0.4 | Ruler |
| [Daredevil](../perks/Daredevil.md) | Ruler damage | (2.15 − 1.15 · HP fraction) | Ruler |
| [Glass Cannon](../perks/Glass%20Cannon.md) | Ruler damage | 1.8 | Ruler |
| [Warrior Training](../perks/Warrior%20Training.md) | Ruler damage | 2^((night − 1)/108) | Ruler |
| [Additional Armor](../royal-forge/Additional%20Armor.md) | Max HP | 1.6 | Ruler |
| [Builder's Guild](../town-center/Builder's%20Guild.md) | Max HP | 1.5 | Ruler |
| [Castle-Up](../town-center/Castle-Up.md) | Max HP | 1.4 | Ruler |
| [Glass Cannon](../perks/Glass%20Cannon.md) | Max HP | 0.2 | Ruler |
| [Heavy Armor](../perks/Heavy%20Armor.md) | Max HP | 3.5 | Ruler |
| [Magic Armor](../town-center/Magic%20Armor.md) | Max HP | 2.5 | Ruler |
| [Royal Mastery](../town-center/Royal%20Mastery.md) | Max HP | 1.75 | Ruler |
| [Royal Training](../town-center/Royal%20Training.md) | Max HP | 1.75 | Ruler |
| [Spell Scroll](../perks/Spell%20Scroll.md) | Ability cooldown | 0.65 | Equipped ruler weapon; dagger maximum cooldown |
| [Assassin's Training](../town-center/Assassin's%20Training.md) | Active cooldown | 0.5 | Ruler |
| [Blessed Weaponry](../royal-forge/Blessed%20Weaponry.md) | Active cooldown | 0.6 | Ruler; dagger uses maximum cooldown |
| [Lighter Materials](../perks/Lighter%20Materials.md) | Auto-attack cooldown | 0.67 | Equipped ruler weapon |
| [Lighter Weaponry](../royal-forge/Lighter%20Weaponry.md) | Passive cooldown | 0.6 | Ruler |
| [Godly Curse](../town-center/Godly%20Curse.md) | Bonus damage | — | Enemy hit by ruler weapon |
| [Godly Curse](../town-center/Godly%20Curse.md) | Max HP | 1.75 | Ruler |

## Automatic attack: Blood beam

| Stat | Value | Condition |
| --- | --- | --- |
| Attack interval | 0.2 s | Standing still |
| Opening damage | 0.35 HP |  |
| Range | 23 |  |
| Flying range | 28.75 |  |
| Target | Nearest enemy |  |
| Base DPS | 1.75 | Standing still, before ramp |
| Moving interval | 0.4 s |  |
| Maximum DPS | 30 | Standing still |
| Moving DPS | 0.87 | Before ramp |
| Maximum moving DPS | 15 |  |

| Stat | Value | Condition |
| --- | --- | --- |
| Ramp multiplier per second | 1.25 | Repeated hits on one enemy |
| Maximum time credited per hit (s) | 0.22 |  |
| Maximum ramp multiplier | 17.14 |  |

Changing targets resets the ramp to 1. Bonus damage = opening damage · ruler damage multiplier · (ramp − 1). The opening hit already includes ruler damage.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Resistant to ruler damage | 0.5 |
| Ranged armor | 0.5 |
| Boss | 0.9 |

### Damage by enemy

| Enemy | Opening beam (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Barrel Knight](../enemies/Barrel%20Knight.md), [Big Spider](../enemies/Big%20Spider.md), [Bloodwing](../enemies/Bloodwing.md), [Catapult](../enemies/Catapult.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Fire Snail](../enemies/Fire%20Snail.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Monster Rider](../enemies/Monster%20Rider.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Quicksling](../enemies/Quicksling.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Swordsman](../enemies/Swordsman.md), [Thing](../enemies/Thing.md), [Wasp](../enemies/Wasp.md), [Wheel](../enemies/Wheel.md), [Wind-Boat](../enemies/Wind-Boat.md) | 0.35 |
| [Exploder](../enemies/Exploder.md), [Ghost](../enemies/Ghost.md), [Racer](../enemies/Racer.md), [Ram](../enemies/Ram.md) | 0.17 |

## Active ability: Blood sacrifice

| Stat | Value | Condition |
| --- | --- | --- |
| Cooldown | 9 s |  |
| Opening damage | 20 HP |  |
| Range | 23 |  |
| Flying range | 28.75 |  |
| Target | Nearest enemy |  |
| Damage per HP exchanged | 2 |  |
| Bonus damage | 1 HP | On a positive exchange |

| Stat | Value |
| --- | --- |
| HP reserve (fraction of max HP) | 0.1 |
| Minimum payment (fraction of max HP) | 0.05 |
| Ruler movement speed multiplier | 0.33 |
| Self-slow | 4 s |

After the opening hit and Godly Curse, transfer the lesser of half the enemy’s remaining HP and the ruler’s HP above the reserve. A positive transfer costs at least the minimum payment, even if it dips below the reserve. The extra damage uses the transfer before that minimum.

### Damage multipliers

**Target:** Resistant to ruler damage, Ranged armor

**Multiplier:** 0.5

### Damage by enemy

| Enemy | Opening active hit (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Barrel Knight](../enemies/Barrel%20Knight.md), [Big Spider](../enemies/Big%20Spider.md), [Bloodwing](../enemies/Bloodwing.md), [Catapult](../enemies/Catapult.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Fire Snail](../enemies/Fire%20Snail.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Monster Rider](../enemies/Monster%20Rider.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Quicksling](../enemies/Quicksling.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Swordsman](../enemies/Swordsman.md), [Thing](../enemies/Thing.md), [Wasp](../enemies/Wasp.md), [Wheel](../enemies/Wheel.md), [Wind-Boat](../enemies/Wind-Boat.md) | 20 |
| [Exploder](../enemies/Exploder.md), [Ghost](../enemies/Ghost.md), [Racer](../enemies/Racer.md), [Ram](../enemies/Ram.md) | 10 |
