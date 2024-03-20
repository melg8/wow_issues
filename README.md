# Wow issues reported by me

## Wsg doesnt register flag carry
   - Original issue number: 1591
   - Opened: 00:28 18/07/2022
   - Status: Closed

### Please, provide a clear description what the bug is: 
On my horde rogue character Melgo (not hardcore mode character, but with War Mode challenge enabled) - playing in bracket 40-49 on wsg - take alliance flag and take it to our base i can't place it and get +1 to our team. Our flag is on base and not captured by enemy team. If i drop my flag with right click on buf, and other horde player pick it up - he can score flag by simply entering ring around our flag. I myself cant score flag by entering red zone around our flag, by entering and going out from it, jumping, dropping and picking it up again. So i bassically can't score as flag capture.

### Steps to reproduce the behavior with as much detail as possible:
- Go to wsg as Melgo in 40-49 bracket (maybe that behaviour same on other brackets)
- capture ally flag
- bring it to horde base
- Enter room with horde flag
- Enter circle around horde flag
- Nothing happens.

### Expected behavior. Describe how it should work: 
Should score as flag capture and get additional honor.

## Flare doesnt work on Jaguero Stalker
   - Original issue number: 4035
   - Opened: 04:27 27/07/2023
   - Status: Open
   - Tags:
      - Hunter
      - NPC
      - Spell
    
### Please, provide a clear description what the bug is:
Jaguero Stalker ignores Flare spell. Probably there are other npcs which have same behaviour.

### Steps to reproduce the behavior with as much detail as possible:
- Go near Jaguero Stalker
- Put Flare on top of it.
- Observe both "Faded" and "Flare" debuff on it. at same time.

### IDs of affected creatures, items, quests or spells with a link to the relevant page:

- NPC: https://database.turtle-wow.org/?npc=2522
- Flare: https://database.turtle-wow.org/?spell=1543
- Faded: https://database.turtle-wow.org/?spell=6408

### Expected behavior. Describe how it should work:
Npc should drop "faded" and become visible while affected by Flare.

## Pets prowl ignores Faerie Fire from mobs
   - Original issue number: 4089
   - Opened: 10:04 05/08/2023
   - Status: Closed
   - Tags:
      - Couldn't reproduce

### Please, provide a clear description what the bug is:
When Winterfall Pathfinder applies Faerie Fire spell to hunter's pet, hunter still can use prowl and pet will be in stealth while under debuf.

# Steps to reproduce the behavior with as much detail as possible:
- Attack Winterfall Pathfinder with hunter's pet which know prowl
- Wait for Winterfall Pathfinder to apply Faerie Fire to pet.
- Kill Winterfall Pathfinder, wait for pet to get out of combat.
- Use prowl skill
- Observe pet in prowl state while with Faerie Fire debuf is still on it.

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
   - NPC: Winterfall Pathfinder
   - Skill: Prowl

## Winterfall runners stack up in sneaky way as single mob
   - Original issue number: 4126
   - Opened: 08:11 11/08/2023
   - Status: Closed

### Please, provide a clear description what the bug is:
Winterfall runners that roam across winterspring can stack up in the way, that player see them as single mob, while in reality there is three of them roaming in sync. This can be problematic for hardcore character, that will try to aggro single mob, and get 2 as gift.

### Steps to reproduce the behavior with as much detail as possible:
- Go to 63.4, 26.5 in winterspring
- Wait for roamers
- Observe something like this:

Their models and animations sync up, so only way to saw 3 of them is by using nameplates.

## Av still has backdoor jump on alliance base
   - Original issue number: 4114
   - Opened: 14:12 08/08/2023
   - Status: Closed

### Please, provide a clear description what the bug is:
Today were introduced fix for av backdoor jumping to make game fair. Main issue on topic was closed: #4082.
On horde side now backdoor jump is not accesible. But on alliance side there is still way to work around invisible wall that were introduced. Please fix it to make map more balanced.
Steps to reproduce the behavior with as much detail as possible: Here is example of druid using backdoor jump on new version of map today.
After that he was trying to cap gy, so he didnt encounter any problems from last screen till gy. I observed druid

