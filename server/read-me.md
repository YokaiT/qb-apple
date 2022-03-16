# qb-apple
An Apple store robbery for FiveM using QBCore Framework.



# Add the following code to your shared items.lua in qb-core, 

-- Apple Store Robbery
['airpods'] 				 	 = {['name'] = 'Air Pods', 			  	     	['label'] = 'Air Pods', 			    ['weight'] = 1500, 		['type'] = 'item', 		['image'] = 'airpods.png', 			    ['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Apple Airpods'},
['appletv'] 				     = {['name'] = 'Apple TV', 			  	  	    ['label'] = 'Apple TV', 			    ['weight'] = 1500, 		['type'] = 'item', 		['image'] = 'appletv.png', 		        ['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'AppleTV'},
['beats'] 				 	     = {['name'] = 'Beats Headset', 			  	['label'] = 'Golden Chain', 			['weight'] = 1500, 		['type'] = 'item', 		['image'] = 'beats.png', 			    ['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Beats wireless headset'},
['macbook'] 				     = {['name'] = 'Mac Book', 			  	     	['label'] = 'Mac Book', 			    ['weight'] = 2000, 		['type'] = 'item', 		['image'] = 'macbook.png', 		        ['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,	   ['combinable'] = nil,   ['description'] = 'Apple Macbook'},
['ipad'] 			 	 	     = {['name'] = 'IPad', 			  			    ['label'] = 'IPad', 				    ['weight'] = 7000, 	    ['type'] = 'item', 		['image'] = 'ipad.png', 				['unique'] = false, 	['useable'] = false, 	['shouldClose'] = true,    ['combinable'] = nil,   ['description'] = 'Apple iPad'},

# Add item images to your inventory images example (qb-inventory > html > images)


# Add the following code to qb-pawnshop > config.lua (adjust pricing to suit your economy) 
    [5] = {
        item = "tablet",
        price = math.random(50,100)
    },
    [6] = {
        item = "iphone",
        price = math.random(50,100)
    },
    [7] = {
        item = "samsungphone",
        price = math.random(50,100)
    },
    [8] = {
        item = "laptop",
        price = math.random(50,100)
    },
    [9] = {
        item = "airpods",
        price = math.random(50,100)
    },
    [10] = {
        item = "appletv",
        price = math.random(50,100)
    },
    [11] = {
        item = "ipad",
        price = math.random(50,100)
    },
    [12] = {
        item = "macbook",
        price = math.random(50,100)
    },
    [13] = {
        item = "beats",
        price = math.random(50,100)
    },


