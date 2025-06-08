# BTCAnalysisBot
A Telegram bot for real-time Bitcoin (BTC) analysis with >80% accuracy.

## Features
- Python 3.8+
- Telegram Bot Token (@BotFather)
- CoinGecko API (free)
- Binance API (optional)
- X API (optional for sentiment analysis)
- Free hosting (e.g., Heroku, Render)

## Setup
1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd BTCAnalysisBot
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Configure APIs:
   - Create `src/config.py` with your API keys (see `config.py` example).
4. Run the bot:
   ```bash
   python src/main.py
5. Deploy to Heroku:
   - Create a Heroku app.
   - Push the repository to Heroku.
   - Set environment variables for API keys.

## Commands
- `/start`: Start the bot.
- `/price`: Get current BTC price.
- `/analyze`: Get technical analysis with charts.
- `/alert <price>`: Set a price alert.

## License
MIT
