# Battle Axe (Ruler Weapon)

| Weapon action | Damage | Cooldown (s) | Type | Range | AoE range |
| --- | --- | --- | --- | --- | --- |
| Auto attack: [Axe swing](#automatic-attack-axe-swing) | 1.14 | 0.4 | melee | 4 | 3.63 |
| Ability: [Shield](#active-ability-shield) | — | 12.5 | — | — | — |

Shield cooldown starts when invulnerability ends.

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
| [Healing Spirits](../perks/Healing%20Spirits.md) | Healing received | 1.65 | Ruler, troops, heroes and owned buildings |
| [Spell Scroll](../perks/Spell%20Scroll.md) | Ability cooldown | 0.65 | Equipped ruler weapon; dagger maximum cooldown |
| [Assassin's Training](../town-center/Assassin's%20Training.md) | Active cooldown | 0.5 | Ruler |
| [Blessed Weaponry](../royal-forge/Blessed%20Weaponry.md) | Active cooldown | 0.6 | Ruler; dagger uses maximum cooldown |
| [Lighter Materials](../perks/Lighter%20Materials.md) | Auto-attack cooldown | 0.67 | Equipped ruler weapon |
| [Lighter Weaponry](../royal-forge/Lighter%20Weaponry.md) | Passive cooldown | 0.6 | Ruler |
| [Godly Curse](../town-center/Godly%20Curse.md) | Bonus damage | — | Enemy hit by ruler weapon |

## Automatic attack: Axe swing

| Stat | Value | Condition |
| --- | --- | --- |
| Attack interval | 0.4 s |  |
| Damage | 1.14 HP |  |
| Range | 4 |  |
| Target | Nearest ground enemy; damage around the ruler |  |
| Base DPS | 2.86 |  |
| Lifesteal (fraction of hit damage) | 0.37 | Per enemy, including overkill |
| Damage radius | 3.63 |  |

Healing Spirits affects lifesteal; self-healing bonuses do not.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Resistant to ruler damage | 0.5 |
| Boss | 2 |
| Siege | 2.25 |
| Flying | 0 |
| Monster | 0.75 |

### Damage by enemy

| Enemy | Axe swing (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Swordsman](../enemies/Swordsman.md) | 1.14 |
| [Barrel Knight](../enemies/Barrel%20Knight.md), [Catapult](../enemies/Catapult.md), [Iron Tower](../enemies/Iron%20Tower.md), [Quicksling](../enemies/Quicksling.md), [Ram](../enemies/Ram.md), [Wheel](../enemies/Wheel.md) | 2.58 |
| [Big Spider](../enemies/Big%20Spider.md), [Fire Snail](../enemies/Fire%20Snail.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Monster Rider](../enemies/Monster%20Rider.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Thing](../enemies/Thing.md) | 0.86 |
| [Bloodwing](../enemies/Bloodwing.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Wasp](../enemies/Wasp.md), [Wind-Boat](../enemies/Wind-Boat.md) | 0 |
| [Exploder](../enemies/Exploder.md) | 0.96 |
| [Ghost](../enemies/Ghost.md) | 0.57 |
| [Racer](../enemies/Racer.md) | 0.43 |

## Active ability: Shield

| Stat | Value | Condition |
| --- | --- | --- |
| Cooldown | 12.5 s | After the ability ends |
| Target | Ruler |  |
| Invulnerability | 3.5 s |  |

| Stat | Value |
| --- | --- |
| Between activations | 16 s |
