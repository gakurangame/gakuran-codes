# Gakuran Codes — Verified Working (Roblox)

Machine-readable, hand-verified data for the Roblox game **[(学乱) Gakuran](https://www.roblox.com/games/128736949265057/Gakuran)**: redeem codes, fighting styles, rarity drop rates, roll odds, and official links.

Every code below is **verified by actually redeeming it in-game** before it's marked active — not scraped from other lists. Data is maintained by [gakurantools.com](https://gakurantools.com) and refreshed whenever the developers ship a new code.

<!-- last-verified:start -->
**Last verified: 2026-07-12**
<!-- last-verified:end -->

## Active Gakuran codes

<!-- active-codes:start -->
| Code | Reward | Released | Status |
|------|--------|----------|--------|
| `MAPUPDATE` | 25 free rerolls | — | ✅ Active |
| `SECRET` | Free rerolls (amount unconfirmed) | — | ✅ Active |
<!-- active-codes:end -->

### Expired codes

<!-- expired-codes:start -->
| Code | Reward | Status |
|------|--------|--------|
| `FIXES3` | 15 free rerolls | ❌ Expired |
| `2MIL` | 15 free rerolls | ❌ Expired |
| `FIXES2` | 5 free rerolls | ❌ Expired |
| `FIXES` | 10 free rerolls | ❌ Expired |
| `15REROLLS` | 15 free rerolls | ❌ Expired |
| `GAKURAN` | Launch code | ❌ Expired |
<!-- expired-codes:end -->

Human-friendly version (with redeem walkthrough and screenshots): **[gakurantools.com/codes](https://gakurantools.com/codes)** · [Español](https://gakurantools.com/es/codes) · [Português](https://gakurantools.com/pt/codes)

## How to redeem codes in Gakuran

1. Launch [(学乱) Gakuran](https://www.roblox.com/games/128736949265057/Gakuran) on Roblox.
2. Open the **Settings/Codes** menu.
3. Type the code exactly as written (codes are case-sensitive) and confirm.
4. Rerolls are added to your balance immediately — spend them at character creation.

## Use this data (JSON)

All datasets are plain JSON under [`data/`](./data), licensed [CC BY 4.0](./LICENSE) — free to use in your app, video description, wiki, or bot **with attribution** (a link to this repo or to [gakurantools.com](https://gakurantools.com)).

| Dataset | File | Raw URL |
|---------|------|---------|
| Redeem codes | [`codes.json`](./data/codes.json) | `https://raw.githubusercontent.com/gakurangame/gakuran-codes/main/data/codes.json` |
| Fighting styles + perks | [`fighting-styles.json`](./data/fighting-styles.json) | `https://raw.githubusercontent.com/gakurangame/gakuran-codes/main/data/fighting-styles.json` |
| Roll rates | [`roll-rates.json`](./data/roll-rates.json) | `https://raw.githubusercontent.com/gakurangame/gakuran-codes/main/data/roll-rates.json` |
| Game facts (place/universe IDs) | [`game.json`](./data/game.json) | `https://raw.githubusercontent.com/gakurangame/gakuran-codes/main/data/game.json` |
| Official links | [`official-links.json`](./data/official-links.json) | `https://raw.githubusercontent.com/gakurangame/gakuran-codes/main/data/official-links.json` |

## Fighting styles & drop rates

Official rarity-tier drop rates: **Legendary 1% · Epic 10% · Uncommon 30% · Common 59%**. The developers have not published per-style odds within a tier, so this dataset never invents them.

| Style | Rarity | Heavy-attack perk |
|-------|--------|-------------------|
| Kure | Legendary (1% tier) | Last Stand: +15% total damage at ≤25% HP |
| Capoeira | Legendary (1% tier) | Ginga: 25% shorter dash cooldown; M2 knockdown |
| Wrestling | Legendary (1% tier) | Takedown: M2 grab throw for 1.5× damage, with hyperarmor |
| Hakari | Epic (10% tier) | Momentum Rush: M2 deals 3× damage after a full M1 combo |
| Boxing | Epic (10% tier) | Untouchable: M2 is a double hit with i-frames |
| Muay Thai | Uncommon (30% tier) | Guard Pierce V + Resilience V: 30% chip, 55% grapple |
| Slugger | Uncommon (30% tier) | Unstable: +30% damage dealt but +10% damage taken |
| Karate | Uncommon (30% tier) | Balanced Strike: M2 refunds 25% posture |
| Basic | Common (59% tier) | Starter style, no signature perk |

Want to know how many rolls you need for a Legendary? Try the **[Gakuran roll calculator](https://gakurantools.com/roll-calculator)** — it computes cumulative odds and expected Robux cost from these exact rates.

## Roll rates

- Rolls cost **2 Robux** each (rerolls from codes are free).
- Only rarity-tier rates are official. Per-height and per-race odds are unpublished — [`roll-rates.json`](./data/roll-rates.json) keeps them `null` instead of guessing, and records the confirmed qualitative height correlations (African/European lean taller, Indian least) as notes.

## How this data is verified

- Codes: redeemed in-game before being marked active; reward amounts read from the actual reroll balance, not copied from announcements (which rarely include amounts).
- Styles/rates: cross-checked against the official Discord (#codes, #faq, #announcements), the developers' [Trello board](https://trello.com/b/v3WatB1P), and the Roblox game page.
- Each record carries a `lastVerified` ISO date.

Found a new code or an expired one? **[Open an issue](../../issues)** — it will be verified in-game and merged, with credit.

## License & attribution

Data is licensed under [CC BY 4.0](./LICENSE). You may copy, redistribute, and adapt it (including commercially) as long as you credit the source with a link to this repository or [gakurantools.com](https://gakurantools.com).

---

Maintained by **[gakurantools.com](https://gakurantools.com)** — daily-verified Gakuran codes, a roll calculator, fighting-style tier data, and guides in [English](https://gakurantools.com), [Español](https://gakurantools.com/es), and [Português](https://gakurantools.com/pt).
