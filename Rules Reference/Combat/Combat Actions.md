
# Attack
The goal of combat is to damage your opponent's [[Health Track]]. This is achieved using [[#decisive]] attacks, which spend [[Initiative]]. [[#Withering]] attacks lower your opponent's [[Initiative]] while increasing your own, but usually do not affect [[Health Track]]. 
## withering
1. First, decide which #combatAbility is appropriate for the attack (this is often determined by the weapon being used)
 2. Make a [[#hit roll]] with a [[Dice Rolls#Dice Pool|pool]] of (Dexterity + #combatAbility + [[Accuracy]] (of the weapon) + other [[Dice Rolls#Modifiers|modifiers]]) against a [[Dice Rolls#Difficulty|difficulty]] of the target's [[Combat Traits#Defense|Defense]].
	 - If [[#hit roll]] succeeds, the attacker gains 1 [[Initiative]] and continues.
	 - If [[#hit roll]] fails, the action ends.
 3. Determine the [[#raw damage]], usually (Strength + Damage (of the weapon) + [[Dice Rolls#Threshold Successes|threshold successes]] from the [[#hit roll]]).
 4. Make a [[#damage roll]] with a [[Dice Rolls#Dice Pool|pool]] of ([[#raw damage]] - target's [[Soak]]) to a minimum of the weapon's [[Overwhelm]]. This roll *[[Dice Rolls#Doubling|Doubles 10s]]* as normal.
 5. Count the [[Dice Rolls#Successes|successes]] on the [[#damage roll]], subtract this number from the target's [[Initiative]] and add it to your character's [[Initiative]].
## decisive
 1. First, decide which #combatAbility is appropriate for the attack (this is often determined by the weapon being used)
 2. Make a [[#hit roll]] with a [[Dice Rolls#Dice Pool|pool]] of (Dexterity + #combatAbility + other [[Dice Rolls#Modifiers|modifiers]]) against a [[Dice Rolls#Difficulty|difficulty]] of the target's [[Combat Traits#Defense|Defense]]. (Note that this roll **does not include weapon [[Accuracy]]**)
	 - If [[#hit roll]] succeeds, continue.
	 - If [[#hit roll]] fails, and your [[Initiative]] is 1-10, lose 2 [[Initiative]]. If it is 11+, lose 3 [[Initiative]].
3. Make a [[#damage roll]] with a [[Dice Rolls#Dice Pool|pool]] equal to your current [[Initiative]]. ***This roll does not [[Dice Rolls#Doubling|double 10s]]***.
	- Check if the target has a [[Hardness]] score greater than the [[#damage roll]] [[Dice Rolls#Dice Pool|dice pool]]. If they do, they take no damage. This is still considered a successful attack.
4. Count the [[Dice Rolls#Successes|successes]]  of the [[#damage roll]] and apply that many levels of damage to the target's [[Health Track]]. This damage will be [[Health Track#Bashing|bashing]] or [[Health Track#Lethal|lethal]] according to the weapon used.
5. Reset your character's [[Initiative]] to [[Initiative#Base value|base value]] (3 by default).

# Disengage
# Glossary
## raw damage
The dice pool of a [[#withering]] [[#damage roll]] before [[Soak]] is applied.
## hit roll
The first roll made in any [[#Attack]], determines whether the defender can evade or parry the attack before it causes harm. Usually has a dice pool of at least the attacker's (Dexterity + #combatAbility) and a [[Dice Rolls#Difficulty|difficulty]] equal to the defender's [[Defense]].  
## damage roll
The second roll in an [[#Attack]], after the [[#hit roll]]. Used to determine the amount of damage dealt.