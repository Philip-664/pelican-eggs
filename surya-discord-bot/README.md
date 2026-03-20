# Surya Discord Bot (TypeScript)

Discord.js v14 TypeScript bot for matchmaking and game room management.

## Features
- Matchmaking queue system (1v1, 2v2, 3v3, 4v4)
- Platform support: Mobile, Misto, Emulador
- Betting rooms
- Points & leaderboard system
- Staff moderation commands
- Auto-build TypeScript on start

## Install

1. In Pelican Panel → Eggs → Import Egg
2. Upload `egg-surya-discord-bot.json`

## Environment Variables

| Variable | Description |
|----------|-------------|
| `DISCORD_TOKEN` | Your Discord bot token |
| `CLIENT_ID` | Discord application client ID |
| `GUILD_IDS` | Comma-separated guild IDs |
| `AUTO_UPDATE` | Set to `1` to auto git pull on start |
