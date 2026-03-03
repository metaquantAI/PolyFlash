# PolyFlash ⚡

**Professional Polymarket Trading Bot**  
By **[MetaQuant Universe](https://metaquantuniverse.com)**  
[Official Polymarket Page](https://metaquantuniverse.com/polymarket)

---

## 🚀 Why PolyFlash?

PolyFlash is a **beginner-friendly yet powerful** Python trading bot for Polymarket.  
It combines real-time WebSocket data, gasless trading, built-in strategies, and ultra-simple deployment — perfect for both personal use and **commercial distribution**.

Whether you want to automate your own trading or sell ready-to-use versions to your clients, PolyFlash is designed for speed, security, and easy rebranding.

---

## ✨ Key Features

- **Simple & Clean API** — Start trading in just a few lines of code  
- **Gasless Trading** — Zero gas fees with Polymarket Builder Program  
- **Real-time WebSocket** — Live orderbook updates with zero delay  
- **15-Minute Markets Support** — BTC, ETH, SOL, XRP Up/Down markets  
- **Flash Crash Strategy** — Ready-to-use volatility scalping strategy  
- **Terminal UI** — Beautiful real-time orderbook display  
- **Secure Key Storage** — Private keys encrypted with PBKDF2 + Fernet  
- **Paper Trading Mode** — Test safely before going live  
- **89+ Unit Tests** — Fully tested and reliable  
- **One-Click Launch** — `run.bat` for Windows clients (no coding needed)  
- **Easy Monetization** — Ready for White-Label, SaaS, or one-time sales

---

## 🚀 Ultra-Fast Installation (Windows – 2 minutes)

1. **Double-click `run.bat`** (recommended for clients)  
2. Fill your `.env` file  
3. The bot starts automatically!

### Manual Installation (for developers)

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python examples/quickstart.py

Configuration – .env File
Copy .env.example → rename to .env and fill:
env# PolyFlash ⚡ - MetaQuant Universe
POLY_PRIVATE_KEY=0x...
POLY_SAFE_ADDRESS=0x...
POLY_BUILDER_API_KEY=          # Optional - for gasless
POLY_BUILDER_API_SECRET=       # Optional
POLY_BUILDER_API_PASSPHRASE=   # Optional
POLY_RPC_URL=https://polygon-rpc.com
POLY_LOG_LEVEL=INFO
Get your Safe Address here: polymarket.com/settings
Enable gasless: Apply for Builder Program on the same page.

Available Strategies & Examples
1. Flash Crash Strategy (most popular)
Bashpython strategies/flash_crash_strategy.py --coin BTC --size 10
Automatically buys when probability drops suddenly and takes profit.
2. Real-time Orderbook TUI
Bashpython strategies/orderbook_tui.py --coin ETH --levels 10
3. Examples Folder

quickstart.py → First test
basic_trading.py → Place/cancel orders
strategy_example.py → Create your own strategies

Full strategy guide: docs/strategy_guide.md

Advanced Features (Ready for Monetization)

Telegram Notifications – Add in 5 minutes
Web Dashboard – Real-time monitoring
EXE Version – One-click executable for clients (PyInstaller)
Docker Support – For cloud/SaaS deployment
White-Label Ready – Change logo, name, colors in minutes

Want me to add these for you? Just say the word.

For Clients & Resellers (Business Edition)
This bot is 100% designed for easy distribution:

Clients just double-click run.bat
No Python knowledge required
You can sell as:
One-time license ($99–$299)
Monthly subscription with updates
White-label version under your brand


Official Site: https://metaquantuniverse.com/polymarket

⚠️ Important Disclaimer

Trading involves substantial risk of loss.
This is a technical tool only — no financial advice.
Use a dedicated wallet and never share your private key.
Always test in paper mode first.


License
MIT License – feel free to fork, modify, and commercialize (just keep the original copyright notice).

Made with ❤️ by MetaQuant Universe
Questions? Need custom features or White-Label version?
→ Visit metaquantuniverse.com/polymarket

Star this repo if you like it! ⭐
