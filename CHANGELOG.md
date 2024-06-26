# 1.9.0
---
- Added ``impulse-damage`` to selectors for Led By Example for kineticists allies
- Added Note for ``Ready to lead by example`` using Athletic Maneuvers to correctly link ``Effect: Led By Example`` on success
- Fixed ``Helpful word`` not increasing success when used with skills rather than class dc-10
- Added Area Templates in feat descriptions of feats with Area of Effects
- Corrected wording of ``Warlord's Doom``

# 1.8.1
---
- removed extra } in Hybrid Reactions json blocking release

# 1.8.0
---
- Fixed Bulwarking Command missing the Command Trait
- Fixed Leaderhip style's colored SVGs not loading on Firefox due to lack of height/width
- Added missing Lead by Example (Free Action) separate action
- Reduced Bleeding follow through persistent damage to 2x the number of the warlord's leadership dices
- Updated Helpful word Check Generator to allow other types of Skill checks
- Fixed Hybrid Leadership giving more than the first tier aura of the chosen leadership when obtaining features for your leadership style
- Added Hybrid Commands (Level 10) and Hybrid Reactions (Level 14) to obtain commands and reactions from other leadership styles obtained with Hybrid Leadership
- Fixed incorrect levels on multiple features
- Fixed homebrew traits entry in module.json

# 1.7.0
---
- Defy Death (Feat 18) has been renamed to Keep Fighting!
- Initial Implementation of Focus Fire's effects
  - Uses a Roll Option Visible in the Action Tab of the Character Sheet
  - As of current implementation, Bonus Damage must be deactivated manually for 2nd and later damage on the target of focus fire
- Balance Changes :
  - Exemplar of command raised from level 18 feat to level 20 feat to match similar vanilla classes feats
  - Final Stand (Feat 20) bonus to AC/Saving throws reduced to +2
  - Final Stand's resistance to all damage reduced to 5
  - Focus Fire (Feat 20) change target action has been changed to a single action with the command trait
  - Focus Fire's Bonus Damage can only be activated once per character on the Focused Target
  - Legendary Push (Feat 20) quickened has been reduced to 1 extra action without limits on its usage
  - Warlord's doom (Feat 18) has an additional note stopping its effect from activating from its own strike

# 1.6.0
---
- Added automation for Extend Aura
   - Automatically increases the radius of leadership auras if the effect is applied
   - Extend Aura now applies to all warlord class auras instead of just one aura
- Initial implementation of Leadership Paragon Features 
   - uses notes rule elements on ally's damage rolls to link the effects
- Improved use of Helpful word with or without Commander's Guidance
   - Posts Effect:Aid on class and skill check rolls when "Effect: Helpful Word Ready" is active
   - If the Warlord has the Feat Commander's Guidance (level 6), "Effect: Commander's Guidance" is sent instead, replicating the regular Aid effect but with its additional +1
- Fixed Helpful word DC Generator macro's empty confirmation to correctly print a dc of 15
- Fixed Greater Skirmishing Aura radius
- Fixed Imposing Leadership's Intimidation Training
- Added an Item Alteration to Inspiring Leadership to add a note on the Marshal dedication's Aura
   - The Auras have the same effect but the Inspiring Leadership version gets upgraded as the Warlord levels up
   - The note explains how to disable the marshal Aura if the warlord has the Inspiring Leadership version
- Assigned icons to some effects using icons provided by the pf2e system spell icons

# 1.5.0
---
- Added removeAfterRoll to Effect:Ready to Lead by Example, including athletics rolls if warlord has the feat Athletic Leadership
- Removed custom labels from Effect:Bulwarking Command flat modifiers
- Corrected Effect:Bulwarking Command flat modifier type from Untyped to Status
- Added "Multi Target Damage" Checkbox in Action Tab of Character Sheet to mark that your next damage has multiple targets
- Added Martial notes for Led by example bonus damage for use when RollOption MultiTarget-Damage is active
- Made the Reminder to remove the Led by Example Effect after use clearer

# 1.4.0
---
- Removed testing visuals for Friendly Shield and Shielding Bastion's Auras
- Fixed Shielding Bastion not finding the actor's shield for the bonus to reflex saves
- Merged Shielding Bastion back into Friendly Shield as an upgrade to reduce redundant actions
  - Once the Feat is acquired, Friendly Shield's Reach aura is deactivated, preventing duplicate effects
  - Added Item Alteration to insert Shielding Bastion Description inside of Friendly Shield's description once active

# 1.3.0 - 1.3.2b
---
- Initial Foundry package release (took a few releases to get the on release action to work)
- Removed testing opacity on Friendly Shield's reach aura

# 1.2.2
---
- Removed aura on Shielding Bastion (feat) as it only needs to be on the active self effect

