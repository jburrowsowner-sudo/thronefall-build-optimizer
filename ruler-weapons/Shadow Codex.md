# Shadow Codex (Ruler Weapon)

| Weapon action | Damage | Cooldown (s) | Type | Range |
| --- | --- | --- | --- | --- |
| Auto attack: [Curse](#automatic-attack-curse) | 1, 1 | 1.5 | ranged | 17, 20, 26 |
| Ability: [Curse blast](#active-ability-curse-blast) | 27 | 10 | ranged | ∞ |

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
| [Spell Scroll](../perks/Spell%20Scroll.md) | Ability cooldown | 0.65 | Equipped ruler weapon; dagger maximum cooldown |
| [Assassin's Training](../town-center/Assassin's%20Training.md) | Active cooldown | 0.5 | Ruler |
| [Blessed Weaponry](../royal-forge/Blessed%20Weaponry.md) | Active cooldown | 0.6 | Ruler; dagger uses maximum cooldown |
| [Lighter Materials](../perks/Lighter%20Materials.md) | Auto-attack cooldown | 0.67 | Equipped ruler weapon |
| [Lighter Weaponry](../royal-forge/Lighter%20Weaponry.md) | Passive cooldown | 0.6 | Ruler |
| [Godly Curse](../town-center/Godly%20Curse.md) | Bonus damage | — | Enemy hit by ruler weapon |

## Automatic attack: Curse

| Stat | Value | Condition |
| --- | --- | --- |
| Attack interval | 1.5 s |  |
| Damage | 1 HP |  |
| Range | 17 |  |
| Flying range | 20 |  |
| Flying boss range | 26 |  |
| Target | Uncursed enemy first, then nearest enemy, then distant flyers |  |
| Base DPS | 0.66 |  |
| Echo damage | 1 HP | Each previously cursed enemy |
| DPS on same cursed enemy | 1.33 |  |

| Stat | Value |
| --- | --- |
| Projectile speed | 90 units/s |
| Maximum chase distance | 10,000 |

Damage all previous marks before adding the new one. Shooting a marked enemy hits it with both the dart and the echo. No mark limit or expiry.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Boss | 2 |

## Active ability: Curse blast

| Stat | Value |
| --- | --- |
| Cooldown | 10 s |
| Damage per cursed enemy | 27 HP |
| Target | All cursed enemies |
| Range | ∞ |

Consumes every mark. Activating without any marks still spends the cooldown.

### Damage multipliers

| Target | Multiplier |
| --- | --- |
| Boss | 2 |
