# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built fresh by the after-hours routine on 2026-10-14 (Wednesday close), fired
~6:06pm ET. Asian/European overnight-session news has **not** been checked at this hour — that is
the job of the ~8am overnight true-up routine before tomorrow's (2026-10-15, Thursday) open.

**⚠️ EXPLICIT USER PRIORITY WATCH (flagged ~6:56pm ET, 2026-10-14): SCHW and TSM — be ready to
move fast at the open if either sets up cleanly.** Both report before tomorrow's open and neither
has reported yet. As of ~6:56pm ET:
- **TSM:** close $445.12 → AH $423.80 (**-4.8%**). This is **pre-earnings drift**, not a reaction
  (hasn't reported) — drifting down with today's broader chip-sector weakness (STM/MCHP/UMC/GFS
  all soft). Watch whether this reverses, extends, or the actual print changes the picture entirely.
- **SCHW:** close $95.94 → AH $96.64 (**+0.7%**), mild, also pre-earnings.
- Both must still clear the full Step 5 (catalyst)/Step 6 (price structure) gate live once actuals
  post — this flag means "check first and fast," not "pre-approved." Carry forward into the 8am
  true-up and 9:40am opening-bell cycle as top-priority checks the moment each reports.

**Step 0 — held position defense check:** `get_equity_positions` confirms **BLK and AZZ are both
still held.** Neither needed off-hours defense this evening:
- **AZZ's $130 resting stop expired untriggered at the close** (GFD order, `last_transaction_at`
  20:40 UTC / 4:40pm ET, state=cancelled, cumulative_quantity=0) — price never touched $130 during
  the session (intraday low ~$134.99). This is normal GFD expiration, not a loss event, but **AZZ
  now has no resting stop at all** and needs a fresh one placed first thing tomorrow (9:40am
  cycle) at $130 or higher per the user's last instruction, before any other Step 2 work.
- **BLK has no stop** — per explicit user instruction today ("ok to let it go unsupported for
  now"), left as-is. Current AH price ($1,071.00) is well within normal range, no emergency.

**Account status:** Two open stock positions, both from today's user-directed entries:
- **BLK** — 0.269420 sh @ $1,092.53 avg cost. AH last $1,071.00 (bid $1,067.95/ask $1,075.00,
  wide/thin AH spread) — **-1.97%** unrealized. No stop (fractional position, structurally cannot
  carry a stop_market/stop_limit trigger — confirmed twice today; left unsupported per user
  instruction).
- **AZZ** — 2.1025 sh @ $140.00 avg cost. AH last $137.66 (bid $134.98/ask $145.38, wide/thin AH
  spread) — **-1.6%** unrealized. Stop expired at the close (see Step 0) — needs replacement
  tomorrow morning.
- Cash/buying power: $2,354.77.

**Tone at this build:** A genuinely broad risk-off session — not isolated to our names. SPX fell
from 7,811 (Tuesday close) to ~7,700 intraday (-1.4%), VIX rose from 15.37 this morning to 17.21 by
3pm. AI/crypto/quantum-adjacent names were hit hardest across the board: CRWV -16%, NBIS -11%,
ORCL -9.4%, DELL -11.7%, IREN/WULF/CIFR/RGTI/QBTS all -9% to -16%, and the crypto-stock watchlist
(COIN/MSTR/MARA/RIOT/CLSK/HUT/BMNR/HOOD/CORZ) all down 5-13% with no confirmed catalyst found via
WebSearch. BLK and AZZ held up comparatively well given this backdrop — both down under 2%
unrealized, well inside normal volatility, nowhere near either position's risk floor.

---

## Open positions (carried from today's user-directed entries)
**BLK** — 0.269420 sh @ $1,092.53, AH $1,071.00 (-1.97%), no stop (fractional, unsupported per
user instruction — monitor manually each cycle).
**AZZ** — 2.1025 sh @ $140.00, AH $137.66 (-1.6%), stop expired at close — **place a fresh stop
first thing at the 9:40am cycle** (last level was $130; confirm with user whether to hold that
floor or adjust given the move since).

---

## Ranked candidates (new, for tomorrow's open)

### 1. TSM (Taiwan Semiconductor) — scheduled earnings before tomorrow's open, high-profile
- **Catalyst:** Q3 2026 earnings due before the open (est. EPS $4.45) — a major semiconductor
  bellwether reporting one day after ASML's big beat (+19.3%) this morning, in a session where
  chip-adjacent names (STM, MCHP, UMC, GFS) were still mixed/weak amid the broader tech selloff.
- **Freshness confidence:** High by definition (scheduled, not yet reported) — direction and
  magnitude unknown until the print; flagging for the 8am true-up and 9:40am cycle to check
  immediately once actuals post.
- **Disqualifiers:** None yet — entirely contingent on the actual results and reaction.
- **Options read:** Not checked — no reaction to evaluate yet.
- **Verdict:** Top story to watch tomorrow morning given today's chip-sector volatility and
  ASML's strong print as a sector read-through.

### 2. Bank/financials cluster — scheduled earnings before tomorrow's open
- **SCHW** (est. $1.66), **USB** (est. $1.32), **PNC** (est. $4.91), **BNY** (est. $2.26),
  **FHN** (est. $0.53), **MRSH** (est. $1.97) all report before the open — a direct continuation
  of this week's bank-earnings wave (GS/JPM/WFC/C/UNH Tuesday; BLK/MS/BAC/STT Wednesday).
- Also reporting: **IBKR** (pm, est. $0.67), **PLD** (am, est. $1.58, large industrial REIT),
  **ERIC** (am, est. $0.14), **AA**/Alcoa (pm, est. $1.52), **JBHT**/trucking bellwether
  (pm, est. $1.81), **MAN**/staffing bellwether (am, est. $1.01), **CMC** (am, est. $1.96), plus
  smaller regional banks (INDB, SFNC, WAFD, BSVN, WABC, CNS, UBFO) and **WIT** (am, est. $0.04).
- **Verdict:** Not a candidate yet — this week's pattern (GS/UNH both failed Step 6 structure
  despite big beats; MS/BAC/STT/FAST all beat-or-missed with reactions fighting the catalyst
  direction) argues for treating any gap here with full Step 6 scrutiny rather than chasing the
  headline beat. Flagging for the 9:40am cycle to check once actuals post.
