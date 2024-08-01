---
tags:
  - source/solar-book
---
In Exalted, the words of prophets, courtiers, and princes carry as much power as a warrior’s sword or a sorcerer’s magic. Social influence is the system used for resolving interactions in which characters attempt to manipulate, persuade, or coerce each other. With the social actions listed below, characters can gain the trust of others and then use that to influence them, changing or shaping their beliefs over the course of a conversation, oration, or artistic performance.
# Overview
Social influence in Exalted revolves around [[Intimacy|Intimacies]]. In terms of gameplay, you’re either going to be *influencing someone’s outlook* (by creating, destroying, strengthening, or weakening Intimacies), or using Intimacies to *persuade someone to do what you want*. Intimacies are the core of this system.

Without exploiting an [[Intimacy]], [[Persuade|persuasion]] isn’t possible. No matter how charismatic you might be, a stranger won’t give over his life to your cause just because you say so— there has to be a reason to make him take such course of action. Perhaps they trust and respect you; perhaps they hate someone you’ve set yourself against; perhaps by doing so, they’ll further their own goals or stand up for what they believe in. All such motives are described by Intimacies. **In short: You need to play on an [[Intimacy]] to be able to talk people into doing things you want them to do. The stronger the [[Intimacy]], the more you can convince people to do in its name.**

Specifically, most [[#Social Actions]] utilise an [[Influence roll]], which accounts for the presence and relative strength of a target's Intimacies.
# [[Order]] of Actions
[[Combat Action]] don’t usually have special timing—there are no “Social turns.” When multiple characters attempt social actions in the same scene, who rolls when can be decided by the natural flow of the conversation, or by procedure (in a court, for example, there are strict rules regarding who speaks when). If two characters are both trying to present different arguments to a single individual, then that individual’s player decides who to listen to first. If it’s still not clear who acts in which order, then the characters with the highest ([[Wits]] + [[Socialize]]) go first, with the Storyteller breaking any ties.

[[Combat Action]] in combat operate as a miscellaneous action
# [[Social Actions]]
```dataview
TABLE WITHOUT ID
FROM #Action/social
```
```dataview
TABLE WITHOUT ID file.link AS "Name", contains(file.etags, "Action/social/influence") AS "Uses [[Influence roll]]"
FROM #Action/social
SORT file.ctime
```
## Retrying [[Social Actions]]
Each [[#Social Actions|social action]] has different conditions under which it may be retried. See the individual files.
# [[Appearance]]
While the [[Appearance]] Attribute may be rolled as part of social actions, it also has another function in social influence, granting a bonus against weak-willed characters. Those of low [[Resolve]] are more easily impressed and awed by striking, beautiful individuals, or easily [[Threaten|intimidated]] by the [[Hideous|profoundly ugly]].

If a character’s [[Appearance]] rating is higher than his target’s [[Resolve]], then he gains a dice bonus on all [[Instill]] and [[Persuade|persuasion]] attempts against that individual equal to the difference. Thus, a character with [[Appearance]] 5 attempting to use a persuade action on an individual with [[Resolve]] 3 would gain a +2 bonus. This comparison is made before any bonuses to [[Resolve]] are factored in.

If addressing a group (p. 220), compare [[Appearance]] to the average [[Resolve]] of the group (usually 2 or 3) to determine any appropriate bonus.
# Social Complications
A number of considerations may arise when winning friends and influencing people:
## One Target vs. Many Targets
Sometimes, a character may wish to make a single [[Influence roll]] against multiple characters. He can choose to target only a select group, or to apply the influence roll against anyone who hears him. However, people find it easier to ignore arguments that are not directly addressed to them. **Whenever an influence roll targets more than one character, it suffers a -3 penalty.**

Because the different targets of an influence roll can have varying [[Resolve]] ratings, the success or failure of the action is determined separately for each target.
<details><summary>Example</summary>A [[Dawn]] Caste who rolls four successes to threaten a mercenary cadre into backing down from a fight might successfully intimidate the rank and file with [[Resolve]] 2, but not the unit’s God-Blooded leader with [[Resolve]] 5.</details>
## Written [[Social Actions]]
The written word can be used to persuade or manipulate others just as easily as speech or whisper. Characters who wish to convey influence through a letter, pamphlet, book, or other written work do so as a written [[Social Actions|social action]]. The time taken to create a written missive varies based on the form and length of the work. The Storyteller decides how long it takes, with a minimum time of five minutes in most cases. Likewise, the time needed to read the missive is decided by the Storyteller based on length.

The Ability used when rolling for a written social action is always [[Linguistics]]. When a character reads the message, compare the successes rolled for it to his [[Resolve]] to determine if it succeeds, as with normal [[Influence roll|influence rolls]]. Written social actions can be written to apply either against a single intended reader or against anyone who reads them, with the usual effects for [[#One Target vs. Many Targets|targeting multiple characters]].
## Gestures and Body [[Language]]
When a character attempts to communicate through gestures, appearance, and body language alone, the target of such silent influence adds +2 to his [[Resolve]]. This is normally only useful for attempts at intimidation or seduction, but players are free to be creative and think up with other applications. Many things are impossible to communicate silently—no amount of hand-waving or quirked eyebrows can explain the intricacies of a First Age relic or the intricate politics of a Dynastic household. 

This penalty doesn’t apply to any true [[Language#Sign languages|sign language]], or [[Inspire]] actions using dance.
## Overturning [[Influence]]
<details><summary>Imagine this scenario—</summary>
Rellus the Glorious Mantle of [[Dawn]], warrior of the [[Dawn]] Caste, is speaking with his Lunar lover, who has a standing grudge against the [[Mask of Winters]]. She persuades him to round up his Marukani followers and ride against the Mask’s armies, using a persuade action. Upon hearing of his forces mobilizing, a Sidereal approaches Rellus and attempts to convince him that his planned war is ill-omened, and that he would be better off seeking allies rather than taking on the Deathlord alone. Rellus has already been persuaded—how to resolve this situation?
</details>

Characters in the world of Exalted are generally loath to abandon a course of action one they’ve set themselves upon it, and so overturning existing social influence with additional social influence is difficult. 

First, a character who has already been persuaded to do something receives a +3 bonus to his [[Resolve]] against any influence that would cause him to abandon or disregard that persuasion. This bonus stacks with the [[Intimacy]] bonus from a relevant [[Intimacy]]. 

Second, a petitioner who wishes to overturn existing persuasive influence must spend a point of [[Willpower]] before making her argument and roll. So, in the above example, the Sidereal must spend a point of [[Willpower]] to impress upon Rellus the dire urgency of the omens she has foreseen—and Rellus’s [[Resolve]] is automatically at +3 to resist her influence, before Intimacies come into play

If the contradictory persuasion succeeds, the targeted character may use a [[Influence roll#Decision Points|Decision Point]] to resist it by citing a conflicting [[Intimacy]], *without spending a point of [[Willpower]] to initiate the Decision Point*—it’s easier to stand by a hard-fought decision than to abandon it and reverse yourself. Conversely, if he wants to abandon his present course of action and accept the new influence, the character must spend a point of [[Willpower]] and cite the [[Intimacy]] which was used to change his mind.

It’s possible to use these rules to model several reversals, so long as each new argument put forward pulls on a different [[Intimacy]] than all those before (which have previously been refuted, similar to [[Influence roll#Lengthy Debates]]). These conditions remain in place for one [[Time#Story|story]] after a character has been influenced to take a course of action—once the next story begins, any lingering influence can be overturned with an ordinary persuasion, bribery, or intimidation attempt.