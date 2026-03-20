# SellAuth Discord Bot

Discord bot for SellAuth invoice, replacement, and coupon management.

## Features
- Invoice lookup via SellAuth API
- Product replacement handling
- Coupon management
- Staff logging channel
- Permission system (Staff / Server Manager / Owner)
- Git clone or manual file upload support

## Install

1. In Pelican Panel → Eggs → Import Egg
2. Upload `egg-sellauth-discord-bot.json`

## Environment Variables

| Variable | Description |
|----------|-------------|
| `DISCORD_TOKEN` | Discord bot token |
| `DISCORD_CLIENT_ID` | Discord application client ID |
| `DISCORD_GUILD_ID` | Discord server (guild) ID |
| `SELLAUTH_API_KEY` | SellAuth API key |
| `SELLAUTH_SHOP_ID` | SellAuth shop ID |
| `SELLAUTH_SHOP_URL` | SellAuth shop URL |
| `STAFF_ROLE_ID` | Role ID for staff permissions |
| `SERVER_MANAGER_ROLE_ID` | Role ID for server manager permissions |
| `OWNER_ROLE_ID` | Role ID for owner permissions |
| `LOG_CHANNEL_ID` | Channel ID for staff action logs |
