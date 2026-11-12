# Mint Money Rewards prototype

Interactive, single-file HTML prototype of the Mint Money Rewards tab, built on the Mint Money 3.0 design system (mm30-ds).

## Run it

Open `index.html` in a browser. There is no build step and no dependencies. Fonts (Plus Jakarta Sans, DM Serif Display) load from Google Fonts and fall back to system fonts offline.

## What's inside

- **Rewards tab (Home):** balances, Spin & win banner, Ways to earn, Milestones, Scratch cards, Pay & earn, Spend your coins, Gift cards, bottom links, bottom nav.
- **Concepts** (switch in the left panel):
  - UC 1: single combined rewards value above the balances.
  - UC 2: no combined value, only Cashback, Coins and MM Credit; Ways to earn moves to the top.
- **Other screens:** How rewards work, Spin & Win (wheel and slots), Scratch cards, Milestones, Rewards store (Vouchers, Deals, Gift cards), Gift cards (dark brand store), My vouchers, Cashback / Coins / MM Credit history.

## Reward rules used in the prototype

| Currency | Rule |
| --- | --- |
| Coins | 24 coins = ₹1 |
| MM Credit | 1 credit = ₹5, spendable on gift cards |
| Cashback | ₹1 = ₹1, applied on bill payments or gift cards |

Gift card checkout lets you pay with coins, coins + ₹ or ₹, then apply cashback and MM Credit. "Pay now" buttons simulate a bill payment and earn rewards.

## Notes

- Brand names (Kartly, Zestbite, Groza and so on) are placeholders.
- State lives in memory only. Reload to reset, or use "Reset prototype".
- Voucher and deal coin prices were not rescaled to the 24 coins = ₹1 rate.
