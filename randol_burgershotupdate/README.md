# Randolio Burgershot UPDATE for QBCore Framework.

## Link to free MLO
```
 https://www.gta5-mods.com/maps/mlo-burgershot-2023-add-on-sp-fivem

```
## If using OX_INVENTORY change Config.Ox to true in the config.lua

## Add images from "images" folder. For OX_INVENTORY add images to ox_inventory/web/images

## Add to your qb-core/shared/items.lua (Credit to https://github.com/Zach488/qb-burgershot for saving me the stress of making my own.)

```

	['burger-bleeder'] 				 = {['name'] = 'burger-bleeder', 			 	['label'] = 'Bleeder', 					['weight'] = 250, 		['type'] = 'item', 		['image'] = 'bs_the-bleeder.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sates Hunger.'},
	['burger-moneyshot'] 			 = {['name'] = 'burger-moneyshot', 			 	['label'] = 'Moneyshot', 				['weight'] = 300, 		['type'] = 'item', 		['image'] = 'bs_money-shot.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sates Hunger.'},
	['burger-torpedo'] 				 = {['name'] = 'burger-torpedo', 			 	['label'] = 'Torpedo', 					['weight'] = 310, 		['type'] = 'item', 		['image'] = 'bs_torpedo.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sates Hunger.'},
	['burger-heartstopper'] 		 = {['name'] = 'burger-heartstopper', 			['label'] = 'Heartstopper', 			['weight'] = 2500, 		['type'] = 'item', 		['image'] = 'bs_the-heart-stopper.png', 	['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sates Hunger.'},
	['burger-meatfree'] 		 	 = {['name'] = 'burger-meatfree', 				['label'] = 'MeatFree', 			['weight'] = 125, 		['type'] = 'item', 			['image'] = 'bs_meat-free.png', 			['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sates Hunger.'},
	['burger-fries'] 				 = {['name'] = 'burger-fries', 			 	  	['label'] = 'Fries', 				['weight'] = 125, 		['type'] = 'item', 			['image'] = 'bs_fries.png', 				['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Sates Hunger.'},
	['burger-softdrink'] 			 = {['name'] = 'burger-softdrink', 				['label'] = 'Soft Drink', 				['weight'] = 125, 		['type'] = 'item', 		['image'] = 'bs_softdrink.png', 		['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'An Ice Cold Drink.'},
	['burger-mshake'] 			     = {['name'] = 'burger-mshake', 				['label'] = 'Milkshake', 				['weight'] = 125, 		['type'] = 'item', 		['image'] = 'bs_milkshake.png', 		['unique'] = false, 	['useable'] = true, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Hand-scooped for you!'},
	['burger-bun'] 				 	 = {['name'] = 'burger-bun', 			 	  	['label'] = 'Bun', 			['weight'] = 125, 		['type'] = 'item', 					['image'] = 'bs_bun.png', 		    		['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'An Ingredient'},
	['burger-meat'] 				 = {['name'] = 'burger-meat', 			 	  	['label'] = 'Cooked Patty', 			['weight'] = 125, 		['type'] = 'item', 		['image'] = 'bs_patty.png', 		    	['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'An Ingredient'},
	['burger-lettuce'] 				 = {['name'] = 'burger-lettuce', 			 	['label'] = 'Lettuce', 				['weight'] = 125, 		['type'] = 'item', 			['image'] = 'bs_lettuce.png', 	    		['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'An Ingredient'},
	['burger-tomato'] 				 = {['name'] = 'burger-tomato', 			 	['label'] = 'Tomato', 				['weight'] = 125, 		['type'] = 'item', 			['image'] = 'bs_tomato.png', 	    		['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'An Ingredient'},
	['burger-raw'] 				 	 = {['name'] = 'burger-raw', 			 		['label'] = 'Raw Patty', 				['weight'] = 125, 		['type'] = 'item', 		['image'] = 'bs_patty_raw.png', 	        ['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'An Ingredient'},
	['burger-potato'] 				 = {['name'] = 'burger-potato', 			 	['label'] = 'Bag of Potatoes', 		['weight'] = 1500, 		['type'] = 'item', 			['image'] = 'bs_potato.png', 	    		['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'An Ingredient'},
	['burger-mshakeformula'] 		 = {['name'] = 'burger-mshakeformula', 			['label'] = 'Milkshake Formula', 		['weight'] = 125, 		['type'] = 'item', 		['image'] = 'bs_ingredients_icecream.png', ['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'An Ingredient'},
	['burger-sodasyrup'] 		 	 = {['name'] = 'burger-sodasyrup', 				['label'] = 'Soda Syrup', 		['weight'] = 125, 		['type'] = 'item', 				['image'] = 'bs_ingredients_hfcs.png', 	['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'An Ingredient'},

```
## For OX_INVENTORY add to ox_inventory/data/items.lua
```
["burger-bun"] = {
    label = "Bun",
    weight = 125,
    stack = true,
    close = true,
    description = "An Ingredient",
    client = {
        image = "bs_bun.png",
    }
},

["burger-mshake"] = {
    label = "Milkshake",
    weight = 125,
    stack = true,
    close = true,
    description = "Hand-scooped for you!",
    client = {
        image = "bs_milkshake.png",
    }
},

["burger-moneyshot"] = {
    label = "Moneyshot",
    weight = 300,
    stack = true,
    close = true,
    description = "Sates Hunger.",
    client = {
        image = "bs_money-shot.png",
    }
},

["burger-heartstopper"] = {
    label = "Heartstopper",
    weight = 2500,
    stack = true,
    close = true,
    description = "Sates Hunger.",
    client = {
        image = "bs_the-heart-stopper.png",
    }
},

["burger-lettuce"] = {
    label = "Lettuce",
    weight = 125,
    stack = true,
    close = true,
    description = "An Ingredient",
    client = {
        image = "bs_lettuce.png",
    }
},

["burger-fries"] = {
    label = "Fries",
    weight = 125,
    stack = true,
    close = true,
    description = "Sates Hunger.",
    client = {
        image = "bs_fries.png",
    }
},

["burger-mshakeformula"] = {
    label = "Milkshake Formula",
    weight = 125,
    stack = true,
    close = true,
    description = "An Ingredient",
    client = {
        image = "bs_ingredients_icecream.png",
    }
},

["burger-meatfree"] = {
    label = "MeatFree",
    weight = 125,
    stack = true,
    close = true,
    description = "Sates Hunger.",
    client = {
        image = "bs_meat-free.png",
    }
},

["burger-softdrink"] = {
    label = "Soft Drink",
    weight = 125,
    stack = true,
    close = true,
    description = "An Ice Cold Drink.",
    client = {
        image = "bs_softdrink.png",
    }
},

["burger-bleeder"] = {
    label = "Bleeder",
    weight = 250,
    stack = true,
    close = true,
    description = "Sates Hunger.",
    client = {
        image = "bs_the-bleeder.png",
    }
},

["burger-raw"] = {
    label = "Raw Patty",
    weight = 125,
    stack = true,
    close = true,
    description = "An Ingredient",
    client = {
        image = "bs_patty_raw.png",
    }
},

["burger-meat"] = {
    label = "Cooked Patty",
    weight = 125,
    stack = true,
    close = true,
    description = "An Ingredient",
    client = {
        image = "bs_patty.png",
    }
},

["burger-tomato"] = {
    label = "Tomato",
    weight = 125,
    stack = true,
    close = true,
    description = "An Ingredient",
    client = {
        image = "bs_tomato.png",
    }
},

["burger-sodasyrup"] = {
    label = "Soda Syrup",
    weight = 125,
    stack = true,
    close = true,
    description = "An Ingredient",
    client = {
        image = "bs_ingredients_hfcs.png",
    }
},

["burger-potato"] = {
    label = "Bag of Potatoes",
    weight = 1500,
    stack = true,
    close = true,
    description = "An Ingredient",
    client = {
        image = "bs_potato.png",
    }
},

["burger-torpedo"] = {
    label = "Torpedo",
    weight = 310,
    stack = true,
    close = true,
    description = "Sates Hunger.",
    client = {
        image = "bs_torpedo.png",
    }
},

```
## Add this to your @qb-core/shared/jobs.lua 
```
burgershot = {
		label = 'Burgershot',
		defaultDuty = false,
		grades = {
			['0'] = {name = 'Trainee', payment = 50 },
			['1'] = {name = 'Employee', payment = 75 },
			['2'] = {name = 'Burger Flipper',payment = 100},
			['3'] = {name = 'Manager', payment = 125 },
			['4'] = {name = 'Owner', isboss = true, payment = 150 },
		},
	},	

```

