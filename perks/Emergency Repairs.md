# Emergency Repairs (Perk)

## Effects

| Stat | Value | Condition | Target |
| --- | --- | --- | --- |
| Current HP | +0.25 · (missing HP − mean missing HP) | Every 2 s | Living walls and gates |

## Hidden mechanics

Each check compares missing HP, not the fraction of HP missing. Less-damaged walls and gates give up HP while more-damaged ones recover it, regardless of distance. Knocked-out pieces are not revived.

## Impacted damage dealers

[Wide Gate](../walls/Wide%20Gate.md) · [Wide Wall](../walls/Wide%20Wall.md)

## Craaghelm

Every 2 s, living gates and wall sections share their **missing HP**, not their remaining health fractions. Each moves 0.25 of the way toward the group’s mean missing HP. A wide gate can give HP to a distant narrow wall; no adjacent connection is required. A knocked-out piece is not included or revived.

### Affects

**Built, living wall or gate**

| Affects | Stat | Value |
| --- | --- | --- |
| [Gate](../walls/Gate.md) · [Wall Segment](../walls/Wall%20Segment.md) · [Wide Gate (Craaghelm)](../walls/Wide%20Gate.md#craaghelm) · [Wide Wall (Craaghelm)](../walls/Wide%20Wall.md#craaghelm) | Missing HP transfer | 0.25 of difference from mean every 2 s |
