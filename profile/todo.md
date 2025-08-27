# ➡️ To-do:
<sup><sup>*items are not in order of completion</sup></sup>

## 🔜 Next Release:
- fix DiscordChatBridge webhook avatar icon being Steve. Probably just need to change which mc chat head provider the plugin points to.

## ↩️ Planned:
- custom chat colors, use by typing `&#` before the hex color. Potential for custom name colors in chat.
- add debug line in F3 menu that shows what block ID, block name translation key and metadata of the block you're looking at.
- fix lighting around transparent blocks like signs
- overhaul texture system; add a 2nd terrain.png
- native controller support (for handheld devices like Steam Deck)
- make Creepers spawn less frequently
- make mobs only spawn in light levels less than 2 or 1
- add shift-clicking for furnaces and armor slots
- add Redstone Lamps
- fix redstone update order
- add an item specifically for claim/selection wand
- wooden buttons
- optimize weather rendering [C]
- add option to turn off grass side rendering [C]
- fix fullscreen on Linux [C] (probably by just making the window borderless windowed)
- make client retry connecting if failed with "bad login" (sometimes false, maybe packet dropping error?) 

## ⛔ Abandoned/Not completable:
- edit DiscordChatLink and increase delay of the starting message **--no longer necessary**
- investigate the sapling non stacking **--caused by mcMMO tree feller skill**

## ℹ️ Ideas:
- right click to sit on slab?
- add spruce and birch planks?
- add a fourth tree type?
- add horses?
- add structures like strongholds or villages from b1.8.1? (strongholds would be purely decorational)

## ☑️ Completed Tasks:
- add support for custom side and bottom textures for iron, gold and diamond blocks
- add chat history
- add text navigation
- add controls options for all inputs like F5, F2, F3
- add upside down slabs
- add FOV slider
- make Discord RPC in custom launcher show "Team Proteus"
- add stone bricks
- add gold/silk touch
- add iron trapdoors
- add more slab variants
- add weather slider
- add UI sounds from Legacy Console Edition
- add all music discs from the full release of Minecraft
- add hooks to include other chat messages not detected by DiscordChatLink  **--HeroicDeath will broadcast death messages through DiscordChatLink.**
- make non block-dependent trapdoors
- make armor slot icons render in inventory
- make chest top textures connect and rotate east-west or north-south
- make blocks like torches, redstone dust and repeaters placeable on upside-down slabs
- make FOV increase slightly while sprinting
- MAKE PORTALS LESS NOISY
- buff and nerf gold picks (slower but more durable)
- stop using Recaf to develop
- ported over code from Recaf to source so that I can compile onstead of decompiling and recompiling over and over
- overhaul textboxes and chat system (again)
- increase range of note block pitch from 2 octaves to 4 octaves **--required altering paulscode SoundSystem; changed the clamping of pitch from (0.5F,2.0F) to (0.125F,8.0F)**
- tweak mcMMO to make Gold tools not double drop items
- add/embed SmartMoving into the server and client (credit to Divisor, the author of the mod)
- fix cape rendering **--caused by incomplete SmartMoving cape renderer class**
- fix armor rendering **--caused by desync of armor model and player model**
- fix water not creating sources when on source blocks
- fix some clientside entity jerkiness
- fix placement of slabs
- fix the order of item damage and block breaking
- fix consumption of food when player is full
- fix trapdoor placement code
- fix player drowning server-side but not client-side.
- upgraded chat system again, now the chatbox will dynamically scroll to keep the cursor in frame.
- add crouch to place on interactable blocks
- add upside-down trapdoors
- wool colors from Minecraft Classic
- fix "moved wrongly" spam for noclipping players
- fix default keybindings
- add debug into item names in inventory such that when F3 is open, hovering over items in the inventory shows the Item ID, metadata/damage value and item name translation key underneath the item name and description.