## Add these to rpemotes.
```
["bsdrink"] = {
        "amb@world_human_drinking@coffee@male@idle_a", 
        "idle_c", 
        "BS Drink",
        AnimationOptions = {
            Prop = 'prop_food_bs_juice02',
            PropBone = 28422,
            PropPlacement = {
                0.02,
                0.0,
                -0.10,
                0.0,
                0.0,
                -0.50
            },
            EmoteLoop = true,
            EmoteMoving = true,
        } 
   },
    ["fries"] = {
        "mp_player_inteat@burger", 
        "mp_player_int_eat_burger",
        "Fries", 
        AnimationOptions = {
            Prop = 'prop_food_bs_chips',
            PropBone = 60309,
            PropPlacement = {
                -0.0100, 
                0.0200, 
                -0.0100, 
                -175.1935, 
                97.6975, 
                13.9598
            },
            EmoteMoving = true,
        }
    },
    ["fbbq"] = {
        "amb@prop_human_bbq@male@idle_a",
        "idle_b", 
        "fbbq", 
        AnimationOptions = {
            Prop = "prop_fish_slice_01",
            PropBone = 28422,
            PropPlacement = {
                0.0,
                0.0,
                0.0,
                0.0,
                0.0,
                0.0
            },
            EmoteLoop = true,
            EmoteMoving = false,
        }
    },
	["uncuff"] = {
		"mp_arresting",
		"a_uncuff",
		"Uncuff",
			AnimationOptions = {
			EmoteLoop = true,
			EmoteMoving = true
		}
	},

```

## Add the 2 .ogg files in [sounds] to interact-sound/client/html/sounds

## For OX_INVENTORY add to ox_inventory/data/shops.lua

```
burgershot = {
    name = 'Burgershot',
    groups = {
        ['burgershot'] = 0
    },
    inventory = {
        { name = 'burger-bun', price = 0},
        { name = 'burger-raw', price = 0},
        { name = 'burger-tomato', price = 0},
        { name = 'burger-lettuce', price = 0},
        { name = 'burger-potato', price = 0},
        { name = 'burger-mshakeformula', price = 0},
        { name = 'burger-sodasyrup', price = 0},
    },
},

```
