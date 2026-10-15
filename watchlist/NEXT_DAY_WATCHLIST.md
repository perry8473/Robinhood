# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built fresh by the after-hours routine on 2026-10-15 (Thursday close), fired
~6:05pm ET for tomorrow (2026-10-16, Friday). Asian/European overnight-session news has **not**
been checked at this hour — that is the job of the ~8am overnight true-up routine before
tomorrow's open.

**Step 0 — held position defense check:** Only position now is **MRSH's fractional remainder**
(0.237949 sh, avg cost $189.83) — the whole-share portion (1 sh) was sold today, first via a
regular-hours stop raised to $185 (expired untriggered at the close) and then via an after-hours
limit sell that filled at **$185.00**. The fractional remainder has **no resting stop** (can't
carry one) and **cannot be sold in extended_hours or the 24-Hour Market either** — confirmed via
`get_equity_tradability` (`extended_hours_fractional_tradability: false`,
`all_day_tradability: untradable`). Current AH price ~$186.49-186.54, down modestly from the
$189.83 cost but not an emergency — and no action is possible regardless until the regular
session reopens. BLK and AZZ were both fully closed earlier today (BLK +$7.49 at the 3pm cycle;
AZZ -$13.80 and WETO -$2.37 scratch, both per explicit user instruction) — neither carries
forward.

**Account status:** One position — **MRSH**, 0.237949 sh @ $189.83 avg cost, ~$186.50 AH
(-1.75%). Cash ~$2,604 (post BLK/AZZ/WETO closes and the 1-share MRSH sale). No options positions.

