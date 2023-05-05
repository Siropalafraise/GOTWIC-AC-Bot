# GOTWIC AC Bot

This Discord bot will help your team in the AC event. It can time rallies with a precision of ±1s and predict races.\
It is very easy to use, as it is fully integrated within Discord.

# Main commands

* /ac_addplayer

The bot will register the selected player with their X and Y coordinates, their solo marching speed percentage, their rally marching speed percentage, the troop speed they are going to use in their rally, and their strongest troop type.\
The bot will return the information that you just gave it.\
The bot will return predictions for racing.

* /ac_rally

The bot will return a list of rally timings for every registered player for the selected building.\
The /ac_countdown command is now ready.

* /ac_countdown

The bot will start (or stop) the voice countdown, based on the last /ac_rally command.\
Players will have to manually click on the "Attack now" button when they hear their timing.

* /ac_list

The bot will return the list of registered players.

* /ac_racingtiles

The bot will return a list of the best coordinates for racing, according to your marching speed and the buildings that you want to capture.\
Players will have to register to know which troop type is associated with which colour.

# Secondary commands

* /ac_deleteplayer

The bot will remove the selected player from the list.

* /ac_map

The bot will show/update the AC map with the formation in each building.

* /ac_reset

The bot will reset the list of players.\
The bot will reset the map.\
The bot will disconnect from the voice channel.

# Use during a match

* Entrance phase

The bot manager uses /ac_reset to clear data from the past.\
Racers choose their coordinates using /ac_racingtiles.\
Rally leaders register with /ac_addplayer.\
The bot manager uses /ac_list to make sure that everyone is correctly registered.

* Match phase

The bot manager uses /ac_rally before every rally.\
The bot manager uses /ac_countdown to launch the countdown.\
The bot manager uses /ac_map to inform everyone which troop type is needed in which building.

# Installation

[Click here](https://discord.com/api/oauth2/authorize?client_id=864522986995843113&permissions=3278848&scope=applications.commands%20bot) to add the bot to your Discord server.\
After inviting the bot in your Discord server, you will have to send me your Discord server's ID. If you don't know how to get it, simply use any command and the bot will give it to you.

# Image gallery

Coming soon...

# Contact
To install the bot on your server, or for any question, please contact me :
* https://discord.gg/cNbNvn88ky
* Siropalafraise#3862 on Discord
