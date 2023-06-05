# Round_Avatar

Installation:

Download "Round_Avatar" in addons.

Usage example:

local Panel = vgui.Create( "DFrame" ) 
Panel:SetPos( 200, 200 ) 
Panel:SetSize( 500, 500 ) 
Panel:SetTitle( "Avatar Test" ) 
Panel:MakePopup() 

local Avatar = vgui.Create( "AvatarMask", Panel ) 
Avatar:SetSize( 64, 64 ) 
Avatar:SetPos( 4, 30 ) 
Avatar:SetPlayer( LocalPlayer(), 64 ) 
