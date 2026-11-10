# Next-Day Watchlist — build for Tuesday, 2026-11-10

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as a candidate. Built 6:05pm ET Monday 2026-11-09, **trued up 8am ET Tuesday 2026-11-10** against overnight/pre-market action.

## STRATEGY FRAMEWORK — updated 2026-11-10 by explicit user instruction (sequence of clarifying messages)
This account now runs a deliberate **blend of three opportunity types** every cycle, not just the original catalyst-driven day/swing track:
1. **Day/swing (existing):** fresh-catalyst-confirmed, 85-confidence-bar, same-day/week exit discipline — unchanged.
2. **Long-horizon value/solid-base (NEW):** large-cap or genuinely liquid mid-cap names that are undervalued on fundamentals or show a solid multi-week/month technical base — held days to months, no fresh-news-catalyst requirement (the valuation/base itself is the thesis), liquidity is the hard gate (must be easy to exit if cash is needed elsewhere), wider structure-based stop instead of the tight day-trade trail. Flagged explicitly as "LONG-HORIZON" in any report where one is entered.
3. **Sensible speculative ("occasional moonshot"):** a less-certain setup is fine to score and execute when the upside is both *likely* (credible path, not a lottery ticket) and *meaningful* (a real move) — still subject to every existing gate (catalyst confirmation, caps, stops), just not marked down in score merely for being speculative in character.

**Weekly performance target reframed:** 3-5%/week remains a reference *parameter* for judging whether an opportunity's size/quality aligns with the account's goals — not a literal weekly requirement. User's words: "Goal of 3-5% weekly is parameter to consider whether something aligns with our goals. Some will miss. So achieve half that in reality is still very good outcome," and separately, "Aggregate making goal of 1-2% weekly gains would be amazing, if consistently reached over long periods... that's over time and average." Flat weeks (like 2026-11-09's, zero trades/zero P&L) are expected and never a reason to force a marginal trade. Also explicitly confirmed: **"Lots of turbulence right now. Sitting patiently is ok"** — patience is the preferred default in choppy conditions, not just a fallback.

All of this has been persisted into the standing trigger prompt (trig_017rc7KNGPfAKxjUEkCNNN82) so every future cycle carries it forward automatically — this note is a summary for quick reference, not the authoritative source.

**Account housekeeping (2026-11-10):** user confirmed the $600 balance increase was a deposit (not a trading artifact), and separately moved crypto holdings out of the read-only benchmark account 570898312 into another account — that benchmark should now be read as its **stock + ETF portion only**.

## Step 0 — held position check (6pm routine, re-confirmed 8am)
No stock or options position held (`get_equity_positions` confirmed empty both at 6pm and again at 8am; all option legs are legacy zero-quantity). Nothing to defend. Account flat entering today.

## Tuesday 2026-11-10 — 8am true-up: pre-market reactions on last night's candidates
- **ONTO:** pre-market $199.00 vs Monday close $194.04, **+2.6%** — faded from last night's AH peak ($209.89, +8.4%) but still net positive vs. the regular close. WEAKENED vs. last night's peak, but still a live, confirmed-catalyst setup — re-verify live structure at the open.
- **TTWO:** pre-market $214.50 vs close $207.40, **+3.4%** — holding close to last night's AH level ($215.92). STRENGTHENED/steady — the cleanest hold-through of the three.
- **TTD:** pre-market $14.15 vs close $14.93, **-5.2%** — reversed hard overnight; was +2.5% in last night's AH read. WEAKENED significantly — the beat reaction did not hold. Demoted, no longer a live bullish candidate.
- **QLYS:** pre-market $192.63 vs close $202.46, **-4.9%** — still down but partially recovered from last night's AH low (-8.1%). UNCHANGED verdict: bearish/fade, not a long.
- **RKLB:** pre-market $54.20 vs close $58.86, **-7.9%** — extending the post-miss decline further (was -5.0% AH). WEAKENED further — confirmed bearish, avoid long.
- **HIMS:** pre-market $22.71 vs close $22.94, **-1.0%** — stabilizing somewhat vs. last night's -2.8% AH. Still negative, no longer worth a bearish flag on its own.
- **MARA:** pre-market $6.48 vs close $6.64, **-2.4%** — mild fade, still muted/no fresh signal.

