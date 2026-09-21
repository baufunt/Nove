# Vailds – Discord Bot

**Vailds** is the official bot for this server.
It’s built for speed, fun, and a little bit of sarcasm.
Use it to keep the channel lively, automate tasks, and get quick answers.

---

## Overview

* **Fast & Reliable** – Written in JavaScript (Node.js) with discord.js v14.
* **Feature-Rich** – Commands, moderation tools, utilities, and custom reactions.
* **Self-Healing** – Auto-reconnects, auto-restarts, and health-check endpoints.
* **Easy to Extend** – Modular command structure with simple configuration files.
* **Server-Friendly** – Designed to work smoothly without unnecessary resource usage.
* **Customizable** – Configure commands, responses, permissions, and server settings to fit your community.

## Commands

| Command                        | Description                         | Example                             |
| ------------------------------ | ----------------------------------- | ----------------------------------- |
| `,cmds`                        | List all available commands         | `,cmds`                             |
| `,bi`                          | Check bot latency and response time | `,bi`                               |
| `,ban @user`                   | Ban a user from the server          | `,ban @Baufunt`                     |
| `,kick @user`                  | Kick a user from the server         | `,kick @Baufunt`                    |
| `,mute @user`                  | Temporarily restrict a user         | `,mute @Baufunt`                    |
| `,remindme 10m "Coffee break"` | Set a personal reminder             | `,remindme 10m "Coffee break"`      |
| `,userinfo @user`              | View information about a user       | `,userinfo @Baufunt`                |
| `,serverinfo`                  | View information about the server   | `,serverinfo`                       |
| `,avatar @user`                | Display a user's avatar             | `,avatar @Baufunt`                  |
| `,clear 10`                    | Delete recent messages              | `,clear 10`                         |
| `,sm 10`                       | Set channel slowmode                | `,sm 10`                            |
| `,lock`                        | Lock the current channel            | `,lock`                             |
| `,unlock`                      | Unlock the current channel          | `,unlock`                           |
| `,warn @user`                  | Issue a warning to a user           | `,warn @Baufunt`                    |
| `,warnings @user`              | View a user's warnings              | `,warnings @Baufunt`                |
| `,unmute @user`                | Remove a user's mute                | `,unmute @Baufunt`                  |
| `,unban userid`                | Unban a user                        | `,unban 123456789`                  |
| `,say message`                 | Send a message through the bot      | `,say Hello everyone`               |
| `,8ball question`              | Get a random response               | `,8ball Will I win?`                |
| `,reminders`                   | View your active reminders          | `,reminders`                        |
| `,help command`                | Get information about a command     | `,help ban`                         |

> **All commands are case-insensitive.**

---

## Moderation

Vailds includes a collection of moderation tools designed to help keep the server organized.

* Ban and kick users
* Temporarily mute users
* Issue and track warnings
* Clear messages in bulk
* Lock and unlock channels
* Configure slowmode
* Manage moderation permissions
* Keep moderation actions organized through logs

Moderation commands can be restricted to users with the appropriate Discord permissions.

---

## Utilities

Vailds also provides several useful tools for everyday server activity.

* User information
* Server information
* Avatar viewing
* Latency checks
* Bot uptime
* Reminders
* Polls
* Random choices
* Dice rolls
* Coin flips
* Custom responses

---

## Reminders

The built-in reminder system allows users to create reminders directly through Discord.

**Example:**

`,remindme 10m "Coffee break"`

You can use different time formats depending on how the reminder system is configured, such as:

* `10m` — 10 minutes
* `2h` — 2 hours
* `1d` — 1 day

Use `,reminders` to view your active reminders.

---

## Automatic Features

Vailds can handle repetitive server tasks automatically.

Possible automatic features include:

* Welcome messages
* Leave messages
* Automated responses
* Moderation logging
* Message filtering
* Server activity logging
* Automatic role assignment
* Custom trigger responses
* Health monitoring

---

## Reliability

Vailds is designed to stay online and recover from common failures automatically.

* Automatic Discord reconnection
* Automatic process recovery
* Health-check endpoints
* Error handling
* Command error recovery
* Runtime logging
* Basic service monitoring

---

## Permissions

Commands that affect other users or server settings require the appropriate Discord permissions.

For example:

* Moderation commands require moderation permissions.
* Channel management commands require channel-management permissions.
* Server configuration commands require administrator-level permissions where necessary.

Vailds does not grant users permissions they do not already have.

---

## Command Format

Most commands follow this format:

`,command [arguments]`

**Example:**

`,ban @user`

Optional arguments can be placed after the command:

`,remindme 30m "Check the server"`

Commands are case-insensitive, so the following are treated the same:

`,CMDS`
`,Cmds`
`,cmds`

---

## Error Handling

If a command cannot be completed, Vailds will provide an appropriate response instead of silently failing.

Common causes include:

* Missing arguments
* Invalid user mentions
* Insufficient permissions
* Missing bot permissions
* Invalid time formats
* Unknown commands
* Discord API errors

---

## Development

Vailds is built with:

* **Node.js**
* **JavaScript**
* **discord.js v14**
* **Discord API**
* Modular command handlers
* Configurable server settings

The project is structured to make adding new commands and features straightforward.

---

## Future Features

Planned or expandable features may include:

* Custom server configuration
* Advanced moderation logs
* Auto-moderation
* Custom command creation
* Reaction roles
* Ticket systems
* Temporary voice channels
* Leveling and XP
* Server statistics
* Advanced reminder management
* Custom welcome systems
* Moderation case management

---

## Support

If you encounter an issue with Vailds, report the problem to the server staff or bot developers with:

1. The command you used
2. What you expected to happen
3. What happened instead
4. Any error message Vailds provided

This helps make troubleshooting faster and easier.

---

## Quick Start

New to Vailds?

Start with:

`,cmds`

Then try:

`,bi`

or:

`,serverinfo`

For information about a specific command:

`,help ban`

Vailds is built to handle the boring stuff, keep things organized, and occasionally make your server a little more interesting.