- **Options read:** Not checked — no catalyst to evaluate against yet.

### 3. Today's after-close earnings (EQBK, EDUC, HOMB) — no edge
- **EQBK:** Beat ($1.40 vs $1.30 est.) but AH -0.8% ($46.20 vs $46.83 close) — beat-but-down,
  small regional bank.
- **HOMB:** Beat ($0.65 vs $0.63 est.) but AH -0.4% ($28.14 vs $28.36 close) — same pattern,
  small regional bank.
- **EDUC:** Reported a loss (-$0.19, no estimate on file), AH -1.9% ($1.28 vs $1.305 close) —
  penny stock, no real catalyst edge.
- **Verdict:** None of these show a confirmed, tradeable reaction — all too small and/or the
  price action doesn't reward the print. Not carried as live candidates.

### 4. Crypto-stock watchlist — broad decline, no catalyst, not actionable
- COIN -5%, MSTR -6%, MARA -10%, RIOT -10%, CLSK -11%, HUT -10%, BMNR -5%, HOOD -9%, CORZ -13%
  (approximate 3pm-cycle figures). WebSearch found no confirmed same-day crypto catalyst.
- **Verdict:** Broad-basket decline, no catalyst — not actionable in either direction tonight.

---

## Today's after-close earnings reactions (2026-10-14, pm)

| Ticker | Est. EPS | Actual EPS | AH reaction | Notable? |
|---|---|---|---|---|
| EQBK | $1.30 | $1.40 — beat | -0.8% | No — beat but down |
| HOMB | $0.63 | $0.65 — beat | -0.4% | No — beat but down |
| EDUC | — (no estimate) | -$0.19 (loss) | -1.9% | No — too small, no edge |
| CMTL, PNFP, VSEE, SNV | — | Not yet reported | — | Pending, small-cap, not pursued |

## Tomorrow's scheduled earnings (2026-10-15) — before the open unless noted

| Ticker | Timing | Est. EPS | Notable? |
|---|---|---|---|
| **TSM** | am | $4.45 | Yes — see candidate #1, major chip bellwether |
| **SCHW** | am | $1.66 | Yes — bank cluster, see candidate #2 |
| **USB** | am | $1.32 | Yes — same cluster |
| **PNC** | am | $4.91 | Yes — same cluster |
| **BNY** | am | $2.26 | Yes — same cluster |
| **FHN** | am | $0.53 | Yes — same cluster |
| **MRSH** | am | $1.97 | Yes — same cluster |
| **PLD** | am | $1.58 | Moderate — large industrial REIT |
| **ERIC** | am | $0.14 | Moderate — telecom equipment |
| **MAN** | am | $1.01 | Moderate — staffing bellwether |
| **CMC** | am | $1.96 | Moderate — materials |
| **AA (Alcoa)** | pm | $1.52 | Moderate — materials |
| **JBHT** | pm | $1.81 | Moderate — trucking bellwether |
| **IBKR** | pm | $0.67 | Moderate — brokerage |
| INDB, SFNC, WAFD, BSVN, WABC, CNS, UBFO, WIT, LOOP | am/pm | various | Small-caps, not pursued |

## Scheduled macro events
No major scheduled macro print identified for tomorrow as of this build (not independently
re-verified — check at the 8am true-up). Today's broad risk-off (VIX 15.37→17.21, SPX -1.4%) had
no single confirmed catalyst found via WebSearch — treat as a general risk-off backdrop heading
into tomorrow's bank/chip earnings wave, not a resolved, one-off event.

## Small-cap-tech shortlist
Not checked at this build (the Technology-sector pre-market scan is the 8am true-up's job). Note
for continuity: the 3pm cycle's Technology sector sweep returned **zero matches** today.

## Sources used in this build (6pm, 2026-10-14)
- `get_equity_positions` / `get_equity_orders` (BLK, AZZ) — confirmed both still held, AZZ's $130
  stop expired untriggered at the close, BLK remains without a stop per user instruction.
- `get_equity_quotes` (BLK, AZZ, EQBK, EDUC, HOMB) — all after-hours figures above vs. official
  close.
- `get_earnings_calendar` (today -1 day window, tomorrow +1 day window, unfiltered) — all figures
  in the earnings tables above.
- Today's 11am/12pm/3pm market-hours cycles (this session's own chat record) — broad risk-off
  tone, crypto-watchlist declines, options-flow scan showing sector-wide AI/crypto weakness.
