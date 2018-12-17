![Shiro](https://i.imgur.com/0zGSqDL.png)
![Info](https://img.shields.io/badge/Lib-Discord.js-blue.svg)
![Info2](https://img.shields.io/badge/DB-MongoDB-blue.svg)
![Guilds](https://img.shields.io/badge/Guilds-12-green.svg)
![license](https://img.shields.io/badge/License-Mozilla%20Public%20License%202.0-green.svg)

***
**►** [**Invite Link**](https://goo.gl/KbFYzT)

**►** [**Support Server**](https://discord.gg/ypEBGHB)
***
## Documentation
### Commands
##### Moderation
* **\>ban \<member\> [reason]**
  > Bans the specified member for an optional reason
* **\>kick \<member\> [reason]**
  > Kicks the specified member for an optional reason
* **\>mute \<member\> [time] [reason]**
  > Mutes the specified member by creating (if it doesnt exist) and assigning the *@Muted* role, optional time in minutes, optional reason
* **\>prune \<number\>**
  > Bulk deletes a number of messages (max. 100). Aliases: *purge*, *clear*
* **\>warn \<member\> [reason]**
  > Warns the mentioned member [reason optional]
* **\>report \<members\> [reason]**
   > Reports the mentioned members to the server owner [reason optional]
   
   > *For supporters only*
##### Information
* **\>help**
  > Shows all commands
* **\>setup**
  > Shows all server configuring commands
* **\>settings**
  > Shows an overview of the server's enabled or disabled settings. *note: certain functions are toggled off by default*
* **\>serverinfo**
  > Returns information related to the server: Icon, Onwer, Region, Member Count, Emoji Count, Text, Voice Channels and Roles
* **\>userinfo [member]**
  > Returns information related to a user: Icon, Full Name, ID, Status, Presence, Join Date, Account Creation Date and Roles
* **\>botstatus**
  > Returns information related to the bot: Icon, Owner, Language, Ping, Api Ping Time, Bot Uptime, System Uptime, System Info and useful links
* **\>changelog**
  > Returns information about the bot version
* **\>invite**
  > Returns the bot's invite link
##### Reactions (400+ unique gifs)
* **\> kiss, hug, pat, lick, tickle, bite, poke, pinch, slap, blush, mad, scared, tired, cry, run, nervous**
##### Games
* **\>say \<text\>**
  > Deletes the original message and then returns its contents
* **\>embed [text]**
  > Embeds the text into a cute embed
* **\>dice**
  > Rolls the dice, pretty straightforward
* **\>8ball \<text\>**
  > Emulates the 8ball game
* **\>team \<text\> \<text\> \<text\>....**
  > Returns an embed seperating the arguments randomly into 2 teams
* **\>ship \<arg1\> \<arg2\>**
  > Returns how compatible 2 people are with each other, 2 arguments should be given only for it to work properly and they can be mentions too
* **\>rps \<rock or paper or scissors\>**
  > Emulates a rock, paper, scissors game with the bot
##### Fun
* **\>movie \<movie name\>**
  > Returns information about a movie taken from the OMDB Api \nReturned Info: Title, Release date, Runtime, Genre, Director, Writer, Plot/Summary, Imdb rating, Type
* **\>urban \<word or phrase\>**
  > Returns information about a word or phrase taken from Urban Dictionary\nReturned Info: Definition, Author, Upvotes & Downvotes and an example. Aliases: *ud*
* **\>weather \<city or area\>**
  > Returns weather information for the specified city or area\nReturned Info: What the weather looks like, Date, Timezone, Temperature, Humidity, Wind and obervation point
* **\>fortnite \<platform\> [username]**
  > Returns fortnite stats for the specified user on the specified platform(*pc*, *xbox*, *ps4*)\nReturned Info: Solo/Duo/Squad Wins, Kd, Matches Played, Kills
* **\>itunes  \<type\> \<item\>**
  > Returns information from iTunes about a product. Types are: *music*, *movie*, *podcast*, *audiobook*, *ebook*, *software*, *all*. Term *all* will return 10 results with that correspond to the *name* regardless of their category
* **\> dog, shibe, cat, bird, fox, lizard**
  > Fetches animals pictures
* **\> chuckjoke, punchjoke, mamajoke, dadjoke**
  > Returns jokes, easy right?
* **\>comic**
  > Fetches a random comic
* **\>react**
  > Returns a gif depending on the specified reaction (*yes*, *no*, *maybe*)
* **\>fakeid**
  > Returns an embed containing fake user infomation (*Name*, *Gender*, *Age*, *Region*, *Phone number*, *Email*, *Password*)
* **\>advice**
  > Returns random advice
* **\> dogfact, catfact**
  > Returns a random fact, that's all
* **\>insult**
  > Returns a random fancy insult. Try not to offend anyone
* **\>size [member]**
  > Returns the size of your pickle ( ͡° ͜ʖ ͡°) 100% accuracy. Aliases: *pickle*
* **\>randomcolor**
  > Returns an embed with information about a randomly generated color. Aliases: *rc*
##### Nsfw
* **\>rule34 \<tag\>, yandere \<tag\>, danbooru \<tag\>, gelbooru \<tag\>, xbooru \<tag\>, realbooru \<tag\>, plot**
  > Fetches a random (nsfw) picture, provide only one tag for more accurate results. Aliases: *34*, *yan*, *dan*, *gel*, *xb*, *rb*
## Server Configuring/Settings
* **\>setmodlog \<channel name or id\>**
  > Sets the channel in which the bot will log: Bans, Unbans, Kicks, Mutes, Unmutes, Warns, Filtered Words Warns, Filtered server invites and links. Aliases: *smod*
* **\>disablemodlog**
  > Completely disable the moderation logging, channel has to be reassigned to enable it back (*>setmodlog \<channel id\>*)
  Aliases: *dmod*
* **\>setchatlog \<channel name or id\>**
  > Set the channel in which the bot will log: Deleted, Edited Messages and Bulk Deletions. Aliases: *schat*
* **\>disablechatlog**
  > Completely disable the chat logging, channel has to be reassigned to enable it back (*>setchatlog \<channel id\>*)
  Aliases: *dchat*
* **\>setchangelog \<channel name or id\>**
  > Set the channel in which the bot will log: Name, Nickname, Channel, Emoji, Role changes. Aliases: *schange*
* **\>disablechangelog**
  > Completely disable the change logging, channel has to be reassigned to enable it back (*>setchangelog \<channel id\>*)
  Aliases: *dchange*
***
* **\>filter**
  > Toggle chat filtering on or off
* **\>filteradd \<word\>**
  > Add a word to the bad word list (max 10 words, for supporters the limit is 20 words). Aliases: *fa*
* **\>filterremove \<word\>**
  > Remove a word from the bad word list. Aliases: *fr*
* **\>filterlist**
  > See all the bad words set to be filtered. Aliases: *fl*
***
* **\>blockinvites**
  > Toggle server invite deletion on or off. Aliases: *bi*
* **\>blocklinks**
  > Toggle link deletion on or off. Aliases: *bl*
* **\>mentionlimit \<number\>**
  > Set the max mentions a message is allowed to have (*\>mentionlimit 0* to disable). Aliases: *ml
***
* **\>joinmessage**
  > Toggle welcome messages on or off. Aliases: *jm*
* **\>setjoinchannel \<channel name or id\>**
  > Set the channel in which the bot will welcome new members. Aliases: *sjc*
* **\>setjoinmessage \<text\>**
  > Set the message that will displayed when a member joins the server. Aliases: *sjm*
  > 
  > You can add (*--mention, --username, --id, --created*) in the message. When the the message will get sent they will be replaced by the new member's *tag*, *username* + *discriminator*, *id*, and *date* that their account was created
  > 
  > eg. *>setjoinmessage Welcome --mention to the server (--id)*
* **\>leavemessage**
  > Toggle leave messages on or off. Aliases: *lm*
* **\>setleavechannel \channel name or id\>**
  > Set the channel in which the bot will send a message when a member leaves. Aliases: *slc*
* **\>setleavemessage \<text\>**
  > Set the message that will displayed when a member leaves the server. Aliases: *slm*
  > 
  > You can add (*--username, --id, --created*) in the message. When the the message will get sent they will be replaced by the member's *username* + *discriminator*, *id*, and *date* that their account was created
  > 
  > eg. *>setleavemessage Sad to see you go --username*
***
* **\>autorole**
  > Toggle autorole function on or off. Autorole is the role that a members receives when they join the server
* **\>autoroleadd \<role name or id\>**
  > Add a role to the autorole list (max 1 roles, for supporters the limit is 10 roles). Aliases: *ara*
* **\>autoroleremove \<role name or id\>**
  > Remove a role from the autorole list. Aliases: *arr*
* **\>autorolelist**
  > See all the roles that are set to be given when a new members join. This command will also clear the autorole list from roles that have been deleted (this will be improved in the future). Aliases: *arl*
