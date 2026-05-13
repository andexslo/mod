N0P present : AWE v3.1


++ Object

AWE 3.1 is the follow-up to AWE v3 Community Edition, which itself was a follow-up to AWE 3.0 beta 10b.


++ Added/changed features since 3.0 beta 10b

AWE v3.1 :

- better handling of incompatible gametype and map, with a fallback gametype/map
When an incompatible gametype/map is detected, the server no longer switches to DM with players stuck into spectators.
Instead, the current rotation item is skipped and the rotation continues on the next item.
When not using a rotation, the server switches to the gametype and map specified by the dvar awe_fallback_gametype_map.

- new option for spawn protection, allowing to punish a player attacking a protected player
A player attacking a spawn protected player can be punished : drop weapon, reflect damage or suicide.
This is controlled by dvar awe_spawn_protection_punish.

- new custom gametype : LIB (Liberation)
AWE now has 21 gametypes ! (5 standard, 16 custom)

- CTFB upgraded to 1.3 (bug fix)

- HTF upgraded to 1.1 (new options !)

- IHTF upgraded to 1.4 (bug fix)

- VIP upgraded to 1.4 (bug fix)

- more localized text

- more maps configuration for BT/DOM/ONS gametypes

- clan options : move clan members to the same team and non clan members to the other team, reserve a server slot to ensure priority of clan members over non clan members

- new option allowing players to safely jump over tripwires (dvar awe_tripwire_jump)

- anti camping

- fix : CNQ reference removed from CoD2maps.arena


AWE v3 CE :
- new client mods with red dot on compass disabled when enemy fires
- new custom gametypes : BT, CTFB, CNQ, DOM, ECTF, EHQ, ESD, HM, ONS, VIP, totalling 20 gametypes !
- upgraded gametype : IHTF (1.3)
- Lee Enfield selectable from American weapons menu
- warmup delay
- anti dive bomber & bunny hopper
- next map voting extension
- new option in the ingame vote menu allowing to choose from all available gametypes
- new option in the ingame vote menu allowing to choose from all available maps
- new option in the ingame menu allowing to display the serverinfo screen
- admin commands
- bash mode
- fix : can no longer place tripwire when standing at spawn
- fix : turret temperature bar moved a little higher to avoid overlapping with server logo, localized string for overheating message
- fix : AWE bots now working when secondary weapons enabled, some runtime errors corrected
- optimized handling of serverinfo dvars, to completely avoid "SV_SetConfigValueForKey: overflow" error
- new options for team killing punishment : kick player, freeze controls during 1 minute


++ Note on the new custom gametypes

ECTF, EHQ and ESD are extensions of the stock CTF, HQ and SD gametypes respectively, with lots of customization and new features.
ESD brings features similar to the famous RSD gametype for COD1.

CTFB is CTF with a twist, which leads to interesting gameplay.

CNQ is the famous Conquest TDM gametype ported to COD2.

HM and VIP are role based gametypes, where certain players are the targets to reach. VIP is team oriented, whereas HM has no team.

DOM is a re-creation of the DOM gametype in COD/UO, with new features.
BT and ONS are variants of DOM, with important changes in the number and order of objectives.
For those familiar with COD3 on consoles, BT is the equivalent of the WAR gametype in COD3, but much better of course ;-)

CNQ and LIB need maps specially designed to support these gametypes.
BT, DOM and ONS need maps configuration data from a configuration file. AWE provides a default file with a selection of custom maps.


++ Compatibility

COD2 1.3 only


++ Installation

The installation of AWE v3.1 is the same as for AWE 3 beta 10b, and only differs by the following :

1. The package is available in a zipped form only.
There is no longer an installer for the Windows platform.
The install method is thus the same for all platforms (Windows, Linux, Mac OSX).

2. The client part is now available in 6 different versions instead of 3.
The original b0.iwd, b1.iwd and b2.iwd are still there unchanged.
Three new ones (a0.iwd, a1.iwd and a2.iwd respectively) are identical to their b counterpart with the only difference that they have the red dots on compass disabled when enemy fires.

Here is a summary of their features :
a0 = no blood mod + red dots on compass disabled
a1 = Blood mod version 1.0 (unrealistic) + red dots on compass disabled
a2 = Blood mod version 2.0 (realistic) + red dots on compass disabled
b0 = no blood mod + red dots on compass enabled
b1 = Blood mod version 1.0 (unrealistic) + red dots on compass enabled
b2 = Blood mod version 2.0 (realistic) + red dots on compass enabled

3. The client Sound part is now available.
While only work with this version of AWE 3.1

Here is a summary of their features :
z_awe_v3.1_client = Taunts I + Taunts II

--------------
Taunts I:
--------------

AMERICAN:

1. Hey fritzy, Hitler's a jackass punk!
2. What's the matter, not used to the enemy shooting back?
3. Hey fritz, kiss my ass, you dirty kraut bastard!
4. Got one!/Got him!
5. You can heil Hitler in hell!
6. That's one less kraut to worry about!
7. Hey fritz, Hitler plays with dolls!
8. Hey fritz, your sister said to say hi!
9. You're going home in a coffin fritz!

BRITISH:

1. See you in hell or Berlin, whichever I get to first!
2. Come ahead, you jerry cowards, square go, come on!"
3. Die, you jerry rotter!
4. Got one!/Got him!
5. Got that bloody wanker!
6. That's one less jerry to worry about!
7. You'll be pushing up daisies before this war's over!
8. Lucky bastard!
9. And come back anytime, you jerry bastards, we'll be waiting for ya!

