# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built fresh by the after-hours routine on 2026-10-19 (Monday close), fired
~6:06pm ET for 2026-10-20 (Tuesday); **trued up by the 8am overnight pass**, fired ~7:53am ET.
GE/RTX/NOC/MMM/HAL have all now reported (all beat) — HAL promoted to top candidate (beat and
up); GE demoted (beat but down hard pre-market). IRON/AMRO both weakening overnight. AAOI/COHR
both fading notably pre-market.

**Step 0 (8am true-up) — held position defense check:** Only position is **CLF**, 21 sh @
$13.96 avg. `get_equity_orders` confirms zero resting orders (GFD stop expired at Monday's
close, as expected — not yet re-placed since market hasn't opened). Pre-market price
$13.78-13.83 (bid $13.78) — down ~2.3% from Monday's $14.10 close, but nowhere near the old
$12.90 floor. **No action possible or needed** — no stop exists to defend against yet, and
price isn't remotely close to the reference floor. A fresh regular-hours stop gets placed at
the 9:40am opening-bell cycle.

**Account status:** One position — **CLF**, 21 sh @ $13.96 avg, ~$13.78-13.83 pre-market
(-1.3%). Cash ~$2,662. No options positions.

**Tone at this build (8am):** Mixed. SPX 7,690.73, NDX 29,529.34 (both stale, Monday-close
carryover — no live pre-market index tick), **VIX 18.83**, up from Monday's 17.56-18.21 range —
a continued mild uptick in caution. SPY pre-market $764.85-764.91 vs Monday's close $766.48
(-0.2%), consistent with the VIX pickup. No major overnight macro event identified.

---

## Ranked candidates (trued up 8am, 2026-10-20)

### 1. HAL (Halliburton) — STRENGTHENED — beat and up, confirmed pre-market
- **Catalyst:** Q3 2026 earnings, reported this morning. EPS **$0.60 actual vs $0.58 est. —
  beat**. Source: `get_earnings_calendar`.
- **Direction/magnitude:** Bullish. Pre-market $34.10-34.47 vs Monday's close $32.98 —
  **+4.0% pre-market**, the cleanest beat-and-up reaction of the whole AM earnings cluster.
- **Freshness confidence:** High — fresh this morning, confirmed beat, clean reaction.
- **Disqualifiers:** None found yet.
- **Options read (PRELIMINARY, NOT A LIVE QUOTE — reflects Monday's close):** $34C exp.
  2026-11-06 (17 DTE — passes). Monday's close premium $0.95/contract (~$95) — passes the
  ~$296 sizing cap. OI 67, volume only 5 — thin, needs live reverification. Listed chain:
  pass. Structural read: **PASS on DTE/premium/chain, but liquidity is thin — verify live
  spread/volume before treating as viable.**
- **Verdict:** New top candidate — check first at 9:40am.

### 2. RTX, NOC, MMM — beat and up, milder reactions
- **RTX:** EPS **$2.26 vs $1.78 est. — a ~27% beat.** Pre-market $194.90-195.98 vs close
  $192.11 (**+1.5%**). Beat and up, modest magnitude.
- **NOC:** EPS **$7.89 vs $7.19 est. — beat.** Pre-market $514.00-518.47 vs close $510.65
  (**+0.7%**). Beat and up, mild.
- **MMM:** EPS **$2.50 vs $2.39 est. — beat.** Pre-market $163.02-165.19 vs close $162.01
  (**+1.2%**). Beat and up, mild.
- **Verdict:** All confirmed beat-and-up but weaker magnitude than HAL — check live at the open
  if HAL doesn't pan out.

### 3. GE — WEAKENED — beat but down hard, classic "priced in" pattern
- **Catalyst:** EPS **$2.25 vs $2.01 est. — a ~12% beat.**
- **Direction/magnitude:** Despite the beat, pre-market $301.00-301.50 vs Monday's close
  $311.28 — **-3.2% pre-market**. A real beat reacting negatively, the same "beat but down"
  pattern seen repeatedly this cycle (TRV, CFG, FITB last week).
- **Verdict:** Not a candidate — beat does not predict direction, demoted from yesterday's
  pending-cluster placeholder.

### 4/5. IRON (Disc Medicine) / AMRO (Amaero) — WEAKENED — both fading pre-market
- **IRON:** Monday's regular close $78.98 → pre-market $78.25-79.18 (~flat to slightly down).
  Momentum has stalled — no longer extending, just holding near Monday's close. Still **no
  catalyst found**. **Options still FAIL** (nearest expiration 2026-11-20, 31 DTE, outside the
  7-30 window).
- **AMRO:** Monday's regular close $5.61 → pre-market $4.77-5.45 (as much as **-7.3%** at the
  bid) — fading hard overnight, giving back a chunk of Monday's gain. Still **no catalyst
  found**. **Options still FAIL** (no listed chain at all).
- **Verdict:** Both demoted — IRON stalled, AMRO actively reversing. Neither looks like a
  continuation candidate at the open; re-verify live before writing either off completely, but
  the overnight trend is negative for both.

### 6. RLI, STLD, DX, AGNC, HBCP — Monday's after-close bank/financial earnings batch, no fresh setups
- **RLI:** huge beat ($0.86 vs $0.54 est., +59%) but AH reaction flat (~-0.2%) — beat, no
  reaction, not a candidate.
- **STLD** (Steel Dynamics — same sector as CLF): missed ($5.29 vs $5.41 est.) and down
  further AH (-3.75% from regular close) — miss and down, not a candidate, but notable as a
  same-sector read against CLF's strength (sector dispersion, not a sector-wide move).
  announced
- **DX:** big miss (-28% vs est.) but already fully priced in during today's regular session
  (-3.3% intraday); AH flat. Not fresh.
- **AGNC:** miss, -2.3% further AH on top of an intraday decline. Small, not a candidate.
- **HBCP:** miss; quote data unreliable (broken bid), not pursued.
- **Verdict:** None of tonight's financial-sector earnings produced a fresh, tradeable reaction.

---

## Optoelectronic standing watch — AAOI / COHR (user standing interest, 8am check)
- **AAOI:** Monday's regular close $78.20 → pre-market $74.40-74.64 (**-4.9%**) — a real
  overnight fade, reversing most of Monday's gain. No fresh catalyst found (no equity-news
  tool available this session).
