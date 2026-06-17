DayZ Modular Loot System Files XML Mod Changelog & Terms Of Use

This batch created 230526.

These files and code snippets are offered for use as a BETA playtest. They may contain mistakes that cause errors on your server.

These XML files will make various changes to your Community Server, without editing the vanilla files:

-------------------------------------

Most items spawn pristine and undamaged.

5 Second login / logout.

8 hour server restarts with warning message.

Complete Vehicles with loot.

More Vehicles.

More Weapons.(Not Sakhal).

Weapons will spawn with attachments & mags.

Full Mags.

More Mags. (Not Sakhal).

More Boxed Ammo, Less Loose Ammo. (Not Sakhal).

More Food. (Not Sakhal).

More Drinks. (Not Sakhal).

More Meds. (Not Sakal).

More Tools & Building Supplies. (Not Sakhal).

All flags spawn, but only one of each. (Not Sakhal).

-------------------------------------

This is scalespeeder gamings modular loot / CLE modding system, which is designed to be update independant, simple to install  and highly customizable.

Limited Testing on PC Chernarus Local Server DAYZ  Version 1.29 May 2026.

Designed to work with PC, PlayStation & Xbox DayZ Community Servers.

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml files could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded xml files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

-----------------------

PLEASE READ THE INSTRUCTIONS ON HOW TO INSTALL THESE FILES

To download the files from Github click the green "code" button, then "download zip" then extract the files to your local PC.

-----------------------

Stop your server.

On console you already have a "custom" folder inside the mission folder on your server. ON PC YOU MUST MAKE ONE, eg: mpmissions\dayzOffline.chernarusplus\custom

Now upload the ALL the files from the Github / Mega.

Don't worry that you're getting files you don't need, they're small text files and don't take up much space.

Next open up your vanilla cfgeconomycore.xml, and near the bottom, above the closing

</economycore>

tag,

paste this on a Chernarus Server:

	<ce folder="custom">
	
	<file name="admin-server-restart-and-message-messages.xml" type="messages" />
	<file name="admin-short-login-pristine-items-globals.xml" type="globals" />

	<file name="flags-edited-types.xml" type="types" />
	
	<file name="food-chernarus-more-food-and-drinks-types.xml" type="types" />
	
	<file name="meds-boosted-types.xml" type="types" />
	
	<file name="tools-boosted-misc-types.xml" type="types" />
	
	<file name="guns-complete-pristine-spawnabletypes.xml" type="spawnabletypes" />
	<file name="guns-chernarus-boosted-full-mags-types.xml" type="types" />
	<file name="guns-chernarus-boosted-box-ammo-less-loose-types.xml" type="types" />
	<file name="guns-boosted-chernarus-types.xml" type="types" /><!--use with caution may cause errors-->
	
	<file name="Veh-Truck_01_Covered-complete-building-supplies-cfgspawnabletypes.xml" type="spawnabletypes" />
   	<file name="Veh-Truck_01_Covered_Blue-complete-building-supplies-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Truck_01_Covered_Orange-complete-building-supplies-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-CivilianSedan-complete-with-FRod-cfgspawnabletypes.xml" type="spawnabletypes" />
   	<file name="Veh-Sedan_02-complete-with-Farming-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-OffroadHatchback-complete-with-M4A1-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Hatchback_02-complete-with-Hunting-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Boat_01-complete-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Offroad_02-complete-with-weapons-cfgspawnabletypes.xml" type="spawnabletypes" />
	
	<file name="veh-more-VehicleBoat-events.xml" type="events" />
	<file name="veh-more-VehicleCivilianSedan-events.xml" type="events" />
	<file name="veh-more-VehicleHatchback02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroad02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroadHatchback-events.xml" type="events" />
	<file name="veh-more-VehicleSedan02-events.xml" type="events" />
	<file name="veh-more-VehicleTruck01-events.xml" type="events" />
	</ce>
	
