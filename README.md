# Beautiful-Doom
Beautiful Doom mod for GZDoom
Forum thread:
https://forum.zdoom.org/viewtopic.php?f=43&t=50004&sid=1c1118c879d5317400aba8752ec93aed

Repo is here!

Progress so far:

ADDED/IMPROVED
* A lot of stuff moved to Zscript
* Added Modern weaponset (BFGs currently inaccessible; both Chainsaws accessible; neither is in ZScript yet)
* Completely revamped blood graphics and physics (still a lot to be done yet)
* Bullet tracers now aim exactly at the same place where the hitscan bullet hits (thanks A_D_M_E_R_A_L for the suggestion) 
* Added SpriteShadow mod by Nash Muhandes
* The red 'overheat' tint of the Enhanced Chaingun now has several degrees of intensity that fade in and out gradually

FIXED
* Empty casings now spawn at the corret position when using Vanilla Pistol
* Fixed a missing frame in the Megasphere animation (thanks A_D_M_E_R_A_L)
* SSG now properly leaves shot decals instead of bullet decals
* Fixed an issue with a few guns where their firing sprite would light up fully instead of just the muzzle flash
* BFG orb's decorative 'lightning' will no longer be able to cause enemies to enter their pain state
* Removed unnecessary resource-intensive dynamic light on flame particles emitted by Lost Souls
* Restored BFG and Plasma Rifle kickback (thanks 3saster)
* Mancubus now properly calls A_BossDeath in 'plasma death' animation (thanks 3saster)
* Cyberdemon and Spider Mastermind now become non-solid after the correct amount of time in their death animations (thanks 3saster)
* All sprites in the mod are now correctly PNG which will eliminate conflicts with other wads that have custom palettes
* The statusbar kill count now caps at 9999 monsters instead of 999
* You can no longer fire 3 shots using dual Pistols if you only have 2 pistol ammo left
* When using Enhanced Chaingun alt. attack the first three bullets will no longer have 0 spread
* Icon of Sin's and Arch Vile summoning pentagrams will no longer fall down if they were created in the air

CHANGED
* Enhanced Chaingun can now fire 60 bullets before overheating instead of 50 (the warning red color comes up at 30 instead of 25)
