
# Introduction to Role-Playing Games

For those unfamiliar with tabletop roleplaying games, the objective is to build and experience a story together, via the tool of role-playing. This is accomplished by the group selecting a master-of-ceremonies, referred to as the _Game Master_, to guide the narrative and interpret the rules for the other players. Each of the other players will then craft their own character, known as a _Player Character_, according to established rules. Games are usually run as _Sessions_, which may be a one-off adventure, part of a larger _Campaign_, or even part of an _Epic_. It is a fairly free-form, collaborative, creative exercise, where everyone has a chance to build the world.

In a session, the players can be given any number of opportunities to interact with the world. These interactions can range from engaging in peaceful negotiations to staging coups, haggling for wares at a market to making your own equipment, running from the law to becoming the law, and so on. In general, if an action bears significance and there are established rules for said action, then the action can be performed, and if there are no established rules for an action the _Game Master_ has the authority to make their own rules.

Before beginning play it should be acknowledged that this text is a guide, that the players and the _Game Master_ have the power to ignore or modify these rules, provided the group as a whole agrees to the changes.

# Creating Your Player Character

Before creating your _Player Character_, you and your _Game Master_ must agree on whether the game will be using the _Basic_ or _Advanced_ ruleset. The rulesets are largely the same, but the _Advanced_ ruleset requires more math and bookkeeping, so for players who prefer to do less math and do not like taking notes, the _Basic_ ruleset might be preferred. Throughout the rest of this text, the _Basic_ ruleset will be assumed, with _Advanced_ variant rules mentioned in asides.

A character at its core requires three things: _Attributes_, a _Lineage_, and a _Class_. A background occupation can also be included, which may grant additional skills or modifiers. Players may also establish their character's _Alignment_, which can have an affect on their relationships with deities, non-playable characters, or even metaphysical concepts. Everything else, a character's appearance, gender, backstory, etc. are all for flavor and have little to no mechanical bearing on the playing of the character.

There is no explicit required combination of _Attributes_, _Lineage_, and _Class_; the only thing that matters is what do _you_ the player want to play. Some classes have suggestions for _Attributes_, to make playing them easier, but in the end, they are but suggestions, and you are free to ignore them. 

The caveat to this freedom is that some combinations of _Attribute_, _Lineage_, and _Class_ may result in a character that is simply un-fun to play. Character creation should be carefully coordinated between the players and the _Game Master_, to ensure everyone is able to contribute and have fun.

The only time there is an explicit requirement is in the case of multiclassing, which may require an _Attribute_ to be of a certain level before a second or more class can be obtained. Multiclassing will be explained in detail later on.

## Attributes

All characters are defined by three core _Attributes_: their _Body_, their _Mind_, and their _Soul_.
* _Body_ affects proficiency in combat, athletic abilities, endurance, Hit Points; in short, all physically-oriented attributes are derived from _Body_. If you are building a character with a heavy focus on combat, whether melee or ranged, this is the _Attribute_ to pay attention to.
* _Mind_ governs all mental attributes and abilities, such as mental fortitude, capacity to learn new things, and ability to focus under stress, in addition to other particulars, like magic use. Naturally, this is the most important attribute for spellcasters, like wizards, sorcerers, and summoners.
* _Soul_ determines connection to deities and to other people and creatures; it is your character's "heart", and is essential if you are playing a priest, bard, or druid. Regardless of character class, a little charisma or empathy can go a long way in negotiations, making this a vital _Attribute_ for diplomatic characters.

> **Advanced Attributes**
> 
> In the advanced ruleset, the _Attributes_ are a bit more granular, but still fall under the categories of _Body_, _Mind_, and _Soul_. The following is a general idea of what these _Advanced Attributes_ might be used for:
> * Body
>   * Strength - melee combat, lift capacity
>   * Dexterity - ranged combat, sleight of hand
>   * Constitution - maximum Hit Points, poison resistance
> * Mind
>   * Wisdom - wild magic, passive perception
>   * Intelligence - languages, book knowledge
>   * Focus - combat casting, attribute enhancer
> * Soul
>   * Faith - divine magic, communing with spirits
>   * Charisma - persuasion, performance, diplomacy
>   * Empathy - handling animals, sensing motives

