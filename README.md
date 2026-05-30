<div align="center">

# 🦄 Mercaria Unicorn GOLD EA

### Adaptive Grid Trading System for MetaTrader 5 · XAUUSD-optimized

[![Platform](https://img.shields.io/badge/Platform-MetaTrader%205-2b6cb0)](https://www.mql5.com/en/market/product/177680)
[![Instrument](https://img.shields.io/badge/Instrument-XAUUSD%20(Gold)-d4af37)](https://www.mql5.com/en/market/product/177680)
[![Version](https://img.shields.io/badge/Version-3.572-6b46c1)](https://www.mql5.com/en/market/product/177680)
[![MQL5 Market](https://img.shields.io/badge/Buy%20on-MQL5%20Market-orange)](https://www.mql5.com/en/market/product/177680)
[![YouTube](https://img.shields.io/badge/YouTube-Live%20Runs-red)](https://www.youtube.com/@Mercaria_Official)

**[🛒 Get it on MQL5 Market](https://www.mql5.com/en/market/product/177680)** · **[▶️ Watch live runs](https://www.youtube.com/@Mercaria_Official)** · **[✈️ Telegram](https://t.me/mercaria)** · **[🌐 Website](https://www.mibase.online/ea)**

</div>

---

## What is it?

**Mercaria Unicorn GOLD EA is an adaptive grid trading robot for MetaTrader 5, optimized for Gold (XAUUSD).** It automatically scales grid levels, lot sizes, and stop thresholds to your account equity across four selectable volatility profiles — **Normal, Spike M, Spike L, and Black Swan** — so the same risk profile works on a $1k, $10k, or $100k account without manual recalculation.

Unlike typical "fixed‑parameter" grids that trade blindly, Unicorn calculates the safest number of levels and lot size for your deposit and chosen market model — with transparent margin formulas and worst‑case forecasts shown directly on the chart panel. No black box.

> **Who it's for:** traders who want a ready‑made, math‑driven position manager — from beginners (1–2 yrs) using the pre‑configured profiles, to professionals using it purely as an execution/recovery engine on top of their own entries.

---

## 📊 Live & Demo Results

Documented sessions on real and demo accounts (RoboForex, USD). Full verified history, equity curves and reviews are on the **[MQL5 product page](https://www.mql5.com/en/market/product/177680)**.

| Account | Type | Broker | Gain | Max Drawdown |
|:--|:--:|:--:|:--:|:--:|
| Live #1 | **Real** | RoboForex | **+534%** | 14.7% |
| Live #2 | **Real** | RoboForex | **+87.7%** | 8.1% |
| Demo ($10,000 → $12,912) | Demo | RoboForex | **+29.1%** | 1.2% |

**Recorded live test runs (YouTube):**

| Session | Result |
|:--|:--|
| Live run on XAUUSD | **+20% balance** in ~40 min |
| Live run on XAUUSD | **+25% balance** in ~2 hours |
| Live run on XAUUSD | **+10% balance** in ~2 hours |
| Live run on XAUUSD | **+10% balance** in ~1 hour |

> ⚠️ **Risk disclaimer.** The figures above are from individual real/demo sessions and **do not guarantee future performance**. Grid strategies are sensitive to broker conditions (spread, commission, swap). Trading leveraged instruments such as Gold (XAUUSD) carries a significant risk of loss. Always test on a demo account first and never risk capital you cannot afford to lose.

---

## ▶️ Video Walkthroughs

<div align="center">

[![+20% balance in 40 min](https://img.youtube.com/vi/7upSJgX2cww/hqdefault.jpg)](https://www.youtube.com/watch?v=7upSJgX2cww)
[![+25% balance in 2 hours](https://img.youtube.com/vi/QMWAYeDfixg/hqdefault.jpg)](https://www.youtube.com/watch?v=QMWAYeDfixg)

[![+10% balance in 2 hours](https://img.youtube.com/vi/UQ7MmLNcQA4/hqdefault.jpg)](https://www.youtube.com/watch?v=UQ7MmLNcQA4)
[![+10% balance in 1 hour](https://img.youtube.com/vi/DoJNDuzMEQo/hqdefault.jpg)](https://www.youtube.com/watch?v=DoJNDuzMEQo)

**▶️ All videos on the [Mercaria YouTube channel](https://www.youtube.com/@Mercaria_Official)**

</div>

---

## ⚙️ Key Features

| Feature | What it does |
|:--|:--|
| **4 Volatility Profiles** | Switch NORMAL / SPIKE_M / SPIKE_L / BLACK SWAN in one click for calm days, news days (CPI/FOMC), NFP surprises, or crises. |
| **Adaptive Sizing Engine** | Calculates the safest grid depth and lot size from your real‑time equity — with a built‑in safety buffer. No manual back‑testing of combinations. |
| **Lot Scaling (v3.572)** | When lot size changes (manually or via AutoSizing), TP, SL, trailing and profit‑protection thresholds scale automatically. Same risk on any deposit. |
| **Two‑Layer Profit Protection** | Percentage peak‑lock (locks profit after an N% pullback from peak) followed by a USD trailing stop. |
| **Profit‑to‑SL Bonus** | Optionally adds a portion of closed profit to the pool's allowed drawdown as a cushion — the more you earn in a session, the larger the buffer. |
| **Account Protection** | Hard pool stop‑loss in USD + limit on SL hits per session + auto‑stop on session profit target. |
| **Safety Controls** | **PANIC** (instant close‑all), **LOCK** (prevents accidental clicks in volatility), **READ‑ONLY** (safe for screen‑sharing/recording). |

---

## 🆚 Why Adaptive Grid Beats Traditional Bots

| Capability | Traditional Grid / Martingale | **Mercaria Unicorn GOLD EA** |
|:--|:--|:--|
| **Sizing logic** | Fixed levels; adds blindly regardless of margin | Adaptive Sizing Engine — recalculates from equity |
| **News management** | Static settings; often blows up on CPI/FOMC | 4 volatility profiles, one‑click depth/step change |
| **Drawdown insurance** | Static SL; risks 100% on major trends | Two‑layer protection + Profit‑to‑SL cushion |
| **Scale portability** | Manual recalculation for $1k / $10k / $100k | Lot Scaling — all thresholds adapt to volume |

---

## 📋 Specifications

| | |
|:--|:--|
| **Platform** | MetaTrader 5 |
| **Instrument** | XAUUSD (Gold) — adaptable to other CFDs via grid step |
| **Timeframe** | Any (strategy runs on the tick feed) |
| **Min. deposit** | $300 on a Cent account · $1,000–$2,000 on Standard |
| **Recommended leverage** | 1:500 or higher |
| **Account type** | ECN / Raw Spread, hedging recommended |
| **Activations** | 5 per purchase · free demo available |
| **Version** | 3.572 |

---

## 🚀 Quick Start

1. **Install from MQL5** — after purchase the EA appears in your MT5 *Navigator → Market*. Drag it onto an **XAUUSD** chart (any timeframe).
2. **Configure (F7)** — for the first run keep defaults and set only: `LotSize = 0.01`, `MaxDrawdownUSD ≈ 5–10%` of deposit, `AutoSizing_Mode = ADVISORY`, `AutoSizing_Scenario = SPIKE_M`.
3. **Enable Algo Trading** — click the green *Algo Trading* button.
4. **Watch the panel** — it shows status, recommendations and worst‑case forecasts for all 4 scenarios. Test on **demo for 1–2 sessions** before going live.

---

## 💳 Pricing & Licensing

Buy once or rent monthly on the official MQL5 Market. Every purchase includes **5 activations** and a **free demo**.

| Plan | Price |
|:--|:--|
| Monthly rental | **$50 / month** |
| 6‑month rental | **$250** (save ~18%) |
| Lifetime license | **$5,000** |

> 💡 Price rises every 10 copies sold on MQL5 — the final price will be 3–4× the starting price.

**[→ Get on MQL5 Market](https://www.mql5.com/en/market/product/177680)**

---

## ❓ FAQ

**What is the absolute minimum capital required?**
$300 on a Cent account. On Standard accounts we recommend $1,000–$2,000 to safely use the Spike M / Spike L profiles.

**Does it require constant manual monitoring?**
No — it can run 100% automated. Semi‑automatic management (checking the economic calendar daily and raising the volatility profile before major news) yields the best risk‑reward.

**Why Gold (XAUUSD)?**
Gold has deep liquidity and high daily volatility, ideal for short grid‑recovery cycles. It can trade other CFDs by calibrating the grid step.

**Can I test before buying?**
Yes — a free demo is on the MQL5 page. Test for at least 1–2 full sessions to verify your broker's execution, spreads and margin.

---

## 🌍 Read in your language

**Full user guide (HTML):**
[🇬🇧 English](https://htmlpreview.github.io/?https://github.com/MIB-2026/mercaria-unicorn-gold-ea/blob/main/descriptions/UserGuide-EN.html) ·
[🇺🇦 Українська](https://htmlpreview.github.io/?https://github.com/MIB-2026/mercaria-unicorn-gold-ea/blob/main/descriptions/UserGuide-UK.html)

**Market description:**
[🇬🇧 EN](descriptions/Description-EN.txt) ·
[🇩🇪 DE](descriptions/Description-DE.txt) ·
[🇮🇹 IT](descriptions/Description-IT.txt) ·
[🇹🇷 TR](descriptions/Description-TR.txt) ·
[🇨🇳 ZH](descriptions/Description-ZH.txt)

---

## 🔗 Links

- 🛒 **MQL5 Market:** https://www.mql5.com/en/market/product/177680
- ▶️ **YouTube (live runs):** https://www.youtube.com/@Mercaria_Official
- ✈️ **Telegram:** https://t.me/mercaria
- 🌐 **Website:** https://www.mibase.online/ea
- 👤 **Author:** Anton Serozhkin — quantitative developer & EA author (14 years trading, 4 years building AI/quant systems).

---

<div align="center">

*Mercaria Unicorn GOLD EA · v3.572 · for MetaTrader 5 · © Anton Serozhkin / Mibase.*
*This repository is a product presentation. Trading involves substantial risk of loss.*

</div>
