---
cssclasses: clean-embeds
aliasses: [rogue, burglar]
image: class_image.png
tags: [rogue]
combat_category: "Semi-Martial"
requirements: "DEX 9+, INT 9+"
hplevel1: "6 + CON Mod"
hplevels2to10: "+1d6 + CON Mod per level"
hplevels11up: "+1 per level"
hitdie: "1d6 + CON Mod"
initbonus: "+2"
weapons: "small & medium"
armor: "light armor & bucklers"
---
> [!infobox|right ws-med]+
> ![[this.image]]
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
>  table += "\n| **Category:** | " + pg.combat_category + " |";
>  table += "\n| **Weapon Training:** | " + pg.weapons + " |";
>  table += "\n| **Armor Training:** | " + pg.armor + " |";
>  dv.paragraph(table);
> ```

# `=this.file.name`
Thieves are those who take what they want or need by stealth, disarming traps and picking locks; or "borrowing" money from pockets, belt-pouches, etc. right under the nose of the "mark" without the victim ever knowing.[^1]

## Starting Equipment
- an Adventurer's Pack
- a `=this.file.name`'s Pack
- 6d6 silver

## `=this.file.name` skills & Abilities

### Climb
![[z. Class Abilities#Climb Wall]]

### Decipher
![[z. Class Abilities#Decipher]]

### Legerdemain
![[z. Class Abilities#Legerdemain]]

### Open Locks
![[z. Class Abilities#Open Locks]]

### Notice
![[z. Class Abilities#Perception]]

### Search

### Sneak Attack
![[z. Class Abilities#Sneak Attack]]

### Stealth
![[z. Class Abilities#Stealth]]

### Survival

### Traps
![[z. Class Abilities#Traps]]

## Combat
Because of their need for stealth and free movement, thieves cannot wear armour heavier than leather and cannot use shields larger than bucklers. They can use any Light or Medium weapon.  They are considered a [[7. Weapon Proficiency#Martial, Semi-Martial, Non-Martial|Semi-Martial]] class.

### New Weapon Proficiencies
 Thieves gain a new weapon proficiency at level 4 and every 4 levels thereafter.
  
## After Reaching 10th Level
A thief can establish a thief den, attracting 2d6 apprentices of 1st level. These thieves will serve the character with some reliability; however, should any be arrested or killed, the PC will not be able to attract apprentices to replace them. A successful thief might use these followers to start a Thieves’ Guild.

## `=this.file.name` Progression Table
| <br>Level | <br>Experience | Hit<br>Dice* | Attack<br>Bonus | Doom<br>Save | Ray<br>Save | Hold<br>Save | Blast<br>Save | Spell<br>Save | Save<br>Target | <br>Knacks |
| :-------: | -------------: | -----------: | :-------------: | :----------: | :---------: | :----------: | :-----------: | :-----------: | :------------: | :--------: |
|     1     |              0 |          1d6 |       +0        |      +3      |     +2      |      +3      |      +0       |      +1       |      16+       |     0      |
|     2     |          1,200 |          2d6 |       +1        |      +3      |     +3      |      +4      |      +1       |      +2       |      16+       |     1      |
|     3     |          2,400 |          3d6 |       +1        |      +4      |     +4      |      +5      |      +2       |      +2       |      16+       |     1      |
|     4     |          4,800 |          4d6 |       +2        |      +4      |     +4      |      +5      |      +2       |      +3       |      16+       |     1      |
|     5     |          9,600 |          5d6 |       +2        |      +5      |     +5      |      +6      |      +3       |      +4       |      17+       |     2      |
|     6     |         20,000 |          6d6 |       +3        |      +6      |     +6      |      +7      |      +4       |      +5       |      17+       |     2      |
|     7     |         40,000 |          7d6 |       +3        |      +6      |     +7      |      +8      |      +5       |      +5       |      17+       |     2      |
|     8     |         80,000 |          8d6 |       +4        |      +7      |     +8      |      +9      |      +6       |      +6       |      17+       |     3      |
|     9     |        160,000 |          9d6 |       +4        |      +7      |     +9      |     +10      |      +7       |      +7       |      17+       |     3      |
|    10     |        280,000 |         10d6 |       +5        |      +8      |     +10     |     +11      |      +8       |      +8       |      18+       |     3      |
|    11     |        400,000 |       10d6+1 |       +5        |      +9      |     +10     |     +11      |      +8       |      +8       |      18+       |     4      |
|    12     |        520,000 |       10d6+2 |       +6        |      +9      |     +11     |     +12      |      +9       |      +9       |      18+       |     4      |
|    13     |        640,000 |       10d6+3 |       +6        |     +10      |     +12     |     +13      |      +10      |      +10      |      18+       |     4      |
|    14     |        760,000 |       10d6+4 |       +7        |     +10      |     +13     |     +14      |      +11      |      +11      |      18+       |     5      |
|    15     |        880,000 |       10d6+5 |       +7        |     +11      |     +14     |     +15      |      +12      |      +11      |      19+       |     5      |
|    16     |      1,000,000 |       10d6+6 |       +8        |     +12      |     +15     |     +16      |      +13      |      +12      |      19+       |     5      |
|    17     |      1,120,000 |       10d6+7 |       +8        |     +12      |     +15     |     +16      |      +13      |      +13      |      19+       |     6      |
|    18     |      1,240,000 |       10d6+8 |       +9        |     +13      |     +16     |     +17      |      +14      |      +14      |      19+       |     6      |
|    19     |      1,360,000 |       10d6+9 |       +9        |     +13      |     +17     |     +17      |      +15      |      +14      |      19+       |     6      |
|    20     |      1,480,000 |      10d6+10 |       +10       |     +14      |     +18     |     +18      |      +16      |      +15      |      20+       |     7      |

### `=this.file.name` Abilities by Level

| <br>Level | <br>Climb | <br>Decipher | <br>Legerdemain | Open<br>Locks | <br>Notice | <br>Search | <br>Stealth | <br>Survival | <br>Traps | Sneak<br>Attack |
| :-------: | :-------: | :----------: | :-------------: | :-----------: | :--------: | :--------: | :---------: | :----------: | :-------: | :-------------: |
|     1     |    5+     |      --      |       12+       |      10+      |     7+     |     8+     |     8+      |      8+      |    10+    |      +1d4       |
|     2     |    5+     |      --      |       11+       |      10+      |     6+     |     7+     |     8+      |      8+      |    10+    |      +1d4       |
|     3     |    5+     |     12+      |       10+       |      9+       |     6+     |     7+     |     7+      |      7+      |    9+     |      +1d4       |
|     4     |    5+     |     12+      |       10+       |      9+       |     6+     |     7+     |     7+      |      7+      |    9+     |      +1d4       |
|     5     |    4+     |     11+      |       9+        |      8+       |     5+     |     7+     |     6+      |      7+      |    8+     |      +2d4       |
|     6     |    4+     |     11+      |       9+        |      8+       |     5+     |     6+     |     6+      |      7+      |    8+     |      +2d4       |
|     7     |    4+     |     10+      |       8+        |      7+       |     5+     |     6+     |     5+      |      7+      |    7+     |      +2d4       |
|     8     |    4+     |     10+      |       8+        |      7+       |     4+     |     6+     |     5+      |      6+      |    7+     |      +2d4       |
|     9     |    3+     |      9+      |       7+        |      6+       |     4+     |     6+     |     4+      |      6+      |    6+     |      +3d4       |
|    10     |    3+     |      9+      |       7+        |      6+       |     4+     |     5+     |     4+      |      6+      |    6+     |      +3d4       |
|    11     |    3+     |      8+      |       6+        |      5+       |     3+     |     5+     |     3+      |      6+      |    5+     |      +3d4       |
|    12     |    3+     |      8+      |       6+        |      5+       |     3+     |     5+     |     3+      |      6+      |    5+     |      +3d4       |
|    13     |    2+     |      7+      |       5+        |      4+       |     3+     |     5+     |     2+      |      6+      |    4+     |      +4d4       |
|    14     |    2+     |      7+      |       5+        |      4+       |     2+     |     4+     |     2+      |      5+      |    4+     |      +4d4       |
|    15     |    2+     |      6+      |       4+        |      3+       |     2+     |     4+     |     2+      |      5+      |    3+     |      +4d4       |
|    16     |    2+     |      6+      |       4+        |      3+       |     2+     |     4+     |     2+      |      5+      |    3+     |      +4d4       |
|    17     |    2+     |      5+      |       3+        |      2+       |     2+     |     4+     |     2+      |      5+      |    2+     |      +5d4       |
|    18     |    2+     |      5+      |       3+        |      2+       |     2+     |     3+     |     2+      |      5+      |    2+     |      +5d4       |
|    19     |    2+     |      4+      |       2+        |      2+       |     2+     |     3+     |     2+      |      4+      |    2+     |      +5d4       |
|    20     |    2+     |      4+      |       2+        |      2+       |     2+     |     3+     |     2+      |      4+      |    2+     |      +5d4       |
# Footnotes

[^1]: [[OSE Advanced Fantasy Player's Tome.pdf#page=76|APT, p.74]]