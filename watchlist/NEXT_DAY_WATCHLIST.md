# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built fresh by the after-hours routine on 2026-10-20 (Tuesday close), fired
~6:06pm ET for 2026-10-21 (Wednesday). **Asian/European overnight-session news has NOT been
checked yet at this hour** — that is the job of the ~8am overnight true-up routine before the
open.

**Step 0 (6pm) — held position defense check:** Only position is **HAL**, 8 sh @ $33.20 avg.
Regular-hours stop at $31.00 expired as expected at the 4:00pm close (GFD). After-hours quote:
last trade $33.61 (close), last non-reg $33.66 (5:23pm ET), bid $33.62 / ask $34.00 (5:37pm ET)
— well above the $31 floor, no defense action needed or possible to improve on. Position is
safe overnight at current levels.

**Account status:** One position — **HAL**, 8 sh @ $33.20 avg, ~$33.62 bid after-hours
(+1.3% from entry). Cash ~$2,669. No options positions.

**Tone at this build (6pm):** SPX 7,715 / NDX 29,541 / VIX 17.42 as of the 3pm cycle (no fresh
after-hours index tick available). Calm, unremarkable session — no broad risk-off or risk-on
signal. A very heavy day of earnings (60+ reports today alone), mostly a non-event for
individual names beyond the ones below.

---

## Ranked candidates (6pm build, for 2026-10-21)

### 1. COF (Capital One) — beat and up, real and fresh
- **Catalyst:** Q3 2026 earnings, reported after today's close (2026-10-20). EPS **$6.69 actual
  vs $5.49 est. — a ~22% beat.** Source: `get_earnings_calendar`.
- **Direction/magnitude:** Bullish. AH bid $208.50 vs regular close $199.83 — **+4.3%**, clean
  beat-and-up reaction so far.
- **Freshness confidence:** High — fresh tonight, large-cap, should carry through to the open
  barring overnight fade.