- **COHR:** Monday's regular close $232.02 → pre-market $223.50-224.00 (**-3.7%**) — also
  fading hard overnight. No fresh catalyst found.
- Both names showing a real overnight reversal, not just noise — standing watch only, not a
  trade signal, but worth flagging given the magnitude.

---

## Today's after-close earnings reactions (2026-10-19, pm)

| Ticker | Est. EPS | Actual EPS | AH reaction | Notable? |
|---|---|---|---|---|
| **RLI** | $0.54 | $0.86 — huge beat | ~flat | No — beat, no reaction |
| **STLD** | $5.41 | $5.29 — miss | -3.75% | No — miss and down |
| ZION | $1.65 | $1.78 — beat | Not checked | No — small regional bank |
| BOKF | $2.52 | $2.64 — beat | Not checked | No |
| WASH | $0.87 | $1.01 — beat | Not checked | No |
| WRB | $1.16 | $1.17 — inline | Not checked | No |
| RBB | $0.57 | $0.74 — beat | Not checked | No |
| KARO | $0.57 | $0.57 — inline | Not checked | No |
| WAL | $2.43 | $2.45 — inline | Not checked | No |
| FNB | $0.43 | $0.43 — inline | Not checked | No |
| WTFC | $3.30 | $3.37 — beat | Not checked | No |
| SMBK | $0.96 | $1.10 — beat | Not checked | No |
| AERO | $0.27 | $0.28 — beat | Not checked | No |
| **AGNC** | $0.39 | $0.37 — miss | -2.3% AH | No — miss and down |
| CCK | $2.26 | $2.39 — beat | Not checked | No |
| **HBCP** | $1.50 | $1.28 — miss | Unreliable quote | No |
| **DX** | $0.53 | $0.38 — big miss | Flat AH (priced in intraday) | No — already reacted |

