# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built fresh by the after-hours routine on 2026-10-15 (Thursday close), fired
~6:05pm ET for today (2026-10-16, Friday); **trued up by the 8am overnight pass**, fired ~7:53am
ET. AA remains top candidate, now extending further pre-market. RF and MTB join as new
beat-and-up names from today's bank wave; TFC/CFG/TRV are beat/miss-but-down, continuing the
week's dominant pattern (TRV especially — a ~25% EPS beat reacting -4% pre-market).

**Step 0 (8am true-up) — held position defense check:** Only position is still **MRSH's
fractional remainder** (0.237949 sh, avg cost $189.83). `get_equity_orders(state=confirmed)`
confirms zero resting orders (no stop possible on a fractional position). Pre-market price
$187.36 (bid $186.60) — actually recovered slightly overnight, nowhere near a floor even if one
existed. **No action possible or needed** — same structural gap as every check since yesterday
afternoon; resolves automatically once the regular session reopens and the fraction becomes
sellable again. BLK and AZZ were fully closed yesterday (BLK +$7.49; AZZ -$13.80; WETO -$2.37
scratch; AMOD +18% via a laddered stop) — none carry forward.

**Account status:** One position — **MRSH**, 0.237949 sh @ $189.83 avg cost, ~$186.50 AH
(-1.75%). Cash ~$2,604 (post BLK/AZZ/WETO closes and the 1-share MRSH sale). No options positions.

**Tone at this build (8am):** Quiet, stable. SPX 7,744.06, NDX 29,935.59, VIX **16.14** —
continuing to ease overnight (16.46 → 16.14), no overnight macro event found. Calm backdrop
heading into today's bank-earnings wave.

---

## Ranked candidates (trued up 8am, 2026-10-16)

### 1. AA (Alcoa) — STRENGTHENED — large beat, reaction extending pre-market
- **Catalyst:** Q3 2026 earnings, after Thursday's close. EPS **$1.82 actual vs $1.52 est. — a
  ~20% beat**. Source: `get_earnings_calendar`.
- **Direction/magnitude:** Bullish, strengthening. AH close (Thu) $40.75 → pre-market now
  **$41.18-41.35** (bid/ask), i.e. **+1.9% pre-market on top of** Thursday's +1.7% AH move —
  continuing to extend, not fading. Still a clean "beat and up."
- **Freshness confidence:** High — reaction has now held/extended through two full sessions of
  quotes (AH Thursday → pre-market Friday) without reversing.
- **Disqualifiers:** None found. Still needs live spread/volume confirmation at the open.
- **Options read (PRELIMINARY, not a live quote, refreshed 8am):** $41C exp. 2026-11-06 (22 DTE
  — **passes**). Premium unchanged at $1.78 close, OI 64. **Still passes the ~$295 sizing cap**
  (~$178/contract). Listed chain: **pass**. Structural read unchanged: PASS on all three
  checkable items.
- **Verdict:** Still the top candidate — the only name this week with a genuinely confirmed,
  extending beat-and-up reaction AND a structurally viable options path. Check first at 9:40am.

### 2. RF (Regions Financial) and MTB (M&T Bank) — NEW, beat-and-up from today's bank wave
- **RF:** Q3 EPS **$0.73 vs $0.66 est. — beat.** Reaction: close $27.31 → pre-market $27.70
  (**+1.4%**). Beat and up.
- **MTB:** Q3 EPS **$5.08 vs $4.94 est. — beat.** Reaction: close $218.65 → pre-market $220.00
  (**+0.6%**). Mild beat and up.
- **Freshness confidence:** High (confirmed actuals + live pre-market reaction), but — per the
  standing lesson from BNY/MRSH this week — a pre-market beat-and-up reaction has repeatedly
  faded hard once the regular session opens. Needs live confirmation, not assumed to hold.
- **Options read:** Not checked yet — second-tier candidates behind AA; check live at 9:40am if
  either still looks clean at the open.
