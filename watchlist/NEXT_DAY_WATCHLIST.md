# Next-Day Watchlist — build for Monday, 2026-11-02

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as a candidate. Built 6pm ET Friday 2026-10-30 (after-hours catalyst research), covering the weekend gap into Monday's open.

## Step 0 — held position defense check
No stock or options position held entering the weekend (`get_equity_positions` confirmed empty). Nothing to defend. No trades were executed Friday afternoon — the elevated "real positive expectations for Monday AM" bar set by the user was not met by any candidate across the 9:40am/11am/12pm/3pm cycles, so the account stays flat into the weekend.

## Account state
Flat, fully in cash. No new realized P&L Friday (no trades). Benchmark account (570898312, read-only, ETF buy-and-hold) tracked for comparison only — never traded.

## Market tone into the close — broadening, deepening selloff
SPX 7,540 (down from 7,720 overnight / ~7,699 Thursday 3pm), NDX 28,162 (down from 29,403 overnight), **VIX 21.88 — up from 16.95 at Thursday's 3pm cycle and 18.66 at Friday's 8am true-up**. The options-flow scan's red/bearish match count nearly doubled through the day (67 at noon → 124 at 3pm). This is the dominant backdrop for Monday: broad risk-off, not isolated to a few names.

## Key finding: late-day reversal of pattern on the day's biggest earnings movers
REGN, RIVN, and GPN all **closed the regular session measurably stronger than their 3pm intraday reads** — a reversal of the "spike-then-fade" pattern that characterized the 9:40am open (where REGN, GILD, RIVN, DXCM all showed failed-breakout/reversal behavior). Per the routine's own Step 4 standard ("a stock that closed strong near its high is a better next-day continuation candidate than one that faded into the close"), this strengthens the case for Monday follow-through on REGN and RIVN specifically:

| Ticker | 3pm | Regular close | AH (as of ~6pm) | Change (close vs. prior close) |
|---|---|---|---|---|
| REGN | $917.95 | **$928.61** | $926.00 | +13.4% (fresh high, held) |
| RIVN | $11.72 | **$12.19** | $12.15 | +6.5% (held) |
| GPN | $94.85 | **$96.98** | $96.00 | +13.1% (held) — still excluded, see below |
| GILD | — | $170.80 | $170.92 | +3.1% (pared back from the $172.45 pre-market high) |
| DXCM | — | $82.31 | $83.50 | +3.0% (modest, AH ticking higher) |

## Bullish — ranked candidates for Monday's open

**#1 RIVN (Rivian) — promoted to #1, strongest close-vs-3pm follow-through + tradeable options size**
- **Catalyst:** Q3 narrower loss -$0.48 vs. -$0.74 est, reported after close Thursday 10/29. Still fresh (3 calendar days by Monday, markets closed over the weekend) — catalyst not stale.
- **Direction/magnitude:** Bullish, closed $12.19 (+6.5%), up from $11.72 at 3pm and holding into AH ($12.15). No fade into the close despite the broader market selling off hard into 3pm-4pm.
- **Freshness confidence:** Medium-high — this is the one name among the three best movers where the options market shows real liquidity at a size this account can actually use.
- **Options read (LIVE quote, 11/13 expiration, ~14 DTE):** $12 call — mark **$0.675** (bid $0.62 / ask $0.73), IV 60.5%, delta 0.58, **OI 917 / volume 601** (genuinely liquid, unlike the thin REGN contract below). One contract = **$67.50**, comfortably inside the ~$297 options cap (10% of ~$2,970 balance) — up to ~4 contracts fits the cap. This is the one candidate where options sizing actually works for this account.
- **Disqualifiers:** Still unprofitable as a company; low share price means tight stops are wide in % terms. Re-verify real (not thin AH) volume at Monday's open, and re-check against Monday's broader tape — if the risk-off tone (VIX 21.88) carries into Monday, even a strong closer can gap down with the market.

