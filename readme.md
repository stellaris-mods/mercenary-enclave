# Mercenary Enclave

# Todo / Ideas
- Perhaps make the AI use the enclave now that operations cost energy. For example during forced truce periods where they cant attack someone they want to attack, or if they simply have too much energy laying around, and a negative opinion of someone, just launch a mining station raid randomly. Can't be too often though, or it will get annoying.
- Add +trust when you order an operation?
- MISSION TYPE: Guard Solar System (or Guard Colony), where the mercenaries will guard a system/colony from hostile fleets/invasions. This should probably cost influence per month, and not be usable while you're in an active conflict.
- Add on monthly pulse (while operation is active) that increases operation detect chance?
- AI Rebellion can colonize planets that we should be able to liberate
- ED and Swarm annihilate planets completely, I think? This means we never need to "liberate" them.
- Make sure the enclave can spawn their operations fleet if the enclave HQ is inside the borders of an empire that has given them access, AND they are the target.
- Make a copy of unrest.4235 and run that on the target if a planet liberation attempt fails? We would have to make a copy, because the vanilla event uses FROM/FROMFROM in the localisation strings
- Probably want to ignore systems/planets with `has_any_megastructure = yes` for various operation types
- Military Military Ships Raid target selection probably needs tweaking
- What are the `shroud` and `shroud_spirits` country types? Should they be valid targets for any operations?
- MISSION TYPE: Assist Fleet/Admiral, where the Mercenary Enclave will rush in to assist you in combat for the next 5-10-20-50 or whatever years (cheaper per year, if the contract is longer). Perhaps tie it to a specific Admiral, and if that admiral dies somehow open a window to let the player select the next admiral the ME should follow
- During a Liberation mission, if the target planet suddenly is NOT a valid liberation target, either find a new target, or abort, depending on how far along we are

# Steam description

[//]: # (start)
Steam description transliterated from `steam.bbcode` by [our release script](https://raw.githubusercontent.com/stellaris-mods/scripts/master/stlrel).

## **Adds a new type of Enclave to new games; the Mercenary Enclave\!**
Works with existing savegames, spawns a new random solar system for the Enclave\.
100% chance of 1x spawns in new games\.
Compatible with all addons\.
Works in multiplayer\.
AI does not use the Enclave services (AI doesn't use any enclave)\.

I have marked the addon as requiring the Leviathans DLC because Paradox fanboys complain in the comments section\.

_Mercenary Operations fleets, once they reach the solar system where their primary target is, turn hostile towards everyone\. Please do not attempt to follow them into combat, or use them as "allies" in wars\. You can do that, of course, just stay away from the fleet\._

## Beta
There's a few features I can add, but someone needs to tell me if they want them or not:

* Civilian Military Ships Raid \- kill 2\-4 science/construction vessels, usable against crisis as well
* Enclave respawns after 5\-10 years if destroyed
* Military Station System Raid, clears all military stations from selected solar system
* Guard System, the enclave parks a military fleet in your preferred controlled solar system, attacking any hostile fleets that enter
* Repair Fleet, send a rapid response construction crew to any of your fleets to repair them
* NEW ADDON: Assassination\-type Enclave, will never be in this mod\. I will maybe make this in a new mod\.
* NEW ADDON: Scrapyard Enclave, where you can sell/buy ships\. Will never be in this mod\. I will maybe make this in a new mod\.
* YOUR IDEA HERE


Does the AI Revolt empire, Swarm, or ED colonize planets? Should they be valid targets for the "liberate planet" option? Why can noone answer this in the comments?

Bug\-wise, there are probably quite a few\. I never play multiplayer, so I need some help testing that\. I rarely, like once per 3\-4 months, play a few years of singleplayer Stellaris, so I need help testing that as well\.

## Tuning/adjusting
We probably need to tune/adjust the costs of some operations\. I really need some input here\. I have no idea what things should cost\. Tell me what YOU think in the comments, please\.

## Services
Whiteout Enterprises offers a wide range of services, depending on several factors, including trust towards your empire and the target you select\.

1. Spaceport Raid
1. Military Ships Raid
1. Civilian Raid
1. Liberate Planet
1. Clear Space



Not all operations can be conducted against all empires\. Swarm/ED/Fallen are also valid targets, but not for all types\.

## 1\. Spaceport Raid
Base cost: 5000 minerals
Success chance: 80%
Detection risk: 20%
The enclave selects a spaceport in the target empire, and sends a dedicated operations fleet to destroy it\.

## 2\. Military Ships Raid
Base cost: 10000 minerals
Success chance: 80%
Detection risk: 25%
The enclave selects a valid military fleet target in the target empire, and attempts to kill it and all ships within\. Will track ships that are split from the original fleet, and even if the fleet is entirely gone it will still hunt down the ships that were part of the original fleet\.

## 3\. Civilian Raid
Base cost: 2500
Success chance: 95%
Detection risk: 25%
Targets 5\-12 mining, research, observation, and frontier stations in the target empire and sends a dedicated operations squad to eliminate them\.

## 4\. Liberate Planet
Base cost: 15000
Success chance: 75%
Detection risk: 35%
Finds a colonized planet in the target empire, sends a fleet to bombard it and then invades it\. Once the mercenaries have control of the planet, the population will be "convinced" to adopt the same ethos as you, and a new puppet government will be created, installed, and the planet instantly liberated from what we can only presume is the tyranny of their overlords\.

## 5\. Clear Space
Cost: 300 \- 3000
Success chance: 95%
This operation is only available once you reach a certain trust level with the enclave\. They will dispatch a fleet to clear out space monsters around inside your territories, allowing you to focus your time and energy on other tasks\.

## Target Selection
_Whiteout Enterprises will never reveal their target selection criteria\._

## Success Chance
_We've tried to interpret this number many times, but we simply can not find a consistent behavior\. It seems that the higher the chance is, if their initial fleet is destroyed, there is a higher chance that they will send another one\.
But we don't know\._

Note that different empire target types can impact the success chance of an operation\.

## Detection risk
Several factors will modify the chance that you are revealed to the target empire as to who ordered the operation\. The problem is that sometimes during an operation, the target will capture and interrogate the mercenary operatives\. This is simply an estimate of the chance that this will happen\.
Empires that detect an operation against them will be really angry with you, depending on the type of operation and their ethos\.
Players will get a notification telling them who ordered the operation, if they manage to detect it\.

## Depositing minerals
The mercenary enclave can act as a sort of bank for you, where you can deposit minerals in 2500 chunks\. Doing so will increase their trust of you by 5, but they will collect an administrative fee of 5% per year\.
If the enclave is destroyed, all your deposits are gone\.
When you order an operation from the enclave, they will first use up any deposit before they access your empires treasury\.

## Allowing border access
Allowing border access to the enclave will increase their trust of you every year\. They will also construct a military station complex inside your borders that they may use to dispatch operation fleets\.

If you revoke the access, and there is a station complex inside your borders, the enclave will not care\. The complex will remain, and if you want it gone, you will have to attack it\.

## Contacting me
Feel free to start a new discussion topics on any of my addons, or post in the comment section below\. If you want to talk to me directly, I hang out on the [NSC Discord server](https://discord\.gg/K9jUfws)\. Type _@folk_ in the \#modding\-discussion channel and I will see your message\.


[//]: # (stop)
