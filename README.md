# Vangelico Heist For QBCore

# Requirements
- QB-Framework: https://github.com/qbcore-framework/qb-core

- PolyZone: https://github.com/qbcore-framework/PolyZone

- QB-Target: https://github.com/BerkieBb/qb-target

- Thermite Minigame: This will be located in the discord | Vangelico Heist / #Requirements

- Laptop Minigame: This will be located in the discord | Vangelico Heist / #Requirements

# Future Updates

- Adding Translations to the progressbar

- Adding More Dispatch Systems (Will be adding Core, CDD and ERP_MDT when released)

# Installation

- Create a file inside nui_doorlock / config, and add this inside the file (this will ensure the door is locked)
```
Config.DoorList['doubledoor'] = {
	authorizedJobs = { ['police']=0 }, -- ['ambulance']=0, ['bcso']=0
	lockpick = false,
	doors = {
		{objHash = 1425919976, objHeading = 306.00003051758, objCoords = vec3(-631.955384, -236.333268, 38.206532)},
		{objHash = 9467943, objHeading = 306.00003051758, objCoords = vec3(-630.426514, -238.437546, 38.206532)}
    },
	audioRemote = false,
	locked = true,
	slides = false,
	maxDistance = 2.5,
    --oldMethod = true,
    --audioLock = {['file'] = 'metal-locker.ogg', ['volume'] = 0.6},
    --audioUnlock = {['file'] = 'metallic-creak.ogg', ['volume'] = 0.7},
    --autoLock = 1000
}
```

- Add this item to qb-core / shared / items.lua

```
["usb_green"] 		 	     	 = {["name"] = "usb_green", 					["label"] = "Green USB", 				["weight"] = 5000, 	    ["type"] = "item", 		["image"] = "usb_green.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,	   ["combinable"] = nil,   ["description"] = "What is this USB used for?"},
```

- Add usb_green to inventory / html / images

This will be located in the discord | Vangelico Heist / #Requirements

# Locales System

- English, Turkish, French

Other Languages Coming Soon!

[Discord](https://discord.gg/GXxpdEX3c4) | [Tebex](https://prime-scripts.tebex.io/)

# Author 'SocialPeely#4095'