# 1.2.1
---
- Corrected Pack type for journal compendiums to "JournalEntry"

# 1.2.0
---
- Added Warlord Journals compendium for notes about the class or Automation homebrew options through other optional modules
- Added the Active Effect of Effect:Raise a Shield to Friendly Shield, Shielding Order and Shielding Bastion as self effects
- Added a 5ft Aura to Friendly Shield so the bonus is only active if the chosen ally is next to the Warlord
- Added missing Aura to Shielding Bastion as it affects all adjacent allies

# 1.1.1
---
- Restored missing warlord item DB

# 1.1.0
---
- Fixed Helpful Word Check Generator macro to be a script macro rather than Chat
- Changed patch numbering system to be more accurate in preparation for official foundry module release
- Cleaned up packs folder of old files

# 1.0.14
---
- Renamed the warlord item compendium back to "warlord" to fix every link being broken
  - To be renamed correctly at a later date to have proper clean names for things
- Removed the "-" for the folder name to fit in with other compendium folders made for PF2e

# 1.0.13
---
- Sorted Warlord Content into compendium Folder
- Created Warlord Macros Compendium pack
- Created Warlord Helpful Word Check Generator macro for GMs to more easily create the check in chat

# 1.0.12
---
- fixed pack name causing link issues

# 1.0.11
---
- Removed invalid journal compendium code

# 1.0.10
---
- Added Visual and Auditory Traits to Commander's Strike
- Fixed Lead By example not applying to Athletic actions while having the athletic leadership feat

# 1.0.9
---
- Renamed Alertness to Perception Expertise as according to the Remaster Changes
- Updated Metamagic to Spellshape as according to Remaster Changes
- Adjusted the Helpful Word feature's GM note to include the option action:aid into the roll so bonus to checks to aid can be applied while using Class DC - 10 as modifier

# 1.0.8
---
- Fixed Friendly shield not pointing at item.origin to find the shield
- Changed helpful word check reminder to be only shown to gm rather than a gm note on the item edit window
- removed doubled assets folder inside of /packs/ (unused)

# 1.0.7
---
- Automated Warlord's Doom one-degree-worse effect
- Corrected Warlord's Comfort to be a class feature rather than a class feat
- Added Continuing the Example and Marked to continue the Example Effects
  - One is for the ally to apply the second effect after damage rolls
- Added colored game-icons.net icons to differenciate each style
- Fixed Errors on leadership style Auras related to level scaling

# 1.0.6
---
- Implemented uses of the Note Rule Element to display effects on success
  - Lead by Example now shows effects to apply on (drag from chat to) ally according to the warlord's feats
- Reworked implementation of Magical Follow Through and Bleeding Follow through
  - Now back to the same effect on all types of allies and works with placing effects on ally that are shown on success/crit success
    - Led by example now prints the bonus damage roll if the spell-damage roll has the roll option area-damage
    - Posts the bonus damage with persistent damage when bleeding follow through effect is on ally
  - Led by example bonus damage is also disabled by default if the spell-damage roll has the roll option area-damage
    - To prevent the dice being rolled if it's an aoe and user skips the damage prompt (with shift or settings)
- Implemented level 8 Leadership Style Aura Feats
  - Merged into 1 new feat "Skillful Aura"
  - Works by giving additional effects through the style's aura when the feat is taken
- Separated Fearless Presence additional effect into a free action
  - Warlord's comfort (free action)
  - Trigger : You or an ally within your aura gains the frightened condition
  - Effect : Reduces the condition’s value by 1.
  - Will allow rebalancing of the effect by either adding a frequency or changing it into a reaction

# 1.0.5
---
- removed extra "," in module.json that was breaking it

# 1.0.4
---
- Adjustments to implementation of Bleeding Follow Through(level 8) and Magical Follow through(level 4)
  - Led by example now indicates for casters in the prompt that the damage is only for single target damage spells
    - Magical follow through and Bleeding Follow through now list all possible spell damage types in their description using inline damage prompts that will check with the warlord's stats when posted to chat
      - Temporary Solution until less cluttered implementation (possibly with macros)
    - Untyped and Untyped + Bleed also available for spells that do Slashing/Piercing/Bludgeoning or Only Bleed Damage
- Nested Warlord Items Folder inside of a Warlord Compendium Folder to allow other types of Compendium to be added to the module cleanly
- Added Key Attribute options availability for Leadership Styles
- Re-added frequency text to the top of feats to follow regular formatting
- Added publication text and authors to details of all warlord compendium items
- Changed Medical Assistance (level 6) from passive to free action
  - Same Effect, reduces the frequency of Warlord's respite to 1 round rather than 10 minutes


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
