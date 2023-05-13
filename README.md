# hashantools
Targeting and party coordination tools for the MUD text game Achaea. All party communication is read over GMCP, to be more resistant to illusions.

###################################################################

Basic aliases to know:

htadd <person> - add a new target to the list
htaddcity <city> - Uses QW for the city specified and adds all citizens of that city to your target list
htremove <person> - remove a target from the list
htshow - show all targets, with links to move targets up, down, or remove from the list
htup <person> - Move a target higher in the list
htdown <person> - Move a target lower in the list
htrelay - Send your target list, in order, to the party **
htn - Select the next target in your priority list who is in the room with you
  
** When a party leader (see below) uses htrelay, everyone else in the group using Hashan Tools receives a message they can click on to import all targets to match the leader
  
###################################################################

Party leader aliases:
  
htlead <person> - Add a party leader
htlead remove <person> - Remove a party leader
htlead show - Show party leaders
  
###################################################################
  
Affliction Sharing

This should work right out of the gate if you have AK installed. Make sure the Hashan Tools package is installed after AK in the package list. Any time AK detects a new affliction on your target, you will send it to the party with a message like:

(Party): Dunui says, "Hhaos hit with Anorexia"
  
If other party members enable sharing, AK will automatically be updated with afflictions they share using this same format.
  
###################################################################
  
Other Configuration

See the CONFIG - CHANGE VALUES HERE file for configuration options, including functions or aliases you use to set or get your current target.
