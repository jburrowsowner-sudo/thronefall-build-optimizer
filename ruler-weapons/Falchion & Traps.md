# Falchion & Traps (Ruler Weapon)

| Weapon action | Damage | Cooldown (s) | Type | Range | AoE range |
| --- | --- | --- | --- | --- | --- |
| Auto attack: [Three-strike combo](#automatic-attack-three-strike-combo) | 6.88 | 2 | melee | 5 | — |
| Ability: [Trap](#active-ability-trap) | 7–35 | 14 | melee | — | 2.3, 6 |

Auto cooldown follows the third strike. Trap cooldown starts after the third placement.

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
| [Gods' Lotion](../perks/Gods'%20Lotion.md) | Regeneration | 2.1 | Ruler |
| [Heavy Armor](../perks/Heavy%20Armor.md) | Regeneration | 1.35 | Ruler |
| [Additional Armor](../royal-forge/Additional%20Armor.md) | Self-healing rate | 1.6 | Ruler |
| [Builder's Guild](../town-center/Builder's%20Guild.md) | Self-healing rate | 1.5 | Ruler |
| [Castle-Up](../town-center/Castle-Up.md) | Self-healing rate | 1.4 | Ruler |
| [Magic Armor](../town-center/Magic%20Armor.md) | Self-healing rate | 2 | Ruler |
| [Royal Mastery](../town-center/Royal%20Mastery.md) | Self-healing rate | 1.75 | Ruler |
| [Royal Training](../town-center/Royal%20Training.md) | Self-healing rate | 1.75 | Ruler |
| [Spell Scroll](../perks/Spell%20Scroll.md) | Ability cooldown | 0.65 | Equipped ruler weapon; dagger maximum cooldown |
| [Assassin's Training](../town-center/Assassin's%20Training.md) | Active cooldown | 0.5 | Ruler |
| [Blessed Weaponry](../royal-forge/Blessed%20Weaponry.md) | Active cooldown | 0.6 | Ruler; dagger uses maximum cooldown |
| [Lighter Materials](../perks/Lighter%20Materials.md) | Auto-attack cooldown | 0.67 | Equipped ruler weapon |
| [Lighter Weaponry](../royal-forge/Lighter%20Weaponry.md) | Passive cooldown | 0.6 | Ruler |
| [Godly Curse](../town-center/Godly%20Curse.md) | Bonus damage | — | Enemy hit by ruler weapon |
| [Godly Curse](../town-center/Godly%20Curse.md) | Self-healing rate | 1.75 | Ruler |

## Automatic attack: Three-strike combo

| Stat | Value | Condition |
| --- | --- | --- |
| Attack interval | 2 s | After third strike |
| Damage per strike | 6.88 HP |  |
| Range | 5 |  |
| Target | Ground monsters first, then other ground enemies |  |
| Base DPS | 8.6 |  |
| Strikes per combo | 3 |  |
| Between strikes | 0.2 s |  |
| Healing on kill | 12.5 HP | Blade kills only |

Each strike picks a target. Attack-speed upgrades shorten the gap after the combo, not the gap between its strikes.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Resistant to ruler damage | 0.5 |
| Monster | 2 |
| Boss | 2 |

### Damage by enemy

| Enemy | One blade strike (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Barrel Knight](../enemies/Barrel%20Knight.md), [Catapult](../enemies/Catapult.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Exploder](../enemies/Exploder.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Quicksling](../enemies/Quicksling.md), [Racer](../enemies/Racer.md), [Ram](../enemies/Ram.md), [Swordsman](../enemies/Swordsman.md), [Wheel](../enemies/Wheel.md) | 6.88 |
| [Big Spider](../enemies/Big%20Spider.md), [Fire Snail](../enemies/Fire%20Snail.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Monster Rider](../enemies/Monster%20Rider.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Thing](../enemies/Thing.md) | 13.76 |
| [Bloodwing](../enemies/Bloodwing.md), [Flying Mage](../enemies/Flying%20Mage.md), [Fury](../enemies/Fury.md), [Wasp](../enemies/Wasp.md), [Wind-Boat](../enemies/Wind-Boat.md) | — |
| [Ghost](../enemies/Ghost.md) | 3.44 |

## Active ability: Trap

| Stat | Value | Condition |
| --- | --- | --- |
| Cooldown | 14 s | After third trap |
| Fully charged damage | 35 HP |  |
| Target | Where the ruler placed the trap |  |
| Starting damage | 7 HP |  |
| Charge time | 12 s |  |
| Placements per cooldown | 3 |  |
| Damage radius | 2.3 |  |

| Stat | Value |
| --- | --- |
| Trigger width | 1 |
| Trigger height | 20 |
| Trigger depth | 1 |
| Enemy detection radius | 20 |
| Hit area: width | 6 |
| Hit area: height | 15.56 |
| Hit area: depth | 6 |
| Center offset: vertical | 4.96 |

Damage rises linearly until full charge. Ruler damage is fixed at placement; Melee Attack applies at detonation. Dusk resets placements; untriggered traps expire at dawn. Multiple enemies crossing the trigger in the same frame can cause more than one blast.

Overlapping hit areas damage each enemy once per blast.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Boss | 2 |
| Monster | 1.33 |
| Resistant to ruler damage | 0.75 |

### Damage by enemy

| Enemy | Fully charged trap (HP) |
| --- | --- |
| [Archer](../enemies/Archer.md), [Barrel Knight](../enemies/Barrel%20Knight.md), [Catapult](../enemies/Catapult.md), [Dark Warrior](../enemies/Dark%20Warrior.md), [Flail](../enemies/Flail.md), [Flogre](../enemies/Flogre.md), [Flying Mage](../enemies/Flying%20Mage.md), [Iron Tower](../enemies/Iron%20Tower.md), [Master Crossbowmen](../enemies/Master%20Crossbowmen.md), [Mole Archer](../enemies/Mole%20Archer.md), [Mole Warrior](../enemies/Mole%20Warrior.md), [Ogre](../enemies/Ogre.md), [Peasant](../enemies/Peasant.md), [Pikes](../enemies/Pikes.md), [Quicksling](../enemies/Quicksling.md), [Ram](../enemies/Ram.md), [Swordsman](../enemies/Swordsman.md), [Wheel](../enemies/Wheel.md), [Wind-Boat](../enemies/Wind-Boat.md) | 35 |
| [Big Spider](../enemies/Big%20Spider.md), [Bloodwing](../enemies/Bloodwing.md), [Fire Snail](../enemies/Fire%20Snail.md), [Fury](../enemies/Fury.md), [Giraffe Slime](../enemies/Giraffe%20Slime.md), [Hunterling](../enemies/Hunterling.md), [Monster Rider](../enemies/Monster%20Rider.md), [Slime](../enemies/Slime.md), [Small Spider](../enemies/Small%20Spider.md), [Spider](../enemies/Spider.md), [Spiky Giraffe](../enemies/Spiky%20Giraffe.md), [Spiky Slime](../enemies/Spiky%20Slime.md), [Thing](../enemies/Thing.md), [Wasp](../enemies/Wasp.md) | 46.55 |
| [Exploder](../enemies/Exploder.md), [Racer](../enemies/Racer.md) | 34.91 |
| [Ghost](../enemies/Ghost.md) | 26.25 |
