[
	{
		"name": "Skutatoi",
		"replaces": "Bank",
		"cost": 120,
		"uniqueTo": "Imperium",
		"cityStrength": 5,
		"cityHealth": 35,
		"hurryCostModifier": 50,
		"requiredBuilding": "Market",
		"requiredTech": "Chivalry",
	},
	{
		"name": "Theodosian Library",
		"replaces": "Library",
		"uniqueTo": "Sapphire City",
		"hurryCostModifier": 25,
		"culture": 2,
		"uniques": ["[+1 Science] Per [1] Population in this city"],
		"requiredTech": "Writing"
	},
	{
		"name": "Pedrian Battle School",
		"replaces": "Colosseum" 
		"uniqueTo": "Pedras"
		"cost": 125
		"maintenance": 0,
		"happiness": 3,
		"hurryCostModifier": 25,
		"percentStatBonus": {"culture": 25},
		"requiredTech": "Construction"
	},
]
	[
	{
		"name": "Spectator",
		"outerColor": [255,255,255]
//		"innerColor": [255,255,255]
	},
	{
		"name": "Imperium",
		"leaderName": "Certanium",
		"adjective": ["Ukrainian"],
		"startBias": ["Coast","Plains"],
		"preferredVictoryType": "Domination",
		
		"startIntroPart1": ".",
		"startIntroPart2": ".",
		
		"declaringWar": "Your lands will soon be mine, prepare for war!",
		"attacked": "Have you declared war on us? This was a huge mistake on your part, prepare to be destroyed.",
		"defeated": "Imperium has fallen. But Imperiumism, lives in you.",
		"introduction": "Greetings, I am Certanium. Emperor of Imperium. Gaze in awe on the majesty that is our great civilization!",
		
		"neutralHello": "what do you need?",
		"hateHello": "you...",
		"tradeRequest": "accecpt this offer.",
		"outerColor": [189,69,72],
		"innerColor": [255,255,0],
		"uniqueName": "Imperiumism",
		"uniques": ["+[20]% combat bonus for units fighting in [Foreign Land]", "+15% Combat Strength for all units when attacking Cities", "[+[5]% [Production] from every [Monument]"],
		"cities": ["Imperium","Vinovia","Melta","Clausentium","Curia","Susasa","Clupea","Ad Flexium","Onuba","Sarius","Metium","Sileium","Quidium","Gidia","Cantium","Arpina","Poltam","Cantium","Aripina","Emessa","Etuggus","Sussus","Amogus","Kirovohrad","Chernivtsi","Khmelnytskyi","Rivne","Ivano-Frankivsk","michaelsenpai","cwiskun","adamchan","baka","toomany","Melito","Citius","uhhhhhh","Bellunim","Draconia","Portanium","SussyBaka"],
		},
		{
		"name": "Sapphire City",
		"leaderName": "Theodosis The Magnificent",
		"adjective": ["Sapphirian"],
		"startBias": ["Grassland","Plains"],
		"preferredVictoryType": "Scientific",
		
		"startIntroPart1": ".",
		"startIntroPart2": ".",
		"declaringWar": "The world will be more beautiful without you. Prepare for war.",
		"attacked": "I thought you were better!",
		"defeated": "I thought that you were better than them. It seems I was wrong.",
		"introduction": "Greetings. I am Theodosis I, Queen Mother of the Sapphire City, please, be kind.",
		"neutralHello": "greetings.",
		"hateHello": "say what you must. be on your way!",
		"tradeRequest": "Let's unite our nations through peace, trade, and cooperation!",
		"outerColor": [ 51,103,153],
		"innerColor": [248,223,97],
		"uniqueName": "Sapphirian Knowledge",
		"uniques": ["[+4 Science] from every [Great Barrier Reef]","[+4 Science] from every [Old Faithful]","[+4 Science] from every [El Dorado]","[+4 Science] from every [Fountain of Youth]","[+4 Science] from every [Grand Mesa]","[+4 Science] from every [Mount Fuji]","[+4 Science] from every [Krakatoa]","[+4 Science] from every [Rock of Gibraltar]","[+4 Science] from every [Cerro de Potosi]","[+4 Science] from every [Barringer Crater]", "[Great Scientist] is earned [50]% faster"],
		"cities": ["Sapphire City","Theodosiana","Sapphiriana","Quartz Town","Oxhey","Northwick","Redmoor","Oxhaven","Langthwaite","Readpool",
			"Market Southford","Kirington","Oxmere","Northhall","Whitepool","Hardon","Bridge","Merw","Balkh","Mosul",
			"Aydab","Bayt","Suhar","Taif","Hama","Tabuk","Sana'a","Shihr","Tripoli","Tunis","Kairouan","Algiers","Oran"]
	},
	{
		"name": "Pedras",
		"leaderName": "Pedrina",
		"adjective": ["Pedrian"],
		"startBias": ["Plains"],
		"preferredVictoryType": "Domination",
	
		"startIntroPart1": ".",
		"startIntroPart2": ".",
		"declaringWar": "Sorry, not sorry. your cities would just look better if they were purple.",
		"attacked": "Ha! I've been waiting for this one! turn it up!.",
		"defeated": "Wrong! You sithing monster! I hope you burn for this!",
		"introduction": "Spariuk Pedrina! I'm the Empress of Pedras, who might you be?",
		"neutralHello": "Spariuk!",
		"hateHello": "What do you need?!",
		"tradeRequest": "Thoughts?",
		"outerColor": [ 86, 26, 147],
		"innerColor": [103,103,103],
		"uniqueName": "Pedrian Culture and Battle Commands",
		"uniques": ["[+1 Culture] from every [Horses]", "[+1 Culture] from every [Iron]", "[+1 Culture] from every [Aluminum]", "[+1 Culture] from every [Coal]", "[+1 Culture] from every [Oil]", "[+1 Culture] from every [Uranium]", "+[1] Movement for all [non-air] units"],
		"cities": ["Pedras","Hetzwigg","Novgorod","Rostov","Yaroslavl","Yekaterinburg","Yakutsk","Vladivostok","Smolensk","Orenburg",
			"Krasnoyarsk","Khabarovsk","Bryansk","Tver","Novosibirsk","Magadan","Murmansk","Irkutsk","Chita","Samara",
			"Arkhangelsk","Chelyabinsk","Tobolsk","Vologda","Omsk","Astrakhan","Kursk","Saratov","Tula","Vladimir","Perm",
			"Voronezh","Pskov","Starayarussa","Kostoma","Nizhniy Novgorod","Suzdal","Magnitogorsk"]
	},

]
[
	{
		"name": "Imperial Guard",
		"unitType": "Melee",
		"replaces": "Musketman",
		"uniqueTo": "Imperium",
		"movement": 2,
		"strength": 35,
		"cost": 200,
		"requiredTech": "Banking",
		"upgradesTo": "Rifleman",
		"obsoleteTech": "Rifling",
		"uniques": ["+[25]% combat bonus in [Grassland]","+[25]% combat bonus in [Forest]","+[25]% combat bonus in [Plains]"],
		"attackSound": "shot"
	},
	{
		"name": "Royal Fleet",
		"unitType": "WaterMelee",
		"replaces": "Caravel",
		"uniqueTo": "Sapphire City",
		"movement": 4,
		"strength": 36,
		"cost": 120,
		"requiredTech": "Astronomy",
		"upgradesTo": "Ironclad",
		"obsoleteTech": "Combustion",
		"uniques": ["+[33]% Strength vs [City]","Double movement in coast"],
		"hurryCostModifier": 30
	},
	{
		"name": "Pedrina's Guard",
		"unitType": "Melee",
		"replaces": "Great War Infantry",
		"uniqueTo": "Pedras",
		"movement": 2,
		"strength": 50,
		"cost": 320,
		"requiredTech": "Archaeology",
		"upgradesTo": "Infantry",
		"obsoleteTech": "Plastics",
		"uniques": ["+[20]% Strength in [Foreign Land]"],
		"attackSound": "shot"
	},
]
