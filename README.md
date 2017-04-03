#  CustomArkLootDrops
----

_Improved and re-balanced default world beacons for hosted [ARK: Survival Evolved](https://www.youtube.com/survivetheark) servers._  

* This code is designed for PC servers. Sorry XBOX and PS4 players, it's nothing personal, I just only play PC.
* Designed with _Balance_ in mind. I consider feedback when updating this code. If you noticed unbalanced things let me know.

## The Goal  
The goal with this drop rework is to improve the World Sky Beacons crates in ARK: Survival Evolved and focus on balancing for what would really make sense while making sure they are not too overpowered. The Sky Beacons should be more exciting to hunt for and unexpected finds will keep players coming back.

### How are these new beacons different?  
* The Sky Beacons here are updated and balanced with every patch and include a much more filled out table of items. Nearly every standard item is in them, the odds chart is rather large and I didn't find the time to update it into a user friendly viewing format, but you'll notice they much more varying, and even surprising sometimes. 
* There are super rare drops in some of them that may be something along the lines of a super high quality pike or weapon appropriate to the beacon level, and these special items are at a rarity of .003% odds or so, thus probably won't be found. 
* The Scorched Earth version has been further reworked to update the crates based on scorched earth unique items and dinos and the Deep _Sand_ crates have been reworked to remove unusable items.
* In general, items are grouped to a beacon color near the item's Engram Level.  
* Explosives are in small quantities except in one super rare case.  
* Items with Quality Ratings (Weapons, Armor, Saddles) drop individual pieces or patterns and are scaled up slightly in Double Crates (they have rings on them). Finding extremely high quality pieces is very rare on a server 4 difficulty. This rarity scales up or down along with game server difficulty as normal.

Support  
----
*If you've found this code useful, please consider donating for my hours or helping with the updates to help keep this project alive. It's more than just a quick re-code, its a re-balance as well. Hours of my life do go into it and its been a fun ride so far, but I won't always have time as I have to make ends meet.*

* [PayPal](https://www.paypal.me/mattearly/)  
* Bitcoin: 1Nwi1GBJtsuo1WQJqK83Ckr5NDJ3zwi5mM  


ToDo  
----

1. Analyze new patch 255  
  * New Dino: Electrophorus! - nothing to do
  * New Dino: Microraptor!  - add egg
  * New Dino: Ammonite! - nothing to do
  * New Dino: Thylacoleo! - add saddle
  * New Structure: Tek Forcefield - Tek building set wont be in sky crates for now check back later
  * New Structures: Tek Tileset & Tek Doors - Tek building set wont be in sky crates for now check back later
  * Rocket Launcher & C4 rebalance: C4 now does approximately 70% more damage to Structures than Rockets. Rocket Launcher can no longer have Item Stats (though its base Damage has been increased 20% to compensate). Rocket Turrets now take a slight amount of damage when they fire, and can not fire under 5% HP.  - leaving the code as it is, rocket launchers still drop in red but are no longer effected by durability
2. Change pillbox drops to logout/spawn point drops (add 1 bed)  - added to stone pillboxes
3. Version Specific
	1. Both Standard and Scorched Earth
		- [ ] Add Archaeopteryx Egg - spawn code: PrimalItemConsumable_Egg_Archa_C
    	- [ ] Add Therizinosaurus Egg - spawn code: waiting on wiki to update with spawn code
	    - [ ] Add Sweet Vegetable Cake - spawn code: PrimalItemConsumable_SweetVeggieCake_C
	    - [ ] Add Bio Toxin - spawn code: waiting on wiki to update with spawn code
	    - [ ] Add Megalosaurus Egg - spawn code: PrimalItemConsumable_Egg_Megalosaurus_C
	    - [ ] Add Tapejara Egg - spawn code: PrimalItemConsumable_Egg_Tapejara_C
	    - [ ] Add Moschops Egg - spawn code: PrimalItemConsumable_Egg_Moschops_C
	    - [ ] Add Beer Jar - spawn code: PrimalItemConsumable_BeerJar_C
	   	- [ ] Add New Dino Items: Ovis Aries!
		- [ ] Add New Dino Items: Purlovia!
		- [ ] Add Scissors - blue
		- [ ] Add lvl 50 Thylacoleo Saddle - PrimalItemArmor_ThylacoSaddle_C
	2. Standard Only
		- [ ] Add Pachyrhino Egg - spawn code: PrimalItemConsumable_Egg_Pachyrhino_C
		- [ ] Add Kaprosuchus Egg - spawn code: PrimalItemConsumable_Egg_Kaprosuchus_C
		- [ ] Add Troodon Egg - spawn code: PrimalItemConsumable_Egg_Troodon_C
		- [ ] Add Pegomastax Egg - spawn code: PrimalItemConsumable_Egg_Pegomastax_C
		- [ ] Add Microraptor Egg - PrimalItemConsumable_Egg_Microraptor_C
		- [ ] Add lvl 95 Pheromone Dart - PrimalItemAmmo_AggroTranqDart_C



You are welcome to Edit the code and even make your own versions
----
To do this, Fork or Download then Edit the code for the beacons. After editing, run the **compile_code** powershell script (most versions of Windows can do this) to turn it into a new FULL_DEPLOY_CODE file. If you think your changes benefit this overall code, create a merge request. 

To learn more about editing beacons, Google is your best friend. There is a lot of useful information out there. If you look at the broken down, syntax-ed code on my Github, you'll see the patterns.
