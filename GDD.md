# GAME DESIGN DOCUMENT
---------------------------------------------------------------------------------------------------

> ## Nomenclatures and Initials
> -------------------------------------------------------------------------------------------------
>
> * PC: Playable Character
> * native: game npcs
> * flora: all kind of flower, trees etc.
> * fauna: all kind of non-npc, non-flora creatures, including passive, neutral and aggressive animals.
> * rarity: common, rare, extreme rare, unique.
> * project state: WIP = Work in Progress, Queue = on Queue list, Done = Finished, OnSearch = mechanic being searched

> ## game details
> -------------------------------------------------------------------------------------------------
>
> >	### terrain
> >
> >	* 1 main continent, named: Azure Continent, with the botton covered with tropical forest, the botton and mid border rounded by beachs, the center point is when reside the only
> >     big city is a grass plain surrounded by rainforest, and the top of the continent gradualy swifting between taiga to snowy mountains.
> >	* 1 Island, named: Forbidden Island, half of the continent is covered by taiga and the other half by snowy Mountains, with strong and fast creatures roaming 
> >     around the hole continent.
> >	* separated in chunks/tiles to improve performance
> >	* GameMap: 419^2km(20.5km X 20.5km), 1 small continent, 1 small island.
> >	* main continent: 126.31^2km || 10.88km X 11.61km, 1 main city, 2 villages and 2 underground villages,
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
> >	* 2 UnderGround villages accessed by the mines, with a cave system underground the main continent,
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
> >		* the start and backstory must be different to every character
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
> >			* Taiga and rainForest.
> >			* common
> >					 
> >		* Pine Trees  
> >			* live for 100 ~ 1000 years, 30 ~ 50m tall,
> >			* has brownish ~ redish bark, with needle-like leaves that varies from 6 - 30cm long, with pine frutes that varies on color between greenish ~ brownish pended on, 
> >			* Taiga, rainforest and tropical forest
> >			* common					 
> >					  
> >		* Ebony Trees 
> >			* live for 60 ~ 200 years, reaches a height of 20 ~ 30m,
> >			* has thick bark wich varies in color between whitish brawn ~ dark brown, and a dense black hardwood.
> >			* tropical forest.
> >			* Rare
> >		
> >		* Oak Trees   
> >			*
> >			*
> >			* rainForest and tropical forest
> >			* common
> >
> >		* Banana Trees
> >			*
> >			*
> >			* beach
> >			* common
> >					  
> >		* Cherry Trees
> >			* live for 30 ~ 40 years, usualy 10m tall with branchs 3.5 ~ 4.5m Wide,
> >			* has a dark brown bark with white ~ pinkish flower and leaves that only blossom in spring,
> >			* tropical forest.
> >			* Extreme Rare
> >					  
> >	* Fauna:
> >		* 	
>	
	
