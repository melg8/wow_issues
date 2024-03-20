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



## Wrong "Soulbound" status of Zebra mount item on site 
   - Original issue number: 6448
   - Opened: 21:49 06/03/2024
   - Status: Open

### Please, provide a clear description what the bug is:
For Zebra mount item on site it says its Soulbound, but ingame it says that it is "Binds when used" which is also confirmed by gm.

### Steps to reproduce the behavior with as much detail as possible:
- Look at description of item on site: *missing image*
- Compare it with description of item ingame: *missing image*

# IDs of affected creatures, items, quests or spells with a link to the relevant page:
Item: Zebra

## Expected behavior. Describe how it should work: 
Site should also say "Binds when used" on this item cause it is somewhat hard to obtain item and knowledge about it being soulbound or not is actually can change g *missing text*


## Possible race condition in combat logs from server 
   - Original issue number: 6458
   - Opened: 16:17 07/03/2024
   - Status: Open

### Please, provide a clear description what the bug is:
I oberved log notification about damage dealed to target which is already dead judging by the logs. Maybe its related to Hand of Justice cause i got proc of it at start.

### Steps to reproduce the behavior with as much detail as possible:
- Stay face away from some low health enemy Zhevra but in melee range.
- Make 4 buttons with same attack (like kick)
- Spam them alot with 4 fingers
- Wait for zebra to slowly go towards your facing direction
- Observe log as such: *missing image*

