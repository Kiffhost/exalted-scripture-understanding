---
aliases:
  - Merit
tags:
  - source/solar-book
  - source/lunar-book
---
Merits are special features that add distinction to characters. Some [[Merits]] are physical advantages (such as [[Strong Lungs]]), while others represent specific learned aptitudes—additional languages the character knows how to read and speak are a common example. Still other [[Merits]] may represent social advantages, such as great wealth.

In addition to personal quirks and aptitudes, [[Merits]] also represent unusual supernatural features and capabilities. The most common source of such “Supernatural Merits” is the transformative power of the Wyld—a gift few seek. Other individuals might gain such features through divine parentage, sorcerous experimentation, or the blessings (or curses) of the many spirits of Creation. Supernatural [[Merits]] may offer great power, but those which obviously twist the mind or body also bring suspicion and hatred from the majority of Creation’s residents, who fear the mad touch of the Wyld. 

Each Merit has a number of dots (•) associated with it. These dots represent the number of points that must be spent to purchase the Merit. Some [[Merits]] allow for a range of dots (• to •••, for example). These allow players to purchase a low or high rating as appropriate—and often to raise low ratings over time during play. 

All [[Merits]] can be purchased with Merit points or bonus points during character creation. After character creation, [[Merits]] fall into three categories, governing how they may (or may not) be obtained during play. Certain magical phenomena (especially the mutating power of the Wyld or sorcerous projects) might occasionally violate these rules, as described below.

Some [[Merits]] have attached **drawbacks**—weaknesses or limitations inherent to their use or possession.

# TLDR

[[Merits]] add mechanical details to a character, useful for indicating background. They account for the miscellaneous and varying advantages of being an Exalted which are not represented in [[Charms]] or [[The Anima Banner]].
# Types

### Innate

Innate [[Merits]] can only be taken during character generation, with Merit points or bonus points. They can only be gained during play through some form of magical intervention—it’s impossible to simply decide to cultivate such [[Merits]]. 

### Purchased

In addition to being purchased at character creation as normal, these [[Merits]] may be purchased or advanced for (new rating x 3) experience points during play. You don’t have to pay for ratings that don’t do anything, and so [[Boundless Endurance]] (••) would cost 6 experience, not 9. Purchased [[Merits]] with variable ratings must be bought in sequence. 

### Story

Once play begins, these [[Merits]] may only be obtained or advanced through the course of the story, at the Storyteller’s discretion—Allies, for example, cannot be purchased with experience points, but must be gained through roleplaying and social influence. 

## Supernatural
These [[Merits]] bestow supernatural capabilities, and may generally only be obtained by magical means. The most common source of supernatural [[Merits]] in Exalted is exposure to the Wyld. Few seek out such power, both due to the unpredictability of the Wyld’s blessings, and because of the extreme stigma attached to obvious Wyld mutation throughout Creation.

These [[Merits]] are primarily presented to represent the warping power of the Wyld, and to aid Storytellers in putting together beastfolk, Wyld mutants, or similar characters. It’s very uncommon for individuals with such [[Merits]] to experience Solar Exaltation, but not unheard of. Characters can only begin play with supernatural [[Merits]] with explicit permission from the Storyteller.
## Sorcerous
These merits are each associated with a particular [[Shape Sorcery#Initiations|initiation]]. Only sorcerers belonging to that initiation may gain these merits. They are always [[#Purchased]] merits.

## Mutations
Mutations are [[#Innate]] or [[#Purchased]] [[Merits]] (Exalted, p. 158), mundane or [[#supernatural]], that alter or improve a character’s physical body, such as [[Ambidextrous]], [[Giant]], or [[Wings]].
# List
Lists of non-sorcerous merits
## Solar Appropriate
```dataview
TABLE WITHOUT ID 
	file.link as Merit,
	regexreplace(string(filter(file.tags, (t) => contains(t, "merit/"))), "#merit/", "") AS Type,
	string(filter(file.etags, (t) => contains(t, "Supernatural"))) AS Supernatural
FROM "Merits" and #merit and #Solar 
SORT contains(file.etags, "Supernatural"), string(filter(file.tags, (t) => contains(t, "merit/")))
```

## Lunar Appropriate
```dataview
TABLE WITHOUT ID 
	file.link as Merit,
	regexreplace(string(filter(file.tags, (t) => contains(t, "merit/"))), "#merit/", "") AS Type,
	string(filter(file.etags, (t) => contains(t, "Supernatural"))) AS Supernatural
FROM "Merits" and #merit and #Lunar 
SORT contains(file.etags, "Supernatural"), string(filter(file.tags, (t) => contains(t, "merit/")))
```

## Sidereal Appropriate
```dataview
TABLE WITHOUT ID 
	file.link as Merit,
	regexreplace(string(filter(file.tags, (t) => contains(t, "merit/"))), "#merit/", "") AS Type,
	string(filter(file.etags, (t) => contains(t, "Supernatural"))) AS Supernatural
FROM "Merits" and #merit and #Sidereal 
SORT contains(file.etags, "Supernatural"), string(filter(file.tags, (t) => contains(t, "merit/")))
```

## Dragon-Blooded Appropriate
```dataview
TABLE WITHOUT ID 
	file.link as Merit,
	regexreplace(string(filter(file.tags, (t) => contains(t, "merit/"))), "#merit/", "") AS Type,
	string(filter(file.etags, (t) => contains(t, "Supernatural"))) AS Supernatural
FROM "Merits" and #merit and #Dragon-Blooded  
SORT contains(file.etags, "Supernatural"), string(filter(file.tags, (t) => contains(t, "merit/")))
```

## Abyssal Appropriate
```dataview
TABLE WITHOUT ID 
	file.link as Merit,
	regexreplace(string(filter(file.tags, (t) => contains(t, "merit/"))), "#merit/", "") AS Type,
	string(filter(file.etags, (t) => contains(t, "Supernatural"))) AS Supernatural
FROM "Merits" and #merit and #Abyssal  
SORT contains(file.etags, "Supernatural"), string(filter(file.tags, (t) => contains(t, "merit/")))
```