- **Verdict:** Flagged for the 9:40am cycle to check early, with the explicit caveat that this
  week's beat-and-up names have tended to fade by mid-morning.

### 3. CFG, TFC, TRV — beat/miss-but-down, continuing the week's dominant pattern
- **TRV** (Travelers): Q3 EPS **$9.18 vs $7.35 est. — a massive ~25% beat** — yet pre-market
  **-4.1%** ($368.00 vs $383.89 close). The starkest "beat but down" of the entire week.
- **CFG:** beat ($1.41 vs $1.38), pre-market **-2.1%** ($62.11 vs $63.43).
- **TFC:** missed ($1.16 vs $1.20), pre-market **-2.0%** ($45.61 vs $46.57) — miss and down,
  consistent with the miss.
- **LADR, WBS, CMA, CBAT, CLPS:** not yet reported or unverified as of this build.
- **Verdict:** Not candidates — TRV in particular is a strong reminder that even an exceptional
  beat does not predict direction this week. Check live at 9:40am only if price action reverses
  materially from pre-market.

### 4. IBKR, INDB — smaller beat-and-up names, weaker setups (from Thursday's close)
- **IBKR:** inline EPS ($0.67 vs $0.67 est.), AH +1.7% ($85.61 vs $84.14) — mild positive drift,
  not a clean beat-driven move. Options: $85C exp. 2026-11-06, close $3.33/AH mark $4.45 →
  **~$445/contract, FAILS the ~$295 sizing cap**.
- **INDB:** beat ($1.90 vs $1.84), AH +1.4% ($77.08 vs $76.04) — small regional bank, thin AH
  liquidity (bid/ask $75.07/$81.50, very wide). Options not checked — too small/illiquid a move
  to prioritize research budget on.
- **Verdict:** Both weaker than AA — smaller reactions, one fails sizing, the other too thin to
  trust pre-open. Not carried as top candidates, flagging for completeness only.

### 5. CNS, JBHT, LOOP — mixed/noisy, not pursued
- **CNS:** missed ($0.89 vs $0.90) but AH **+3.9%** — counterintuitive reaction on a very
  wide/thin AH spread (bid $63.11/ask $74.00), likely unreliable thin-trade noise rather than a
  real signal. Re-check at the open.
- **JBHT:** beat ($1.82 vs $1.81, small) but AH -0.5% — another "beat but down," consistent with
  the week's theme, not a candidate.
- **LOOP:** missed (-$0.06 vs -$0.05 est.), AH move noisy on a sub-$1 penny stock — too
  illiquid/small to pursue.

---

## Optoelectronic standing watch — AAOI / COHR (user standing interest, 8am check)
- **AAOI:** close $83.73 → pre-market $83.76-83.80 — essentially flat, **holding its recent
  range**. No fresh catalyst found (no equity-news tool available this session).
- **COHR:** close $250.60 → pre-market $248.00-248.51 (**-0.8%**) — mild **fading**, no fresh
  catalyst found.
- Standing watch only, not a trade signal. Neither shows a scoreable move this morning.

---

## Today's after-close earnings reactions (2026-10-15, pm)

| Ticker | Est. EPS | Actual EPS | AH reaction | Notable? |
|---|---|---|---|---|
| **AA** | $1.52 | $1.82 — big beat | **+1.7%** | **Yes — candidate #1** |
| IBKR | $0.67 | $0.67 — inline | +1.7% | Minor — candidate #3, options fail cap |
| INDB | $1.84 | $1.90 — beat | +1.4% | Minor — candidate #3, thin AH liquidity |
| JBHT | $1.81 | $1.82 — beat | -0.5% | No — beat but down, week's pattern |
| CNS | $0.90 | $0.89 — miss | +3.9% (thin) | No — likely noise, wide spread |
| SFNC | $0.53 | $0.54 — beat | Not checked | No — small regional bank |
| LOOP | -$0.05 | -$0.06 — miss | Noisy | No — penny stock |
| WAFD | $0.84 | pending | +1.9% (pre-report drift) | Pending — hasn't reported yet as of this build |
| UBFO | — (unverified) | — | Not checked | No — unverified small-cap |

