Humbug
======

Minecraft server plug-in: Simply disables various functionality

- Disables Anvil use.
- Disables Ender Chest use.
- Disables Villager trading.
- Disables Wither block destruction radius.
- Disables Wither and Wither Skull explosions.
- Disables cobblestone generation from lava and water.
- Makes the Protection enchantment a little stronger
- Enables adjustment of all Player maximum health
- Removes the Enchanted Book recipe.
- Removes the Enchanted Golden Apple recipe.
- Converts Enchanted Golden Apples to normal Golden Apples if a Player attempts to eat them.
- Disables Ender Pearl Teleportation

The 'humbug' console command can be used to get or set any of the configuration file settings while the server is running. Also available are 'humbug save' and 'humbug reload'.

Config file settings:
- debug: Boolean, Turns on debug logging (currently there is none)
- anvil: Boolean, Turns on anvil use
- ender_chest: Boolean, Turns on ender chest use
- villager_trades: Boolean, Turns on villager trades
- wither: Boolean, Turns on the wither
- wither_explosions: Boolean, Turns on wither explosions destroying blocks. Wither/Wither Skull explosions will always occur to damage players, this only effects block breakage.
- wither_insta_break: Boolean, Turns on the wither insta-break ability
- cobble_from_lava: Boolean, Turns on cobblestone generation when lava and water mix
- cobble_from_lava_scan_radius: Integer, Sets the radius to scan for lava/water interaction
- ench_book_craftable: Boolean, Allows the Enchanted Book recipe to be used
- scale_protection_enchant: Boolean, Increases damage reduction granted by the Protection enchantment
- player_max_health: Integer, sets all Player maximum health
- ender_pearl_teleportation: Boolean, Turns on Ender Pearl teleportation
- ench_gold_app_edible: Boolean, Allows players to eat Enchanted Golden Apples. If false, Enchanted Golden Apples are converted to normal Golden Apples
- ench_gold_app_craftable: Boolean, Allows the Enchanted Golden Apple recipe to be used

Default configuration:
- debug: false
- anvil: false
- ender_chest: false
- villager_trades: false
- wither: true
- wither_explosions: false
- wither_insta_break: false
- cobble_from_lava: false
- cobble_from_lava_scan_radius: 0
- ench_book_craftable: false
- scale_protection_enchant: true
- player_max_health: 20
- ender_pearl_teleportation: false
- ench_gold_app_edible: false
- ench_gold_app_craftable: false
