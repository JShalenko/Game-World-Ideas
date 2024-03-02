# Dice System
Utilizing a 2d12(maybe a 2d10 or 2d20 system if we like it later)
Checks are based on a success-difficulty system:
- Difficulty = # of successes needed to fully pass the skill challenge
	- May incorporate "half-success" for only passing half of the challenges
- Successes are granted if one matches or beats an appropriate skill DC(TBD)
	- Natural 12s count as 2 successes(could also be natural 20s or 10s later)
- With only 2 dice and no meta-currencies to add more, there are only 4 possible skill difficulties. Here are the chances of rolling them:

Let $x$ be the number to beat,  and let $S$ represent the smallest number of successes needed(otherwise known as the Difficulty), and assume that the maximum value of the dice are 12. Then

$$
P(S=1) = \frac{143 +2x - x^2}{144}
$$

$$
P(S = 2) = \frac{167 - 24x + x^2}{144}
$$

$$
P(S = 3) = \frac{25 - 2x}{144}
$$

$$
P(S = 4) = \frac{1}{144}
$$

---
# Stats
At the moment there are around 5 core stats in mind for the system. The base ideas for now are:
1. Brawn/Strength:
	- Overall ability to wield heavy objects and acts as a general strength stat
	- *May affect health in future(?)*
2. Agility/Finesse:
	- Precision based stat focusing on swiftness and the ability to move quickly
	- *may affect the ability to parry/dodge attacks(?)*
3. Endurance:
	- Stat centered around character ability to perform activities for long periods of time.
	- May affect "rate of fire" or "rate of attacks" for different weapons
		- *Possibly stamina resource for martials(?)*
4. Power:
	- Magic stat that centers around indulgence into differing fields of magic
		- Gives players a "magic point" that they are able to invest into on of many different magic skills (TBD)
	- May negatively affect Health proportional to character "Indulgence"
		- ***Means of which TBD***
5. Mana(?):
	- Magic stat that grants players the ability to utilize their spells & provides a resource pool
		- ***Could possibly be used for non-casters utilizing magic items instead of charges(?)***
		- ***Might be tied to Endurance in how many spells can be used at once or how much before burnout(?)***

### Q: What if players run out of either resource pool?
### A: Players will be able to utilize their abilities(at least one more time) at a risk or much higher cost (mechanics TBD).

--- 
# Other Possible Ideas
1. Capstone abilities/features interwoven into skill development/point allocation for incentive
2. Possible free deployment action on initiative for all combatants (*or only players(?)*)
3. Criticals on generating more successes than necessary (# of extra needed TBD)

---
# Next Big Questions:
1. What races exist in the setting? Humans only? Elves? Dwarves? *Custom system-specific races?*
2. Without the incorporation of classes, will the system incorporate something similar? Will it have Roles and specific abilities like in *Cyberpunk RED*? Will it be like Career Skills from *Warhammer Fantasy 2nd Edition*? Will none of these exist, and instead feats will be the metric for character development? If so, do we make a lot of very specific feats, or more generalized ones? Both?
