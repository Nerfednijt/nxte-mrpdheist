# nxte-mrpdheist
 Free open-source MRPD heist easy to adjust to your server with the config.lua

Features:
- server synced
- Night vision goggles
- Blackout 
- NPC's 
 
TO DO :
- add the pictures in the images folder to your inventory/html/images folder
- add next code to your qb-core/shared/items.lua :
- ['nightgoggles'] 			 		= {['name'] = 'nightgoggles', 					['label'] = 'Night vision helmet', 		['weight'] = 5000, 		['type'] = 'item', 		['image'] = 'nightvision.png', 			['unique'] = true, 		['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'A high-tier military night vision helmet'},
- ['armorykey'] 			 			= {['name'] = 'armorykey', 						['label'] = 'Armory Access Card', 		['weight'] = 1000, 		['type'] = 'item', 		['image'] = 'armorykey.png', 			['unique'] = true, 		['useable'] = false, 	['shouldClose'] = false,   ['combinable'] = nil,   ['description'] = 'A access card for the MRPD armory'},


PREVIEW : https://medal.tv/games/gta-v/clips/fLicm3mCTq4At/d1337nkc2UXF?invite=cr-MSwzUk8sMjM3NTk3MjEs


Dependency's:
- Hack : https://github.com/Prime-Script/prime-vangelico/tree/main/assets ( hacking folder )
- Thermite game : https://github.com/pushkart2/memorygame
