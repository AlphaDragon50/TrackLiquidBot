[![Invite](https://img.shields.io/badge/Invite-TrackLiquid-blue)](https://discord.com/oauth2/authorize?client_id=1366056784049082398&permissions=92160&integration_type=0&scope=bot+applications.commands)
[![Support](https://img.shields.io/badge/Support-Discord-7289DA)](https://discord.gg/ZwUmxk2Y3B)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE.md)

# 📡 TrackLiquid — Hyperliquid Wallet Tracker

TrackLiquid brings real-time Hyperliquid perp position alerts straight into your Discord server.

---

## 🚀 Quick Start

1. **Invite TrackLiquid**  
   Click your personal invite link and choose a server.

2. **Pick Your Alerts Channel**  
   `/setchannel` → select the channel where alerts should post.

3. **Add Wallets to Track (up to 3)**  
   `/addwallet 0x5078c2fbea2...bedb6 [Whale]`  
   *Optional alias helps you read alerts at a glance.*

4. **View Unrealized PnL**  
   `/unrealized` → select a tracked wallet to see its current unrealized P&L.

---

## ⚙️ Core Commands

| Command           | Description                                                                                   |
|-------------------|-----------------------------------------------------------------------------------------------|
| `/help`           | Show a quick reminder of all available commands.                                              |
| `/addwallet`      | Track a new wallet (with an optional alias). Use up to 3 wallets per server.                  |
| `/listwallets`    | Quickly list your tracked wallets and aliases.                                                |
| `/managewallet`   | View, rename, or remove any tracked wallet (includes “Remove All”).                           |
| `/openpositions`  | Show current open PERP positions for a tracked wallet (size, entry price, leverage, P&L).    |
| `/unrealized`     | Show unrealized PnL for a tracked wallet.                                                     |
| `/setchannel`     | Choose which channel receives perp notifications (leave blank to clear).                      |
| `/status`         | Display bot uptime and how many wallets you’re tracking (e.g. `2/3`).                         |

---

## 💡 Examples

- **Add a wallet with an (optional) alias**  
  `/addwallet 0xABC...123 MyTradingWallet`  
  <div align="center">
    <img src="./assets/addwallet.prompt.PNG" alt="Add Wallet Prompt" width="300" />
    <img src="./assets/addwallet.embed.PNG"  alt="Add Wallet Confirmation" width="300" />
  </div>

- **List & manage wallets**  
  `/managewallet` → choose “MyTradingWallet” → rename, remove, or clear all.  
  <div align="center">
    <img src="./assets/managewallet_panel.PNG" alt="Manage Wallet Panel" width="300" />
    <img src="./assets/managewallet_embed.PNG" alt="Manage Wallet Embed" width="300" />
  </div>

- **Check open positions**  
  `/openpositions` → select your wallet → see entry price, size, leverage, PnL.  
  <div align="center">
    <img src="./assets/openpositions_embed.PNG" alt="Open Positions Embed" width="300" />
  </div>

- **Check Unrealized PnL**  
  `/unrealized` → select your wallet → shows current unrealized profit & loss.  
  <div align="center">
    <img src="./assets/unrealized_embed.PNG" alt="Unrealized PnL Embed" width="300" />
  </div>

- **View bot status**  
  `/status` → shows uptime and number of tracked wallets (e.g. `2/3`).  
  <div align="center">
    <img src="./assets/status_embed.PNG" alt="Status Embed" width="300" />
  </div>

---

## 🤝 Support

If you hit a snag or have a feature request, join our Support Server:  
👉 https://discord.gg/ZwUmxk2Y3B

---

© 2025 AlphaDragon50 · [MIT License](./LICENSE.md)  
