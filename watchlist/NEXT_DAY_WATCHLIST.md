# Next-Day Watchlist — build for Wednesday, 2026-11-04

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as a candidate. Built 6:05pm ET Tuesday 2026-11-03 (after-hours catalyst research).
>
> **Asian and European overnight-session news has NOT been checked yet at this hour** — those sessions haven't opened/traded when this routine fires. That's the job of the ~8am overnight true-up routine that updates this same file before the open.

## Step 0 — held position defense check
`get_equity_positions` confirmed empty for account 787937630. Nothing to defend — the account is flat (NXT was closed today ahead of the close per explicit user instruction, -2.44%; AAOI stopped out -2.96%; COHR closed on explicit instruction -1.75%).

## Account state
Flat, fully in cash (~$2,950). Three realized losses today (NXT, AAOI, COHR — all no-catalyst technical/momentum plays, all small/contained). Benchmark account 570898312 remains read-only, tracked for comparison only.

## Today's after-close earnings reactions — huge dispersion
A very large PM earnings slate reported today. The standout reactions:

| Ticker | Result | Regular close | AH (as of ~6:06pm ET) | Reaction |
|---|---|---|---|---|
| **ANET** | Big beat, $1.20 vs $1.06 est | $164.14 | **$192.50** | **+17.3%** |
| **SMCI** | Huge beat, $1.81 vs $1.20 est | $30.44 | **$34.48-34.50** | **+13.3%** |
| **AMD** | Beat, $2.09 vs $1.89 est | $466.84 | **$520.80** | **+11.6%** |
| **SWKS** | Beat, $1.28 vs $1.20 est | $85.17 | **$70.75-71.49** | **-16.9%** (sold hard despite the beat — likely guidance) |
| AMGN | Big beat, $6.45 vs $5.77 est | $465.45 | $454.00-455.00 | -2.3% (down despite beat) |
| BKNG | Beat, $4.66 vs $4.49 est | $153.75 | $154.20-155.00 | +0.3-0.8% (modest) |
| ALAB | Beat, $1.32 vs $1.12 est | $229.67 | $232.03-232.50 | +1.1-1.2% (modest) |
| PRU | Beat, $3.77 vs $3.33 est | $118.30 | $118.81-122.00 | roughly flat (wide AH spread) |

All verified via `get_earnings_calendar` (report.verified=true, eps.actual populated). Note: these are last-regular-close-based reactions pulled right at/just after the close — re-verify for genuine follow-through (not just an initial AH print) at the 8am true-up and again live at 9:40am.

## Ranked candidates for Wednesday's open

**#1 ANET (Arista Networks) — strongest reaction, real catalyst, cleanest size**
- **Catalyst:** Q3 beat, $1.20 vs $1.06 est, reported after close today (2026-11-03), verified.
- **Direction/magnitude:** Bullish, +17.3% AH ($164.14 → $192.50).
- **Freshness confidence:** High — same-day, verified beat with the largest AH reaction of the slate.
- **Disqualifiers:** None yet identified; re-verify real (not thin-AH) volume and a clean base at the open — a 17% gap often needs time to stop whipsawing before it's tradeable (per standing Step 6 guidance).
- **Options read (PRELIMINARY, priced off today's regular-session close — not a live AH quote, options don't trade after hours): 11/13 expiration (~10 DTE), $195 call — mark $1.635 (bid $1.32/ask $1.95), IV 76.8%, delta 0.15, OI 41/volume 49.** One contract = $163.50, within the ~$295 cap. Structural read: DTE PASS, premium-vs-cap PASS, listed chain PASS, OI thin but present — re-verify live spread/volume at the open.

**#2 SMCI (Super Micro) — huge beat, huge reaction, smaller/more volatile name**
- **Catalyst:** Q1 FY27 huge beat, $1.81 vs $1.20 est, reported after close today, verified.
- **Direction/magnitude:** Bullish, +13.3% AH ($30.44 → $34.48).
- **Freshness confidence:** High on the catalyst; SMCI has a history of outsized volatility (include both in thesis and stop sizing if this is pursued tomorrow).
- **Disqualifiers:** Lower share price means a tight stop is wide in % terms; re-verify real volume at the open, not a thin AH print.
- **Options read:** not checked this build (scoped to top 2 given the late hour) — check live at 8am/9:40am if this remains a live candidate.

**#3 AMD — mega-cap, extremely liquid, but options don't fit the cap**
- **Catalyst:** Q3 beat, $2.09 vs $1.89 est, reported after close today, verified.
- **Direction/magnitude:** Bullish, +11.6% AH ($466.84 → $520.80).
- **Freshness confidence:** High — clean beat, strong AH reaction on a mega-cap name.
- **Disqualifiers:** Share price is high; stock-only entry would be a large per-share commitment for this account's size.
- **Options read (PRELIMINARY): 11/13 expiration (~10 DTE), $525 call — mark $11.775 (bid $11.45/ask $12.10), IV 82.1%, delta 0.30, OI 498/volume 267 — genuinely liquid.** One contract = **$1,177.50 — well above the ~$295 cap.** Structural read: DTE PASS, listed chain PASS, OI/volume PASS, **premium-vs-cap FAIL.** A further-OTM strike would fit the cap but at much lower delta/quality — stock-only (small size) is the more realistic route for this account if pursued.

## Flag — SWKS, bearish reaction despite a beat
Skyworks beat ($1.28 vs $1.20) but sold off hard after hours (-16.9%, $85.17 → ~$71) — classic "beat but bad guidance" pattern. Not a long candidate; could be of interest as a short/put thesis if the fade holds into the morning, but that requires a fresh look at the actual guidance commentary (not available via WebSearch this session) before treating it as more than a flag.

## Macro / overnight note
WebSearch for overnight macro/Fed news returned no results dated to tomorrow (2026-11-04) — consistent with this session's established same-day-coverage gap. One tangentially-relevant item surfaced: a reported Fed decision holding rates at 3.75%-4.00% (10-2 vote), with December hike odds elevated, and a stated calendar including October payrolls on Nov 6 and October CPI on Nov 10 — dates/details unconfirmed, flagging as unverified context only, not a trading input.

## Tomorrow (2026-11-04) scheduled earnings — notable names
**AM:** UBER, MCD, CVS, EMR, NVO, DDOG, HUT (our crypto watchlist name), QCOM reports PM not AM — correcting, QCOM/APP/ARM/MELI/SNAP/Z/ZG/MSI/FICO all report PM. **COHR reports PM tomorrow** — the name closed out of this account today; no position, just FYI. **ZG reports PM tomorrow** — one of the names on the user's standing hold list (LOAR/NXT/MGRC/ZG group); worth noting ahead of any future revisit of that group.

## Pending binary events / standing notes
- LOAR/MGRC/ZG/CLRO remain on the user's explicit hold from Monday — ZG specifically now has an earnings catalyst landing tomorrow PM, worth re-visiting that whole group fresh once the result is in.
- DAIC (CID HoldCo) remains excluded from consideration regardless of any future move — tied to the 2026-09-17 "don't chase" realized-loss lesson.
- Benchmark account 570898312 (ETF buy-and-hold) remains **read-only** — tracked for performance comparison only, never traded.
