# 🏥 Healthcare Lead Discovery Agent

**CLEAN VERSION - 3 STEPS ONLY**

## 🎯 What it does:
1. **EXA Search** → Find healthcare practices  
2. **Notion Storage** → Store leads with scoring
3. **Telegram Bot** → Interface for interaction

## 🚀 Quick Start:

```bash
# Install dependencies
npm install

# Set environment variables
export EXA_API_KEY="your-exa-key"
export NOTION_DATABASE_ID="your-notion-db-id" 
export NOTION_API_KEY="your-notion-key"
export TELEGRAM_BOT_TOKEN="your-telegram-token"

# Start the agent
npm start
```

## 📡 Endpoints:
- `POST /automate` - Process healthcare practice URL
- `POST /telegram-webhook` - Telegram bot webhook
- `GET /health` - Health check

## 🛠 Deploy to Railway:
1. Connect this repo to Railway
2. Set environment variables in Railway dashboard  
3. Deploy automatically with Railway.toml

**NO NEXT.JS, NO COMPLEXITY - JUST THE HEALTHCARE AGENT**