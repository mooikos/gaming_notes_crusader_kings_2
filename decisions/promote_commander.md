# promote commander

name
- employ_soldier

requirement
- NOT in_seclusion

cost
- 25 prestige
- 25% gold

result
- if bloodline_inspire_commanders
  - 95%
    - spawn_great_commander_effect
  - 5%
    - spawn_fantastic_commander_effect
    - get opinion_legendary_commander (+25 opinion) for 50 years
- else
  - spawn_good_commander_effect
