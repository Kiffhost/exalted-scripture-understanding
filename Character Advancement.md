# Celestial Exalted Advancement Table

| Trait                                                          | Experience Cost         | [[#Training Times]]           |
| -------------------------------------------------------------- | ----------------------- | ----------------------------- |
| Attribute increase default                                     | Current x 4<sup>a</sup> | (New rating) months           |
| Attribute increase if Caste/Favoured                           | Current x 3             | (New rating + 1) weeks        |
| Ability increase default                                       | Current x 2             | (New rating) weeks            |
| Ability increase if Caste/Favoured                             | (Current x 2) - 1       | (New rating) days             |
| New Ability                                                    | 3                       |                               |
| [[Specialty]]                                                  | 3                       | 2 weeks                       |
| [[Merits#Purchased\|Purchased Merit]]                          | New Rating x3           | (New rating weeks)            |
| [[Willpower]]                                                  | 8                       | 1 month                       |
| Solar Charm (Ability is not Caste/Favoured)                    | 10                      | (Ability + Essence mins) days |
| Solar Charm (Ability is Caste/Favoured)                        | 8                       | (Ability min) days            |
| [[Martial Arts]] Charm default                                 | 10                      | (Ability + Essence mins) days |
| [[Martial Arts]] Charm (Ability<sup>b</sup> is Caste/Favoured) | 8                       | (Ability min) days            |
| *Sidereal* Sidereal Martial Arts Charm                         | 10                      | (Essence minimum x 4) days    |
| Spell ([[Occult]]/[[Intelligence]] is not Caste/Favoured)<br>  | 10                      | 2 weeks per Circle            |
| Spell ([[Occult]]/[[Intelligence]] is Caste/Favoured)          | 8                       | 2 weeks per Circle            |
| New Evocation                                                  | 10                      | (Essence minimum x 4) days    |
| *Lunar* Animal Latent Ability                                  | 6                       | 1 week                        |
<sup>a</sup>[[Casteless]] Lunars get -1 cost to all Attribute increases. 
<sup>b</sup>[[Solar Exalted]] with [[Brawl]] Caste/Favoured and all [[Sidereal Exalted]] receive this discount. 

# Terrestrial Exalted Advancement Table

| Trait                                                        | Experience Cost        | [[#Training Times]]           |
| ------------------------------------------------------------ | ---------------------- | ----------------------------- |
| Attribute Increase                                           | Current rating x 4     | (New rating) months           |
| Standard Ability increase                                    | Current rating x 2     | (New rating) weeks            |
| Aspect/Favoured Ability increase                             | (Current rating x 2)-1 | (New rating) days             |
| New Ability                                                  | 3                      |                               |
| [[Specialty]]                                                | 3                      | 2 weeks                       |
| [[Merits#Purchased\|Purchased Merit]]                        | New Rating x 3         | (New rating) weeks            |
| [[Willpower]]                                                | 8                      | 1 month                       |
| Charm (Ability is not Aspect/Favoured)                       | 10                     | (Ability + Essence mins) days |
| Charm (Ability is Aspect/Favoured)                           | 8                      | (Ability min) days            |
| [[Martial Arts]] Charm (Martial Arts is not Aspect/Favoured) | 10                     | (Ability + Essence mins) days |
| [[Martial Arts]] Charm (Martial Arts is Aspect/Favoured)     | 8                      | (Ability min) days            |
| Spell ([[Occult]] is not Aspect/Favoured)<br>                | 12                     | 2 weeks                       |
| Spell ([[Occult]] is Aspect/Favoured)                        | 10                     | 2 weeks                       |
| Evocation                                                    | 12                     | (Essence minimum x 4) days    |

# Experience Points

Each character gains 5 experience points at the end of every session. These points may be spent immediately, or saved to be spent later.
## Exalted Experience
#custom/note This section has been generalised, each book lists each type of Exalted Experience separately.

In addition to normal experience points, players have the opportunity to gain Exalted experience in each session. **Exalted experience may be spent on anything except Charms specific to that type of Exalted.**

<details><summary>Specifically</summary>Attributes, Abilities, Specialties, Merits, Willpower, Martial Arts Charms, Evocations, and spells are all valid, as are things like spirit Charms learned with the Eclipse anima power, sorcerous workings, or Charms with experience point costs in their activation. </details>

Players have two opportunities to gain Exalted experience per session. They may earn up to one [[#Expression Bonus]], and one [[#Role Bonus]], for a total of up to 4 Solar experience per session.

### Expression Bonus
Characters can gain 2 points of [[#Solar Experience]] by fulfilling *one* of the following criteria per session: 
- Expressing, supporting, or engaging a Major or Defining [[Intimacy]] in such a way that it reveals something about the character, develops the character’s personality, or provides a character moment that everyone at the table enjoys. 
- Being significantly challenged, endangered, or harmed in the course of protecting or upholding a Major or Defining Intimacy. 
- Being significantly impeded, endangered, or harmed by a [[Flaws|Flaw]].

### Role Bonus
Characters can gain 2 points of solar experience by fulfilling *one* of the following criteria per session: 
- Intentionally ceding the ‘spotlight’ of the scene’s focus to another player’s character in such a way that it makes that character shine in the role of their Caste, or directly supporting them in a cool and dramatic expression of their Caste’s function.
- *Dragon-Blooded only:* Roleplaying the effects of the Great Curse in a way that reveals something about the character, develops her personality, or provides a character moment that everyone at the table enjoys.
- Caste-specific criteria:
```dataview
TABLE WITHOUT ID link(file.name+"#Experience Trigger", regexreplace(regexreplace(file.path, "^\w+/\w+/", ""), "\.md", "")) AS "XP Trigger"
FROM "Traits/Anima" AND (#Dragon-Blooded OR #Lunar OR #Solar OR #Sidereal)
SORT contains(file.tags,"Dragon-Blooded"),contains(file.tags,"Solar"), contains(file.tags,"Sidereal"), contains(file.tags,"Lunar")
```

# Training Times
The [[#Experience Points|above]] training times assume characters spend a significant portion of the quoted time working on the talent in question. Note:
- The characters need not train exclusively.
	- If they did train at the exclusion of all else, they could raise their traits significantly faster than shown.
- Many forms of training may potentially benefit multiple Traits. 
- Practical experience also counts as a significant amount of training. 
	- This is especially true for [[Charms]], which are often largely instinctive.
	- [[Evocations]] require training but also rapport with the [[Artifact]], often developed in battle.
	- [[Martial Arts]] Charms always require rigorous training.
	- Learning spells requires a mentor or a text copy of the spell, and many hours of study.
- Mentors and similarly skilled trainers should also reduce training times, proportionate to their skill at teaching.

# Raising Essence
Rather than spending experience points or even Exalted experience to raise Essence, characters’ Essence ratings increase automatically once they have earned and spent enough experience points on other traits. Essence doesn’t generally rise immediately after spending sufficient experience. The chart below shows how many experience points are necessary before an Exalted becomes eligible to raise his Essence. Exalted experience does not count toward this total.


| Essence Rating | Celestial | Dragon-Blooded |
| -------------- | --------- | -------------- |
| 2              | 50        | -              |
| 3              | 125       | 75             |
| 4              | 200       | 250            |
| 5              | 300       | 325            |
| 6+             | ???       | ???            |
