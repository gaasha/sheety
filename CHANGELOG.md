## Change log
### Unreleased
> Bug fixes
- First tick adre consuming abilities will no longer randomly use relentless
- Fixed ability timers not resetting if they were used again
- Fixed Inspiration aura
- PE will now give adrenaline when using Inspiration aura
- Fixed Limitless not activating
- Fixed errors for limitless
- Fixed cooldowns

> Highlights
- Fixed SGB damage when in the Hybrid preset
- Updated `Incendiary` hit timing (1t later than before)
- Updated column sizes to better fit in your screen
- Updated cells with abilities on cooldown to be turned red with white background
- Added a background colour and font colour to the title of the builder to match current combat style
- Auras will be shown at the top of the builder and in the exports
- Removed black backgrounds from all images
- Updated `Sonic Wave` image
- Updated colour references to be shown in the order they are used

### 2.5.7
> Bug fixes
- `Smoke Cloud` no longer clears stalls and will now release them

> Highlights
- More formula optimisation and updating
- Changed all damage ranges and reformatted the database for easier use
- Lost stall error is disabled until a future version
- Can now use `relentless` and `stall` before or after an ability

### 2.5.6
> Bug fixes
- Fixed hit timing names for dragon weapons and `Chaos Roar`
- Fixed `Leng` spec duration
- Fixed negative adrenaline not showing red colour
- PvME builder feature: perks that aren't active will no longer show
- Fixed `Abs` hit timings
- Fixed `Wrackruin` image not showing
- Fixed `Binding Shot Flank` damage
- Fixed dragon weaponry damage
- Fixed `SGB` damage
- Fixed the Import script
- Fixed Hit timings after Bolg proc
- Fixed design issues with the Header
- Switched the position of Swaps and its images
- Broke bolg, fixed it, broke it again, fixed it but it wasn't fixed, fixed bolg

> Highlights
- PvME builder feature: comments add a line break automatically
- Using `/` before or after a comment will act as a line break
- PvME builder feature: can now change the colour and background colour of the rotation title
- Refreshed all `ECB` damage
- Added a reference template: Vorago Phase 1 - Accel Climb
- Damage loads on edit and no longer requires scripts
- Optimised all formulas that required the old damage script
- Added images to show current Bolg stacks
- Started the process of fixing all formulas one by one. Half of the main Sheet was updated along with several bug fixes
- More than one stack image can be shown at the same time
 
### 2.5.5
> Bug fixes
- Fixed damage calculations
- Fixed `Shadow Tendrils` hit timing
- Fixed BOLG stacks and PE for `Grico`, `BOLG` spec and `Shadow Tendrils`
- Removed Hit timings during nulled ticks
- Removed checkboxes from the top of the builder
- Fixed hit timings for `DDS` and `DClaws`
- Changed hit timing names
- Simplified hit timing calcs
- Improved the sidebar, exports speed, import, and other scripts
- Fixed the ability search bar not resetting
- Added `Ezk` (6, 9 bleed hits) hit timings
- `Crit` will now recognize when FSoA is active

