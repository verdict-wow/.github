# Blizzard - HUD


## Action Bar *N*
*A 1-12 button action bar, arranged in a grid in any way vertically or horizontally. Configured in the options, there are 8 actions bars, the 7 last of which are toggable.*


## Archeology Bar


## Arena Frames

## Bags
*Includes a central bag icon with # of slots indicator, a popout display of all bags equipped, with the reagent bag always shown.*


## Boss Frames


## Boss Warnings


## Buffs and Debuffs

- Collapse the buff bar on login
- icons could should show brief explanatory text, focused on actionable ones, maybe as a vertical tray instead (what addons do this?)
- Alert when party buffs or healthstones are missing
- Track solo consumable buffs
- Rebuff reminders for short-duration buffs and shields (especially Shaman, Mage) that aren't macroable.
- Reminder to re-apply Darkmoon buff after zoning or logging in
- Audible ping for important procs (e.g. Ironfur on Druid, DH Vengeance equivalent) or maybe just recommend macro them?
- Buff and consumable reminder while leveling (food, potions, etc.)

## Cast Bar (self)


## Chat Frame
*Includes the Social (O) friend indicator button, Voice Communication button, Emote Button, the Chat frame tabs and window, scrollbars, and resizable frame.*

- Suppress noisy system messages, including Lua error spam
- Automatically organize messages into appropriate tabs
- Declutter trade, general, and services channels — separate conversations from listings by type
- Filter out gray loot


## Cooldown Manager


## Damage Meter


## Duration Bars


## Equipment Durability


## Encounter Bar


## Enemy Nameplates

**General**:
- Hunter target marker often conflicts with custom nameplates (covers it)

**Monster specific:**
- Nameplates should show kill-order priority for mythic and trash pulls


## External Defensives


## Experience Bar (+ Reputation Bar)
*Includes Experience and Reputation bars. Status Bar 2 is overlaid ontop to cover the Reputation Bar when active.*

- Resize bars (mini thick bars)
- Show percentage completion as overlay text
- Hide XP bar when at max level
- Hide Rep bar at max rep; show a toast if one isn't already shown


## Extra Abilities


## Friendly Nameplates

**NPC specific:**
- Only vendors and quest givers should show nameplates names in cities (no health bars)

**Player specific:**
- Party nameplates should show only names in instances


## HUD Tooltip

- Chromie time picker, adventure board, expansion starter NPCs, and town portals should clearly indicate their expansion


## Local Tooltip


## Loot Window


## Menu (Menu Tray)
*Includes a mini tray of UI menus buttons, and the dungeon finder icon. Not to be confused with the ESC Menu.*

*Buttons can include the Dungeon Finder status window, Character Info, Professions, Talents & Spellbook, Achievements, Quest Log (L), Housing Dashboard, Guild & Communities, Group Finder (J), Warband Collections, Adventure Guide, Shop, Game Menu (ESC).*

- Hide the notification dot on the WoW Shop button
- Group Finder eye icon should be independently movable and scalable (outside Edit Mode), with a clearer new-applicant indicator (and optionally a toast)


## Minimap
*Includes a search filter dropdown menu icon, a location title, the current time, the calendar icon, a circular radar, and hover zoom controls.*

