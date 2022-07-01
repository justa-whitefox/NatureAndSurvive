# GAME DESIGN DOCUMENT

> ## Nomenclatures and Initials
> * PC: Player Character
> * native: game npcs
> * flora: all kind of flower, trees etc.
> * fauna: all kind of non-npc, non-flora creatures, including passive, neutral and aggressive animals.
> * rarity: common, rare, extreme rare, unique.
> * project state: WIP = Work in Progress, Queue = on Queue list, Done = Finished, OnSearch = mechanic being searched

> ## game details
>
> >	### terrain
> >
> >	* 1 main continent, named: Azure Continent, with the botton covered with tropical forest, the botton and mid border rounded by beachs, the center point when reside the only
> >     big city is a grass plain surrounded by rainforest, and the top of the continent gradualy swifting between taiga to snowy mountains.
> >	* 1 small continent, named: Forbidden Continent, half of the continent is covered by taiga and the other half by snowy Mountains, with strong and fast creatures roaming 
> >     around the hole continent.
> >	* separated in chunks/tiles to improve performance
> >	* GameMap: 419^2km(20.5km X 20.5km), 1 small continent, 1 small island.
> >	* main continent: 126.31^2km || 10.88km X 11.61km, 1 main city, 4 villages,
> >	* small island: 6.46^2km || 2.36km X 2.74km, no citys, no villages,
> >	* Biomes: rainforest, tropical forest, taiga, mountains, snowy mountains, grass plains,
> >	* Danger Zones: based on how far they are of the city,
>		
> > ### buildings
> >
> >	* ruined citys dominated by flora, dangerous fauna roaming arround,
> >	* small villages spread across the continent,
> >	* 1 main bigger city in the center of the main continent, named: vermilion, the city of steel,
> >	* 2 villages citys-like spread across the main continent around the main city,
> >	* 2 villages house-tree like spread across the continent in the densest forests,
> > * 4 mines going in the mountains, source of ores for the main city.
>			
> > ### Humanoid Characters Characteristics
> >
> > * behaviors and reactions based on traits,
> > * NPC separated in Natives-Nature(align with nature) and Natives-Civilization(align with citys and concrete buildings),
> > * Traits:
> > 	* friendly		=
> > 	* smart			=
> > 	* adventurous   =
> > 	* curious		=
> > 	* tough			=
> > 	* shy		    =
> > 	* selfish	    =
> > 	* sneaky		=
> > 	* mean			=
> > 	* wild			=
> > 	* mischievous	=
> > 	* dangerous 	=
>			
> > ### Main Mechanics
> >
> >	* Player Creation
> >		* the PC can choose between 12 characters with differents traits,
> >		* the start point must be different to every character
> >
> >	* Save
> >		* auto-save
> >		* save before and after a load
> >		* save when exit to main menu or desktop
> >
> >	* GUI
> >		* no HUD, all interaction of the PC with the world must be done using an phisical object
> >		* the in-game menu(status, health, equipment, inventory, etc) will have a apparence of a book to increase immersion and realism
> > 	* the monitoring of health, stamina and time can be done using a watch in the character's wrist
> >		* player must be able to choose between run or fight against certain characters
> >
> >	* world caracteristcs
> >		* world and PC ilumination must be done using torch, oil lamps or any other way that fit in the medieval context
> >		* all world characters will be mute
> >		* punitive combat, 
> >		* permaDeath, with 1 respawn(cutscene of been rescued), easy mode with no limit to respawn gived as a choice in the beginning of the game
>	
> > ### storyline
> >
> > * you, just a normal human bean, chill in your home, are just resting in your restroom when a global catastrophe come down,
> > * you quickly search for shelter, when notice, the beatiful and dangerous radiative light tint your windows with a growing green,
> > * you turn on the TV and see in every chanel warning about a radiative disaster across the earth, 
> > * you get closer to the windown to hear more clearly the roar of the thunder, the scream of the wind, and the grumbles and growls of the storm,
> > 
> >	* -----!> susceptible to changes
> > * you run down your stairs to the basement to get somehow save from the catastrophic radiative rain outhere, and ...
> > * <!----
> > 
> > * you awake and the first thing you notice is the chaos in the basement, everything broken and torn around,
> > * you then decide to go up the stairs,	
> > * and then you notice: everything has changed, the only thing left of your house is the floor and a few wall but something feels wrong,
> > * you notice that ... the walls and floors look so old, just like centures has passed,
> > * the wall has moss growing in all it's surface, there is hude trees at the horizon and grass everywhere,
> > * you don't know what hapen, but you instictively know: there is no come back, you will have to find the answer by yourself!.
>
> > ### worldBuilding
> >
> >	* The has been destroyed by an Radiative catastrophe with unknown origin,
> >	* The catastrophe mutate the fauna to growth bigger, stronger, faster, smarter,
> >	* The flora grows bigger and spread all across the continent without anything to stop it,
> >	* Only a small number of humanoids survive and thoses, now live in hude walled citys or spreat across the continent,
>						
> > ### Environment
> >
> >	* Biomes:
> >		* rainforest 
> >			* highest species diversity, 27°C or 60°F, rainy and dry seasons, quite hight temperatures and heavy rainfall	 
> >			* dense forest with broadleaf trees, mosses, fern, palms and orchids.	 
> >			* trees growth very dense and block most of the ligh.	 
> >			* home for mostly tree animals(monkeys, snakes, frogs, lizards, small mammals).	 
> >			* soil useless for agriculture.	 
> >			* caracteristcs: low mist or fog all year, conifers. 
> >		
> >		* tropical forest
> >			*
> >
> >		* taiga
> >			*
> >
> >		* mountains
> >			*
> >			
> >		* grassy plains
> >			*
> >			
> >		
> >	* Flora:
> >		* Aspen Trees 
> >			* live for 40 ~ 150 years, 15 ~ 30m tall,	  
> >			* has brights yellowish ~ deep red leaves in the autumn, and white barks with black marks,	  
> >			* cold biomes, and regions as taiga.
> >			* common
> >					 
> >		* Pine Trees  
> >			* live for 100 ~ 1000 years, 30 ~ 50m tall,
> >			* has brownish ~ redish bark, with needle-like leaves that varies from 6 - 30cm long, with pine frutes that varies on color between greenish ~ brownish pended on, 
> >			* from more neutral temperatures to cold biomes like taiga
> >			* common					 
> >					  
> >		* Ebony Trees 
> >			* live for 60 ~ 200 years, reaches a height of 20 ~ 30m,
> >			* has thick bark wich varies in color between whitish brawn ~ dark brown, and a dense black hardwood.
> >			* native to warm and arid regions, apear also in tropical forests.
> >			* Rare
> >		
> >		* Oak Trees   
> >			*
> >			*
> >			*
> >			* common
> >					  
> >		* Cherry Trees
> >			* live for 30 ~ 40 years, usualy 10m tall with branchs 3.5 ~ 4.5m Wide,
> >			* has a dark brown bark with white ~ pinkish flower and leaves that only blossom in spring,
> >			* tropical climates with middle latitude.
> >			* Extreme Rare
> >					  
> >	* Fauna:
> >		* 	
>	
	
