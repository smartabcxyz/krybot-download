# KryBOT – Automated Gold Trading for MetaTrader 5

KryBOT is an Expert Advisor (EA) designed to automate Gold (XAU/USD) trading on the MetaTrader 5 (MT5) platform. It supports multiple trading styles, from short-duration scalping and intraday trading to configurable longer-term and trend-following strategies.

KryBOT runs directly inside the MT5 terminal using a native `.ex5` file. Key trading parameters can be adjusted through its on-chart dashboard. According to the project description, KryBOT is designed to work with MT5-compatible brokers, including ECN/RAW and Standard accounts.

## Key Features

### 1. Automated Scalping

Monitors Gold market momentum and executes trades automatically when the configured trading conditions are met.

### 2. Short-Term and Trend-Following Trading

Supports intraday trading and can be configured for trend-following or longer-term strategies, rather than focusing exclusively on rapid scalping.

### 3. Multi-Defense Risk Management

KryBOT includes multiple layers of trade protection and risk-management features:

- **1:1 Hedge Lock** — a configurable hedging mechanism.
- **Multi-Tier TP/SL** — multiple take-profit and stop-loss levels.
- **Structure-Based Trailing** — trails positions using newly formed swing highs and lows.
- **Daily Profit Target** — a configurable daily profit threshold.
- **Maximum Daily Loss Protection** — a configurable daily loss limit.

### 4. On-Chart MT5 Dashboard

Adjust settings such as lot size, stop-loss mode, take-profit levels, trailing options, and daily risk limits directly from the dashboard displayed on the chart.

### 5. Telegram Alerts and Controls

Supports Telegram notifications and quick control through the functions provided by the bot.

## Main Parameters Explained

| Parameter | Description |
|---|---|
| **Lot Size** | Sets the trading volume for each order. |
| **Hedge Setting** | Enables or disables the 1:1 Hedge Lock mechanism. |
| **SL Mode** | Selects a stop-loss method, such as fixed points, ATR-based, or structure-based. |
| **TP/SL Tiers** | Configures multiple take-profit and stop-loss levels. |
| **Trailing** | Adjusts trade protection based on newly formed swing highs or lows. |
| **Daily Profit Target** | Sets the target profit threshold for the day. |
| **Max Daily Loss** | Sets the maximum permitted daily loss. |
| **Pause/Resume** | Pauses or resumes the EA using the on-chart panel. |
| **Telegram Alerts** | Enables supported notifications and Telegram controls. |

## Risk Disclaimer

Gold (XAU/USD) can be highly volatile. Hedging, stop-loss orders, trailing mechanisms, and daily limits do not eliminate all trading risks, including slippage, execution differences, or the possibility of substantial losses. Results depend on market conditions, broker execution, and configuration. KryBOT does not guarantee profits. Consider evaluating the EA on a demo account before using real funds.