- **Disqualifiers:** None found yet. Re-verify AH hasn't faded by the 8am true-up.
- **Options read (PRELIMINARY, NOT A LIVE QUOTE — reflects tonight's AH, not regular-session):**
  $210C exp. 2026-11-06 (17 DTE — passes). Mark $2.70/contract (~$270) — passes the ~$294 sizing
  cap but close to it. OI 6, volume 0 (pre-tomorrow reset) — **thin, liquidity concern, verify
  live spread/volume before treating as viable.** Structural read: **PASS on DTE/premium, FAIL
  on liquidity as of tonight's snapshot — re-check live at the open.**
- **Verdict:** Top candidate — check first at 9:40am regular session.

### 2. NLY (Annaly Capital) — beat and up, real and fresh
- **Catalyst:** EPS **$0.80 actual vs $0.78 est. — beat.** Source: `get_earnings_calendar`.
- **Direction/magnitude:** Bullish. AH bid $18.35 vs close $17.72 — **+3.6%**, clean mREIT
  beat-and-up.
- **Freshness confidence:** High — fresh tonight, clean reaction.
- **Disqualifiers:** Small absolute price (~$18) — typical for an mREIT, not a liquidity
  concern in the underlying, but position sizing will be in whole shares at modest dollar size.
- **Options read (PRELIMINARY):** $18.50C exp. 2026-11-06 (17 DTE — passes). Mark
  $0.36/contract (~$36) — comfortably passes the sizing cap. OI 79, volume 8 — thin but better
  than COF's. Structural read: **PASS on DTE/premium/OI, volume still light — re-verify live.**
- **Verdict:** Second candidate — cheaper options expression than COF if that route is explored.

### 3. SPCX — big beat and up, large magnitude
- **Catalyst:** EPS **$0.35 actual vs $0.16 est. — a ~119% beat.** Source: `get_earnings_calendar`.
- **Direction/magnitude:** Bullish. AH bid $157.96 vs close $147.96 — **+6.8%**, strong reaction.
- **Freshness confidence:** High — fresh tonight, big magnitude.
- **Disqualifiers:** None found in the catalyst itself, but note the move is already large
  (+6.8% AH) — watch for further extension vs. fade by the 8am true-up before treating as a
  fresh breakout at the open.
- **Options read (PRELIMINARY):** $160C exp. 2026-11-06 (17 DTE — passes). Mark
  $3.75/contract (~$375) — **FAILS the ~$294 sizing cap.** OI 1,507 / volume 2,271 — the most
  liquid of tonight's names, but the premium itself disqualifies at this strike; a further
  OTM strike would be needed to fit the cap. Structural read: **FAIL on premium cap at this
  strike.**
- **Verdict:** Watch — real catalyst, but already extended AH and options premium too rich at
  the near-ATM strike.

### 4/5. NFLX, ISRG — real beats, reacting NEGATIVELY ("beat but down")
- **NFLX:** EPS **$0.87 vs $0.82 est. — beat.** AH bid $64.74 vs close $69.85 — **-7.3%**, a
  sharp "beat but down" reaction (likely guidance/subscriber-metric driven). Large magnitude,
  bearish.
- **ISRG:** EPS **$3.00 vs $2.54 est. — an ~18% beat.** AH bid $403.51 vs close $433.18 —
  **-6.9%**, same "beat but down" pattern.
- **Verdict:** Not long candidates per the beat-does-not-predict-direction pattern seen
  repeatedly this cycle. Flagged for awareness only; a bearish options expression (e.g. NFLX
  $65P 11/06, listed and tradable) was not fully priced tonight given the research budget —
  not pursued further, re-evaluate only if continued weakness is confirmed at the open.

### Carried forward from today's cluster — still holding, no fresh trigger
- **EFX** +11.3% today (real beat), AH bid $176.67 — holding steady, flat since the close.
- **HAS** +10.6% today (real ~57% beat), AH bid $109.60 — holding/slightly extending.
- **MMM** +5.1%, **NOC** +4.5%, **RTX** +0.7% — all real beats from this morning, holding
  roughly flat to slightly softer in AH. No fresh entry trigger; already several hours into
  their moves as of today's close.
- **GE** -3.6% — still negative, beat-but-down, not a candidate.

---

## Today's after-close earnings reactions (2026-10-20, pm) — notable names only

| Ticker | Est. EPS | Actual EPS | AH reaction | Notable? |
|---|---|---|---|---|
| **COF** | $5.49 | $6.69 — big beat | **+4.3%** | Yes — candidate #1 |
| **NLY** | $0.78 | $0.80 — beat | **+3.6%** | Yes — candidate #2 |
| **SPCX** | $0.16 | $0.35 — huge beat | **+6.8%** | Yes — candidate #3 |
| **NFLX** | $0.82 | $0.87 — beat | **-7.3%** | Beat but down hard — not a long candidate |
| **ISRG** | $2.54 | $3.00 — big beat | **-6.9%** | Beat but down hard — not a long candidate |
| **CB** | $6.74 | $7.66 — beat | ~-1.1% | Beat, flat/down — not notable |
| PEGA | $0.43 | $0.35 — miss | ~-1.7% | Miss and down, small — not pursued |
| OZK | $1.43 | $1.50 — beat | ~-0.9% | Beat but flat — not notable |
| UAL | $2.59 | $2.54 — miss | ~+0.4% | Miss but flat/up — not notable |
| ALK | $0.29 | $0.36 — beat | ~-0.7% | Beat but flat — not notable |
| EWBC | $2.72 | $2.76 — beat | Quote unreliable (wide AH spread) | Not pursued |

## Tomorrow's scheduled earnings (2026-10-21) — before the open ("am" timing)

Large/notable names reporting before tomorrow's open: **TMO** (Thermo Fisher), **NEE**
(NextEra Energy), **PM** (Philip Morris), **DHR** (Danaher), **ABT** (Abbott), **T** (AT&T),
**MCO** (Moody's), **CME**, **NTRS**, **WAB**, **LAD**, **MHO**, plus a long tail of regional
banks (ONB, SF, CTBI, FCCO, OFG, PLBC, HCSG, BKU, TDY, WGO). None of these have reported yet —
all are "pending, check pre-market tomorrow" rather than scored tonight.

## Tomorrow's scheduled earnings — after tomorrow's close ("pm" timing, relevant to the 6pm 10/21 build)

Big names reporting after tomorrow's close: **META**, **TSLA**, **TXN**, **IBM**, **LRCX**,
**CSX**, **KMI**, **URI**, **LVS**, **MOH** — not actionable tonight, noted for the next
after-hours build.

## Scheduled macro events
No major scheduled macro print identified for tomorrow as of this build. VIX was 17.42 at the
3pm cycle, calm. Asian/European overnight sessions not yet checked — see note at top.

## Sources used in this build (6pm, 2026-10-20)
- `get_equity_positions` / `get_equity_orders` (HAL) — Step 0 check, GFD stop expired as
  expected at 4:00pm close, no action needed or possible; AH price well above the old floor.
- `get_equity_quotes` (HAL, ISRG, COF, CB, NFLX, SPCX, PEGA, OZK, UAL, ALK, NLY, EWBC, GE, EFX,
  HAS, MMM, NOC, RTX) — all after-hours figures vs. official regular-session close.
- `get_earnings_calendar` (today days=-1, tomorrow days=1) — full after-close reaction table
  and tomorrow's scheduled reporters, both am and pm timing.
- `get_option_chains` / `get_option_instruments` / `get_option_quotes` (COF, NLY, SPCX) — all
  three pass DTE; COF/NLY thin on volume, SPCX fails the premium cap at the near-ATM strike.
  NFLX put checked structurally (chain exists, $65P listed) but not fully priced tonight.
- No `get_equity_news` tool available this session (confirmed again) — all catalyst
  confirmation relies on `get_earnings_calendar` actuals vs. estimates plus price reaction.
