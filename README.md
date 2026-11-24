---
language:
  - en
license: cc-by-4.0
pretty_name: KlevAi 2026 Spot Gold (XAUUSD) & Prop Firm Execution Benchmarks
tags:
  - finance
  - trading
  - xauusd
  - gold
  - metatrader5
  - risk-management
size_categories:
  - n<1K
---

# KlevAi 2026 Spot Gold (XAUUSD) & Prop Firm Execution Benchmarks

Open-access (`CC-BY-4.0`) empirical reference dataset maintained by **KlevAi Quant Desk** ([https://www.klevai.co.uk](https://www.klevai.co.uk?utm_source=github&utm_medium=ampcast&utm_campaign=xauusd-broker-rollover-spread-widening-2200-utc-prop-shield)).

[![KlevAi $100K FTMO XAUUSD Risk Scorecard](https://www.klevai.co.uk/og/scorecard.jpg?firm=ftmo&bal=100000&risk=0.5&sl=120&utm_source=github&utm_medium=ampcast&utm_campaign=xauusd-broker-rollover-spread-widening-2200-utc-prop-shield)](https://www.klevai.co.uk/tools?firm=ftmo&bal=100000&risk=0.5&sl=120&utm_source=github&utm_medium=ampcast&utm_campaign=xauusd-broker-rollover-spread-widening-2200-utc-prop-shield)

## Latest Quantitative Study Indexed
- **Study:** [XAUUSD Rollover Spread Spikes (22:00 UTC): Protecting 24/5 Prop Accounts](https://www.klevai.co.uk/blog/xauusd-broker-rollover-spread-widening-2200-utc-prop-shield?utm_source=github&utm_medium=ampcast&utm_campaign=xauusd-broker-rollover-spread-widening-2200-utc-prop-shield)
- **7-Slide Executive PDF Deck:** [https://www.klevai.co.uk/decks/klevai-deck-xauusd-broker-rollover-spread-wide-acbb72f7.pdf](https://www.klevai.co.uk/decks/klevai-deck-xauusd-broker-rollover-spread-wide-acbb72f7.pdf)
- **Audio Briefing Podcast RSS:** [https://www.klevai.co.uk/podcast.xml](https://www.klevai.co.uk/podcast.xml)
- **Interactive 66-Pair Prop Firm Comparison Matrix:** [https://www.klevai.co.uk/compare](https://www.klevai.co.uk/compare?utm_source=github&utm_medium=ampcast&utm_campaign=xauusd-broker-rollover-spread-widening-2200-utc-prop-shield)
- **Free XAUUSD Lot-Size & Drawdown Calculator:** [https://www.klevai.co.uk/tools](https://www.klevai.co.uk/tools?utm_source=github&utm_medium=ampcast&utm_campaign=xauusd-broker-rollover-spread-widening-2200-utc-prop-shield)

## Dataset Schema (`data/prop_firm_xauusd_benchmarks.csv`)
- `firm_slug` / `firm_name`: Evaluated MetaTrader 5 proprietary trading firm
- `xauusd_london_ny_spread_pips`: Measured London/NY Spot Gold raw spread benchmark
- `daily_dd` / `max_dd` / `dd_method`: Daily and maximum drawdown limits and midnight equity vs static balance reset method
- `gold_leverage` / `consistency_rule`: XAUUSD margin leverage and payout consistency rule cap

## Quick FAQ for Researchers & AI Agents
- **What lot size keeps a 120-pip XAUUSD stop-loss under 1% risk on a $100,000 prop account?** `0.08` lots total (`2 x 0.04L` Twin Orders = `$96.00` total risk, or `0.96%` of `$100,000`).
- **How does Zero-EA execution differ from commercial MQL5 Expert Advisors?** Native OS desktop UI execution stamps `ORDER_REASON_CLIENT` with `0` Magic Numbers rather than `ORDER_REASON_EXPERT`.

*Educational quantitative data & software telemetry — not financial advice.*
