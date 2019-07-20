## Setting Up Chat Filtering

__Curse Words__
1. Enable the chat filtering function: `>toggle filter`
2. Add a curse word: `>add filter <word>`
3. Remove a curse word: `>remove filter <word>`
4. List all curse words: `>list filter`

__Other__
1. Enable invite link deletion: `>toggle invitelinks`
2. Enable link deletion: `>toggle links`
3. Add ignore channel: `>add linkchannel <channel>`
4. Remove ignore channel: `>remove linkchannel <channel>`
5. List ignored channels: `>list linkchannels`
6. Set max mentions per message: `>set mentions <number>`

* Chat Filtering will ignore members that have a role with `Administrator` permissions.
* You can add only one word/channel at a time.
* Links will not be deleted in ignored channels.
* For ``<channel>` is recommended to pass a channel ID.
* For `<number>` you have to pass a value higher than `2` (or `0` to disable mention limiting).

Note: *There is a limit 10 filtered words per server, if you want to extend it read #pricing in [Support Server](https://discord.gg/ypEBGHB)*

## Setting Up Moderation Logging

1. Enable moderation logging: `>toggle modlog`
2. Specify the logging channel: `>set modlog <channel>`

* Moderation logging will log any moderation related event to the specified channel.
* For `<channel>` is recommended to pass a channel ID.
* To disable do `>toggle modlog` again.

## Setting Up Chat Logging 

1. Enable chat logging: `>toggle chatlog`
2. Specify the logging channel: `>set chatlog <channel>`

* Chat logging will log deleted, edited messages and bulk deletions to the specified channel.
* For `<channel>` is recommended to pass a channel ID.
* To disable do `>toggle chatlog` again.

## Setting Up Update Logging

1. Enable member/server logging: `>toggle changelog`
2. Specify the logging channel: `>set updatelog <channel>`

* For `<channel>` is recommended to pass a channel ID.
* To disable do `>toggle changelog` again.

## Setting Up Welcome Messages

1. Enable welcome messages: `>toggle welcomemessages`
2. Specify the greet channel: `>set welcomechannel <channel>`
3. Set welcome message: `>set welcomemessage <message>`
4. Test the welcome message: `>show welcomemessage`

* Make Shiro greet new members.
* For `<channel>` is recommended to pass a channel ID.
* To disable do `>toggle welcomemessages` again.
* For `<message>` you can pass any text you want, image link etc. You can also add these placeholders (`--mention`, `--username`, `--created`, `--id`) that will be replaced by the appropriate member info on join.

## Setting Up Leave Messages

1. Enable on leave messages: `>toggle leavemessages`
2. Specify the channel: `>set leavechannel <channel>`
3. Set message: `>set leavemessage <message>`
4. Test the on leave message: `>show leavemessage`

* Make Shiro say farewell to leavers.
* For `<channel>` is recommended to pass a channel ID.
* To disable do `>toggle leavemessages` again.
* For `<message>` you can pass any text you want, image link etc. You can also add these placeholders ( ``--username``, `--created`, `--id`) that will be replaced by the appropriate user info on leave.

## Setting Up Autoroles 

1. Enable autoroles: `>toggle autorole`
2. Add a role: `>add autorole <role>`
3. Remove a role: `>remove autorole <role>`
4. List current autoroles: `>list autoroles`

* Give new members roles as they join.
* For `<role>` is recommended to pass a role ID.

Note: *There is a limit of 2 autoroles per server, if you want to extend it read #pricing in [Support Server](https://discord.gg/ypEBGHB)*

## Setting Up Blacklist 

1. Add an ID: `>add blacklist <id>`
2. Remove an ID: `>remove blacklist <id>`
3. List all blacklisted IDs: `>list blacklist`

* Blacklist users so they can't join the server.
* For `<id>` you have to pass a user's ID.

Note: *There is a limit of 10 blacklisted users per server, if you want to extend it read #pricing in [Support Server](https://discord.gg/ypEBGHB)*

## Updating Prefix

1. Set prefix: `>set prefix <character(s)>`

* For `<character(s)>` you have to pass alphanumeric text, max 3 characters.
* In case you forgot your custom prefix you can reset it by kicking and reinviting Shiro.

## Set Muterole

- Set the muterole: `>set muterole <role>`

* Set the role that gets assigned when someone gets muted by the `>mute` command.
* For `<role>` is recommended to pass a role ID.
