---
title: 3. Roll system
description: Let's talk about dice. How to use them?
---

# 3. Roll system

Every player roll in Open Tale is based on an attribute. These are the dice that
are used for each attribute level:

| Attribute level | Dice | Average score
|:-:|:-:|:-:
| 1 | 2d4 | 5
| 2 | d4+d6 | 6
| 3 | 2d6 | 7
| 4 | d6+d8 | 8
| 5 | 2d8 | 9
| 6 | d8+d10 | 10
| 7 | 2d10 | 11
| 8 | d10+d12 | 12
| 9 | 2d12 | 13

## 3.1. Heroism

The GM can reward characters with *Heroic Badges*, which can be spent in the
beginning of the player's turns. If the player chooses so, every roll on that
turn happens with an extra d4.

Characters cannot carry more than one Heroic Badge at a time.

## 3.2. Roll modifiers

Roll modifiers are ingredients that can be used to spice up the story in certain
moments. There are four **mutually exclusive** roll modifiers in Open Tale:
*Inferiority*, *Disadvantage*, *Advantage* and *Superiority*.

Inferiority and Disadvantage are nerfs applied on the die with the highest
value. Advantage and Superiority are buffs applied on the die with the smallest
value. Their mechanics are as follows:

* Inferiority: pick the die with the highest value and roll it again, keeping
the smallest value

* Disadvantage: pick the die with the highest value and roll it again, keeping
the second value and ignoring the first one

* Advantage: pick the die with the smallest value and roll it again, keeping
the second value and ignoring the first one

* Superiority: pick the die with the smallest value and roll it again, keeping
the highest value

If there is a tie between dice scores, re-roll the biggest die (d4 < d6 < d8 <
d10 < d12).

Notice that Disadvantage and Advantage are not absolute modifiers, in the sense
that it's still possible to worsen the score in case of Advantage or improve
the score in case of Disadvantage. These results can be interpreted as if the
character got overconfident when on Advantage... or was able to focus and
overcome a situation of Disadvantage.

Some circumstances tell you exactly which modifier to apply, but the GM is free
to say which modifier can be used throughout the game.

#### Compensating modifiers

It's possible that characters become subject to opposing modifiers, such as
Advantage and Disadvantage at the same time. When this happens, we can think of
modifiers as integer numbers:

| Inferiority | Disadvantage | Advantage | Superiority
|:-:|:-:|:-:|:-:
| -2 | -1 | 1 | 2

So, continuing on the given example, if the character is on Advantage **and**
Disadvantage, they nullify each other, resulting in no modifier at all (1 - 1 =
0).

Another example: suppose that a character is on Superiority **and**
Disadvantage. The resulting modifier is Advantage because 2 - 1 = 1.

This is just a general guideline. Ultimately, the GM has the final word
regarding which modifier should be applied (or no modifier at all).

## 3.3. Critical rolls

A critical roll happens when two (or more) dice score higher than their
individual average scores. So for instance, when rolling a d4+d6, a critical
roll would require the d4 to score at least 3 **and** the d6 to score at least
4. The table below shows more examples:

| Roll | Respective dice results | Critical?
|:-:|:-:|:-:
| d4+d6 | 2 and **4** | No
| d4+d6 | **4** and **5** | Yes
| d4+d6+d8 | 2, 2 and **8** | No
| d4+d8+d10 | **4**, **7** and **9** | Yes
| d4+2d12 | **3**, **9** and 2 | Yes

Critical rolls are an important aspect of the system because they may trigger
certain skill conditions.
