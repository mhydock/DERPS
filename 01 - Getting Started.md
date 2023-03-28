
# Introduction to Role-Playing Games

For those unfamiliar with tabletop roleplaying games, the main conceit is for each player to craft their own characters, according to established rules and guides, and for a designated narrator, usually referred to as the _Dungeon Master_ or _Game Master_, to weave an adventure for the players' characters. Games are usually run as _Sessions_, which may be a one-off adventure, part of a larger _Campaign_, or even part of an _Epic_. It is a fairly free-form, collaborative, creative exercise, where everyone has a chance to build the world and tell their story.

In a session, the players can be given any number of opportunities to interact with the world. These interactions can range from engaging in peaceful negotiations to staging coups, haggling for wares at a market to making your own equipment, running from the law to being the law, and so on and so forth. In general, if there are established rules for an action the action can be performed, and if there are not established rules for an action the Game Master has the authority to make their own rules. The Game Master also has the right to ignore or modify the rules in this text, provided the other players agree to the changes.

# Creating Your Character

Before creating your character, you and your Game Master must agree on whether the game will be using the _Basic_ or _Advanced_ ruleset. The rulesets are largely the same, but the _Advanced_ ruleset requires more math and bookkeeping, so for players who prefer to do less math and do not like taking notes, the _Basic_ ruleset might be preferred. Throughout the rest of this text, the _Basic_ ruleset will be assumed, with _Advanced_ variant rules mentioned in asides.

A character at its core requires three things: base attributes, a lineage, and a class. A background occupation can also be included, which may grant additional skills or modifiers. Optionally, if players are interested in the concept of "Alignment" then they may choose this during creation as well. Everything else, a character's appearance, gender, backstory, etc. are all for flavor and have little to no mechanical bearing on the playing of the character.

It should be noted that there is no explicit required combination of attributes, lineage, and class. An orc can be a paladin, a fighter can have cripplingly-low strength; the only thing that matters is what do _you_ the player want to play. Some classes have suggestions for base attributes, to make playing them easier, but in the end, they are but suggestions, and you are free to ignore them. The only time this is not the case is when multiclassing, which may require an attribute to be of a certain level before a second or more class can be obtained. Multiclassing will be explained in detail later on.

## Base Attributes

All characters are defined by three core attributes: their _Body_, their _Mind_, and their _Soul_.
* The _Body_ attribute affects one's proficiency in combat, athletic abilities, endurance, Hit Points; in short, all physically-oriented attributes are derived from _Body_. If you are building a character with a heavy focus on combat, whether melee or ranged, this is the attribute to pay attention to.
* The _Mind_, on the other hand, governs all mental attributes and abilities, such as one's mental fortitude, their capacity to learn new things, and their ability to focus under stress, in addition to other particulars, like magic use. Naturally, this is the most important attribute for spellcasters, like wizards, sorcerers, and summoners.
* Finally, the _Soul_ attribute is the attribute that determines one's connection to deities and to other people and creatures; it is your character's "heart", and is essential if you are playing a priest, bard, or druid. Regardless of character class, a little charisma or empathy can go a long way in negotiations, making this a vital attribute for diplomatic characters.

> **Advanced Attributes**
> 
> In the advanced ruleset, the attributes are a bit more granular, but still fall under the categories of Body, Mind, and Soul. The following is a general idea of what these granular attributes might be used for:
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

### Attribute Scores and Modifiers

Each attribute has an _Attribute Score_ and an _Attribute Modifier_ attached to it. An Attribute Score is defined at character generation, and can be increased during character progression. A score of 10 represents the statistical average level for any given attribute for a character. An Attribute Modifier is derived from the Attribute Score, and is simply the score minus 10.

Note that it is perfectly acceptable for a character, playable or otherwise, to be "lacking" in an attribute, and thus have a score under 10. Not all scores need to be above 10 for a character to be a viable adventurer.

Attribute Scores are determined primarily by two values: a _Base Score_ and a _Lineage Modifier_. Some backgrounds may also impart a bonus to attributes. Additionally, some items and abilities may temporarily increase your Attribute Score; this value is a _Temporary Modifier_. The total Attribute Score then is the sum of these constituent parts. While the Temporary Modifier frequently changes, the Base Score and the Lineage Modifier are usually static.

Generating the Base Score of an attribute can be performed in the following ways:

#### Point Buy Method (Deterministic)

Each attribute starts at 10. The player is granted 3 points (6 if playing with advanced attributes) to allocate however they want. Furthermore, the player may take points from any attribute and move it to another. No score may be less than 7, nor higher than 13. For generating peasants or non-adventurers, do not give the character the 3 (or 6) bonus points.

#### Dice Roll Method (Random)

For each attribute the player rolls two ten-sided dice (d10), takes the higher value, and adds 5. No score may be less than 7, nor higher than 13. For generating peasants or non-adventurers, the die with the lower value is used.

### Dependent Attributes

In addition to the base attributes that define your character, there are other attributes strongly influenced by the base attributes. These are:

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

