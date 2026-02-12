---
cssclasses: clean-embeds
aliasses: [killer, spy]
image: class_image.png
tags: [rogue]
combat_category: "Semi-Martial"
requirements: "STR 9+, DEX 9+, INT 9+"
hplevel1: "6 + CON Mod"
hplevels2to10: "d6 + CON Mod / level"
hplevels11up: "+2 / level"
hitdie: "1d6 + CON Mod"
initbonus: "+1"
weapons: "any"
armor: "light, shields"
---
> [!infobox|right ws-med]+
> ![[assassin.jpg]]
> ###### `=this.file.name`
> ```dataviewjs
> let pg = dv.current();
> let table = "###### Attributes";
> table += "\n| Attribute | Value |" +
>              "\n| --------- | ----- |";
>  dv.header(3, pg.title);
>  table += "\n| **Requirements:** | " + pg.requirements + " |";
>  table += "\n| **HP at Level 1:** | " + pg.hplevel1 + " |";
>  table += "\n| **HP for Levels 2 to 10:** | " + pg.hplevels2to10 + " |";
>  table += "\n| **HP for Levels 11+:** | " + pg.hplevels11up + " |";
>  table += "\n| **Hit Die:** | " + pg.hitdie + " |";
>  table += "\n| **Initiative:** | " + pg.initbonus + " |";
>  table += "\n| **Combat Category:** | " + pg.combat_category + " |";
>  table += "\n| **Weapons:** | " + pg.weapons + " |";
>  table += "\n| **Armor:** | " + pg.armor + " |";
>  dv.paragraph(table);
> ```

# `=this.file.name`

## Starting Equipment
- an Adventurer's Pack
- a `=this.file.name`'s Pack
- 4d6 silver

