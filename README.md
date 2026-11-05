# Spot Arbitrage Screener for Binance and Bybit

A **Spot Arbitrage Screener** is a specialized cryptocurrency trading tool that continuously monitors spot markets across multiple exchanges to identify profitable cross-exchange arbitrage opportunities.


## 🌍 Available Documentation

| Language | Documentation |
|----------|---------------|
| 🇺🇸 English | [README.md](README.md) |
| 🇪🇸 Español (LATAM) | [README_ES.md](README_ES.md) |


---
### Spanish Documentation

Looking for a Binance P2P Bot, Binance P2P Automation, Repricing Binance P2P or Competitor Tracking solution in Spanish?

👉 Read the full Spanish documentation: [README_ES.md](README_ES.md)


Unlike traditional trading bots that focus only on automatic order execution, this software is built primarily as a **real-time arbitrage scanner**. It compares live prices, analyzes order books, checks available liquidity, verifies withdrawal and deposit networks, calculates expected profit, and helps traders discover executable opportunities before they disappear.

Currently, the software supports **Binance** and **Bybit**, allowing traders to monitor hundreds of trading pairs simultaneously without manually switching between exchanges.

<p align="center">
<img src="https://py-dev.top/media/store/products/spot-arbitrage-screener-binance-bybit/thumb_full_spot-arbitrage-screener_mmjBIz9.jpeg">
</p>

Unlike many cloud-based trading services, the Spot Arbitrage Screener is **self-hosted software**. It runs entirely on your own computer or VPS, giving you complete control over your trading environment, exchange connections and API credentials.

There are **no recurring monthly subscriptions**, no vendor lock-in and no dependency on external trading servers. Your exchange API keys remain under your control while the application operates from your own infrastructure.

---

# Why This Is a Screener First, Not Just a Trading Bot

Many cryptocurrency trading bots advertise automation as their primary advantage.

However, in real cross-exchange arbitrage, the biggest challenge is usually not placing an order — it is **finding profitable opportunities before everyone else does**.

Price differences between exchanges often exist for only a few seconds or minutes.

During that time a trader must determine:

* Which exchange offers the lower purchase price
* Which exchange offers the higher selling price
* Whether sufficient liquidity exists
* Whether withdrawal networks are compatible
* Whether transfer fees still leave a profitable spread
* Whether enough volume is available
* Whether the opportunity has existed long enough to be considered reliable

Performing all of these checks manually across hundreds of trading pairs is extremely time-consuming.

The Spot Arbitrage Screener continuously performs these calculations in real time and displays only opportunities that satisfy your configured trading conditions.

Rather than replacing trader decision-making, the software dramatically reduces the time required to identify profitable situations.

Its primary goal is to answer one simple question:

> **"Where is the next executable arbitrage opportunity?"**

---

# Why Choose Self-Hosted Software Instead of SaaS?

Many cryptocurrency arbitrage tools today are offered as **Software as a Service (SaaS)**.

Although cloud services can simplify deployment, they also introduce several limitations:

* recurring monthly payments;
* dependence on third-party servers;
* limited customization;
* subscription restrictions;
* external handling of exchange API connections.

The Spot Arbitrage Screener follows a different philosophy.

It is **self-hosted software** that runs entirely on your own infrastructure.

Whether you prefer Windows, Linux or your own VPS, you maintain complete ownership of your trading environment.

## Self-Hosted vs SaaS

| Feature                          | Spot Arbitrage Screener | Typical SaaS Platform    |
| -------------------------------- | ----------------------- | ------------------------ |
| One-Time Purchase                | ✅ Yes                   | ❌ Usually No             |
| Monthly Subscription             | ❌ Not Required          | ✅ Required               |
| Runs on Your Computer            | ✅ Yes                   | ❌ Usually No             |
| VPS Deployment                   | ✅ Supported             | ⚠ Limited                |
| Full Source Code                 | ✅ Included              | ❌ Closed Platform        |
| API Keys Stay Under Your Control | ✅ Yes                   | ⚠ Depends on Provider    |
| Lifetime License                 | ✅ Yes                   | ❌ Subscription Continues |
| Independent of Vendor Servers    | ✅ Yes                   | ❌ No                     |
| Privacy                          | ✅ Local Execution       | ⚠ Depends on Service     |
| Upgrade on Your Schedule         | ✅ Yes                   | ❌ Controlled by Provider |

For professional traders, infrastructure control is often just as important as trading speed.

Running the software locally means your trading environment remains available even if a third-party SaaS provider changes pricing, introduces usage limits or discontinues its service.

Your exchange API keys stay under your control, trading logic executes on your own machine, and there are no recurring platform fees required to continue using the software.

---

# Main Features