| Stat       | Base | Lvl Multi. | Die | Attr Mod (Basic) | Attr Mod (Adv) |
|------------|------|------------|-----|------------------|----------------|
| Hit Points | 10   | 1x         | d12 | Body             | CON            |
| Stamina    | 5    | 0.5x       | d6  | Body             | CON            |
| Mana/Tech  | 10   | 1x         | d8  | Class dep.       | Class dep.     |

To calculate the final values, the general formula is: 
> Base + Lvl Multi * Player Level * Attr Mod + Player Level # Die Rolls

If the Attribute Modifier is negative, then this value is subtracted instead of added. These stats may not be lower than their Base values. If the player is not interested in taking chances, instead of rolling dice they may take half the max value of the relevant die (i.e. d12 -> 6, d8 -> 4, d6 -> 3). The Attribute Modifier for Mana and Tech points is determined by classes, and the stat's score will only increase on Class Level increases, instead of Player Level increases; the same multiplier applies.

For Fortitude, Reflex, and Willpower, the Level Multiplier is defined by the class, and the sum relies on the following attributes:

| Stat      | Attr Mod (Basic) | Attr Mod (Adv) |
|-----------|------------------|----------------|
| Fortitude | Body             | CON            |
| Reflex    | Body             | DEX            |
| Willpower | Mind             | FOC            |

The calculation is then:
> Attr Mod + Level Multiplier * Attr Mod

In cases where the attribute modifier is less than or equal to 0, the value used in calculations will instead be 1.

For faith-based characters (paladins, clerics, etc), Soul/FTH can be substituted for Mind/FOC for Willpower.

The final dependent attributes rarely change. Initiative is based on a character's active or passive Perception skill, according to the situation: it changes when the Perception skill's score changes.

Agility defines the number of actions a character (or monster) can take during a turn in combat. Calculating it involves the character's size and one basic (or two advanced) attribute modifiers. 

The formula is as follows:
> (size base) + Body / 5
>
> OR
>
> (size base) + (STR + DEX) / 10

The modifier part is rounded up if positive (more positive) and rounded down if negative (more negative). The agility is always at least 1.

The base agility values per size are listed below:
| Size     | Base |
|:---------|:----:|
| Tiny     |   4  |
| Small    |   3  |
| Medium   |   2  |
| Large    |   1  |
| Huge     |  -1  |
| Gigantic |  -2  |
| Titanic  |  -4  |

## Lineage

A character's lineage is their species, subspecies, mystical origin, etc. Lineage can impart certain bonuses and penalties based on anatomical morphology. Examples include a negative modifier to strength for diminutive lineages, or a positive modifier to wisdom for long-lived lineages. Some lineages are hybrids of other lineages, and as such may benefit or suffer from positive and negative modifiers from both of their parents.

Aside from simple mechanical differences, lineages can also provide flavor and substance to a narrative. For instance, a sentient automata may be a curiosity, if not a minor celebrity, in a village of gnome engineers, but be ostracized and loathed in a commune of elvish druids. It is a good idea to discuss your character's lineage with your Game Master before you begin your campaign, to ensure that your character's lineage suits the setting, and to establish expectations.

> **Lineage and Culture**
>
> A character's lineage does not dictate their cultural heritage. Depending on setting, there _may_ be a history of beings of a certain lineage having, or being perceived to have, a certain culture, but this is not universal nor guaranteed. Furthermore, the larger a population the greater its chances of diversifying, especially as it fragments and/or takes in those of other cultures. The same lineage can easily produce communities known for their all-encompassing love and acceptance, or feared for their extreme violence and xenophobia.

## Class

A class represents a character's training and expertise, less a job and more of a career path or a trade. The skills, techniques, abilities, and knowledge associated with a class are developed or earned through hard work and experience. Many weapons, armors, and tools, and most magics, _require_ that one have experience in an appropriate class before they can make effective use of the item or spell.

Choosing your starting class is a very important decision, and poor coordination between party members when selecting character classes can result in an unbalanced and ineffective party. Be sure to consider both the campaign setting and the class choices of your fellow players if you wish to improve your chances of building an effective character.

> **Multiclassing**
>
> While focusing on progressing with a single class often offers the simplest path to strength and competence, sometimes it results in a stunted character with limited utility. Branching out into a different class can grant flexibility in play style, and can create a character far more powerful than one restricted to the abilities and techniques of a single class.
>
> In order to multiclass, when a character has reached the agreed-upon criteria to advance in character level, they may choose to gain a level in a new class, provided they meet that class's multiclass criteria (usually base attributes above a specified minimum).
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

In addition to trained/untrained status, skills can also be allocated _Skill Points_ during character progression. The total number of Skill Points a character can allocate is determined by the level of their class, multiplied by a modifier specified for that class. For multiclassed characters, the total is simply the sum of the Skill Points per class. Skills that require a class cannot be allocated points if the character is not trained in that class.

The following table is a list of all skills, their class requirement, and the associated attributes (both Basic and Advanced).

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
> If you want more granular skills, try substituting for the following. Note that not all substitutes rely on the same attributes:
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
> If you want more granular categories of knowledge, try substituting for the following. Note that not all substitutes rely on the same attributes:
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