## `=this.file.name` Abilities
Assassins can use the following skills with the chance of success shown in the [[#Updated Assassin Table]]

### Climb Wall
To ascend or descend sheer cliffs or walls without need of climbing gear. If vertical, the surface must be rough or cracked. At least one check must be made per 100 feet of climbing. Failure indicates the climber has slipped and fallen at about the midpoint of the check and will suffer falling damage.  Climbing speed is 1/4 normal ground speed.
- **Retrying:** The character may immediately retry a failed climb attempt but must start over from the point to which they fell.
- **After Level 10:** This characters ability to climb becomes praeternatural and may climb surfaces that are nearly smooth as well as being able to climb surfaces beyond vertical (such as crawling along a ceiling).  Additionally, their climb speed increases to 1/2 normal walking speed.

### Decipher
A successful check allows this character to understand the gist of a non-magical text in a language they do not speak, unravel a cipher, or identify cryptically labelled landmarks on a map.
- **Time:** Time depends on the length of the text to be deciphered.
- **Retrying:** Only one attempt to read a document may be made unless some means of improving the odds are discovered or a new character level has been reached.
- **Natural 12:** On a roll of natural 12, the character is convinced that their translation is correct, though it definately is not.
- **After Level 10:** Magical texts and ciphers may be attempted, but at [[3d. Advantage and Disadvantage|Disadvantage]].  Arcane spell scrolls decoded in this way may be used as if this character were the proper spellcasting class, however, this requires a second check (without disadvantage) at a penalty equal to the spell's tier.  Failure may result in a [[9. Magic|mishap]].

### Disguise
Characters of any class may don disguises, but this character is a master of the art— able to create disguises that pass even close scrutiny.  The character may appear up to 5% taller or shorter and up to 10% lighter or heavier (but must remain within the same [[size category]]).  They may also appear as a different sex or species (at [[3d. Advantage and Disadvantage|Disadvantage]] if the chosen species is significantly different, such as a human attempting to appear as a [[lizard-folk]]).

**After Level 10:** This character can change their appearance so radically as to be able to change their apparent size category by 1 full step, and may even assume appearances of radically different species (like a humanoid attempting to appear as a non-humanoid creature).  Such attempts are made at [[3d. Advantage and Disadvantage|Disadvantage]], but the disadvantage for less extreme differences is removed.

### Listen
To hearken at a door and detect the faintest of noises on the other side, perceive the distant footfalls of a wandering monster, or distinguish a single voice in a
crowd. Six rounds (one minute) of concentrated listening are required.  More than 4 inches of wood, 3 inches of stone or 2 inches of metal will prevent this ability from working.

**After Level 10:** Double the amount of material that may be listened through.

### Open Locks
To pick locks or disable latching mechanisms of a non-magical nature. Thieves’ tools are required. 
- **Time:** Each attempt to pick a lock requires 1 Turn.
- **Retrying:** Additional attempts may only be made after the character has either gained a new level or found some means by which to improve their odds.
- **Natural 12:** On a roll of natural 12, the character must Save Versus Doom or accidentally jam the lock with their tools.
- **After Level 10:** Magical locks may be picked, but the roll is made at [[3d. Advantage and Disadvantage|Disadvantage]].

### Poison
This character is trained in the brewing of a great variety of [[poisons]] (and their antidotes).  This only applies to non-magical poisons.   Victims of a [[Poison|poisoning]] by this character suffer [[3d. Advantage and Disadvantage|Disadvantage]] to the saving throw.  Frequent exposure to poisons grant the assassin [[3d. Advantage and Disadvantage|Advantage]] on all saving throws and ability checks to resist poisons.
- **Time:** It takes a minimum of 1 [[Watch]] to brew a poison assuming all the ingredients are already on-hand.
- **Retrying:** A failed attempt ruins the poison and its ingredients and the character must start over again from scratch.
- **Natural 12:** On a roll of natural 12, the character must Save Versus Doom or accidentally poison themselves.
- **After Level 10:** Magical poisons may be brewed, but the roll is made at [[3d. Advantage and Disadvantage|Disadvantage]] unless this character has the assistance of a spellcaster.

### Search
This character is well-trained in finding hidden/secret doors, traps and the like.
- **Time:** It takes a minimum of 1 [[Turn]] to search a 10ft x 10ft x 10ft area or a Large or bigger object.  Medium or smaller objects take at least 1 minute to search.
- **Retrying:** Additional attempts may only be made after the character has either gained a new level or found some means by which to improve their odds.
- **Natural 12:** Treat as a normal failure.
- **After Level 10:** Searches only take 1/2 the normal time.

### Sneak Attack
When this character has *Advantage* on an attack, add the listed damage on the table below to the attack.  This ability will not work against targets immune to critical hits (like many undead and oozes) nor against targets more than 1 size category larger or smaller than the attacker.

### Stealth
**Hiding:** This character may make a Stealth Check to remain undetected when shadows are the only cover available.
**Sneaking:** If a [[Surprise Roll]] indicates that a thief’s party has been detected, the thief may make a Stealth Check to remain undetected.
Movement while using stealth is halved.
- **After Level 10:** The character becomes effectively invisible to both sight and sound while hiding.  They may also move full speed.

### Traps
To remove, set, or reset complex, clockwork-like traps. Separate checks must be made to accomplish each facet of this skill: set, remove, reset.  Also, a new trap may be built if the mechanism is simple and the parts available; anything more complex requires the assistance of an engineer. Thieves’ tools are required when practicing this ability.
- **Time:** Each attempt to disarm a trap requires 1 Turn.
- **Retrying:** Additional attempts may only be made after the character has either gained a new level or found some means by which to improve their odds.
- **Natural 12:** On a roll of natural 12, the character must Save Versus Doom or accidentally spring the trap.
- **After Level 10:** Magical traps may be disarmed, but the roll is made at [[3d. Advantage and Disadvantage|Disadvantage]].  Setting or resetting a magical trap requires the assistance of a spellcaster.

## Combat
Assassins cannot wear armor bulkier than leather but may use shields. They can use all types of weapons.  They are considered a [[7. Weapon Proficiency#Martial, Semi-Martial, Non-Martial|Semi-Martial]] class.

## Hirelings
Assassins of 1st–3rd level may not employ retainers, mercenaries, or specialists. From 4th level, an assassin may hire other assassins of lower level. From 8th level, an assassin may hire thieves, and from 12th level any type of character.

At 6th level, an assassin may seek or be sought out by
one or more henchmen, classed individuals (typical-
ly of similar class, race, and/or culture) who become
loyal followers. For more information, see Chapter 8:
Adventure, hirelings and henchmen.

## After Reaching 10th Level
An assassin may attempt to take over an existing guild of assassins or thieves by killing the old guild-master. This may be achieved by any means (e.g. poisoning, assassination, duel). If successful, the character can maintain a guild of 7d4 members. 75% of the existing members will leave, but new members (typically 1st level assassins) will arrive over time.

## New Weapon Proficiencies
Assassins gain a new weapon proficiency at level 4 and every 4 levels thereafter.

## `=this.file.name` Progression Table

| <br>Level | <br>Experience | Hit<br>Dice | Attack<br>Bonus | Doom<br>Save | Ray<br>Save | Hold<br>Save | Blast<br>Save | Spell<br>Save | Save<br>Target | <br>Knacks |
| :-------: | -------------: | ----------: | :-------------: | :----------: | :---------: | :----------: | :-----------: | :-----------: | :------------: | :--------: |
|     1     |              0 |         1d6 |       +0        |      +3      |     +2      |      +3      |      +0       |      +1       |      16+       |     0      |
|     2     |          1,750 |         2d6 |       +1        |      +3      |     +3      |      +4      |      +1       |      +2       |      16+       |     1      |
|     3     |          3,500 |         3d6 |       +1        |      +4      |     +4      |      +5      |      +2       |      +2       |      16+       |     1      |
|     4     |          7,000 |         4d6 |       +2        |      +4      |     +4      |      +5      |      +2       |      +3       |      16+       |     1      |
|     5     |         14,000 |         5d6 |       +2        |      +5      |     +5      |      +6      |      +3       |      +4       |      17+       |     2      |
|     6     |         28,000 |         6d6 |       +3        |      +6      |     +6      |      +7      |      +4       |      +5       |      17+       |     2      |
|     7     |         56,000 |         7d6 |       +4        |      +6      |     +7      |      +8      |      +5       |      +5       |      17+       |     2      |
|     8     |        112,000 |         8d6 |       +4        |      +7      |     +8      |      +9      |      +6       |      +6       |      17+       |     3      |
|     9     |        220,000 |         9d6 |       +5        |      +7      |     +9      |     +10      |      +7       |      +7       |      17+       |     3      |
|    10     |        330,000 |        10d6 |       +5        |      +8      |     +10     |     +11      |      +8       |      +8       |      18+       |     3      |
|    11     |        440,000 |      10d6+2 |       +6        |      +9      |     +10     |     +11      |      +8       |      +8       |      18+       |     4      |
|    12     |        550,000 |      10d6+4 |       +7        |      +9      |     +11     |     +12      |      +9       |      +9       |      18+       |     4      |
|    13     |        660,000 |      10d6+6 |       +7        |     +10      |     +12     |     +13      |      +10      |      +10      |      18+       |     4      |
|    14     |        770,000 |      10d6+8 |       +8        |     +10      |     +13     |     +14      |      +11      |      +11      |      18+       |     5      |
|    15     |        880,000 |     10d6+10 |       +8        |     +11      |     +14     |     +15      |      +12      |      +11      |      19+       |     5      |
|    16     |        990,000 |     10d6+12 |       +9        |     +12      |     +15     |     +16      |      +13      |      +12      |      19+       |     5      |
|    17     |      1,100,000 |     10d6+14 |       +9        |     +12      |     +15     |     +16      |      +13      |      +13      |      19+       |     6      |
|    18     |      1,210,000 |     10d6+16 |       +10       |     +13      |     +16     |     +17      |      +14      |      +14      |      19+       |     6      |
|    19     |      1,320,000 |     10d6+18 |       +11       |     +13      |     +17     |     +17      |      +15      |      +14      |      19+       |     6      |
|    20     |      1,430,000 |     10d6+20 |       +11       |     +14      |     +18     |     +18      |      +16      |      +15      |      20+       |     7      |
|           |                |             |                 |              |             |              |               |               |                |            |
### `=this.file.name` Abilities by Level

| <br>Level | Climb<br>Wall | <br>Decipher | <br>Disguise | <br>Listen | Open<br>Lock | <br>Poison | <br>Search | <br>Stealth | <br>Traps | Sneak<br>Attack |
|:---------:|:-------------:|:------------:|:------------:|:----------:|:------------:|:----------:|:----------:|:-----------:|:---------:|:---------------:|
|     1     |      5+       |     13+      |      8+      |     9+     |     10+      |    11+     |     8+     |     8+      |    10+    |      +1d6       |
|     2     |      5+       |     13+      |      8+      |     9+     |     10+      |    11+     |     8+     |     8+      |    10+    |      +1d6       |
|     3     |      5+       |     12+      |      7+      |     8+     |      9+      |    10+     |     8+     |     7+      |    9+     |      +1d6       |
|     4     |      5+       |     12+      |      7+      |     8+     |      9+      |    10+     |     7+     |     7+      |    9+     |      +1d6       |
|     5     |      4+       |     11+      |      6+      |     7+     |      8+      |     9+     |     7+     |     6+      |    8+     |      +2d6       |
|     6     |      4+       |     11+      |      6+      |     7+     |      8+      |     9+     |     7+     |     6+      |    8+     |      +2d6       |
|     7     |      4+       |     10+      |      5+      |     6+     |      7+      |     8+     |     6+     |     5+      |    7+     |      +2d6       |
|     8     |      4+       |     10+      |      5+      |     6+     |      7+      |     8+     |     6+     |     5+      |    7+     |      +2d6       |
|     9     |      3+       |      9+      |      4+      |     5+     |      6+      |     7+     |     6+     |     4+      |    6+     |      +3d6       |
|    10     |      3+       |      9+      |      4+      |     5+     |      6+      |     7+     |     5+     |     4+      |    6+     |      +3d6       |
|    11     |      3+       |      8+      |      3+      |     4+     |      5+      |     6+     |     5+     |     3+      |    5+     |      +3d6       |
|    12     |      3+       |      8+      |      3+      |     4+     |      5+      |     6+     |     5+     |     3+      |    5+     |      +3d6       |
|    13     |      2+       |      7+      |      2+      |     3+     |      4+      |     5+     |     4+     |     2+      |    4+     |      +4d6       |
|    14     |      2+       |      7+      |      2+      |     3+     |      4+      |     5+     |     4+     |     2+      |    4+     |      +4d6       |
|    15     |      2+       |      6+      |      2+      |     2+     |      3+      |     4+     |     4+     |     2+      |    3+     |      +4d6       |
|    16     |      2+       |      6+      |      2+      |     2+     |      3+      |     4+     |     3+     |     2+      |    3+     |      +4d6       |
|    17     |      2+       |      5+      |      2+      |     2+     |      2+      |     3+     |     3+     |     2+      |    2+     |      +5d6       |
|    18     |      2+       |      5+      |      2+      |     2+     |      2+      |     3+     |     3+     |     2+      |    2+     |      +5d6       |
|    19     |      2+       |      4+      |      2+      |     2+     |      2+      |     2+     |     2+     |     2+      |    2+     |      +5d6       |
|    20     |      2+       |      4+      |      2+      |     2+     |      2+      |     2+     |     2+     |     2+      |    2+     |      +5d6       |
