# Discord Ticket Bot

## Overview
Advanced Discord Ticket System Bot built with discord.js v14. This bot provides a modern and fully customizable ticket system with dynamic panels, claim system, and staff management tools.

## Features
- Dynamic ticket panel system (buttons and select menus)
- Per-button category system
- Role-based ticket handling
- Claim and unclaim system with points tracking
- Staff tools (add/remove users, rename, transfer ownership)
- Ticket close, reopen, and delete system
- Clean UI using Discord Components V2
- Fast and optimized structure

## Project Structure
index.js  
events/interactionCreate.js  
commands/  
database/  
database/tickets/  
database/numbers.json  
.env  

## Setup

### 1. Install dependencies
npm install

### 2. Create .env file
Create a file named .env and add:

DISCORD_TOKEN=
CLIENT_ID=
GUILD_ID=
OWNER_ID=

### 3. Run bot
node index.js

## Requirements
- Node.js v16.9.0 or higher
- Discord Bot Token
- Enabled intents in Discord Developer Portal

## Notes
- Make sure the bot has proper permissions:
  - Manage Channels
  - Manage Roles
  - Send Messages
  - Read Message History

- Keep database folder writable
- Restart bot after any configuration change

## License
This project is licensed under the MIT License.

## Author
hvtvv072