> Highlights
- Smoke cloud can now release stalls
- Added the ability to copy your rotation into [PvME builder](https://i.gyazo.com/f41775cef06ccdf913762c5e369611d5.mp4)
- PvME Builder feature now allows to use stored exported rotations
- Exports will save data needed for the PvME Builder to be used at any moment
- Changed the design
- Hit timings: removed '1' after single hit abilities
- Added more slots for abilities and aliases
- Updated damage for Dragon weapons: `DDS`, `DMace`, `DClaws`, `DLong`, `D2H`, `DHally`
- Added a Hybrid style - Damage will only be calculated for the selected style
- Added hit timings for `DScim`
- Importing from previous versions will now also import exported rotations
- When exporting: if no sheet is available you may create one with the dropdown options
- Changed the format of script images

### 2.5.4
- Fixed broken images
- Fixed the image for `TC`
- Added a filter for the **Swaps** column
- Added `Dscim` (Dragon Scimitar) special attack
- Fixed adrenaline cap when Havoc armour is enabled
- Added `DLong` (Dragon Longsword) special attack
- Changed images for `TC` and `Lose Target`
- Fixed a typo with tips
- Rotations and References will now move up/down when the initial tick is changed (must select the **Blank** template)
- Fixed an issue with the Extra relic and Persistent Rage
- Improved the script to **Export** by adding a blank sheet for the user if there wasn't one available
- Fixed `DClaws` hit timings
- Removed cooldowns for `Dhally` and its shared cooldown with Cleave
- Fixed a bug with Exsanguinate stacks damage
- Fixed `Chaos Roar` to not break when non-melee abilities are used
- Fixed `Smoke Cloud` not releasing stalls
- Changed the design of some parts of the builder
- Added the ability to hide columns with checkboxes in the Settings
- Sped up the process of damage calcs
- Fixed hit timings for `Binding Shot` and `Tight Bindings`
- Added Bolg stacks
- Added `Clear bolg` to clear the current stacks

### 2.5.3
- Fixed adrenaline for Voke/Surge/Escape/Dive off/on GCD
- Fixed not being able to cast ECB the tick after the previous ECB ends
- Fixed Incite Tsunami using stacks after the effect expired

### 2.5.2
- Fixed errors related to cooldowns after using `Time Warp`
  -  In exchange for this, cooldowns will be ignored during TW and will not return any errors
- Images that depend on long loading times have been split from the regular images to improve performance while building rotations
- Fixed `SGB` damage
- Fixed `Load Rotations` to delete previous damage
- Fixed images not loading with ability aliases
- Fixed aura icons
- Fixed cooldown errors not appearing

### 2.5.1
- Moved all settings and scripts to the right side of the builder
- Fixed `Insufficient Adrenaline` errors to check the adrenaline one ability before rather than one tick before
- Improved the loading speed of the `+ X adrenaline` feature
- Fixed Reference templates
- Fixed an error with unknown ability names when the range was empty
- Improved damage calculations by splitting Hurricane, Overpower and other abilities into individual hits
- Removed the Notes column in `Abilities` and replaced it with a column for chaos roar
- Improved scripts speed
- Improved exports to merge rotation + swaps for a smaller export result

### 2.5.0
- Updated formulas to speed up calculations
- Updated the load range for rotations
- Fixed colour references for the first two cells
- Updated the `Export` script to load faster (15s~) and require less steps
- Fixed an error causing References to not be saved properly
- Improved the loading speed of Reference scripts
- Updated all References
- Added the ability `snipe flank` - gives the effect of the Enchantment of dread (Nightmare gauntlets)
- Added `Frost Surge` and its ability damage
- Renamed `Hydrix` to  `Hydrix Proc`
- Added a column to equip weapons/gear or cast spells instead of typing `equip...`
- Fixed Exsanguinate damage when under FSoA
- Improved all scripts - reduced about 200 lines of code
- Fixed damage after stalling abilities
- Added a column for notes - this will be stored with the Save script but will not appear in exports
- Fixed numerous performance issues by changing the code and formulas, as well as Conditional Formatting
- Removed Needle buff as it was inaccurate
- Fixed adrenaline given by autos with Invigorating Perk
- Fixed monolith energy required by Fury of the Small
- Fixed adrenaline given by VOH armour when at max adrenaline
- Fixed ability damage when an off-style ultimates are active
- Added two new buttons to replace previous functions:
  - Export & Import: same feature as Export and Import but both in one sidebar
  - Damage Calculations: gets damage of your current rotation. Damage no longer loads on edit for better performance
- Changed the width of abilities in the List of Abilities tab to fit more abilities on screen

### 2.4.8
- Fixed cooldown IDs for the Havoc armour
- Fixed formatting issues when exporting
- Fixed FSoA damage

### 2.4.7
- Fixed an error with `Zerk` when Havoc armour is disabled
- Fixed font colours when only one combat style was used
- Fixed spell stacks after stalling and releasing abilities
- Added aliases to the list of timers (for example: Zerk or Berserk)

### 2.4.6
- Fixed stalls - Stalling will no longer cancel the next ability
- Fixed Surge adrenaline on GCD
- Fixed Glacial Embrace stacks before Tsunami
- Added a feature - `Havoc Xp` to change the amount of VOH armour pieces equipped

### 2.4.5
- Fixed cooldowns when time is set to Seconds
- Changed the format of the Errors column
- Added an image for the version / outdated version
- Fixed damage when using `Swiftness` (Death's Swiftness)
- Added `BOLG` (Bow of the Last Guardian) special as an ability, no effects yet
- Fixed the speed of Loading and Exporting scripts
- Fixed Wen Arrows not resetting stacks after the effect
- Added a setting for `Reflexes` Invention Perk
- Fixed the `Adrenaline` command to allow integers
- Fixed Escape/Surge/Voke/Dive to not give adrenaline mid GCD
- Fixed Damage calculations affecting the Vestments of havoc set effect
- Fixed Vestments of havoc 15% buff to start 1 tick later
- Fixed Wen Arrows - `Swiftness` no longer activates the effect
- Added Damage presets for No Aura/Mahjarrat/every Zerk Variant/all Zerk + Smoke Cloud

### 2.4.4
- Fixed an issue causing `apot` (Replenishment Potion) to give the effect of `renewal` (Adrenaline Renewal)
- Fixed the duration of `zerk` (Berserk) with the Vestments of havoc armour set effect
- Fixed adrenaline gain for consecutive ultimates when the Vestments of havoc armour is enabled
- Fixed adrenaline gain of `enh apot` (Super adrenaline potion)
- Updated the `adrenaline` command to accept other variants of the word
  - For example: `20 adre`, `20 adrenaline`
- Updated the format of all buttons

### 2.4.3
- Fixed `Barge` (Greater Barge) buff to take into account channeled abilities
- Added cooldown reduction to `Zerk` (Berserk) when `Flurry` (Greater Flurry) lands a hit
  - For more information go [here](https://runescape.wiki/w/Greater_Flurry)
- Added an option for Enchantment of flames (Kerapac's wrist wraps)
  - For more information go [here](https://runescape.wiki/w/Enchantment_of_flames)
- Added an option for Enchantment of agony (Gloves of passage)
  - For more information go [here](https://runescape.wiki/w/Enchantment_of_agony)
- Added wildcards to ability names. Aliases and shorter names will now work
  - For example: SWH returns `Hammer`
- Updated the images for `Sunshine`, `Swiftness` (Death's Swiftness) and their Greater Variants
- Updated the image for the Herald of Chaos set effect and renamed the setting to `Vestments of havoc`
- Updated the image for `Blood Blitz`, `Vuln Bomb` and `Renewal` (Adrenaline Renewal)
- Added full name aliases to all abilities
- Fixed `Tsunami` adrenaline when under the effects of Incite Fear
- Fixed the Vestments of havoc armour to cancel the 15% extra adrenaline after another ultimate is used
- Fixed the adrenaline priority of the Vestments of havoc armour

### 2.4.2
- Fixed	Deadshot damage
- Fixed	Exsanguinate stacks not clearing after the timer ends
- Fixed	Gloves of Passage default options (not equipped)
- Added	`Wen` and `Ful` arrow effects. Use `quiver arrowname` to equip it and `unequip arrowname` to unequip it
- Added	a new column for stacks (Wen Arrows, Exsanguinate, Incite Fear) as images
- Changed	names of arrows to be equipped with the prefix "quiver" (equip wen, equip ruby, equip hydrix)
- Added	using `Max Adre`  now sets adrenaline to max
- Added	`Herald of Chaos` (0 to 4 pieces), Greater Sunshine and Greater Death's Swiftness have been added
- Fixed	duration of Exsanguinate stacks
- Fixed	Wrack and Ruin to work after the exsanguinate stacks timer hits 0
- Fixed	interactions with `Crits` when not under the effects of Incendiary (and variants) or FSoA
- Added	the error `Lost stall` when a stall is interrupted
- Fixed `Barge` (Greater Barge) to now work only after 8 ticks have passed since the last damaging ability

### 2.4.1
- Added `Vengeance` and `Dreadnip`
- Fixed Limitless duration
- Fixed interactions with Hydrix procs
- Added `Cumulative Damage` option to check damage at certain points during a rotation
- Changed errors IDs to display more precise information
- Removed unnecessary information from the main page
- Fixed `Incite Nami` to work with crits

### 2.4.0
- Added errors when casting `Omnipower` (and variants) and `Tsunami` under their minimum adrenaline requirement
- Added adrenaline priority individually per ability used
- Changed the icon for `Target Cycle`
- Fixed cooldowns of: `Fury`, `Needle`, `Gconc`, `Sonic`, `Shatter`, `Sacrifice`, `Tuska's Wrath`, `Anticipation`, `Debilitate` and `Devotion`
- Added `Fury` and renamed the greater version to `GFury`
- Fixed the duration of Berserker (reduced by 1 tick)
- Fixed `Hydrix` buff to work for autos and basic abilities
- Changed the amount of errors visible at the same time
- Fixed `Tsunami` giving the wrong adrenaline value
- Fixed Adrenaline Renewal (`Renewal`) not updating empty ticks
- Fixed typos in #Abilities tab
- Fixed `Frag walk`. It returned non-walked damage
- Changed the format of the whole Sheet
- Damage is now directly linked to Ability Damage Maths via scripts
- Added Damage Presets
- Added `FSoA` damage
- Removed Ripper Demon and Berserker's Fury buff (can be enabled in Ability Damage Maths)
- Changed Berserker's Fury with a selection of PvM relics to add to the relic power
- Added Kerapac's wrist wraps effect
- Added `Combust +2` (after using Wrack and Ruin)
- Fixed `Blood Tendrils` damage
- Added `Zek Eof` (Ez-ZekKil). It caps at 6 hits (9 with MW Spear)
- Added further improvements to the sheet's speed by reducing loading times for damage formulas
- Added `Warped Gem` in the Ring of Vigour settings
- Added #List of Abilities tab with a new design for abilities
- Added a search box and filter to #List of Abilities
- Changed the format of the Changelog
- Fixed Surge giving adrenaline during GCD with Natty active
- Added Relics at the top of the rotation builder. They will also appear when exporting

### 2.3.3
- Fixed an error causing `wrackruin` (Wrack and ruin) to not work when at 12 Exsanguinate stacks
- Fixed the amount of adrenaline given after `Time Warp`. It depends on the adrenaline you had at the end of TW's activation tick
- Added Vorago Phase 1 template post rework
- Fixed an error with adrenaline overflow, causing autos to give adrenaline after specs

### 2.3.2
- Added `GChain` (Greater Chain)
- Added `Vuln Bomb`
- Fixed an error when adding multiple spaces between abilities
- Fixed  an error causing abilities to not affect adrenaline in some cases
- Added 142 rows for longer rotations
- Added `Deathspore` effect
- Fixed `Ingen` highlight duration
- Fixed an error causing Natural Instinct to return the wrong values

### 2.3.1
- Fixed Frag walk values
- Fixed damage for Overpower and Igneous Overpower
- Added GCD errors when Disruption Shield cancels channels
- Added a confirmation before overwriting Rotations/References
- Fixed Greater Barge + Destroy to hit at the right ticks
- Changed the Crit ability to only give adrenaline when under the effects of Incendiary/Tsunami/Meteor
- Added a new Template called Blank, which starts at the tick you choose and 100% damage on every cell
- Changed the name of the old Blank template to Default, which now starts at tick -23 and only adds damage starting from tick 0
- Added `Lose Target` to stop gaining/losing adrenaline and `Target Cycle` (regain target)
- Fixed hit timing of Flurry after barge
- Fixed hits 2/3/4 for Destroy after Barge
- Changed the font colour when Limitless error is displayed
- Fixed Vorago's The End References
- Added toggle to view time in Seconds or Ticks

### 2.3.0
- Initial release
