# the hitbox command
the parameters are !hitbox target {commands} excludedTarget
an example is !hitbox partname {!sit hit} me
this will make everyone *touching* the part (except for you) sit down
"hit" in the {commands} parameter is the person touching the part
the hit tag is both a player tag and a string. ||e.g. you can do !m hit, to return their display name, or !fling hit, to fling them||

# all the keywords (that i know of)
**player tags**
me - yourself
nearest - the nearest player to you
farthest - the farthest player to you
others - everybody in the server other than you
near - everyone in a range near you
far - everyone that ISNT in the range near you
random - a random player
hit - this can only be used in the hitbox command, it is the person touching the part
**the next tags arent for getting players, but return strings. they have to have a space before and after.** ||e.g. my display name is mydisplay :white_check_mark:, my display name is mydisplay! :x:||
mydisplay - your display name
myusername - your username
playercount - the amount of players in the server
myhealth - your health
RNG(1/2) - gives a random number between the two inputs, the first number must be smaller than the second number

# repeat
it is not a command, but repeats commands an amount of times
the usage is repeat n [commands] end
for example, "repeat 10 !disguise me !wait 0.1 end"
the maximum amount of repeats is 10
||repeats used to be able to be embedded in eachother, but are not anymore, e.g. repeat 10 repeat 10 !sit end !jump end - sits 100 times, and jumps 10 times||
repeats are very useful for shortening strings by a LOT, for example a string i made:
!clean repeat 10 !addpart me grey 1 0 block plastic yes no 1 1 1 0 -1.5 -10 90 0 60 aura !rotate me 0 36 end !particle parts 6900421398 50 5 5 white white 0 0 10 0 0 1000 1 yes top
instead of having to copy everything inside the repeat and pasting it 10 times, i can put it in a repeat loop and it is much easier to use
the limit of this is if you want to have something change every single time (such as transparency) in a loop you cant ||although there is a scrpt to make commands like these, [here](https://pastebin.com/726LUaVm)||

# particle
ill add this because it has an insane amount of parameters
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
direction - what direction the particles emit out of. ||e.g. top left back right front, won't matter if spread is 360||

# chat tags
usually unlockable through badges, chat tags give you a title before your name in chat.
for example "[ctao]: meow" -> "[epic glitcher][ctao]: meow"
these are all the tags currently in the game (10)
Fan - unlocked by joining blacklight's group, [here](https://www.roblox.com/communities/17044066)
Donator - unlocked by buying the donation gamepass, [here](https://www.roblox.com/game-pass/812596930)
Herobrine - unlocked by being jumpscared by herobrine ||in my experience, herobrine appears much more often in private servers||
Met The Owner - unlocked by having blacklight in your server
COLD BLOODED MURDERER - unlocked by doing the following: (preferably in a private server)
1. run "!knife" and then run "!anchor repeat 100 !dummynpc me !dummynpc me end !wait 0 !anchor npcs !bring npcs !health npcs 1 !unanchor me" then **WAIT AT LEAST 10 SECONDS** for your game to return to normal
2. equip the knife and click once to kill the npcs
The Reaper - unlocked by doing the following: (preferably in a private server)
1. run "!scythe" and then run "!anchor repeat 100 !dummynpc me !dummynpc me end !wait 0 !anchor npcs !bring npcs !health npcs 1 !unanchor me" then **WAIT AT LEAST 10 SECONDS** for your game to return to normal
2. kill the npcs by clicking/tapping once with scythe
3. run "!anchor repeat 60 !dummynpc me end !wait 0 !bring npcs !weld dummy npcs !anchor dummy !health npcs 100 !unanchor me"
4. hit the npcs twice with the scythe, and then hit them once and ~2 seconds later press harvest souls (q)
5. if you dont get max soul power right away, run the command again and use scream (z) and harvest souls (q) again once killed
misc. ||if your scythe breaks at any point, reset and do it again||
epic glitcher - unlocked by getting the wave 60 badge (instructions will be in the next section)
:speaking_head::fire:yapper:fire::speaking_head: - unlocked by being given it by an admin for any reason (e.g. winning minigames)
Administrator - unlocked by being given it by blacklight to moderate servers and reports (to nearly everyone, this will be unobtainable)
