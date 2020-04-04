---
title: 3. Roll system
description: Let's talk about dice. When and how to use them?
---

# 3. Roll system

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

## 3.1. Roll modifiers

Roll modifiers are ingredients that can be used to spice up the story in certain
moments. There are four mutually exclusive roll modifiers in Open Tale:
*Inferiority*, *Disadvantage*, *Advantage* and *Superiority*.

Inferiority and disadvantage are nerfs applied on the die with the highest
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

Notice that disadvantage and advantage are not absolute modifiers, in the sense
that it's still possible to worsen the score in case of advantage or improve
the score in case of disadvantage. These results can be interpreted as if the
character got overconfident when on advantage... or was able to focus and
overcome a situation of disadvantage.

## 3.2. Explosions

After applying the roll modifier, if any, the player can gain extra scores from
dice explosions.

An explosion happen when a die hits its highest value. The player can roll it
again and add the next value to the final score. **Dice may explode
indefinitely**, so players can have the chance to achieve surprisingly high
scores.

## 3.3. Expected scores

Let's define the *expected score* of an attribute level as the integer
approximation of the average score if we roll dice many many times. These are
the expected scores for each attribute level:

| Level | Inferiority | Disadvantage | Neural | Advantage | Superiority
|:-:|:-:|:-:|:-:|:-:|:-:
| 1 | 4 | 5 | **6** | 8 | 8 |
| 2 | 5 | 6 | **7** | 8 | 9 |
| 3 | 6 | 7 | **8** | 9 | 10 |
| 4 | 6 | 7 | **9** | 10 | 11 |
| 5 | 7 | 8 | **10** | 11 | 12 |
| 6 | 8 | 9 | **11** | 12 | 13 |
| 7 | 9 | 10 | **12** | 14 | 15 |
| 8 | 9 | 11 | **13** | 15 | 16 |
| 9 | 10 | 11 | **14** | 16 | 17 |

These numbers are useful to design appropriate challenges as a GM and also for
the players to understand their own powers.