## Tuesday 2026-11-10 — AM reporters: verified actuals and pre-market reactions as of ~8am ET
- **VG:** EPS $0.96 actual vs $0.52 est — **big beat**. Pre-market $12.23 vs close $11.80, **+3.6%** — clean, proportionate positive reaction. **Best fresh setup this morning.**
- **SE (Sea Limited):** EPS $0.78 actual vs $0.94 est — **miss**. Pre-market $70.24 vs close $77.96, **-9.9%** — severe, proportionate negative reaction. Large-cap, high-attention; avoid long, not pursued as short without explicit approval.
- **ONON:** EPS $0.66 actual vs $0.46 est — beat, but pre-market $35.58 vs close $37.53, **-5.2%** — another "sell the beat" case (joining MNDY, QLYS from this week's pattern). Not a long.
- **WIX:** EPS $1.42 actual vs $1.12 est — beat, but pre-market $67.51 vs close $69.75, **-3.2%** — same sell-the-beat pattern. Not a long.
- **TDG (TransDigm):** EPS $12.44 actual vs $12.05 est — beat, pre-market essentially flat (-0.07%, $1218.00 vs $1218.85) — muted, already priced in for this large, slow-moving industrial name.
- **LQDA:** EPS -$2.64 actual vs $0.93 est — **huge miss**, but pre-market $49.68 vs close $47.87, **+3.8%** — price action directly contradicts the EPS line; WebSearch found no same-day article explaining the disconnect (likely a one-time charge or revenue/guidance-driven reaction overriding the GAAP EPS miss). Flagged as unexplained/needs live reverification, not scored.
- **BTDR:** EPS -$0.38 actual vs -$0.33 est — miss, pre-market flat (-0.07%). Muted.
- **QBTS:** EPS -$0.13 actual vs -$0.11 est — miss, pre-market $11.16 vs close $11.47, -2.7%. Mild negative, consistent but not a standout.
- **ATAT:** EPS $0.22 actual vs $0.56 est — big miss, pre-market essentially flat (-0.08%) — thin pre-market liquidity, no clear reaction yet.
- **HSAI:** EPS $0.01 actual vs $0.08 est — miss, pre-market +1.1% — muted/inconsistent, not a standout either way.
- **CRWV, RGTI:** still report PM today, unchanged from last night — carry forward, not yet actionable.

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

## Standing watch — optoelectronic sector (AAOI / COHR), Tuesday update
- **AAOI:** Monday close $52.10. Pre-market $49.54 (bid $49.40/ask $49.56), **-4.9%** — pulling back/giving back some of Monday's strong run. No fresh news found via WebSearch.
- **COHR:** Monday close $225.19. Pre-market $217.91 (bid $217.00/ask $218.15), **-3.2%** — same pattern, fading off Monday's hot run. No fresh news found.
Both remain standing-watch-only, closed positions from Friday 11/6's trade (small realized gains, +$12.06 combined) — this is a pullback after two strong up days, not a catalyst-driven move. No re-entry proposed without a fresh qualifying setup on its own merits.

## Pre-market small-cap-tech shortlist
Not checked this build (after-hours, regular-session-only scan data) — Technology sector sweep found only thin/no-catalyst names all day today (JZ, HOLO, TLS — TLS reclassified as enterprise security with a real catalyst, scored 60, not executed). Re-run fresh at the 9:40am cycle.

## Market condition — overnight/pre-market Tuesday 2026-11-10
SPX 7,549.94, NDX 27,907.63, VIX 20.17 — essentially flat overnight vs. Monday's 3pm read (SPX 7,561.55, VIX 19.87), ticking up slightly but still holding under 21. No major overnight macro shock found via WebSearch.

## Pending binary events / standing notes (carried forward)
- LOAR/MGRC/ZG/NXT remain on the user's explicit hold from the earlier-week instruction — no new information this pass.
- DAIC (CID HoldCo) remains excluded from consideration regardless of any future move — tied to the 2026-09-17 "don't chase" realized-loss lesson.
- Benchmark account 570898312 (ETF buy-and-hold) remains **read-only** — tracked for performance comparison only, never traded. **Updated 2026-11-10 by explicit user instruction:** the user made a deposit to the agentic account (confirming the $600 increase flagged at today's 9:40am cycle — not a trading gain) and separately moved crypto holdings out of the benchmark account into another account of theirs. Going forward, the benchmark comparison should be read as the **stock + ETF portion only** of account 570898312 — crypto is no longer part of that benchmark.
- **Standing note, added 2026-11-10 by explicit user instruction** ("Lots of turbulence right now. Sitting patiently is ok"): the user is explicitly comfortable with the account sitting flat/idle through choppy conditions rather than forcing a trade to stay active. This reinforces, not loosens, the existing 85-confidence bar and DON'T-CHASE principle — patience is the explicitly preferred default right now, not just a tolerated fallback when nothing qualifies.
- SECTOR CONCENTRATION CAP and MICRO-CAP CONCURRENCY CAP remain in effect for every cycle until the user says otherwise.
- Options-flow scan (8719a93e-58d5-4b84-9905-c0c93b7676c1) was rate-limited on **every single cycle today** (9:40am, 11am, 12pm, 3pm) — worth flagging to the user as a persistent, not intermittent, issue if it continues tomorrow.

## Options consideration
Covered above for last night's top 3 (ONTO/TTWO/TTD) — all preliminary/structural only. Updated this morning's top candidate, **VG**: listed chain confirmed, expirations include 2026-11-13 (3 DTE, too close) and 2026-11-20 (10 DTE, within window) — DTE window: PASS (structural), listed chain: PASS. Premium/OI/live spread: not checked (pre-market, no live tradeable quote). Re-pull live for all four (ONTO/TTWO/VG, TTD now demoted) fresh at the 9:40am opening-bell cycle before any options consideration — this is pure head-start research, not a pre-approval of any kind.

## 9:40am opening-bell cycle (2026-11-10) — results
**Account:** flat, **$3,534.01** (up from Monday's $2,934.01 — a **$600 increase** with `pending_deposits: $600` showing on the account; this looks like a deposit, not a trading gain — flagging plainly since today's account value jumped exactly $600 with zero trades taken). Balance now clearly >$2,000, so OPTIONS SIZING cap reverts to 10% of balance (~$353) once/if an options position is considered. No positions open, nothing to manage. Sector concentration: 0/2 every sector. Micro-cap slot: open. Time-stops: none. WBD one-time exit instruction from 2026-09-22 remains moot (no WBD position has existed in months).
**Market:** SPX 7,506.27, NDX 27,689.57, VIX 20.81 — ticked up slightly from yesterday's close (VIX 19.87→20.81), still range-bound, no major shock.
**Crypto watchlist:** mixed today (no repeat of yesterday's broad rally) — MARA +6.3%, RIOT +4.7% up; COIN -1.5%, MSTR -1.6%, CLSK -0.7%, HUT -1.1%, BMNR -2.7%, HOOD -1.1% down; CORZ +0.5% flat. No action, informational only.

**Carryover candidates from the overnight watchlist, re-verified live at the open:**
- **ONTO:** $198.26 vs Monday close $194.04, +2.2% — but the first 10 minutes ranged $196.31-$206.09 (~4.9% range), a spike-and-fade pattern typical of opening noise. **Too early to call — re-check at 11am.**
- **TTWO:** $221.31 vs close $207.40, +6.7% — first 10 min ranged $217.73-$229.46 (~5.3%), same opening-noise pattern despite the strong headline gain. **Too early to call — re-check at 11am.**
- **VG:** $11.90 vs close $11.80, +0.8% — moderated further from this morning's pre-market +3.6%; first 10 min ranged $11.60-$12.19 (~5% range). **Too early to call — re-check at 11am.**
- **TTD:** demoted per the 8am true-up (reversed to -5.2% pre-market); live now -0.6% — no longer a live bullish candidate, dropped from consideration.

**Full 15-scan sweep — notably quiet session:** General=0, Small-mid=2 (**PEPG +163%** $166M relvol 37x, TTEC +37.6% $69M relvol 7.8x), Mid-cap=0, Large-cap=0, Technology=3 (PXLW +29.6% $31M relvol 872x, TTEC, MNDO +45.4% $17.6M relvol 146x), Healthcare=2 (PEPG, AMIX +25.3% $3.3M relvol 37x), Industrials=0, Energy=0, Communication Services=0, Utilities=0, Consumer Defensive=1 (TWG +12.7% $2.2M), Real Estate=0, Financial Services=0, Consumer Cyclical=0, Basic Materials=0. Options-flow scan: **unavailable — rate-limited again, every cycle this week so far, not retried.**

**Step 5 catalyst verification on fresh sweep hits:**
- **PEPG (+163%, $166M):** No same-day catalyst. Next verified earnings date is 2026-11-24 (two weeks out), not today — unconfirmed WebSearch mentions of 11/5 or 11/10 earnings dates do not match the earnings-calendar record. **No catalyst found — fails Step 5**, despite the extreme magnitude.
- **TTEC (+37.6%, $69M):** Actually reported **yesterday PM** (11/9) with a **miss** (-$0.10 actual vs $0.19 est, verified) — today's big rally directly contradicts that miss, no news found explaining the disconnect (same pattern as last night's LQDA anomaly). **Unexplained — flagged, not scored.**
- **PXLW (+29.6%, $31M):** Next earnings is tomorrow PM (2026-11-11), not yet reported. **No catalyst found for today's move — fails Step 5.**
- **MNDO (+45.4%, $17.6M):** Thin, low-liquidity name with a documented history of "little company news... low liquidity exaggerates moves" per WebSearch. **No catalyst found — fails Step 5.**
- **AMIX, TWG:** sub-$5M extreme microcaps, consistent with the no-catalyst speculative-froth pattern seen all week; not individually searched. **No confirmed catalyst, fails Step 5.**

**Standing watch — AAOI/COHR:** AAOI $49.54 vs Monday close $52.10, -4.9%; COHR $222.41 vs close $225.19, -1.2% (COHR partially recovering from this morning's -3.2% pre-market read). Both continuing Tuesday's pullback after Monday's hot run — no fresh news, not a trade signal.

**Verdict:** No qualifying trade this cycle. Every carryover bullish candidate (ONTO/TTWO/VG) is genuinely too early to call 10 minutes into the session — all three showed a sharp spike-and-fade in the opening range, exactly the kind of volatile opening-minute noise Step 6 expects and says not to force a read on. Every fresh sweep hit either has no confirmed catalyst or (TTEC) directly contradicts its own confirmed catalyst. Carrying ONTO/TTWO/VG forward to the 11am cycle for a cleaner structural read once the open settles.
**No-catalyst candidates suggested for approval:** No — PEPG/MNDO/TWG/AMIX's magnitude is notable but none shows a clean, compelling setup beyond "unexplained spike," and TTEC's rally actively contradicts its own catalyst.
**Options potential:** not run — no candidate cleared Step 6 (all three carryovers flagged "too early to call").
**Exceptional small-deal exception:** not invoked. **Small-cap tech:** PXLW/MNDO flagged above, no catalyst, not pursued even under the carve-out's approval gate.
**Time-stops:** none (flat). **Sector concentration:** 0/2 every sector. **Micro-cap slot:** open.

## 11:00am cycle (2026-11-10) — results
**Account:** flat, $3,534.01 (the $600 Monday-to-today increase noted at 9:40am stands — still appears to be a deposit, no trades have occurred). Sector concentration: 0/2 every sector. Micro-cap slot: open. Time-stops: none.
**Market:** SPX 7,502.02, NDX 27,710.97, VIX 20.65 — essentially flat vs. the 9:40am read, range-bound.
**Crypto watchlist:** MARA +11.1% (continuing to extend), RIOT +1.8%, CORZ +1.8% up; COIN -4.0%, MSTR -3.7%, CLSK -3.6%, BMNR -5.0%, HOOD -2.6%, HUT -0.4% down — more red than green this cycle, a shift from yesterday's broad rally. No action, informational only.

**Carryover candidates, re-verified:**
- **ONTO:** $198.99 vs Monday close $194.04, +2.6% — holding roughly steady vs. the 9:40am read. Catalyst now 2 days old (Monday PM beat); no longer fresh. Not re-scored.
- **TTWO:** $224.32 vs close $207.40, **+8.1%** — strengthening further (was +6.7% at 9:40am). 30-min bars show early chaos (high $229.46/low $214.29 in the first 30 min) resolving into a tighter, higher range the last 30 min ($222.50-$225.84) — structure is settling into a tradeable base. Catalyst is 2 days old.
- **VG:** $12.04 vs close $11.80, +2.0% — modest, steady. Catalyst also 2 days old.
- **AAOI/COHR:** AAOI $48.08 vs Monday close $52.10, -7.7% (deepening); COHR $217.26 vs close $225.19, -3.5%. Both continuing the pullback, no fresh news. Standing watch only.

**Full 15-scan sweep — three fresh confirmed-catalyst names found this cycle:**
General=1 (SECZ +33% $1.14B), Small-mid=5 (SECZ, PEPG +136%, PDYN +19% $175M, TTEC +54%, KULR +30% $75M), Mid-cap=0, Large-cap=0, Technology=6 (SECZ, PXLW +15% relvol 1046x, PDYN, TTEC, KULR, MNDO +46% relvol 165x), Healthcare=4 (SENS +22% $518M, PEPG, AMIX +17% relvol 322x, ELAB +5% $1.3M), Basic Materials=1 (TREO +36% $27M), Consumer Cyclical=1 (SSM +11% $1.7M), Financial Services=0, Real Estate=0, Consumer Defensive=0, Utilities=0, Communication Services=0, Energy=0, Industrials=1 (CIIT +6% $2.7M). Options-flow scan: **unavailable — rate-limited again.**

**Step 5 catalyst verification on the three real-sized fresh names:**
- **SECZ (Securitize, $1.14B):** Reported Q3 2026 last night (11/9 PM) — a **miss** (-$0.41 actual vs -$0.03 est, verified). BUT the same earnings call announced genuine fresh business news: a tokenized money-market fund with BlackRock, a tokenized ARK venture fund, a Neuberger high-income fund tokenization, and a Cantor Fitzgerald collaboration on onchain IPOs. **Mixed/real catalyst** — the EPS line missed badly but the strategic announcements are the likely actual driver of the +33% move.
- **SENS (Senseonics, $518M):** Reported Q3 2026 last night (11/9 PM) — a **beat** (-$0.50 actual vs -$0.52 est, verified), plus management presenting at the Stifel Healthcare Conference today (11/10). **Real/fresh catalyst confirmed.**
- **PDYN (Palladyne AI, $175M):** Reported Q3 2026 **this morning** (11/10 AM) — a **beat** (-$0.17 actual vs -$0.23 est, verified), continuing a trend of narrowing losses each quarter. **Real/fresh catalyst confirmed** — the freshest of the three (same-day AM report).
- **PEPG, TTEC, PXLW, MNDO, KULR, TREO, SSM, CIIT, ELAB, AMIX:** unchanged or newly thin/no-catalyst — **no confirmed catalyst, fails Step 5.**

**Step 6 price structure on the three confirmed-catalyst names (30-min bars since open):**
- **SECZ:** opened $8.73 → spiked to $9.73 → dropped to $8.25 → recovered to $9.86 → pulled back to $9.32-9.36. ~20% total range across 90 minutes, no clear resolved base. **Chaotic — fails Step 6**, re-check later.
- **SENS:** opened $12.445 → spiked to **$13.978** → crashed to $11.67 → now $12.03. ~19.6% range, classic spike-and-fade. **Chaotic — fails Step 6**, re-check later.
- **PDYN:** opened $3.74 → early range $3.56-$4.08 → resolved into a tighter, higher range the next two bars ($3.82-$4.24, then $4.10-$4.24) — now consolidating near highs with a definable floor ~$4.10. **Passes Step 6** — early chaos resolved into a tradeable structure.

**Confidence scores:**
- **PDYN: 78** — clean same-day beat, structure has resolved well, narrowing-losses trend is a genuine positive arc. Held below 85 by: still a small ($175M) name with real losses every quarter, already +19% intraday, liquidity/spread not deeply tested. Not executed.
- **TTWO: 72** — cleanest structure of all the carryovers, but catalyst is now 2 days stale and the stock is up a cumulative ~8% over two sessions — the "already extended" entry the DON'T-CHASE principle flags as weaker outside the formal small-cap-tech carve-out too. Not executed.
No other candidate reached scoring (SECZ/SENS failed Step 6 chaos; everything else failed Step 5).

**Options potential:**
- **PDYN:** listed chain confirmed, 2026-11-20 expiration (10 DTE, within window) — DTE window: PASS (structural), listed chain: PASS. Premium/OI/live spread not pulled (stock score below 85, no execution contemplated).
- **TTWO:** listed chain confirmed (per yesterday's build), 2026-11-20 (10 DTE) within window — same structural PASS, not pursued further.
**No-catalyst candidates suggested for approval:** No — PEPG/TTEC/PXLW/MNDO/KULR/TREO's magnitude is notable but none shows a clean setup distinct from unexplained/thin-float churn.
**Exceptional small-deal exception:** not invoked. **Small-cap tech:** PXLW/MNDO/KULR flagged, no catalyst, not pursued; PDYN is NOT subject to the small-cap-tech carve-out (market cap $175M, above the sub-$15-20M threshold) and was scored normally.
**Time-stops:** none (flat). **Sector concentration:** 0/2 every sector. **Micro-cap slot:** open.
**Qualifying trade:** none this cycle — PDYN (78) and TTWO (72) scored but neither cleared 85.

## 12:00pm cycle (2026-11-10) — first cycle under the new blended-strategy framework
**Account:** flat, $3,534.01. Sector concentration: 0/2 every sector. Micro-cap slot: open. Time-stops: none.
**Market:** SPX 7,486.54, NDX 27,531.73, VIX 20.82 — flat vs. 11am, still range-bound.
**Crypto watchlist:** mostly red today — CLSK -6.6%, BMNR -5.3%, MSTR -4.6%, COIN -4.0%, HOOD -3.5%, HUT -2.6% down; MARA +5.8% up (lone standout); RIOT flat, CORZ -0.3%. No action, informational.
**Carryover:** ONTO flat (+0.1%), VG flat (+0.8%), TTWO holding +7.2%, TTD whipsawed back to +4.0% (was -5.2% at 9:40am) — too unstable to treat as a clean candidate given the reversal pattern today. AAOI -9.2%/COHR -7.4% continuing to deepen, no fresh news, standing watch only. PDYN/TTWO from the 11am cycle: PDYN cooled to only +6.5% (down from +19% premarket), TTWO still the strongest carryover.

**Full 15-scan sweep — two new real-sized earnings movers found:**
General=2 (SENS +13.7%, SECZ +22.7%), Small-mid=6 (SENS, SECZ, PEPG +119-136%, PDYN, TTEC +68-81%, KULR +20-21%), Mid-cap=2 (**AAON new $5.18B +21.7%**, CSQR new $2.54B +15.1%), Large-cap=1 (**EMBJ new $13.75B +6.8%**), Technology=6 (SECZ, PXLW +29%, TTEC, KULR, LGCL new +13%, MNDO +46-60%), Healthcare=5 (SENS, PEPG, LGVN new +38%, TCRT new +7.5%, BNGO new +12%), Industrials=3 (APT new +8%, RAIL new +6.5%, CIIT +6%), Consumer Cyclical=1 (EFOI new +11%), Financial Services=1 (AAME new +13.3%), Communication Services=1 (**ZIP new $353M +33.9%**), Basic Materials=1 (TREO +27.9%), Real Estate=0, Consumer Defensive=0, Utilities=0, Energy=0. Options-flow scan: **unavailable — rate-limited again, every single cycle today.**

**Step 5 catalyst verification on the four new real-sized names:**
- **AAON ($5.18B, HVAC/water-systems manufacturer):** Q3 2026 reported last night (11/9 PM) — **big beat**, $0.83 actual vs $0.57 est (+46%), the third consecutive quarterly beat (also beat Q1 and Q2 2026). **Real/fresh catalyst confirmed.** Notable: the stock traded near $127 in June 2026 before a guidance-driven selloff into the $60s-80s range — today's beat may mark the start of a base, worth re-evaluating as a possible LONG-HORIZON candidate on a future cycle once the post-earnings dust settles (not scored as long-horizon today — today's move is clearly the earnings catalyst, a day/swing read).
- **ZIP (ZipRecruiter, $353M):** Q3 2026 reported last night (11/9 PM) — beat, $0.06 actual vs -$0.01 est (swung positive vs. an expected loss). **Real/fresh catalyst confirmed.**
- **CSQR (Csquare, $2.54B, post-IPO industrial/SPAC-type name):** Q3 2026 reported last night — a **miss** (-$0.58 actual vs -$0.49 est), yet stock +15.1%. No explanation found for the disconnect (same "unexplained" pattern as LQDA/TTEC earlier this week). **Fails Step 5 as a clean catalyst** despite real size.
- **EMBJ (Embraer, $13.75B, large-cap aerospace):** Q3 2026 reported **this morning** (11/10 AM) — a **big miss** ($0.398 actual vs $0.87 est), yet stock only +6.8%, with a forward ADS split also announced and "tariff impact already priced in" per one source. Mixed/contradictory signal. **Fails Step 5 as a clean catalyst.**
- **PEPG, TTEC, PXLW, MNDO, KULR, TREO, LGCL, LGVN, TCRT, BNGO, APT, RAIL, CIIT, EFOI, AAME:** no confirmed same-day catalyst found (consistent thin-float/no-catalyst pattern) — **fails Step 5.**

**Step 6 price structure on AAON and ZIP (30-min bars):**
- **AAON:** opened $71.59 → first 30min range $67.87-$78.50 (wide, typical opening chaos) → resolved into a tighter $75-80 band over the next 2.5 hours, now consolidating ~$75-77.5. Clean-ish resolved structure. **Passes Step 6** — but the stock already gapped ~22% at the open and this is now ~3 hours into the move (12pm cycle), which is a weaker, more extended entry per the don't-chase principle applied qualitatively to non-small-cap-tech names.
- **ZIP:** opened $4.705 → climbed steadily to a high of $6.03 → pulled back to $5.72 in the most recent 30-min bar (-3.7% off the peak). Less resolved than AAON — still showing active profit-taking.

**Confidence scores:**
- **AAON: 76** — strong, confirmed beat (3rd consecutive), real size/liquidity, structure has resolved into a tradeable range. Held below 85 primarily by extension/lateness (~3hrs post-gap) rather than catalyst or structure quality. Not executed. Flagged as a candidate to re-evaluate for the LONG-HORIZON track once the post-earnings base settles.
- **ZIP: 68** — real beat but smaller/more volatile name, structure still actively pulling back off its peak rather than consolidating. Not executed.
No other candidate reached scoring (CSQR/EMBJ failed Step 5 on contradictory catalyst signals; everything else had no catalyst at all).

**Options potential:** not pulled live for AAON/ZIP this cycle (both below 85, no execution contemplated) — will re-check if either strengthens next cycle.
**No-catalyst candidates suggested for approval:** No — CSQR and EMBJ's up-moves directly contradict their own earnings misses, which is a weaker basis for a no-catalyst discretionary flag than a genuinely unexplained clean technical setup.
**Exceptional small-deal exception:** not invoked. **Small-cap tech:** PXLW/MNDO/KULR/LGCL flagged, no catalyst, not pursued.
**Time-stops:** none (flat). **Sector concentration:** 0/2 every sector. **Micro-cap slot:** open.
**Qualifying trade:** none this cycle — AAON (76) and ZIP (68) scored but neither cleared 85. Consistent with the user's "sitting patiently is ok" guidance during this turbulent stretch.

## 3:00pm cycle (2026-11-10) — results

**Account:** Still flat, $3,534.01 cash/total value, no open positions (stock or options). Micro-cap slot open. Sector concentration: none open. Time-stop flags: none. Options sizing cap now 10% of balance = ~$353 (balance crossed $2000). `pending_deposits` field shows $600 — status unclear (likely the same deposit flagged at 9:40am still settling in the field), no action needed.

**Market:** SPX 7,505.86 / NDX 27,625.18 / VIX 20.09 — choppy, VIX ticking down slightly from midday.

**Crypto watchlist:** MARA +7.2% (standout again), CORZ +0.9%, RIOT +0.8% — rest red: COIN -3.7%, MSTR -4.7%, CLSK -6.9%, HUT -1.9%, BMNR -4.9%, HOOD -3.3%.

**Carryovers re-verified:** ONTO +0.6% (flat, still too-early-to-call), VG +0.5% (flat), TTWO +8.1% (continuing to hold/extend), TTD +3.4% (still whipsawed/unstable, not treating as clean), AAOI -7.9% / COHR -5.6% (both continuing to bleed, no fresh news, watch only).

**Full sweep (all scans run; Options-flow scan 8719a93e again rate-limited — unavailable, standard handling):**
- General: 3 (SENS, SECZ, ZIP)
- Small-mid: 9 (SENS, SECZ, ZIP, RAIL, PEPG, HUCK, PLX, TTEC, KULR)
- Mid-cap: 4 (SANM, AAON, CSQR, PRCH)
- Large-cap: 1 (EMBJ)
- Basic Materials: 1 (TREO, $27M — too illiquid)
- Consumer Cyclical: 1 (EFOI, $28M — too illiquid)
- Financial Services: 3 (PRCH, AAME $23M — too illiquid, AVAT $35M — too illiquid)
- Real Estate: 0
- Consumer Defensive: 1 (MSS, $862K — too illiquid)
- Utilities: 0
- Communication Services: 1 (ZIP)
- Energy: 0
- Industrials: 2 (APT $57M — too illiquid, RAIL $146M — too illiquid)
- Technology: 7 (SECZ, PXLW, HUCK, TTEC, KULR, LGCL $1.8M — too illiquid, MNDO)
- Healthcare: 6 (SENS, PEPG, PLX, LGVN $6.4M — too illiquid, AMIX $3.3M — too illiquid, BNGO $16M — too illiquid)
- Options-flow: unavailable (rate-limited every cycle this session)

**Catalyst verdicts (new/re-checked names):**
- ZIP: real/fresh catalyst — Q3 reported 2026-11-09 pm, verified=true, actual $0.06 vs est -$0.01 (swing to profit). Passes.
- SANM ($8.0B): real/fresh catalyst — Q4 reported 2026-11-09 pm, verified, actual $4.43 vs est $3.19 (4th consecutive beat). Catalyst confirmed, but see Step 6 below.
- KULR ($75M): earnings reported today am, verified, actual +$0.10 (no estimate to compare) — directionally positive but WebSearch found no dated corroboration. Treating cautiously; see Step 6.
- PRCH ($2.36B): earnings were reported 2026-10-28 (13 days ago) — stale, not fresh. Today's move unexplained by that report; WebSearch surfaced an undated KBW downgrade note. No fresh catalyst found.
- PEPG ($166M, +90% intraday): Q3 reported today am, actual -$0.28 vs est -$0.27 — essentially an inline miss, does NOT explain a 90% rally. Unexplained anomaly — joining CSQR/EMBJ/LQDA/TTEC this week's pattern. Fails Step 5.
- HUCK ($138M): no earnings event found; WebSearch found no dated catalyst (profile-page noise only, some content mismatched to a different ticker). No catalyst found.
- AAON/CSQR/EMBJ/TTEC/PXLW/MNDO/SECZ/SENS: verdicts unchanged from earlier cycles today (AAON real/fresh beat; CSQR/EMBJ unexplained-anomaly/contradictory; TTEC/PXLW/MNDO no-catalyst; SECZ/SENS chaotic, failed Step 6 earlier).
- All other sweep names: too illiquid (market cap noted above).

**Step 6 price structure:**
- ZIP: Opened $4.70, climbed in an orderly uptrend (one clean pullback $5.98→$5.72, then resumed) to $6.42 by the close of this window — a genuine resolved uptrend, passes structurally. BUT now ~5.5 hours into an already-extended move (up ~37% intraday, more off yesterday's close) — DON'T-CHASE discount applies heavily this late in the day.
- SANM: Opened $164.95, spiked to $167.97, then reversed hard down to $150.11 (a ~10% round-trip whipsaw), then partially recovered to $155.88 — chaotic, failed-breakout pattern. Fails Step 6 despite a clean confirmed catalyst.
- KULR: Opened $1.80, ran to $2.20, then chopped back down to ~$1.98 with several near-zero-volume bars — spike-and-fade, unresolved. Fails Step 6.

**Confidence scores:** ZIP = 70 (clean catalyst + resolved structure, but heavily discounted for lateness/extension — don't chase). SANM and KULR not scored (failed Step 6). Neither candidate reaches scoring threshold vs. the 85 bar.

**No-catalyst candidates suggested for approval:** No.
**Small-cap tech candidates under consideration:** No new ones awaiting approval. HUCK/PXLW/MNDO/LGCL noted as no-catalyst, not surfaced.
**Time-stop flags:** None (no open positions).
**Micro-cap concurrency slot:** Open.
**Sector concentration slots:** None open.
**Options checklist status:** No options position open. Sizing cap now ~$353 (10% of $3,534 balance).
**Stock position status:** None open.

**Action taken:** None. No trade this cycle — consistent with "sitting patiently is ok." ZIP is the closest candidate but is being passed on for being too extended this late in the session; would need a fresh, earlier-caught setup to qualify next time.
