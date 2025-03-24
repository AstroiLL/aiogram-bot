# Telegram Echo Bot

A simple Telegram bot built with aiogram 3.x that echoes back messages to users. This bot demonstrates basic Telegram bot functionality using modern Python async/await patterns.

## Features

- `/start` command handler that greets users with their name
- Echo functionality that sends back any received message
- Error handling for unsupported message types
- HTML formatting support for messages

## Requirements

- Python 3.13 or higher
- Telegram Bot Token (obtain from [@BotFather](https://t.me/BotFather))

## Installation

1. Clone the repository:
```bash
git clone <your-repository-url>
cd aiogram-bot
```

2. Create and activate a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows use: .venv\Scripts\activate
```

3. Install dependencies using uv:
```bash
uv pip install .
```

4. Create a `.env` file in the project root and add your Telegram bot token:
```
TELEGRAM_BOT_TOKEN=your_bot_token_here
```

## Usage

Run the bot:
```bash
python echo_bot.py
```

The bot will start and respond to:
- `/start` command with a personalized greeting
- Any other message by echoing it back to the sender

## Development

This project uses:
- [aiogram](https://docs.aiogram.dev/) - Modern Telegram Bot API framework
- [uv](https://github.com/astral-sh/uv) - Fast Python package installer and resolver
- Python 3.13+ for modern async/await features

## License

[Add your license here]
