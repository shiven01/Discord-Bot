# Discord Bot

A Discord bot built with discord.js that provides utility commands including ping, server information, and user information.

## Features

- `/ping` - Simple ping command to check if the bot is responsive
- `/server` - Displays information about the current server
- `/user` - Shows information about the user who ran the command

## Prerequisites

- Node.js v18.0.0 or newer
- Discord.js v14.x
- A Discord Bot Token (from Discord Developer Portal)

## Installation

1. Clone the repository:
```bash
git clone [your-repository-url]
cd [your-repository-name]
```

2. Install dependencies:
```bash
npm install
```

3. Create a `config.json` file in the root directory with your bot credentials:
```json
{
    "token": "YOUR_BOT_TOKEN",
    "clientId": "YOUR_CLIENT_ID",
    "guildId": "YOUR_GUILD_ID"
}
```

4. Deploy commands:
```bash
node deploy-commands.js
```

5. Start the bot:
```bash
node index.js
```

## Usage

Once the bot is running, you can use the following slash commands in your Discord server:
- `/ping` - Bot responds with "Pong!"
- `/server` - Shows server name and member count
- `/user` - Displays information about the user who used the command

## Project Structure

```
Discord-Bot/
├── commands/
│   └── utility/
│       ├── ping.js
│       ├── server.js
│       └── user.js
├── config.json
├── deploy-commands.js
├── index.js
├── package.json
└── README.md
```

## Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

Shiven Shekar