## "No pockets to pick" on mob with pickpocket table with quest item.
   - Original issue number: 6277
   - Opened: 11:42 15/02/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
In database on site there is pickpockeiting table for mob: Forest Ooze Even containing quest item: Encoded Fragment But when you try to pickpocket that creature you get error: "No pockets to pick".

### Steps to reproduce the behavior with as much detail as possible:
- Get in stealth as a rogue to Forest Ooze
- Try pickpocket on it.
- Observe error message: "No pockets to pick".

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
NPC: Forest Ooze
Item: Encoded Fragment
Quest: Encoded Fragments
Spell: Pickpocket

### Expected behavior. Describe how it should work:
I would suggest one of two options:
1. change mob to be pickpocketable
2. change pickpocket table to be empty

## Missing item bonus on site database 
   - Original issue number: 6298
   - Opened: 09:49 18/02/2024
   - Status: Open
   - Tags:
      - Website

### Please, provide a clear description what the bug is:
For item Lynxstep Boots on site there is no additional stats bonuses displayed. But ingame it shows: "Equip: increases run speed by 3%" And it really is increasing running speed when you wear this boots.

### Steps to reproduce the behavior with as much detail as possible:
- Look at Lynxstep Boots tooltip ingame:
- Compare it with Lynxstep Boots description on site:
- Observe site version is missing part "Equip: increases run speed by 3%" and probably dont showup on page of all items providing +3 run speed increase.

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
Item: Lynxstep Boots


## Warsong horde ramp charge bug
   - Original issue number: 6324
   - Opened: 21:27 21/02/2024
   - Status: Open
   - Tags:
      - Battlegrounds
      - MMAP

### Please, provide a clear description what the bug is:
When player with charge ability tries to charge someone while being present on exit from room into ramp. And his target is above Z axis on top of tunnel he charges into tunnel instead (with great speed). This was noticed on horde base, but probably may occure on alliance side as well. Wery nasty bug for pvp situations, also may be abusable.

### Steps to reproduce the behavior with as much detail as possible:
- Go outisde of top entrance of horde base into ramp part as horde druid in bear form.
- Charge alliance target approaching from alliance side (so outside into horde base).
- Observe you get charged into tunnel ( first into lower entrance to base, then to flag room, than to tunnel).

### Expected behavior. Describe how it should work:
You should charge players on top of tunnel - so if player is outside - he gets charged outside, and not placed inside of tunnel.



## Alterac Valley hut backdoor jumping course
   - Original issue number: 6356
   - Opened: 12:59 25/02/2024
   - Status: Closed

### Learn your craft!

I would like to address terrible state of alliance on AV. Only 4 of 10 paladins and 2 of 5 mages use this backdoor jump! We need to educate people on how to do better!
The issue

for quite some time ago but didnt have any outcome. Latest AV backdoor that needs fixing *missing screenshot*

- This issue were brought up recently also in twow discord.

- This issue were brought up multiple times in ingame bg chat while experiencing this unfair hut ambush.

*missing screenshot*

So this issue were noticed by players on forums, discord, ingame chats and now here on github. I'm suggesting dev team finally look into this matter.

I want to notice that this fixes arent something terribly new to begin with. First of all suggested fixes were implemented in older av map before av rework although this map had other backdoor jumps issues. So rework fixed old backdoor jumps but introduced new one for horde side only.

for alliance side. Now its time for horde side!

### So how palas should do it tho?

Here you go, full sequence, as I have promised! (Credit for video goes to Tendies)

*missing link*
https://github.com/slowtorta/turtlewow-bug-tracker/assets/16599015/8920bb05-8c86-457a-8cee-734fe66f8f5d

### Whats wrong with it?

