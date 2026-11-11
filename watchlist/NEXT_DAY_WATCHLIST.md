# Next-Day Watchlist — true-up for Wednesday, 2026-11-11

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.** Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as an actionable candidate.

## Note on this file's state

This build supersedes last night's 2026-11-10 6pm build (FRNM/MRCY/CRWV/ZIP/SANM as top candidates) with fresh overnight/pre-market data. (An earlier local git-cache issue briefly made it look like that 6pm build and the whole day's history had vanished from the branch — a `git fetch` confirmed it was a stale local ref, not real data loss; everything is intact in the repo's history.)

## Step 0 — held position check

No stock or options position held (`get_equity_positions`/`get_option_positions` both confirmed empty, re-verified this pass). Nothing to defend.

## Standing watch — optoelectronic sector (AAOI / COHR)

Both up strongly pre-market, part of a **sector-wide move**, not isolated news:
- **AAOI**: prior close $48.32 → pre-market ~$51.60-51.72, **+6.9%**. Extending higher.
- **COHR**: prior close $214.66 → pre-market ~$233.15-234.80, **+8.9%**. Extending higher.
- Context (WebSearch): the AI-optics group (Coherent, Lumentum, and peers) has been rallying this week on "AI datacenter demand" and M&A-driven re-rating commentary (Marvell's $115B Lumentum deal cited as highlighting "the value of scarce AI optics"). COHR specifically beat on revenue (+49.9% YoY) when it reported 2026-11-04 and has been whipsawing hard since (a 13% one-day drop, then sharp rebounds) — still net up on the week but volatile. This is sector-wide tailwind, not a fresh dated catalyst on either name specifically this morning.
- Standing note unchanged: this is a watch item per explicit user interest in the sector, not a trade signal — the 9:40am cycle still applies its normal Step 5/6 gate before treating either as live.

## Overnight follow-through on yesterday's (2026-11-10) candidates

| Ticker | Yesterday's close | Pre-market now | Change | Status |
|---|---|---|---|---|
| **CRWV** | $48.73 | ~$56.14-56.20 | **+15.3%** | STRENGTHENED sharply — already a very large pre-market gap on top of yesterday's earnings beat. No specific new overnight catalyst confirmed via WebSearch (only historical CRWV volatility pattern found, nothing dated to today) — treat the size of this gap itself as the headline risk: this is already a big move before the bell, DON'T-CHASE caution applies heavily at the open. |
| **MRCY** | $83.58 | ~$86.50-87.38 | +3.5% further | STRENGTHENED modestly — continuing the post-beat move cleanly. |
| **SANM** | $155.43 (after a whipsaw day) | ~$165.00-166.59 | +6.9% further | STRENGTHENED — resolving cleaner than yesterday's chaotic intraday whipsaw; worth a fresh Step 6 structure check at the open since yesterday's disqualifier was structure, not catalyst. |
| **FRNM** | $10.77 | ~$10.94 (wide spread, bid $10.02/ask $11.10) | +1.6%, faded from last night's $11.42 AH print | WEAKENED — losing steam, thin/wide pre-market market. Still no options chain (unchanged). |
| **ZIP** | $6.59 | ~$6.55-6.58 | flat/slightly down | WEAKENED/fizzled — no overnight follow-through on yesterday's extended-but-real move. Demote. |

## Today's (2026-11-11) scheduled earnings — before the open

High-market-cap AM reporters today are thin; notable ones already reported with results in (per calendar): RUM (-$0.19 vs -$0.13 est, miss), ODD/Smartsheet ($0.37 vs $0.27 est, beat), NSANY (-$0.13, loss), GIB ($1.65 vs $1.64, in-line), BGSI ($0.68 vs $0.86, miss). None of these have been checked yet for pre-market price reaction — flag for the 9:40am cycle to verify fresh if any show unusual pre-market volume. After today's close (sets up Thursday, not today): CTVA, FNV, TTEK, ENS, CAE, OR — not actionable today.

## Macro / index tone

SPX 7,520.93 / NDX 27,740.80 (both modestly higher vs yesterday's close) / **VIX 18.46**, down meaningfully from yesterday's 20.09-20.82 range — tone has improved overnight, less choppy than described in the "sitting patiently is ok" stretch earlier this week. Worth noting but not a reason to loosen any standing gate.

## Pre-market small-cap-tech shortlist (Step 3b)

Technology sector scan (scan_id 4ab9bad9) returned **0 matches** pre-market. Nothing to shortlist this morning.

## Options consideration — top candidates (PRELIMINARY, NOT LIVE QUOTES — all priced off yesterday's 4pm close, before today's pre-market gaps)

- **CRWV** $56 call, 2026-11-20 (9 DTE): close $2.66/contract ($266) — **passes current $353 sizing cap**, OI 1,387, volume 413, tight $2.60/$2.71 spread. Structural read: DTE pass, premium pass, listed chain pass, liquidity good. **Caveat: this premium predates today's +15% pre-market gap in the stock — it will reprice materially higher once the options market opens and must be re-pulled live, not used as-is.**
- **MRCY** $87.5 call, 2026-11-20 (9 DTE): close $4.33/contract ($433) — fails the $353 cap; wide $2.75/$5.90 spread (thin), OI only 60, volume 36. Weak structurally even before repricing for the further +3.5% pre-market move.
- **SANM** $165 call, 2026-11-20 (9 DTE): close $4.65/contract ($465) — fails the $353 cap; wide $3.30/$6.00 spread, OI 852, volume 186. Also pre-dates the +6.9% pre-market move.

## User instruction, 2026-11-11 (pre-open, via chat)

User flagged the morning tape independently ("tech stocks, semi and opto electronics seem to be climbing") and then gave explicit direction: **"CRWV, COHR and AAOI can all be measured for entry, tightly supported stops would be the plan."** This is a real-time steer to give all three serious entry consideration at the open, with the stop specifically anchored tight to the nearest clear support level (not the default wider band) if any of them qualifies. This does not waive the normal gates — each still needs Step 5 catalyst confirmation and Step 6 clean structure before sizing/entry, and CRWV's size of pre-market gap still warrants normal don't-chase judgment — but the user's emphasis is to actively look for a tight, support-based entry on these three rather than pass on them by default. Carry this into the 9:40am cycle.

## Summary for the 9:40am cycle

Ranked by live-setup likelihood: **CRWV** (biggest pre-market move, options structurally the cleanest of the three but the stock-side move is already very large — treat as a don't-chase risk, not a slam dunk), **SANM** (cleaner structure forming, re-check Step 6 fresh), **MRCY** (still constructive but thinner options liquidity), then **AAOI/COHR** (standing watch, sector-wide tailwind, re-verify catalyst specificity before scoring). **FRNM** and **ZIP** are demoted — no real overnight follow-through.

## 9:40am opening-bell cycle (2026-11-11) — results

Account: still flat, $3,534.01, no open positions. SPX 7,587.52 / NDX 28,235.37 / VIX 18.47 — risk-on tone continuing from pre-market. No WBD/GRML/CRML positions exist (that one-time instruction from weeks ago is stale/inapplicable — nothing to act on).

**CRWV / COHR / AAOI — per explicit user instruction this morning to measure these three for entry with tightly-supported stops:** all three gapped up hard and were still actively whipsawing in the first ~12 minutes of the session:
- CRWV: $55.65-$57.40 range in the first 10 minutes (~3% bar-to-bar swings), still oscillating as of 9:42am ($55.66-56.50 the last two 1-min bars).
- COHR: $228.55-$238.65 range, still swinging ($229.01-233.65 the last two bars).
- AAOI: $51.53-$53.85 range, marginally the most orderly of the three (higher lows visible) but still $53.21-54.10 swings minute-to-minute.

None had resolved into a level clean enough to place a genuinely *tight, support-based* stop against (per the user's own stated plan) — any stop set right now would be guessing at a level mid-whipsaw, not anchored to real support. Per standing Step 6 guidance ("big catalyst days often show violent early price discovery that only resolves into a tradeable base later — it's fine to pass early and re-check later"), all three are flagged **too early to call — re-check at 11am**, not dropped. This isn't a pass on the user's idea, it's in service of it: a tight stop needs an actual support level to anchor to, which hasn't formed yet.

**Full sweep:** General=1 (BRAI, no catalyst found — erratic history of unexplained swings, skip), Small-mid=1 (BRAI, same), Mid-cap=0, Large-cap=0, Basic Materials=1 (YMAT $4.6M, too illiquid), Consumer Cyclical=0, Financial Services=1 (CANG $47M, too illiquid), Real Estate=0, Consumer Defensive=0, Utilities=0, Communication Services=0, Energy=0, Industrials=1 (BKYI $4.9M, too illiquid), Technology=1 (BRAI, same), Healthcare=0, Options-flow=rate-limited/unavailable (standard, every cycle this session). Nothing here clears any bar.

**No-catalyst candidates suggested for approval:** CRWV/COHR/AAOI are effectively in this bucket (sector-momentum move, no fresh company-specific dated catalyst on COHR/AAOI specifically — CRWV has its own fresh earnings beat) — already covered by the user's own explicit go-ahead this morning, so no separate approval needed; carrying forward as "too early to call" rather than fully approved-and-pending, since structure hasn't qualified yet either.
**Small-cap tech candidates:** none.
**Time-stop flags:** none (no positions).
**Micro-cap concurrency slot:** open.
**Sector concentration slots:** none open.
**Options checklist status:** no options position open; sizing cap ~$353 (10% of balance).
**Stock position status:** none open.

**Action taken:** None. Continuing to watch CRWV/COHR/AAOI into the 11am cycle for a resolved, tradeable structure.

## 11:00am market-hours cycle (2026-11-11) — results

**Account:** Was flat $3,534.01 going into this cycle. SPX 7,607.91 / NDX 28,422.44 / VIX 17.71 — continued risk-on.

**CRWV/COHR/AAOI structure update:** By 11am all three had resolved out of the early-session chaos into genuine, clean higher-lows uptrends (confirmed via 5-minute bars since the open) — CRWV built a base ~$58.90-59.50 before continuing to $60+; COHR built a base ~$237-241 before continuing to $245; AAOI's base formed earliest (~$54.30-55.50) before continuing to $56+. All three now have real, identifiable support to anchor a tight stop to, per the user's own plan.

**Sector cap note:** CRWV, COHR, and AAOI are all Morningstar Technology-sector names. The SECTOR CONCENTRATION CAP limits new positions to 2 per sector at a time, so only 2 of the 3 could be opened this cycle.

**Trade 1 — COHR:** Bought 1 share @ $242.46 (limit $245.30). Catalyst: company's own Nov 4 revenue beat (+49.9% YoY) plus this week's "AI optics" sector re-rating — broad-basket/sector-driven rather than a single fresh dated event, but real and company-grounded; covered by the user's explicit go-ahead this morning. Stop: resting stop_market sell at **$240.50** (-0.8% from entry at placement, tight/support-based, placed and confirmed). 

**Trade 2 — AAOI:** Bought 6 shares @ $56.31 (limit $56.40). Catalyst: no company-specific news found (pure sector-sympathy move off the AI-optics theme) — a no-catalyst/broad-basket case, covered by the same explicit user go-ahead. Stop: resting stop_market sell at **$55.00** (-2.3% from entry, tight/support-based, placed and confirmed).

**CRWV — BLOCKED:** The buy order (5 shares, limit $60.60) was denied by a permission-layer safety classifier on this end (not a Robinhood rejection) with no reason given — likely tripped by the size of the day's move. I did not retry the identical order (per the denial's own instructions not to attempt workarounds). Net effect: only 2 of the 3 names got opened, which conveniently fits the 2-per-sector cap anyway — AAOI took the slot CRWV would have used. **Flagging this for you directly: if you want CRWV specifically, you'd need to place that one yourself in the app; I won't keep retrying it here.**

**Other sweep activity:** Full sweep run (General=2: RSKD real/fresh catalyst — see below; BRAI no catalyst. Small-mid=2: same two. Mid-cap=0. Large-cap=0. Basic Materials=2: GEVO $344M real/fresh catalyst — beat reported 11/10pm, extended/not chased; YMAT $4.6M too illiquid. Consumer Cyclical=1: **FOSL** $467M real/fresh catalyst (beat $0.23 vs -$0.06 est, reported 11/10pm, verified) — structure resolved into a tight ~$9.90-10.14 base but already +28% on the day by the time of evaluation — DON'T-CHASE discount applied, scored ~72, not entered. Financial Services=1: CANG $47M too illiquid. Real Estate=0. Consumer Defensive=1: BGS $216M, catalyst exists (beat, reported 11/10pm) but modest size, not pursued this cycle. Utilities=1: NXXT $315K too illiquid. Communication Services=1: ZDGE $35.5M too illiquid. Energy=0. Industrials=1: BKYI $4.9M too illiquid. Technology=4: RSKD (real/fresh catalyst, beat reported today am, but **Technology sector cap already at 2/2** with COHR+AAOI open — not opening a third), BRAI/BDAI/OBAI all no-catalyst or too illiquid. Healthcare=2: CRVO $20.9M, LSTA $11.1M, both too illiquid. Options-flow: rate-limited/unavailable again (standard).

**Confidence scores:** FOSL ~72 (real catalyst, resolved structure, but already extended). RSKD not scored (blocked by sector cap, not a Step 5/6 failure). GEVO not scored (real catalyst but extended, didn't rank above FOSL).

**No-catalyst candidates suggested for approval:** AAOI and COHR are effectively in this category but already covered by the user's own explicit morning go-ahead — no separate approval pending. No new ones.
**Small-cap tech candidates:** none new.
**Time-stop flags:** none yet (both positions opened this cycle, haven't reached 1 full trading day).
**Micro-cap concurrency slot:** open (neither COHR nor AAOI is sub-$5/micro-cap).
**Sector concentration slots:** Technology: 2/2 (COHR, AAOI) — AT CAP. No third Technology position (including RSKD, CRWV) until one closes.
**Options checklist status:** No options position open. Sizing cap ~$353 (10% of balance).
**Stock position status:**
- COHR: 1 share @ $242.46, stop $240.50 (support-based, tight per user instruction).
- AAOI: 6 shares @ $56.31, stop $55.00 (support-based, tight per user instruction).

**Qualifying trades:** COHR (1 sh @ $242.46, stop $240.50) and AAOI (6 sh @ $56.31, stop $55.00) — both executed per the user's explicit morning instruction to measure CRWV/COHR/AAOI for entry with tightly-supported stops, once their structure resolved. CRWV blocked by an internal permission classifier, not re-attempted.

## Mid-cycle updates (2026-11-11, between 11am and 12pm)

- **COHR stopped out** at $240.46 (filled 16:08:20 UTC) — clean, tight exit per design, -0.82% ($242.46 → $240.46). Technology sector slot freed (now 1/2, AAOI only).
- **User suggested considering RSKD** for the freed slot (real/fresh catalyst: Q3 beat $0.07 vs $0.02 est, reported today am, verified). Checked structure: RSKD peaked ~$11.13 around 10:25am ET then rolled over into a fade/chop, now ~$10.48 with lower highs since the peak — not a clean higher-lows base. **Declined to enter** — chasing a fading move isn't the setup the tight-stop plan calls for. Watching for a fresh base/turn before reconsidering.
- **User asked to bump AAOI's stop** since it climbed. Raised resting stop from $55.00 to **$55.85** (cancelled old order, confirmed cancellation, placed and confirmed new one) — now sits just below the most recent higher-low cluster ($56.12-56.15) with AAOI trading ~$57.33.
- **Standing conditional instruction (2026-11-11, pending):** User said "if it climbs above $57.50 then try to stop at entry price. $56.30" — i.e. once AAOI prints above $57.50, cancel the resting stop and replace it with one at breakeven ($56.30, the entry price). Checked immediately: AAOI was at $57.40, **not yet triggered**. Carry this forward every cycle/check until it either triggers (then execute: cancel $55.85 stop, place new stop at $56.30, confirm both) or the user says otherwise — do not drop this silently.
- **TRIGGERED at 12pm cycle:** AAOI printed $57.51. Cancelled the $55.85 stop (confirmed cancelled), placed and confirmed a new resting stop at **$56.30** (breakeven). Position is now risk-free from here.
- **RSKD re-checked:** continued fading, now ~$10.03-10.48 well off its ~$11.13 peak. Pass confirmed correct — still watch-only, not a position.

## 12:00pm market-hours cycle (2026-11-11) — results

**Account:** $3,539.21 total ($345.06 in AAOI, $3,194.15 cash). SPX 7,632.41 / NDX 28,512.10 / VIX 17.55 — risk-on continuing, VIX still easing.

**Crypto watchlist:** all green — COIN +4.5%, MSTR +1.6%, MARA +7.2%, RIOT +2.3%, CLSK +7.5%, HUT +7.6%, BMNR +6.9%, HOOD +5.1%, CORZ +8.4%.

**Full sweep:** General=5 (REZI, RSKD, FOSL, BRAI, GEVO). Small-mid=5 (RSKD, FOSL, BGS, BRAI, GEVO). Mid-cap=1 (REZI). Large-cap=1 (IBKR). Basic Materials=3 (RETO $1.1M too illiquid, GEVO $344M extended/no new catalyst, YMAT $4.6M too illiquid). Consumer Cyclical=2 (FOSL, SEGG $4.5M too illiquid). Financial Services=1 (CANG $47M too illiquid). Real Estate=0. Consumer Defensive=1 (BGS $216M — real catalyst, beat reported 11/10pm, but modest/not pursued). Utilities=1 (NXXT $315K too illiquid). Communication Services=2 (RDCM $173M, catalyst unclear, modest move; ZDGE $35.5M too illiquid). Energy=0. Industrials=3 (**REZI**, BUUU $847M no catalyst found, BKYI $4.9M too illiquid). Technology=4 (RSKD, RNTZ $18.5M too illiquid, BRAI, BDAI $22.7M too illiquid — **sector cap 1/2, AAOI open**). Healthcare=8 (CARL $404M no catalyst, PYPD/PRME/KRMD/VIVO/CRVO/SNOA/LSTA all too illiquid or no catalyst). Options-flow: rate-limited again.

**Catalyst verdicts (new names this cycle):**
- **REZI** (Resideo Technologies, $2.95B, Industrials): real/fresh catalyst — Q3 beat $0.52 vs $0.40 est, reported 2026-11-10 pm, verified=true. Structure: genuinely clean, orderly climb with higher lows nearly the entire session (opened $19.51, now ~$22.47-22.52, +15.6%), tight ~0.2% spread. **Scored 86 — clears the bar.**
- **IBKR** (Interactive Brokers, $35.2B, Financial Services): +7.5%, no dated catalyst found via WebSearch or earnings calendar — not scored, no-catalyst/not pursued.
- FOSL: still extended (+27%), don't-chase applies, not re-scored.
- RSKD: faded further, confirmed pass.
- GEVO, BGS, RDCM, BUUU, CARL: no fresh catalyst found or too illiquid, not pursued.

**REZI — BLOCKED:** Buy order (15 shares, limit $22.60) was denied by the same on-session permission classifier that blocked CRWV this morning, this time with reason "[Real-World Transactions]." This is now the **second autonomous equity buy blocked this session** (CRWV this morning, REZI now) — notably, the AAOI/COHR buys and all stop-order management (placing, cancelling, raising stops) went through fine both times. The pattern looks like fresh new-position BUY orders specifically are being inconsistently flagged. Not retried, per the denial's own instructions. **Flagging this to the user directly — REZI (clean catalyst, clean structure, scored 86) could not be opened; if you want it, you'd need to place it yourself.**

**Confidence scores:** REZI = 86 (not executed — blocked). No other new scores this cycle.
**No-catalyst candidates suggested for approval:** IBKR noted but not formally surfaced for approval (real move but no catalyst found at all, no compelling technical story beyond the price move itself).
**Small-cap tech candidates:** none new.
**Time-stop flags:** none (AAOI not yet 1 full trading day old).
**Micro-cap concurrency slot:** open.
**Sector concentration slots:** Technology 1/2 (AAOI). Industrials would be 1/2 if REZI had filled — currently 0/2 since the order was blocked.
**Options checklist status:** no options position; sizing cap ~$354.
**Stock position status:** AAOI — 6 sh @ $56.31, stop now $56.30 (breakeven, raised twice this morning per user instruction), trading ~$57.51-57.52 (+2.1%).

**Qualifying trade:** REZI (86, real catalyst, clean structure) — **blocked, not executed.** No other qualifying trade this cycle.
