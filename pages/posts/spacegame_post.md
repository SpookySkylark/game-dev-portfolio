---
title: Space Trading Game
date: 2023/4/26
description: Exploring my space trading game.
tag: app development
author: You
---

# Space Trading Game


# Web Demo

<div style={{align: "center"}}>
<iframe src="https://game-dev-portfolio-pi.vercel.app/apps/space/index.html" style={{align: "center"}} name="Space Trading Game" scrolling="no" frameborder="1" marginheight="px" marginwidth="0px" height="680px" width="1020px"></iframe>
</div>

#
# About

## Intro
The "Space Trading Game" is a small prototype of a game I made to serve as the basis for future projects and to practice creating games with Unity. I've always been very interested in games about space travel and progression systems, so I was excited to have the chance to make a game which utilizes both. The project uses a realistic style of space flight with constant acceleration and deceleration and rotating part way through. The idea was to create a low-sci-fi trading game where lacking more advanced technology like a FTL drive or shields or lasers would present more of a challenge and certain obstacles to overcome. While the prototype isn't rife with the dangers I had in mind, it still demonstrates the "realistic" movement of the vessels between planets.

## Controls
The game is designed with simple mouse controls in mind. Left click selects, right click cancels. Buying and selling items is as simple as clicking the item in the appropriate inventory, but requires a fleet docked at the selected planet. To command fleets to move, simply select a planet with a docked fleet, click 'Launch' and then click the destination. Further work was being done on indicating the game is in a "launch" state and more clarity with purchased items were both planned and partially implemented, but could not be completed due to time constraints. The games controls could easily be adapted for a touch screen given time.

## The Economy
One feature I am particularly proud of is the games simulated economy. The game will adjust the buy and sell prices of goods automatically, based on a number of factors. Planets will consider current stock and reduce the price to match, but also pay much more for resources they are unable to produce themselves. As is the case with many games, items sell for less than they are bought for, making it important for the player to find the right market for the products. A feature to have planets consume goods was in progress but was dropped due to time constraints.

## Production Progression
Another feature that was to play a major role in the final game, is the idea of tiered goods, and planetary production. This is a system where a planet will produce certain goods if supplied with certain other goods. The main example of this is the planet Titan, which has a refinery, and will turn and Iron Ore in the inventory into Metal Plates over time. These plates have more value that the ore, but also have a further use. If brought to a planet with a space station or shipyard, such as Neuvo Domum, the shipyard will make use of the planets to create expensive consume ships, which have a very high trading margin. In a full and complete game this would be massively expanded, and planets would gain new productions and consumption as they grow from successful trade.

## Graphics
While the priority was always being readable, the lighting effects available in Unity worked very well in this setup, and I'm very happy with how the lighting and shading came out in regards to the planets. The ships travel path is another element I would call successful. I was targeting a more realistic sort of space flight, where the ships accelerate for half a journey, and then flip and decelerate the rest of the way. Heavily inspired by The Expanse. The effect came out well, though it was quite a bit of development time. The slower methodical nature of the ships gives the game a more relaxed feeling, but I built the system in such a way that it would allow for easy adjustments to acceleration and deceleration speed.

## Future Plans
I don't plan to continue this project, but it will be the basis for other project. A large number of features were being worked on and were even partially implemented, but I ran out of time and had to scale back to a more manageable level for a game made in about 9 hours (A lot of which went into drawing the ships and icons, I'm not proud to say). The tooltip system to explain what each icon means was the biggest feature that I had to cut, and it was very close to working. A few more hours would easily be enough to add such a feature. Another major feature was to be being able to buy new ships and replace specific ships in a fleet, but the scope of that was likewise unreasonable. I made a special effort to future proof the game design, and all items and production facilities are neatly classed in such a way that it would be simple to add new items and production facilities that intake those items. 