The Spot Arbitrage Screener combines market monitoring, opportunity analysis and optional trading automation into a single application.

## Real-Time Spot Arbitrage Scanning

Continuously monitors Binance and Bybit spot markets to discover cross-exchange arbitrage opportunities.

## Order Book Analysis

Uses real order book data instead of simple ticker prices, allowing more realistic profitability calculations.

## Live Profit Calculation

Calculates estimated profit in both percentage and USD based on current executable prices.

## Liquidity Verification

Checks available market depth before presenting an opportunity.

## Withdrawal Network Analysis

Displays supported withdrawal networks together with associated transfer fees.

## Deposit Network Verification

Verifies whether assets can be deposited to the destination exchange using compatible blockchain networks.

## Opportunity Lifetime Tracking

Shows how long an arbitrage opportunity has remained active.

## Whitelist and Blacklist

Monitor only selected cryptocurrencies while excluding unwanted or low-liquidity assets.

## Telegram Notifications

Receive instant alerts whenever profitable opportunities matching your strategy appear.

## Optional Auto Buy

Automatically place a buy order when configured profit conditions are satisfied.

## VPS Ready

Deploy the software on Windows, Linux or a dedicated VPS for continuous market monitoring.

## Full Source Code

The application includes complete source code, allowing advanced users to inspect, customize and extend functionality according to their own trading requirements.

---

# Live Arbitrage Scanner

The Live Arbitrage Scanner continuously compares supported trading pairs between Binance and Bybit.

Instead of simply displaying price differences, it evaluates whether an arbitrage opportunity is actually executable under current market conditions.

Every detected opportunity includes the information necessary to make an informed trading decision.

### Information displayed for every opportunity

* Trading Pair (BTC/USDT, ETH/USDT, SOL/USDT and many more)
* Buy Exchange
* Sell Exchange
* Buy Price
* Sell Price
* Available Market Volume
* Executable Order Book Liquidity
* Estimated Profit (%)
* Estimated Profit (USD)
* Opportunity Lifetime
* Supported Withdrawal Networks
* Supported Deposit Networks
* Withdrawal Fees
* User-defined Profit Threshold
* Whitelist and Blacklist Validation

Rather than overwhelming traders with raw exchange data, the software filters and organizes market information into a clear list of actionable opportunities.

This allows traders to spend less time monitoring markets manually and more time evaluating profitable trades.

---

# Optional Auto-Buy Function

The primary purpose of the Spot Arbitrage Screener is to discover profitable cross-exchange opportunities as quickly as possible.

For traders who want an additional speed advantage, the software also includes an **optional Auto-Buy mode**.

When enabled, the application continuously monitors all configured trading pairs. As soon as an opportunity reaches your predefined minimum profit threshold, the software can automatically place a **spot buy order** on the exchange offering the lower price.

This significantly reduces reaction time compared to manual execution, which is particularly important because arbitrage opportunities often disappear within seconds.

The Auto-Buy feature is completely optional and can be enabled or disabled at any time.

> **Important**
>
> The standard version focuses on fast opportunity detection and optional buy execution.
> Asset transfers between exchanges and the final sell order remain under the trader's control, allowing every arbitrage opportunity to be reviewed before completion.

---

# Why Opportunity Lifetime Matters

Not every arbitrage opportunity is equally reliable.

A spread that exists for only one or two seconds may disappear before an order can be executed, while opportunities that remain active for a longer period often provide a higher probability of successful execution.

For this reason, the Spot Arbitrage Screener continuously tracks **Opportunity Lifetime**.

Instead of showing only the current profit percentage, the software also records how long each arbitrage opportunity has remained active.

This additional information helps traders distinguish between:

* short market spikes;
* temporary price anomalies;
* more stable arbitrage opportunities.

Many experienced traders use Opportunity Lifetime together with profit percentage when deciding whether an opportunity is worth executing.

---

# Advanced Filters

Every trader follows a different strategy.

Some focus only on Bitcoin and Ethereum.

Others monitor hundreds of alternative cryptocurrencies simultaneously.

To support different trading styles, the Spot Arbitrage Screener includes a comprehensive filtering system.

## Whitelist

Monitor only selected trading pairs or cryptocurrencies.

Example:

* BTC
* ETH
* SOL
* XRP

## Blacklist

Exclude unwanted assets from scanning.

This is particularly useful for ignoring:

* low-liquidity tokens;
* meme coins;
* newly listed assets;
* highly volatile markets.

## Minimum Profit

Display only opportunities that exceed your configured minimum profit percentage.

This helps eliminate low-value spreads that would not justify transfer fees or execution risk.

## Maximum Deposit

Specify the maximum capital used when calculating executable opportunities.

