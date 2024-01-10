# SINCE 2023 ROCKSTAR DOESNT ALLOW REAL LIFE BRANDS, USE THIS PACK ON YOUR OWN RISK

# Addon guns for QBCore

This is a **FREE** release!



**Supplied Snippets**

- qb-core
- qb-weapons
- qb-smallresources
- qb-policejob
- qb-jewelery
- qb-ambulancejob

## Installation

- Put the `custom_weapons` into your `resources` folder.


## Drop first code in `qb-core/shared/items.lua`

```lua
	-- Custom Weapons
	['weapon_ak47'] 		 		 = {['name'] = 'weapon_ak47', 	 			  	['label'] = 'AK-47', 					['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_assaultrifle.png', 				['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A rapid-fire, magazine-fed automatic rifle designed for infantry use'},
	['weapon_de'] 					 = {['name'] = 'weapon_de', 			 	  	['label'] = 'Desert Eagle',			    ['weight'] = 8000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'deagle.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A .50 caliber firearm designed to be held with both hands'},
	['weapon_fnx45'] 				 = {['name'] = 'weapon_fnx45', 	 			  	['label'] = 'FN FNX-45', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'weapon_combat-pistol.png', 			['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A combat version small firearm designed to be held in one hand'},
	['weapon_glock17'] 				 = {['name'] = 'weapon_glock17', 			 	['label'] = 'PD Glock 17', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'glock-17.png', 						['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'PD GUN'},
	['weapon_m4'] 					 = {['name'] = 'weapon_m4', 	 			  	['label'] = 'PD M4A1', 					['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_carbinerifle.png',			 	['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A lightweight automatic rifle for the Police'},
	['weapon_m9'] 					 = {['name'] = 'weapon_m9', 				 	['label'] = 'Beretta M9A3', 			['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'm1911.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A M91'},
	['weapon_m70'] 					 = {['name'] = 'weapon_m70', 	 			  	['label'] = 'M70', 						['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'm70.png',  							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A rapid-fire, magazine-fed automatic rifle designed for infantry use'},
	['weapon_m1911'] 				 = {['name'] = 'weapon_m1911', 	 			  	['label'] = 'M1911', 					['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'browning.png',  						['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A hefty firearm designed to be held in one hand (or attempted)'},
	['weapon_uzi'] 					 = {['name'] = 'weapon_uzi', 			 	  	['label'] = 'UZI', 						['weight'] = 10000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',				['image'] = 'uzi.png', 								['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A handheld lightweight machine gun'},
	['weapon_mac10'] 				 = {['name'] = 'weapon_mac10', 			 	  	['label'] = 'MAC-10', 					['weight'] = 10000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',				['image'] = 'mac-10.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A handheld lightweight machine gun'},
	['weapon_mossberg'] 			 = {['name'] = 'weapon_mossberg', 			 	['label'] = 'Mossberg 500', 			['weight'] = 10000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_SHOTGUN',			['image'] = 'mossberg500.png',						['unique'] = true,	 	['useable'] = false,["created"] = nil,	['description'] = 'A sawn-off smoothbore gun for firing small shot at short range'},
	['weapon_remington'] 			 = {['name'] = 'weapon_remington', 		 	  	['label'] = 'Remington 870', 			['weight'] = 8000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SHOTGUN',			['image'] = 'remington.png', 						['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A pump-action smoothbore gun for firing small shot at short range'},
	['weapon_scarh'] 				 = {['name'] = 'weapon_scarh', 				 	['label'] = 'PD SCAR-H', 				['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'scar.png',								['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'An extremely versatile assault rifle for any combat situation'},
	['weapon_shiv'] 				 = {['name'] = 'weapon_shiv', 			 	  	['label'] = 'Shiv', 					['weight'] = 3000, 		['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'shiv.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'An instrument composed of a blade fixed into a handle, used for cutting or as a weapon'},
	['weapon_ar15'] 				 = {['name'] = 'weapon_ar15', 	 	 		 	['label'] = 'PD AR-15', 				['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'WEAPON_AR15.png', 						['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A lightweight automatic rifle for the Police'},
	['weapon_mk14'] 				 = {['name'] = 'weapon_mk14', 	 			  	['label'] = 'PD MK14', 					['weight'] = 23000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_SNIPER',			['image'] = 'mk14.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A very accurate single-fire rifle'},
	['weapon_huntingrifle'] 		 = {['name'] = 'weapon_huntingrifle', 	 	  	['label'] = 'Hunting Rifle', 			['weight'] = 23000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_SNIPER',			['image'] = 'huntingrifle.png', 					['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A very accurate Rifle for hunting'},
	['weapon_katana'] 				 = {['name'] = 'weapon_katana', 	 		  	['label'] = 'Katana', 					['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'katana.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A single-edged sword that is the longer of a pair worn by the Japanese samurai.'},
	['weapon_sledgehammer'] 				 = {['name'] = 'weapon_sledgehammer', 	 		  	['label'] = 'Sledge Hammer', 					['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'sledgehammer.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A Sledge Hammer to destroy peoples heads'},
	['weapon_mp9'] 			 = {['name'] = 'weapon_mp9', 		 	  	['label'] = 'MP9', 				['weight'] = 10000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',				['image'] = 'weapon_mp9.png', 		['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A handheld lightweight machine gun'},
	['weapon_m110'] 		 = {['name'] = 'weapon_m110', 	 	  	['label'] = 'M110', 			['weight'] = 23000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SNIPER',			['image'] = 'WEAPON_M110.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A very accurate single-fire rifle'},
	['weapon_hk416'] 		 = {['name'] = 'weapon_hk416', 	 	  	['label'] = 'HK-416', 			['weight'] = 13000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'WEAPON_HK416.png', 	['unique'] = true, 		['useable'] = false,["created"] = nil,["decay"] = 30.0,     	['description'] = 'A lightweight automatic rifle'},
	['weapon_ak74'] 		 		 = {['name'] = 'weapon_ak74', 	 			  	['label'] = 'AK-74', 					['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_ak74.png', 				        ['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A rapid-fire, magazine-fed automatic rifle designed for infantry use'},
	['weapon_aks74'] 		 		 = {['name'] = 'weapon_aks74', 	 			  	['label'] = 'AK-S74', 					['weight'] = 13000, 	['type'] = 'weapon', 	['ammotype'] = 'AMMO_RIFLE',			['image'] = 'weapon_aks74.png', 				    ['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'A rapid-fire, magazine-fed automatic rifle designed for infantry use'},
	['weapon_glock18c'] 			 = {['name'] = 'weapon_glock18c', 			 	['label'] = 'Glock 18C', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'glock-18c.png', 						['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'semi automatic pistol'},
	['weapon_glock22'] 			     = {['name'] = 'weapon_glock22', 			 	['label'] = 'Glock 22', 				['weight'] = 7000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_PISTOL',			['image'] = 'glock-22.png', 						['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'pistol'},
	['weapon_mp5'] 				 	 = {['name'] = 'weapon_mp5', 			 	  	['label'] = 'H&K MP5', 					['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = 'AMMO_SMG',				['image'] = 'MP5.png', 			                    ['unique'] = true, 		['useable'] = false,["created"] = nil, 	['description'] = 'A handheld lightweight machine gun'},
['weapon_colbaton'] 			 = {['name'] = 'weapon_colbaton', 		 	  	['label'] = 'PD Baton', 				['weight'] = 1000, 		['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'weapon_colbaton.png', ['unique'] = true, 		['useable'] = false,["created"] = nil, 	['description'] = 'A Pd Baton'},
    --knife
    ['WEAPON_URBANRBFKNIFE'] 		         = {['name'] = 'WEAPON_URBANRBFKNIFE', 	 	  	['label'] = 'Urban Masked Butterfly Knife', 			['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,			['image'] = 'WEAPON_URBANRBFKNIFE.png', 					['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Urban Masked Butterfly Knife'},
    ['WEAPON_STAINEDRBFKNIFE'] 				 = {['name'] = 'WEAPON_STAINEDRBFKNIFE', 	 		  	['label'] = 'Stained Butterfly Knife', 					['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_STAINEDRBFKNIFE.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Stained Butterfly Knife.'},
    ['WEAPON_SLAUGHTERBFKNIFE'] 			 = {['name'] = 'WEAPON_SLAUGHTERBFKNIFE', 	 		  	['label'] = 'Slaughter Butterfly Knife', 					['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_SLAUGHTERBFKNIFE.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Slaughter Butterfly Knife.'},
    ['WEAPON_SCORCHEDBFKNIFE'] 				 = {['name'] = 'WEAPON_SCORCHEDBFKNIFE', 	 		  	['label'] = 'Scorched Butterfly Knife', 					['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_SCORCHEDBFKNIFE.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Scorched Butterfly Knife.'}, 
    ['WEAPON_SAFARIBFKNIFE'] 				 = {['name'] = 'WEAPON_SAFARIBFKNIFE', 	 		  	['label'] = 'Safari Mesh Butterfly Knife', 					['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_SAFARIBFKNIFE.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Safari Mesh Butterfly Knife.'},
    ['WEAPON_KARAMBITKNIFE'] 				 = {['name'] = 'WEAPON_KARAMBITKNIFE', 	 		  	['label'] = 'Karamabit Knife', 					['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_KARAMBITKNIFE.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Karamabit Knife.'},
    ['WEAPON_HUNTSMANKNIFE'] 				 = {['name'] = 'WEAPON_HUNTSMANKNIFE', 	 		  	['label'] = 'Huntsman Knife', 					['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_HUNTSMANKNIFE.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Huntsman Knife.'},
    ['WEAPON_GUTKNIFE'] 				     = {['name'] = 'WEAPON_GUTKNIFE', 	 		  	['label'] = 'Gut Knife', 					['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_GUTKNIFE.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Gut Knife.'},
    ['WEAPON_FORESTBFKNIFE'] 				 = {['name'] = 'WEAPON_FORESTBFKNIFE', 	 		  	['label'] = 'Forest Butterfly Knife', 					['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_FORESTBFKNIFE.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Forest Butterfly Knife.'},
    ['WEAPON_PERFORATOR'] 				     = {['name'] = 'WEAPON_PERFORATOR', 	 		  	['label'] = 'The Perforator',					['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'PERFORATOR.png', 							['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'PERFORATOR.'},
    ['WEAPON_BLUEBFKNIFE'] 			        = {['name'] = 'WEAPON_BLUEBFKNIFE', 	 		  	['label'] = 'Blue Steel Butterfly Knife', 			['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_BLUEBFKNIFE', 						['unique'] = true, 		['useable'] = false,["created"] = nil,	        ['description'] = 'Blue Steel Butterfly Knife',},
    ['WEAPON_BFKNIFE'] 				        = {['name'] = 'WEAPON_BFKNIFE', 	 		  	    ['label'] = 'Vanilla Butterfly Knife', 				['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						        ['image'] = 'WEAPON_BFKNIFE', 	 						['unique'] = true, 		['useable'] = false,["created"] = nil,	['description'] = 'Vanilla Butterfly Knife',},
    ['WEAPON_CHBFKNIFE'] 			 = {['name'] = 'WEAPON_CHBFKNIFE', 	 		  	    ['label'] = 'Case Hardened Butterfly Knife', 		['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_CHBFKNIFE', 	 					['unique'] = true, 		['useable'] = false,["created"] = nil,	        ['description'] = 'Case Hardened Butterfly Knife',},
    ['WEAPON_CRIMSONBFKNIFE'] 		 = {['name'] = 'WEAPON_CRIMSONBFKNIFE', 	 		['label'] = 'Crimson Butterfly Knife', 				['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						['image'] = 'WEAPON_CRIMSONBFKNIFE', 					['unique'] = true, 		['useable'] = false,["created"] = nil,	        ['description'] = 'Crimson Butterfly Knife',},
    ['WEAPON_FADEBFKNIFE'] 			 = {['name'] = 'WEAPON_FADEBFKNIFE', 	 		  	['label'] = 'Fade Butterfly Knife', 				['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						    ['image'] = 'WEAPON_FADEBFKNIFE', 					['unique'] = true, 		['useable'] = false,["created"] = nil,	        ['description'] = 'Fade Butterfly Knife',},
    ['WEAPON_FLIPKNIFE'] 			 = {['name'] = 'WEAPON_FLIPKNIFE', 	 		        ['label'] = 'Flip Knife', 					        ['weight'] = 1000, 	['type'] = 'weapon', 	['ammotype'] = nil,						                    ['image'] = 'WEAPON_FLIPKNIFE', 	 ['unique'] = true, 		['useable'] = false,["created"] = nil,	    ['description'] = 'Flip Knife',},


```



