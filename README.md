# MakiMusicBot
a telegram music bot for streaming music in telegram group vc
```markdown
# Telegram Music Bot

Welcome to the Telegram Music Bot project! This bot allows users to stream music and videos from YouTube in voice chats on Telegram.

## Installation and Deployment

### VPS Deployment

1. **Prerequisites:**

   - Python 3.7+
   - MongoDB
   - FFmpeg

2. **Clone the Repository:**

   ```bash
   git clone https://github.com/your-username/telegram-music-bot.git
   cd telegram-music-bot
   ```

3. **Install Dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Create `.env` File:**

   Create a `.env` file in the project directory with the following content:

   ```env
   API_ID=your_api_id
   API_HASH=your_api_hash
   SESSION_STRING=your_session_string
   MONGODB_URI=your_mongodb_uri
   YOUTUBE_API_KEY=your_youtube_api_key
   ```

5. **Run the Bot:**

   ```bash
   python bot.py
   ```

### Heroku Deployment

Click the button below to deploy the bot to Heroku:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Koyeb Deployment

Click the button below to deploy the bot to Koyeb:

[![Deploy](https://deploy.koyeb.com/button.svg)](https://deploy.koyeb.com/deploy)

### Railware Deployment

Click the button below to deploy the bot to Railware:

[![Deploy](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/your-username/telegram-music-bot&envs=API_ID,API_HASH,SESSION_STRING,MONGODB_URI,YOUTUBE_API_KEY)

## Usage

1. **Add the Bot to a Telegram Group:**

   Invite the bot to your Telegram group by searching for its username (@your_bot_username).

2. **Bot Commands:**

   - `/start`: Start the bot and get usage instructions.
   - `/play <song name>`: Play a song from YouTube by name.
   - `/play <YouTube link>`: Play a specific YouTube video.
   - `/video <YouTube link>`: Stream the entire video.
   - `/skip`: Skip the current track.
   - `/stop`: Stop the playback.
   - `/queue`: View the current playback queue.

## License

This project is licensed under the [MIT License](LICENSE).
```

Remember to replace placeholders such as `your-username`, `your_api_id`, `your_api_hash`, `your_session_string`, `your_mongodb_uri`, and `your_youtube_api_key` with your actual information. The above content provides a comprehensive guide for installation, deployment, usage, and licensing for your Telegram Music Bot project.