The software estimates realistic trade sizes based on your configured deposit amount.

## Maximum Transaction Size

Limit the maximum amount used for a single opportunity.

This feature can help manage portfolio exposure and reduce trading risk.

## Auto-Buy Profit Threshold

Set an independent profit percentage required before Auto-Buy is allowed to execute.

This threshold may be higher than the minimum display threshold, allowing traders to receive information about smaller opportunities while only automating trades with larger expected returns.

---

# Telegram Notifications

The Spot Arbitrage Screener integrates with Telegram to deliver important trading events directly to your mobile device or desktop.

Notifications can include:

* newly discovered arbitrage opportunities;
* opportunities exceeding your profit threshold;
* Auto-Buy execution events;
* application status updates;
* important trading information.

Telegram integration allows traders to stay informed even when they are away from their trading workstation.

---

# Installation

The Spot Arbitrage Screener is designed for straightforward deployment.

Supported platforms include:

* Windows
* Linux
* VPS servers

## Requirements

* Python 3.x
* Binance API Key
* Binance Secret Key
* Bybit API Key
* Bybit Secret Key
* Telegram Bot Token (optional but recommended)

---

# Configuration

## Step 1 — Create a Telegram Bot

Telegram notifications require a Bot Token generated through **BotFather**.

Detailed instructions:

https://py-dev.top/blog/setup-guides/how-to-create-telegram-bot-botfather-api-token

After creating your Telegram bot, copy the generated token into the configuration file.

Example:

```
BOT_TOKEN = 'YOUR_TELEGRAM_BOT_TOKEN'
```

---

## Step 2 — Configure Binance API

Create a Binance API Key from your Binance account.

The API credentials are used to:

* retrieve market information;
* place optional buy orders;
* access supported trading pairs.

After creating the API Key and Secret Key, add them to the configuration file.

---

## Step 3 — Configure Bybit API

Create a Bybit API Key from your Bybit account.

The software uses these credentials to:

* retrieve live market data;
* compare prices;
* analyze arbitrage opportunities.

Store both the API Key and Secret Key inside the configuration file.

---

## Step 4 — Install Python

If Python is not already installed, download and install the latest Python 3 release.

Installation guide:

https://py-dev.top/blog/setup-guides/how-to-install-python-on-windows

---

## Step 5 — Launch the Software

Extract the application archive.

Open the project folder.

Run:

```
start.bat
```

or launch the application manually using Python.

The software will automatically load current exchange information, available trading pairs, supported blockchain networks and other required market data.

---

# Typical Workflow

A typical trading session follows these steps:

1. Start the Spot Arbitrage Screener.
2. Load market information from Binance and Bybit.
3. Configure filters.
4. Set minimum profit percentage.
5. Define whitelist or blacklist.
6. Enable Telegram notifications (optional).
7. Enable Auto-Buy (optional).
8. Monitor detected arbitrage opportunities.
9. Review opportunity details.
10. Execute the complete arbitrage strategy according to your trading plan.

---

# Frequently Asked Questions

## Does the software automatically complete the entire arbitrage cycle?

No.

The standard version is designed primarily as a Spot Arbitrage Screener with optional automatic buy execution.

Asset transfers and final sell orders remain under the trader's control.

---

## Can I disable Auto-Buy?

Yes.

Auto-Buy is completely optional and can be enabled or disabled at any time.

The software works perfectly as a monitoring and opportunity discovery platform.

---

## Does the software support Binance and Bybit?

Yes.

The current version monitors spot markets on Binance and Bybit.

---

## Are my API Keys stored on external servers?

No.

The Spot Arbitrage Screener is self-hosted software.

Your API credentials remain on your own computer or VPS.

---

## Do I need to pay monthly subscription fees?

No.

The software is distributed under a **one-time payment** model.

There are no recurring monthly subscription fees required to continue using the application.

---

## Can I run the software on my VPS?

Yes.

The Spot Arbitrage Screener supports deployment on Windows, Linux and VPS servers, allowing continuous market monitoring 24 hours a day.

---

## Is the source code included?

Yes.

The software includes full source code, allowing advanced users to inspect, customize and extend functionality according to their own requirements.

---

---

# Available Documentation

Additional documentation is available on the official project website.

These guides explain the software in greater detail, including installation, configuration, trading workflow and practical use cases.

## English Documentation

* Spot Arbitrage Screener for Binance and Bybit
  https://py-dev.top/application-software/spot-arbitrage-screener-binance-bybit

## Español

* Spot Arbitrage Screener para Binance y Bybit
  https://py-dev.top/es/software-de-aplicaciones/spot-arbitrage-screener-binance-bybit

---

### Related Binance P2P Automation Tool

