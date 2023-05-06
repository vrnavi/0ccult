---
title: Commands
description: The commands for the Dishwasher Discord bot.
image: /dishwasher.png
---

These are the available commands for Dishwasher. Not all are shown.<br>
For your reference:<br>
- **[argument]** represents a required argument.
- **{argument}** is an optional requirement.
- argument **(default)** is the default if not specified.

## Basic Features

`about`<br>
Tells you about the bot.

`avy` [user/"server" (yourself)]<br>
Returns an avatar of a user.

`color` [hex color code]<br>
Shows an image of the color you specify.

`cotd`<br>
Displays the current Color of The Day.

`hello`<br>
Says hello to you.

`help`<br>
Gives you a link to this page.

`hug`<br>
Gives you a hug.

`info` [user (yourself)]<br>
Gets information on a user.

`install`<br>
Gives you instructions on how to install a dishwasher.

`kill` [text/mention]<br>
Kills someone.

`membercount`<br>
Shows the current member count of the server.

`ping`<br>
Shows the bot's latency.

`server`<br>
Gives you a link to the bot's home server.

`youtube`/`yt` [search term]<br>
Searches youtube for a query.

### Conversion

`dec` [number]<br>
Converts Base16 to Base10.

`hex` [number]<br>
Converts Base10 to Base16.

### Join*

`joinscore` {joinscore or mention}<br>
Posts your (or someone else's) joinscore for the current server.

`joingraph`<br>
Posts a graph of times people have joined.

### Prefixes

`prefixes`<br>
Shows your currently active prefixes.

`prefixes add` [prefix]<br>
Adds a new prefix.

`prefixes remove` [number]<br>
Removes a prefix.

### Timezone

`timezone`/`tz` [timezone]<br>
Sets your timezone. You can use [this list](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) as a reference.

`timefor`/`tf` [user]<br>
Shows the timezone for you, or someone else.

### Reminders

`remind` [time] [text]<br>
Reminds you about something in Direct Messages.<br>
Use "number then unit" format, such as *5s*, which is the minimum.

`reminders`<br>
Lists your reminders.

`reminders remove` [index]<br>
Removes a reminder.<br>
You can get the index from the `reminders` command.

### Server Specific

`mylogs`<br>
Lists actions taken on you by Staff.

`pingmod`<br>
Pings the Staff team.

`staff`<br>
Shows the currently active Staff members.

## Staff Features

`ban` [target] {reason}<br>
Bans a user and messages them with the reason.

`dban` [target] [duration] {reason}<br>
Bans a user with a specified amount of days worth of messages deleted, messages them with the reason.

`kick` [target] {reason}<br>
Kicks a user.

`massban` [targets]<br>
Bans several users with their IDs without messaging them.

`modtoggle`
Toggles between your Ex-Staff and Staff role.

`purge` [limit] {channel (current)}<br>
Clears a given number of messages.

`sban` [target] {reason}<br>
Bans a user without messaging them.

`unban` [target] {reason}<br>
Unbans a user.

`warn` [target] {reason}<br>
Warns a user.

### Tosses

`archive` [user]<br>
When performed in the designated Toss channel, will archive the current channel.<br>
When performed elsewhere, will search the archives for a given user.

`toss` [target]<br>
Tosses a target, replacing all of their roles with one role.

`untoss` [target]<br>
Untosses a target, restoring their roles.

### Surveyr

`survey`/`s`<br>
Posts the 5 recent surveys.

`reason`/`r` [case ID or "l"]{-case ID for "l"} [reason]<br>
Records a reason for a survey.

`censor`/`c` [case ID or "l"]{-case ID for "l"}<br>
Censors a survey's name.

`dump`/`d` [case ID or "l"]{-case ID for "l"}<br>
Dumps user IDs for surveys.

### Lockdown

`lock` {channel (current)} {soft (false)}<br>
Prevents people from speaking. Will have a "hard" tone by default.<br>
Use true/false with the "soft" argument to adjust this behavior.

`lockdown` {channels (all)} ...<br>
Puts the server on lockdown, preventing new users from talking.<br>
May automatically trigger after mention spam.

`unlock` {channel (current)}<br>
Unlocks the current channel for speaking.

`unlockdown` {channels (all)} ...<br>
Unlocks the entire server for everyone to speak in once more.

### Notes

`note` [target] {note}<br>
Adds a note to a user.

### Watch

`watch` [target] {note}<br>
Puts a user under watch.

`unwatch` [target] {note}<br>
Removes a user from the watch list.

### Raid Mode

`raidmode` ["on"/"off" (show current state)]<br>
Toggles Raidmode, a feature to post all new users in the Staff channel.

### Puppet Features

`botnickname` {nickname}<br>
Sets the current nickname. Send command by itself to reset.

`nickname` [target] {nickname}<br>
Sets a users nickname. Send command by itself to reset.

`playing` [game]<br>
Sets the bot's "currently playing" status. Send command by itself to reset.
Change lasts until next playing rotation.

`react` [channel] [message id] [emoji]<br>
Puts a reaction on a message.

`reply` [channel] [message id] [text]<br>
Replies to a message in a given channel with a given text.

`say` [text]<br>
Repeats some text.

`speak` [channel] [text]<br>
Repeats some text in a given channel.

`typing` [duration]<br>
Puts a "Bot is typing..." in chat for a period of time.