Throughout the course of an adventure it is likely for a player to be presented with a _Skill Challenge_. This is an event whereby the character needs to rely on a skill to perform a certain action. These challenges pit a known _Challenge Rating_ against the character's aptitude with a related skill, plus a random value generated by the roll of a 20-sided die.

> **Passive Skills**
>
> Some skills can be used passively. With these skills, if they are declared to be performed passively, a d20 is not needed, and a flat value of 10 is substituted instead. Allocated points are not considered, but class bonus is.
> 
> Skills that can be used passively include:
> * Convince
> * Perception
> * Knowledge
> 
> and any other skill that makes sense for the character's background (e.g. Stealth, Perform).

Below is a possible scenario, involving both untrained skill use and a passive skill:

> * Thog the Barbarian needs to sneak past a guard, lest he draw the attention of the entire fort.
> * Thog is not trained in sneaking, because barbarians do not usually sneak.
> * Sneaking is a skill that can be used untrained though, as conceptually, sneaking is not that difficult.
> * As such, Thog may attempt to sneak, relying on his Body (DEX) score, along with whatever points have been allocated to his Stealth skill during the course of character progression.
> * Thog's player rolls a d20, and adds the result to Thog's Stealth score.
> * If the total is greater than the guard's passive perception, Thog succeeds, otherwise Thog fails.

> **Trained vs. Untrained vs. Class Skills**
> 
> As mentioned previously, training with a particular skill will impart a bonus during skill challenges, while attempting to perform a skill that requires class training without training in said class will incur a penalty. The bonus for a trained skill is **+3** while the penalty for an untrained class skill is **-10**.

### Degrees of Success and Failure

Success and failure are rarely binary. Instead, they often occur on a gradient. Below is a table of the enumerated degrees of success and failure, and the roll's difference from the skill challenge:

| Degree           |   | Difference |
|:-----------------|:-:|:----------:|
| Critical Failure | - |     >10    |
| Failure          | - |     2-10   |
| Minor Failure    | - |     1-2    |
| Minor Success    | + |     0-2    |
| Success          | + |     2-10   |
| Critical Success | + |     >10    |

Starting from the bottom, a Critical Success occurs when a player's skill check is 10 points or more higher than the skill challenge. A critical success is flawless, demonstrating extreme luck, skill, or even divine intervention.

If the skill check is between 2 and 10 points above the skill challege, then it is a regular Success. This represents an average event, a well-practiced maneuver, a victory without any flair.

Matching the skill check exactly, and up to 2 points above, results in a Minor Success, barely managing a task, but a success none-the-less.

Missing the skill check by 1 or 2 points results in a Minor Failure. In many cases, a minor failure is a small, largely inconsequential mistake, and can be retried, assuming the challenge at hand isn't life-threatening.

A skill check falling between 2 and 10 points below the skill challenge leads to a regular Failure. These failures are too dramatic to not be retried, but are ultimately nothing fantastic.

At 10 points or more below the skill challenge, the player has rolled a Critical Failure. A critical failure is devastating, the consequence of a severe lack of luck or skill, or even divine punishment.

Under certain circumstances, a success or failure can be upgraded or downgraded. For instance, succeeding in a separate Focus check can grant a single level upgrade, while failing an attempted Focus check will cause a downgrade by a level. 

In all cases, rolling a 20 will result in a double upgrade, allowing for a success even if the maximum total would only allow for a minor failure. Conversely, rolling a 1 will result in a double downgrade, turning what should have been a success into a minor failure, or a minor failure into a Critical Failure.

# Character Progression

The primary method by which a character can become stronger is by increasing their competence in one or more classes. A character's competence in their class is represented by their Class Level, which is increased after reaching certain milestones. These milestones can be reached through various means, such as by acquiring a set amount of experience points, if playing a game that uses experience points, or by GM fiat, such as after certain difficult battles, the conclusion of important scenarios, or in-game passage of time.

When a character reaches a level milestone, the player has the option to increase the level of a class they are already proficient in, or begin learning a new class, if they meet that class's prerequisites. By improving a known class, or acquiring a new one, a character may learn new abilities specific to that class. The sum of the levels of a character's known classes is the character's Player Level, or Character Level for NPCs. 

In addition to class abilities, gaining levels also has the chance to improve the character's attributes. If playing by Basic rules, an attribute point is earned every four Player Levels, to spend on any basic attribute. If playing by Advanced rules, an attribute point is earned every other Player Level to spend on any advanced attribute. Upon increasing an attribute, all skills and other character stats based on that attribute will improve accordingly.

After updating attributes, it's time to allocate skill points, as described in the previous section on Skills. If the player has acquired a new class, and that class comes with training in skills the player did not know before, then these should also be marked and their scores updated.

The last stats to be updated are the dependent attributes, such as Hit Points, Stamina Points, and Mana/Tech Points. Follow the standard formulas for HP, SP, and MP/TP, and make adjustments to Fortitude, Reflex, and Willpower according to class multipliers. While not likely, if the Agility score needs to be updated, remember to do so, as the number of actions per turn is very important in combat.
