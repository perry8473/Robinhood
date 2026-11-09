# Next-Day Watchlist — build for Tuesday, 2026-11-10

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as a candidate. Built 6:05pm ET Monday 2026-11-09. Asian and European overnight-session news has **NOT** been checked yet at this hour (those sessions haven't opened/traded) — that is the job of the ~8am overnight true-up routine.

## WEEKLY PERFORMANCE TARGET — standing note (carried forward)
3-5% account growth this week via tight trailing stops, conservative execution, no autonomous sizing increase (explicit user instruction, 2026-11-08). Today (Monday 2026-11-09), the account ran flat all day — four market-hours cycles found no candidate clearing the 85-confidence autonomous bar (three cycles had no confirmed catalyst at all; the 3pm cycle found four real-catalyst names but all too extended/late in the session to enter cleanly). Zero realized P&L today, but also zero risk taken — consistent with the conservative framing. No $ deployment change made or proposed.

## Step 0 — held position check (6pm routine)
No stock or options position held (`get_equity_positions` confirmed empty; all option legs are legacy zero-quantity). Nothing to defend. Account flat entering tomorrow, same as it has been all session.

## Today's (2026-11-09) PM earnings reactions — after-hours price action vs. today's close
Verified actuals via `get_earnings_calendar`, AH reaction via `get_equity_quotes` (last_non_reg_trade_price vs. today's close) as of ~6:05pm ET:

**Bullish, fresh, worth a fast look at tomorrow's 9:40am open:**
- **ONTO (Onto Innovation):** EPS $2.44 actual vs $2.30 est — beat. AH $209.89 vs close $193.72, **+8.4%** — strong, proportionate reaction to a clean beat. Best setup of tonight's reporters.
- **TTWO (Take-Two Interactive):** EPS $0.99 actual vs -$0.59 est — big beat (swung positive vs. an expected loss). AH $215.92 vs close $207.37, **+4.1%** — solid positive reaction.
- **TTD (The Trade Desk):** EPS $0.33 actual vs $0.22 est — beat. AH $15.33 vs close $14.96, **+2.5%** — modest but positive; this is the same TTD flagged all day today as "reports PM, not yet actionable" — now has a real, fresh, confirmed catalyst for tomorrow.

**Bearish / fade — not long candidates, flag only:**
- **QLYS (Qualys):** EPS $2.12 actual vs $1.86 est — beat, but AH $186.00 vs close $202.45, **-8.1%** — another "sell the beat" case (same pattern as MNDY earlier this week, AXON/TEAM/MCHP the week before). Guidance-driven selloff likely. Not a long; possible short-candidate flag only, not pursued without explicit approval.
- **RKLB (Rocket Lab):** EPS -$0.12 actual vs -$0.06 est — miss (wider loss than expected). AH $55.85 vs close $58.81, **-5.0%** — negative reaction matches the miss. Avoid long.
- **HIMS (Hims & Hers):** EPS $0.03 actual vs $0.06 est — miss. AH $22.30 vs close $22.94, **-2.8%**. Avoid long.

**Muted / inconclusive — no fresh actionable setup:**
- **MARA:** EPS $1.28 actual vs -$0.09 est — a massive beat, but AH barely moved (+0.45%, $6.67 vs $6.64 close) — likely already priced in given MARA (and the whole crypto-miner complex) was already up hard intraday today on the broader crypto rally. On our standing crypto watchlist — watch for Tuesday's open reaction once the full session can price it, but tonight's AH move alone isn't a fresh signal.
- **OXY:** EPS $1.91 vs $1.46 est — beat, AH +0.4% ($55.99 vs $55.79) — muted, already largely anticipated.
- **LCID:** EPS -$2.30 vs -$2.32 est — essentially in-line. AH -3.7% ($3.48 vs $3.62) — negative despite the inline print, likely guidance-driven; thin/speculative name regardless.
- **PLUG:** still shows no actual posted as of this build (estimate -$0.06 unconfirmed) — not yet a tradeable catalyst.
- **CWEN, JBS, TDW:** notable misses tonight (CWEN $0.42 vs $1.80 est; JBS $0.16 vs $0.94 est; TDW $0.35 vs $0.70 est) — not on our standing watchlist, noted for completeness, not pursued.

## Preliminary options read (top 3 bullish candidates only — PRELIMINARY, NOT A LIVE QUOTE)
Equity options cannot execute outside regular hours — any quote here is from today's regular-session close and must be re-verified fresh at tomorrow's open. All three below have listed options chains with an expiration inside the 7-30 DTE window:
- **ONTO:** expirations include 2026-11-20 (11 DTE) — listed chain: PASS (structural). DTE window: PASS. Premium/OI/live spread: not checked (no live market right now).
- **TTWO:** expirations include 2026-11-20 (11 DTE) and others — listed chain: PASS. DTE window: PASS. Premium/OI/live spread: not checked.
- **TTD:** expirations include 2026-11-20 (11 DTE) and others — listed chain: PASS. DTE window: PASS. Premium/OI/live spread: not checked.
All three: re-pull live option chains/quotes fresh at the 9:40am opening-bell cycle before any options consideration — this is pure head-start research, not a pre-approval of any kind.

## Tomorrow (2026-11-10) — scheduled AM reporters (before the open, most relevant for a fresh-open watchlist)
Notable/high-profile names reporting before tomorrow's open per `get_earnings_calendar` (unverified actuals — these are upcoming, not yet reported):
- **ONON (On Holding)** — est $0.46.
- **SE (Sea Limited)** — est $0.94. Large-cap, high-attention name.
- **TDG (TransDigm)** — est $12.05. Large-cap.
- **WIX** — est $1.12.
- **HMC (Honda)** — est unconfirmed.
- **BTDR (Bitdeer)** — est -$0.33. Crypto-mining-adjacent, worth a glance alongside the standing crypto watchlist.
- **LEGN, SRRK, ATAT, HSAI, AUTL, ACCS** and many smaller/thinner names also report AM — not individually flagged given smaller size/lower attention; re-check at Step 4 sweep if any show unusual pre-market volume.
None of these have actuals yet — all are "stale/unconfirmed, awaiting verified result" per the standing catalyst-confirmation rule. Carrying forward as names to watch for a fresh verified beat/miss at tomorrow's 8am true-up and 9:40am opening-bell cycle.

## Tomorrow (2026-11-10) — scheduled PM reporters (sets up Wednesday)
**CRWV (CoreWeave)** — est -$1.53, PM. High-attention AI-infrastructure name; flag for Tuesday's EOD/after-hours routines, not actionable Tuesday itself.
**RGTI, QBTS** (quantum computing pair) — both report, timing mixed (QBTS am, RGTI pm) — notable sector-pair, watch for a possible correlated reaction across both names.

## Standing watch — optoelectronic sector (AAOI / COHR)
Both remain standing-watch-only, closed positions from Friday 11/6's trade (small realized gains, +$12.06 combined). COHR ran hard again today (+7-8% intraday per the 9:40am cycle read) but no re-entry proposed without a fresh qualifying setup on its own merits — chasing a closed winner back in on a gap-up would itself violate the DON'T-CHASE principle. Continue standing-watch-only treatment.

## Pre-market small-cap-tech shortlist
Not checked this build (after-hours, regular-session-only scan data) — Technology sector sweep found only thin/no-catalyst names all day today (JZ, HOLO, TLS — TLS reclassified as enterprise security with a real catalyst, scored 60, not executed). Re-run fresh at the 9:40am cycle.

## Market condition — close of day 2026-11-09
SPX 7,561.55 (final intraday read, 3pm cycle), NDX 27,917.56, VIX 19.87 — VIX closed the week's first session under 20 for the first time, a genuine stabilization signal after last week's volatility. Broad crypto-equity rally held up all day (CLSK +12.8%, HUT +7.1%, CORZ +7.9%, RIOT +6.6% at the 3pm read). No major macro shock identified.

## Pending binary events / standing notes (carried forward)
- LOAR/MGRC/ZG/NXT remain on the user's explicit hold from the earlier-week instruction — no new information this pass.
- DAIC (CID HoldCo) remains excluded from consideration regardless of any future move — tied to the 2026-09-17 "don't chase" realized-loss lesson.
- Benchmark account 570898312 (ETF buy-and-hold) remains **read-only** — tracked for performance comparison only, never traded.
- SECTOR CONCENTRATION CAP and MICRO-CAP CONCURRENCY CAP remain in effect for every cycle until the user says otherwise.
- Options-flow scan (8719a93e-58d5-4b84-9905-c0c93b7676c1) was rate-limited on **every single cycle today** (9:40am, 11am, 12pm, 3pm) — worth flagging to the user as a persistent, not intermittent, issue if it continues tomorrow.

## Options consideration
Covered above for the top 3 bullish PM reporters (ONTO/TTWO/TTD) — all preliminary/structural only, pending live re-verification at the open.
