# MechMaintenanceByCost
BattleTech mod (using BTML) that changes your maintenance cost of your mechs from a flat sum for all mechs, to a cost, specific to the cost of the mech chassis.

## Requirements
** Warning: Uses the experimental BTML mod loader that might change, come here again to check for updates **

* install [BattleTechModLoader](https://github.com/Mpstark/BattleTechModLoader/releases) using the [instructions here](https://github.com/Mpstark/BattleTechModLoader)

## Features
- Your monthly mech cost now depend on the chassis.
- This makes Light mechs more attractive and Assault mechs more hard to sustain.

## Download

Downloads can be found on [github](https://github.com/Morphyum/MechMaintenanceByCost/releases).

## Settings
Setting | Type | Default | Description
--- | --- | --- | ---
PercentageOfMechCost | float | default 0.003 | The percentage of the chassis cost you have to pay monthly. 1 = 100% / 0 = 0%
CostByTons | bool | default false | set this to true if you want tonnage to be the factor to determine the drop costs.
cbillsPerTon | int | default 500 | if CostByTons is true, this sets the cost per ton.
    
## Install
- After installing BTML, put  everything into \BATTLETECH\Mods\ folder.
- If you want a different percentage set it in the settings.json.
- Start the game.
