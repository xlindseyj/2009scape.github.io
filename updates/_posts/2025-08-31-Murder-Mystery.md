---
title: Murder Mystery
tags: news
layout: newspost
date: 2025-08-31 00:00:00 +0000
authors: Update Bot
excerpt: "Murder Mystery has been implemented, and many other changes in Gielinor..."
modtype: Bot
avatar: avatar8fa9.gif
---
Greetings Explorers

There have been some more changes in Gielinor:


- Fixed dagon'hai robe top and bottom missing prayer bonus<br />
Fixed saradomin bracers requiring 70 defense<br />
Added missing animations and sounds to blessed axe
- Fixed multihit spells incorrectly targeting familiars<br />
Fixed multihit spells incorrectly being limited to exclusively players or exclusively NPCs per cast
- Improved docker support<br />
Updated README for docker<br />
Cleaned up run and build bash scripts
- Fixed Digsite quest items that damage player on drop potentially dealing more damage than intended
- Removed inauthentic pets<br />
Removed option to obtain inauthentic TzRek-Jad pet
- Corrected attack, defence and death animations used by Waterfiends (idle attack animation is an authentic bug)
- Corrected list of god items
- Fixed the wall beasts in the lumbridge swamp dungeon
- Corrected all four DT bosses' despawn behaviors<br />
Added the missing music definition for the eastern half of Damis's cave<br />
Buffed Kamil's ice barrage attack to always hit two 5s<br />
Fixed a bug where Fareed's weapon unequip message would fire even if you did not have a weapon equipped
- Fixed Varrock essence miner bot<br />
<br />
Essence miner bot will now sell the acquired pure essence on the GE after it reaches at least 500
- Fixed PK news announcement breaking due to incorrect time processing
- Removed Grand Exchange privacy
- Implemented Gnome Barman dialogue
- <b>Implemented Murder Mystery</b>
- Fixed seers diary inferno adze bonus<br />
Fixed Thormac staff enchantment
- Changed most of the doors in Draynor Manor to not autowalk<br />
Implemented Draynor Manor chair NPCs (The ones that follow you around the house)
- Refactored Peer the Seer to better handle edge cases
- Fixed skull visually persisting on death
- Fixed first stage of Kalphite Queen not counting as a Kalphite slayer task
- Fixed spam casting Humidify consuming additional runes upon next cast
- Poison immune enemies are now immune to poison
- Removed usage of predetermined GE prices
- Improved battlestaff crafting
- Restricted random events inside KBD lair
- Changed Rogue's Purse herblore level requirement for cleaning from 8 to 3 and corrected XP awarded
- Added dialogue for gnome woman NPCs
- Seers' flax claim migrated to daily-seers-flax.json file<br />
Geoffrey in Seers' Village should give the correct amount of noted flax every day
- Added the "You do not have an axe to use." message for trying to chop a fruit tree without an axe
- Willow branches now properly regrow every 5 minutes
- Implemented semi-authentic Pious Pete random event
- Cats will no longer eat buckets<br />
Created a new command, ::petrate, for testing pet growth. ::petrate 0 is for pausing growth, 1 for 1x rate, and 2 uses the dev rate of growth (100x normal)<br />
Adult and overgrown cats will not grow hungry<br />
Removed several pets inauthentic to 2009<br />
Dogs no longer can turn into minotaurs<br />
Wolpertingers now double yield and experience from bushes
- Relicym's Balm is now created as a 3-dose rather than 4-dose potion<br />
All Barbarian Mixes can now be consumed with appropriate effects<br />
Corrected healing for caviar Barbarian Mixes
- Implemented farming spirit trees
- Fixed exception running ::completediaries
- Rewrote or refactored many interfaces, fixing many small bugs
- Corrected wizard projectiles and cast height
- Mithril dragons now only use their range attack when outside melee range
- Shooting stars now authentically award the discovery bonus XP in a single chunk (players with unclaimed XP prior to this change will still be able to claim it by mining the star)
- Farming improvements<br />
<br />
White Berry Bushes can now be protected<br />
Giant Ent properly increases Belladonna yield<br />
Mushrooms now disease properly<br />
Fixed various bush bugs<br />
Fruit Trees can now be chopped<br />
Fixed Scarecrow needing to grow to work<br />
Mushrooms should now visually update as each mushroom is picked from the patch<br />
Poison Ivy Bushes are now disease immune<br />
Poison Ivy Berries picked in the Champion's Guild Patch now finishes a Varrock Diary task
- The Ancient Cavern Canoe can now be used without the screen permanently fading to black until logging out
- Corrected Sumona's red dragon assignment<br />
Removed inauthentic aviansie assignments<br />
Fixed GWD beacon not being repairable<br />
Surprise exam is no longer optional<br />
Fixed level checks for All Fired Up beacon repair
- Fixed bug where the front door to Lord Handlemort's mansion in Ardougne remains locked even after obtaining totem
- Fixed dark beast dropping big bones<br />
Fixed too high health for leech
- Implemented Lletya Fruit Tree Patch<br />
Implemented Harmony Island Allotment Patch. Patch is still unreachable without The Great Brain Robbery
- Fixed Goblin Diplomacy quest log text
- Fixed charging orbs to check magic level instead of crafting
- Corrected Gunslik's shop items
- Corrected spider HP to 2 points
- Fixed maze reward chest amount<br />
Fixed ToG quest point requirements
- Crumble undead now more effective against zogres and skogres
- Fixed bots not picking up loot
- Fixed the bug where an NPC would show up on an item dialogue<br />
Refactored both item and double item dialogues
- Huge refactor improving the handling of players being given items, or situations where items are exchanged
- Reverted Lumbridge random event teleport fix due to trapping players in random event<br />
Spam clicking maze shrine now handled

