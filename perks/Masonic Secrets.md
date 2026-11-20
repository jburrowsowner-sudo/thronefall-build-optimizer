# Masonic Secrets (Perk, Craaghelm)

Each built wall and gate gains **0.05 of its starting max HP per day**, including day one. The increment is fixed at initialization: it neither compounds nor grows when a wall is upgraded.

After sunrise the piece compares the current day number with the last one it credited. A newly built piece catches up all missed days at once. A 240-HP piece gains 12 max HP per credited day; building it on day four gives +48. The update also fills current HP to the new maximum. Defense towers are not recipients.

## Affects

| Affects | Stat | Value |
| --- | --- | --- |
| [Gate](../walls/Gate.md) · [Wall Segment](../walls/Wall%20Segment.md) · [Wide Gate (Craaghelm)](../walls/Wide%20Gate.md#craaghelm) · [Wide Wall (Craaghelm)](../walls/Wide%20Wall.md#craaghelm) | Maximum HP per credited day | +0.05 of starting max HP; refill to new max |
