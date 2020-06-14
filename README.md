Chat Commands/all
:FSN: Framework API Documentation

Info:
The documentation is under mass development, I've no idea where I'm going with this, I just put it together really quick to help you and your players.

misc
/news role #
Set role for News job

Argument
Type
Required
Description
#1 role
string
?
/news toggle #
Toggle the News job

Argument
Type
Required
Description
/givecash (gc) #
Give cash to another player

Argument
Type
Required
Description
#1 player
source (number)
?
#2 amount
number
?
/mask (m) #
Toggle mask (MP_FREEMODE models)

Argument
Type
Required
Description
/hat (h) #
Toggle hat (MP_FREEMODE models)

Argument
Type
Required
Description
/glasses (g) #
Toggle glasses (MP_FREEMODE models)

Argument
Type
Required
Description
/ping #
Send a ping to another player

Argument
Type
Required
Description
#1 player
source (number)
?
/ping accept #
Accept a ping

Argument
Type
Required
Description
#1 pingid
number
?
/ping decline #
Decline a ping

Argument
Type
Required
Description
#1 pingid
number
?
/service request #
Send a ping to certain jobs

Argument
Type
Required
Description
#1 service (taxi|ems|tow)
string
?
/playerinfo #
See player reporting info

Argument
Type
Required
Description
#1 player
source (number)
?
/911 #
Send a message to cops/ems

Argument
Type
Required
Description
#1 message
string
?
/911r #
Reply to a 911 message

Argument
Type
Required
Description
#1 id
number
?
#2 message
string
?
/walktype #
Change your walktype

Argument
Type
Required
Description
#1 walktype
string
?
/destroyweapon #
Destroy the weapon in your hand

Argument
Type
Required
Description
/dropweapon #
Drop the weapon in your hand

Argument
Type
Required
Description
/weaponinfo #
See info of the weapon in your hand

Argument
Type
Required
Description
/phone (p) #
Open phone GUI

Argument
Type
Required
Description
/phonenumber (pn) #
Emit chat msg with phone number to nearby players

Argument
Type
Required
Description
/sit (s) #
Use basic sit animation

Argument
Type
Required
Description
/me (m) #
Emit roleplay text on playermodel

Argument
Type
Required
Description
#1 message
string
?
/roll (dice) #
Roll a dice

Argument
Type
Required
Description
#1 startnumber
number
?
#2 endnumber
number
?
/clear (104) #
Clear nearest service blip

Argument
Type
Required
Description
/emote (e) #
Do an emote

Argument
Type
Required
Description
#1 anim
string
?
/money #
Display money prompt

Argument
Type
Required
Description
/quit #
Leave current employment

Argument
Type
Required
Description
/save #
Trigger character saving

Argument
Type
Required
Description
vehicle
/door (d) #
Open/Close vehicle door

Argument
Type
Required
Description
#1 open|o / close|c
?
#2 fl/fr/rl/rr/hood/trunk/back1/back2 | doorid
?
/glovebox (gb) #
Access small vehicle inventory

Argument
Type
Required
Description
/window (win) #
Toggle window of your seat

Argument
Type
Required
Description
chat
/ooc (looc) #
Global OOC chat message

Argument
Type
Required
Description
#1 message
string
?
dev
/dev tuner #
Force open tuner GUI

Argument
Type
Required
Description
/dev inv #
Force open a players inv

Argument
Type
Required
Description
#1 player
source (number)
?
/dev softlog #
Force open character GUI

Argument
Type
Required
Description
/dev pedrevive #
Revive nearby PED

Argument
Type
Required
Description
/dev pedcarry #
Carry nearby PED

Argument
Type
Required
Description
/dev addmoney #
Give your character money

Argument
Type
Required
Description
#1 amount
number
?
/dev pdduty #
Force set PD duty (character needs PD level)

Argument
Type
Required
Description
/dev setinfractions #
Force update character license infractions

Argument
Type
Required
Description
#1 player
source (number)
?
#2 license
?
#3 number
?
/dev debug #
Misc GUI elements for DEV

Argument
Type
Required
Description
/dev insdbg #
Instance GUI elements for DEV

Argument
Type
Required
Description
/dev mdt #
Force open MDT gui

Argument
Type
Required
Description
/dev revive #
EMS revive yourself

Argument
Type
Required
Description
/dev xyz #
Print XYZ details in console

Argument
Type
Required
Description
/dev car #
Spawn a vehicle

Argument
Type
Required
Description
#1 model
?
/dev weapon #
Spawn a weapon

Argument
Type
Required
Description
#1 spawnname
?
/dev fix #
Repair current vehicle

Argument
Type
Required
Description
/dev giveitem #
Put items in inv

Argument
Type
Required
Description
#1 itemname
?
#2 amount
number
?
/dev kill #
Force kill a player

Argument
Type
Required
Description
#1 player
source (number)
?
ems
/airlift #
Respawn after timer ends

Argument
Type
Required
Description
/ems inspect #
Inspect player for damage

Argument
Type
Required
Description
#1 player
source (number)
?
/ems item #
Get EMS item

Argument
Type
Required
Description
#1 bandage|b/morphine|m/painkillers|p
?
/ems frevive #
Force EMS revive (full health)

Argument
Type
Required
Description
#1 player
source (number)
?
/ems tow #
Mark a vehicle for tow

Argument
Type
Required
Description
#1 target|t/vehplate
?
/ems extra #
Add/Remove vehicle extra

Argument
Type
Required
Description
#1 all/extraid
?
/ems livery #
Set vehicle livery

Argument
Type
Required
Description
#1 liveryid
?
/ems impound #
Delete vehicle

