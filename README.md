# Rinku-s-Filter

Basic Loot Filter for Project Diablo 2

Hey everyone, this filter is fairly basic.

It removes clutter that you don't usually need.

I don't like heavily customized content, so I don't include any custom texts or descriptions, I merely mark items.

Things that are hidden:
* Low amounts of gold (progressively)
* Throwing poison / fulmination potions (at level 7)
* Healing, Mana and Rejuvination Potions with low regen (progressively)
* Antidotes (at level 20, you should have gotten past Andariel by then)
* Thawing Potions (at level 25, some might want them for Duriel)
* Stamina Potions (at level 10, in PD2 you don't really experience stamina issues) 
* Inferior Items (Always hidden)
* Arrows and Bolts (Always hidden, go to line 145 to change)
* Regular Non-Superior Normal Items with one or no sockets, Magic Normal Items (at level 30)
* All Regular Normal Items except Superior Items with 3 Sockets or more (level 45)
* Regular Non-Superior Exceptional Items with one or no sockets, Magic Exceptional Items (at level 60)
* All regular Exceptional Items except for Superior Items with 2 Sockets or more (at level 75)

Things that give information:
* All shown Item drops (Weapons or Armor) show in order: ItemName[!exc or !!!elt][#Sockets][eth?][itemlvl]RW-base?
* Runes show their Rune Number and Stacks show Quantity
* Gems are stylised to be more recognizable, none are hidden (this was copied from another filter)
* Starting with mid-tier runes, all runes, unique items, set items and potentially decent runeword bases trigger a notification and show on the minimap
