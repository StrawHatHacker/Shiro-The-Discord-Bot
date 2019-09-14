![Shiro](https://i.imgur.com/OQPTNgN.png)

[![Discord Bots](https://discordbots.org/api/widget/status/444198945183367189.svg?noavatar=true)](https://discordbots.org/bot/444198945183367189)
[![Discord Bots](https://discordbots.org/api/widget/servers/444198945183367189.svg?noavatar=true)](https://discordbots.org/bot/444198945183367189)
[![Discord Bots](https://discordbots.org/api/widget/upvotes/444198945183367189.svg?noavatar=true)](https://discordbots.org/bot/444198945183367189)
[![Discord Bots](https://discordbots.org/api/widget/owner/444198945183367189.svg?noavatar=true)](https://discordbots.org/bot/444198945183367189)

A multipurpose bot featuring 600+ reaction anime gifs, full moderation, fully customizable server automation, logging and many others features

**►** [**Invite Me**](https://discordapp.com/api/oauth2/authorize?client_id=444198945183367189&permissions=0&scope=bot)

**►** [**Support Server**](https://discord.gg/ypEBGHB)

To become a supporter send us an email here: ntahsp@gmail.com

***
## Documentation
### Commands
##### Moderation
* **\>hackban \<user ids\>**
  > Bans users by id. Also works for users that are not in the server
* **\>ban \<mentions\> [reason]**
  > Bans the specified members for an optional reason
* **\>kick \<mentions\> [reason]**
  > Kicks the specified members for an optional reason
* **\>mute \[time\] \<mentions\> [reason]**
  > Mutes the specified members by assigning the the *Mute Role* that has been set with the *\>set muterole \<role\>* command, optional reason. Time format: 0h or 0m. Eg: *>mute 2h @Sophie smells bad*
* **\>unmute \<mentions\> [reason]**
  > Unmutes the specified members by unassigning the the *Mute Role* that has been set with the *\>set muterole \<role\>* command, optional reason
* **\>prune [member mention or number]**
  > * `>prune <number>`. Deletes a number of messages.
  >
  > * `>prune <member mention>`. Deletes as many messages as possible sent by the mentioned member.
  >
  > * `>prune`. Delete as many messages from Shiro as possible.

    Aliases: *purge*, *clear*
* **\>warn \<mentions\> [reason]**
  > Warns the mentioned members for an optional reason
* **\>addrole \<role\> \<target\>**
  > Adds a role to the specified target(member or role). Role can be given by id, name, or role mention. Target can be a member id, member name, member mention, all, humans, bots, a role, role name or role id.
* **\>removerole \<role\> \<target\>**
  > Removes a role from the specified target. Details same as above
* **\>warnlog \<add, remove, edit or member\>**
  > Add\* a warnlog entry for a member, eg. *\>warnlog add @Sophie \<reason\>*
  
  > Remove\* a warnlog entry of a member, eg. *\>warnlog remove @Sophie \<entry id\>*
  
  > Edit\* the reason of a warnlog entry of a member, rg. *\>warnlog edit @Sophie \<entry id\> \<reason\>*
  
  > List a member's last 10 warnlog entries, eg. *\>warnlog @Sophie*
  
  > *Add*, *remove* and *edit*, are available only for supporting servers
* **\>report \<mentions\> [reason]**
   > Reports the mentioned members to the server owner for an optional reason
   
   > *Report command is available only for supporting servers*
##### Information
* **\>help [command]**
  > Shows all commands or help about a specific command 
  > *\>help settings* will display all server configuring commands
* **\>settings**
  > Shows an overview of the server's enabled or disabled settings. note: certain functions are toggled off by default and you have to toggle them on using the *>toggle* command
* **\>guide**
  > Get a list of all guides for Shiro
* **\>serverinfo**
  > Returns information related to the server: Icon, Onwer, Region, Member Count, Emoji Count, Text, Voice Channels and Roles
* **\>userinfo [mention or name]**
  > Returns information related to a member in the server: Icon, Full Name, ID, Status, Presence, Highest Role, Join Date, Account Creation Date, Roles or Key Permissions
* **\>botstatus**
  > Returns information related to the bot: Icon, Language, Ping, Api Ping Time, Bot Uptime, System Uptime, Guilds/Users, System Info and useful links (Alias: *\>ping*)
* **\>invite \<`bot` or `server`\>**
  > Returns the bot's invite link or generates a new server invite
##### Reactions (600+ unique gifs)
* **\>kiss [members], hug, cuddle pat, lick, tickle, bite, poke, pinch, slap, blush, mad, scared, tired, sleep, yawn, cry, run, nervous, pout, wink, smug, stare, kill, wave, nom, sip**
##### Games
* **\>say \<text\>**
  > Deletes the original message and then returns its contents
* **\>embed [text]**
  > Deletes the original message and embeds the text into a cute embed
* **\>quote [text]**
  > Deletes the original message and quotes the text. Equivalent to doing `> text....` on discord.
* **\>dice**
  > Rolls the dice, pretty straightforward
* **\>8ball \<text\>**
  > Emulates the 8ball game
* **\>team \<text\> \<text\> \<text\>....**
  > Returns an embed seperating the arguments randomly into 2 teams
* **\>ship \<args1\> | [args2]**
  > Returns how compatible 2 people are with each other (99% of ships have sailed). Results change every month.
* **\>fight \<args1\> | [args2]**
  > Fight with people and see who is the strongest
* **\>rps \<rock or paper or scissors\>**
  > Emulates a rock, paper, scissors game with the bot
##### Fun
* **\>movie \<movie name\>**
  > Returns information about a movie taken from the OMDB Api
* **\>urban \<word or phrase\>** 
  > Returns information about a word or phrase taken from Urban Dictionary
* **\>weather \<city or area\>**
  > Returns weather information for the specified city or area
* **\>fortnite \<platform\> [username]**
  > Returns fortnite stats for the specified user on the specified platform(*pc*, *xbox*, *ps4*)
  
  > *Fortnite is available only for supporting servers*
* **\>itunes \<type\> \<item\>**
  > Returns information from iTunes about a product. Types are: *music*, *movie*, *podcast*, *audiobook*, *ebook*, *software*, *all*. Term *all* will return 10 results with that correspond to the *name* regardless of their category
  
  > *ITunes is available only for supporting servers*
* **\> dog, shibe, cat, bird, fox, goat, panda, redpanda, koala**
  > Fetches animals pictures
* **\>comic**
  > Fetches a random comic
* **\>advice**
  > Returns random advice
* **\>insult**
  > Returns a random fancy insult. Try not to offend anyone
* **\>size [member]**
  > Returns the size of your pickle ( ͡° ͜ʖ ͡°) 100% accuracy. Results change every month. Aliases: *pickle*
* **\>color \<type\> \<specify color properties\>**
  > Returns information about a specified or random color. Type can be either *rgb* or *hex* or *random*. In case of rgb you have to specify 3 values between 0-255 (eg *\>color rgb 100 100 150*). In case of hex you have to specify a hex value(eg *\>color hex ffffff*)
* **\>meme**
  > Fetches a random meme from Reddit
* **\>lyrics <song title>**
  > Finds lyrics for your favourite songs
## Server Configuring/Settings
> * **If you want help in how to setup certain funtions for your server read the [guide](https://github.com/StrawHatHacker/Shiro-The-Discord-Bot/blob/master/shiro-guide.md)**
>
> * **Toggle, add/remove, set require *Administrator* permissions**
##### Toggle (on/off)
* **\>toggle modlog**
  > Enables or disables moderation logging
* **\>toggle chatlog**
  > Enables or disables chat logging
* **\>toggle updatelog**
  > Enables or disables member/server update logging
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
* **\>toggle strictmode**
  > Enables or disables strict mode for certain bot functions. For now only `filter` becomes stricter
##### Add or Remove
* **\>add/remove filter \<word\>**
  > Adds or removes a word from the filtered words list. Members who type that word will get their message deleted
  > Dms member
  > 
  > *Limited at 10 words, 20 words for supporting servers*
* **\>add/remove linkchannel \<channel\>**
  > Adds or removes a channel from the list of ignored channels. Channels added to the list will get ignored when links are posted
* **\>add/remove autorole \<role\>**
  > Adds or removes a role from the auto role list. When a user joins they will get assigned all of the specified roles
  > 
  > *Limited at 1 role, 10 roles for supporting servers*
##### Set
* **\>set modlog \<channel\>**
  > Sets the channel for moderation logging
* **\>set chatlog \<channel\>**
  > Sets the channel for chat logging. Logs edited/deleted messages, bulk deletions
* **\>set updatelog \<channel\>**
  > Sets the channel for member/server update logging
* **\>set welcomechannel \<channel\>**
  > Sets the channel in which the bot will welcome new members
* **\>set welcomemessage \<message\>**
  > Sets the welcome message
  > 
  > You can add (*--mention, --username, --id, --created*) in the message. When the the message will get sent they will be replaced by the new member's *tag*, *username* + *discriminator*, *id*, and *date* that their account was created
  > 
  > eg. *>set welcomemessage Welcome --mention to the server (--id)*
* **\>set leavechannel \<channel\>**
  > Sets the channel in which the bot will say goodbye to members that left the guild
* **\>set leavemessage \<message\>**
  > Sets the leave message
  > 
  > You can add (*--username, --id, --created*) in the message. When the the message will get sent they will be replaced by the user's *username* + *discriminator*, *id*, and *date* that their account was created
  > 
  > eg. *>set leavemessage Sayonara --username (--id)*
* **\>set prefix \<prefix\>**
  > Sets the server's prefix
* **\>set mentions \<number\>**
  > Sets the mention limit that is allowed per message. Set to `0` to disable. Can only be higher than `2`.
* **\>set muterole \<role\>**
  > Sets the role which will be assigned when a member gets muted. Eg. with the *\>mute* command
##### List or Show
* **\>list filter**
  > Lists all filtered words
* **\>list \<welcomemessage\>**
  > Shows the welcome message with you as the new member
* **\>list \<leavemessage\>**
  > Shows the leave message with you as the left member
* **\>list linkchannels**
  > Lists all channels in which link deletion is disabled
* **\>list \<autoroles\>**
  > Lists all auto the roles that will be autoassigned when a new member joins

Note: *When calling a list/show command, roles and channels that have been deleted from the guild but they still exist in the database will get removed*

[![Discord Bots](https://discordbots.org/api/widget/444198945183367189.svg)](https://discordbots.org/bot/444198945183367189)