## Drop the next code in `qb-core/shared/weapons.lua`

```lua
	[`weapon_ak47`] 		 = {['name'] = 'weapon_ak47', 	 	['label'] = 'AK-47', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_m70`] 		 = {['name'] = 'weapon_m70', 	 	['label'] = 'M70', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_de`] 			 = {['name'] = 'weapon_de', 		['label'] = 'Desert Eagle', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_fnx45`] 			 = {['name'] = 'weapon_fnx45', 		['label'] = 'FN FNX45', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_glock17`] 			 = {['name'] = 'weapon_glock17', 		['label'] = 'PD Glock 17', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_m4`] 		 = {['name'] = 'weapon_m4', 	 	['label'] = 'PD M4A1', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_m9`] 			 = {['name'] = 'weapon_m9', 		['label'] = 'Beretta M9A3', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_m1911`] 			 = {['name'] = 'weapon_m1911', 		['label'] = 'M1911', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_uzi`] 			 = {['name'] = 'weapon_uzi', 		['label'] = 'UZI', 			['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_mac10`] 			 = {['name'] = 'weapon_mac10', 		['label'] = 'MAC-10', 			['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_mossberg`] 		 = {['name'] = 'weapon_mossberg', 	['label'] = 'Mossberg 500', 		['ammotype'] = 'AMMO_SHOTGUN',	['damagereason'] = 'Devastated / Pulverized / Shotgunned'},
	[`weapon_remington`] 		 = {['name'] = 'weapon_remington', 	['label'] = 'Remington 870', 		['ammotype'] = 'AMMO_SHOTGUN',	['damagereason'] = 'Devastated / Pulverized / Shotgunned'},
	[`weapon_scarh`] 		 = {['name'] = 'weapon_scarh', 	['label'] = 'PD SCAR-H', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_shiv`] 				 = {['name'] = 'weapon_shiv', 			['label'] = 'Shiv', 				['ammotype'] = nil,	['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`weapon_katana`] 				 = {['name'] = 'weapon_katana', 			['label'] = 'Katana', 				['ammotype'] = nil,	['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`weapon_sledgehammer`] 				 = {['name'] = 'weapon_sledgehammer', 			['label'] = 'Sledge Hammer', 				['ammotype'] = nil,	['damagereason'] = 'Melee killed / Whacked / Executed / Beat down / Murdered / Battered'},
        [`weapon_ar15`] 		 = {['name'] = 'weapon_ar15', 	 	['label'] = 'PD AR-15', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_mk14`] 		 = {['name'] = 'weapon_mk14', 	 	['label'] = 'PD MK14', 				['ammotype'] = 'AMMO_SNIPER',	['damagereason'] = 'Ended / Sniped / Shot down / Floored'},
	[`weapon_huntingrifle`] 		 = {['name'] = 'weapon_huntingrifle', 	 	['label'] = 'Hunting Rifle', 				['ammotype'] = 'AMMO_SNIPER',	['damagereason'] = 'Ended / Sniped / Shot down / Floored'},
	[`weapon_mp9`] 			 = {['name'] = 'weapon_mp9', 		['label'] = 'MP9', 			['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_m110`] 		 = {['name'] = 'weapon_m110', 	 	['label'] = 'M110', 				['ammotype'] = 'AMMO_SNIPER',	['damagereason'] = 'Ended / Sniped / Shot down / Floored'},
	[`weapon_hk416`] 		 = {['name'] = 'weapon_hk416', 	 	['label'] = 'HK-416', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_ak74`] 		 = {['name'] = 'weapon_ak74', 	 	    ['label'] = 'AK-74', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_aks74`] 		 = {['name'] = 'weapon_aks74', 	 	    ['label'] = 'AK-S74', 				['ammotype'] = 'AMMO_RIFLE',	['damagereason'] = 'Ended / Rifled / Shot down / Floored'},
	[`weapon_glock22`] 		 = {['name'] = 'weapon_glock22', 		['label'] = 'Glock 22', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_glock18c`] 	 = {['name'] = 'weapon_glock18c', 		['label'] = 'Glock 18C', 			['ammotype'] = 'AMMO_PISTOL',	['damagereason'] = 'Pistoled / Blasted / Plugged / Bust a cap in'},
	[`weapon_mp5`] 			 = {['name'] = 'weapon_mp5', 		    ['label'] = 'H&K MP5', 				['ammotype'] = 'AMMO_SMG',		['damagereason'] = 'Riddled / Drilled / Finished / Submachine Gunned'},
	[`weapon_colbaton`] 	 = {['name'] = 'weapon_colbaton', 		['label'] = 'Baton', 				['ammotype'] = nil,	            ['damagereason'] = 'Beat'},
    ---knifes
	[`WEAPON_URBANRBFKNIFE`] 		         = {['name'] = 'WEAPON_URBANRBFKNIFE', 	 	  	['label'] = 'Urban Masked Butterfly Knife', 					['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_STAINEDRBFKNIFE`] 				 = {['name'] = 'WEAPON_STAINEDRBFKNIFE', 	 		  	['label'] = 'Stained Butterfly Knife', 					['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_SLAUGHTERBFKNIFE`] 			 = {['name'] = 'WEAPON_SLAUGHTERBFKNIFE', 	 		  	['label'] = 'Slaughter Butterfly Knife', 				['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_SCORCHEDBFKNIFE`] 				 = {['name'] = 'WEAPON_SCORCHEDBFKNIFE', 	 		  	['label'] = 'Scorched Butterfly Knife', 				['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_SAFARIBFKNIFE`] 				 = {['name'] = 'WEAPON_SAFARIBFKNIFE', 	 		  	['label'] = 'Safari Mesh Butterfly Knife', 					['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_KARAMBITKNIFE`] 				 = {['name'] = 'WEAPON_KARAMBITKNIFE', 	 		  	['label'] = 'Karamabit Knife', 								['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_HUNTSMANKNIFE`] 				 = {['name'] = 'WEAPON_HUNTSMANKNIFE', 	 		  	['label'] = 'Huntsman Knife', 								['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_GUTKNIFE`] 				     = {['name'] = 'WEAPON_GUTKNIFE', 	 		  	['label'] = 'Gut Knife', 										['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_FORESTBFKNIFE`] 				 = {['name'] = 'WEAPON_FORESTBFKNIFE', 	 		  	['label'] = 'Forest Butterfly Knife', 						['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_PERFORATOR`] 				     = {['name'] = 'WEAPON_PERFORATOR', 	 		  	['label'] = 'The Perforator',								['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_BLUEBFKNIFE`] 			        = {['name'] = 'WEAPON_BLUEBFKNIFE', 	 		  	['label'] = 'Blue Steel Butterfly Knife', 					['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_BFKNIFE`] 				        = {['name'] = 'WEAPON_BFKNIFE', 	 		  	    ['label'] = 'Vanilla Butterfly Knife', 						['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_CHBFKNIFE`] 			 = {['name'] = 'WEAPON_CHBFKNIFE', 	 		  	    ['label'] = 'Case Hardened Butterfly Knife', 						['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_CRIMSONBFKNIFE`] 		 = {['name'] = 'WEAPON_CRIMSONBFKNIFE', 	 		['label'] = 'Crimson Butterfly Knife', 								['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_FADEBFKNIFE`] 			 = {['name'] = 'WEAPON_FADEBFKNIFE', 	 		  	['label'] = 'Fade Butterfly Knife', 								['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},
	[`WEAPON_FLIPKNIFE`] 			 = {['name'] = 'WEAPON_FLIPKNIFE', 	 		        ['label'] = 'Flip Knife', 					        				['ammotype'] = nil,				['damagereason'] = 'Knifed / Stabbed / Eviscerated'},


```

## Drop the next code in `qb-weapons/config.lua`

```lua
    --Custom Weapons
    ['weapon_ak47'] 			     = 0.15,
    ['weapon_de'] 	                 = 0.15,
    ['weapon_fnx45'] 			     = 0.15,
    ['weapon_glock17'] 		         = 0.15,
    ['weapon_m4'] 			         = 0.15,
    ['weapon_hk416'] 			     = 0.15,
    ['weapon_mk14'] 			     = 0.15,
    ['weapon_m110'] 			     = 0.15,
    ['weapon_huntingrifle'] 	     = 0.20,
    ['weapon_ar15'] 			     = 0.15,
    ['weapon_m9'] 	                 = 0.15,
    ['weapon_m70'] 			         = 0.15,
    ['weapon_m1911'] 		         = 0.15,
    ['weapon_mac10'] 			     = 0.15,
    ['weapon_uzi'] 	                 = 0.15,
    ['weapon_mp9'] 	                 = 0.15,
    ['weapon_mossberg'] 		     = 0.15,
    ['weapon_remington'] 		     = 0.15,
    ['weapon_scarh'] 			     = 0.15,
    ['weapon_shiv'] 	             = 0.15,
    ['weapon_katana'] 	             = 0.15,
    ['weapon_sledgehammer'] 	     = 0.15,
    ['weapon_mp5'] 			         = 0.15,
    ['weapon_glock18c'] 		     = 0.15,
    ['weapon_glock22'] 			     = 0.15,
    ['weapon_aks74'] 			     = 0.15,
    ['weapon_ak74'] 			     = 0.15,
    ['weapon_ak74'] 			     = 0.15,
    ['WEAPON_PERFORATOR'] 		     = 0.05,
    ['WEAPON_BLUEBFKNIFE'] 			 = 0.05,
    ['WEAPON_BFKNIFE'] 				 = 0.05,
    ['WEAPON_CHBFKNIFE'] 			 = 0.05,
    ['WEAPON_CRIMSONBFKNIFE'] 		 = 0.05,
    ['WEAPON_FADEBFKNIFE'] 			 = 0.05,
    ['WEAPON_FLIPKNIFE'] 			 = 0.05,
    ['WEAPON_FORESTBFKNIFE'] 		 = 0.05,
    ['WEAPON_GUTKNIFE'] 			 = 0.05,
    ['WEAPON_HUNTSMANKNIFE'] 		 = 0.05,
    ['WEAPON_KARAMBITKNIFE'] 		 = 0.05,
    ['WEAPON_SAFARIBFKNIFE'] 		 = 0.05,
    ['WEAPON_SCORCHEDBFKNIFE'] 		 = 0.05,
    ['WEAPON_SLAUGHTERBFKNIFE'] 	 = 0.05,
    ['WEAPON_STAINEDRBFKNIFE'] 		 = 0.05,
    ['WEAPON_URBANRBFKNIFE'] 		 = 0.05,
```

## replace the next code in `qb-weapons/config.lua` (about line 170)

```lua
WeaponAttachments = {
    clip_attachment = {
        weapon_pistol = `COMPONENT_PISTOL_CLIP_02`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CLIP_02`,
        weapon_combatpistol = `COMPONENT_COMBATPISTOL_CLIP_02`,
        weapon_appistol = `COMPONENT_APPISTOL_CLIP_02`,
        weapon_pistol50 = `COMPONENT_PISTOL50_CLIP_02`,
        weapon_snspistol = `COMPONENT_SNSPISTOL_CLIP_02`,
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CLIP_02`,
        weapon_heavypistol = `COMPONENT_HEAVYPISTOL_CLIP_02`,
        weapon_vintagepistol = `COMPONENT_VINTAGEPISTOL_CLIP_02`,
        weapon_ceramicpistol = `COMPONENT_CERAMICPISTOL_CLIP_02`,
        weapon_microsmg = `COMPONENT_MICROSMG_CLIP_02`,
        weapon_smg = `COMPONENT_SMG_CLIP_02`,
        weapon_assaultsmg = `COMPONENT_ASSAULTSMG_CLIP_02`,
        weapon_minismg = `COMPONENT_MINISMG_CLIP_02`,
        weapon_smg_mk2 = `COMPONENT_SMG_MK2_CLIP_02`,
        weapon_machinepistol = `COMPONENT_MACHINEPISTOL_CLIP_02`,
        weapon_combatpdw = `COMPONENT_COMBATPDW_CLIP_02`,
        weapon_assaultshotgun = `COMPONENT_ASSAULTSHOTGUN_CLIP_02`,
        weapon_heavyshotgun = `COMPONENT_HEAVYSHOTGUN_CLIP_02`,
        weapon_assaultrifle = `COMPONENT_ASSAULTRIFLE_CLIP_02`,
        weapon_carbinerifle = `COMPONENT_CARBINERIFLE_CLIP_02`,
        weapon_advancedrifle = `COMPONENT_ADVANCEDRIFLE_CLIP_02`,
        weapon_specialcarbine = `COMPONENT_SPECIALCARBINE_CLIP_02`,
        weapon_bullpuprifle = `COMPONENT_BULLPUPRIFLE_CLIP_02`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CLIP_02`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CLIP_02`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CLIP_02`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CLIP_02`,
        weapon_compactrifle = `COMPONENT_COMPACTRIFLE_CLIP_02`,
        weapon_militaryrifle = `COMPONENT_MILITARYRIFLE_CLIP_02`,
        weapon_heavyrifle = `COMPONENT_HEAVYRIFLE_CLIP_02`,
        weapon_mg = `COMPONENT_MG_CLIP_02`,
        weapon_combatmg = `COMPONENT_COMBATMG_CLIP_02`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CLIP_02`,
        weapon_gusenberg = `COMPONENT_GUSENBERG_CLIP_02`,
        weapon_marksmanrifle = `COMPONENT_MARKSMANRIFLE_CLIP_02`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CLIP_02`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CLIP_02`,
        --Custom-Weapons
        WEAPON_M9 = `COMPONENT_M9_CLIP_01`,
        WEAPON_MP9 = `COMPONENT_MP9_CLIP_01`,
        WEAPON_UZI = `COMPONENT_MICROSMG_CLIP_01`,
        WEAPON_MAC10 = `COMPONENT_MICROSMG_CLIP_01`,
        WEAPON_AK47 = `COMPONENT_AK47_CLIP_01`,
        WEAPON_M70 = `COMPONENT_M70_CLIP_01`,
        WEAPON_M110 = `COMPONENT_M110_CLIP_01`,
        WEAPON_HK416 = `COMPONENT_HK416_CLIP_01`,
    },
    drum_attachment = {
        weapon_smg = `COMPONENT_SMG_CLIP_03`,
        weapon_machinepistol = `COMPONENT_MACHINEPISTOL_CLIP_03`,
        weapon_combatpdw = `COMPONENT_COMBATPDW_CLIP_03`,
        weapon_heavyshotgun = `COMPONENT_HEAVYSHOTGUN_CLIP_03`,
        weapon_assaultrifle = `COMPONENT_ASSAULTRIFLE_CLIP_03`,
        weapon_carbinerifle = `COMPONENT_CARBINERIFLE_CLIP_03`,
        weapon_specialcarbine = `COMPONENT_SPECIALCARBINE_CLIP_03`,
        weapon_compactrifle = `COMPONENT_COMPACTRIFLE_CLIP_03`,
    },
    flashlight_attachment = {
        weapon_pistol = `COMPONENT_AT_PI_FLSH`,
        weapon_pistol_mk2 = `COMPONENT_AT_PI_FLSH_02`,
        weapon_combatpistol = `COMPONENT_AT_PI_FLSH`,
        weapon_appistol = `COMPONENT_AT_PI_FLSH`,
        weapon_pistol50 = `COMPONENT_AT_PI_FLSH`,
        weapon_heavypistol = `COMPONENT_AT_PI_FLSH`,
        weapon_snspistol_mk2 = `COMPONENT_AT_PI_FLSH_03`,
        weapon_revolver_mk2 = `COMPONENT_AT_PI_FLSH`,
        weapon_microsmg = `COMPONENT_AT_PI_FLSH`,
        weapon_smg = `COMPONENT_AT_AR_FLSH`,
        weapon_assaultsmg = `COMPONENT_AT_AR_FLSH`,
        weapon_smg_mk2 = `COMPONENT_AT_AR_FLSH`,
        weapon_combatpdw = `COMPONENT_AT_AR_FLSH`,
        weapon_pumpshotgun = `COMPONENT_AT_AR_FLSH`,
        weapon_assaultshotgun = `COMPONENT_AT_AR_FLSH`,
        weapon_bullpupshotgun = `COMPONENT_AT_AR_FLSH`,
        weapon_pumpshotgun_mk2 = `COMPONENT_AT_AR_FLSH`,
        weapon_heavyshotgun = `COMPONENT_AT_AR_FLSH`,
        weapon_combatshotgun = `COMPONENT_AT_AR_FLSH`,
        weapon_assaultrifle = `COMPONENT_AT_AR_FLSH`,
        weapon_carbinerifle = `COMPONENT_AT_AR_FLSH`,
        weapon_advancedrifle = `COMPONENT_AT_AR_FLSH`,
        weapon_specialcarbine = `COMPONENT_AT_AR_FLSH`,
        weapon_bullpuprifle = `COMPONENT_AT_AR_FLSH`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_AR_FLSH`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_AR_FLSH`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_AR_FLSH`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_AR_FLSH`,
        weapon_militaryrifle = `COMPONENT_AT_AR_FLSH`,
        weapon_heavyrifle = `COMPONENT_AT_AR_FLSH`,
        weapon_marksmanrifle = `COMPONENT_AT_AR_FLSH`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_AR_FLSH`,
        weapon_grenadelauncher = `COMPONENT_AT_AR_FLSH`,
        --Custom-Weapons
        WEAPON_MAC10 = `COMPONENT_AT_AR_FLSH`,
        WEAPON_MAC10 = `COMPONENT_AT_PI_FLSH`,
        WEAPON_HK416 = `COMPONENT_AT_AR_FLSH`,
    },
    suppressor_attachment = {
        weapon_pistol = `COMPONENT_AT_PI_SUPP`,
        weapon_pistol_mk2 = `COMPONENT_AT_PI_SUPP_02`,
        weapon_combatpistol = `COMPONENT_AT_PI_SUPP`,
        weapon_appistol = `COMPONENT_AT_PI_SUPP`,
        weapon_pistol50 = `COMPONENT_AT_AR_SUPP_02`,
        weapon_heavypistol = `COMPONENT_AT_PI_SUPP`,
        weapon_snspistol_mk2 = `COMPONENT_AT_PI_SUPP_02`,
        weapon_vintagepistol = `COMPONENT_AT_PI_SUPP`,
        weapon_ceramicpistol = `COMPONENT_CERAMICPISTOL_SUPP`,
        weapon_microsmg = `COMPONENT_AT_AR_SUPP_02`,
        weapon_smg = `COMPONENT_AT_PI_SUPP`,
        weapon_assaultsmg = `COMPONENT_AT_AR_SUPP_02`,
        weapon_smg_mk2 = `COMPONENT_AT_PI_SUPP`,
        weapon_machinepistol = `COMPONENT_AT_PI_SUPP`,
        weapon_pumpshotgun = `COMPONENT_AT_SR_SUPP`,
        weapon_assaultshotgun = `COMPONENT_AT_AR_SUPP`,
        weapon_bullpupshotgun = `COMPONENT_AT_AR_SUPP_02`,
        weapon_pumpshotgun_mk2 = `COMPONENT_AT_SR_SUPP_03`,
        weapon_heavyshotgun = `COMPONENT_AT_AR_SUPP_02`,
        weapon_combatshotgun = `COMPONENT_AT_AR_SUPP`,
        weapon_assaultrifle = `COMPONENT_AT_AR_SUPP_02`,
        weapon_carbinerifle = `COMPONENT_AT_AR_SUPP`,
        weapon_advancedrifle = `COMPONENT_AT_AR_SUPP`,
        weapon_specialcarbine = `COMPONENT_AT_AR_SUPP_02`,
        weapon_bullpuprifle = `COMPONENT_AT_AR_SUPP`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_AR_SUPP`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_AR_SUPP_02`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_AR_SUPP_02`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_AR_SUPP`,
        weapon_militaryrifle = `COMPONENT_AT_AR_SUPP`,
        weapon_heavyrifle = `COMPONENT_AT_AR_SUPP`,
        weapon_sniperrifle = `COMPONENT_AT_AR_SUPP_02`,
        weapon_marksmanrifle = `COMPONENT_AT_AR_SUPP`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_AR_SUPP`,
        weapon_heavysniper_mk2 = `COMPONENT_AT_SR_SUPP_03`,
        --Custom-Weapons
        WEAPON_M9 = `COMPONENT_AT_PI_SUPP_02`,
        WEAPON_M1911 = `COMPONENT_AT_PI_SUPP_02`,
        WEAPON_DE = `COMPONENT_AT_PI_SUPP_02`,
        WEAPON_FNX45 = `COMPONENT_AT_PI_SUPP_02`,
        WEAPON_MP9 = `COMPONENT_AT_AR_SUPP_02`,
        WEAPON_UZI = `COMPONENT_AT_AR_SUPP_02`,
        WEAPON_MAC10 = `COMPONENT_AT_AR_SUPP_02`,
        WEAPON_AK47 = `COMPONENT_AT_AR_SUPP_02`,
        WEAPON_M70 = `COMPONENT_AT_AR_SUPP_02`,
        WEAPON_M110 = `COMPONENT_AT_AR_SUPP`,
        WEAPON_HK416 = `COMPONENT_AT_AR_SUPP`,
    },
    smallscope_attachment = {
        weapon_pistol_mk2 = `COMPONENT_AT_PI_RAIL`,
        weapon_snspistol_mk2 = `COMPONENT_AT_PI_RAIL_02`,
        weapon_microsmg = `COMPONENT_AT_SCOPE_MACRO`,
        weapon_smg = `COMPONENT_AT_SCOPE_MACRO_02`,
        weapon_assaultsmg = `COMPONENT_AT_SCOPE_MACRO`,
        weapon_combatpdw = `COMPONENT_AT_SCOPE_SMALL`,
        weapon_assaultrifle = `COMPONENT_AT_SCOPE_MACRO`,
        weapon_bullpuprifle = `COMPONENT_AT_SCOPE_SMALL`,
        weapon_militaryrifle = `COMPONENT_AT_SCOPE_SMALL`,
        weapon_mg = `COMPONENT_AT_SCOPE_SMALL_02`,
        weapon_revolver_mk2 = `COMPONENT_AT_SCOPE_MACRO_MK2`,
        weapon_smg_mk2 = `COMPONENT_AT_SCOPE_MACRO_02_SMG_MK2`,
        weapon_pumpshotgun_mk2 = `COMPONENT_AT_SCOPE_MACRO_MK2`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_SCOPE_MACRO_02_MK2`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_SCOPE_MACRO_MK2`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_SCOPE_MACRO_MK2`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_SCOPE_MACRO_MK2`,
        weapon_advancedrifle = `COMPONENT_AT_SCOPE_SMALL`,
        weapon_grenadelauncher = `COMPONENT_AT_SCOPE_SMALL`,
        --Custom-Weapons
        WEAPON_MP9 = `COMPONENT_AT_SCOPE_MACRO`,
    },
    medscope_attachment = {
        weapon_smg_mk2 = `COMPONENT_AT_SCOPE_SMALL_SMG_MK2`,
        weapon_pumpshotgun_mk2 = `COMPONENT_AT_SCOPE_SMALL_MK2`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_SCOPE_SMALL_MK2`,
        weapon_combatmg_mk2 = `COMPONENT_AT_SCOPE_SMALL_MK2`,
        weapon_carbinerifle = `COMPONENT_AT_SCOPE_MEDIUM`,
        weapon_specialcarbine = `COMPONENT_AT_SCOPE_MEDIUM`,
        weapon_combatmg = `COMPONENT_AT_SCOPE_MEDIUM`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_SCOPE_MEDIUM_MK2`,
    },
    largescope_attachment = {
        weapon_sniperrifle = `COMPONENT_AT_SCOPE_LARGE`,
        weapon_marksmanrifle = `COMPONENT_AT_SCOPE_LARGE_FIXED_ZOOM`,
        weapon_heavysniper_mk2 = `COMPONENT_AT_SCOPE_LARGE_MK2`,
    },
    holoscope_attachment = {
        weapon_heavyrevolver_mk2 = `COMPONENT_AT_SIGHTS`,
        weapon_smg_mk2 = `COMPONENT_AT_SIGHTS`,
        weapon_pumpshotgun_mk2 = `COMPONENT_AT_SIGHTS`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_SIGHTS`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_SIGHTS`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_SIGHTS`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_SIGHTS`,
        weapon_combatmg_mk2 = `COMPONENT_AT_SIGHTS`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_SIGHTS`,
    },
    advscope_attachment = {
        weapon_sniperrifle = `COMPONENT_AT_SCOPE_MAX`,
        weapon_heavysniper = `COMPONENT_AT_SCOPE_MAX`,
        weapon_heavysniper_mk2 = `COMPONENT_AT_SCOPE_MAX`,
    },
    nvscope_attachment = {
        weapon_heavysniper_mk2 = `COMPONENT_AT_SCOPE_NV`,
    },
    thermalscope_attachment = {
        weapon_heavysniper_mk2 = `COMPONENT_AT_SCOPE_THERMAL`,
    },
    flat_muzzle_brake = {
        weapon_smg_mk2 = `COMPONENT_AT_MUZZLE_01`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_MUZZLE_01`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_MUZZLE_01`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_MUZZLE_01`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_MUZZLE_01`,
        weapon_combatmg_mk2 = `COMPONENT_AT_MUZZLE_01`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_MUZZLE_01`,
    },
    tactical_muzzle_brake = {
        weapon_smg_mk2 = `COMPONENT_AT_MUZZLE_02`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_MUZZLE_02`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_MUZZLE_02`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_MUZZLE_02`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_MUZZLE_02`,
        weapon_combatmg_mk2 = `COMPONENT_AT_MUZZLE_02`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_MUZZLE_02`,
    },
    fat_end_muzzle_brake = {
        weapon_smg_mk2 = `COMPONENT_AT_MUZZLE_03`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_MUZZLE_03`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_MUZZLE_03`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_MUZZLE_03`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_MUZZLE_03`,
        weapon_combatmg_mk2 = `COMPONENT_AT_MUZZLE_03`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_MUZZLE_03`,
    },
    precision_muzzle_brake = {
        weapon_smg_mk2 = `COMPONENT_AT_MUZZLE_04`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_MUZZLE_04`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_MUZZLE_04`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_MUZZLE_04`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_MUZZLE_04`,
        weapon_combatmg_mk2 = `COMPONENT_AT_MUZZLE_04`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_MUZZLE_04`,
    },
    heavy_duty_muzzle_brake = {
        weapon_smg_mk2 = `COMPONENT_AT_MUZZLE_05`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_MUZZLE_05`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_MUZZLE_05`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_MUZZLE_05`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_MUZZLE_05`,
        weapon_combatmg_mk2 = `COMPONENT_AT_MUZZLE_05`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_MUZZLE_05`,
    },
    slanted_muzzle_brake = {
        weapon_smg_mk2 = `COMPONENT_AT_MUZZLE_06`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_MUZZLE_06`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_MUZZLE_06`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_MUZZLE_06`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_MUZZLE_06`,
        weapon_combatmg_mk2 = `COMPONENT_AT_MUZZLE_06`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_MUZZLE_06`,
    },
    split_end_muzzle_brake = {
        weapon_smg_mk2 = `COMPONENT_AT_MUZZLE_07`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_MUZZLE_07`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_MUZZLE_07`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_MUZZLE_07`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_MUZZLE_07`,
        weapon_combatmg_mk2 = `COMPONENT_AT_MUZZLE_07`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_MUZZLE_07`,
    },
    squared_muzzle_brake = {
        weapon_pumpshotgun_mk2 = `COMPONENT_AT_MUZZLE_08`,
        weapon_heavysniper_mk2 = `COMPONENT_AT_MUZZLE_08`
    },
    bellend_muzzle_brake = {
        weapon_heavysniper_mk2 = `COMPONENT_AT_MUZZLE_09`
    },
    barrel_attachment = {
        weapon_smg_mk2 = `COMPONENT_AT_SB_BARREL_02`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_BP_BARREL_02`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_SC_BARREL_02`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_AR_BARREL_02`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_CR_BARREL_02`,
        weapon_combatmg_mk2 = `COMPONENT_AT_MG_BARREL_02`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_MRFL_BARREL_02`,
        weapon_heavysniper_mk2 = `COMPONENT_AT_SR_BARREL_02`,
    },
    grip_attachment = {
        weapon_combatpdw = `COMPONENT_AT_AR_AFGRIP`,
        weapon_assaultshotgun = `COMPONENT_AT_AR_AFGRIP`,
        weapon_bullpupshotgun = `COMPONENT_AT_AR_AFGRIP`,
        weapon_heavyshotgun = `COMPONENT_AT_AR_AFGRIP`,
        weapon_assaultrifle = `COMPONENT_AT_AR_AFGRIP`,
        weapon_carbinerifle = `COMPONENT_AT_AR_AFGRIP`,
        weapon_advancedrifle = `COMPONENT_AT_AR_AFGRIP`,
        weapon_specialcarbine = `COMPONENT_AT_AR_AFGRIP`,
        weapon_bullpuprifle = `COMPONENT_AT_AR_AFGRIP`,
        weapon_bullpuprifle_mk2 = `COMPONENT_AT_AR_AFGRIP_02`,
        weapon_specialcarbine_mk2 = `COMPONENT_AT_AR_AFGRIP_02`,
        weapon_assaultrifle_mk2 = `COMPONENT_AT_AR_AFGRIP_02`,
        weapon_carbinerifle_mk2 = `COMPONENT_AT_AR_AFGRIP_02`,
        weapon_heavyrifle = `COMPONENT_AT_AR_AFGRIP`,
        weapon_combatmg = `COMPONENT_AT_AR_AFGRIP`,
        weapon_combatmg_mk2 = `COMPONENT_AT_AR_AFGRIP_02`,
        weapon_marksmanrifle = `COMPONENT_AT_AR_AFGRIP`,
        weapon_marksmanrifle_mk2 = `COMPONENT_AT_AR_AFGRIP_02`,
        weapon_grenadelauncher = `COMPONENT_AT_AR_AFGRIP`,
    },
    comp_attachment = {
        weapon_pistol_mk2 = `COMPONENT_AT_PI_COMP`,
        weapon_snspistol_mk2 = `COMPONENT_AT_PI_COMP_02`,
        weapon_revolver_mk2 = `COMPONENT_AT_PI_COMP_03`,
    },
    luxuryfinish_attachment = {
        weapon_pistol = `COMPONENT_PISTOL_VARMOD_LUXE`,
        weapon_combatpistol = `COMPONENT_COMBATPISTOL_VARMOD_LOWRIDER`,
        weapon_appistol = `COMPONENT_APPISTOL_VARMOD_LUXE`,
        weapon_pistol50 = `COMPONENT_PISTOL50_VARMOD_LUXE`,
        weapon_revolver = `COMPONENT_REVOLVER_VARMOD_GOON`,
        weapon_snspistol = `COMPONENT_SNSPISTOL_VARMOD_LOWRIDER`,
        weapon_heavypistol = `COMPONENT_HEAVYPISTOL_VARMOD_LUXE`,
        weapon_smg = `COMPONENT_SMG_VARMOD_LUXE`,
        weapon_assaultsmg = `COMPONENT_ASSAULTSMG_VARMOD_LOWRIDER`,
        weapon_microsmg = `COMPONENT_MICROSMG_VARMOD_LUXE`,
        weapon_pumpshotgun = `COMPONENT_PUMPSHOTGUN_VARMOD_LOWRIDER`,
        weapon_sawnoffshotgun = `COMPONENT_SAWNOFFSHOTGUN_VARMOD_LUXE`,
        weapon_assaultrifle = `COMPONENT_ASSAULTRIFLE_VARMOD_LUXE`,
        weapon_carbinerifle = `COMPONENT_CARBINERIFLE_VARMOD_LUXE`,
        weapon_advancedrifle = `COMPONENT_ADVANCEDRIFLE_VARMOD_LUXE`,
        weapon_specialcarbine = `COMPONENT_SPECIALCARBINE_VARMOD_LOWRIDER`,
        weapon_bullpuprifle = `COMPONENT_BULLPUPRIFLE_VARMOD_LOW`,
        weapon_heavyrifle = `COMPONENT_BULLPUPRIFLE_VARMOD_LOW`,
        weapon_mg = `COMPONENT_MG_VARMOD_LOWRIDER`,
        weapon_combatmg = `COMPONENT_COMBATMG_VARMOD_LOWRIDER`,
        weapon_sniperrifle = `COMPONENT_SNIPERRIFLE_VARMOD_LUXE`,
        weapon_marksmanrifle = `COMPONENT_MARKSMANRIFLE_VARMOD_LUXE`,
    },
    digicamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO`,
    },
    brushcamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_02`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_02`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_02`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_02`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_02`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_02`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_02`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_02`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_02`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_02`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_02`,
    },
    woodcamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_03`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_03`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_03`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_03`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_03`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_03`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_03`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_03`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_03`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_03`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_03`,
    },
    skullcamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_04`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_04`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_04`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_04`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_04`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_04`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_04`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_04`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_04`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_04`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_04`,
    },
    sessantacamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_05`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_05`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_05`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_05`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_05`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_05`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_05`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_05`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_05`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_05`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_05`,
    },
    perseuscamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_06`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_06`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_06`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_06`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_06`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_06`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_06`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_06`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_06`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_06`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_06`,
    },
    leopardcamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_07`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_07`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_07`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_07`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_07`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_07`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_07`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_07`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_07`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_07`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_07`,
    },
    zebracamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_08`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_08`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_08`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_08`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_08`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_08`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_08`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_08`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_08`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_08`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_08`,
    },
    geocamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_09`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_09`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_09`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_09`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_09`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_09`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_09`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_09`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_09`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_09`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_09`,
    },
    boomcamo_attachment = {
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_10`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_10`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_10`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_10`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_10`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_10`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_10`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_10`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_10`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_10`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_10`,
    },
    patriotcamo_attachment = {
        weapon_heavyrifle_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_IND_01`,
        weapon_snspistol_mk2 = `COMPONENT_SNSPISTOL_MK2_CAMO_IND_01`,
        weapon_pistol_mk2 = `COMPONENT_PISTOL_MK2_CAMO_IND_01`,
        weapon_smg_mk2 = `COMPONENT_REVOLVER_MK2_CAMO_IND_01`,
        weapon_pumpshotgun_mk2 = `COMPONENT_PUMPSHOTGUN_MK2_CAMO_IND_01`,
        weapon_bullpuprifle_mk2 = `COMPONENT_BULLPUPRIFLE_MK2_CAMO_IND_01`,
        weapon_specialcarbine_mk2 = `COMPONENT_SPECIALCARBINE_MK2_CAMO_IND_01`,
        weapon_assaultrifle_mk2 = `COMPONENT_ASSAULTRIFLE_MK2_CAMO_IND_01`,
        weapon_carbinerifle_mk2 = `COMPONENT_CARBINERIFLE_MK2_CAMO_IND_01`,
        weapon_combatmg_mk2 = `COMPONENT_COMBATMG_MK2_CAMO_IND_01`,
        weapon_marksmanrifle_mk2 = `COMPONENT_MARKSMANRIFLE_MK2_CAMO_IND_01`,
        weapon_heavysniper_mk2 = `COMPONENT_HEAVYSNIPER_MK2_CAMO_IND_01`,
    },
}

```

## Replace the next code in `qb-smallresources/client/weapdraw.lua`

```lua
local weapons = {
	--Custom Weapon
	'WEAPON_AK47',
	'WEAPON_M9',
	'WEAPON_FNX45',
	'WEAPON_DE',
	'WEAPON_GLOCK17',
	'WEAPON_M4',
	'WEAPON_HK416',
	'WEAPON_MK14',
	'WEAPON_HUNTINGRIFLE',
	'WEAPON_AR15',
	'WEAPON_M70',
	'WEAPON_M1911',
	'WEAPON_MAC10',
	'WEAPON_UZI',
	'WEAPON_MP9',
	'WEAPON_M110',
	'WEAPON_MOSSBERG',
	'WEAPON_REMINGTON',
	'WEAPON_SCARH',
	'WEAPON_SHIV',
	'WEAPON_KATANA',
	'WEAPON_SLEDGEHAMMER',
	'WEAPON_COLBATON',
	'WEAPON_MP5',
	'WEAPON_GLOCK18C',
	'WEAPON_GLOCK22',
	'WEAPON_AKS74',
	'WEAPON_AK74',
}
--Weapons that require the Police holster animation
local holsterableWeapons = {
	--'WEAPON_STUNGUN',
	--Custom Weapon
	'WEAPON_DE',
	'WEAPON_GLOCK17',
	'WEAPON_M9',
	'WEAPON_M1911',
	'WEAPON_FNX45',
	'WEAPON_GLOCK18C',
	'WEAPON_GLOCK22',
}
```

## Drop the next code in `qb-smallresources/client/recoil.lua` ( LINE 107 )

```lua
	-- CUSTOM WEAPONS
	[GetHashKey("weapon_ak47")] = 0.5,
	[GetHashKey("weapon_de")] = 0.5,
	[GetHashKey("weapon_fnx45")] = 0.3,
	[GetHashKey("weapon_glock17")] = 0.3,
	[GetHashKey("weapon_m4")] = 0.3,
	[GetHashKey("weapon_hk416")] = 0.3,
	[GetHashKey("weapon_mk14")] = 0.4,
	[GetHashKey("weapon_m110")] = 0.4,
	[GetHashKey("weapon_huntingrifle")] = 0.4,
	[GetHashKey("weapon_ar15")] = 0.4,
	[GetHashKey("weapon_m9")] = 0.4,
	[GetHashKey("weapon_m70")] = 0.5,
	[GetHashKey("weapon_m1911")] = 0.4,
	[GetHashKey("weapon_mac10")] = 0.7,
	[GetHashKey("weapon_uzi")] = 0.7,
	[GetHashKey("weapon_mp9")] = 0.7,
	[GetHashKey("weapon_mossberg")] = 0.7,
	[GetHashKey("weapon_remington")] = 0.7,
	[GetHashKey("weapon_scarh")] = 0.5,
```

## Replace the next code in `qb-jewelery/config.lua`

```lua
Config.WhitelistedWeapons = {
    [`weapon_assaultrifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_carbinerifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pumpshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_sawnoffshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_compactrifle`] = {
        ["timeOut"] = 10000
    },
    [`weapon_microsmg`] = {
        ["timeOut"] = 10000
    },
    [`weapon_autoshotgun`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol_mk2`] = {
        ["timeOut"] = 10000
    },
    [`weapon_combatpistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_appistol`] = {
        ["timeOut"] = 10000
    },
    [`weapon_pistol50`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m4`] = {
        ["timeOut"] = 10000
    },
    [`weapon_hk416`] = {
        ["timeOut"] = 10000
    },
    [`weapon_ar15`] = {
        ["timeOut"] = 10000
    },
    [`weapon_scarh`] = {
        ["timeOut"] = 10000
    },
    [`weapon_de`] = {
        ["timeOut"] = 10000
    },
    [`weapon_fnx45`] = {
        ["timeOut"] = 10000
    },
    [`weapon_glock17`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mossberg`] = {
        ["timeOut"] = 10000
    },
    [`weapon_remington`] = {
        ["timeOut"] = 10000
    },
    [`weapon_ak47`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m70`] = {
        ["timeOut"] = 10000
    },
    [`weapon_uzi`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mp9`] = {
        ["timeOut"] = 10000
    },
    [`weapon_mac10`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m9`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m1911`] = {
        ["timeOut"] = 10000
    },
    [`weapon_m110`] = {
        ["timeOut"] = 10000
    },
}
```

## Replace the next code in `qb-ambulancejob/config.lua`

```lua
    --[[ HIGH CALIBER ]]
    [`WEAPON_DE`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_M4`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_HK416`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_AR15`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_AK47`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_M70`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_SCARH`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_MK14`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_M110`] = Config.WeaponClasses['HIGH_CALIBER'],
    [`WEAPON_HUNTINGRIFLE`] = Config.WeaponClasses['HIGH_CALIBER'],
    --[[ MEDIUM CALIBER ]]
    [`WEAPON_UZI`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_MAC10`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    [`WEAPON_MP9`] = Config.WeaponClasses['MEDIUM_CALIBER'],
    --[[ SMALL CALIBER ]]
    [`WEAPON_GLOCK17`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_M9`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_M1911`] = Config.WeaponClasses['SMALL_CALIBER'],
    [`WEAPON_FNX45`] = Config.WeaponClasses['SMALL_CALIBER'],
    --[[ SHOTGUN ]]
    [`WEAPON_REMINGTON`] = Config.WeaponClasses['SHOTGUN'],
    [`WEAPON_MOSSBERG`] = Config.WeaponClasses['SHOTGUN'],
    --[[ CUTTING ]]
    [`WEAPON_SHIV`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_KATANA`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_BAYONETKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_BLUEBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_BFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_CHBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_CRIMSONBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_FADEBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_FLIPKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_FORESTBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_GUTKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_HUNTSMANKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_KARAMBITKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_SAFARIBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_SCORCHEDBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_SLAUGHTERBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_STAINEDRBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    [`WEAPON_URBANRBFKNIFE`] = Config.WeaponClasses['CUTTING'],
    --[[ HEAVY IMPACT ]]
    [`WEAPON_SLEDGEHAMMER`] = Config.WeaponClasses['HEAVY_IMPACT'],
    [`WEAPON_PERFORATOR`] = Config.WeaponClasses['HEAVY_IMPACT'],
```

## Add the next code to your `BackItems.lua` [devyn-backitems](https://github.com/devin-monro/devyn-backitems) script (OPTIONAL)

```lua
    ["weapon_ak47"] = {
        model="w_ar_ak47",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_m70"] = {
        model="w_ar_m70",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_remington"] = {
        model="w_sg_remington",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_m110"] = {
        model="w_sr_m110",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_huntingrifle"] = {
        model="w_sr_huntingrifle",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_uzi"] = {
        model="w_sb_uzi",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 0.0,
    },
    ["weapon_mp9"] = {
        model="w_sb_mp9",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 0.0,
    },
    ["weapon_mk14"] = {
        model="w_sr_mk14",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_mossberg"] = {
        model="w_sg_mossberg",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 0.0,
    },
    ["weapon_m4"] = {
        model="w_ar_m4",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_hk416"] = {
        model="w_ar_hk416",
        back_bone = 24818,
        x = -0.0,
        y = -0.17,
        z = 0.08,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_scarh"] = {
        model="w_ar_scarh",
        back_bone = 24818,
        x =  0.12,
        y = -0.17,
        z = -0.0,
        x_rotation = 0.0,
        y_rotation = 180.0,
        z_rotation = 0.0,
    },
    ["weapon_mac10"] = {
        model="w_sb_mac10",
        back_bone = 24818,
        x = 0.0,
        y = -0.17,
        z = -0.12,
        x_rotation = 0.0,
        y_rotation = -180.0,
        z_rotation = 180.0,
    },
    ["weapon_katana"] = {
        model="w_me_katana",
        back_bone = 24818,
        x = -0.2,
        y = -0.15,
        z = 0.12,
        x_rotation = 0.0,
        y_rotation = -120.0,
        z_rotation = 180.0,
    },
    ["weapon_perforator"] = {
        model="w_me_perforator",
        back_bone = 24818,
        x = -0.2,
        y = -0.15,
        z = 0.12,
        x_rotation = 0.0,
        y_rotation = -120.0,
        z_rotation = 180.0,
    },
```

## Add this next line of code to your weaponsTable in `ps-dispatch/client/cl_events.lua`

```lua
-- Custom weapons
    [GetHashKey("weapon_ak47")] = "CLASS 3: AK-47",
    [GetHashKey("weapon_de")] = "CLASS 2: Desert Eagle",
    [GetHashKey("weapon_fnx45")] = "CLASS 1: FN .45",
    [GetHashKey("weapon_glock17")] = "CLASS 1: Glock 17",
    [GetHashKey("weapon_m4")] = "CLASS 3: M4",
    [GetHashKey("weapon_hk416")] = "CLASS 3: HK-416",
    [GetHashKey("weapon_mk14")] = "CLASS 4: MK 14",
    [GetHashKey("weapon_mk14")] = "CLASS 4: M110",
    [GetHashKey("weapon_huntingrifle")] = "CLASS 3: Hunting Rifle",
    [GetHashKey("weapon_ar15")] = "CLASS 3: AR-15",
    [GetHashKey("weapon_m9")] = "CLASS 1: M9",
    [GetHashKey("weapon_m70")] = "CLASS 3: m70",
    [GetHashKey("weapon_m1911")] = "CLASS 1: 1911",
    [GetHashKey("weapon_mac10")] = "CLASS 2: Mac-10",
    [GetHashKey("weapon_uzi")] = "CLASS 2: Uzi",
    [GetHashKey("weapon_mp9")] = "CLASS 2: MP9",
    [GetHashKey("weapon_mossberg")] = "CLASS 2: Mossberg",
    [GetHashKey("weapon_remington")] = "CLASS 2: Remington",
    [GetHashKey("weapon_scarh")] = "CLASS 3: Scar-H"
```

## (OPTIONAL) Add the weapons to your police armory `qb-policejob/config.lua`

```lua
Config.Items = {
    label = "Police Armory",
    slots = 30,
    items = {
        [1] = {
            name = "weapon_glock17",
            price = 12,
            amount = 1,
            info = {
                attachments = {
                    {component = "COMPONENT_AT_PI_FLSH", label = "Flashlight"},
                }
            },
            type = "weapon",
            slot = 11,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [2] = {
            name = "weapon_m4",
            price = 12,
            amount = 1,
            info = {
                attachments = {
                    {component = "COMPONENT_AT_AR_FLSH", label = "Flashlight"},
                }
            },
            type = "weapon",
            slot = 19,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [3] = {
            name = "weapon_ar15",
            price = 12,
            amount = 1,
            info = {
                attachments = {
                    {component = "COMPONENT_AT_AR_FLSH", label = "Flashlight"},
                    {component = "COMPONENT_AT_SCOPE_MEDIUM", label = "Scope"},
                    {component = "COMPONENT_AT_AR_AFGRIP", label = "AF-Grip"},
                }
            },
            type = "weapon",
            slot = 20,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [4] = {
            name = "weapon_remington",
            price = 12,
            amount = 1,
            info = {
                attachments = {
                    {component = "COMPONENT_AT_SG_FLSH", label = "Flashlight"},
                }
            },
            type = "weapon",
            slot = 21,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [5] = {
            name = "weapon_scarh",
            price = 12,
            amount = 1,
            info = {
                attachments = {
                    {component = "COMPONENT_AT_AR_FLSH", label = "Flashlight"},
                }
            },
            type = "weapon",
            slot = 24,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
        [6] = {
            name = "weapon_mk14",
            price = 12,
            amount = 1,
            info = {
                attachments = {
                    {component = "COMPONENT_AT_SCOPE_LARGE", label = "Scope"},
                }
            },
            type = "weapon",
            slot = 25,
            authorizedJobGrades = {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14}
        },
    }
}
```