## Today's earnings (2026-10-20) — actuals as of 8am true-up, before the open unless noted

| Ticker | Est. EPS | Actual EPS | Pre-market reaction | Notable? |
|---|---|---|---|---|
| **HAL** | $0.58 | $0.60 — beat | **+4.0%** | Beat and up — see candidate #1 |
| **RTX** | $1.78 | $2.26 — big beat | **+1.5%** | Beat and up — see candidate #2 |
| **NOC** | $7.19 | $7.89 — beat | **+0.7%** | Beat and up — see candidate #2 |
| **MMM** | $2.39 | $2.50 — beat | **+1.2%** | Beat and up — see candidate #2 |
| **GE** | $2.01 | $2.25 — beat | **-3.2%** | Beat but down — see #3 |
| SYF, KEY, UCB, VICR, GPC, MSCI, EFX, CBSH, AUB, VMI, ALLY, DCOM, MBWM, PEBO, CCBG, IRDM, MLI | various | mostly beats | Not checked | No — second-tier, not pursued |
| COF, OZK, HWC, CB, QCRH, UAL, ELS, NLY, ISRG, ALK, EWBC, HAS, **NFLX** | various | pm, not yet reported | — | Pending, after today's close — relevant to tonight's 6pm build |

## Scheduled macro events
No major scheduled macro print identified for today as of this true-up. VIX ticked up again
overnight (17.56-18.21 Monday → 18.83 this morning) — a continued mild caution signal, no
confirmed shock. SPX/NDX readings are stale (Monday-close carryover, no live pre-market index
tick); VIX and SPY are the only fresh overnight-tone signals.

## Small-cap-tech shortlist
Checked at this build: Technology sector pre-market scan (scan_id 4ab9bad9) returned **zero
matches**. Nothing to add. Continuity note: EXYN (Exyn Technologies) remains "already
extended, not chasing" from Monday — not carried forward as a live candidate.

## Sources used in this build (8am true-up, 2026-10-20)
- `get_equity_positions` / `get_equity_orders` (CLF) — Step 0 check, zero resting orders (GFD
  expired Monday close, not yet re-placed), no action possible or needed pre-market.
- `get_equity_quotes` (CLF, IRON, AMRO, SLN, AAOI, COHR, GE, RTX, NOC, MMM, HAL, SPY) — all
  pre-market figures above vs. official Monday close.
- `get_index_quotes` (SPX, NDX, VIX) — overnight tone read; SPX/NDX stale, VIX fresh.
- `get_earnings_calendar` (today, 1-day window) — confirmed actuals for GE/RTX/NOC/MMM/HAL and
  the full second-tier list.
- `run_scan` (Technology sector, scan_id 4ab9bad9) — zero matches.
- `get_option_chains` / `get_option_instruments` / `get_option_quotes` (HAL) — $34C 11/06
  passes all three preliminary structural checks, thin OI/volume caveat noted.
- No `get_equity_news` tool available this session (confirmed again) — IRON/AMRO/AAOI/COHR
  catalyst checks and all "no catalyst found" verdicts rely on price action only.

## Sources used in the 6pm build (2026-10-19, carried forward)
- `get_equity_positions` / `get_equity_orders` (CLF) — Step 0 check, GFD stop expired as
  expected, no action needed or possible.
- `get_equity_quotes` (CLF, IRON, AMRO, SLN, AAOI, COHR, RLI, STLD, DX, AGNC, HBCP, SPY) — all
  after-hours figures vs. official Monday close.
- `get_earnings_calendar` (today, tomorrow, 1-day windows each) — all figures in the Monday
  earnings table above.
- `get_option_chains` (IRON, AMRO) — IRON fails DTE window (nearest expiration 31 DTE), AMRO has
  no listed chain at all.
