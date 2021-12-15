# GOTWIC AC Bot
This Discord bot helps with rally timings in the AC event.

# Installation
* [Click here](https://discord.com/api/oauth2/authorize?client_id=812358480392224778&permissions=11264&scope=bot) to add this bot to your Discord server
* This bot also replies to DMs

# Main commands
*/ac_register (only for rally leaders)

Register yourself with your X and Y coords, and your marching speed percentage. The bot will remember you for the rest of the match.

*/ac_rally (only for marquis)

Computes rally timing for every registered rally leader. The bot will return every rally leaders' timing for the selected building.

## /ac_countdown (only for marquis)

Starts / stops the voice countdown. The bot will connect to your voice channel and do a countdown (the countdown starts 10s before the slowest rally leader). Rally leaders will have to manually click on the "Attack now" button when they hear their timing.

## /ac_map

Shows / updates the AC map. The bot will return the AC map with the formations in each building.

## /ac_reset (only for marquis)

Resets the rally leader list and disconnects the bot from the voice channel. Use this command before every match to start a new list of rally leaders.

# Secondary commands
## /ac_list

List of registered rally leaders.

## /ac_addplayer (only for marquis)

Adds 1 rally leader to the list. Use this command to register someone who does not have the rally leader role, or someone who struggles to register themself.

## /ac_deleteplayer (only for marquis)

Deletes 1 rally leader from the list.


