Argument
Type
Required
Description
/ems ped carry #
Carry nearby PED

Argument
Type
Required
Description
/ems ped revive #
Revive nearby PED

Argument
Type
Required
Description
/ems car #
Spawn vehicle from ems_cars table

Argument
Type
Required
Description
#1 vehicleid
?
/ems command level #
Set character EMS level

Argument
Type
Required
Description
#1 characterid
?
#2 level
?
/ems escort #
Escort player

Argument
Type
Required
Description
#1 player
source (number)
?
/ems vehicle #
Force player into vehicle they are looking at

Argument
Type
Required
Description
#1 player
source (number)
?
/ems revive #
Revive a player (partial health)

Argument
Type
Required
Description
#1 player
source (number)
?
pd
/rifle (ar) #
Get AR from PD vehicle

Argument
Type
Required
Description
/shotgun (sg) #
Get shotgun from PD vehicle

Argument
Type
Required
Description
/pd inspect #
Inspect player for injuries

Argument
Type
Required
Description
#1 player
source (number)
?
/shotgun (sg) #
Get shotgun from PD vehicle

Argument
Type
Required
Description
/pd item #
Get EMS item

Argument
Type
Required
Description
#1 bandage|b/morphine|m/painkillers|p
?
/pd fine #
Fine a player

Argument
Type
Required
Description
#1 player
source (number)
?
#2 amount
number
?
/pd mdt #
Open the MDT

Argument
Type
Required
Description
/pd gsr #
GSR test a player

Argument
Type
Required
Description
#1 player
source (number)
?
/pd tow #
Mark a vehicle for tow

Argument
Type
Required
Description
#1 target|t/vehplate
?
/pd ped carry #
Carry nearby PED

Argument
Type
Required
Description
/pd ped revive #
Revive nearby PED

Argument
Type
Required
Description
/pd radar #
Toggle PD speed radar HUD

Argument
Type
Required
Description
/pd emote ticket #
Perform ticket emote

Argument
Type
Required
Description
/pd cpic #
CPIC search player

Argument
Type
Required
Description
#1 player
source (number)
?
/pd search #
Search player

Argument
Type
Required
Description
#1 all/inventory/weapons/money/strip
?
#2 player
source (number)
?
/pd command givelicense #
Give player license

Argument
Type
Required
Description
#1 driver|drivers/weapon|weapons/pilot|pilots
?
#2 player
source (number)
?
/pd command duty #
Toggle player PD duty

Argument
Type
Required
Description
#1 player
source (number)
?
/pd command level #
Set player PD level

Argument
Type
Required
Description
#1 player
source (number)
?
#2 level
?
/pd license infraction #
Add infractions to license

Argument
Type
Required
Description
#1 player
source (number)
?
#2 driver/weapon/pilot
?
#3 amount
number
?
/pd license take #
Force view a players license

Argument
Type
Required
Description
#1 player
source (number)
?
#2 driver/weapon/pilot
?
/pd dispatch #
Toggle dispatch notifications

Argument
Type
Required
Description
/pd runplate #
Run a plate on the DMV database

Argument
Type
Required
Description
#1 plate
?
/pd revive #
Revive a player

Argument
Type
Required
Description
#1 player
source (number)
?
/pd softcuff (pd sc) #
Cuff a player (can walk)

Argument
Type
Required
Description
#1 player
source (number)
?
/pd cuff (pd c) #
Cuff a player (can NOT walk)

Argument
Type
Required
Description
#1 player
source (number)
?
/pd livery #
Change vehicle livery

Argument
Type
Required
Description
#1 liveryid
?
/pd extras #
List vehicle extras

Argument
Type
Required
Description
/pd extra #
Toggle a vehicle extra

Argument
Type
Required
Description
#1 all/extraid
?
/pd escort #
Escort a player

Argument
Type
Required
Description
#1 player
source (number)
?
/pd boot #
Disable a vehicle

Argument
Type
Required
Description
/pd unboot #
Re-enable a vehicle

Argument
Type
Required
Description
/pd putinveh #
Put a player in the vehicle they are looking at

Argument
Type
Required
Description
#1 player
source (number)
?
/pd car #
Spawn a police vehicle from pd_cars table

Argument
Type
Required
Description
#1 carid
?
/pd fix #
Repair current vehicle

Argument
Type
Required
Description
/pd impound #
Delete a vehicle (no fee)

Argument
Type
Required
Description
/pd impound2 #
Delete a vehilce (impound fee)

Argument
Type
Required
Description
/pd jail #
Send a player to jail

Argument
Type
Required
Description
#1 player
source (number)
?
#2 time (minutes)
?
admin
/ac #
Admin chat

Argument
Type
Required
Description
#1 message
string
?
/amenu (am) #
Admin menu

Argument
Type
Required
Description
#1 message
string
?
/admin freeze #
Freeze player

Argument
Type
Required
Description
#1 player
source (number)
?
/admin menu #
Admin menu

Argument
Type
Required
Description
/admin announce #
Announce a message in every players chat

Argument
Type
Required
Description
#1 message
string
?
/admin goto #
Teleport to player

Argument
Type
Required
Description
#1 player
source (number)
?
/admin bring #
Bring a player to you

Argument
Type
Required
Description
#1 player
source (number)
?
/kick #
Kick a player

Argument
Type
Required
Description
#1 player
source (number)
?
/ban #
Ban a player

Argument
Type
Required
Description
#1 message
string
?
#2 1d/2d/3d/4d/5d/6d/1w/2w/3w/1m/2m/perm
?
#3 reason
?