## Today's earnings (2026-10-16) — actuals as of 8am true-up, before the open unless noted

| Ticker | Est. EPS | Actual EPS | Pre-market reaction | Notable? |
|---|---|---|---|---|
| **TRV** | $7.35 | $9.18 — huge beat | **-4.1%** | Beat but down hard — see #3 |
| **CFG** | $1.38 | $1.41 — beat | **-2.1%** | Beat but down — see #3 |
| **TFC** | $1.20 | $1.16 — miss | **-2.0%** | Miss and down — see #3 |
| **RF** | $0.66 | $0.73 — beat | **+1.4%** | Beat and up — see candidate #2 |
| **MTB** | $4.94 | $5.08 — beat | **+0.6%** | Beat and up — see candidate #2 |
| LADR, WBS, CMA | $0.21 / $1.63 / $1.45 | not yet reported | — | Pending, check at 9:40am |
| CBAT, CLPS | — | unverified/small | — | Too small, not pursued |

## Scheduled macro events
No major scheduled macro print identified for today as of this true-up. VIX 16.46 → 16.14
overnight — continuing to ease, no overnight shock. Calm backdrop into today's bank wave.

## Small-cap-tech shortlist
Checked at this build: Technology-sector pre-market scan (scan_id 4ab9bad9) returned **zero
matches**. Nothing to add. Note for continuity: yesterday's BBCI/AMOD/WETO/XLAB — AMOD and WETO
were both traded yesterday on explicit user instruction (AMOD stopped out +18%, WETO closed
flat) and should not be chased again without a fresh setup.

## Sources used in this build (8am true-up, 2026-10-16)
- `get_equity_positions` / `get_equity_orders(state=confirmed)` (MRSH) — Step 0 check, zero
  resting orders, no action possible or needed on the fractional remainder.
- `get_equity_quotes` (MRSH, AAOI, COHR, AA, IBKR, TFC, CFG, RF, MTB, TRV, WBS, CMA, SPY) — all
  pre-market figures above vs. official prior-session close.
- `get_index_quotes` (SPX, NDX, VIX) — overnight tone read.
- `get_earnings_calendar` (today, 1-day window) — confirmed actuals for MTB/RF/CFG/TFC/TRV and
  pending names.
- `run_scan` (Technology sector, scan_id 4ab9bad9) — zero matches.
- `get_option_quotes` (AA) — refreshed, unchanged from the 6pm build, still passes all checks.
- No `get_equity_news` tool available this session (confirmed again) — AAOI/COHR catalyst check
  and all "no catalyst found" verdicts rely on price action only.

## Sources used in the 6pm build (2026-10-15, carried forward)
- `get_equity_positions` / `get_equity_orders` (MRSH) — confirmed the 1-share AH sale filled at
  $185.00, fractional remainder has no stop and is structurally untradable off-hours.
- `get_equity_tradability` (MRSH) — confirmed no extended_hours or all_day fractional support.
- `get_equity_quotes` (MRSH, AA, IBKR, JBHT, INDB, CNS, LOOP, WAFD, SPY) — all AH figures above
  vs. official close.
- `get_earnings_calendar` (today, tomorrow, 1-day windows each) — all figures in the earnings
  tables above.
- `get_option_chains` / `get_option_instruments` / `get_option_quotes` (AA, IBKR) — AA passes all
  preliminary structural checks (DTE, cap, listed chain); IBKR fails the sizing cap.
- Thursday's 11am/12pm/3pm market-hours cycles (this session's own chat record) — AMOD/WETO/AZZ/
  BLK trade history, MRSH continuation thesis, broad sector-sweep results.
