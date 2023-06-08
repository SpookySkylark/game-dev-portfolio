---
title: Skeleton Smashers - First Look
date: 2023/6/8
description: A first look at my new work-in-progress title.
tag: app development
author: You
---

# Skeleton Smashers!

I've been hard at work on a brand new game! It's not ready for a demo yet, but I wanted to share a few recent clips I took to demonstrate features. 

# The Basics

<video width="640" height="480" controls>
    <source src="../videos/basics.mp4" type="video/mp4"></source>
    Your browser does not support the video tag.
</video> 

This is a clip simply showing some basics of the game. The game is a mix between breakout and 'suvival' games that have become popular recently. After defeating all the skeletons and collecting enough loot, the player will have a chance to purchase various upgrades or additional abilities (shown below), increasing their damage. Enemies that have weapons are more threatening, and the ones with shields will block any attack that comes from the front, but wooden shields will break after doing so. The enemies damage the player when they reach the bottom of the screen, and are returned to the top to attempt another attack.

*UI, ball, and paddle are placeholder graphics*

# Shields

<video width="640" height="480" controls>
  <source src="../videos/shields.mp4" type="video/mp4"></source>
    Your browser does not support the video tag.
</video> 

This is a clip more closely demonstraiting shields. The enemies will be knocked back when blocking, even if they take no damage, and even if the shield is broken. Damage from the sides or above will totally ignore the shield. It's worth mentioning that this is a set up for testing, and in the final game the decrepit skeletons will not be able to appear with shields, as they are missing the arm that would hold them. 

*Background, ball, paddle, UI and boarder are placeholder graphics*

# Abilities: Chain Lightning

<video width="640" height="480" controls>
  <source src="../videos/zapzap.mp4" type="video/mp4"></source>
    Your browser does not support the video tag.
</video> 

This is a clip of my favoruite ability: Chain Lightning! I'm a big sucker for this spell in every game it's in, as it's always fun to see how it "chains" between targets. Getting this working is a major reason I'm so excited about the project! The spell will correctly find the nearest target, then the next nearest after that, and bounce to them in turn. Each chain does less damage, but the damage, number of times in chains, and amount of damage it loses with each target, can all be changed by purchasing upgrades between rounds. I even added an animated line rendered texture for extra zappiness! 

*Background, ball, paddle, UI and boarder are placeholder graphics*

# Loot Boxes and Treasure

<video width="640" height="480" controls>
  <source src="../videos/treasure.mp4" type="video/mp4"></source>
    Your browser does not support the video tag.
</video> 

This clip is showing off the "Loot Boxes" mechanic I added, which gives enemies a tiny chance to drop a box of treasures! (Chance was highly increased to take this clip). The loot boxes are very very rare but the vast hoards of enemies make them a semi-regular occourance. They drop an excessive amount of treasures (reduced from this test, but still a lot!) but must be hit with the ball itself, and will not be broken open by any abilities. There is also a treasure generating mechanic, where the game will create a series of varried loot items, each with their own value, based on the total value of loot the function is told to create. This is why the treasure chests drop a huge variety of different loot items, and although the different does not matter much to the player, the variety in loot makes getting the loot boxes very rewarding. In the future I plan to also have them drop free upgrade cards or, if I ever create a meta game, meta game unlocks.

*Background, ball, paddle, UI and boarder are placeholder graphics*