### Attribute Scores

Each _Attribute_ has an _Attribute Score_, defined at character generation, and increased during character progression. A score of 5 represents the statistical "average" level for any given _Attribute_ for a character; 10 represents a "legendary" ability, while a 0 represents a complete absence of ability, which usually manifests as catatonia.

_Attribute Scores_ are determined primarily by two values: a _Base Score_ and a _Lineage Modifier_. Some backgrounds may also impart a bonus to attributes. Additionally, some items and abilities may temporarily increase your _Attribute Score_; this value is a _Temporary Modifier_. The total _Attribute Score_ then is the sum of these constituent parts. While the _Temporary Modifier_ frequently changes, the _Base Score_ and the _Lineage Modifier_ are usually static.

Note that it is perfectly acceptable for a character, playable or otherwise, to be "lacking" in an _Attribute_, and thus have a score under 5. Not all scores need to be above 5 for a character to be a viable adventurer.

### Dependent Attributes

In addition to the core _Attributes_ that define your character, there are other traits strongly influenced by the core _Attributes_. These are:

 - Hit Points - Health, how much damage can be taken before enterying a Dying state
 - Stamina Points - Capacity for exertion
 - Mana Points - Mystical energy, used for casting magic
 - Tech Points - Mental/corporeal energy, used for performing certain martial techniques
 - Fortitude - Strength of body, capacity to endure physical challenges
 - Reflex - Speed of body, capacity to react instinctively to danger
 - Willpower - Strength of mind and soul, capacity to endure mental challenges
 - Agility - Swiftness in combat
 - Initiative - Alertness, readiness for combat

Some dependent attributes are formulaic and increase every level. The table below shows how these values are calculated:

| Stat       | Base | Die | Attr Score (Basic) | Attr Score (Adv) |
|------------|------|-----|--------------------|------------------|
| Hit Points | 10   | d12 | Body               | CON              |
| Stamina    | 5    | d6  | Body               | CON              |
| Mana/Tech  | 10   | d8  | Class dep.         | Class dep.       |

To calculate the final values, the general formula is: 
> Base + Player Level * Attr Score + Player Level # Die Rolls

More simply, values at first level will be the **Base** plus the **Attribute Score** plus the result of the given **Die Roll**. On every level up, the player will again add the **Attribute Score** and another **Die Roll**.

If the player is not interested in taking chances, instead of rolling dice they may take half the max value of the relevant die (i.e. d12 -> 6, d8 -> 4, d6 -> 3). The _Attribute Score_ for Mana and Tech points is determined by classes, and the stat's score will only increase on _Class Level_ increases, instead of _Player Level_ increases; the same multiplier applies.

For Fortitude, Reflex, and Willpower, opportunities to increase are defined by the class, and the sum relies on the following attributes:

| Stat      | Attr Score (Basic) | Attr Score (Adv) |
|-----------|--------------------|------------------|
| Fortitude | Body               | CON              |
| Reflex    | Body               | DEX              |
| Willpower | Mind               | FOC              |

