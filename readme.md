# Telegram Bot

A Telegram bot for managing attack requests with admin approval system, MongoDB database, and external API integration.

## Features

- 🔐 User approval system with expiration dates
- 👑 Admin commands for user management
- 📊 Attack statistics and logging
- 🚫 Blocked ports validation
- 💾 MongoDB database for persistent storage
- 🔄 24/7 deployment ready (Railway, Heroku, etc.)

## Prerequisites

- Python 3.11 or higher
- MongoDB database (Atlas or local)
- Telegram Bot Token (from @BotFather)
- External API endpoint with authentication key

## Environment Variables Setup

Create a `.env` file in the root directory with the following variables:

```env
BOT_TOKEN=8890953986: AAFaLT1UWKMFZn8v8iv18_KiYSn
-HK2QiKs
MONGODB_URI=your_mongodb_connection_string
DATABASE_NAME=my_database
API_URL=https://your-api-domain.com
API_KEY=your_api_key_here
ADMIN_IDS=123456789,987654321
```