or this for a Livonia / Enoch Server:

	<ce folder="custom">
	
	<file name="admin-server-restart-and-message-messages.xml" type="messages" />
	<file name="admin-short-login-pristine-items-globals.xml" type="globals" />

	<file name="flags-edited-types.xml" type="types" />
	
	<file name="food-livonia-more-food-and-drinks-types.xml" type="types" />
	
	<file name="meds-boosted-types.xml" type="types" />
	
	<file name="tools-boosted-misc-types.xml" type="types" />
	
	<file name="guns-complete-pristine-spawnabletypes.xml" type="spawnabletypes" />
	<file name="guns-livonia-enoch-boosted-full-mags-types.xml" type="types" />
	<file name="guns-livonia-boosted-box-ammo-less-loose-types.xml" type="types" />
	<file name="guns-boosted-livonia-types.xml" type="types" /><!--use with caution may cause errors-->
	
	<file name="Veh-Truck_01_Covered-complete-building-supplies-cfgspawnabletypes.xml" type="spawnabletypes" />
   	<file name="Veh-Truck_01_Covered_Blue-complete-building-supplies-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Truck_01_Covered_Orange-complete-building-supplies-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-CivilianSedan-complete-with-FRod-cfgspawnabletypes.xml" type="spawnabletypes" />
   	<file name="Veh-Sedan_02-complete-with-Farming-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-OffroadHatchback-complete-with-M4A1-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Hatchback_02-complete-with-Hunting-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Boat_01-complete-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Offroad_02-complete-with-weapons-cfgspawnabletypes.xml" type="spawnabletypes" />
	
	<file name="veh-more-VehicleCivilianSedan-events.xml" type="events" />
	<file name="veh-more-VehicleHatchback02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroad02-events.xml" type="events" />
	<file name="veh-more-VehicleOffroadHatchback-events.xml" type="events" />
	<file name="veh-more-VehicleSedan02-events.xml" type="events" />
	<file name="veh-more-VehicleTruck01-events.xml" type="events" />	
	
	</ce>
	
or this for a Sakhal Server:

<ce folder="custom">
		
	<file name="admin-server-restart-and-message-messages.xml" type="messages" />
	<file name="admin-short-login-pristine-items-globals.xml" type="globals" />
	
	<file name="guns-complete-pristine-spawnabletypes.xml" type="spawnabletypes" />
	<file name="guns-sakhal-full-mags-types.xml" type="types" />
	
	<file name="Veh-Truck_01_Covered-complete-building-supplies-cfgspawnabletypes.xml" type="spawnabletypes" />
   	<file name="Veh-Truck_01_Covered_Blue-complete-building-supplies-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Truck_01_Covered_Orange-complete-building-supplies-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-CivilianSedan-complete-with-FRod-cfgspawnabletypes.xml" type="spawnabletypes" />
   	<file name="Veh-Sedan_02-complete-with-Farming-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-OffroadHatchback-complete-with-M4A1-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Hatchback_02-complete-with-Hunting-cfgspawnabletypes.xml" type="spawnabletypes" />
	<file name="Veh-Boat_01-complete-cfgspawnabletypes.xml" type="spawnabletypes" />

	<file name="veh-more-VehicleBoat-events.xml" type="events" />
	<file name="veh-more-VehicleCivilianSedan-events.xml" type="events" />
	<file name="veh-more-VehicleHatchback02-events.xml" type="events" />
	<file name="veh-more-VehicleMilitaryBoat-events.xml" type="events" />
	<file name="veh-more-VehicleOffroadHatchback-events.xml" type="events" />
	<file name="veh-more-VehicleSedan02-events.xml" type="events" />
	<file name="veh-more-VehicleTruck01-events.xml" type="events" />	
	
	</ce>

Save the file.

Upload where necessary.

If you don't want to use a particular file, simple delete the relevant line or comment it out with <!-- at the beggining and --> at the end.

If you want the options to have complete vehicles but no loot, see the relevent tutorials at https://www.youtube.com/playlist?list=PL_QA4GNmiCzdl82RIOZvdFveq5_bDBrPY
	
Vailidate your edited files to check you haven't made any mistakes with https://www.xmlvalidation.com/

Restart your server & changes should start to take effect. How quickly will depend on the population of your server.

----------

Dominus vobiscum! scalespeeder

GOOD LUCK!
