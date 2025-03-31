---
tags:
  - custom/summary
aliases:
  - Ability
---

```dataview
TABLE WITHOUT ID file.link AS "Ability", filter(regexreplace(file.etags, "#Ability/(.+)", "$1"), (x) => regexmatch("\w+", x)) AS "Useful For"
FROM "Traits/Abilities" AND #Ability 
SORT file.name
```
