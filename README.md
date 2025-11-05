# The Ultimate Utility Bot in Python

This is a powerful and versatile Discord bot built with Python, designed to provide a wide range of utility features to your server. From moderation to fun interactive elements and information lookup, this bot aims to be a comprehensive solution for your Discord server management and entertainment needs.

## Features

The bot's functionalities are organized into several categories (cogs):

### General
- `botinfo`: Displays information about the bot.
- `help`: Provides a list of commands and their usage.
- `ping`: Checks the bot's latency.
- `uptime`: Shows how long the bot has been running.

### Information Lookup
- `avatar`: Retrieves a user's avatar.
- `channelinfo`: Displays information about a specific channel.
- `define`: Provides definitions for words.
- `imdb`: Searches for movie information on IMDb.
- `invite`: Generates an invite link for the bot.
- `reddit`: Fetches content from Reddit.
- `roleinfo`: Shows information about a specific role.
- `serverinfo`: Displays information about the Discord server.
- `steam`: Looks up Steam game information.
- `twitch`: Fetches Twitch stream information.
- `urban`: Searches for definitions on Urban Dictionary.
- `userinfo`: Displays information about a user.
- `weather`: Provides weather information for a given location.
- `youtube`: Searches for YouTube videos.

### Interactive Elements
- `loop`: Loops the current song (likely for music bots).
- `lyrics`: Fetches lyrics for a song.
- `meme`: Generates random memes.
- `play`: Plays music (likely from YouTube or other sources).
- `skip`: Skips the current song.
- `volume`: Adjusts the music volume.

### Moderation
- `permissions`: Manages user permissions.

### Server Management
- `autorole`: Automatically assigns roles to new members.
- `ban`: Bans a user from the server.
- `clear`: Clears a specified number of messages.
- `goodbye`: Sends a goodbye message when a member leaves.
- `kick`: Kicks a user from the server.
- `lock`: Locks a channel.
- `mute`: Mutes a user.
- `slowmode`: Sets slowmode for a channel.
- `unban`: Unbans a user.
- `unlock`: Unlocks a channel.
- `unmute`: Unmutes a user.
- `warn`: Warns a user.
- `warnings`: Displays a user's warnings.
- `welcome`: Sends a welcome message to new members.

### Utilities
- `ascii`: Converts text to ASCII art.
- `base64`: Encodes/decodes Base64.
- `color`: Displays color information.
- `embedbuilder`: Helps create custom embeds.
- `leaderboard`: Displays a leaderboard (likely for levels or other stats).
- `level`: Manages user levels and experience.
- `qr`: Generates QR codes.
- `remind`: Sets reminders.
- `shorten`: Shortens URLs.
- `stats`: Displays various statistics.
- `suggest`: Manages suggestions.
- `ticket`: Manages support tickets.
- `timestamp`: Generates timestamps.
- `translate`: Translates text.

## Setup

To set up and run this bot, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/shubh6801/The-utility-bot.git
cd The-utility-bot
```

### 2. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
./venv/Scripts/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Environment Variables

Create a `.env` file in the root directory of the project and add the following:

```
DISCORD_BOT_TOKEN=YOUR_BOT_TOKEN_HERE
# Add any other API keys or sensitive information here
```

Replace `YOUR_BOT_TOKEN_HERE` with your actual Discord bot token. You can get this from the Discord Developer Portal.

### 5. Run the Bot

```bash
python bot.py
```

## Configuration

The `config` directory contains JSON files for various configurations, such as:
- `autoroles.json`
- `goodbye_messages.json`
- `reminders.json`
- `suggestions.json`
- `ticket_config.json`
- `warnings.json`
- `welcome_messages.json`
- `xp.json`

These files allow you to customize the bot's behavior without modifying the code.