**#2 REGN (Regeneron) — strong close, but options are not viable for this account's size**
- **Catalyst:** Q3 big beat $20.07 vs. $15.75 est, reported after close Thursday 10/29.
- **Direction/magnitude:** Bullish, closed at $928.61 (+13.4%, fresh high) after reversing off an intraday whipsaw — up from $917.95 at 3pm, holding in AH ($926.00).
- **Freshness confidence:** High on the catalyst; tempered by the standing 90-day/1-year price-context rule — this is a fresh high, which the standing rule flags for elevated mean-reversion/IV-crush risk (REGN already round-tripped once intraday Friday before recovering).
- **Options read (LIVE quote, 11/13 expiration, ~14 DTE):** $930 call — mark **$24.90** (bid $21.80 / ask $28.00, a wide ~$6 spread), IV 34.4%, delta 0.51, **OI 2 / volume 0** — essentially no liquidity. One contract = **$2,490**, more than 8x the entire ~$297 options cap. **Options entry here is not viable for this account regardless of thesis quality** — any REGN exposure would have to be via stock, and even then $928/share means a single share is ~31% of total account value, a real concentration/sizing problem on its own.
- **Disqualifiers:** Fresh-high mean-reversion risk (standing rule); untradeable options size; stock-only entry would be a large single-name concentration for this account.

**#3 GILD (Gilead) — real but smaller continued strength**
- **Catalyst:** Q3 EPS beat $2.55 vs. $2.18 est.
- **Direction/magnitude:** Bullish but paring — closed $170.80 (+3.1%), down from the $172.45 pre-market high reported at the 8am true-up. AH basically flat ($170.92).
- **Freshness confidence:** Medium — clean beat holding a real gain, but the smallest % move of the earnings-driven group and already giving back some of its earlier strength.
- **Disqualifiers:** Needs a fresh options/liquidity check at Monday's open; not yet re-verified since the 8am true-up.

**#4 DXCM (Dexcom) — modest, AH ticking higher**
- **Catalyst:** Q3 EPS beat $0.73 vs. $0.67 est.
- **Direction/magnitude:** Bullish, closed $82.31 (+3.0%), with AH actually extending to $83.50 — the only one of the five names still climbing after hours.
- **Freshness confidence:** Medium — smallest regular-session move but the AH tick higher is worth re-checking at Monday's open.
- **Disqualifiers:** Needs fresh options check; medtech name, generally liquid.

## Excluded — GPN (Global Payments), capped merger-arb / unconfirmed rumor
+13.1% Friday on an unconfirmed FT report of a CD&R/GTCR take-private approach (~$40B EV, no price/financing confirmed). A WebSearch tonight found **no independent corroboration** of this specific take-private rumor — the only GPN/GTCR news that turned up is the already-closed Worldpay acquisition (GTCR's unrelated, prior, completed deal, closed January 2026). The rumor remains exactly as unconfirmed as it was intraday Friday.
**Still excluded per the user's own stated Friday-afternoon standard** ("need real positive expectations to jump in Friday afternoon" / "looking for things that may have value or potential Monday AM"): binary, unconfirmed deal-news risk (confirm/deny/leak over a weekend with zero ability to react) is the opposite of that standard, regardless of how strong the stock's close looked. Noted as a strengthening situation to watch, not a candidate — reuse this reasoning for any future capped-arb rumor near a weekend.

## Standing watch — optoelectronic sector (AAOI / COHR), update
Both still lower, sector-wide (Marvell/Lumentum M&A-sympathy move), not company-specific:
- **AAOI:** closed $69.07, **-12.8%** on the day — actually worse than the -9.0% pre-market read at 8am, not an improvement. AH roughly flat ($69.14).
- **COHR:** closed $210.30, **-11.3%** on the day, AH ticking up slightly to $212.50 (+1% off the close).
- Both remain standing-watch only, not scored or tradeable candidates. Still no company-specific catalyst on either name (AAOI earnings not until 11/5).

## Monday 2026-11-02 earnings slate
Heavy, but **mostly PM reporters** (after Monday's close — relevant for Tuesday's open, not Monday's): AAPL, PLTR, VRTX, ON, ROKU, GRAB, FANG, WMB, CRBG, NBIX, MTCH, DOC, O, JAZZ, and many smaller names.
**AM reporters (could move Monday's open directly):** MAR, IDXX, CHKP, CIFR, TEM, KOS, EL, ETR, PEG, TSEM, NSSC, AKR, CNA, RYAAY, ALX, L, CHH, AXSM, FOX/FOXA. None of these have been checked yet for pre-market reaction — that's the 8am true-up / 9:40am cycle's job once pre-market volume builds Monday.

## Pending binary events / standing notes
- DAIC (CID HoldCo) remains excluded from consideration regardless of any future move — tied to the 2026-09-17 "don't chase" realized-loss lesson.
- ADT still shows no confirmed earnings catalyst for its sustained move — actual report date is 2026-11-03 — continue flagging as unexplained/stale until that date.
- Benchmark account 570898312 (ETF buy-and-hold, SPY/QQQ/SCHD/JEPI/WQTM/DDDD) remains **read-only** — tracked for performance comparison only, never traded.
