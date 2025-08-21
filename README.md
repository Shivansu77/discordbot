# Discord Bot

A simple yet powerful Discord bot built with Discord.js that can create threads and respond to slash commands.

## ✨ Features

- Create threads from messages
- Slash command support
- Easy to extend with new commands
- Error handling and logging
- Environment variable configuration

## 🚀 Getting Started

### Prerequisites

- Node.js v16.9.0 or higher
- npm or yarn package manager
- Discord Bot Token from [Discord Developer Portal](https://discord.com/developers/applications)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/discord-bot.git
   cd discord-bot
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Create a `.env` file in the root directory with your bot token:
   ```env
   DISCORD_TOKEN=your_bot_token_here
   ```

### Usage

1. Start the bot:
   ```bash
   node index.js
   ```

2. Invite the bot to your server using the following URL (replace `CLIENT_ID` with your bot's client ID):
   ```
   https://discord.com/oauth2/authorize?client_id=CLIENT_ID&permissions=8&scope=bot%20applications.commands
   ```

## 🤖 Commands

### Message Commands
- `create [url]` - Creates a new thread with the provided URL

### Slash Commands
- `/ping` - Replies with 'Pong!'

## 📁 Project Structure

```
discord-bot/
├── commands/          # Slash command files
├── node_modules/      # Dependencies
├── .env               # Environment variables
├── .env.example       # Example environment variables
├── .gitignore         # Git ignore file
├── index.js           # Main bot file
├── package.json       # Project manifest
└── README.md          # This file
```

## 🔧 Configuration

Copy `.env.example` to `.env` and update the values:

```env
DISCORD_TOKEN=your_bot_token_here
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Discord.js](https://discord.js.org/)
- [Node.js](https://nodejs.org/)
- [dotenv](https://www.npmjs.com/package/dotenv)
