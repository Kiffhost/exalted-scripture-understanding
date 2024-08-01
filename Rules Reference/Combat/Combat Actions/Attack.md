---
tags:
  - Action/combat
  - source/solar-book
---
# [[Attack]]
The goal of combat is to damage your opponent's [[Health Track]]. This is achieved using [[#decisive]] attacks, which spend [[Initiative]]. [[#Withering]] attacks lower your opponent's initiative while increasing your own, but usually do not affect [[Health Track]]. 
## withering
1. First, decide which #Ability/combat is appropriate for the attack (this is often determined by the weapon being used)
 2. Make a [[#hit roll]] with a [[Dice Rolls#Dice Pool|pool]] of ([[Dexterity]] + #Ability/combat + [[Accuracy]] (of the weapon) + other [[Dice Rolls#Modifiers|modifiers]]) against a [[Dice Rolls#Difficulty|difficulty]] of the target's [[Defense]].
	 - If the hit roll succeeds, the attacker gains 1 [[Initiative]] and continues.
	 - If the hit roll fails, the action ends.
 3. Determine the [[#raw damage]], usually ([[Strength]] + Damage (of the weapon) + [[Dice Rolls#Threshold Successes|threshold successes]] from the hit roll).
 4. Make a [[#damage roll]] with a pool of (raw damage - target's [[Soak]]) to a minimum of the weapon's [[Overwhelm]]. This roll *[[Dice Rolls#Doubling|Doubles 10s]]* as normal.
 5. Count the [[Dice Rolls#Successes|successes]] on the damage roll, subtract this number from the target's [[Initiative]] and add it to your character's [[Initiative]].
## decisive
 1. First, decide which #Ability/combat is appropriate for the attack (this is often determined by the weapon being used)
 2. Make a [[#hit roll]] with a [[Dice Rolls#Dice Pool|pool]] of ([[Dexterity]] + #Ability/combat + other [[Dice Rolls#Modifiers|modifiers]]) against a [[Dice Rolls#Difficulty|difficulty]] of the target's [[Defense]]. (Note that this roll **does not include weapon [[Accuracy]]**)
	 - If the hit roll succeeds, continue.
	 - If the hit roll fails, and your [[Initiative]] is 1-10, lose 2; if it is 11+, lose 3. The action ends.
3. Make a [[#damage roll]] with a pool equal to your current initiative. ***This roll does not [[Dice Rolls#Doubling|double 10s]]***.
	- Check if the target has a [[Hardness]] score greater than the [[#damage roll]] dice pool. If they do, they take no damage. This is still considered a successful attack.
4. Count the [[Dice Rolls#Successes|successes]] of the damage roll and apply that many levels of damage to the target's [[Health Track]]. This damage will be [[Health Track#Bashing|bashing]] or [[Health Track#Lethal|lethal]] according to the weapon used.
5. Reset your character's initiative to [[Initiative#Base value|base value]] (3 by default).
### Gambit
Gambits are a special sort of [[#decisive]] attack. Rather than inflicting [[Health Track]] damage, gambits are used to execute special maneuvers which can significantly shift the course of battle, such as disarming or unhorsing an opponent.

Gambits are attempted by declaring which gambit is being attempted and making a [[#decisive]] [[#hit roll]] against the opponent. If the attack fails, the attacker loses [[Initiative]] as normal. If the hit roll succeeds, the attacker rolls with a [[Dice Rolls#Dice Pool|pool]] equal to their [[Initiative]]. Rather than inflicting [[Health Track]] damage, this roll is trying to match the gambit’s [[Dice Rolls#Difficulty|difficulty]] rating. If this roll successful, the gambit has paid off!

Regardless of success, the character loses initiative equal to the gambits difficulty +1. A character cannot attempt a gambit who's cost would place them in [[Initiative#Crash]].
#### Disarm 
(difficulty 3)
A successful disarm gambit allows the character to knock an opponent’s weapon out of his hand, flinging it away to short range. Retrieving a disarmed weapon normally requires moving to the weapon’s location and using a draw/ready weapon action to reclaim it.
#### Unhorse
(difficulty 4):
A successful unhorse gambit allows the character to knock an opponent off his mount. An unhorsed character suffers one level of bashing damage and is rendered prone, and the mount usually flees in the confusion. This is generally an easier and less-costly option than trying to target a mount with a decisive attack to kill it. (While this is perhaps unrealistic, players generally don’t enjoy having their trusty horses shot out from under them, especially if the animal is a familiar. Storytellers running especially gritty games may want to allow the unhorse gambit to be used to shoot mounts out from under riders as well as forcibly dismounting opponents, at difficulty 5.)
#### Distract 
(difficulty 3-5) 
The character leads, threatens, or feints his target into the path of an ally’s decisive attack. The attacker declares an ally (who is not in [[Initiative]] Crash) as the beneficiary of this distraction; that ally gains the [[Initiative]] the character loses as a result of successfully executing this gambit. The transferred [[Initiative]] must be used to attack the gambit’s target on the ally’s next turn, or it is lost. A character can only benefit from one distraction bonus at a time. 
#### Grapple
(difficulty 2)
The character seizes her opponent in a clinch, limiting his movement and gaining the opportunity to do truly severe damage. Grapples are a bit more complicated than other gambits, and are explained in greater detail below.
# Glossary
## raw damage
The dice pool of a [[#withering]] [[#damage roll]] before [[Soak]] is applied. Usually ([[Strength]] + Damage (of the weapon) + [[Dice Rolls#Threshold Successes|threshold successes]] from the [[#hit roll]])
## hit roll
The first roll made in any [[#Attack]] (sometimes called an attack roll). Determines whether the defender can evade or parry the attack before it causes harm. Usually has a [[Dice Rolls#Dice Pool|dice pool]] of at least the attacker's ([[Dexterity]] + #Ability/combat) and a [[Dice Rolls#Difficulty|difficulty]] equal to the defender's [[Defense]].  
## damage roll
The second roll in an [[#Attack]], after the [[#hit roll]]. Used to determine the amount of damage dealt. Damage rolls are exempt from [[Health Track#wound penalties]]. 

[[#withering|Withering]] attacks have a damage [[Dice Rolls#Dice Pool|pool]] of [[#raw damage]] - [[Soak]]. 

[[#decisive|Decisive]] attacks have a damage pool equal to the attacker's current [[Initiative]].