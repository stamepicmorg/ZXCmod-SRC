# ZXCmod 1.27 free source 2008-2009.

For compile dll, need C++ 5 or 6 and Half-Life SDK 2.3  
Get current HL SDK [here](https://github.com/ValveSoftware/halflife). 

Visit [this](https://github.com/ZXCmod/ZXCmod-info) repo for read other information. 

#Changelog

###1.27 
 
- third attack on glock: gravity-shock bullets - (hl_wpn_glock.cpp)
- third attack on crowbar: teleportation - (crowbar.cpp)
- third attack on gauss: electro-ray - (gauss.cpp)
- new console command: mp_fragmonsters. Allow any values. Default 1 - (game.cpp, combat.cpp, game.h)
- fixed: client-side animation disabled. - (client.cpp & anothers with FEV_)
- secondary and reload attacks on mortars - (func_tank.cpp)
- optimized shotgun clusters - (shotgun.cpp)
- other little changes. 


###v1.26

- New weapons and changes.
- Sentry cant stuck in floor and walls - (rpg.cpp)
- Nuke has more direct damage *10 - (gauss.cpp)
- added new weapon: analog rocket-crowbar from RC - (crowbar.cpp)
- increase freeze from 1.25 to 2.25 - (hornetgun.cpp)
- allow to freeze anybody monsters - (combat.cpp)
- new function: ThirdAttack(). Any effect by pressed USE and ATTACK1 keys - (weapons.cpp, weapons.h)
- third attack n shotgun - (shotgun.cpp)
- third attack on satchels (invisibility) - (satchel.cpp, player.cpp)
- fixed crowbar animation                                                                             
- many other changes and release.


###v1.25

- New weapons: alt-nuke on egon (press reload) and freeze hornets (secondary attack on hornetgun).
- Rebalance of turrets. Sentry has 90% hp, turret - 100%. Low dmg.
- added "Headhot" message.


###v1.24

- New turret for Rocket launcher.
- small rebalance of turrets. Sentry has 100% hp, turret - 150%.
- turret and sentry are do not shot ally in mp_teamplay 1.
- some effects to players, machines and radiation. 


###v1.23
- NukeBomb explode fixed.
- Return autoset cl_lw 1 for best fire prediction (must some bugs with animation hand weapons (i work on it)).
- added new weapon: Flash grenates on Hornetgun. Small damage, big explode. Press reload for attack.
- Many other changes.


###v1.22
- GravGrenade lags fixed.
- Removed autoset some console commands and AUTOUPDATE.
- added new weapon: Uranium Bullet on 357(press RMB, if you have 6 bullets for magnum).


###v1.21
- changed damage by some weapons.
- added new weapon: GravGrenade (press R if you have 5 handgrenades).
- more effects by nuke bomb.
- more small changes.


###v1.17
- Fixed some bugs.
- Added new weapons: Crystal Heal (need 6 satchel, when press R key), Turrel (mouse 2 on RPG).
- Automatic parrent CMD by server to all clients: rate 25000, cl_lw 0, cl_updaterate 20, cl_cmd 20.
- Now fixed towers (as crossfire or doublecross).
- Gibs removed (for slow internet is great).