when recalling will be not effective after they get hut flag.

Also it opens drednaught tank classes ways to solo cap hut. They just run mounted whole route, and after that kill everything on flag - kiting elite and capping flag in the end.

Because of this exploit on map 8 of 10 games finish into alliance winning just because horde base is open to be ambushed by any amount of alliance players without any slowing down factos. While horde will struggle to cross over bridge getting spammed by archers and other npcs.

Because of this exploit alot of good pvp players just refuse to recall and defend base, cause they see how outnumbered they are each time.

### Suggestions

This would be main fix for issue, even if others not implemented, this would resolve part of problem.

Increase height of collision box for fence *missing screenshot*

### Hows hut doing?

Mages go brrrrr backdoor *missing screenshot*

Keep up! *missing screenshot*

All of this screenshots were gathered in 20 minutes of single av. It repeats every game.


## Alterac Valley hut advanced jumping course 
   - Original issue number: 6362
   - Opened: 22:58 25/02/2024
   - Status: Open

### More jumps to the god of jumps!

Because #6356 issue were approved and i got alot of messages in discord and on github about other routes/jumps that were not included in previous issue i decieded to invest a little more time and capture all "issues" with current hut geodata and uploaded videos showing how this abuses can be implemented. They range from easy to abuse easy to fix, to more advanced jumps involving usage of potions.

I don't want to overwork our great developers but it would really cool if this issues can be fixed as well. @ratkosrb hopes on you!

First ill list them all as links with codenames for overview. Next ill link them with previews for more visual representation.

### Fence jumps
    Fence jump 1
    Fence jump 2
    Fence jump 3

### Hut backdoor pull
    Hut backdoor pull - ranges can pull elites through wall, and kite them away, also can hit players spawning on this gy.

### Hole in a wall
    Hole in a wall 1
    Hole in a wall 2

### Wall jumps
    Wall jump 1
    Wall jump 2

### Safe falls
    Safe fall to hut 1 - needs only safe fall buff of any kind to implement, fast route
    need only safe fall buff of any kind to implement, long route

Fence jump 1
Fence jump 2
Fence jump 3

Hole in a wall 1
Wall jump 1

Safe fall to hut 1
Safe fall to hut 2

## Alterac Valley afk abuse
   - Original issue number: 6363
   - Opened: 23:44 25/02/2024
   - Status: Open
   - Tags:
      - Battlegrounds
    
### Please, provide a clear description what the bug is:
- Inactive debuf dissapears when player dies
- Inactive debuf don't get applied to players in ghost form (dead).

### Steps to reproduce the behavior with as much detail as possible:
- Go to AV. Stay for 10 minutes in pseudo afk.
- Get Inactive debuf
- Die from any cause, observe debuf is gone.

### This opens abuse for player who wants to afk farm:
- join av
- die in any way
- run from gy as ghost to any safe spot where he will not bring attention to himself
- stay in pseudo afk while your fellows farming honor for you.

### Expected behavior. Describe how it should work:
- This debuf should persist while player is dead
- This debuf should be granted to players in ghost form(dead) also.
- This debuf should update value (1,2,3) of ticks while player in ghost form(dead).


## Alterac Vallue doesnt respect mount rules
   - Original issue number: 6364
   - Opened: 00:29 26/02/2024
   - Status: Open
   - Tags:
      - Battlegrounds
      - Needs Replication

### Please, provide a clear description what the bug is: 
Character is still mounted if returned from Alterac Valley (or any other bg) while being mounted on that bg. This gives opportunity to be mounted in locations where mounting is forbidden. Like so:

### Steps to reproduce the behavior with as much detail as possible:
As in video: https://www.youtube.com/watch?v=O7Wz45O79JE

### Triskelion of Roving Elements speed bonus doesnt stack with boots minor speed increase bonus 
   - Original issue number: 6376
   - Opened: 19:36 27/02/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