> ## RoadMap
> -------------------------------------------------------------------------------------------------
>
> * Terrain
> 	* basic modeling and texturing main continent and island[Done]
> 	* upgrade to URP[Done]
> 	* Skybox[WIP]
>	* water[OnSearch]
> 	* Day Night Cycle[OnSearch]
> 	* Seasons
>	* whether[OnSearch]
>	* Chunk/Tile split
> 	* detailing land models in each chunk/tile[WIP]
>
> * Environment
>	* Grass[OnSearch]
> 	* Trees[OnSearch]
> 	* bushes
> 	* stones
> 	* ores
> 	* mushrooms
>	* Cave System
>
> * Buildings
>	* city(base area, wall)
>	* villages(base area, fence)
>	* underground villages
>	* houses
>	* commercial buildings(shopping, etc)
>	* work buildings(forges, etc)
>	* mines
> 		
> * Player
> 	* player controller
> 	* player interaction
> 	* player reactions, HUD effects
> 	* player stat buffs and debuffs
> 		
> * User Interface
> 	* Book Cover/
>		> Main Menu/Title
>		> New Game/Button --> page 1
>		> Continue/Button --> page 2
>		> Configurations/Button --> page 3
>		> Exit/Button --> Exit Game
>
>	* Page 1
>		> Select character/Selection Screen
>		> Select Difficult/Selection Buttons
>			* cannot be changed later
>			* normal mode: how the game was created to be, you only have 1 live, save deleted after game over 
>			* easy mode: you can respawn infinitely
>
>	* page 2
>		> Continue/TItle
>		> Select Save/Selection Menu
>
>	* page 3
>		> Configurations/Title
>		> Master Volume/Slider
>		> BGM Volume/Slider 
>		> VFX Volume/Slider 
>		> Screen Resolution/Dropdown Menu 
>		> Input Manager/Button --> Page 4
>
> 	* page 4
>		> Controllers/title
>		> Move Forward/Dropdown
>		> Move Backward/Dropdown
>		> Move Rightward/Dropdown
>		> Move Leftward/Dropdown
>		> Jump/Dropdown
>		> ETC to complete
>
>	* page 5
>		> Character Sheets/Title
>		> Name/Info Display
>		> Age/Info Display
>		> Gender/Info Display
>		> Weight/Info Display
>		> Height/Info Display
>		> Trait/Info Display
>
>	* page 6
>		> Skills/Title
>		> Athletics/Info Display
>		> Dexterity/Info Display
>		> Medicine/Info Display
>		> Forge/Info Display
>		> HandCraft/Info Display
>		> Sneak/Info Display
>		> Self-Defence/Info Display
>		> Cook/Info Display
>		> Mine/Info Display
>		> LumberJack/Info Display
>		> Hunt/Info Display
>
> 	* page 7
>		> Inventory/Title
>		> Pocket/SubTitle and Weight limit of pocket
>		> |_Nature&Survive__  / Inventory space ocuped by book
>		> |_________________  / Free Inventory Space
>		> |_________________  / The Pocket inventory has 6 slots
>		> |_________________
>		> |_________________
>		> |_________________
>		> BackPack/SubTitle and Weight limit of backpack
>		> |_________________  / Free Inventory space
>		> |_________________  / The Backpack Inventory has at least 10 slots 
>		> |_________________  / The slots only end when the weight limit is reached
>		> |_________________
>
>	* page 8
>		> Equipment/Title
>		> |___Eyes_Slot__  	   (**)		> |__Head_Slot__
>		> |___Neck_Slot__		|
>		> |Backpack_Slot_	   /|\		> |__Torso_Slot_
>							  / | \
>		> |__Wrist_Slot__	 /  |  \	> |__belt_Slot__
>		> |_Finger_Slot__	/   |   \ 	> |__Hand_Slot__
>							   / \
>							  /   \		> |__Legs_Slot__
>		> |__Feet_Slot___  __/     \__
>		> Statistics/SubTitle
>		> Weight/Info Display			> Cut Resistence/Info Display
>		> Cold Resistence/Info Display	> Blunt Resistence/Info Display
>
> 	* page 9
>		> Status/Title
>		> Hidratation/Info Display 		> Head/Info Display
>		> Hunger/Info Display			> Sight/Info Display
>		> Physic Cond./Info Display		> hearing/Info Display
>		> Rest/Info Display 			> Torso/Info Display
>		> Health/Info Display 			> Right Arm/Info Display
>										> Left Arm/Info Display
>										> Right Leg/Info Display
>										> Left Leg/Info Display
>
>	* page 10
>		> Map/Title
>		> Map/Image
>		> Symbols/Descripiton Display
>	
>	* page 11
>		> Tips and advice/Title
>		> WASD to Move/Tutorial Display
>		> [___] to Jump/Tutorial Display
>		> Shift to Run/Tutorial Display
>		> Ctrl to sneak/Tutorial Display
>		> <- () -> to Look/Tutorial Display
>		> RMB to Interact/Tutorial Display
>		> LMB to Attack/Tutorial Display
>		> TAB to access In-Game Menu/Tutorial Display
>		> hide if you hear steps in the woods/Tips Display
>		> don't go to far in the forests/Tips Display
>
>	* page 12
>		> Option/Title
>		> Achievements/Button --> page 13
>		> Configurations/Button --> page 3
>		> Main Menu/Button --> Book Cover
>		> Exit/Button --> Exit Game
>
>	* page 13
>		> Achievements/Title
>		> undefined/text with checkbox
> 		
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
> 	* Underground natives
> 	* Fauna
> 		
> * mechanics
> 	* smith
> 	* craft
> 	* Sneeak
> 	* self-defence
> 	* medicine
> 	* mining
> 	* choping
> 	* hunting(with bow)
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

> ## WorldBuilding
> -------------------------------------------------------------------------------------------------
>
> ### World Timeline
> 
>
> ### Characters Backstory
>
>
>