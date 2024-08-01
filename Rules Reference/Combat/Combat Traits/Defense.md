---
tags:
  - "#trait/combat"
  - source/solar-book
---
Defense is a static value trait representing a character's ability to protect themselves in combat. It acts as the [[Dice Rolls#Difficulty|difficulty]] for opponent's [[Attack#hit roll|hit rolls]] in combat.

This protection can take the form of [[#Parry]] or [[#Evasion]], each of which are themselves a static value #trait/combat. The highest applicable value between these two is the [[Defense]] value. 

[[Dice Rolls#Modifiers]] which affect [[Defense]] (for example *[[#Onslaught penalty|onslaught penalties]]*) always modify both Parry and Evasion as well.
# Parry
A static value #trait/combat equal to ([[Dexterity]] + #Ability/combat) / 2 rounded up + weapon's [[Defense]] bonus. 

#Ability/combat will be either [[Brawl]], [[Martial Arts]], or [[Melee]], whichever is appropriate to the weapon being used to parry. Ranged weapons such as [[Self Bow|bows]] or [[Chakram|chakrams]] cannot be used to parry.

Relevant [[Specialty|specialities]] in the #Ability/combat add +1 to the Parry value.
# Evasion
A static value #trait/combat equal to ([[Dexterity]] + [[Dodge]]) / 2 rounded up - armor's [[Mobility Penalty]], if any. 

Relevant [[Dodge]] [[Specialty|specialities]] add +1 to the Evasion value.
# Onslaught penalty
Every time an opponent attacks a character, that character suffers a cumulative -1 [[Defense]] penalty until their next turn, called an *onslaught penalty*. 