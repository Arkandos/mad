---
aliases:
  - Tests
---
# Dice System
Magic and Damnation uses 6-sided dice for all rolls, hereafter referred to as d6. +1d means that you roll one additional die of that type. For example, +2d Armor means you would roll 2 additional Armor dice.
## Test
When making a Test, gather up a number of dice equal to your score in the relevant [[Mage Details#Skills|Skill]] and roll them together. Each 5 or 6 on a die counts as a success. Most Tests only require 1 success, while some require more.
# Rounds and Phases
Each [[Mission]] is divided into rounds, and each round is divided into phases. Each round progresses in the following order:
## 1. Mage Phase
1.1. First resolve any player-created effects from previous rounds (if any) with a [[Delay]] (like a  [[Formulae]])
1.2. Spawn any dead mages.
1.3. All mages regain 3 Weave.
1.4. Then all mages take 3 actions each, in the order of their choice. The players decide in which order each mage takes their turn. Once a mage has finished their turn, the next mage takes their turn. When all mages have taken their turn, the round advances to the Enemy Phase. 
## 2. Enemy Phase
2.1. Every enemy activates starting with the enemies closest to a mage. During a normal activation, an enemy moves a number of squares equal to their Speed towards the nearest target to them and then uses an ▶ action. An enemy unable to use their ▶ action moves their Speed an extra time instead.
2.2. Some enemies may have special movement modes or abilities that alter how they traverse the map.
- Climb: Can move along any surface
- Fly: Can fly through the air
- Jump: Can jump a number of squares through the air but must land on solid ground.
2.3. All enemies have at least one ability they can use after moving if possible. If an enemy has multiple that could be used, they use the more devastating option (Magistrate's discretion).
## 3. Autonomous Phase
3.1. All allied characters like [[Summon|Summons]] act.
3.2. While Summons are under the control of their owning player, they *must* act according to their ability text. This means they may act how their player does not want them to.
3.3. [[Allies]], even if under the control of a player, do not grant vision unless otherwise specified. This means the Magistrate may have to adjudicate what an ally sees.
## 4. Spawn Phase
4.1. New enemies are placed upon the map at enemy spawn points corresponding to the enemy types visible on the [[Scrying Orb]].
4.2. Add 1 [[Doom]] to the [[Doom Clock]].
4.2.1. Then check if it has reached a Doom Threshold for the first time. If it has, then resolve the effect attached to that Threshold.
4.3. Then, change the enemy types visible on the [[Scrying Orb]] to represent enemies that will spawn in the next Spawning phase. Then the next round begins, with a new Mage Phase.


# Mechanics
## Cost
Whenever you use an effect, you must pay all associated costs (which are usually listed below the name of the effect). The most common costs are actions, Weave, and Toughness. Any mentions of "spend" or "for X" are also costs.
## Reactions
Each Mage can use one [[Action types|Reaction]] per round. Only certain effects utilise reactions.
## Mounts
Some creatures can be mounted by becoming its rider. A rider counts as occupying all squares of the mount. When the mount moves, all riders move with it. A mount can have a number of riders equal to its Mount capacity, one of which controls the mount. Once per round / mount, a rider may become the controller of the mount. Whenever the controller would move, they may instead allow the mount to move (using the mounts Speed).
## Rounding
Whenever a fraction occurs, it is rounded down unless otherwise specified.
## Halved effect
When an effect is halved, all effects on the target are reduced by half. Damage is reduced by half (after all other modifiers). Status effects are halved where applicable, and a status effect reduced below 1 is not applied. Binary status effects cannot be halved and are not applied if they would be.
## Origin
The origin of an effect is where it spreads out form. Your square is the origin for a Melee, Ranged, or Close attack since it ebgins from you. The origin of an Area Burst is its center square.
## Ranges
### Ranged X
Within X squares that you have line of sight and line of effect to
### Melee X
As Ranged, but ignores cover. Melee range usually requires physically being able to touch the target, with a hand or weapon.
## Targets
Beyond targeting creatures directly, there are a number of ways to target an area.

| Name                      | Short explanation                                                                                |
| ------------------------- | ------------------------------------------------------------------------------------------------ |
| [[Aura]] X                | X squares away from the origin                                                                   |
| [[Core Rules/Ranges & Areas/Barrage]] X by Y        | Y linked [[Zone\|Zones]], each X by X squares large.                                             |
| [[Burst]] X               | X squares in all directions from the center. A Burst 1 is 3x3 squares. A burst 2 is 5x5 squares. |
| [[Area Burst]] X within Y | A Burst who's center must be within Y squares.                                                   |
| [[Close Burst]] X         | A Burst which extends X squares out from the origin                                              |
| [[Line]] X by Y           | A line that is X squares wide and Y squares long                                                 |
# Facing
All creatures in the game have a directional facing, which must be in an intercardinal direction. Whenever you take an action, you may change your facing (and you must face the direction of your target). This is most important when using ranged abilities, but some enemies may take advantage of your facing!
# Cover
When you are in cover, you gain a +3d [[Armor]] and [[Resist]] bonus against attacks that go through the cover. You may use the [[Take Cover]] action to increase your cover bonus.
## Difficult Terrain
When moving through difficult terrain, each square requires two squares of movement.
# Actions
During your turn in the [[#1. Mage Phase|Mage Phase]], you can take up to three actions. Each action must be completed before you can take another. You cannot take an action in the middle of another.

You can also take one Reaction per round, in response to specific trigger events.
# Forced Movement
Some movement is forced, meaning its not optional. When you forcefully move a target, you decide their direction as long as the move is legal. You can only move creatures across terrain that supports them (flying creatures can be moved through the air). The following are types of forced movement:
* Push: Each square the target is moved must be further away from the origin.
* Pull: Each square the target is moved must be further away from the origin.
* Slide: The target can be moved in any direction.

---
*Created 2026-04-30*