> ## RoadMap
>
> * Terrain
> 	* basic modeling and texturing main continent and island[Done]
> 	* modeling and texturing main continent and island details[WIP]
> 	* upgrade to URP[Done]
> 	* Skybox
>	* water
> 	* Day Night Cycle[OnSearch]
> 	* Seasons
>	* whether[OnSearch]
>	* Grass[OnSearch]
> 	* Trees[OnSearch]
>	* Chunk/Tile split
> 		
> * Player
> 	* player controller
> 	* player interaction
> 	* player reactions
> 	* player stat buffs and debuffs
> 		
> * UI
> 	* Main Menu/Title, book cover
>	* New Save/button, book Cover --> page 1
>			 * select a character/selection screen, page 1
>
> 	* Continue/button, book cover --> page 2
>			 * select save/button, page 2
>
> 	* Configurations/button, book cover --> page 3
>			 * Master Volume/slider, page 3
>			 * BGM Volume/slider, page 3
>			 * VFX Volume/slider, page 3
>			 * Screen Resolution/dropdown menu, page 3
> 			 * input manager/button page 3 --> page 4
>				* controller menu/controller sets, page 4
>
>	* Exit/button, book cover --> exit game
>
> 	* In-Game Menu
>		* character sheets/info display, page 5
>		* skills/info display, page 6
>		* inventory/interactive info display, page 7
>			* the interaction with the equipment will be done with notes-like pop-up, like: equip or discart
>
>		* equipment/info display, page 8
>			* areas able to be equiped: head, neck, upper body, low body, feet, hand, wrist, fingers
>
>		* status/info display, page 9
>		* map/info display, page 10
>		* tips and advice/info display, page 11
>		* option/title, page 12
>			* configurations/button, page 12 --> page 3
>			* Achievements/button, page 12 --> page 13
>			* Main menu/button, page 12 --> Main menu/book cover
>			* Exit/button, page 12 --> exit game
>		* achievements/title
>			* undefined
> 		
> * Environment
> 	* Dynamic Chopable trees[OnSearch]
> 	* bushes
> 	* stones
> 	* ores
> 	* mushrooms
>
> * Buildings
>	* city(base area, wall)
>	* villages(base area, fence)
>	* houses
>	* commercial buildings(shopping, etc)
>	* work buildings(forges, etc)
>	* mines
> 		
> * Objects
> 	* refined ores
> 	* armours
> 	* tools
> 	* weapons
> 	* itens
> 		
> * characters
> 	* 12 Playable Characters
> 	* Natives
> 	* Unique Characters
> 	* Fauna
> 		
> * mechanics
> 	* smith
> 	* craft
> 	* Sneeak
> 	* self-defence
> 	* medicine
> 	* mine
> 	* chop
> 	* hunt(with bow)
> 		
> 		
> * animation
> 	* walk (fauna, natives, PC)
> 	* run (fauna, natives, PC)
> 	* trot (fauna)
> 	* jump (fauna, natives, PC)
> 	* chop (PC)
> 	* interact (PC)
> 	* attack (fauna, aggressive flora, natives, PC)
> 	* swim (fauna, natives, PC)
> 	* defend (fauna, natives, PC)
> 		
> * IA
> 	* natives IA
> 	* fauna IA
>
> * Achievements and trophies
> 	* Undefined
> 	
> * Optimization
> 	* batch materials
> 	* clean unused edge, vertices and overlaping faces on models
> 		