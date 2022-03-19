# GOTWIC AC Bot
This Discord bot helps with rally timings in the AC event.

If you already know how to time your rallies properly then this bot will automate the process, and also improve the timing even more.
If you still struggle with rally timings then this bot will solve all your problems and you will greatly improve your performances in AC.

The bot is very easy to use, as it is fully integrated within Discord thanks to Slash Commands.
Its precision is ±1s (2s window) which is way better than any other alliances (most people don't like to admit that their timing is around ±3s (6s window) at best). Proofs in the RallyTimings.xlsx file, with timings of 274 rallies.

It is a Discord bot, which means that it stays on Discord. It can only send messages, mention everyone (with @), connect to a voice channel, and speak. It cannot see your game, it cannot click for you, it cannot modify the game files, ...

# Main commands
* /ac_register (only for rally leaders)

Register yourself with your X and Y coords, and your marching speed percentage. The bot will remember you for the rest of the match.

![/ac_register](https://i.imgur.com/BKCOLm5.png)

* /ac_rally (only for marquis)

Computes rally timing for every registered rally leader with the right marching speed bonus. The bot will return every rally leaders' timing for the selected building. The /ac_countdown command is now ready.

![/ac_rally_1](https://i.imgur.com/kS2GcMC.png)
![/ac_rally_2](https://i.imgur.com/HDujSmq.png)
![/ac_rally_3](https://i.imgur.com/UBCcKT2.png)

* /ac_countdown (only for marquis)

Starts / stops the voice countdown. The bot will connect to your voice channel and do a countdown based on the last /ac_rally command (the countdown starts 10s before the slowest rally leader). Rally leaders will have to manually click on the "Attack now" button when they hear their timing.

![/ac_countdown_1](https://i.imgur.com/EOxrWNL.png)
![/ac_countdown_2](https://i.imgur.com/Fzb5tlm.png)

* /ac_map

Shows / updates the AC map. The bot will return the AC map with the formations in each building.

![/ac_map](https://i.imgur.com/J2bfyem.png)

* /ac_reset (only for marquis)

Resets the rally leader list and disconnects the bot from the voice channel. Use this command before every match to start a new list of rally leaders.

![/ac_reset](https://i.imgur.com/ld8Ls9R.png)

# Secondary commands
* /ac_list

List of registered rally leaders.

* /ac_addplayer (only for marquis)

Adds 1 rally leader to the list. Use this command to register someone who does not have the rally leader role, or someone who struggles to register themself.

* /ac_deleteplayer (only for marquis)

Deletes 1 rally leader from the list.

# Installation
[Click here](https://discord.com/api/oauth2/authorize?client_id=864522986995843113&permissions=3278848&scope=bot%20applications.commands) to add this bot to your Discord server.

After inviting the bot in your Discord server, you will have to contact me for the set up process. I will need:

0. Go to your account Setting, Advanced, Enable Developer Mode
1. Name of your Discord server (case sensitive)
2. ID of your Discord server (right click on your server's name, Copy ID)
3. ID of the Marquis role (right click on the Marquis role, COPY ID)
4. ID of the Rally Leader role (right click on the Rally Leader role, COPY ID) (Pass this step if you don't have that role)
5. ID of the Member role (right click on the Member role, COPY ID)
6. ID of the voice channel you are going to use during AC (right click on the voice channel, COPY ID)
7. The troop type you are going to use in the rally (the bot only works if all the rally leaders use the same troop type)

After setting up the bot, you will need to test it to make sure everything works fine:
1. Register yourself with fake info (ex: X = 25, Y = 65, % = 150.50)
2. Add another player with fake info (ex: The bot, X = 15, Y = 68, % = 125%)
3. Display the list of registered players
4. Rally a building
5. Start the countdown (make sure it starts 10s before the slowest player with the highest timing)
6. Display the AC map
7. Reset the list

# Miscellaneous
It's still experimental, it worked well in the last 2 seasons (S9 and S10) so it should still work but you never know.

It will be disabled if you match up against my alliance.

I'm giving it for free for now but my goal is to make some money out of it, not much but a few $, not sure when.

If you play events at GMT 19 (or 7 or 13 during weekends), then you can contact me for debug during the event, but be ready to do it "the good old way" just in case, as a plan B.

Image gallery : https://imgur.com/a/qqesviL

# Contact
To install the bot on your server, or for any question, please contact me :
* https://discord.gg/cNbNvn88ky
* Siropalafraise#3862 on Discord
* Sirop in game


