Triskelion of Roving Elements speed bonus doesnt stack with boots minor speed increase bonus.

### Steps to reproduce the behavior with as much detail as possible:
- Download and install MonkeySpeed for speed measurement
- Start running at normal speed (no speed modifiers)
- Enter the command /mscalibrate to calibrate the speed.
- Observe addon showing 100 as we run forward (thanks to Zorg for providing test results!)
- Put on Triskelion of Roving Elements into trinket slot. Start running forward, observe speed still equal to 108. *missing screenshot*
- If you remove speed boots, you still get 108 speed value.

Quest: An Honorary Gelkis 
Spell: Enchant Boots - Minor Speed

### How it should work
When both boots and trinket are put on you should get sum of their bonuses, so 116 value.

### Motivation for that change
*missing text*
for example. So even with stacked bonus player will have running speed increased less then Zanza provides. 8. This quest item is available for both factions in any given moment, so it doesn't discriminate agains any group of players. 9. Literaly in description of item it says that it does "Minor increase to running and swimming speed" which player with boots enchant just doesnt observe at all. Imagine dissapointment of player who farmed so much reputation, did all quests, choose this trinket and saw its basically not working.
Additional thought

It would be great if devs can also check if Dyad of Twitching Elven Ears + stealth detection bonus stacks with all other + stealth detection bonuses, cause if it is not - it should be.

### Looking for turtles embedded addon leaks memory 
   - Original issue number: 6377
   - Opened: 20:27 27/02/2024
   - Status: Open
   - Tags:
      - Bundled AddOn

### Please, provide a clear description what the bug is:
LFT addon which is embedded into twow client leaks memory even when not actively used for party search.

### Steps to reproduce the behavior with as much detail as possible:
- Install pfDebug addon from shagu for memory consumption visualisation
- Run twow original client with pfDebug addon enabled.
- Right-Click on the Frame to open the Analyzer
- Press Scan button on alanyzer
- After Scan become active, close window with X on it.
- Play some game without using LFT in any way. Just kill some mobs in location.
- Try to play some more, but have at least 1 party member with you. (This was condition in which i observed this issue, but i don't know for sure if it is required condition to reproduce bug.
- I suppose effect will be more present it large online numbers on server, cause more events will happen.
- Open up Analyzer again and observe results like so:

### Expected behavior
Expected to have around zero leak value for such permanent addition to the game.

### Why its important
I play on old pc in which any lags are more noticible than more modern pcs. When any of addons leaks (uses in unreasonable way alot of memory) it makes garbage collector of game to run more frequently removing memory which were allocated by addon and actually already not used. Each garbage collection for me represents like 1-4 seconds freeze of game, which can be quite annoying in pve/raiding situation and brutaly horrifying in pvp situations. Especially its concerning cause this happens no matter what. And i dont have way to disable this addon, while i dont need this functionallity at all.

### Unlootable herbs in Silverpine Forest
   - Original issue number: 6408
   - Opened: 20:27 27/02/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
There is several herbs in silveprine forest that cant be looted due to zone change. They just dissapear when you try to get closer to them.

### Steps to reproduce the behavior with as much detail as possible:
- Do the same thing as shown in video.
- *missing video*

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
Object: Mageroyal
Object: Silverleaf

Related to #5312

### Expected behavior. Describe how it should work:
You should be able to close distance on them and pick them up.


## Mageroyal spawn inside of home 
   - Original issue number: 6410
   - Opened: 19:02 02/03/2024
   - Status: Open
   - Tags:
      - Object
      - Profession
   
### Please, provide a clear description what the bug is:
Mageroyal herb spawns inside of home. You can still barely see it through textures. Location: Hillsbrad Foothills 42.5 52.0.

### Steps to reproduce the behavior with as much detail as possible:
- Do the same thing as shown in video.
- *missing video*

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- Object: mageroyal

### Expected behavior. Describe how it should work:
This spawn should be removed or transefered somewhere outside of building.

