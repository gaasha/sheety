## Change log
### 2.4.9
- Updated formulas to speed up calculations
- Updated the load range for rotations
- Fixed colour references for the first two cells

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
