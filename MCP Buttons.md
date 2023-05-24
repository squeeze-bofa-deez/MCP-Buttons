## MCP Buttons

------------------------------------------------------------------------------------------------

# Follow/Assist (Press in order)

Mage/Healer:
Obj_OgreMCP:PasteButton[OgreConsoleCommand,OFA-MH,-letsgo,all,-ass,Martius,all,-Ofol,all,Cheezecake,-ofol--,-ofol--,-ofol--]

Scout:
Obj_OgreMCP:PasteButton[OgreConsoleCommand,OFA-S,-letsgo,all,-ass,Martius,all,-Ofol,Melee,Kelin,-ofol--,-ofol--,-ofol--]

Tank:
Obj_OgreMCP:PasteButton[OgreConsoleCommand,OFA-T,-letsgo,YOURTANK,-ass,Martius,YOURTANK,-Ofol,YOURTANK,Martius,-ofol--,-ofol--,-ofol--]

------------------------------------------------------------------------------------------------

# Food and Drink Toggle On and Off

Obj_OgreMCP:PasteButton[FoodDrink_AutoConsume,Food-T,all,TOGGLE]

------------------------------------------------------------------------------------------------

# Cure Toggle On and Off

Obj_OgreMCP:PasteButton[OgreConsoleCommand,Cure_Tog,-ChangeOgreBotUIOption,\"All\",checkbox_settings_disablecaststack_cure,TOGGLE]

------------------------------------------------------------------------------------------------

# Cure Curse Toggle On and Off

Obj_OgreMCP:PasteButton[OgreConsoleCommand,Curse_T,-ChangeCastStackListBoxItem,\"All\",\"Cure Curse\",TOGGLE]

------------------------------------------------------------------------------------------------

# Ignore NPC HP (100%) Toggle

Obj_OgreMCP:PasteButton[OgreConsoleCommand,INH_T,-UplinkOptionChange,\"All\",checkbox_settings_ignoretargettoattackhealthcheck,TOGGLE]

------------------------------------------------------------------------------------------------

# Absorb Magic Toggle On and Off

Obj_OgreMCP:PasteButton[ChangeCastStackListBoxItem,Dispel,all,absorb magic,toggle]

------------------------------------------------------------------------------------------------

# Overseer Check

Obj_OgreMCP:PasteButton[Overseer_CheckQuests,Overseer]

------------------------------------------------------------------------------------------------

# Move Behind Toggle On and Off

Obj_OgreMCP:PasteButton[Uplinkoption_change,Front,IRWBN:${Me.Name},checkbox_settings_movebehind,toggle]

------------------------------------------------------------------------------------------------

# Tinker to Me

Obj_OgreMCP:PasteButton[UseItem..,Tinker to Me,All,Call of the tinker]

------------------------------------------------------------------------------------------------

# Use Hunter's Neck

Obj_OgreMCP:PasteButton[UseItem..,H-Neck,All,Skyshrine Hunter's Medallion,All,Frost Hunter's Medallion]

------------------------------------------------------------------------------------------------

# Invis After Combat Toggle On and Off (Used for smuggling)

Obj_OgreMCP:PasteButton[Uplinkoption_change,InvisON,all,checkbox_settings_cancelinvisaftercombat,toggle]

------------------------------------------------------------------------------------------------

# Use Totem

Obj_OgreMCP:PasteButton[UseItem..,TotemOfQ,all,Totem of Quickness]

------------------------------------------------------------------------------------------------

# SETUPFOR

Obj_OgreMCP:PasteButton[ChangeOgreBotUIOption,CS / Setup,igw:${Me.Name},checkbox_settings_movetoarea,TRUE,-campspot,igw:${Me.Name},-SetUpFor,igw:${Me.Name}]

------------------------------------------------------------------------------------------------

# Mug of Fulfillment

Obj_OgreMCP:PasteButton[Apply_Verb,Mug,Mug of Fulfillment,use]

------------------------------------------------------------------------------------------------

# Skyshrine Banner

Obj_OgreMCP:PasteButton[Apply_Verb,SS Banner,Pennant of Skyshrine Loyalty,Return to Skyshrine]

------------------------------------------------------------------------------------------------

# Logs Out

Obj_OgreMCP:PasteButton[Camp,Camp]

------------------------------------------------------------------------------------------------

# Re-Kindle Heartbound

Obj_OgreMCP:PasteButton[Heartstone_RekindleBond,Rekindle]

------------------------------------------------------------------------------------------------

# Resume Replacement (Shares Missions)

Obj_OgreMCP:PasteButton[OgreConsoleCommand,Resume,-Resume,-ShareAllMissions,crusader,-ShareAllMissions,brawler,-ShareAllMissions,warrior,-ShareAllMissions,cleric,-ShareAllMissions,shaman,-ShareAllMissions,druid,-ShareAllMissions,enchanter,-ShareAllMissions,sorcerer,-ShareAllMissions,summoner,-ShareAllMissions,bard,-ShareAllMissions,rogue,-ShareAllMissions,predator]

------------------------------------------------------------------------------------------------