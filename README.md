# GOTWIC AC Bot
This Discord bot helps with rally timings in the AC event.

If you already know how to time your rallies properly then this bot will automate the process, and also improve the timing even more.
If you still struggle with rally timings then this bot will solve all your problems and you will greatly improve your performances in AC.

The bot is very easy to use, as it is fully integrated within Discord thanks to Slash Commands.
Its precision is ±1s (2s window) which is way better than any other alliance (most people don't like to admit that their timing is around ±3s (6s window) at best.

It is a Discord bot, which means that it stays on Discord. It can only send messages, mention everyone (with @), connect to a voice channel, and speak. It cannot see your game, it cannot click for you, it cannot modify the game files, ...

# Main commands
* /ac_register (only for rally leaders)

Register yourself with your X and Y coords, and your marching speed percentage. The bot will remember you for the rest of the match.

* /ac_rally (only for marquis)

Computes rally timing for every registered rally leader. The bot will return every rally leaders' timing for the selected building. The /ac_countdown command is now ready.

* /ac_countdown (only for marquis)

Starts / stops the voice countdown. The bot will connect to your voice channel and do a countdown based on the last /ac_rally command (the countdown starts 10s before the slowest rally leader). Rally leaders will have to manually click on the "Attack now" button when they hear their timing.

* /ac_map

Shows / updates the AC map. The bot will return the AC map with the formations in each building.

* /ac_reset (only for marquis)

Resets the rally leader list and disconnects the bot from the voice channel. Use this command before every match to start a new list of rally leaders.

# Secondary commands
* /ac_list

List of registered rally leaders.

* /ac_addplayer (only for marquis)

Adds 1 rally leader to the list. Use this command to register someone who does not have the rally leader role, or someone who struggles to register themself.

* /ac_deleteplayer (only for marquis)

Deletes 1 rally leader from the list.

# Installation
* [Click here](https://discord.com/api/oauth2/authorize?client_id=864522986995843113&permissions=3278848&scope=bot%20applications.commands) to add this bot to your Discord server
* You have to contact me before using it, to set it up (permissions, voice channel, troop type)

# Set up
I will need:
0. Go to your account Setting, Advanced, Enable Developer Mode
1. Name of your Discord server (case sensitive)
2. ID of your Discord server (right click on your server's name, Copy ID)
3. ID of the Marquis role (right click on the Marquis role, COPY ID)
4. ID of the Rally Leader role (right click on the Marquis role, COPY ID) (Pass this step if you don't have that role)
5. ID of the Member role (right click on the Member role, COPY ID)
6. ID of the voice channel you are going to use during AC (right click on the voice channel, COPY ID)
7. The troop type you are going to use in the rally (the bot only works if all the rally leaders use the same troop type)

## Contact
To install the bot on your server, or for any idea, suggestion, fix, etc., please contact me on Discord (Siropalafraise#3862) or in the game (Sirop)


















