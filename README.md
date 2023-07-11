# dunui party tools
Targeting and party coordination tools for the MUD text game Achaea. All party communication is read over GMCP, to be more resistant to illusions.

All of the aliases below are the *default* values. These can be customized any time - see the directions in the Aliases script (under CONFIG - CHANGE VALUES HERE)

###################################################################

Basic aliases to know:

dpt add \<person\> - add a new target to the list

dpt addcity \<city\> - Uses QW for the city specified and adds all citizens of that city to your target list

dpt remove \<person\> - remove a target from the list

dpt show - show all targets, with links to move targets up, down, or remove from the list

dpt up \<person\> - Move a target higher in the list

dpt down \<person\> - Move a target lower in the list

dpt send - Send your target list, in order, to the party **

dptnr - Select the highest priority target who is in the room with you

dptn - Select the next target in the priority list regardless whether they are in the room
  
  
** When a party leader (see below) uses htrelay, everyone else in the group using Hashan Tools receives a message they can click on to import all targets to match the leader
  
###################################################################

Party leader aliases:
  
dpt leaders add \<person\> - Add a party leader

dpt leaders remove \<person\> - Remove a party leader

dpt leaders show - Show party leaders
  
###################################################################
  
Affliction Sharing

This should work right out of the gate if you have AK installed. Make sure the Hashan Tools package is installed after AK in the package list. Any time AK detects a new affliction on your target, you will send it to the party with a message like:

(Party): Dunui says, "Hhaos hit with Anorexia"
  
If other party members enable sharing, AK will automatically be updated with afflictions they share using this same format.
  
###################################################################
  
Other Configuration

See the CONFIG - CHANGE VALUES HERE file for configuration options, including functions or aliases you use to set or get your current target.
