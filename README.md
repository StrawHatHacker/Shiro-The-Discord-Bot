![Shiro](https://i.imgur.com/OQPTNgN.png)

[![Discord Bots](https://discordbots.org/api/widget/status/444198945183367189.svg?noavatar=true)](https://discordbots.org/bot/444198945183367189)
[![Discord Bots](https://discordbots.org/api/widget/servers/444198945183367189.svg?noavatar=true)](https://discordbots.org/bot/444198945183367189)
[![Discord Bots](https://discordbots.org/api/widget/upvotes/444198945183367189.svg?noavatar=true)](https://discordbots.org/bot/444198945183367189)
[![Discord Bots](https://discordbots.org/api/widget/owner/444198945183367189.svg?noavatar=true)](https://discordbots.org/bot/444198945183367189)

A multipurpose bot featuring 600+ reaction anime gifs, full moderation, fully customizable server automation, logging and many others features

**►** [**Invite Me**](https://discordapp.com/api/oauth2/authorize?client_id=444198945183367189&permissions=0&scope=bot)

**►** [**Support Server**](https://discord.gg/ypEBGHB)

Become a supporter: https://www.patreon.com/shiroandyumiko

***
## Documentation
### Commands
##### Moderation
* **\>hackban \<user ids\>**
  > Bans users by id. Also works for users that are not in the server. Max ids: 10
* **\>ban \<mentions\> [reason]**
  > Bans the specified members for an optional reason. Max mentions: 10
* **\>kick \<mentions\> [reason]**
  > Kicks the specified members for an optional reason. Max mentions: 10
* **\>mute \[time\] \<mentions\> [reason]**
  > Mutes the specified members by assigning the the *Mute Role* that has been set with the *\>set muterole \<role\>* command, optional reason. Max mentions: 10. Time format: 0h or 0m. Eg: *>mute 2h @Sophie smells bad*
* **\>unmute \<mentions\> [reason]**
  > Unmutes the specified members by unassigning the the *Mute Role* that has been set with the *\>set muterole \<role\>* command, optional reason. Max mentions: 10
* **\>prune [member mention or number]**
  > * `>prune <number>`. Deletes a number of messages
  >
  > * `>prune <member mention>`. Deletes as many messages as possible sent by the mentioned member
  >
  > * `>prune`. Delete as many messages from Shiro as possible

    Aliases: *purge*, *clear*
* **\>warn \<mentions\> [reason]**
  > Warns the mentioned members for an optional reason. Max mentions: 10
* **\>roleadd \<role\> \<target\>**
  > Adds a role to the specified target(member or role). Role can be given by id, name, or role mention. Target can be a member id, member name, member mention, all, humans, bots, a role, role name or role id
* **\>removerole \<role\> \<target\>**
  > Removes a role from the specified target. Details same as above
> **\>rolecolor \<hex\> \<role\>**
  > Changes the color of the specified role.
> **\>rolementionable \<role\>**
  > Makes the specified role mentionable
* **\>warnlog \<add, remove, edit or member\>**
  > Add\* a warnlog entry for a member, eg. *\>warnlog add @Sophie \<reason\>*
  
  > Remove\* a warnlog entry of a member, eg. *\>warnlog remove @Sophie \<entry id\>*
  
  > Edit\* the reason of a warnlog entry of a member, rg. *\>warnlog edit @Sophie \<entry id\> \<reason\>*
  
  > List a member's last 10 warnlog entries, eg. *\>warnlog @Sophie*
  
  > *Add*, *remove* and *edit*, are available only for supporting servers
##### Information
* **\>help [command]**
  > Shows all commands or help about a specific command 
  > Type *\>help settings* to display all server configuring commands
* **\>settings**
  > Shows an overview of the server's enabled or disabled settings. note: certain functions are toggled off by default and you have to toggle them on using the *>toggle* command
* **\>guide**
  > Get a list of all guides for Shiro
* **\>serverinfo**
  > Returns information related to the server: Icon, Onwer, Region, Verification Level, Created Date, Role Count, Human & Bot count, Online & Offline Members Count, Channel Count and Emoji Count
* **\>userinfo [mention or name]**
  > Returns information related to a member in the server: Icon, ID, Status, Presence, Role Count, Highest Role, Join Date, Account Creation Date and Key Permissions
* **\>channelinfo [mention or name]**
  > Returns information related to a channel of the server: ID, Type, Category, Created Date
* **\>botstatus**
  > Returns information related to Shiro: Ping, Bot Uptime and System Uptime, Server Count, Shard ID (Aliases: *\>ping*)
* **\>invite**
  > Returns the bot's invite link and a server invite
##### Reactions (500+ unique gifs)
* **\>kiss [members], hug, cuddle pat, lick, tickle, bite, poke, pinch, slap, blush, mad, scared, tired, sleep, yawn, cry, run, nervous, pout, wink, smug, stare, punch, kick, wave, nom, sip**
##### Games
* **\>say \<text\>**
  > Deletes the original message and then returns its contents
* **\>embed [text]**
  > Deletes the original message and embeds the text into a cute embed
* **\>quote [text]**
  > Deletes the original message and quotes the text. Equivalent of doing `> text....` on discord.
* **\>dice [sides]* [times]*
  > Rolls the dice, pretty straightforward. Max rolls: 10
* **\>8ball \<text\>**
  > Emulates the 8ball game
* **\>team \<text\> \<text\> \<text\>....**
  > Seperates the argurments into 2 teams
* **\>ship \<args1\> | [args2]**
  > Returns how compatible 2 people are with each other (99% of ships have sailed). Results change every month.
* **\>fight \<member mention\>**
  > Fight with people and see who is the strongest
* **\>rps \<rock or paper or scissors\>**
  > Emulates a rock, paper, scissors game with the bot
* **\>poll \<text\>**
  > Creates a poll. Simple poll: `>poll "Question"`. Multi poll: `>poll "Question" "answer1" "answer2" ...`
##### Fun
* **\>movie \<movie name\>**
  > Returns information about a movie taken from the OMDB Api: Release Date, Runtime, Genre, Director, Writer, Imdb Rating and Plot
* **\>urban \<word or phrase\>** 
  > Returns information about a word or phrase taken from Urban Dictionary: Definition, Author, Votes and an Example. Nsfw channel required
* **\>weather \<city or area\>**
  > Returns weather information for the specified city or area: Temperature, Humidity, Wind
* **\>fortnite \<platform\> [username]**
  > Returns fortnite stats for the specified user on the specified platform(*pc*, *xbox*, *ps4*)
  
  > *Fortnite is available only for supporting servers*
* **\>itunes \<type\> \<item\>**
  > Returns information from iTunes about a product. Types are: *music*, *movie*, *podcast*, *audiobook*, *ebook*, *software*, *all*. Term *all* will return 10 results with that correspond to the *item* regardless of their type
  
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
  > Fetches a random meme from Reddit. Nsfw channel required
* **\>lyrics \<song title\>**
  > Finds lyrics for your favourite songs
## Server Configuring/Settings
> * **If you want help on how to setup certain funtions for your server read the [guide](https://github.com/StrawHatHacker/Shiro-The-Discord-Bot/blob/master/shiro-guide.md)**

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
  > *Limited at 10 words, 50 words for supporting servers*
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
