# Commands
## Hitbox
The parameters are `!hitbox target {commands} excludedTarget`.
An example is `!hitbox partname {!sit hit} me`.
- This will make everyone touching the part <small>except for you</small> sit down.
The "hit" tag in the {commands} parameter is the person touching the part.
The hit tag is both a player tag and a string. <small>e.g. you can do !m hit, to return their display name, or !fling hit, to fling them</small>.

## Repeat
it is not a command, but repeats commands an amount of times
the usage is `repeat n [commands] end`
for example, "repeat 10 !disguise me !wait 0.1 end"
the maximum amount of repeats is 10
repeats are very useful for shortening strings by a LOT, for example a string i made:
`!clean repeat 10 !addpart me grey 1 0 block plastic yes no 1 1 1 0 -1.5 -10 90 0 60 aura !rotate me 0 36 end !particle parts 6900421398 50 5 5 white white 0 0 10 0 0 1000 1 yes top`
instead of having to copy everything inside the repeat and pasting it 10 times, i can put it in a repeat loop and it is much easier to use.

## Particle <small>ill add this because it has an insane amount of parameters</small>
target - person (or part) you run it on
id - the image id of the particle
rate - how fast particles are emitted
size - the beginning size of the particle
size2 - the size the particle changes to during its lifetime
color - the beginning color of the particle
color2 - the color the particle changes to during its lifetime
transparency - the beginning transparency of the particle, a number between 0 and 1, 0 being fully visible and 1 being invisible
transparency2 - the transparency the particle changes to during its lifetime
speed - how fast the particle moves
spread - the range of directions the particle can move out from, from 0 to 360
rotation - what rotation the particles have, does not affect direction spread etc
rotspeed - similar to rotation, but how fast the particles rotate
lifetime - how long each particle lasts
locked - whether particles emit from one spot, or a random position in your torso, yes/no
direction - what direction the particles emit out of. <small>e.g. top left back right front, won't matter if spread is 360</small>

# Keywords <small>that i know of</small>
## Player keywords
me - yourself
nearest - the nearest player to you
farthest - the farthest player to you
others - everybody in the server other than you
near - everyone in a range near you
far - everyone that ISNT in the range near you
random - a random player
hit - this can only be used in the hitbox command, it is the person touching the part
## String keywords <small>they return strings, not players</small>
mydisplay - your display name
myusername - your username
playercount - the amount of players in the server
myhealth - your health
RNG(1/2) - gives a random number between the two inputs, the first number must be smaller than the second number

# Chat tags
usually unlockable through badges, chat tags give you a title before your name in chat.
for example "[ctao]: meow" -> "[epic glitcher][ctao]: meow"
these are all the tags currently in the game (10)
Fan - unlocked by joining blacklight's group, [here](https://www.roblox.com/communities/17044066)
Donator - unlocked by buying the donation gamepass, [here](https://www.roblox.com/game-pass/812596930)
Herobrine - unlocked by being jumpscared by herobrine. <small>in my experience, herobrine appears much more often in private servers</small>
Met The Owner - unlocked by having blacklight in your server
COLD BLOODED MURDERER - unlocked by doing the following: (preferably in a private server)
1. run `!knife` and then run `!anchor repeat 100 !dummynpc me !dummynpc me end !wait 0 !anchor npcs !bring npcs !health npcs 1 !unanchor me` then **WAIT AT LEAST 10 SECONDS** for your game to return to normal
2. equip the knife and click once to kill the npcs
The Reaper - unlocked by doing the following: (preferably in a private server)
1. run `!scythe` and then run `!anchor repeat 100 !dummynpc me !dummynpc me end !wait 0 !anchor npcs !bring npcs !health npcs 1 !unanchor me` then **WAIT AT LEAST 10 SECONDS** for your ping to return to normal
2. kill the npcs by clicking/tapping once with scythe
3. run `!anchor repeat 60 !dummynpc me end !wait 0 !bring npcs !weld dummy npcs !anchor dummy !health npcs 100 !unanchor me`
4. hit the npcs twice with the scythe, and then hit them once and ~2 seconds later press harvest souls (q)
5. if you dont get max soul power right away, run the command again and use scream (z) and harvest souls (q) again once killed
misc. <small>if your scythe breaks at any point, reset and do it again</small>
epic glitcher - unlocked by getting the wave 60 badge (instructions will be in the next section)
🗣🔥yapper🔥🗣 - unlocked by being given it by an admin for any reason (e.g. winning minigames)
Administrator - unlocked by being given it by blacklight to moderate servers and reports (to nearly everyone, this will be unobtainable)
furry - unobtainable, this tag is for blacklight
||some tags used to have animations prior to the textchatservice update, but dont anymore||

# wave badges
now in a diffrent game, <small>by using `!servers` and pressing [Star Glitcher](https://example.com),</small> wave badges give you four rewards when unlocked
**wave 30**
requires being in the game since wave 11, and beating wave 30 with a minimum of 100k total damage
gives you starglitcher's vindictive mode (mayhem>death>vindictive) and sgev
**wave 60**
requires being in the game since wave 16, and beating wave 60 with a minimum of 1 million total damage
gives you permenant use of `!memer` and the epic glitcher tag