RUSSIAN:

1. You poor fascist bastards came all the way here just to die!
2. How does it feel to die on the Russian front?
3. Die, you fascist bastard!
4. Got one!/Got him!
5. This one's for my mother/valentina/father/little sister/dog!
6. That's one less fascist to worry about!
7. Run, you dirty German bastards!
8. For mother Russia!
9. *Yells for his motherland*

GERMAN:

1. What is wrong, did you wet your pants?!
2. Die, that makes it easier for both of us!
3. Die!
4. Got one!
5. You were not that hard to kill! / That was too easy!
6. One less Russian/American/Brit to worry about!
7. (Allied Specific)
8. (Allied Specific)
9. You fight like a bunch of girls!

--------------
Taunts II:
--------------

AMERICAN:

1. Kiss my New York ass!
2. Give it up klaus, you think Hitler cares if you live, he don't give a rats ass about you!
3. Hey klaus, I'll piss on you in hell!
4. This one's from Tenessee!
5. New York says hi, you kraut bastard!
6. Hey klaus, your CO's wearing a dress!
7. Kick their asses back to the fatherland!
8. *Cheers*

BRITISH:

1. How about you nazis come out here and goose step into my sights!
2. Send them packing, lads!
3. So much for the master race!
4. Pack it, you jerry bastard!
5. Nailed him!
6. Put that in your pipe and smoke it!
7. Come on! Give the bastard another one!
8. Go and run, you jerry bastard!

RUSSIAN:

1. Die fritz, we'll throw you out in the spring!
2. Push back those fascist invaders!
3. Kill those fascists!
4. Another room, another dead German!
5. Better you than me, fascist!
6. Find your own building, fritz!
7. Eat Dirt! This is Russian soil!
8. For the Soviet Union and for your glorious motherland, get ready!

GERMAN:

1. Give up, we both know that you don't stand a chance!
2. In the end, you will be beaten anyway!
3. Sissy! Your whole army is girly!
4. (Allied Specific)
5. Better you than me, yank/Brit/communist!
6. (Allied Specific)
7. (Allied Specific)
8. (Allied Specific)

4. The server part of the mod is no longer presented as flat files but in a single IWD.
Server admins seeking further control can still uncompress it into files and folders.
When uncompressing, be careful to remove the blank gametype scripts (maps\mp\gametypes\*.gsc) in the client part IWD, otherwise the game will load them first and AWE won't start. Doing this will cause the loading screens to show the gametypes with a short name (eg "htf" instead of "Hold the Flag").
The server part (z_awe_svr_3.1.iwd) has to be placed in your fs_game folder, just like one of the client parts (a*.iwd or b*.iwd).


++ Configuration

The standard AWE dvars have been kept intact.
New dvars have been introduced to configure the new options.
Please refer to the bottom part of the sample awe.cfg, as well as all the separate gametype specific configuration files.
Bear in mind that in the sample awe.cfg all dvars definitions are commented out initially, so if you make a change be sure to have the dvar definition uncommented !

The new options for team killing punishment are 5 and 6 (awe_teamkill_method).
The new option for spawn protection punishment is in the spawn protection section of awe.cfg (awe_spawn_protection_punish).
The new option for allowing to jump over tripwires is in the tripwire section of awe.cfg (awe_tripwire_jump).


++ Credits

Core AWE 3.0 beta 10b : Bell - see specific readme
Compass red dots remover : Bullet-Worm
Lee Enfield for American : La Truffe - based on a mod by Bully & Shooter
Anti dive bomber & bunny hopper : La Truffe - based on the implementation in Astoroth's eXtreme+ mod
ECTF gametype : 0ddball and Shooter - based on CTF additions in Bullet-Worm's Powerserver mod
DOM gametype : Matthias, Tally, 0ddball and La Truffe - see specific readme
BT and ONS gametypes : 0ddball (mostly) and La Truffe (a tiny bit) - see specific readme
CNQ gametype : Tally and UncleBone - see specific readme
HM gametype : Tally - see specific readme
ESD gametype : La Truffe - includes modifications from #7's COD2Svr mod - see specific readme
CTFB gametype : La Truffe - based on the gametype from Matthias' Admiral mod - see specific readme
Admin commands : #7, from COD2Svr mod, with additions by La Truffe
Bash mode : #7, from COD2Svr mod
LIB gametype : [HI]DW, with minor changes by La Truffe
Next map voting extension, text localization, maps configuration for BT/DOM/ONS gametypes : 0ddball
EHQ, IHTF and VIP gametypes, warmup delay, new ingame options, fixes, serverinfo dvars change, new options for team killing punishment, handling of incompatible gametype/map, new option for spawn protection punishment, clan options, new option for tripwires, anti camping : La Truffe
Taunts I and Taunts II : Bjuster's Taunts 2.2 made by: -={AA}=-Bjusterbaarlik  

++ Contact

AWE official support forum @ RGN : http://www.raidersmerciless.com/forumdisplay.php?f=75

N0P (Nedgerblansky and 0ddball Productions) are :
- 0ddball (0ddball@free.fr or 0ddball.gromov@gmail.com)
- Nedgerblansky a.k.a. La Truffe (latruffe666@hotmail.com or latruffe666@gmail.com)