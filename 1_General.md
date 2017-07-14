---
title: Mew - General
permalink: mew/general.html
---

# General Tab
This tab contains all the miscellaneous settings.

## Waiting Aetheryte :
Enable/Disable the use of the waiting Aetheryte (list below).

### Aetheryte list :
Where do you want it to wait.
			
### Use Aetheryte idyllshire :
Enable/Disable the use of Idyllshire Aetheryte for going in the Hinterlands, if disable it'll move to the exit by it's own.
			
### Use House Codechunk:
Enable/Disable the use of custom teleport codechunck, usefull if you have a private house and an apartment/friend's house in the same zone.
To get the three parameters (Zone ID, Aetheryte Id and Index) you need to run this code below using RebornConsole (in your plugins list) : 
```csharp
foreach(WorldManager.TeleportLocation location in WorldManager.AvailableLocations){
		Log("Name : {0} | Zone ID : {1} | Aetheryte ID : {2} | Index : {3}",location.Name, location.ZoneId,location.AetheryteId, WorldManager.AvailableLocations.IndexOf(location));
}
```			
## Items Settings 			
### Food List :
Wich food you want to use, if you want to use one.
			
### Manual List :
Wich manual you want to use, if you want to use one.
		
## Gear Set
### Miner :
You Miner gear set number.
			
### Botanist :
You Botanist gear set number.
			
### Fisher :
You Fisher gear set number.
		
## Turn In
### Enable Turn In :
If enable it'll try to turn in your collectable items for scrips based on Minimum Free Slot setting.
			
### Enable Turn In Counterfoil :
If enable it'll try to turn in your collectable items (Adamantite/Chysahl) for counterfoils based on Minimum Free Slot setting.
			
### Minimum Free Slot :
Set the minimum free slots amount to start Turn In. For instance, if set to 140 it'll always try to turn in because you'll always have less than 100 free slot, with 20 it'll only go turn in when you have less than 20 free slots. The security limit is 5 so even if you set less than five it'll act as it was 5.
		
## Mew Key
***Key*** : Put here the key. Make sure to not have a space at the end.

***Refresh Button*** : Use it to test your key. The first try should "always" fail because the login isn't instant as it require a response from the login server.
		
## Buttons
### Import Settings :
Use this button to import previous settings (JSON file), you can also import settings from others but make sure to check your gear set.
			
### Export Settings :
Use this button to export your current settings (JSON file).
			
### Start :
Use this button to start Mew, it'll generate a xml profile based on what's set in the UI, switch to orderbot, (try to) load the profile and start it.

If you have any issue when Starting Mew, please send me the log in Discord. Most of the time, if it doesn't start it's because you don't have my own ExBuddy's fork (properly) installed.
			
### Reset Mew :
Use this button to reset all Mew's settings but the ones in the General Tab.
			
### Reset General :
Use this button to reset the General tab's settings.
		