- Gathering mode: blow up the minimap into a movable, resizable, semi-transparent overlay (don't use edit mode for this) for herbalism and mining gathering. This could be a standalone addon (`Radar`?)
- Quest Log/Map: Barber and Transmog shop pins should be hidden or opt-in — reset on login?
- Addon button tray (addon does this)
- Addon button tray should remove buttons that are in the addon drawer


## Mouse Cursor
- Better visual (but simple) of mouse cursor


## Objective Tracker
*Shows zone and dungeon objectives, quests, various trackable things include recipes, mythic and raid info and timers.*


## Party Frames


## Personal Resource Display


## Pet Bar


## Pet Frame

- warlock shards conflict with pet frame


## Player Frame
*Includes the Portrait model, animation (.zZ), status (like sleeping or in combat) border and icon, Player name and level, Health, Mana.*

- Player frame overlaps with DK rune skulls; may be unnecessary when SBA is active
- Death knight minion frame covers rune skulls

## Progress Bar


## Raid Frames


## Stance Bar


## Status Bar 2
*Positioned above the Reputation Bar.*

- Resize bars (mini thick bars)
- Show percentage completion as overlay text
- Hide when at max, maybe do a toast if there isn't one?


## Talking Head


## Target and Focus

- Party tab-targeting should prefer targets already aggro'd or targeted by a party member
- Improve tab-targeting priority: cycle DPS targets before tanks
- Warn when attacking with no target (e.g. mob died); notify when your target dies
- Warn when your target is immune, especially if adds should be prioritized instead


## Toasts
*Popup window bottom middle that says you accomplished something, looted something good, got an achivement, etc.*

- Add a dismiss button to toasts

## Vehicle Exit Button


## Vehicle Seats




# Blizzard - Dialogs


## Achievements
*Opened from HUD Menu.*


## AddOns (Enable / Disable)
*Opened from Game Menu (ESC).*


## Adventure Guide


## Bags
*Opened by clicking the bag UI Element.*

- Reagent bag slot should only show when empty (hide when a bag is equipped)
- Bank withdraw/deposit should allow maxing a stack instead of erroring when the amount is too high (inc. gold)
- Tooltips on bag items should explain what the item is used for


## Character Info
*Opened from HUD Menu.*

**Equipment tabs:**


**Currencies tab:**
- Tooltips on currencies should explain what they are used for
- Add a search bar

**Reputations tab:**
- Should reflect combined progress across alts when only the highest matters (e.g. Horde/Alliance)
- Indicate which character has each reputation maxed or at the highest level
- Add a search bar

## Dungeon Finder status window
*Opened by clicking the floating eye near the Menu.*


## Edit Mode
*Opened from Game Menu (ESC).*

- SBA display element in edit mode

## Game Menu (ESC)
*Opened by clicking the button on the menu UI element or hitting ESC.*

*Buttons: Options, Shop, AddOns, Edit Mode, Support, Macros, Log Out, Exit Game, Return to Game.*


## Group Finder (J)
*Opened from HUD Menu.*

- Expanded filters (e.g. delve tier, specific dungeon/delve)
- Auto-find or auto-join groups based on current activity


## Guild & Communities
*Opened from HUD Menu.*


## Housing Dashboard
*Opened from HUD Menu.*


## Macros
*Opened from Game Menu (ESC).*

- Auto-generate macros for common actions (mouseover heals, kicks, etc.)
- Target lowest HP mob (critters?) for Prey ability
- Target finder: continuously searches for a target, allows easy marking and shows its direction
- Icons, sets, search, and categories for macros (an addon exists for this)

**Smart Mount:**
- Auto-select mount based on faction, class, race, and zone
- Auto-use underwater mount when entering water; revert when surfacing (see druid auto switch addon)
- Auto-mount Sky Golem when herbalism is active in a supported zone
- Surface mounts with zone-specific jobs or abilities (e.g. gathering, speed) when relevant


## Options
*Opened from Game Menu (ESC).*

**Keybinds:**
- Reserve a dedicated 3rd-party voice key to avoid conflicts
- Consistent keyboard layout across classes for equivalent actions (e.g. interrupt always on the same key)
- Surface important keybind reminders in context (e.g. abilities not yet bound)
- Prompt when rebinding a key that would overwrite an existing binding, showing what it replaces
- Display active keybinds on cooldown bar buttons (already in an addon?)

**Voice Assist:**

- Only voice aggro warnings when in a party and you're not the tank
- Reduce voiceline spam during abundance events and raids
- Resolve conflicts with other addons that use voice


## Professions
*Opened from HUD Menu.*

- Calculate self-craft material cost options
- Auto-calculate profession tool upgrades and remind when upgrades or type changes are available
- Auto-equip profession tools based on the active recipe
- Display moxie on the crafting screen, possibly tied to recipe purchases
- An addon is interfering with keeping the crafting window and recipe window open simultaneously (which?)
- When moxie or skill improves, remind which new recipes are now available (especially vendor skill-point recipes)
- The profession screen can cover the cast bar while crafting; duplicate the cast bar at the bottom of the profession frame

## Quest Log (L) (Map & Quest Log) + Fullscreen Map
*Map & Quest Log opened from HUD Menu.*

*Fullscreen Map (M) opened from the Quest Log (L).*

- Quest markers should remain visible when zoomed out
- Add a search bar to the map
- Add clear breadcrumb navigation to the map
- Barber and Transmog shop pins should be hidden or opt-in — reset on login?
- Easy selection of delves, dungeons, and raids to toggle destinations with arrow breadcrumb navigation
- Toggle PVP quests
- Toggle world-quest-related quests
- Highlight regular quests that overlap with a tracked world quest (same area or objectives)
- Auto-form or auto-join a party for world quests (see `Groupoff` addon; works even without the eye icon)
- Filter out low-value gold, already-collected gear, and irrelevant old-content world quests
- Track Prey and bountiful delve chest completion
- In dungeons, caves, etc, we should display a map. We can use the minimap but blow it up as a starting point likely. Maybe autostich it as you discover? Or have completed ones like some addon in the past?


## Shop
*Real money shop.*

*Opened from HUD Menu or Game Menu (ESC).*


## Social (O)

- Hide Recruit-a-Friend (RAF) rewards except on a weekly basis

## Support (Contact Blizzard)
*Opened from Game Menu (ESC).*


## Talents & Spellbook
*Opened from HUD Menu.*

- Re-import talent tree when leveling up


## Warband Collections
*Opened from HUD Menu.*

**Mounts:**

- Mounts with Jobs

**Pets:**

- Pets with Jobs

**Toys:**

- Toys with Jobs
- Toy function categories




# Blizzard - NPC Dialogs


## Auction House

- Warn when listing/buying an item that's cheaper at a vendor
- When posting or searching, show comparable listings and estimated cost-to-craft
- Allow different auction durations per item type
- Cross-server AH data across your characters for warbound transfer decisions (use cheapest)
- If buying an item you already have listed, offer to cancel your listing instead; warn if listed on another character
- Smarter enchant finder: filter by gear slot, spec, and substat priority
- Calculate AH price vs. best self-craft cost for gear and tools
- Remind to collect mail after an AH purchase


## Bank + Warbound Bank


## Barber
*To customize character appearance.*

## Battle Pet Trainer


## Crafting Orders
*This is the station where you can place crafting orders to the public, guild, or a specific player.*

*Public orders have a problem of not guaranteeing certain qualities (?) depending on who fulfills it.*

- Only show the cost to self-craft (not total mat cost for all options)
- Commission as a % of full material cost (default 15%)
- Calculate self-craft material cost options
- Default to only learned recipes
- Auto-accept "provide materials" for NPC orders
- Add a gold cutoff setting for NPC patron orders
- Account for average mat box reward when calculating gold cost for NPC patron orders
- When viewing a work order, indicate if an alt can craft it

## Flight Master


## Great Vault


## Guild Bank


## Inn


## Item Upgrades


## Lorewalking


## Mailbox


## Main City Portals


## Profession Crafting Station
*Where you can see public, guild, NPC, personal crafting orders.*


## Profession Trainers


## Rostrum of transformation
*To customize mount appearances.*

*Currently mostly limited to dragons.*


## Stable Master
*To manage Hunter pets.*


## Trading Post
**For Housing.**


## Training Dummies


## Transmogrifier

- Browse and filter appearances by expansion source, instance, set, etc.
- Outfit of the day (random outfit)
- "Dress me" / butler mode: suggest or auto-apply premade outfit options

## Vendors

- Vendor item tooltips should indicate already-owned items (some don't, e.g. Arakkoa Outcasts garrison items); display them in red
- Only show currencies you have (midnight crafting shops currently show all)
- Add a search bar to the purchase window
- Add a global in-game search
- Warn when vendoring an item that yields another item
- Don't close bags when closing a vendor if a purchased item added to inventory

# Blizzard - World

## Instances

- Warn if you leave an instance, delve, or raid without looting the boss or chest
- reminder to equip the right gearset and talent spec for the content

## Delves

- Track nemesis pack completion within a delve
- Track banner completion within a delve
- Track gilded stash collection from bountiful delves




# 3rd Party Addons


## Auctionator

- Shopping lists for profession leveling recipes, consumables, and enchants
- Add a "Next item" button in shopping lists
- Prompt to rescan daily when visiting the AH


## Baganator

- Auto-stack identical items

## CraftSim

- When a craft needs concentration, clicking the diamond button should open it in the crafting window or auto-apply concentration
- Allow setting a value for profession points; factor it into profitability calculations (highlight in purple when threshold is met?)
- Add all profitable items to queue, or allow adding to queue directly from the listing page
- Add a compact "mini" display mode for the queue
- Queue item display should match NPC order coloring and layout
- NPC order profitability should factor in average resourcefulness
- Regular order profitability should factor in average multicraft yield
- Manually submitting an NPC work order doesn't remove it from the queue; the queue then shows the stale entry and requires a reload
- Allow queuing patron orders directly into the CraftSim queue
- Add a "needs concentration" option for HQ mats in the craft queue
- Craft queue falls back to HQ mats when LQ mats are unavailable — this is undesirable
- When concentration is required, factor in HQ mat cost if it's negligible
- When the queue window closes, auto-generate the Auctionator shopping list


## MiniCC

- Pet defensives are not shown by default (or at all?)


## Mythic Mentor

- Mythic flask/food check appears in towns — is this intended?


# Platynator

- Improve tab-targeting visual feedback

**Castbar:**
- Deprioritize low-value interrupts; rank by severity

**Monster specific:**
- Nameplate health color should indicate mob type (caster, miniboss, trash) — verify in delves and questing

**Player specific**:
- Nameplate health color should indicate player class (handle multiple same-class — define order)


## Profession Shopping List (PSL)

- Auctionator shopping list export should include item quality (CraftSim does this — is it better to exclude it?)


## Rare Detector

- Rare Detector addon icons shouldn't overwrite world quest icons on the map — confirm this is occurring
- Clicking a rare scanner result should place a map pin with a directional arrow
- Shift-clicking a rare scanner result should announce it in chat


# 1st Party Addons — Vertex 2026 


## Better Defaults
- Better default settings for common addons
- Addon recommendations
- FPS test with saved graphics settings presets
- Opening one window should not close another, enabling tiling on large monitors


## Compendium — Vertex 2026 
*The recommended collection of Vertex addons.*

- Checklists should preserve ignored items; if an update adds a new entry, surface a non-intrusive notification that can be dismissed
- A shared checklist addon that all Vertex addons can tie into, similar to how minimap buttons consolidate
- 3rd party helper app for 2nd monitor or phone
- Track progress for mission-table features (garrison, ships, Legion, Shadowlands, etc.)
- dungeon bonus roll reward pool tracking

## Editor (External Program)
- WYSIWYG visual wow UI editor out of game
- integrate current API and lua version
- examples and easy UI drag and drop components
- component themes
- like shadcn you own the component


## GameSim
- In-game simulation, especially for healing
- Allows for more accurate damage meters that properly attribute damage given by party buffs, and damage mitigated


## Journey — Vertex 2026 
- How to get somewhere (by expansion, quest, etc)
- How to find a shop without consulting a guard
- In-game quest tips
- Smart quest drop and grouping
- Smart quest pickup
- Next activity to progress the character
- Heirloom recommendations (which version, which enchants)
- bag upgrade calculator
- universal questing addon that pulls route data from other addons
- Boss tip helper and explainer
- XP bonus helper (e.g. Darkmoon Faire, damage bonuses)
- Darkmoon Faire guidance for professions and XP
- Reminder for active timewalking dungeons


## Lorewalker / Loreshout — Vertex 2026 

- Voice all NPC lines with lore hints and improved one-liner quest dialogs
- Continue dialog when walking away; queue dialog so it doesn't get skipped
- Right-clicking an NPC should re-open its dialog


## Milestone — Vertex 2026 

- Quests
  - Chapters
  - Expansions
  - Achievements
- Achievements
- Collections
  - Mounts
  - Pets
  - Toys
  - Heirlooms
  - Appearances
  - Campsites
- Professions
- Classes
- Races
- Gold Purchases (overlap)
- Reputations

- List of optional cosmetic/personalization quests
- Notify (via toast or otherwise) when a currency, reputation, or milestone threshold is reached that unlocks purchasable items


## Mounted — Vertex 2026 

- Mount sets, including a minimalist set for trading near Broncos
- Movement speedometer + cooldowns + flight helper
- Smart Mount should use class movement forms (Druid cat, Shaman wolf, Hunter speed) when mounting is unavailable
- Smart Mount should use crafting mounts when in a crafting area

## Professional / Cart — Vertex 2026 
*Professions and Auction House helpers.*

- Recommended point allocation for NPC crafting profession setup
- Show a shortlist of items to vendor beside the AH frame for easy one-click listing
- Suggest recipe purchases based on work order profitability (player and NPC orders)
- Automated recipe recommendations, filterable by profit and skill points
- Cross-character recipe planning: show which alts have a recipe, their points, and a points plan
- Profession unlock guide for NPC orders, covering current and commonly profitable items
- Moxie management: surface recipes purchasable for NPC orders
- Track how many profession points are available to collect, based on time elapsed; note when a pickup is ready
- Account for HQ mats being cheaper than LQ when generating locked-quality shopping lists

## Profiles — Vertex 2026 
- Saved profiles for global, per class, per race, per character


## SBA — Vertex 2026 
- Buffs (top right / nameplates / unit frames):
  - Change what is shown to only what is actionable SBA
- Actions
  - Minimal actions based on what is actionable SBA
- Cooldown Manager
  - Minimal cooldowns on what is actionable SBA
- Buff button that uses whatever buff items you have, recommends some for level
- Light up hunter pet revive and warlock abilities when usable
- In SBA mode, show Runic Power on the Death Knight heal macro button
- Show enrage hint for Hunter
- Rotation helper for when SBA is disabled
- GCD / off-GCD cooldown display to prevent button mashing
- Suggest Hunter pet abilities (e.g. Mortal Strike, Bloodlust)
- Spell steal helper for Mage
- Indicate when no Bloodlust/Heroism is available in the group

# Scratchpad
