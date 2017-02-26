# SimulationCraft-Addon-Extended
Extension of the SimulationCraft addon for World of Warcraft


# Chat Commands
Current chat commands, including the default one, are:
```
/simc -- Creates a textbox with an exported profile for use in simcraft
/scItem -- Creates a textbox with an item string exported from an item tooltip for use in simcraft
```
## /simc
Default command. Exports a character profile ready to be copy pasted into simcraft.

### Example
```
warrior="Dunkslam"
level=110
race=human
region=eu
server=outland
role=
professions=alchemy=800/engineering=632
talents=2333232
spec=fury
artifact=35:0:0:0:0:981:1:982:1:984:1:985:1:988:3:990:3:991:3:993:3:994:1:995:3:996:3:1357:1

head=,id=139058,bonus_id=1727/1808/1507/3336,gem_id=130222
neck=,id=132444,enchant_id=5439,bonus_id=1811,gem_id=130222
shoulder=,id=139686,bonus_id=3386/3384
back=,id=134402,enchant_id=5434,bonus_id=1727/1808/1492/1813,gem_id=130222
chest=,id=139224,bonus_id=1805/1487
wrist=,id=134230,bonus_id=1727/1502/1813
hands=,id=139995,bonus_id=665
waist=,id=134357,bonus_id=1727/1502/1813
legs=,id=137342,bonus_id=1727/1808/1497/3336,gem_id=130222
feet=,id=137529,bonus_id=1727/1507/3337
finger1=,id=121082,enchant_id=5425,bonus_id=3397/1777/1622/1675
finger2=,id=138220,bonus_id=1805/1487
trinket1=,id=137539,bonus_id=3412/1502/1813
trinket2=,id=139064,bonus_id=3397/604/1507/3337
main_hand=,id=128908,bonus_id=751,relic_id=1825:1472:1675/3432:1497:1674/3432:1497:1674,gem_id=141265/141258/141268/0
off_hand=,id=134553,relic_id=0/0,gem_id=0/0/0/0

```

## /scItem
This command extracts information from an item tooltip and formats it to a string for use in simcraft.

Hover over an item to bring up the item tooltip. Then execute this command to bring up the textbox.

### Example
```
,id=132444,enchant_id=5439,bonus_id=3529/3530,gem_id=130246
```
