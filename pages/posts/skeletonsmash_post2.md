---
title: Skeleton Smashers - Second Look
date: 2023/6/20
description: A second look at my new work-in-progress title.
tag: app development
author: You
---

# Skeleton Smashers

While I've been very busy with applications and cover letters, I've found some time to do updates to Skeleton Smashers. I have more features that I am excited to talk about, so read on to see what I have been up to!

# New Enemy Types

<video width="640" height="480" controls>
    <source src="../videos/NewEnemyTypes.mp4" type="video/mp4"></source>
    Your browser does not support the video tag.
</video> 

I've added a slew of new enemy types! So far these are not overly advanced characters, but more some staples which do a good job at rounding out the game and enemy variety. The current new enemies are the Chainmail Skeleton, who has extra health from their armour and is more likely to carry higher-end equipment and shields, the Giant Skeleton, who is very "big boned" and has a tremendous amount of health but is very large and slow, and finally the "Skull Skeleton", which is simply a skull riding on it's own skeletal hand, and is very fragile and never uses equipment (of course) but is very quick.

# New Abilities!

<video width="640" height="480" controls>
  <source src="../videos/bombardment.mp4" type="video/mp4"></source>
    Your browser does not support the video tag.
</video> 

I've added two new abilities, for a total of 5. I plan to have 6 on release, so I'm almost there! The new abilities are the Bombardment ability and the Hoarfrost ability. The Bombardment ability is shown in the video, and will fire exploding cannonballs randomly onto the field. Upgrades can increase the number of canons fired and reduce the delay between rounds. The explosions will respect Line of Sight mechanics, and skeletons can block each other from damage as a result. However, if the cannonball lands directly on the skeleton they take a large amount of damage, and the explosion occurs after the damage, allowing the cannonballs to clear the area they land if the player is lucky. The second new ability, Hoarfrost, uses a similar explosion effect, but in this case it is a cloud, and so ignores line of sight mechanics.

# Status Effects

<video width="640" height="480" controls>
  <source src="../videos/StatusEffect.mp4" type="video/mp4"></source>
    Your browser does not support the video tag.
</video> 

Along with the Hoarfrost ability I have added mechanics for status effects! Currently the only effect is "Chilled" which turns the skeletons blue and causes them to move much much slower for an amount of time. The status effect system can be expanded with more effects, and uses a custom class in order to control each status effect. I have already experimented with adding a "Burning" status effect, which does damage over time, but have yet to add an appropriate vector to apply the effect.

# UI and Reroll

<img src="../images/UIupdate.png" width="640" height="480"></img>

I've also added a number of new UI elements and features to support basic gameplay. There is now a display under the health bar showing the currently owned abilities. Also, an indicator for the players current ball damage, as well as a special Damage Per Second counter, which will indicate the average damage done by the player with all abilities (displayed number is a result of using debug commands to instantly end the previous level). In addition to new UI elements I've also added a reroll button! Currently the player has three rerolls to use as they please in each game. Rerolling will reshuffle the upgrades and weapons, and allow you to pick up upgrades for a newly acquired ability instantly, but should be used carefully. The reroll count is something I hope to tie to a form of meta progression.

