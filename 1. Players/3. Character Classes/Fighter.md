---
cssclasses: clean-embeds
aliasses: [warrior]
image: class_image.png
tags: [warrior]
combat_category: "Martial"
requirements: "CON 9+, (STR or DEX 9+)"
hplevel1: "8 + CON Mod"
hplevels2to10: "+1d8 + CON Mod per level"
hplevels11up: "+2 per level"
hitdie: "1d8 + CON Mod"
initbonus: "+1"
weapons: "all"
armor: "all & shields"
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
Fighters include soldiers, guardsmen, barbarian warriors, and anyone else for whom fighting is a way of life. They train in combat, and they generally approach problems head-on, weapon in hand.

## Starting Equipment
- an Adventurer's Pack
- a `=this.file.name`'s Pack
- 2d6 silver

## `=this.file.name` Skills & Abilities

### Battle Mastery
![[z. Class Abilities#Battle Mastery]]

### Glancing Blow
![[z. Class Abilities#Glancing Blows]]

### Damage Dealer
![[z. Class Abilities#Damage Dealer]]

### Leadership
![[z. Class Abilities#Leadership]]

### Lore (military)
![[z. Class Abilities#Lore (military)]]

### Tactics
![[z. Class Abilities#Tactics]]

### Weapon Specialization
![[z. Class Abilities#Weapon Specialization]]

## Combat
Fighters can use all types of weapons and armor, and are considered a [[7. Weapon Proficiency#Martial]] class.

### New Weapon Proficiencies
Fighters gain a new weapon proficiency at level 3 and every 3 levels thereafter.
  
## After Reaching 10th Level
After reaching 10th level, if the fighter has built or taken control of a castle they can either petition the local powers to become a Lord or Lady, or simply declare themselves such if no one else has claim on the land.  After becoming gentry, they will begin attracting troops and settlers.  

Alternatively, they may choose to found a mercenary guild.  While they gain no land income, they will still attract troops.

## `=this.file.name` Progression Table
| <br>Level | <br>Experience | Hit<br>Dice | Attack<br>Bonus | Doom<br>Save | Ray<br>Save | Hold<br>Save | Blast<br>Save | Spell<br>Save | Save<br>Target | <br>Knacks |
| :-------: | -------------: | ----------: | :-------------: | :----------: | :---------: | :----------: | :-----------: | :-----------: | :------------: | :--------: |
|     1     |              0 |         1d8 |       +1        |      +4      |     +3      |      +2      |      +1       |      +0       |      16+       |     1      |
|     2     |          2,000 |         2d8 |       +1        |      +5      |     +4      |      +3      |      +2       |      +1       |      16+       |     1      |
|     3     |          4,000 |         3d8 |       +2        |      +6      |     +5      |      +4      |      +3       |      +2       |      16+       |     2      |
|     4     |          8,000 |         4d8 |       +3        |      +6      |     +5      |      +4      |      +4       |      +2       |      16+       |     2      |
|     5     |         16,000 |         5d8 |       +3        |      +7      |     +6      |      +5      |      +5       |      +3       |      17+       |     3      |
|     6     |         32,000 |         6d8 |       +4        |      +8      |     +7      |      +6      |      +5       |      +4       |      17+       |     3      |
|     7     |         64,000 |         7d8 |       +5        |      +9      |     +8      |      +7      |      +6       |      +5       |      17+       |     4      |
|     8     |        120,000 |         8d8 |       +5        |     +10      |     +9      |      +8      |      +7       |      +6       |      17+       |     4      |
|     9     |        240,000 |         9d8 |       +6        |     +11      |     +10     |      +9      |      +8       |      +7       |      17+       |     5      |
|    10     |        360,000 |        10d8 |       +7        |     +12      |     +11     |     +10      |      +9       |      +8       |      18+       |     5      |
|    11     |        480,000 |      10d8+2 |       +7        |     +12      |     +11     |     +10      |      +10      |      +8       |      18+       |     6      |
|    12     |        600,000 |      10d8+4 |       +8        |     +13      |     +12     |     +11      |      +11      |      +9       |      18+       |     6      |
|    13     |        720,000 |      10d8+6 |       +9        |     +14      |     +13     |     +12      |      +12      |      +10      |      18+       |     7      |
|    14     |        840,000 |      10d8+8 |       +9        |     +15      |     +14     |     +13      |      +13      |      +11      |      18+       |     7      |
|    15     |        960,000 |     10d8+10 |       +10       |     +16      |     +15     |     +14      |      +14      |      +12      |      19+       |     8      |
|    16     |      1,080,000 |     10d8+12 |       +11       |     +17      |     +16     |     +15      |      +14      |      +13      |      19+       |     8      |
|    17     |      1,200,000 |     10d8+14 |       +11       |     +17      |     +16     |     +15      |      +15      |      +13      |      19+       |     9      |
|    18     |      1,320,000 |     10d8+16 |       +12       |     +17      |     +17     |     +16      |      +16      |      +14      |      19+       |     9      |
|    19     |      1,440,000 |     10d8+18 |       +13       |     +17      |     +17     |     +17      |      +17      |      +15      |      19+       |     10     |
|    20     |      1,560,000 |     10d8+20 |       +13       |     +18      |     +18     |     +18      |      +18      |      +16      |      20+       |     10     |

### `=this.file.name` Abilities by Level
| <br><br>Level | <br><br>Leadership | <br>Lore<br>(military) | <br><br>Tactics | <br>Battle<br>Mastery | Glancing<br>Blow<br>Threshold | <br>Damage<br>Bonus | Specialized<br>Damage<br>Bonus |
|:-------------:|:------------------:|:----------------------:|:---------------:|:---------------------:|:-----------------------------:|:-------------------:|:------------------------------:|
|       1       |        10+         |           8+           |       9+        |          14+          |               1               |         +0          |               +1               |
|       2       |        10+         |           8+           |       9+        |          14+          |               1               |         +1          |               +2               |
|       3       |         9+         |           7+           |       8+        |          13+          |               2               |         +1          |               +3               |
|       4       |         9+         |           7+           |       8+        |          13+          |               2               |         +2          |               +4               |
|       5       |         8+         |           6+           |       7+        |          12+          |               3               |         +2          |               +5               |
|       6       |         8+         |           6+           |       7+        |          12+          |               3               |         +3          |               +6               |
|       7       |         7+         |           5+           |       6+        |          11+          |               4               |         +3          |               +7               |
|       8       |         7+         |           5+           |       6+        |          11+          |               4               |         +4          |               +8               |
|       9       |         6+         |           4+           |       5+        |          10+          |               5               |         +4          |               +9               |
|      10       |         6+         |           4+           |       5+        |          10+          |               5               |         +5          |              +10               |
|      11       |         5+         |           3+           |       4+        |          9+           |               6               |         +5          |              +11               |
|      12       |         5+         |           3+           |       4+        |          9+           |               6               |         +6          |              +12               |
|      13       |         4+         |           2+           |       3+        |          8+           |               7               |         +6          |              +13               |
|      14       |         4+         |           2+           |       3+        |          8+           |               7               |         +7          |              +14               |
|      15       |         3+         |           2+           |       2+        |          7+           |               8               |         +7          |              +15               |
|      16       |         3+         |           2+           |       2+        |          7+           |               8               |         +8          |              +16               |
|      17       |         2+         |           2+           |       2+        |          6+           |               9               |         +8          |              +17               |
|      18       |         2+         |           2+           |       2+        |          6+           |               9               |         +9          |              +18               |
|      19       |         2+         |           2+           |       2+        |          5+           |              10               |         +9          |              +19               |
|      20       |         2+         |           2+           |       2+        |          5+           |              10               |         +10         |              +20               |