Zhevra Charger has at least 386 hp, so it wasnt dead just from 149 damage kick. ](https://database.turtle-wow.org/?spell=1769) Item: Hand of Justice NPC: Zhevra Charger

### Expected behavior. Describe how it should work:
Logs should be in logical order - first all logs about damage, then that i killed target, than that target dies.


## Can join queue for arathi basin with lvl 1 character
   - Original issue number: 6464
   - Opened: 10:38 08/03/2024
   - Status: Open
   - Tags:
      - Battlegrounds
      - Bundled AddOn
      - NPC
### Please, provide a clear description what the bug is: 
When there is arathi basin weekend you can join queue for arathi basin as lvl 1 character after talking to League of Arathor Emissary.

### Steps to reproduce the behavior with as much detail as possible:
- Talk to League of Arathor Emissary in capital sity with your lvl 1 character while its Arathi Basin weekend.
- Video example: *missing video*

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- NPC: League of Arathor Emissary

### Expected behavior. Describe how it should work:
Shouldn't be inconsistent. You shouldn't be able to join AB queue as lvl 1 that way. Or it should also be available in client Battleground Queues addon if joining AB as lvl 1 is intentional.

## Hardcore scoreboard is empty on site 
   - Original issue number: 6465
   - Opened: 11:50 08/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
On site https://armory.turtle-wow.org/hardcore/ Hardcore scoreboard just shows twow logo, and info about hardcore challenge but not participants names.

### Steps to reproduce the behavior with as much detail as possible:
- Go to https://armory.turtle-wow.org/hardcore/
- Observe *missing screenshot*
- Or like this in firefox: *missing screenshot*

This was tested on:
- firefox
- brave
- google chrome
- microsoft edge
- tor browser to excl *missing text*

## Engineering trainer teaches you both Apprentice and Journeyman ability at same time at relearn 
   - Original issue number: 6467
   - Opened: 00:27 09/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
Engineering trainer Nogg is out of his mind! When you try to learn from him secondary proffesion he teaches both Apprentice and Journeman skill into you instead of just Apprentice. It looks like this: *missing screenshot*.

### Expected behavior. Describe how it should work:
Should only learn Apprentice part.

## The Murkfisher actually doesnt catches fish. 
   - Original issue number: 6476
   - Opened: 22:54 09/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is: while it says literally in description that "Catches fish and foe alike."

### Steps to reproduce the behavior with as much detail as possible:
- Get The Murkfisher item
- Try to fish with it
- Observe message that you need fishing pole while you literally have one in your hands.

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- Item: The Murkfisher

### Expected behavior. Describe how it should work:
You should be able to fish with this item in your hands.


## GetCurrentMapContinent return crazy big numbers while in instances
   - Original issue number: 6486
   - Opened: 16:33 11/03/2024
   - Status: Open
   - Tags:
      - Core



### Please, provide a clear description what the bug is: For example when you go inside of UBRS/LBRS GetCurrentMapContinent() return you value 17. BRD gives you 14.

### Steps to reproduce the behavior with as much detail as possible:
- Use macro (or just in chat): /script DEFAULT_CHAT_FRAME:AddMessage("Continent id: ".. GetCurrentMapContinent());
- Go outside, touch some grass, use this macro, observe: 1 - for Kalimdor, 2 - Eastern Kingdoms as per usuall values
- Go inside BRD, use this macro. observe: *missing screenshot*
 value is 14.

### Expected behavior. Describe how it should work:
Some addons just refuse to work in instances, just to name a few:
- MonkeySpeed - Adds a simple movable speedometer displaying speed as a percentage of run speed.
- NotesUNeed - Manager that allows you to track Friends, Ignores, Guild members, Quests, Items and generic notes
- Spy - Detects and alerts you to the presence of nearby enemy players.
- All addons based on Astrolabe library (as Spy uses it for example).

All of this addons are okay with having unknown ids of zones and can handle it, but they weren't ready that vanilla universe will be expanded to have at least 17 known continents. So when you load up in dungeon you just see constant ongoing spam of errors from addons, which is really annoying. Although i fixed them for myself, i think it would be better to have general fix on server side to not have this problem in the first place.


## Jaedenar Adept zero distance blink + no delay
   - Original issue number: 6487
   - Opened: 16:33 11/03/2024
   - Status: Closed
   - Tags:
      - Correct on VMaNGOS
      - NPC
      - Reproduced



### Please, provide a clear description what the bug is:
After being distracted when Jaedenar Adept uses blink ability they stay in same position after blink as they were before blink.

### Steps to reproduce the behavior with as much detail as possible:
- As rogue throw distract such that Jaedenar Adept is affected by it, but yet not aggroed by you.
- Go close enough so Jaedenar Adept aggroes on you, start melee range attacks
- Kick his first fireball which provokes blink
- Or just wait for first spell to be casted, while still attacking Jaedenar Adept with melee attacks
- Observe Jaedenar Adept blink to same place it was before.

Video of such thing happening: *missing video*
No Jaedenar Adept were harmed while filming that video.

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- NPC: Jaedenar Adept
- Spell: Blink, Distract

### Expected behavior. Describe how it should work:
As per spell tooltip Jaedenar Adept should blink and appear in 20 yards from his initial position. Even after being distracted.

## Jaedenar Adept doesn't blink out of stunlock
   - Original issue number: 6488
   - Opened: 18:44 11/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
When stunlocked Jaedenar Adept doesn't use blink ability to get out of it and just dies.

### Steps to reproduce the behavior with as much detail as possible:
- Apply any stunlock abilities towards Jaedenar Adept while being in melee range with it
- Observe it not using blink to get out of stunlock and get distance. Example: *missing video*

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- NPC: Jaedenar Adept
- Spell: Blink

### Expected behavior. Describe how it should work:
This iconic spell is used by mages to not only gain distance but also to get out of stuns. If Jaedenar Adept has it, it should use it to get out of stunlock. I discovered this bug whien i tried to use Jaedenar Adept as target dummy to test my macroses, but was dissapointed that it doesnt perform blink while stunned.


## Antnormi's stun doesn't respect free action potion. 
   - Original issue number: 6490
   - Opened: 22:30 11/03/2024
   - Status: Open

### Please, provide a clear description what the bug is:
When fighting Antnormi his stun goest through even if you have free action potion used.

### Steps to reproduce the behavior with as much detail as possible:
- Start fight with Antnormi
- Drink free action potion
- Observe his stun still on you while you have free action potion on you;

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- Item: Free Action Potion
- Spell: Cowering Roar

### Expected behavior. Describe how it should work:
It shouldn't stun you if you used free action potion. It doesn't have any interesting animations like npc from The Deadmines which swaps weapons on certain health, and you need to be stunned in order for him to finish animation. Here its just stun which says its stun, and not sleep or something else, but which ignores main anti-stun potion in game.

### Antnormi description on site lacks abilities page
   - Original issue number: 6491
   - Opened: 22:34 11/03/2024
   - Status: Open
   - Tags:
      - Website

### Please, provide a clear description what the bug is:
Seems that Antnormi lacks page about his abilities, for example that he has stun ability Cowering Roar.

### Steps to reproduce the behavior with as much detail as possible:
- Go to url https://database.turtle-wow.org/?npc=65125
- Scroll down
- See lack of spells description on page.

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- NPC: Antnormi
- Spell: Cowering Roar

### Expected behavior. Describe how it should work:
It should describe all of his abilites, also should be same for any other bosses in that instance.

### Battle Tabards give weird Entering Battleground debuf
   - Original issue number: 6494
   - Opened: 13:34 12/03/2024
   - Status: Open
   - Tags:
      - Item
      - Needs Replication

### Please, provide a clear description what the bug is:

You can right click Battle Tabard on you and you get Entering Battleground debuf.

### Steps to reproduce the behavior with as much detail as possible:
- Wear Warsong Battle Tabard
- Right click it
- Observe debuf on you

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- Spell: Entering Battleground

### Expected behavior. Describe how it should work:
Should not be clickable like Orgrimar Tarbard for example. And should not give any debufs.

## Can teleport to battleground while in combat and under crowd control spells
   - Original issue number: 6495
   - Opened: 13:40 12/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
When battleground queue procs, you can enter battleground from in combat state. Not only that, you can enter it while being under crowd control spells from mobs or from players.

### Steps to reproduce the behavior with as much detail as possible:
- Queue AV as horde for quick procs
- Start combat with any npc or player
- Press enter battleground
- Observe being teleported to battleground

### Expected behavior. Describe how it should work:
Queue proc should not accept players entering battleground untill they are out of combat. Because of current mechanics people abuse it world pvp situations, like teleporting out of combat/rogue cc from middle of enemy city to avoid being killed. Or do one-shot attacks in gadgedzan (and other neutral cities) and then immediately accepting battlegound proc for avoiding being punished by guards.

## /afk removes you from battleground instantly even in combat and under crowd control spell
   - Original issue number: 6496
   - Opened: 13:45 12/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
If you use /afk on battlegound you get afk state and get teleported out of battleground right away. Even if you are in middle of fight and under crowd control spells of other players.

### Steps to reproduce the behavior with as much detail as possible:
- Get into any battleground
- Start fight with other player, get "In combat status"
- type /afk in chat
- Observe being removed from battleground while still in combat.

### Expected behavior. Describe how it should work:
Afk status should remove frome battleground only if you are not in combat. When you are in combat or under crowd control spells you should not be able to escape pvp by just typing /afk.

In current situation players abuse such mechanics, for example they showup on AV, run for black lotus spawn, even if its on enemy side of map, and after they got it(or not) they simply /afk out of battleground, while under guards, enemy rogues stunlocks etc. Which is quite annoying for players who could get honorable kills but miss them just cause someone used /afk command. Also this mechanics sometiimes is abused by hardcore characters, which feel safe to join av and try to farm there, cause in case of any danger they can insta /afk away from bg while not being punished for that.

## Stealthed players on same team can't see eachother in same raid group in stealth on battlegrounds
   - Original issue number: 6497
   - Opened: 13:52 12/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
When two players are in same group you can see stealthed player just fine. But if you are in same raid group, like on AV, but in different party groups - you can only see eachother on close range via stealth detection.

### Steps to reproduce the behavior with as much detail as possible:
- Join Alterac Valley battleground
- Find some rogue or other stealther class in your team but in different group
- Observe not being able to see him in distance while he is stealthed.

### Expected behavior. Describe how it should work:
While in same raid group on battlegrounds you should be able to see all stealthed friendly players no matter if they are in same party or not. Because of current implementation its hard for stealthed players to coordinate actions with each other, because only way they can see each other is on minimap. So in critical situations players may miscoordinate (for example going onto two different objectives, instead of one) or not approaching enemy at the same time. In other vmangos derived servers i saw that strategy implemented and it works great for improving teamplay.

## Inconsistency between teleport to guild house and hearthstone
   - Original issue number: 6498
   - Opened: 13:59 12/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is: 
In current implementation teleport to guild house takes only 5 seconds, while hearthstone casts for 10 seconds. In current implementation teleport to guild house is not available while in combat, but hearhstone is available in combat, with cast prevention after getting damage. In current implementation teleport to guild house doesnt give visual queues of being casted, while hearthstone give visual casting animation.

### Expected behavior. Describe how it should work: 
I think they should both work the same way, with only difference being position on map where you are traveling to. In current implementation teleport to guild house can be abused by HC players, to escape danger faster, while HS users cant escape in 5 seconds, rendering people not in guilds more vulnerable.


## Human racial diplomacy gives more than 10% bonus.
   - Original issue number: 6501
   - Opened: 14:36 12/03/2024
   - Status: Open
   - Tags:
      - Core

### Please, provide a clear description what the bug is:
Human racial Diplomacy should give +10% reputation bonus. But when you kill npcs which give +5 reputation without bonus, you get +6 reputation each time which is 6/5 = 1.2 == 20% bonus.

### Steps to reproduce the behavior with as much detail as possible:
- As human go to Desolace and kill Maraudine Scout
- Observe getting 6 reputation each time

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- NPC: Maraudine Scout
- Spell: Diplomacy

### Expected behavior. Describe how it should work:
In current implementation +10% round up to +1 reputation from 5 base reputation gain. Easy fix - random gain of 5 or 6 reputation per kill, so in average it would give correct +10% reputation gain compared to other races. Not +20% how is it now.


## Supercharged Chronoboon Displacer doesnt show buffs it captured
   - Original issue number: 6502
   - Opened: 19:08 12/03/2024
   - Status: Open
   - Tags:
      - Bundled AddOn
      - Custom Content Polish

### Please, provide a clear description what the bug is:
When mousover Supercharged Chronoboon Displacer you can't see buffs and their durations.

### Steps to reproduce the behavior with as much detail as possible:
- Get Supercharged Chronoboon Displacer with some buffs captured
- Mouseover it
- Observe tooltip like so: *missing screenshot*

### Expected behavior. Describe how it should work:
It should show captured buffs with timers like it was presented on site: *missing screenshot*


## Alromion gives you hard epilepsy check instead of flying. 
   - Original issue number: 6505
   - Opened: 00:08 13/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
When you press gossip of Alromion "Please guide me through Caverns of Time" instead of just mounting you on fly mount, it also snaps you into the ground and starts randomly spin you character and camera.

### Steps to reproduce the behavior with as much detail as possible:
- Stay infront of Alromion and press "Please guide me through Caverns of Time"
- Press forward as soon as gossip closed. This will just stop you inplace, but if you hold your right mouse button, or move in other directions it will add to the shuttering effect.
- You can increase effect if you continue to try to press movement in different directions.

### WARNING!!! if you have epilepsy do not play this videos.

### Steps to reproduce effect:
- When i first encountered this, looked like so: *missing video*
- Other person near me also got checked: *missing video*

Please fix it asap, its like a warcrime agains humanity, kek.

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- NPC: Alormion

### Expected behavior. Describe how it should work:
Should just roam left and right on ground normally, and not preve *missing text*


## Some of riding animals doesn't provide gossip for riding for 50 copper near gadgedzan 
   - Original issue number: 6506
   - Opened: 00:43 13/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
Some of Riding animals near Gadgetzan doesnt provide option to ride them for 50 copper.

### Steps to reproduce the behavior with as much detail as possible:
- Do as in video: *missing video*

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- NPC:
    - Riding Horse
    - Riding Tiger
    - Riding Raptor

### Expected behavior. Describe how it should work: 
Should be able to click on each of them and ride them for 50 copper.

## Some mounts doesnt have sound for spacebar press while standing still
   - Original issue number: 6507
   - Opened: 0:51 13/03/2024
   - Status: Closed

### Please, provide a clear description what the bug is:
For example Riding Zhevra doesnt produce any sound when you press space bar while standing still.

### Steps to reproduce the behavior with as much detail as possible:
- Mount Zhevra, or Immortal's Champion Drake for example
- Stay still
- Press space bar
- Observe animation playing while no sounds made by mount.

### IDs of affected creatures, items, quests or spells with a link to the relevant page:
- Immortal Champion's Drake

### Expected behavior. Describe how it should work:
The can produce same sound as they do when you just mountup first time. Or some castom sound can be used, like zhevra can use sounds from horses.

# Issues created inside of new bug tracker system.

### You can select too many categories on issue tracker
   - Original issue number: 6530
   - Opened: 23:55 14/03/2024
   - Status: Closed
   - Tags:
      - Website

### Describe the Issue:
You display and user can select too many categories in issue tracker.

## No way to serach by category 
   - Original issue number: 6531
   - Opened: 23:58 14/03/2024
   - Status: Closed
   - Tags:
      - Website

### Describe the Issue: 
There is no way to search issue by same category on site.

## Title of bug report can be too long.
   - Original issue number: 6532
   - Opened: 23:59 14/03/2024
   - Status: Closed
   - Tags:
      - Website
   
### Describe the Issue:
Title doesnt have check for its length

## Can't mount on Immortal Champion's Drake in capitals 
   - Original issue number: 6554
   - Opened: 22:57 15/03/2024
   - Status: Closed
   
### Describe the Issue: 
It says can't mount here when you try to mount on Immortal Champion's Drake in city. While i think i saw regular drakes used in cities. Immortal Drakes should also be usable in capitals. Especially considering amount of their owners online nowdays are much less because of server pop rotation.


## You still can select too many categories on issue tracker
   - Original issue number: 6555
   - Opened: 22:58 15/03/2024
   - Status: Closed

### Describe the Issue:
You removed it from submit report but it still available after creation.


## You can still perform backdoor jump on av 
   - Original issue number: 6556
   - Opened: 23:06 15/03/2024
   - Status: Closed

### Describe the Issue:
You can still perform backdoor jump on av

### How to reproduce:
https://youtu.be/L0KciGFEVN8

## You can be afk on av all day using dig rat
   - Original issue number: 6557
   - Opened: 23:09 15/03/2024
   - Status: Closed

### Describe the Issue:
You can avoid being kicked by auto system from av using dig rat.

### How to reproduce:
Deploy dig rat somewhere on av. Use non damginc ability on it to begin combat. Observe removal of debuff from character. Also combat doesnt brake so you can just stand in combat with dig rat there for hours.

## Caverns of time is unmountable area 
   - Original issue number: 6562
   - Opened: 11:04 16/03/2024
   - Status: Closed

### Describe the Issue:
You cant mount there but with such massive area without anything in it its annoying to walk around when you need to go outside or to move from instance exit to instance entrance. I don't belive that suggestions on forum work so i post it here.

## Corrupted sand is annoying 
   - Original issue number: 6567
   - Opened: 11:22 16/03/2024
   - Status: Closed

### Describe the Issue:
To much of it drops, if you dont use special addon to auto need it, its whole separate work to need all the sand, while progressing this linear instance to the end.

### Young goretusk hyperspawn
   - Original issue number: 6588
   - Opened: 13:26 17/03/2024
   - Status: Closed
   - Tags:
      - NPC

### Describe the Issue:
Young goretusk near graveyard on Sentinel Hill 51.8 49.0 has hyperspawn. He spawns right after it was killed (in 10-15 seconds). Can be abused and farmed afk by clicker.

## Account management page doesnt show characters
   - Original issue number: 6589
   - Opened: 13:28 17/03/2024
   - Status: Closed

### Describe the Issue:
Account management page doesnt show characters, just shows blank space.

## Gms visual appearance doesn't attract attention 
   - Original issue number: 6591
   - Opened: 14:03 17/03/2024
   - Status: Closed

### Describe the Issue:
When gm appears for personal intervention into some issue. Main and only way to visually define him/her as gm is their lvl higher than 60. Gm ticker will be usually eaten by addons representation. But in terms of their appearance they just appear as goblin/tauren etc in normal cloths. So people around them may not notce that this is not regular person but gm. I think gms should have some cusom form (like illusion, or at least custom cloths, or custom size of model, that will always tell anyone around them that this is gm at his work, and you should not mess around with it).


## No way to close your own issues. 
   - Original issue number: 6626
   - Opened: 14:03 17/03/2024
   - Status: Closed
   - Tags:
      - Website

### Describe the Issue:
If one of my issues was fixed, and i noticed that, there is no way to close my issue. I can only delete it.

As an example one of my issues that already should be closed: https://turtle-wow.org/bug-report?id=6465 (ignore the fact it was created on github and moved here and has different username, so i couldnt controll it anyway) but even for owned isssues this still holds.


### Voting system gives you way to wote 3 times just by fast clicking up wote
   - Original issue number: 6632
   - Opened: 21:39 18/03/2024
   - Status: Closed

### Describe the Issue:
Voting system gives you way to wote 3 times just by fast clicking up wote. Probably can be even further abused if you change source code on client side. Server seems not to check for amount of wotes from 1 person on the issue.

Also system doesnt check if you choose any particular character for his nick to be displayed. So you can wote just from newly created account.


## Issue tracker doesnt provide way to determine if issue was answered by team member 
   - Original issue number: 6635
   - Opened: 22:06 18/03/2024
   - Status: Closed

## Describe the Issue:
When your issue wasnt closed, but was answered by team member - like here happened to me: https://turtle-wow.org/bug-report?id=6600 there is no way to see if it was handled by one of staff members or not on issues list. Would be nice to have ticker for that, or even separate marker that this issue was in fact handled by team member in some way or another. Or that team member wrote something in it. Cause i have alot of issues where answers already exist, but its my own comments, or comments by others, and i am intrested in seeing if there was feedback from twow team.

I saw "Turtle wow staff" on messages by torta, so thats good, but something like that need to be shown on the list of all issues as well. And maybe be sortable by that criteria.

You can make number of messages icon green if it has answers by team mebmer.


## If users cant close their issues on tracker, they shouldnt have delete also
   - Original issue number: 6639
   - Opened: 23:19 18/03/2024
   - Status: Closed

### Describe the Issue:
If users cant close their issues on tracker, they shouldnt have delete also. From security perspective now regular user can just nuke all of its issues.


## Add In progress ticker to issues
   - Original issue number: 6640
   - Opened: 23:30 18/03/2024
   - Status: Closed

### Describe the Issue:
Its hard to determine when your issue is closed with words "will be fixed in future(next update/next patch/next week) etc" - if it was already fixed, or its too early to recheck how and if your issue was fixed. "In progress" ticker would be nice to have.
Then issue lifetime is like -opened by someone -> marked by twow team with tickers -> in progress -> closed/done or rejected/not planned/duplicated.
So you can see on what people work now, and you can know that closed issue was done and you can go on live server and check that it was indeed fixed for good.


## New description editor has all parts of issue temlpate at same line
   - Original issue number: 6649
   - Opened: 19:40 19/03/2024
   - Status: Closed

### Describe the Issue:
New description editor has all parts of issue temlpate at same line, like so:

Describe the Issue: How to reproduce: Character the bug occurred on:

### It should be like:
- Describe the Issue:
- How to reproduce:
- Character the bug occurred on:


### Bug tracker looks badly formatted on mobile phones and tablets.
   - Original issue number: 6659
   - Opened: 21:00 19/03/2024
   - Status: Closed

### Describe the Issue:
Bug tracker looks badly formatted on mobile phones and tablets. It shows some of text out of border of issue box and some of icons just float around.


# Still open issues

## No way to fix title name on issue tracker
   - Original issue number: 6533
   - Opened: 00:00 15/03/2024
   - Status: Open
   - Tags:
      - Website    

### Describe the Issue:
No way to fix title nime on issue tracker


## Previews for uploaded images has wrong aspect ratio 
   - Original issue number: 6534
   - Opened: 00:02 15/03/2024
   - Status: Open
   - Tags:
      - Website

### Describe the Issue:
Previews for uploaded images has wrong aspect ratio

### How to reproduce:
Upload image in 1920x1080 observe preview for it.

## Links are not clickable
   - Original issue number: 6535
   - Opened: 00:06 15/03/2024
   - Status: Open
   - Tags:
      - Website
      
### Describe the Issue:
Links are not clickable.

### How to reproduce:
Click it: https://turtle-wow.org/bug-report?bugReportId=5105

Okay maybe they are clickable after upload but not in the moment of writing something. Oh yea. If you are in Add comment section - they are not clickable.

### Can get 413 content too large 
   - Original issue number: 6538
   - Opened: 00:22 15/03/2024
   - Status: Open
   - Tags:
      - Website

### Describe the Issue:
Got this error:
"Oops! An Error Occurred The server returned a "413 Content Too Large".
Something is broken. Please let us know what you were doing when this error occurred. We will fix it as soon as possible. Sorry for any inconvenience caused." When trying to write long text as comment to other issue.


## Tags on issues change color
   - Original issue number: 6552
   - Opened: 22:49 15/03/2024
   - Status: Open
   - Tags:
      - Website

### Describe the Issue:
If you go into concrete issue then press button to return back to main issues board some of issues tags change color - for example Wont fix from red to blue. If you press on "opened reports" button tagc change color again to usual color scheme.

## You can safespot in air using Alormion mount
   - Original issue number: 6553
   - Opened: 22:50 15/03/2024
   - Status: Open

### Describe the Issue:
I tried to change issue text and press save button, but instead of saved changes on issue i got white screen with 500 error on it.

## You can safespot in air using Alormion mount #6563
   - Original issue number: 6563
   - Opened: 11:09 16/03/2024
   - Status: Open

### How to reproduce:
Mountup on Alormion, fly to needed location, get some distance from ground then 2 seconds before dismount press space bar - so it will start roar animation. After dismount observe you standing on air. You can mountup there, you can sit there. Probably you can safespot this way. Should dropdown in any case.

## Illusion: Murlock is broken
   - Original issue number: 6564
   - Opened: 11:09 16/03/2024
   - Status: Open

### Describe the Issue:
When you use other illusions, and press on your mount your illusion automatically cancels out and you just mount up in relgular form. Murlock illusion just errors out that "you are in shapeshift form". Which forces you to manually cancel illusion, which btw isnt instant but takes 3 more seconds to "cast". It should behave in same way as other illusions.


## Fly mount can be used while in illusion:murlock
   - Original issue number: 6565
   - Opened: 11:17 16/03/2024
   - Status: Open

### Describe the Issue:
You can use fly mount in tanaris while in murlock form. This is inconsistent with the idea that you cant use mounts while you in shapeshift murlock form.


## Add stun before mounting on alormion
   - Original issue number: 6568
   - Opened: 11:47 16/03/2024
   - Status: Open

### Describe the Issue:
Known issue that you get stuck into floor if you move while getting mounted on Alormion. Easy fix - add 2 seconds stun, like "your mind synchronizing in time with beast" or something. This will have some roleplay aspect and will fix issue when people should struggle for 45 seconds instead. 

Seems it was added some extra Z to character when he is mounting ont Alormion. I tested this issue and could reproduce stuck bug only 1 out of 19 tries. So i think it can be closed as fixed by now.

Hmm i double checked this, and found spot near his head on right side - which produces this bug. It can be related to terrain difference, if he spawns your mount on same Z as himself, and you stay slightly above that you will get under floor texture. while all of your body still above it. Maybe if we move him a little so he stands where all surrounding area is flat it can fix it once and for all.


## War mode doesnt give bonus gold on daily quests
   - Original issue number: 6570
   - Opened: 12:43 16/03/2024
   - Status: Open


### How to reproduce:
Get lvl 60 take quest from Mystic Guay'Jin - they have base reward 50 copper for one quest and 20 silver for other quest. When you finish this quests while having warmode on - you just get 50 copper and 20 silver. All other quests give more than their base value in description due to warmode buff.

## Glasshide basilisks continues cast of stun even out of range
   - Original issue number: 6571
   - Opened: 12:43 16/03/2024
   - Status: Open

### Describe the Issue:
Glasshide basilisks will continue casting their stun ability even if you run out of melee range. After that animation played but no effect is applied to player. So they just waste this ability. They should stop casting if player out of range of ability, or this ability should have larger range to stun when you at distance from mob.

## AV SHB can be captured thorugh the floor
   - Original issue number: 6573
   - Opened: 13:11 16/03/2024
   - Status: Open

### Describe the Issue:
You can jump up to the weapons rack in the middle stairs section move camera out a bit and click to the flag which is on floor above you. Flag will still be captured.
Here is example for DB south bunker. https://youtu.be/0FxQobQltYY

## Menethil gifts quest works in 10 man strat ud
   - Original issue number: 6574
   - Opened: 14:09 16/03/2024
   - Status: Open

### Describe the Issue:
Menethil gifts quest works in 10 man strat ud as i heard all quest related stuff should be blocked when 10 manning this raid.

## Couldn't reproduce shows as black on black in main bugtracker page #6577
   - Original issue number: 6577
   - Opened: 14:09 16/03/2024
   - Status: Open


###  Describe the Issue:
Couldn't reproduce tag - is unreadable on main page of bug tracker, and also it changes color if you get into issue itself

Example how it looks here: https://ibb.co/3hGttFG

### Select box in bug tracker are not user friendly #6578
   - Original issue number: 6578
   - Opened: 17:25 16/03/2024
   - Status: Open

### Describe the Issue:
When you use any select box in bug tracker (for example for server choose) - if you miss one pixel to the left of box itself - it just closes whole thing, and not put choice in. Also left part of select box are blending in with background making it hard to distinguish.

### Waiting to ressurect while being alive on av
   - Original issue number: 6579
   - Opened: 18:28 16/03/2024
   - Status: Open

### Describe the Issue:
You can get this buff while being alive. IDK how exactly, but thats the video with it happening: https://youtu.be/ovEW08y0aVM

## Account management page doesn't show any services
   - Original issue number: 6590
   - Opened: 13:29 17/03/2024
   - Status: Open

### Describe the Issue:
https://turtle-wow.org/profile#profile-overview - doesn't show services when you click on them, just blank space.

## Battlegrounds give more people join than max cap #6594
   - Original issue number: 6594
   - Opened: 20:52 17/03/2024
   - Status: Open

### Describe the Issue:
I consistently observe more people on bg than its max capacity, like av with 41-44 alliance players, arathi with 17 players on one side. warsong with 11 players on one side.

## Report system has useless scroll bars everywhere
   - Original issue number: 6595
   - Opened: 20:53 17/03/2024
   - Status: Open

### Describe the Issue:
Under each post and each reply you get vertical and horizontal scroll bars, without middle part. Even when message is 100% fit on screen.
I linked image of what i'm talking about https://ibb.co/7JmVkJb
For example this is how github shows answers under issue of different size. How you can see no such scrollbars present anywhere. https://ibb.co/C0T2fYv

## Lighting the pyres quest, pyres diout too fast
   - Original issue number: 6596
   - Opened: 21:04 17/03/2024
   - Status: Open
 
### Describe the Issue:
When you light pyre - it shuts down like in 10 seconds, so there is no point in running around the area, you can just stand on one place and light one pyre til l quest is complete. time should be at least minute or so.

## Client freeze when minimizing game on windows 10
   - Original issue number: 6597
   - Opened: 21:10 17/03/2024
   - Status: Open

### Describe the Issue:
When on windows 10 you press windows key and game gets minimized window, sometimes it freezes game completely. Only full game restart helps.

## Hunters pet last hit damage showing over killed target after death #6598
   - Original issue number: 6598
   - Opened: 21:45 17/03/2024
   - Status: Open

### Describe the Issue:
When you kill mob A with pet, and then start attack on mob B, sometimes you suddenly get attack value over mob A which long dead already.
Video example: https://youtu.be/hCQP6XAZzqM
Directly related to https://turtle-wow.org/bug-report?bugReportId=6458 But has different visual represenation so i wrote it as separate issue. If you watch closely logs you will observe display of pet damaging target after target death. This in turn will kick in visual damage representation kick in when new log messages appear - when you hit your next target. So main issue is 6458 and this is visual manifestation of that issue.


## Dizzle fuelbopper has empty items list for sell
   - Original issue number: 6600
   - Opened: 21:58 17/03/2024
   - Status: Open

### Describe the Issue:
Dizzle fuelbopper has empty items list for sell although in database it show as non empty: https://database.turtle-wow.org/?npc=80137
Maybe related to me being non goblin race. But not intuitive.

## You get out of vanish if your ranged weapon hit after you vanished
   - Original issue number: 6601
   - Opened: 22:06 17/03/2024
   - Status: Open

### Describe the Issue:
If you shoot ranged weapon and then vanish asap you will enter vanish, but will get out of it when arrow hits enemy.
Video example: https://youtu.be/1n-TsgIWhkY
While for pve maybe this is not that much of importance, but in pvp for rogue which is defending some gy on AV it can be quite annoying cause if you hit capper with ranged weapon and insta vanish - you get out of it and hit by npcs. Other way around you forced to stay out of stealth while your arrow in flight - and get all hits from all npcs around you.

### How it should work:
You shout, you vanish, you hit target, you stay in vanish.

## Raptor Punch only shows debuff "you drunk" #6602
   - Original issue number: 6602
   - Opened: 22:20 17/03/2024
   - Status: Open

### Describe the Issue:
Raptor Punch doesnt show buff part in buff, and only shows text "you drunk" in debuf part, not showing - stamina debuff effect.
https://database.turtle-wow.org/?item=5342
