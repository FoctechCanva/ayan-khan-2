# Telegram Promotion Bot

This bot sends promotional messages with inline buttons to join Telegram channels.

## Deployment on Render.com

1. Create a new Web Service on Render
2. Connect to this GitHub repository
3. Set environment variables:
   - `TELEGRAM_BOT_TOKEN`: Your bot token from @BotFather
   - `RENDER_EXTERNAL_URL`: Your Render service URL (e.g., `https://your-service-name.onrender.com`)
4. Set build command: `pip install -r requirements.txt`
5. Set start command: `bash start.sh`

## After Deployment

Set webhook manually by visiting: