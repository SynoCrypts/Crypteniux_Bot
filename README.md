# Crypteniux_Bot
- Note that this is a test repository.


# About:
- A Discord Bot developed by SynoCrypts using Discord.JS
- Over 40+ commands + hidden commands.
- This bot `isn't` hosted `24/7` yet. It's hosted on my PC, so it will only be online when my PC is active.

# Invite:
https://discord.com/oauth2/authorize?client_id=787418243987013642&scope=bot&permissions=8
- If you do not grant the bot administrator permissions, some commands may be unstable.


# Commands:
- The symbols `[` and `]` mean those are required arguments.
- The symbols `(` and `)` mean those are optional arguments.
- Prefix: `s!`

> poll `[string] , [num, seconds]`
- Use comma `,` to separate the poll arguments.
- Maximum seconds: 5000, Minimum seconds: 3
- Example:
- s!poll Cool?, 32

> slowmode `[num]`
- Sets the current channel's slowmode
- Maximum seconds: 5000, Minimum seconds: 1
- Example:
- s!slowmode 1

> kick `[mention] (reason)`
- Kicks the user that is mentioned.
- Example:
- s!kick @🌨Shineiii❄#2504 Posting bad stuff.
- The reason is optional here.

> ban `[mention] (reason)`
- Bans the user that is mentioned.
- Example:
- s!ban @🌨Shineiii❄#2504 I've said stop.
- The reason is optional here too.

> unban `[user id]`
- Unbans the user with the specific user id.
- Enable developer mode to copy IDs.
- Example:
- s!unban 458698478957101056

> purge `[num]`
- Deletes messages.
- Maximum messages: 100, Minimum messages: 1
- Example:
- s!purge 8

> unslowmode
- Sets the channel's slowmode to 0.

> lockdown
- Removes action for the role `@everyone` to send messages in the channel the command is used in.

> unlockdown
- Adds the action for the role `@everyone` to send messages in the channel the command is used in.
