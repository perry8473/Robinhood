# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built fresh by the after-hours routine on 2026-10-14 (Wednesday close), fired
~6:06pm ET; **trued up by the 8am overnight pass on 2026-10-15,** fired ~7:53am ET. TSM and SCHW
have now reported (both beat-but-down pre-market); BNY and MRSH surfaced as new beat-and-up
reactions but fail the options DTE window. See updated sections below.

**Step 0 (8am true-up) — held position defense check:** `get_equity_positions` confirms BLK and AZZ
both still held, unchanged quantities. `get_equity_orders(state=confirmed)` returned **zero resting
orders** — AZZ has no stop (expired at Wednesday's close, as already flagged) and BLK never had one
(fractional, unsupported per user instruction). With no resting stop to breach, Step 0's defense
trigger does not apply to either position — **no action taken.** AZZ bid $125.00/ask $140.25
(wide/thin pre-market spread) — well above the $130 floor regardless; BLK bid $1,074.30/ask
$1,087.00, normal range. AZZ still needs a fresh stop placed at the 9:40am cycle.

**⚠️ EXPLICIT USER PRIORITY WATCH — UPDATE (8am true-up, 2026-10-15): both have now reported.**
- **TSM:** Q3 EPS **$4.60 actual vs $4.45 est. — beat.** Reaction: close $430.00 → pre-market
  $421.99 (**-1.9%**). **Beat but down** — the same pattern that has now repeated all week
  (GS/UNH, MS/BAC/STT/FAST, EQBK/HOMB). Options (11/06 exp., 22 DTE — passes window): $420C mark
  $22.03 → **~$2,203/contract, fails the ~$294 sizing cap** by a wide margin; OI 31/vol 11 (thin).
- **SCHW:** Q3 EPS **$1.69 actual vs $1.66 est. — beat.** Reaction: close $96.80 → pre-market
  $93.92 (**-3.0%**). Also **beat but down.** Options (11/06 exp., 22 DTE): $94C mark $4.90 →
  **~$490/contract, fails the ~$294 cap**; OI 5/vol 4 (very thin).
- **Read:** both are tracking this week's dominant pattern almost exactly — a clean beat with a
  negative pre-market reaction, and both options chains are structurally unworkable (premium too
  large for the sizing cap on top of the direction being wrong anyway). Leaning PASS going into
  the 9:40am cycle, but per your instruction this still gets checked live and fast at the open
  before any final call — pre-market thinness can reverse by 9:30.

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

## Ranked candidates (trued up 8am, 2026-10-15)

### 1. BNY (BNY Mellon) and MRSH — NEW, beat-and-up (the week's exception, not the rule)
- **BNY:** Q3 EPS $2.37 vs $2.26 est. — beat. Reaction: close $137.64 → pre-market $140.00
  (**+1.7%**). Beat AND up — one of the few this week.
- **MRSH** (Marsh McLennan): Q3 EPS $2.03 vs $1.97 est. — beat. Reaction: close $178.40 →
  pre-market $182.79 (**+2.5%**). Also beat and up.
- **Disqualifier — options structurally unavailable on both:** nearest expiration is 2026-10-16
  (1 DTE, fails the 7-30 DTE floor), next is 2026-11-20 (36 DTE, fails the ceiling) — **no listed
  contract falls in the 7-30 DTE window for either name.** Any trade here would have to be
  stock-only.
- **Freshness confidence:** High (confirmed actuals + live pre-market reaction), but pre-market
  volume/spread quality not yet verified — needs the 9:40am cycle's live Step 6 check.
- **Verdict:** Promoted to top of the list for the 9:40am cycle to check first — genuine
  beat-and-up reactions are rare this week, worth a close look despite no options path.

### 2. TSM / SCHW — user priority watch, now reported — see update above (leaning PASS)
Both beat (TSM $4.60 vs $4.45; SCHW $1.69 vs $1.66) but both reacted down pre-market (-1.9% and
-3.0%), and both options chains fail the ~$294 sizing cap badly. See the priority-watch section
above for full detail. Still gets a live check at 9:40am per your instruction, but this is now
tracking as a PASS on current information.

### 3. Bank/financials cluster — remaining names, mostly beat-but-down or inline
- **PNC:** beat ($5.09 vs $4.91), pre-market $212.50 vs $215.80 close (**-1.5%**) — beat but down,
  same pattern as TSM/SCHW.
- **USB:** beat ($1.34 vs $1.32), pre-market print stale/flat (~$56.26); bid dropped to $51.31 on
  a wide/thin pre-market spread — not reliable enough to call a direction yet.
- **FHN:** inline ($0.53 vs $0.53 est.) — no edge expected; bid also showing a wide/thin
  pre-market spread ($20.50 bid vs $22.60 last).
- **MAN:** inline ($1.01 vs $1.01) — no edge expected.
- **CMC, ERIC:** both beat (CMC $2.09 vs $1.96; ERIC $0.18 vs $0.14) — smaller/less liquid,
  pre-market quotes not pulled this build, not pursued.
- **Verdict:** Nothing here clears the bar yet — PNC is following this week's beat-but-down
  pattern; USB/FHN's quotes are too thin/stale to trust pre-market. Not carried as live candidates.

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

## Today's earnings (2026-10-15) — actuals as of 8am true-up

| Ticker | Est. EPS | Actual EPS | Pre-market reaction | Notable? |
|---|---|---|---|---|
| **TSM** | $4.45 | $4.60 — beat | -1.9% | Beat but down — see candidate #2 |
| **SCHW** | $1.66 | $1.69 — beat | -3.0% | Beat but down — see candidate #2 |
| **BNY** | $2.26 | $2.37 — beat | **+1.7%** | **Yes — beat and up, see candidate #1** |
| **MRSH** | $1.97 | $2.03 — beat | **+2.5%** | **Yes — beat and up, see candidate #1** |
| **PNC** | $4.91 | $5.09 — beat | -1.5% | Beat but down, not pursued |
| **USB** | $1.32 | $1.34 — beat | ~flat (stale/thin quote) | No — unreliable pre-market print |
| **FHN** | $0.53 | $0.53 — inline | ~flat (wide/thin spread) | No |
| **MAN** | $1.01 | $1.01 — inline | Not pulled | No — inline, no edge expected |
| **CMC** | $1.96 | $2.09 — beat | Not pulled | No — not pursued |
| **ERIC** | $0.14 | $0.18 — beat | Not pulled | No — not pursued |
| PLD, AA, JBHT, IBKR, WIT, + small regional banks | various | not yet reported (am-timing ones may have posted after this check) | — | Pending/small-cap, not pursued |

## Scheduled macro events
No confirmed major scheduled macro print found for today as of this true-up. SPX 7,718.94 (last
available print, dated to yesterday's 4:36pm close — no fresh overnight futures read via this
session's tools), VIX 17.39 — essentially flat vs. yesterday afternoon's 17.21. No overnight
panic or relief signal; today's tone is earnings-driven, not macro-driven, on current information.

## Small-cap-tech shortlist
Checked at this build: Technology-sector pre-market scan (scan_id 4ab9bad9) returned **zero
matches** again. Nothing to add to the shortlist.

## Optoelectronic standing watch — AAOI / COHR (user standing interest)
- **AAOI:** close $86.22 → pre-market $82.20 (**-4.7%**), bid $82.01/ask $82.40. Fading —
  breaking below its recent range. No catalyst found (no equity-news tool available this
  session, as in prior builds) — treat as an unexplained pre-market pullback, not a signal.
- **COHR:** close $263.32 → pre-market $252.50 (**-4.1%**), bid $251.85/ask $253.00. Also fading,
  same caveat — no catalyst confirmed.
- Standing watch only, per your instruction — not scored as a trade candidate. Both worth a
  second look at the open to see if this is a real gap-down or just thin pre-market noise.

## Sources used in this build (8am true-up, 2026-10-15)
- `get_equity_positions` / `get_equity_orders(state=confirmed)` (BLK, AZZ) — Step 0 defense
  check, zero resting orders found, no action needed (see Step 0 note above).
- `get_equity_quotes` (BLK, AZZ, AAOI, COHR, TSM, SCHW, USB, PNC, BNY, FHN, MRSH, SPY) — all
  pre-market figures above vs. official prior-session close.
- `get_earnings_calendar` (today, 1-day window) — confirmed actuals for TSM/SCHW/USB/PNC/BNY/
  FHN/MRSH/MAN/CMC/ERIC and pending names.
- `get_index_quotes` (SPX, NDX, VIX) — overnight tone read.
- `run_scan` (Technology sector, scan_id 4ab9bad9) — zero matches.
- `get_option_chains` / `get_option_instruments` / `get_option_quotes` (TSM, SCHW, BNY, MRSH) —
  BNY/MRSH fail the 7-30 DTE window entirely; TSM/SCHW have a valid 22-DTE (11/06) contract but
  both premiums (~$2,203 and ~$490/contract) fail the ~$294 sizing cap.
- No `get_equity_news` tool available this session (confirmed again) — overnight news/ratings
  changes could not be independently checked; price action is the only signal used above.

## Sources used in the 6pm build (2026-10-14, carried forward)
- `get_equity_positions` / `get_equity_orders` (BLK, AZZ) — confirmed both still held, AZZ's $130
  stop expired untriggered at the close, BLK remains without a stop per user instruction.
- `get_equity_quotes` (BLK, AZZ, EQBK, EDUC, HOMB) — all after-hours figures above vs. official
  close.
- `get_earnings_calendar` (today -1 day window, tomorrow +1 day window, unfiltered) — all figures
  in the earnings tables above.
- Today's 11am/12pm/3pm market-hours cycles (this session's own chat record) — broad risk-off
  tone, crypto-watchlist declines, options-flow scan showing sector-wide AI/crypto weakness.
