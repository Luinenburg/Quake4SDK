# Fishing By The Rocks
## Features
We've got so many features! Thing to do! Theres
1. Fishing
	1. Pull out the shotgun and shoot at anything with the alt-fire! You'll be given a fish!
2. 5 whole fish!
	1. Depending on what material you hit, you can get
		1. Ugly
			1. Found anywhere the others are not found
			2. Worth 1
		2. Dirty
			1. Found on dirt-like materials
			2. Worth 2
		3. Rocky
			1. Found on rock-like materials
			2. Worth 3
		4. Metallic
			1. Found on metal-like material
			2. Worth 4
		5. Fleshy
			1. Found on flesh-like material
			2. Worth 5
3. 3 types of quests!
	1. Obtain a randomly generated quest ranging in 3 difficulty levels!
		1. Easy
			1. Requires 4-12 ugly or dirty fish
		2. Medium
			1. Requires 6-14 dirty, rocky, or metallic fish
		3. Hard
			1. Requires 8-16 metallic or fleshy fish
4. 5 enhancements!
	1. More Fish
		1. Get double the fish while fishing!
		2. Costs 20
	2. More money
		1. Get double the money per quest!
		2. Costs 40
	3. Multi-fish
		1. Get more than 1 type of fish while fishing!
		2. Costs 60
	4. Easy Quests
		1. 2 less fish required in each quest!
		2. Costs 80
	5. God fisher
		1. Get 1 of every fish whenever you fish, regardless of material!
		2. Costs 100
5. Shop system!
	1. Every enhancement can be purchased at the prices shown above
	2. Money is made by submitting quests
# Commands
## Fish
- giveFish \<fishname> \<amount>
	- Gives the player the amount of fish of type given
	- valid fishname:
		- ugly
		- dirty
		- rocky
		- metallic
		- fleshy
- takeFish \<fishname \<amount>
	- Same as giveFish, but removes that amount of fish
	- valid fishname:
		- ugly
		- dirty
		- rocky
		- metallic
		- fleshy
- displayFish
	- Shows the amount of fish and money the player has
## Quests
- findQuest \<difficulty>
	- Gives the player a quest of provided difficulty
	- valid difficulty:
		- easy
		- medium
		- hard
- submitQuest
	- Submits the current quest the player has
- showQuest
	- Shows the player's current quest
## Enhancements
- showOwnedEnhancements
	- Provides a list of enhancements owned by the player
- showEquippedEnhancements
	- Provides a list of enhancements equipped by the player
- grantEnhancement \<enhancement>
	- gives the player an enhancement if they do not already own it
	- valid enhancement:
		- more_fish
		- more_money
		- multi_fish
		- easy_quests
		- god_fisher
- equipEnhancement \<enhancement>
	- Equips an owned enhancement to the first unequipped slot
	- valid enhancement:
		- more_fish
		- more_money
		- multi_fish
		- easy_quests
		- god_fisher
- unequipEnhancement \<number>
	- Unequips specified enhancement
## Shop
- showEnhancementCost
	- get a list of enhancements and their associated costs
- buyEnhancement \<enhancement>
	- Buys an enhancement
	- valid enhancement:
		- more_fish
		- more_money
		- multi_fish
		- easy_quests
		- god_fisher
# Installation
Unzip the contents of the latest release and drop it into the directory for your quake 4 install.
- If your quake4 install is not in the standard steam directory, the shortcut will not work.