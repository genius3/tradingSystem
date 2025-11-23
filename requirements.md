I am looking for building an advanced trading signal engine that sends structured BUY/SELL signals to a Telegram channel.
This is a serious, professional project, not a simple indicator bot.


Project Overview

You will be building an upgraded version of a zones-based signal system with:

✔ Signal Generation Engine
✔ Market Condition Filter
✔ Multi-layer Scoring System
✔ High-Confidence Signal Tagging
✔ Double-Up Recommendation Logic
✔ 4-Entry Rule Engine
✔ UI Filters (user commands)
✔ Full Trade Logging System
✔ Telegram Bot Integration
✔ Session, Volatility, and Trend Filters

This system must generate extremely clean, filtered signals by analyzing:
Market structure
Trend alignment (M1 + M5)
Candle confirmations
Volatility (ATR)
Session quality
News events
Zone strength
And classify signals as:
⭐ A-Level (High Confidence / Double-Up Eligible)
⭐ B-Level (Good)
⭐ C-Level (Low Priority)

All logic has already been designed.
You will be responsible for implementing it cleanly and professionally.
You Will Build These Modules
1. Data Module
Pull OHLC data from MT5, TradingView API, or equivalent
Update every second (or as fast as API allows)

2. Signal Engine
Implements:
Trend alignment logic
Zone detection
Candle confirmation detection
ATR-based volatility filtering
4-entry rule logic

3. Market Condition Analyzer
Scores market 0–8 based on:
* Volume/session
* ATR range
* Market structure clarity
* News filter
* Spread conditions

Outputs one of:
* PEAK
* GOOD
* NORMAL
* BAD

4. Scoring + Classification Engine
Score each signal 0–10 based on:
* Trend
* Zone strength
* Confirmation
* Volatility
* Session
* News

Classification:
* 8–10 = A (High Confidence / Double Up)
* 6–7 = B
* 4–5 = C
* 0–3 = Reject (No signal)

5. Telegram Bot
 Features:
* Sends formatted signals
* Responds to user filters
* Shows market condition header
* Exports logs
* Allows filtering by signal level
* Optional OTC toggle

6. Trade Logging System
 Stores for each signal:
* Timestamp
* Pair
* Score
* Confidence grade
* Market condition
* Entry result
* Every entry price (Entry 1–4)
* Final outcome
* Stored in JSON, CSV, or SQLite.

Deliverables
✔ Fully working signal engine
✔ Telegram bot with all commands
✔ Clean, scalable code
✔ Documentation for installation
✔ One-time setup + testing
✔ Ability to run 24/7
✔ (Optional) Backtesting script

Required Tools/implementation approaches to apply
To apply, you MUST have experience with:
✔ Python
✔ Telegram Bot API
✔ MT5/MT4 or TradingView API
✔ OHLC data processing
✔ Building trading indicators or bots
✔ Algorithmic strategy logic
✔ Volatility + trend detection
✔ Backtesting experience
