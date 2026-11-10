# AlphaSync Global

**A desktop trading terminal for Exness accounts.** Charts, a trend scanner, rule-based strategies, a backtester, automated trading and a risk dashboard, in one Windows app. It runs on your own computer and talks to your Exness account through your own API key.

> **Download:** go to the [**Releases**](../../releases/latest) page and get `AlphaSync-Setup-x.y.z.exe`.

---

## What you get

| | |
|---|---|
| **Live dashboard** | Balance, equity, floating P&L, margin level, equity curve and open positions, straight from your Exness account. |
| **Trade** | Candlestick and other chart types, 18 built-in indicators, your own formula indicators, order ticket with lot size, stop loss and take profit. |
| **Market scanner** | Trend board across pairs (H1 and M15 direction, strength, RSI, ATR, spread) and a scanner that keeps searching for graded trade setups. |
| **Strategies and backtest** | Rule-based strategies with filters, tested on real Exness candles before you use them. |
| **Auto trading** | A trend engine and a Gold (XAUUSD) scalper that trade the pairs you choose. They are **off after every restart** and only manage trades they opened. |
| **Risk controls** | Mandatory stop loss, lot and position caps, daily profit and loss limits, a kill switch and **Flatten all**. |
| **Multiple accounts** | Save several Exness accounts and switch between them. |
| **Notifications** | Alerts for opportunities, orders, margin and connection problems. |
| **Light and dark themes** | Pick the look you prefer. |

## Install

1. Download `AlphaSync-Setup-x.y.z.exe` from the [latest release](../../releases/latest).
2. Run it and follow the steps. It installs for your user account and does not need administrator rights by default.
3. Open AlphaSync, create your local account, then connect your Exness API key on the **Broker** page.

**Requirements:** Windows 10 or 11 (64-bit) and the Microsoft Edge WebView2 Runtime (already included in Windows 11 and up-to-date Windows 10).

> Windows may show a "Windows protected your PC" notice because the installer is not yet code-signed. Choose **More info**, then **Run anyway**.

## Updates happen inside the app

You never need to come back here to update. When a new version is released, AlphaSync shows a banner:

**"AlphaSync 1.x is available."**, with **What's new**, **Update now** and **Later**.

Click **Update now**. AlphaSync downloads the update, verifies it, installs it and reopens itself. Your accounts, settings and history are kept.

- An update is never installed while auto trading is running or you have open positions.
- Every download is checked against a SHA-256 checksum before it runs.
- You can also check by hand from the profile menu: **Check for updates**.

## Your data and privacy

- Everything runs on your computer. Your Exness credentials are stored locally, never leave your machine except to talk to Exness, and are never shown back in the page.
- Your data lives in `%APPDATA%\AlphaSync`. Uninstalling lets you choose whether to keep or delete it.
- AlphaSync only contacts this repository to look for new versions.

## Safety first

- Connect a **demo account** first and get comfortable before using real money.
- A real-money account stays locked until you confirm it on purpose.
- Open trades keep their stop loss and take profit at Exness even if AlphaSync is closed.

## Risk disclaimer

Trading leveraged products such as forex and gold carries a high risk of loss and is not suitable for everyone. AlphaSync is a software tool, not financial advice, and it does not guarantee profit. Past or backtested results do not predict future results. You are responsible for every trade placed from your account. AlphaSync is not affiliated with or endorsed by Exness.

## Releases

Each release on the [Releases](../../releases) page contains the installer and a `latest.json` file that installed copies of AlphaSync read to find updates. Please do not edit or delete it.

## Support

Open an [issue](../../issues) in this repository for bugs or questions. Please do not post API keys, private keys or account numbers.