The calculation is then:
> Attr Score + (# of opportunities) * Attr Score

For faith-based characters (paladins, clerics, etc), Soul/FTH can be substituted for Mind/FOC for Willpower.

The final dependent attributes rarely change. _Initiative_ is based on a character's active or passive _Perception_ skill, according to the situation: it changes when the _Perception_ skill's score changes.

_Agility_ defines the number of actions a character (or monster) can take during a turn in combat. Calculating it involves the character's _Size_ and one _Basic_ (or two _Advanced_) _Attribute Scores_. 

The formula is as follows:
> (size base) + (Body - 5) / 2
>
> OR
>
> (size base) + (STR + DEX - 10) /2

The total _Agility_ score is always rounded to the nearest positive integer, but is always at least 1.

The base _Agility_ values per size are listed below:
| Size     | Base |
|:---------|:----:|
| Tiny     |   4  |
| Small    |   3  |
| Medium   |   2  |
| Large    |   1  |
| Huge     |  -1  |
| Gigantic |  -2  |
| Titanic  |  -4  |


### Picking Your Base Score
There are any number of methods for producing the base score for a character. Any method is valid, provided the group agrees to use it. Some suggestions are presented below:

#### Point Buy Method (Deterministic)

Each _Attribute Score_ starts at 5. The player is granted 3 points (6 if playing with _Advanced Attributes_) to allocate however they want. Furthermore, the player may take points from any _Attribute Score_ and move it to another. No score may be less than 3, nor higher than 7. For generating peasants or non-adventurers, do not give the character the 3 (or 6) bonus points.

#### Dice Roll Method (Random)

For each _Attribute_ the player rolls two six-sided dice (d6), takes the higher value, and adds 1. No score may be less than 3, nor higher than 7. For generating peasants or non-adventurers, the die with the lower value is used.

## Alignment


## Lineage

A character's _Lineage_ is their species, subspecies, mystical origin, etc. _Lineage_ can impart certain bonuses and penalties based on anatomical / metaphysical morphology. Examples include a negative modifier to strength for diminutive _Lineages_, or a positive modifier to wisdom for long-lived _Lineages_. Some _Lineages_ are hybrids of other _Lineages_, and as such may benefit or suffer from positive and negative modifiers from both of their parents.

Aside from simple mechanical differences, _Lineages_ can also provide flavor and substance to a _Player Character_. For instance, a sentient automata may be a curiosity, if not a minor celebrity, in a village of gnome engineers, but be ostracized and loathed in a commune of elvish druids. It is a good idea to discuss your character's _Lineage_ with your _Game Master_ before you begin your campaign, to ensure that your character's _Lineage_ suits the setting, and to establish expectations.

> **Lineage and Culture**
>
> A character's lineage does not dictate their cultural heritage. Depending on setting, there _may_ be a history of beings of a certain lineage having, or being perceived to have, a certain culture, but this is not universal nor guaranteed. Furthermore, the larger a population the greater its chances of diversifying, especially as it fragments and/or takes in those of other cultures. The same lineage can easily produce communities known for their all-encompassing love and acceptance, or feared for their extreme violence and xenophobia.

## Class

A class represents a character's training and expertise, less a job and more of a career path or a trade. The skills, techniques, abilities, and knowledge associated with a class are developed or earned through hard work and experience. Many weapons, armors, and tools, and most magics, _require_ that one have experience in an appropriate class before they can make effective use of the item or spell.

Choosing your starting class is a very important decision, and poor coordination between party members when selecting character classes can result in an unbalanced and ineffective party. Be sure to consider both the campaign setting and the class choices of your fellow players if you wish to improve your chances of building an effective character.

> **Multiclassing**
>
> While focusing on progressing with a single class often offers the simplest path to strength and competence, it may result in a character with limited utility. Branching out into a different class can grant flexibility in play style, and can create a character far more powerful than one restricted to the abilities and techniques of a single class.
>
> In order to multiclass, when a character has reached the agreed-upon criteria to advance in character level, they may choose to gain a level in a new class, provided they meet that class's multiclass criteria (usually _Attributes_ above a specified minimum).
>
> When calculating derived attributes like Hit, Mana, and Tech points, the values for the individual classes are calculated for each class according to their level, and then summed. These attributes and their roles will be discussed in a later section.


> **Playing Unclassed**
> 
> For the indecisive, or perhaps those interested in playing a Jack-of-all-trades, consider playing an "Unclassed" character. An unclassed character has no specialties or focuses, starts with no trained skills, and is largely restricted to common, non-class techniques. To compensate for these shortcomings, unclassed characters are given more skill points than any class, and are given the opportunity to acquire a common technique or ability _every_ level.
>
> On level-up, players can choose to advance in Unclassed, but only if they have not previously taken a level in any other class. Players also cannot multiclass _into_ Unclassed; once a character has started a class they can never become Unclassed. More details on being Unclassed are covered in the chapter on Classes.

## Skills

Skills represent the mundane abilities of an average adventurer, such as swimming, climbing, or lock picking, or in some cases more vague aspects of their capability, like grace, athleticism, or speechcraft. Some classes come with training in certain skills, which imparts a bonus during skill challenges. 

While many skills can be used untrained, some require experience in a specific class to properly utilize them; a severe penalty will be applied if a character attempts to rely on an untrained skill that requires training.

In addition to trained/untrained status, skills can also be allocated _Skill Points_ during character progression. The total number of _Skill Points_ a character can allocate is determined by their _Class Level_, multiplied by a modifier specified for that class. For multiclassed characters, the total is simply the sum of the _Skill Points_ per class. Skills that require a class cannot be allocated points if the character is not trained in that class.

The following table is a list of all skills, their class requirement, and the associated _Attributes_ (both Basic and Advanced).

| Skill           | Class | Attr (Basic) | Attr (Adv) |
|:----------------|:-----:|:------------:|:----------:|
| Acrobatics      |   -   |     Body     |     DEX    |
| Athletics       |   -   |     Body     |     STR    |
| Convince        |   -   |     Soul     |     CHA    |
| Deceive         |   -   |     Mind     |     INT    |
| Escape          |   X   |     Body     |     DEX    |
| Handle Animal   |   X   |     Soul     |     EMP    |
| Perception      |   -   |     Mind     |     WIS    |
| Perform         |   -   |     Soul     |     CHA    |
| Pilot           |   X   |     Mind     |     INT    |
| Ride            |   -   |     Body     |     DEX    |
| Stealth         |   -   |     Body     |     DEX    |
| Survival        |   X   |     Mind     |     WIS    |
| Tinker          |   X   |     Mind     |     WIS    |

> **Advanced Skills**
>
> If you want more granular skills, try substituting for the following. Note that not all substitutes rely on the same _Attributes_:
> | Skill             | Class | Attr (Basic) | Attr (Adv) |
> |:------------------|:-----:|:------------:|:----------:|
> | **Athletics**     |       |              |            |
> | > Climb           |   -   |     Body     |     STR    |
> | > Jump            |   -   |     Body     |     STR    |
> | > Swim            |   -   |     Body     |     STR    |
> | **Convince**      |       |              |            |
> | > Diplomacy       |   -   |     Soul     |     CHA    |
> | > Intimidate      |   -   |     Soul     |     CHA    |
> | **Deceive**       |       |              |            |
> | > Bluff           |   -   |     Soul     |     CHA    |
> | > Disguise        |   -   |     Mind     |     INT    |
> | > Sleight of Hand |   X   |     Body     |     DEX    |
> | **Perception**    |       |              |            |
> | > Detect          |   -   |     Mind     |     FOC    |
> | > Identify        |   -   |     Mind     |     INT    |
> | > Sense Motive    |   -   |     Mind     |     WIS    |
> | **Perform**       |       |              |            |
> | > Perform (Act)   |   -   |     Soul     |     CHA    |
> | > Perform (Inst)  |   -   |     Body     |     DEX    |
> | **Pilot**         |       |              |            |
> | > Pilot (Air)     |   X   |     Mind     |     INT    |
> | > Pilot (Land)    |   X   |     Mind     |     INT    |
> | > Pilot (Sea)     |   X   |     Mind     |     INT    |
> | **Ride**          |       |              |            |
> | > Ride Animal     |   -   |     Body     |     DEX    |
> | > Ride Vehicle    |   -   |     Body     |     DEX    |
> | **Survival**      |       |              |            |
> | > Forage          |   X   |     Mind     |     WIS    |
> | > Heal            |   X   |     Mind     |     INT    |
> | **Tinker**        |       |              |            |
> | > Disarm Device   |   X   |     Body     |     DEX    |
> | > Disassemble     |   X   |     Body     |     DEX    |
> | > Invent          |   X   |     Mind     |     INT    |
> | > Reassemble      |   X   |     Mind     |     INT    |

### Knowledge

Additionally, a character may have _Knowledge_ of various subjects, usually acquired through the course of their training or prior adventures. Knowledge acts similarly to regular skills, except for the fact that they all require training in a specific class.

| Knowledge        | Attr (Basic) | Attr (Adv) |
|:-----------------|:------------:|:----------:|
| Dungeoneering    |     Mind     |     WIS    |
| Engineering      |     Mind     |     INT    |
| Global           |     Mind     |     INT    |
| Local            |     Mind     |     WIS    |
| Linguistics      |     Mind     |     INT    |
| Materials        |     Mind     |     INT    |
| Military         |     Mind     |     WIS    |
| Mysticism        |     Mind     |     WIS    |
| Nature           |     Mind     |     WIS    |
| Nobility         |     Mind     |     INT    |
| Philosophy       |     Mind     |     INT    |
| Religion         |     Mind     |     INT    |
| Theater          |     Mind     |     WIS    |

> **Advanced Knowledge**
>
> If you want more granular categories of knowledge, try substituting for the following. Note that not all substitutes rely on the same _Attributes_:
> | Knowledge            | Attr (Basic) | Attr (Adv) |
> |:---------------------|:------------:|:----------:|
> | **Engineering**      |              |            |
> | > Architecture       |     Mind     |     INT    |
> | > Civil              |     Mind     |     INT    |
> | > Mechanisms (large) |     Mind     |     INT    |
> | > Mechanisms (small) |     Mind     |     INT    |
> | **Global**           |              |            |
> | > Geography (Global) |     Mind     |     INT    |
> | > Gossip (Global)    |     Mind     |     WIS    |
> | > History (Global)   |     Mind     |     INT    |
> | **Local**            |              |            |
> | > Geography (Local)  |     Mind     |     WIS    |
> | > Gossip (Local)     |     Mind     |     WIS    |
> | > History (Local)    |     Mind     |     INT    |
> | **Materials**        |              |            |
> | > Alchemy            |     Mind     |     WIS    |
> | > Chemistry          |     Mind     |     INT    |
> | > Metallurgy         |     Mind     |     INT    |
> | **Mysticism**        |              |            |
> | > Arcana             |     Mind     |     INT    |
> | > Astrology          |     Mind     |     WIS    |
> | > Esoterica          |     Mind     |     WIS    |
> | **Philosophy**       |              |            |
> | > Astronomy          |     Mind     |     INT    |
> | > Biology            |     Mind     |     INT    |
> | > Geology            |     Mind     |     INT    |
> | > Physics            |     Mind     |     INT    |
> | **Theater**          |              |            |
> | > Acoustics          |     Mind     |     WIS    |
> | > Literature         |     Mind     |     WIS    |

Descriptions of the nature and uses of these different fields of knowledge will be found later in this text.

### Skill Challenges

Throughout the course of an adventure it is likely for a player to be presented with a _Skill Challenge_. This is an event whereby the character needs to rely on a _Skill_ to perform a certain action. These challenges pit a known _Challenge Rating_ against the character's aptitude with a related _Skill_, plus a random value generated by the roll of a 20-sided die. The sum of the _Skill_ score and the result of the die roll is called a _Skill Check_.

The _Challenge Rating_ of an action is determined by the _Game Master_, and the only real rule is that the value be fair. Below is a table of suggested values for _Challenge Ratings_:
| Difficulty     | Score |
|:---------------|------:|
| Trivial        |   5   |
| Easy           |  10   |
| Medium         |  15   |
| Hard           |  20   |
| Legendary      |  25   |
| Impossible     |  30   |

> **Passive Skills**
>
> Some skills can be used passively. With these _Skills_, if they are declared to be performed passively, a d20 is not needed, and a flat value of 10 is substituted instead. Allocated points are not considered, but class bonus is.
> 
> Skills that can be used passively include:
> * Convince
> * Perception
> * Knowledge
> 
> and any other skill that makes sense for the character's background (e.g. Stealth, Perform).


> **Trained vs. Untrained vs. Class Skills**
> 
> As mentioned previously, training with a particular _Skill_ will impart a bonus during _Skill Challenges_, while attempting to perform a _Skill_ that requires class training without training in said class will incur a penalty. The bonus for a trained _Skill_ is **+3** while the penalty for an untrained class _Skill_ is **-10**.

Below is an example scenario, involving both untrained skill use and a passive skill:

> * Thog the Barbarian needs to sneak past a guard, lest he draw the attention of the entire fort.
> * Thog is not trained in _Stealth_, because barbarians do not usually sneak.
> * _Stealth_ is a skill that can be used untrained though, as conceptually, moving without being noticed is not that difficult.
> * As such, Thog may attempt to sneak, relying on his Body (DEX) score, along with whatever points have been allocated to his Stealth skill during the course of character progression.
> * Thog's player rolls a d20, and adds the result to Thog's Stealth score.
> * If the total is greater than the guard's passive perception, Thog succeeds, otherwise Thog fails.

### Degrees of Success and Failure

Success and failure are rarely binary. Instead, they often occur on a gradient. Below is a table of the enumerated degrees of success and failure, and the roll's difference from the _Skill Challenge_:

| Degree           |   | Difference |
|:-----------------|:-:|:----------:|
| Critical Failure | - |     >10    |
| Failure          | - |     2-10   |
| Minor Failure    | - |     1-2    |
| Minor Success    | + |     0-2    |
| Success          | + |     2-10   |
| Critical Success | + |     >10    |

Starting from the bottom, a _Critical Success_ occurs when a player's _Skill Check_ is 10 points or more higher than the _Challenge Rating_. A _Critical Success_ is flawless, demonstrating extreme luck, skill, or even divine intervention.

If the _Skill Check_ is between 2 and 10 points above the _Challenge Rating_, then it is a regular Success. This represents an average event, a well-practiced maneuver, a victory without any flair.

Matching the _Challenge Rating_ exactly, and up to 2 points above, results in a Minor Success, barely managing a task, but a success none-the-less.

Missing the _Challenge Rating_ by 1 or 2 points results in a Minor Failure. In many cases, a minor failure is a small, largely inconsequential mistake, and can be retried, assuming the challenge at hand isn't life-threatening.

A _Skill Check_ falling between 2 and 10 points below the _Challenge Rating_ leads to a regular Failure. These failures are too dramatic to be retried, but are ultimately nothing fantastic.

At 10 points or more below the _Challenge Rating_, the player has rolled a Critical Failure. A critical failure is devastating, the consequence of a severe lack of luck or skill, or even divine punishment.

Under certain circumstances, a success or failure can be upgraded or downgraded. For instance, succeeding in a separate Focus check can grant a single level upgrade, while failing an attempted Focus check will cause a downgrade by a level. 

In all cases, rolling a 20 will result in a double upgrade, allowing for a success even if the maximum total would only allow for a minor failure. Conversely, rolling a 1 will result in a double downgrade, turning what should have been a success into a minor failure, or a minor failure into a Critical Failure.

# Character Progression

The primary method by which a character can become stronger is by increasing their competence in one or more classes. A character's competence in their class is represented by their _Class Level_, which is increased after reaching certain milestones. These milestones can be reached through various means, such as by acquiring a set amount of _Experience Points_, if playing a game that uses _Experience Points_, or by GM fiat, such as after certain difficult battles, the conclusion of important scenarios, or in-game passage of time.

When a character reaches a level milestone, the player has the option to increase the level of a class they are already proficient in, or begin learning a new class, if they meet that class's prerequisites. By improving a known class, or acquiring a new one, a character may learn new abilities specific to that class. The sum of the levels of a character's known classes is the character's _Player Level_, or _Character Level_ for NPCs. 

In addition to class abilities, gaining levels also has the chance to improve the character's _Attributes_. If playing by Basic rules, an _Attribute Point_ is earned every four _Player Levels_, to spend on any basic _Attribute_. If playing by Advanced rules, an _Attribute Point_ is earned every other _Player Level_ to spend on any advanced _Attribute_. Upon increasing an _Attribute_, all _Skills_ and other character stats based on that _Attribute_ will improve accordingly.

After updating _Attributes_, it's time to allocate _Skill Points_, as described in the previous section on _Skills_. If the player has acquired a new class, and that class comes with training in _Skills_ the player did not know before, then these should also be marked and their scores updated.

The last stats to be updated are the dependent attributes, such as Hit Points, Stamina Points, and Mana/Tech Points. Follow the standard formulas for HP, SP, and MP/TP, and make adjustments to Fortitude, Reflex, and Willpower according to class multipliers. While not likely, if the _Agility_ score needs to be updated, remember to do so, as the number of actions per turn is very important in combat.
