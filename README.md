# CombatCenter

The CombatCenter is a plugin for Paper servers that helps track player combat. It is lightweight. Made for servers that want more than just simple kill counters. The CombatCenter plugin is easy to use. Does not add unnecessary complexity.

## Features

- PVP toggle system

- Combat Profile GUI for personal stats

- Combat History to view past fights

- Leaderboard categories

- Killstreak tracking with optional rewards

- Weapon kill and damage dealt statistics

- Totem pop statistics

- SQLite database

- Configurable messages, including hex color support

- The CombatCenter is lightweight and optimized for performance

## Statistics Tracked

- The CombatCenter tracks kills

- It tracks deaths

- The plugin tracks the K/D Ratio

- It tracks the current killstreak

- The CombatCenter tracks the highest killstreak

- It tracks damage dealt

- The plugin tracks damage taken

- It tracks totem pops

- The CombatCenter tracks weapon kills

## Statistics

- Kills
- Deaths
- K/D Ratio
- Current Killstreak
- Highest Killstreak
- Damage Dealt
- Damage Taken
- Totem Pops
- Weapon Kills

## Combat History

Every time a player dies in PvP the CombatCenter records it. You can view past fights through the Combat History GUI. Each entry shows the opponent, the weapon used damage dealt, damage taken killstreak and the time since the fight.

## Killstreak Rewards

The CombatCenter has configurable killstreak rewards. Each reward can execute commands play sounds send messages and broadcast announcements. For example:

```yaml

killstreak-rewards:

enabled:

rewards:

5:

message: "&6Five kill streak!"

broadcast: "&e%player% is on a %streak% kill streak!"

sound: UI_TOAST_CHALLENGE_COMPLETE

commands:

- "eco give %player% 500"

```

## Commands

| Command | Description |

|----------|-------------|

| `/pvp` | Opens the CombatCenter

| `/pvp on` Turns on PvP

| `/pvp off` | Turns off PvP

| `/pvp history` | Opens combat history

| `/pvp stats` | Views your combat profile

| `/pvp top` | Views leaderboards

### Admin Commands

| Command | Description |

|----------|-------------|

/pvp reload` | Reloads configuration

| `/pvp resetstats <player>` | Resets a players statistics

| `/pvp clearhistory <player>` | Clears a players combat history

| `/pvp forcetoggle <player> <on/off>` | Change another player's PvP status |

## Permissions

| Permission | Description |

|------------|-------------|

| `combatcenter.use` | Allows use of the CombatCenter |
| `combatcenter.admin` | Access to admin commands |

## Configuration

The CombatCenter configuration files.

- `Config.yml`

- `messages.yml`

All player-facing messages can be changed.

## Placeholders

### Killstreak Rewards

| Placeholder | Description |
|-------------|-------------|
| `%player%` | Player name |
| `%streak%` | Current killstreak |

## Requirements

- Paper 1.21+, 26.2

- Java 21

## Database

The CombatCenter stores data in a local SQLite database.

Tracked player statistics, weapon statistics and combat history.

No additional database software is needed.

## Support

If you have a problem or want a feature please open an issue on GitHub, make a ticket on our discord or, visit our site!

https://buzzleshivecorp.com/

## Usage

CombatCenter is provided free of charge for personal and commercial Minecraft servers.

You may:
- Use CombatCenter on any server.
- Modify the configuration files for your server.

You may not:
- Redistribute the plugin or its source code.
- Sell or re-upload CombatCenter on another website.
- Claim CombatCenter or its source code as your own work.
- Remove or alter copyright notices included with the plugin.

If you'd like to share CombatCenter with others, please link to the official download page instead of uploading the files elsewhere.

## 🐝 Buzzle’s Hive

Built as part of the Buzzle’s Hive ecosystem.
Focused on performance, simplicity, and clean server experiences.
