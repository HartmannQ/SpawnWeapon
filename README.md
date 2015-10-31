# SpawnWeapon <img src="http://i.imgur.com/swz59Xr.png"></img> <img src="http://i.imgur.com/t1dMFxm.png"></img>

<img src="http://i.imgur.com/2Q2eSwM.jpg"></img>
##Description

####This plugin allows you to remove default weapons and give players weapons that you want.

###Features:

              * You can choose different weapons for each map.
              * Gives specific weapons to particular team.
              * Removes BuyZone if you want it.
              
##Config File

####Put `spawn_weapon.ini` in sourcemod folder. Reads from it, if there is no map config (`map.spawn_weapon.ini`). If you want a separate file for example for nuke:
 
              * Create file nuke.spawn_weapon.ini, and in that map will be read from the file.

###Write a weapon that you want to give on spawn.
####Example:

              * M4A4 for Counter-Terrorists Team
              * AK-47 (CV-47) for Terrorists Team
              * Desert Eagle (Night Hawk .50c) for Both Team
              

```ruby
CT m4a1
TT ak47
CT deagle
TT deagle
```
###Weapon Names List   

```ruby
ak47 
aug
bizon
cz75a
deagle
decoy 
elite 
famas 
fiveseven 
flashbang
g3sg1
galilar
glock 
hegrenade
hkp2000 
incgrenade
knife
m249
m4a1
m4a1_silencer
mac10
mag7
molotov 
mp7
mp9
negev 
nova
p250
p90
sawedoff 
scar20
sg556 
smokegrenade 
ssg08 
taser 
tec9 
ump45
usp_silencer
xm1014
```
### Cvar

#### `buyzone_disable` "1" - Buyzone Remove/Disable 
* 1 - Disable/Remove 
* 0 - Enable/Not Remove .