**Tone at this build:** Quiet, stable close. SPX 7,744.06 (flat vs. today's levels), NDX
29,935.59, VIX 16.46 (continuing to ease all week from Monday's highs). No broad risk-off or
risk-on theme — today was an earnings-digestion day, not a macro-driven one.

---

## Ranked candidates (new, for tomorrow's open)

### 1. AA (Alcoa) — large beat, clean positive AH reaction
- **Catalyst:** Q3 2026 earnings, after today's close (~4:05pm ET). EPS **$1.82 actual vs $1.52
  est. — a ~20% beat**, one of the largest beats of the week. Source: `get_earnings_calendar`.
- **Direction/magnitude:** Bullish. AH: close $40.08 → $40.75 (**+1.7%**). Modest relative to the
  size of the beat, but confirmed positive — beat AND up, breaking this week's dominant
  "beat-but-down" pattern.
- **Freshness confidence:** High — report is only ~2 hours old at this build, reaction still
  forming in thin AH trade.
- **Disqualifiers:** None identified yet. AH volume/spread not yet verified at scale — re-check
  live at the open.
- **Options read (PRELIMINARY, not a live quote):** $41C exp. 2026-11-06 (22 DTE — **passes**
  7-30 window). Last close premium $1.68, AH mark $1.78 → **~$178/contract, passes the ~$295
  sizing cap**. OI 63 (moderate). Listed chain: **pass**. Structural read: PASS on all three
  checkable items — needs live spread/volume/catalyst confirmation at the open per the 9:40am
  cycle's own Step 6.
- **Verdict:** Top candidate for tomorrow — the cleanest "beat and up" reaction of the day, with
  a structurally viable options path unlike most of this week's candidates.

### 2. Bank earnings wave continues — TFC, CFG, RF, MTB, TRV, LADR, WBS, CMA (tomorrow, before open)
- Direct continuation of this week's bank-earnings parade (GS/JPM/WFC/C Tue; BLK/MS/BAC/STT Wed;
  SCHW/USB/PNC/BNY/FHN/MRSH Thu). Truist (TFC, est. $1.20), Citizens (CFG, est. $1.38), Regions
  (RF, est. $0.66), M&T (MTB, est. $4.93), Travelers (TRV, est. $7.32), Ladder Capital (LADR, est.
  $0.21), Webster (WBS, est. $1.63), Comerica (CMA, est. $1.45) all report AM.
- **Verdict:** Not a candidate yet — this week's overwhelming pattern has been "beat but down"
  across nearly every bank reporting (GS, UNH, MS, BAC, STT, FAST, TSM, SCHW, PNC all beat with
  negative-to-flat reactions). BNY and MRSH were the rare exceptions, and MRSH's own reaction
  faded hard intraday today after the open. Treat tomorrow's wave with the same skepticism —
  check live at 9:40am, don't assume a beat moves these names up.
- **Options read:** Not checked — no reaction to evaluate yet.

### 3. IBKR, INDB — smaller beat-and-up names, weaker setups
- **IBKR:** inline EPS ($0.67 vs $0.67 est.), AH +1.7% ($85.61 vs $84.14) — mild positive drift,
  not a clean beat-driven move. Options: $85C exp. 2026-11-06, close $3.33/AH mark $4.45 →
  **~$445/contract, FAILS the ~$295 sizing cap**.
- **INDB:** beat ($1.90 vs $1.84), AH +1.4% ($77.08 vs $76.04) — small regional bank, thin AH
  liquidity (bid/ask $75.07/$81.50, very wide). Options not checked — too small/illiquid a move
  to prioritize research budget on.
- **Verdict:** Both weaker than AA — smaller reactions, one fails sizing, the other too thin to
  trust pre-open. Not carried as top candidates, flagging for completeness only.

### 4. CNS, JBHT, LOOP — mixed/noisy, not pursued
- **CNS:** missed ($0.89 vs $0.90) but AH **+3.9%** — counterintuitive reaction on a very
  wide/thin AH spread (bid $63.11/ask $74.00), likely unreliable thin-trade noise rather than a
  real signal. Re-check at the open.
- **JBHT:** beat ($1.82 vs $1.81, small) but AH -0.5% — another "beat but down," consistent with
  the week's theme, not a candidate.
- **LOOP:** missed (-$0.06 vs -$0.05 est.), AH move noisy on a sub-$1 penny stock — too
  illiquid/small to pursue.

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

## Tomorrow's scheduled earnings (2026-10-16) — before the open unless noted

| Ticker | Timing | Est. EPS | Notable? |
|---|---|---|---|
| **TFC** (Truist) | am | $1.20 | Yes — bank wave, see candidate #2 |
| **CFG** (Citizens) | am | $1.38 | Yes — same cluster |
| **RF** (Regions) | am | $0.66 | Yes — same cluster |
| **MTB** (M&T Bank) | am | $4.93 | Yes — same cluster |
| **TRV** (Travelers) | am | $7.32 | Yes — same cluster, large-cap insurer |
| **LADR** (Ladder Capital) | am | $0.21 | Moderate — smaller REIT |
| **WBS** (Webster) | am | $1.63 | Yes — same cluster |
| **CMA** (Comerica) | am | $1.45 | Yes — same cluster |
| CBAT, CLPS | am | small-cap | No — too small, not pursued |

## Scheduled macro events
No major scheduled macro print identified for tomorrow as of this build (not independently
re-verified — check at the 8am true-up). Today closed quiet (VIX 16.46, SPX roughly flat) —
no broad macro theme heading into tomorrow's bank-earnings continuation.

## Small-cap-tech shortlist
Not checked at this build (the Technology-sector pre-market scan is the 8am true-up's job). Note
for continuity: today's market-hours cycles saw BBCI, AMOD, WETO, XLAB surface repeatedly in the
Technology sweep — AMOD and WETO were both traded today on explicit user instruction (AMOD
stopped out +18%, WETO closed flat) and should not be chased again without a fresh setup. BBCI
and XLAB were never pursued (no catalyst found all day).

## Sources used in this build (6pm, 2026-10-15)
- `get_equity_positions` / `get_equity_orders` (MRSH) — confirmed the 1-share AH sale filled at
  $185.00, fractional remainder has no stop and is structurally untradable off-hours.
- `get_equity_tradability` (MRSH) — confirmed no extended_hours or all_day fractional support.
- `get_equity_quotes` (MRSH, AA, IBKR, JBHT, INDB, CNS, LOOP, WAFD, SPY) — all AH figures above
  vs. official close.
- `get_earnings_calendar` (today, tomorrow, 1-day windows each) — all figures in the earnings
  tables above.
- `get_index_quotes` (SPX, NDX, VIX) — overnight tone read.
- `get_option_chains` / `get_option_instruments` / `get_option_quotes` (AA, IBKR) — AA passes all
  preliminary structural checks (DTE, cap, listed chain); IBKR fails the sizing cap.
- Today's 11am/12pm/3pm market-hours cycles (this session's own chat record) — AMOD/WETO/AZZ/BLK
  trade history, MRSH continuation thesis, broad sector-sweep results.
