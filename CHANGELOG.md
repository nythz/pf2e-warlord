# 1.0.4
---
- Adjustements to implementation of Bleeding Follow Through(level 8) and Magical Follow through(level 4)
  - Led by example now indicates for casters in the prompt that the damage is only for single target damage spells
    - Magical follow through and Bleeding Follow through now list all possible spell damage types in their description using inline damage prompts that will check with the warlord's stats when posted to chat
      - Temporary Solution until less cluttered implementation (possibly with macros)
    - Untyped and Untyped + Bleed also available for spells that do Slashing/Piercing/Bludgeoning or Only Bleed Damage
- Nested Warlord Items Folder inside of a Warlord Compendium Folder to allow other types of Compendium to be added to the module cleanly
- Added Key Attribute options availability for Leadership Styles


# 1.0.3
---
- Implemented auto-Scaling of Lead By Example Bonus Precision Damage
- Partial implementation of Bleeding follow Through
  - Two methods of adding it to the damage roll, both with downsides
    - Add the Bleeding follow through feat to allies of the Warlord as a bonus feat    
    - Two new effects added to bleeding follow through, need to remember to add those when adding led by example ( could have bleeding follow through as an upgraded replacement to LbE )

- Added action icons(reaction, free action, etc) to feats without custom icons
- Modified Nimble Teamwork (level 8) to be a replacement of Shifting Assault (level 1) rather than a passive on the lower level action
- corrected multiple feats not having the correct action type set
- Added 1 per turn frequency to actions with the Flourish Trait
- Changed Punishing Blow (level 14) from passive to free action
- Modified Debilitating Strike (level 16) to be a replacement of Dazing Strike (level 4) rather than a passive on the lower level action

# 1.0.2
---
- added Paragon of Leadership (level 13) to the class automatic progression
  - need the warlord to be aware of these feature, no prompt implemented yet
  - Unsure how to do the Rule Elements for Imposing Leadership
- added leadership dice features to the class automatic progression
  - uses of the leadership dice still isn't implemented, need to figure out a way to have the number of dice as a variable
- Added Folders in "All Styles Features" for ease of browsing
- Used a few Pf2e Class Features Icon for All Style Features that didn't have a custom icon yet

# 1.0.1
---
This patch indicates changes from u/Fanatic66 Warlord 4.5.1 homebrew pdf.

Check the wiki for up to date changes: https://github.com/nythz/pf2e-warlord/wiki

### Base Class Changes :
- Class Hit points per Level : 8 -> 10
  - Raised HP to other martials to allow the warlord to be on the frontline more safely
- Heavy Armor : Untrained -> Trained
  - Added basic heavy armor proficiency to allow warlords to be on the frontline with less Multiple ability depedency
- Starting Skills : 3 -> 5
  - Increased base skill ammount to allow more versatibility
- Added Class Feature : Shield Block
  - Warlord has many shield related feats but doesn't have shield block
  - Added shield block to remove the feat tax to be able to use the shield feats
- Moved Hardy Warlord ( Fortitude mastery + success->crit ) to level 13
- Removed Weapon Specialization (level 13)
- Added Warlord Weapon Mastery, level 15 class feature
  - A lot of Warlord effects are dependant of hitting a target, such as lead by example
  - Weapon Mastery at level 15 is 2 level behind other martials like the expertise but allows the warlord to still keep up at higher levels
- Renamed Greater Aura (level 17) to Supreme Aura (Level 17)
  - to differenciate from the level 11 feature of the same name
---
### Feat Changes :
- Updated Flat-Footed text to Off Guard as per the Remaster on multiple feats :
  - Dreadful Threat (Imposing Feature)
  - Dazing Strike (level 2)
  - Wolf Pack Tactic (Level 6)
  - Debilitating Strike (level 16)
- Modified Shielding Bastion (level 14) to be a replacement of Friendly Shield (Level 1)
  - New action rather than upgrading the old action
  - Now acts as an Aura as it affects all allies surrounding the Warlord
  - Warlord unaffected by Aura needs his own Raise a shield + Effect for the bonus to Reflexes
- Adjusted Traits Charge with Me (Level 4)
  - Removed the open trait as per the Remaster
- Added Reposition to the choices of Athletic Feats
  - Athletic Leadership (level 2)
  - Athletic Command (level 6)
  - Aura of Physicality (level 8)

# 1.0.0
---
- Initial version
