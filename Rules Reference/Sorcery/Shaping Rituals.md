---
tags:
  - source/solar-book
---
Shaping rituals are an abstraction of the many and varied ways a sorcerer might gain [[Rules Reference/Sorcery/Sorcery#Motes]]. 

#custom/note: shaping rituals do not have names. Names presented here and elsewhere are purely for convenience of file reference.

Shaping rituals attached to a particular archetype may allow access to the other benefits of that archetype, usually in the form of purchasable [[Merits]] or Evocations. 
# List
```dataview
TABLE WITHOUT ID file.link AS Ritual, regexreplace(string(file.folder), ".+/", "") AS "Associated Archetype"
FROM #shapingRitual 
```