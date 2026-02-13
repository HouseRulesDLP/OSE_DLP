---
cssclasses: clean-embeds
aliasses: [killer, spy]
image: class_image.png
tags: [rogue]
combat_category: "Semi-Martial"
requirements: "STR 9+, DEX 9+, INT 9+"
hplevel1: "6 + CON Mod"
hplevels2to10: "+1d6 + CON Mod per level"
hplevels11up: "+2 per level"
hitdie: "1d6 + CON Mod"
initbonus: "+1"
weapons: "all"
armor: "light armor & shields"
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
>  table += "\n| **Weapon Training:** | " + pg.weapons + " |";
>  table += "\n| **Armor Training:** | " + pg.armor + " |";
>  dv.paragraph(table);
> ```

# `=this.file.name`
Assassins are adventurers who specialise in the arts of infiltration and killing by stealth. They sometimes form guilds whereby their illicit services may be hired.[^1]

## Starting Equipment
- an Adventurer's Pack
- a `=this.file.name`'s Pack
- 4d6 silver

## `=this.file.name` Skills & Abilities
Assassins can use the following skills with the chance of success shown in the [[#Updated Assassin Table]]

### Climb Wall
![[z. Class Abilities#Climb Wall]]

### Decipher
![[z. Class Abilities#Decipher]]

### Disguise
![[z. Class Abilities#Disguise]]

### Open Locks
![[z. Class Abilities#Open Locks]]

### Perception
![[z. Class Abilities#Perception]]

### Poison
![[z. Class Abilities#Poison]]

### Sneak Attack
![[z. Class Abilities#Sneak Attack]]

### Stealth
![[z. Class Abilities#Stealth]]

### Traps
![[z. Class Abilities#Traps]]

## Combat
Assassins cannot wear armor bulkier than leather but may use shields. They can use all types of weapons.  They are considered a [[7. Weapon Proficiency#Martial, Semi-Martial, Non-Martial|Semi-Martial]] class.

### New Weapon Proficiencies
Assassins gain a new weapon proficiency at level 4 and every 4 levels thereafter.

## After Reaching 10th Level
An assassin may attempt to take over an existing guild of assassins or thieves by killing the old guild-master. This may be achieved by any means (e.g. poisoning, assassination, duel). If successful, the character can maintain a guild of 7d4 members. 75% of the existing members will leave, but new members (typically 1st level assassins) will arrive over time.

Alternatively, the character may build a new guild in a locale that does not already have an assassin's guild.  New members (typically 1st level assassins) will arrive over time.

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

| <br>Level | Climb<br>Wall | <br>Decipher | <br>Disguise | Open<br>Lock | <br>Perception | <br>Poison | <br>Stealth | <br>Traps | Sneak<br>Attack |
|:---------:|:-------------:|:------------:|:------------:|:------------:|:--------------:|:----------:|:-----------:|:---------:|:---------------:|
|     1     |      5+       |      --      |      8+      |     10+      |       9+       |    11+     |     8+      |    10+    |      +1d6       |
|     2     |      5+       |      --      |      8+      |     10+      |       9+       |    11+     |     8+      |    10+    |      +1d6       |
|     3     |      5+       |     12+      |      7+      |     10+      |       8+       |    10+     |     7+      |    10+    |      +1d6       |
|     4     |      5+       |     11+      |      7+      |      9+      |       8+       |    10+     |     7+      |    9+     |      +1d6       |
|     5     |      5+       |     11+      |      6+      |      9+      |       7+       |     9+     |     6+      |    9+     |      +2d6       |
|     6     |      4+       |     10+      |      6+      |      8+      |       7+       |     9+     |     6+      |    8+     |      +2d6       |
|     7     |      4+       |     10+      |      5+      |      8+      |       6+       |     8+     |     5+      |    8+     |      +2d6       |
|     8     |      4+       |      9+      |      5+      |      8+      |       6+       |     8+     |     5+      |    8+     |      +2d6       |
|     9     |      4+       |      8+      |      4+      |      7+      |       5+       |     7+     |     4+      |    7+     |      +3d6       |
|    10     |      4+       |      8+      |      4+      |      7+      |       5+       |     7+     |     4+      |    7+     |      +3d6       |
|    11     |      3+       |      7+      |      3+      |      6+      |       4+       |     6+     |     3+      |    6+     |      +3d6       |
|    12     |      3+       |      7+      |      3+      |      6+      |       4+       |     6+     |     3+      |    6+     |      +3d6       |
|    13     |      3+       |      6+      |      2+      |      6+      |       3+       |     5+     |     2+      |    6+     |      +4d6       |
|    14     |      3+       |      5+      |      2+      |      5+      |       3+       |     5+     |     2+      |    5+     |      +4d6       |
|    15     |      3+       |      5+      |      2+      |      5+      |       3+       |     4+     |     2+      |    5+     |      +4d6       |
|    16     |      2+       |      4+      |      2+      |      4+      |       3+       |     4+     |     2+      |    4+     |      +4d6       |
|    17     |      2+       |      4+      |      2+      |      4+      |       2+       |     3+     |     2+      |    4+     |      +5d6       |
|    18     |      2+       |      3+      |      2+      |      4+      |       2+       |     3+     |     2+      |    4+     |      +5d6       |
|    19     |      2+       |      2+      |      2+      |      3+      |       2+       |     2+     |     2+      |    3+     |      +5d6       |
|    20     |      2+       |      2+      |      2+      |      3+      |       2+       |     2+     |     2+      |    3+     |      +5d6       |
# Footnotes

[^1]: [[OSE Advanced Fantasy Player's Tome.pdf#page=32|APT, p.32]]