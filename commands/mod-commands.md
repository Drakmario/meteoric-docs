> Moderation commands | Catagory: Moderation.
>
>>  Meteoric moderation commands are mainly used by moderators and admins. All of these commands will require role permissions for both the message author as well for the bot. All of these commands will require both the author of the message as well the bot to have the correct role permissions to perform these commands. ⚠ - A update could require these commands to need configuration.

### Poll

Create a poll and send it to a channel using the bot. The bot will send the poll in a embed and will react to it with ✅ for yes and ❌ for no.

* Author Permissions: Manage Messages
* Bot Permissions: Manage Messages
* Usage:

```
m!poll <channel> <topic>
```

### Addrole

Add a role to a user.

* Author Permissions: Manage Roles
* Bot Permissions: Manage Roles
* Usage:

```
m!addrole <@user> <@role>
```

* Aliases: ar

### Removerole

Remove a role from a user.

* Author Permissions: Manage Roles
* Bot Permissions: Manage Roles
* Usage:

```
m!removerole <@user> <@role>
```

* Aliases: rr

### Slowmode

Set/edit the slowmode for a channel. When defining the args for slowmode, define it as "s" for seconds. The max second duration possiable is 21600s.

* Author Permissions: Manage Channels
* Bot Permissions: Manage Channels
* Usage:

```
m!slowmode <args>
```

* Aliases: s

### Purge

Delete a certain amount of messages defined by the message author. The bot can only purge a minimum of 2 and a maximum of 100.

* Author Permissions: Manage Messages
* Bot Permissions: Manage Messages
* Usage:

```
m!purge <2-100>
```

### ⚠ The following commands below will not affect members with administrator permissions.

### Warn

Warns a user with the reason defined by the author.

* Author Permissions: Manage Messages
* Bot Permissions: Manage Messages
* Usage:

```
m!warn <@user | id> <reason>
```

* Aliases: w

### Mute

Mutes a user for a set amount of time defined by the author. Duration examples are s - seconds, m - minutes, h - hours, d - days, and w -weeks. The max time that can be applied to a user is 24 days, if you go byond that limit the bot will cut it down to 1 second. A role named muted is required for this command to work. A reason can also be added for this mute, if nothing is provided for the reason it'll default to "No reason provided".

* Author Permissions: Manage Roles
* Bot Permissions: Manage Roles
* Usage:

```
m!mute <@user> <time> [reason]
```

After the mute time for the user is up, a message will be sent to the same channel that they have been automatically unmute and will remove the muted role from the user. But if the user gets unmuted before their mute time is up then the auto unmute is stop and no message will be sent.

* Aliases: m

### Unmute

Unmutes a muted user. The bot will not unmute members that aren't muted. A reason can also be added for this unmute, if nothing is provided for the reason it'll default to "No reason provided".

* Author Permissions: Manage Roles
* Bot Permissions: Manage Roles
* Usage:

```
m!unmute <@user> [reason]
```

* Aliases: u

### Kick

Kicks a user from the guild. A reason can be added for the kick, if nothing is provided it'll default to "No reason provided".

* Author Permissions: Kick Members
* Bot Permissions: Kick Members
* Usage:

```
m!kick <@user> [reason]
```

* Aliases: k

### Ban

Bans a user from the guild. A reason can be added for the ban, if nothing is provided it'll default to "No reason provided".

* Author Permissions: Ban Members
* Bot Permissions: Ban Members
* Usage:

```
m!ban <@user> [reason]
```

* Aliases: b