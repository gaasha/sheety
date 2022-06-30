## Change log

### 2.4.1
- Added Vengeance and Dreadnip as abilities
- Fixed Limitless duration
- Fixed Interactions with Hydrix procs
- New Cumulative Damage can be toggled to check damage at certain points during a rotation
- Changed errors IDs to display give more precise information
- Removed unnecessary information from the main page
- Fixed Incite Nami ability to work with crits

### 2.4.0
- Added errors when casting Omnipower (and variants) and Tsunami under their minimum adrenaline requirement
- Added individual adrenaline. It used to read the sum of all adrenaline instead of checking if it hit 100%/110% individually
- Changed the icon for Target Cycle
- Fixed cooldowns of: fury, needle, gconc, sonic, shatter, sacrifice, tuska's wrath, sacrifice, anticipation, debilitate, devotion
- Added the ability Fury and renamed the old Fury to GFury
- Fixed the duration of Berserker timer (reduced by 1)
- Fixed Hydrix buff to work for all autos and basic abilities
- Changed the amount of errors visible at the same time. You may expand the column if you get multiple errors
- Fixed Tsunami giving 400% adrenaline
- Fixed adrenaline renewal not updating empty ticks
- Fixed typos in #Abilities
- Fixed Frag walk returned non-walked damage
- New the format of the whole Sheet
- New Damage is now directly linked to Ability Damage Maths via scripts
- New Damage Presets
- New FSoA damage
- Removed Ripper Demon and Berserker's Fury buff (can be enabled in Ability Damage Maths)
- Changed Berserker's Fury with a selection of PvM relics to add to the relic power
- New Kerapac's wrist wraps effect
- New Combust +2 (after using Wrack and Ruin)
- Fixed Blood Tendrils damage
- New Ez-ZekKil (Zek Eof). It caps at 6 hits (9 with MW Spear)
- Added further improvements to the sheet's speed by reducing loading times for damage formulas
- Added warped Gem in the Ring of Vigour settings
- New #List of Abilities tab with a new design for abilities
- New a search box and filter to #List of Abilities
- Changed the format of the Changelog
- Fixed Surge during GCD with Natty active
- Added Relics at the top of the rotation builder. They will also appear when exporting

### 2.3.3
- Fixed an error causing wrack and ruin to not work when under Exsanguinate stacks
- Changed Time Warp to give adrenaline after the effect
- Fixed the amount of adrenaline given after Time Warp. It depends on the adrenaline you had at the end of TW's activation tick
- Added Vorago Phase 1 template post rework
- Fixed an error with adrenaline overflow, causing autos to give adrenaline after specs

### 2.3.2
- Added the ability GChain (Greater Chain)
- Added the ability Vuln Bomb
- Fixed an error when adding multiple spaces between abilities
- Fixed  an error causing the 3rd+ abilities to not affect adrenaline in some cases
- Added 142 rows for longer rotations
- New Deathspore effect work as an ability
- Fixed Ingen's highlight duration
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
- New "Lose Target" (stop gaining/losing adrenaline) and "Target Cycle" (regain target)
- Fixed hit timing of Flurry after barge
- Fixed hits 2/3/4 for Destroy after Barge
- Changed the font colour when Limitless error is displayed
- Fixed Vorago's The End References
- New toggle to view time in Seconds or Ticks

### 2.3.0
- Initial release
