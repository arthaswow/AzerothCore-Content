--[[
-- ############################################################################################################# --
-- 
--  ____    __                                         ______  __              ____                    __      
-- /\  _`\ /\ \__                  __                 /\__  _\/\ \            /\  _`\                 /\ \__   
-- \ \,\L\_\ \ ,_\  __  __     __ /\_\     __      ___\/_/\ \/\ \ \___      __\ \ \L\ \     __    ____\ \ ,_\  
--  \/_\__ \\ \ \/ /\ \/\ \  /'_ `\/\ \  /'__`\  /' _ `\ \ \ \ \ \  _ `\  /'__`\ \  _ <'  /'__`\ /',__\\ \ \/  
--    /\ \L\ \ \ \_\ \ \_\ \/\ \L\ \ \ \/\ \L\.\_/\ \/\ \ \ \ \ \ \ \ \ \/\  __/\ \ \L\ \/\  __//\__, `\\ \ \_ 
--    \ `\____\ \__\\/`____ \ \____ \ \_\ \__/.\_\ \_\ \_\ \ \_\ \ \_\ \_\ \____\\ \____/\ \____\/\____/ \ \__\
--     \/_____/\/__/ `/___/> \/___L\ \/_/\/__/\/_/\/_/\/_/  \/_/  \/_/\/_/\/____/ \/___/  \/____/\/___/   \/__/
--                     /\___/ /\____/                                                                         
--                     \/__/  \_/__/               http://stygianthebest.github.io                                                    
--
-- ############################################################################################################# --
--
-- 	Random Custom Login Screens for World of Warcraft game client v3.3.5a
-- 	By StygianTheBest
--
--	Thanks to Rochet2 for the tips and the Arcadia login screen image and audio.
--	
-- 	Here are several login custom login screens I created with custom music. A random screen will be chosen each 
--	time you launch WoW. You can adjust how often a specific screen appears by editing the random value range. I
--	currenly have Conan's Crypt loading 60% of the time because it's my favorite. If you want one screen to show
--	every time, just set the rand = X where X is a number in the range of the screen you want.
--
--	You will need to adjust the IP Address to your private server in the LoginUI.lua file.
--	
--	The visual FX are mapped based on the screen resolution, so they may need to be tweaked. This can be done by 
--	editing X,Y,Z,O coordinates for each object. I have included a sample file for 1024x768 resolution as well.
-- 
-- 			    Scale	X	Y	Z	Orientation		Model
--	ex: CreateModelFrame(0.05, 	3.17,	1.00,	0.00,	0.00, 			"Spells\\Archimonde_fire.m2")
-- ############################################################################################################# --
]]--