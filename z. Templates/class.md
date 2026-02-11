---
cssclasses: clean-embeds
aliasses: []
image: class_image.png
tags: []
combat_category: ""
requirements: ""
hplevel1: "{num} + CON Mod"
hplevels2to10: "{die} + CON Mod / level"
hplevels11up: "+{num} / level"
hitdie: "{die} + CON Mod"
initbonus: "+{num}"
weapons: ""
armor: ""
---
> [!infobox|right ws-med]+
> ![[this.image]]
> ###### `=this.file.name`
> ```dataviewjs
> let pg = dv.current();
> let table = "###### Attributes";
> table += "\n| Attribute | Value |" +
>              "\n| --------- | ----- |";
>  div.header(3, pg.title);
>  table += "\n| **Requirements:** | " + pg.requirements + " |";
>  table += "\n| **HP at Level 1:** | " + pg.hplevel1 + " |";
>  table += "\n| **HP for Levels 2 to 10:** | " + pg.hplevels2to10 + " |";
>  table += "\n| **HP for Levels 11+:** | " + pg.hplevels11up + " |";
>  table += "\n| **Hit Die:** | " + pg.hitdie + " |";
>  table += "\n| **Initiative:** | " + pg.initbonus + " |";
>  table += "\n| **Category:** | " + pg.combat_category + " |";
>  table += "\n| **Weapons:** | " + pg.weapons + " |";
>  table += "\n| **Armor:** | " + pg.armor + " |";
> ```

# `=this.file.name`

## Starting Equipment
- an Adventurer's Pack
- a `=this.file.name`'s Pack
- {#}d6 silver

## `=this.file.name` Skills

## Combat

  They are considered a [[7. Weapon Proficiency#Martial, Semi-Martial, Non-Martial|Semi-Martial]] [[class_image.png]]
  
## Hirelings

## After Reaching 10th Level

## New Weapon Proficiencies


## Class Abilities

## Updated `=this.file.name` Table
