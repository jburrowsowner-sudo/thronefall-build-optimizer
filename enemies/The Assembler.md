# The Assembler (Enemy, Craaghelm)

**Maps:** Tiefenlift

**Health:** 20,000 HP · **Speed:** 6 units/s · **Slowed speed:** 1.98 units/s

**Traits:** monster, boss.

Starts with a spear, then adds a weapon at each of 3 pickups. Starting each pickup summons 5 [Beetles (Craaghelm)](Beetles.md). Previously collected weapons keep firing.

**Spear:** range 5, 1 s between thrusts. Hits a troop or the ruler for 5, an ordinary building for 7, the Town Center for 27 and a wall for 107.

Each additional weapon deals 10 damage on a 1 s cooldown. In pickup order: **crossbow** (range 20), **spike ring** (trigger range 5) and **firepot** (range 30).

The spike ring hits within 6.75 units. The firepot adds a 6-unit ground blast: 5 damage to troops or the ruler, 8 to buildings. A ground impact burns for 2.14 per tick within 5 units, up to 7 ticks 0.5 s apart. The fire starts only if a living ground troop or the ruler is in the area; buildings do not burn.

**Base damage received per hit:** [Slinger (Craaghelm)](../archery-range/Slingers.md) 4 · [Sniper (Craaghelm)](../archery-range/Snipers.md) 7 · [Defense Tower (Craaghelm)](../towers/Defense%20Tower.md#craaghelm) 8.

## Affects

**At each weapon pickup**

| Affects | Stat | Value |
| --- | --- | --- |
| [Beetles (Craaghelm)](Beetles.md) | Reinforcements | 5 |

## Modifiers

**When hit, before the target’s own defenses or phase effects**

| Modifier | Stat | Value |
| --- | --- | --- |
| [Dwarven Axe (Craaghelm)](../ruler-weapons/Dwarven%20Axe.md) | Base hit with target traits | swing: 12 HP |
| [Keg and Hammer (Craaghelm)](../ruler-weapons/Keg%20and%20Hammer.md) | Base hit with target traits | hammer hit: 27.52 HP |
| [Royal Spanner (Craaghelm)](../ruler-weapons/Royal%20Spanner.md) | Base hit with target traits | throw hit: 10 HP |
| [Stormcoil (Craaghelm)](../ruler-weapons/Stormcoil.md) | Base hit with target traits | echo: 4 HP |
