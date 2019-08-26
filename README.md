## traps menu
screenshot of the menu.
https://steamuserimages-a.akamaihd.net/ugc/777353875114630524/E367DD3FB64713284922EDA9D920AFAE3CDBACE4/

//INSTALL INSTRUCTIONS

	
	1st. Place tmenu inside custom folder. If not create one or place wherever you wish.
	2nd. Place this code inside of keyboard.sqf  if (_dikCode == 0xB8) then {	[] execVM "custom\tmenu\scripts\OM.sqf";	}; . 
	3rd. Open description.ext at the bottom place #include "custom\tmenu\Defines.hpp" then under that place #include             "custom\tmenu\dialog.hpp" .
	4th. Now place TView = compile preprocessFileLineNumbers "custom\tmenu\scripts\viewDistance.sqf"; inside dayz_code\init\compiles.sqf  `   after the if (!isDedicated) then { section.
	5th. copy the .paa files from GUI folder and place it in dayz_code\Gui
	5th. Now you are done.. Change the rules and what not in scripts\OM.sqf and viewdistance if you want.
	
	if you have any trouble add me on steam @ https://steamcommunity.com/id/Trapxxgods/
	or on discord @ Trapxxgods#3949
