# Mint Money Rewards prototype

Interactive, single-file HTML prototype of the Mint Money Rewards tab, built on the Mint Money 3.0 design system (mm30-ds).

## Run it

Open `index.html` in a browser. There is no build step and no dependencies. Fonts (Plus Jakarta Sans, DM Serif Display) load from Google Fonts and fall back to system fonts offline.

## What's inside

- **Rewards tab (Home):** balances (Cashback, Coins, Vouchers), Spin & win banner, Ways to earn, Milestones, Refer & earn, Scratch cards, Pay & earn, Spend your coins, Gift cards, bottom links, bottom nav.
- **Layout:** Mint Rewards title, Ways to earn, Total rewards value widget (Cashback, Coins, Vouchers), then Spin banner and the sections below.
- **Other screens:** How rewards work, Spin & Win (wheel and slots), Scratch cards, Milestones, Rewards store (Vouchers, Deals, Gift cards), Gift cards (dark brand store), My vouchers, Cashback / Coins history, and the Refer & earn flow (below).

## Refer & earn

- **Home widget:** tap anywhere (or "Refer now →") to open the Refer landing page.
- **Refer landing:** WhatsApp invite, share, contacts, summary, friend-count bonuses (10 / 20 / 30), links to Track earnings, How it works and Terms and conditions.
- **Track earnings dashboard:** total coins earned, joined / active / completed counts, bonus milestones with Claim, Active and Completed friend lists with a 7-payment progress track, Remind, and empty states.
- **Demo controls** (left panel, referral screens only): friend pays a bill, 5 friends join and pay, clear friends.
- Placeholder values, to confirm: 120 / 120 / 240 coins on a friend's 1st / 4th / 7th bill (480 per friend); bonuses of 1,500 / 3,500 / 6,000 coins. Terms text is placeholder. Friend names and phone numbers are fictional and masked.

## Reward rules used in the prototype

| Currency | Rule |
| --- | --- |
| Coins | 24 coins = ₹1 |
| Cashback | ₹1 = ₹1, applied on bill payments or gift cards |

Gift card checkout lets you pay with coins, coins + ₹ or ₹, then apply cashback. "Pay now" buttons simulate a bill payment and earn rewards.

## Notes

- Brand names (Kartly, Zestbite, Groza and so on) are placeholders.
- State lives in memory only. Reload to reset, or use "Reset prototype".
- Voucher and deal coin prices were not rescaled to the 24 coins = ₹1 rate.
