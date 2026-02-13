---
cssclasses: clean-embeds
aliasses: [wizard, sorcerer, magician]
image: class_image.png
tags: [spellcaster, arcane]
combat_category: "Non-Martial"
requirements: "INT 9+, WIS 9+"
hplevel1: "4 + CON Mod"
hplevels2to10: "+1d4 + CON Mod per level"
hplevels11up: "+1 per level"
hitdie: "1d4 + CON Mod"
initbonus: "+0"
weapons: "small weapons & staffs"
armor: "none"
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
Mages are those who seek and use knowledge of the arcane. Their magic is a not a matter of faith (like the [[Cleric]]), but rather that of study and formulae. Mages are the worst of all the classes at fighting; hours spent studying massive tomes of magic do not lead a character to become strong or adept with weapons. They are the least hardy, having the least Hit Points and worst Saving Throws. However, their long hours of study of the arcane arts grant them awesome magical power beyond the ken of most mortals.

## Starting Equipment
- an Adventurer's Pack
- a `=this.file.name`'s Pack
- 2d6 silver

## `=this.file.name` Skills & Abilities

### Sense Magic
![[z. Class Abilities#Sense Magic]]

## Combat
They are considered a [[7. Weapon Proficiency#Martial, Semi-Martial, Non-Martial|Semi-Martial]] class.

### New Weapon Proficiencies
  
## After Reaching 10th Level

## `=this.file.name` Progression Table

### `=this.file.name` Abilities by Level
