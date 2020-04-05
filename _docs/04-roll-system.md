---
title: 4. Roll system
description: Let's talk about dice. When and how to use them?
---

# 4. Roll system

Every player roll in Open Tale is based on an attribute. But before rolling dice
for an attribute, it's necessary to know its respective *power*:

**Attribute Power** = 6 + 2 * **Attribute Level**

After calculating the attribute power, we choose two dice (not necessarily of
different types) that sum up to to that quantity and roll them. The available
dice to choose are:

* d4
* d6
* d8
* d10
* d12

For example: A character is going perform an attack with a long sword and his
strength is at level 5. His strength power is 6 + 2 * 5 = 16. Thus, the player
has three options to roll: 1d12+1d4, 1d10+1d6 or 2d8.

## 3.1. Heroism

The GM can reward characters with *Heroic Badges*, which can be spent in the
beginning of the player's turns. If the player chooses so, every roll on that
turn happens with an extra d4.

Characters cannot carry more than one Heroic Badge at a time.

## 3.2. Roll modifiers

Roll modifiers are ingredients that can be used to spice up the story in certain
moments. There are four mutually exclusive roll modifiers in Open Tale:
*Inferiority*, *Disadvantage*, *Advantage* and *Superiority*.

Inferiority and Disadvantage are nerfs applied on the die with the highest
value. Advantage and superiority are buffs applied on the die with the smallest
value. Their mechanics are as follows:

* Inferiority: pick the die with the highest value and roll it again, keeping
the smallest value

* Disadvantage: pick the die with the highest value and roll it again, keeping
the second value and ignoring the first one

* Advantage: pick the die with the smallest value and roll it again, keeping
the second value and ignoring the first one

* Superiority: pick the die with the smallest value and roll it again, keeping
the highest value

Notice that Disadvantage and Advantage are not absolute modifiers, in the sense
that it's still possible to worsen the score in case of Advantage or improve
the score in case of Disadvantage. These results can be interpreted as if the
character got overconfident when on Advantage... or was able to focus and
overcome a situation of Disadvantage.

## 3.3. Explosions

After applying the roll modifier, if any, the player can gain extra scores from
dice explosions.

An explosion happen when a die hits its highest value. The player can roll it
again and add the next value to the final score. **Dice may explode
indefinitely**, so players can have the chance to achieve surprisingly high
scores.

## 3.4. Expected scores

Let's define the *expected score* of an attribute level as the integer
approximation of the average score if we roll dice many many times.

The table below shows the expected scores (*without* ⇒ *with* Heroism) for each
attribute level and roll modifier.

| Level | Inferiority | Disadvantage | Neural | Advantage | Superiority
|:-:|:-:|:-:|:-:|:-:|:-:
| **1** | 4 ⇒ 7 | 5 ⇒ 7 | **6 ⇒ 9** | 8 ⇒ 11 | 8 ⇒ 11 |
| **2** | 5 ⇒ 8 | 6 ⇒ 8 | **7 ⇒ 10** | 8 ⇒ 12 | 9 ⇒ 12 |
| **3** | 6 ⇒ 9 | 7 ⇒ 9 | **8 ⇒ 11** | 9 ⇒ 13 | 10 ⇒ 13 |
| **4** | 6 ⇒ 9 | 7 ⇒ 10 | **9 ⇒ 12** | 10 ⇒ 14 | 11 ⇒ 14 |
| **5** | 7 ⇒ 10 | 8 ⇒ 11 | **10 ⇒ 13** | 11 ⇒ 15 | 12 ⇒ 15 |
| **6** | 8 ⇒ 11 | 9 ⇒ 12 | **11 ⇒ 14** | 12 ⇒ 16 | 13 ⇒ 17 |
| **7** | 9 ⇒ 12 | 10 ⇒ 13 | **12 ⇒ 15** | 14 ⇒ 17 | 15 ⇒ 18 |
| **8** | 9 ⇒ 13 | 11 ⇒ 14 | **13 ⇒ 16** | 15 ⇒ 18 | 16 ⇒ 19 |
| **9** | 10 ⇒ 13 | 11 ⇒ 14 | **14 ⇒ 17** | 16 ⇒ 19 | 17 ⇒ 20 |

These numbers are useful to design appropriate challenges as a GM and also for
the players to understand their own limitations and capabilities.
