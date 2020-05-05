MoreItems Continued!

MoreItems is a custom items plugin that will enhance your Role-Playing server to the max! The possibilities are endless. It is designed for servers who want to add extra special items into the game. Be it items with special powers, RPG items, or just random everyday items! If you are looking for a custom items plugin and you can't find any that are updated look no further. MoreItems has all you would want and more!

I just the guy continued this awesome work :\

If you plan to use powers I suggest using Magic spells. It is a very good plugin for spells.

Boots Of Speed Sword of Fire Assassin Blade Long Sword

MoreItems! Enhance your server's RPG experience!

Features
Endless possibilities!
Create items with custom lore, names, material, item flags, damage, armor and much more!
Built-in Recipe Manager meaning you can make recipes for the cool items you make. The ingredients can be MoreItems items too!
Custom powers with cooldowns!
Works for armor, swords and bows. You can give extra damage and powers to everything!
You can enchant your items too!
Custom mob and block drops! MythicMobs supported!
Automatic Updating! You do NOT need to give the item to players after updating it!
Custom join items!
RPGInventory support! Check the plugin out!
Import your items from RPGItems!
Supports 1.8.x!
Commands
/mi - Main command of MoreItems
/mi create <Item Identifier> - Create an item. The item identifier is the name which you will identify the item as.
/mi give <OPTIONAL: Item Identifier> <OPTIONAL: player> - Give yourself or a player an item. Write without any args to bring forth a GUI.
/mi name <Item Identifier> <Name> - Set an item's name.
/mi material <Item Identifier> <Material> - Set an item's material.
/mi lore <Item Identifier> <Line> <OPTIONAL: Lore> - Set the description for an item. Write no lore for an empty line.
/mi delline <Item Identifier><Line> - Delete a line in the lore.
/mi durability <Item Identifier> <Durability/infinite> - Set the durability of an item. Write infite to get unbreakable (only if using Spigot)
/mi enchant <OPTIONAL: Item Identifier> <Enchantment> <Level> - Add an enchantment to an item. Write without any args to bring forth a GUI.
/mi additemflag <OPTIONAL: Item Identifier> <ItemFlag> - Add an itemflag. Write without any args to bring forth a GUI.
/mi removeitemflag <Item Identifier> <ItemFlag> - Remove and itemflag
/mi damage <Item Identifier> <minimum damage> <maximum damage> - Sets the damage range of an item. Set both minimum and maximum for an absolute damage.
/mi armor <Item Identifier> <Armor> - Set an armor piece's armor rating. This is in percentage so if you write 20 it'll shield 20% of all damage. If more items are worn then the percentage will stack. For example a chest with 20% and a helmet with 10% will give 30% damage reduction.
/mi list - List all MoreItems items
/mi addpower <Item Identifier> <EventType> <Power> <Args> - Add a power
/mi removepower <Item Identifier> <Power> - Remove a power
/mi recipe <Item Identifier> <Shaped/Furnace> - Shaped: Will open the an inventory where you can place items in a 9x9 grid to the left hand side. When you move out of the window the crafting recipe will be set. Furnace: Will open a furnace inventory where you can place an item to be smelted for the item to pop out.
/mi removerecipe <Item Identifier> - Quickly remove a recipe if you made a mistake. You might need to reload the server.
/mi removeitem <Item Identifier> - Delete an item forever!
/mi adddrops <Item Identifier> <Entity> <Chance> - Make the entity drop your item a percentage amount of time!
/mi removedrops <Item Identifier> <Entity> - Remove the drop from the specified entity
/mi addblockdrops <Item Identifier> <Block> <Chance> - Make an item drop from a block!
/mi removeblockdrops <Item Identifier> <Block> - Remove an item from the block drop list
/mi requirepermission <Item Identifier> <true/false> - Default is set to false. If you set this to true then your item can only be used if the player has the permission moreitems.use.<Item Identifier>
/mi setlevel <Item Identifier> <Level> - Set the minimum required experience level to use this item!
/mi addattribute <Item Identifier> <Attribute> <Args> - Add an attribute
/mi removeattribute <Item Identifier> <Attribute> - Remove an attribute
/mi setcolor <Item Identifier> <HEX value> - Set an item's colour. Find the colours here under Color Code
/mi import - Import all items from RPGItems
/mi show - Shows the Item Identifier of the item you're holding
/mi displaydescription <Item Identifier> <true/false> - Set an item to display it's powers and attributes or not!
Permissions
MoreItems.use - The ability to create MoreItems
MoreItems.use.<Item Identifier> - If itemsRequirePermission is set to true or the item is said to require permission then this is the permission node for it.
Discord
 
Click :\


Config
You can either create items via commands or you can do it in bulk via the items.yml. An example of an item from the items.yml would be:

  shovel:
   Material: IRON_SPADE
   Name: '&cShovel Of Doom'
   minDamage: 12
   maxDamage: 22
   Powers:
   - PotionEffect_HOLD-SPEED_200_1
   - PotionEffect_HOLD-JUMP_100_3
   Lore:
   - Its a shovel mate
   ItemFlags:
   - HIDE_ATTRIBUTES

This is the config.yml:

timerInterval: 1 #This is how often the plugin should check for the hold event type.
display powersInDescription: true #If you want powers to not be displayed in the lore then write false
display cooldown: true #If you want cooldowns to be displayed to the user. This might be a good idea to turn off if there are more powers on one item
itemsRequirePermission: false #If all items require permission. If this is set to true then the node is moreitems.use.<Item Identifier>
join Items: #A list of items that the player will receive when joining for the first time ever.
- some item

Powers, EventTypes & Attributes
Click Here to see a list of powers, event types and miscellaneous'

API
Click here to see how to use the API side of MoreItems. With this you can create custom powers and custom items via Java.

Milestones
100 Downloads - hopefully
500 Downloads - Hillaruisly
1000 Downloads - Wow 
Donate
If you wish to donate you can do so Here. Thanks in advance!

If you have any questions feel free to ask.