> 📖 **API Reference:** Looking for full Binance SAPI and C2C schema specs? Check out our [Binance SAPI & C2C REST API Reference](https://github.com/pydevtop/binance-c2c-sapi-endpoints) or interactive docs on [py-dev.top/binance-api](https://py-dev.top/binance-api).

If you are interested in cryptocurrency trading automation, you may also find the following projects useful.

## Binance P2P Trade Bot

A professional automation platform for Binance P2P merchants featuring automatic advertisement repricing, competitor tracking, multiple advertisement management and advanced trading automation.

GitHub

https://github.com/pydevtop/p2p-trade-bot-binance

Website

https://py-dev.top/application-software/p2p-trade-bot-binance

---

## Binance P2P Telegram Bot

Python-based automation software for Binance P2P merchants.

Features include:

* Automatic chat replies
* Order tracking
* Payment detection
* Instant crypto release
* Telegram notifications

GitHub

https://github.com/pydevtop/p2p-binance-telegram-bot

Website

https://py-dev.top/application-software/binance-p2p-telegram-bot

---

# Why Traders Choose Spot Arbitrage Screener

Unlike many cloud-based trading platforms, Spot Arbitrage Screener is designed for traders who prefer complete control over their infrastructure.

Instead of relying on third-party SaaS services, you run the software on your own computer or VPS.

This provides several important advantages:

* No recurring monthly subscription fees.
* One-time purchase with lifetime access.
* Full source code included.
* API keys remain under your control.
* Independent of external cloud providers.
* No vendor lock-in.
* Privacy-focused architecture.
* Designed for long-term professional use.

Whether you monitor a handful of trading pairs or hundreds of cryptocurrency markets simultaneously, the Spot Arbitrage Screener helps reduce manual work while providing fast access to real arbitrage opportunities between Binance and Bybit.

---

# Release History

## Version 1.0.3

### July 23, 2025

**Added Can Buy Amount**

The software now calculates the actual amount that can realistically be purchased using current order book liquidity.

This prevents execution on opportunities with insufficient market depth.

---

## Version 1.0.2

### July 19, 2025

Major update introducing the new Spot Arbitrage Screener engine.

New features include:

* Real-time spot arbitrage scanner
* Multi-pair monitoring
* Completely redesigned interface
* ROI filtering
* Volume filtering
* Telegram integration
* Improved performance
* Dynamic loading of Binance and Bybit trading parameters
* Automatic loading of supported withdrawal networks
* Automatic loading of trading limits

---

## Version 1.0.1

### September 20, 2024

Added exchange event notifications showing buy and sell operations during arbitrage execution.

---

# System Requirements

* Windows 10 / Windows 11
* Linux
* Python 3.x
* Binance Account
* Bybit Account
* Internet Connection

Optional:

* VPS Server
* Telegram Bot

---

# Get Spot Arbitrage Screener

Spot Arbitrage Screener is available as a **self-hosted software solution**.

Every license includes:

* Lifetime license
* One-time payment
* Full source code
* Free installation documentation
* Windows support
* Linux support
* VPS deployment
* Binance support
* Bybit support
* Future software updates

Official product page:

👉 https://py-dev.top/es/software-de-aplicaciones)/spot-arbitrage-screener-binance-bybit

---

# Why Self-Hosted Software?

Many trading platforms require continuous subscription payments while storing your trading environment on external servers.

Spot Arbitrage Screener follows a different philosophy.

Your software runs on your own infrastructure.

Your API credentials stay under your control.

Your trading strategy remains private.

Your software continues working without recurring monthly subscription fees.

For many professional traders, self-hosted deployment offers greater privacy, lower long-term cost and complete ownership of the trading environment.

---

# Contact

Questions, licensing requests or commercial inquiries are always welcome.

Telegram

**@morgan_sql**

Official Website

https://py-dev.top

GitHub

https://github.com/pydevtop

---


# License

This repository is distributed under the MIT License.

The software itself is provided as commercial self-hosted software.

Purchasing a license grants access according to the terms published on the official website.

Unauthorized redistribution, resale or publication of commercial releases without permission from the author is prohibited.

If you discover repositories that falsely claim authorship or redistribute commercial versions without authorization, please report them to GitHub Support.

---

# Support the Project

If you find this project useful, consider supporting its development by:

⭐ Starring the repository

🍴 Sharing it with other traders

📖 Reading the documentation

💬 Following future updates

Your support helps improve the software and enables continued development of new cryptocurrency trading tools for the community.

---

**Author**

**PyDev**

Professional Cryptocurrency Trading Software

Binance • Bybit • P2P Automation • Spot Arbitrage • Telegram Automation • Self-Hosted Solutions
