![Shiro](https://i.imgur.com/OQPTNgN.png)
![Info](https://img.shields.io/badge/Lib-Discord.js-blue.svg)
![Info2](https://img.shields.io/badge/DB-MongoDB-blue.svg)
![Guilds](https://img.shields.io/badge/Guilds-12-green.svg)
![license](https://img.shields.io/badge/License-Mozilla%20Public%20License%202.0-green.svg)

***
**►** [**Invite Link**](https://discordapp.com/api/oauth2/authorize?client_id=444198945183367189&permissions=0&scope=bot)

**►** [**Support Server**](https://discord.gg/ypEBGHB)

<details>To be a supporter send us an email here<summary>email</summary>
<p>
  shirothediscordbot@gmail.com
</p>
</details>

***
## Documentation
### Commands
##### Moderation
* **\>ban \<members\> [reason]**
  > Bans the specified members for an optional reason
* **\>kick \<members\> [reason]**
  > Kicks the specified members for an optional reason
* **\>mute \<members\> [reason]**
  > Mutes the specified members by assigning the the *Mute Role* that has been set with the *\>set muterole \<role\>* command, optional reason
* **\>unmute \<members\> [reason]**
  > Unmutes the specified members by unassigning the the *Mute Role* that has been set with the *\>set muterole \<role\>* command, optional reason
* **\>prune \<number\>**
  > Bulk deletes a number of messages (max. 100). Aliases: *purge*, *clear*
* **\>warn \<member\> [reason]**
  > Warns the mentioned member [reason optional]
* **\>addrole \<role\> \<target\>**
  > Adds a role to the specified target. Role can be given by id, name, or tag. Target can be a member id, member name, member mention, all, humans, bots
* **\>removerole \<role\> \<target\>**
  > Removes a role from the specified target. Details same as above
* **\>report \<members\> [reason]**
   > Reports the mentioned members to the server owner [reason optional]
   
   > *For supporters only*
##### Information
* **\>help [command]**
  > Shows all commands or help about a specific command 
* **\>setup**
  > Shows all server configuring commands
* **\>settings**
  > Shows an overview of the server's enabled or disabled settings. *note: certain functions are toggled off by default*
* **\>serverinfo**
  > Returns information related to the server: Icon, Onwer, Region, Member Count, Emoji Count, Text, Voice Channels and Roles
* **\>userinfo [member]**
  > Returns information related to a user: Icon, Full Name, ID, Status, Presence, Join Date, Account Creation Date and Roles
* **\>botstatus**
  > Returns information related to the bot: Icon, Language, Ping, Api Ping Time, Bot Uptime, System Uptime, System Info and useful links
* **\>changelog**
  > Returns information about the bot version
* **\>invite**
  > Returns the bot's invite link
##### Reactions (400+ unique gifs)
* **\> kiss, hug, cuddle pat, lick, tickle, bite, poke, pinch, slap, blush, mad, scared, tired, sleep, yawn, cry, run, nervous, pout**
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
* **\>ship \<args1\> | \<args2\>**
  > Returns how compatible 2 people are with each other (99% of ships have sailed)
* **\>rps \<rock or paper or scissors\>**
  > Emulates a rock, paper, scissors game with the bot
##### Fun
* **\>movie \<movie name\>**
  > Returns information about a movie taken from the OMDB Api. Returned Info: Title, Release date, Runtime, Genre, Director, Writer, Plot/Summary, Imdb rating
* **\>urban \<word or phrase\>**
  > Returns information about a word or phrase taken from Urban Dictionary. Returned Info: Definition, Author, Upvotes & Downvotes and an example. Aliases: *ud*
* **\>weather \<city or area\>**
  > Returns weather information for the specified city or area. Returned Info: What the weather looks like, Date, Timezone, Temperature, Humidity, Wind and obervation point
* **\>fortnite \<platform\> [username]**
  > Returns fortnite stats for the specified user on the specified platform(*pc*, *xbox*, *ps4*)\nReturned Info: Solo/Duo/Squad Wins, Kd, Matches Played, Kills
  
  > *For supporters only*
* **\>itunes \<type\> \<item\>**
  > Returns information from iTunes about a product. Types are: *music*, *movie*, *podcast*, *audiobook*, *ebook*, *software*, *all*. Term *all* will return 10 results with that correspond to the *name* regardless of their category
  
  > *For supporters only*
* **\> dog, shibe, cat, bird, fox, lizard**
  > Fetches animals pictures
* **\> chuckjoke, punchjoke, dadjoke**
  > Returns jokes, easy right?
* **\>comic**
  > Fetches a random comic
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
* **\>color \<type\> \<specify color or random\>**
  > Returns information about a specified or random color. Type can be either *rgb* or *hex*. In case of rgb you have to specify 3 values between 0-255. In case of hex you have to specify a hex value
##### Nsfw
* **\>rule34 \<tag\>, yandere \<tag\>, danbooru \<tag\>, gelbooru \<tag\>, xbooru \<tag\>, realbooru \<tag\>, plot**
  > Fetches a random (nsfw) picture, provide only one tag for more accurate results. Aliases: *34*, *yan*, *dan*, *gel*, *xb*, *rb*
## Server Configuring/Settings
##### Toggle (on/off)
* **\>toggle modlog**
  > Enables or disables moderation logging
* **\>toggle chatlog**
  > Enables or disables chat logging
* **\>toggle changelog**
  > Enables or disables guild/member change logging
* **\>toggle filter**
  > Enables or disables chat filtering
* **\>toggle welcomemessages**
  > Enables or disables welcome messages, when a new member joins the server
* **\>toggle leavemessages**
  > Enables or disables leaves messages, when a member leaves the server
* **\>toggle invitelinks**
  > Enables or disables discord invite link deletion
* **\>toggle links**
  > Enables or disables link deletion (any link)
* **\>toggle autorole**
  > Enables or disables the automatic role assignment when a new member joins
##### Add or Remove
* **\>add/remove filter \<word\>**
  > Adds or removes a word from the filtered words list
* **\>add/remove linkchannel \<channel\>**
  > Adds or removes a channel from the list of ignored channels for link deletion
* **\>add/remove autorole \<role\>**
  > Adds or removes a role from the auto role list
##### Set
* **\>set modlog \<channel\>**
  > Sets the channel for moderation logging
* **\>set chatlog \<channel\>**
  > Sets the channel for chat logging
* **\>set changelog \<channel\>**
  > Sets the channel for member/guild change logging
* **\>set welcomechannel \<channel\>**
  > Sets the channel in which the bot will welcome new members
* **\>set welcomemessage \<message\>**
  > Sets the welcome message. 
  > 
  > You can add (*--mention, --username, --id, --created*) in the message. When the the message will get sent they will be replaced by the new member's *tag*, *username* + *discriminator*, *id*, and *date* that their account was created
  > 
  > eg. *>set welcomemessage Welcome --mention to the server (--id)*
* **\>set**
  > Sets
  
  
  
  
  
  
  
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
  > Set the max mentions a message is allowed to have (*\>mentionlimit 0* to disable). Aliases: *ml*
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
