---
title: 3. Roll system
description: Let's talk about dice. When and how to use them?
---

# 3. Roll system

Every player roll in Open Tale is based on an attribute. But before rolling dice
for an attribute, it's necessary to know its respective *power*:

**Attribute Power** = 6 + 2 * **Attribute Level**

After calculating the attribute power, we choose **two** dice (not necessarily
of different types) that sum up to to that quantity and roll them. The available
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
moments. There are four **mutually exclusive** roll modifiers in Open Tale:
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

If there is a tie between dice scores, the player is free to choose any of them
to roll again.

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

## 3.3. Explosions

After applying the roll modifier, if any, the player can gain extra scores from
dice explosions.

An explosion happen when a die hits its highest value. The player can roll it
again and add the next value to the final score. **Dice may explode
indefinitely**, so players can have the chance to achieve surprisingly high
scores.

Explosion rolls do not count as new rolls for the attributes.

## 3.4. Expected scores

Let's define the *expected minimum score* of an attribute level as the integer
approximation of minimum score that we should expect 50% of the times we roll
for that attribute. For instance, if the expected minimum score of an attribute
at a certain level is 7, then for 50% of the rolls we will get at least a 7.

The table below shows the expected scores (*without* ⇒ *with* Heroism) for each
attribute level and roll modifier.

| Level | Inferiority | Disadvantage | Neural | Advantage | Superiority
|:-:|:-:|:-:|:-:|:-:|:-:
| **1** | 4 ⇒ 7 | 5 ⇒ 7 | **6 ⇒ 9** | 8 ⇒ 11 | 8 ⇒ 11 |
| **2** | 5 ⇒ 8 | 6 ⇒ 8 | **7 ⇒ 10** | 8 ⇒ 12 | 9 ⇒ 12 |
| **3** | 6 ⇒ 9 | 7 ⇒ 9 | **8 ⇒ 11** | 9 ⇒ 13 | 10 ⇒ 13 |
| **4** | 7 ⇒ 10 | 8 ⇒ 10 | **9 ⇒ 12** | 10 ⇒ 14 | 11 ⇒ 14 |
| **5** | 7 ⇒ 10 | 9 ⇒ 11 | **10 ⇒ 13** | 11 ⇒ 15 | 12 ⇒ 16 |
| **6** | 8 ⇒ 11 | 9 ⇒ 12 | **11 ⇒ 14** | 12 ⇒ 16 | 13 ⇒ 17 |
| **7** | 9 ⇒ 12 | 10 ⇒ 13 | **12 ⇒ 15** | 14 ⇒ 17 | 15 ⇒ 18 |
| **8** | 9 ⇒ 13 | 11 ⇒ 14 | **13 ⇒ 16** | 15 ⇒ 18 | 16 ⇒ 19 |
| **9** | 10 ⇒ 13 | 12 ⇒ 14 | **14 ⇒ 17** | 16 ⇒ 19 | 17 ⇒ 20 |

These numbers are useful to design appropriate challenges as a GM and also for
the players to understand their own limitations and capabilities.

As a rule of thumb, for an attribute level *X*, the expected minimum score is
*X* + 5.
