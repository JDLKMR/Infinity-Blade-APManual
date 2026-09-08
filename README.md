# Infinity Blade Manual APWorld
This is a manual of the classic grossing iOS mobile game, made accessible to play again in recent years after being basically lost to time thanks to the PC port. This manual involves the use of a custom save that starts you off at max level with every stat upgrade unredeemed, and with access to all different armor and equipment.

This first entry in the trilogy is smaller than the others so it doesn't have as many checks, but it has fairly intricate logic that aims to make use of different combinations of equipment tiers, health, attack, shield, and magic upgrades.
## Save File Installation
The included save file starts you at Bloodline 1 with all equipment mastered along with 309 unredeemed skill points.

To install it, place `SwordSave.bin` into `Documents\My Games\Infinity Blade\SwordGame\Saves`.
## Items
- Skill point upgrades (3 upgrades of +25 points for each of the 4 skills, totaling 12, and if all are obtained, add up to 300) (not quite 309 but close enough)
- Three Progressive Equipment Tiers (which equipment you can utilize for each tier will be detailed below)
- The Infinity Blade (separate entirely from the equipment tiers as it is a crucial item that progresses the story. This means you can get it earlier than the highest equipment tier and have a powerful weapon, which logic accounts for.)
## Locations
- Defeating enemies (One per location. Defeating enemies in the same location on different bloodlines does not count as multiple checks)
- Opening chests (Same rule as above: each location is per-game, not per-bloodline)
## Goal Requirements
- Defeat the God King, then subsequently defeat Archarin
  - Requires the needed upgrades or equipment (carefully determined the logic through testing) along with the Infinity Blade
## Extra Notes
- Note that dying to an enemy (with the exceptions of the God King and Zero Mech/Archarin) always gives you the option to either start the castle over or reload to last checkpoint. If you want to go back to before the battle started, then go to last checkpoint.
- If either the God King or Zero Mech/Archarin defeats you, you will be forced into the next bloodline. To prevent this, you can quickly exit the game before it transitions to the next bloodline, allowing you to go back to the checkpoint right before the fight.
## Progressive Equipment Tiers
Note that items are in order as they appear in the inventory, and you can use the specified items plus anything in between or lower, as long as you don't go above the tier you've currently obtained.
### Starting Equipment (not an item, this assumes 0 obtained tiers and is what you start with):
- Weapon: Steel Sword
- Shield: Wooden Shield
- Helmet: Steel Helm
- Armor: Leather
- Ring: Shattered Circle
### Progressive Equipment Tier 1
- Weapons: Talon - Fang
- Shields: Iron Guard - Silverlight
- Helmets: Gold Fury - Gladius
- Armor: Bronze - Plate
- Rings: Ring of Flames - Frozen Band
### Progressive Equipment Tier 2
- Weapons: Thorneblade - Touch of Death
- Shields: Ruby Shield - Gnash
- Helmets: Legion -  Helio
- Armor: Adamant - Helio
- Rings: Gridiron - Cryo Loop
### Progressive Equipment Tier 3 (Cannot use Infinity Blade unless you've obtained it):
- Weapons: Forge - X-SC2
- Shields: Cloven - Tempest
- Helmets: Shadow - Fusion
- Armor: Night - Omega XOS-7
- Rings: Soulless Circle - Thorne
## Potential Future Plans
- Customizable goal
  - Choose between only needing to defeat the God King, only Archarin, or both.
- Remove Infinity Blade logic
  - Takes some power away from the Infinity Blade by making it only serve as a gate for the ending and not be taken into account for combat logic.
