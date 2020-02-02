---
title: "My old games"
date: 2020-02-02
categories:
  - blog
  - gaming
tags:
  - blog
  - 3D
  - games
  - old
published: false
---

When I was in school, about 6-7 years ago, I had found a new hobby and passion - making games.
I'm not sure how but I found a free 3D game maker named [3D RAD](http://web.archive.org/web/20150514120532/http://www.3drad.com/).
I played around a lot with it on my ancient PC, which had a Pentium 4 and 1 Gigabyte of RAM. 3D RAD is no longer being developed,
the latest version you can find is the same one I used at that time. Moreover, the [website](http://www.3drad.com/) only shows a
black window. It is pretty much dead now, though [unofficial forums](http://3drad.org/) exist, 3D RAD is too outdated - there are
better alternatives like Unity and Unreal engine.

## The engine

3D RAD had many features, especially considering that it was developed by an independent developer. It had quite a few examples
included with the engine for a range of games - third person, car racing, airplane simulator, boat simulator, underwater physics
and many others.

<figure>
  <img src="/assets/images/3D-Rad-UI.jpg" />
  <figcaption>The 3D Rad UI</figcaption>
</figure>

The game engine has a simple UI with two panes: objects and 3D viewer. Everything is an object in 3D Rad - rigidbodies, skins, forces,
skyboxes, sprites, scripts (!) - you get a selection of in-built objects that you can use and modify. This has a disadvantage, everything
is cluttered in the object panel. On the 3D viewer, there are helper buttons to move and rotate objects. You can make simple games
without having to write any code, though 3D Rad has scripting support for more advanced mechanisms. The documentation is quite
extensive but simple and understandable (even for a 13 year old like I was).

The scripting engine used was [AngelScript](https://www.angelcode.com/angelscript/) which has a C-like syntax. There was a scripting
[object reference](http://web.archive.org/web/20150508094348/http://3drad.com/Script_reference.htm) which I used when writing scripts.
My programming knowledge was very limited at the time, so [my brother](https://github.com/shreyash14s/) helped me in this.

For being a 3D game engine with so many features, it was very well optimized - it ran well enough (other than the detailed terrain
model not working) on a Pentium 4 2.0Ghz with no GPU. I played around with this a lot, started projects that were left incomplete
as soon as I had an idea for another project. There's probably only one game that I actually completed.

## Some of the games

Following are demos of some games that I made in 3D Rad, they are mostly incomplete with some debug information (a.k.a. random numbers)
right in the middle of the screen.

### Car Fight

<!-- cSpell:disable -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MK5KUZ73Xok" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!-- cSpell:enable -->

A car "fighting" game that has mini Suns for projectiles and a random rigidbody for powerups. In this game, you fight with an enemy
car by shooting balls at each other. The player car is Porsche 911 model that I found on the store in [SketchUp](https://www.sketchup.com/).
The enemy car is a generic inbuilt model in 3D Rad. The blue bar represents your boost fuel which you can use to get a boost for a
while, the fuel fills up slowly but can be filled up quickly by picking up the powerups. On the HUD, there is a speedometer, a
tachometer and a minimap. Although by default, the camera is in a third person view, you can switch to a first person view (which
has floating hands).

### Slingshot

<!-- cSpell:disable -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iueriTNdTMk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!-- cSpell:enable -->

A game where you slingshot a shiny ball onto a generic cuboid. That's it, that's the game. The game enters slow-mo as the ball nears
the target and there is sound effect when it hits. I suspect this game was inspired by some game I played at that time.
(I initially called this game "Catapult", I have no idea why).

### Car Parking

<!-- cSpell:disable -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtm5Dy9rJYo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!-- cSpell:enable -->

Probably the only complete game I ever made. This game was probably inspired from Dr. Driving. The objective is to park your "car"
in the spot shown by the floating fish. There are two camera views - top down and behind.

### Space Shooter

<!-- cSpell:disable -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_6UCF294Hw8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!-- cSpell:enable -->

This game was definitely inspired from Galaxy on Fire 2, which I played a lot for many years. Here, you control a spaceship that can
shoot bullets. There are a few planets and a Sun, with distances shown on each of them and gravity simulated on them. You have two
enemy spaceships that shoot missiles at you and your objective is to shoot them down (which is probably impossible, they are too OP).
You also get a crazy boost feature, that throws your spaceship far forward.

### Circuit Racing

<!-- cSpell:disable -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7IJX1IW6-kA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<!-- cSpell:enable -->

A simple racing game with support for laps around a circuit track, which was built from the inbuilt highway pieces. Your player car
is the same as in [Car Fight](#car-fight) and with a similar HUD (except there is no background for the minimap).