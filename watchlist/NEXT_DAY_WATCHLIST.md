# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built fresh by the after-hours routine on 2026-10-13 (Tuesday close), fired
~6:06pm ET; **trued up by the overnight routine, fired ~7:53am ET on 2026-10-14 (Wednesday).**

**Step 0 — held position defense check (true-up, ~7:53am ET):** `get_equity_positions` confirms
the account is still **flat — no equity or options positions held.** Nothing to defend pre-market.

**Account status:** Flat, $2,943.47 cash/buying power. SKYA (bought earlier today on explicit user
instruction, stop raised $2.20→$2.35→$2.40 through the session) was stopped out at today's open
per the user's final $2.40 floor — that trade is closed; see this afternoon's chat for the exact
fill. No other positions opened today; GS, UNH, BMBL, JNJ, FRMI, MDB, EFXT, AGBK, STGW, RGC and the
rest of today's movers were all checked across the 11am/12pm/3pm cycles and none qualified (no
confirmed catalyst, or capped-arb/structure problems — see below).

**Standing watch — AAOI / COHR (per standing user instruction, checked every morning regardless of
scan results):** **AAOI** prior close $97.78 → pre-market $96.27, bid $96.12/ask $96.50
(**-1.5%**), continuing its fade. **COHR** prior close $289.98 → pre-market $285.50, bid
$285.14/ask $285.80 (**-1.5%**) — yesterday evening's modest AH bounce (+0.8%) fully reversed
overnight, back to fading. No fresh overnight catalyst found for either. Unchanged recommendation:
this optical-sector thesis (LITE/CIEN/COHR/AAOI) remains invalidated; retained here only per the
standing AAOI/COHR morning-check instruction.

**Tone at this build:** A quiet, directionless afternoon after the morning's bank/healthcare
earnings cluster. SPX/NDX drifted mildly higher intraday (SPX 7798→7810.74, VIX flat at 15.43) with
no stress signal. The GS/UNH earnings-beat setups that looked promising this morning both failed
Step 6 price structure by the 11am cycle (gapped to highs, reversed hard within the first 10
minutes) and were formally rejected — a reminder that a big beat alone doesn't guarantee a clean
technical setup once the open's volatility resolves. BMBL (Bumble take-private talks) continued
extending all day (+56% at the close) but remains declined as capped merger-arb. JNJ deteriorated
further through the day (-5.4% to -6.5% depending on the snapshot) with no actionable thesis
either direction.

---

## Today's closed position
**SKYA** — bought today on explicit user instruction (~$150 stake), stop raised $2.20→$2.35→$2.40
across the session, stopped out at the open per the final $2.40 floor. Account is flat as of this
build. Do not re-enter without a fresh, independently-qualifying setup — per the STOCK
TRAILING-STOP RULE, a clean stop-out is not followed by an automatic re-entry.

---

## Ranked candidates

### 1. BLK (BlackRock) — STRENGTHENED/NEW, massive earnings beat, clean pre-market gap
- **Catalyst confirmed (true-up, ~7:53am ET):** Q3 2026 EPS $15.93 actual vs. $14.25 estimate
  (**+11.8% beat**), reported before this morning's open (`get_earnings_calendar`, verified=true).
- **Price action:** Official close $1,066.12 → pre-market $1,120.00, bid $1,113.00/ask $1,120.00
  (**+5.1%**) — large, clean, orderly gap on real size (mega-cap asset manager).
- **Direction/magnitude:** Bullish, matches catalyst direction, the single cleanest beat+gap
  combination in this morning's bank cluster (contrast MS/BAC/STT/FAST below, all "beat/miss but
  down").
- **Freshness confidence:** High — same-morning, confirmed via the earnings calendar, clean
  pre-market confirmation already in hand before the open.
- **Disqualifiers:** None on the stock side — needs live re-verification at the open (gap-fade
  risk is real given yesterday's GS/UNH lesson: both beat big and still failed Step 6 structure
  within 10 minutes of the open).
- **Options read (PRELIMINARY, last-close-basis quotes):** Chain exists; 11/06 expiration (23 DTE
  from today — **PASSES the 7-30 DTE window**). $1,120 call: mark $18.05 → **~$1,805/contract —
  FAILS the ~$294 sizing cap badly**; OI only 1, volume 0 — **also fails liquidity**. BLK's own
  four-figure share price makes any near-the-money contract structurally too expensive, same
  problem as GS/UNH yesterday. **Net: FAIL on premium AND liquidity** — stock-only if this
  re-qualifies live.
- **Verdict:** Best-qualified fresh setup of this build. Top priority for the 9:40am cycle's live
  re-check — but apply yesterday's GS/UNH lesson and demand a held base, not just a clean gap.

### 2. AZZ (AZZ Inc.) — UNCHANGED/holding, confirmed earnings beat, overnight gap intact
- **Catalyst confirmed:** Q2 FY2027 EPS $2.00 actual vs. $1.84 estimate (beat), reported after
  Tuesday's close.
- **Price action (true-up, ~7:53am ET):** Official close $136.71 → pre-market $140.14, bid
  $138.50/ask $140.00 (**+2.5%**) — holding and slightly extending last night's after-hours pop
  ($140.03), not fading. Real size ($4.14B market cap).
- **Freshness confidence:** High — holding its gap overnight is a good sign vs. a name that faded.
- **Disqualifiers:** None new.
- **Options read:** Unchanged from last night — no expiration threads the 7-30 DTE window (nearest
  are 2 and 37 DTE from tomorrow's open). **FAIL on DTE structurally.** Stock-only if it re-qualifies.
- **Verdict:** Still a real, same-day catalyst with a gap that's holding overnight — second priority
  for the 9:40am cycle's live re-check.

### 3. MS / BAC / STT / FAST / ASML — reported, mixed/negative pre-market reactions despite several beats
- **MS (Morgan Stanley):** Beat ($3.03 vs $2.90 est.) but pre-market $185.10 vs close $186.64
  (**-0.8%**) — beat-but-down, same guidance-driven pattern as yesterday's WFC/JNJ/DPZ.
- **BAC (Bank of America):** Missed ($1.08 vs $1.11 est.), pre-market $51.55 vs close $53.96
  (**-4.5%**) — miss and down, consistent reaction.
- **STT (State Street):** Beat slightly ($3.69 vs $3.67 est.) but pre-market $162.00 vs close
  $174.10 (**-6.9%**) — a beat with a large negative reaction, likely guidance-driven; worth
  a closer look live but the gap direction fights the catalyst.
- **FAST (Fastenal):** Beat slightly ($0.35 vs $0.34 est.) but pre-market $48.71 vs close $51.43
  (**-5.3%**) — same beat-but-down pattern.
- **PGR (Progressive):** Not yet reported (actual still null as of this true-up); pre-market
  $224.80 vs close $222.88 (**+0.9%**), modest.
- **ASML:** Huge beat ($14.88 vs $12.47 est., +19.3%) but pre-market essentially flat, $1,706.14
  vs close $1,717.76 (**-0.7%**) — muted reaction despite the size of the beat.
- **Verdict:** Aside from BLK (candidate #1), this cluster is repeating yesterday's "beat doesn't
  predict direction once guidance is in play" lesson. None of MS/STT/FAST/ASML are clean long
  setups (wrong-direction or muted reactions); BAC's miss+down is directionally consistent but not
  a momentum-long thesis. Not carried as candidates — re-check live only if price action changes
  materially at the open.
- **Options read:** Not checked — none of these independently qualify on price action.

### 4. BNAI — reported today, narrower-than-expected loss, not a setup
- **Catalyst:** Q2 EPS -$0.49 actual vs. -$0.80 estimate — a narrower loss, technically a "beat"
  but still a loss, reported pm, **unverified** per the earnings calendar.
- **Price action:** Close $5.28 → AH $5.14 (**-2.7%**) — down despite the narrower loss; market
  not rewarding it.
- **Verdict:** Decline — price action doesn't confirm the catalyst, and it's a small/thin name with
  an unverified report. Not pursued.

### 5. SGLY — reported/reporting today, no edge
- **Status:** No EPS estimate on file, timing pm, unverified. Close $0.704 → AH $0.68 (-3.4%).
  Sub-$1 micro-cap with no confirmed catalyst detail available.
- **Verdict:** Decline — too illiquid/small, no real catalyst data to evaluate.

### 6. GS / UNH — formally rejected intraday, carried forward for the record only
- Both beat materially this morning (GS $17.01 vs $13.05 est.; UNH $4.69 vs $4.14 est.) and gapped
  up clean at the open, but both failed Step 6 price structure by the 11am cycle — gapped to highs
  then reversed hard within the first 10 minutes (UNH went net negative intraday, GS failed to
  rebuild a base) and were formally rejected. Options were already a structural FAIL on premium cap
  for both regardless (~$1,540-$1,980/contract vs. the ~$294 cap).
- **Verdict:** Rejected for today. Would need a genuinely fresh setup (new basing structure,
  unrelated to today's earnings pop) to be reconsidered — not carried as an active candidate.

### 7. BMBL (Bumble) — still extending, still declined as capped merger-arb
- **Status:** Extended through the day to +56% intraday ($5.93-5.94), still no confirmed update to
  deal terms beyond Monday's WSJ/Reuters take-private-talks story (Ithaca Holdings, ~$1B
  valuation).
- **Verdict:** Unchanged — declined per standing merger-arb treatment (NWE/BKH precedent). Watch
  for deal-terms news, not a momentum re-entry point.

### 8. JNJ — deteriorating, no actionable thesis either direction
- **Status:** Beat this morning ($2.59 vs $2.53 est.) but sold off progressively through the day,
  -5.4% to -6.5% depending on the snapshot. No catalyst explains the magnitude of the decline beyond
  "beat but guidance-driven selloff," consistent with the broader WFC/DPZ pattern today.
- **Verdict:** No thesis either direction — not a short or long candidate under this framework.

### 9. EFXT / AGBK / FRMI / STGW / RGC / API and the broader large-cap basket (BP, INFY, ERIC, IFF,
PR, CDW, FIS, BCE, PBF) — no catalyst confirmed across multiple WebSearch attempts today
- All of these appeared as sizeable (>$300M, several >$1B) movers across today's 11am/12pm/3pm
  sweeps. WebSearch was run multiple times today on EFXT, AGBK, FRMI, STGW, RGC, API, PBF and the
  dollar/macro angle for the large-cap basket — none turned up a dated, same-day catalyst.
- The large-cap basket (BP/INFY/ERIC/IFF/PR/CDW/FIS/BCE/PBF) moving 3-7% together across unrelated
  sectors/geographies on moderate relative volume looks like a broad-basket/macro move (possibly
  dollar-driven given the ADR concentration), not individual stock catalysts — flagged as a pattern
  worth re-checking if it repeats tomorrow, but not actionable without a confirmed driver.
- RGC specifically carries a DOJ-investigation/class-action overhang and an extreme-volatility
  history — would be excluded regardless of catalyst strength.
- **Verdict:** No catalyst found for any — not carried forward as candidates.

---

## Today's after-close earnings reactions (2026-10-13, pm)

| Ticker | Est. EPS | Actual EPS | AH reaction | Notable? |
|---|---|---|---|---|
| **AZZ** | $1.84 | **$2.00 — beat** | **+1.65%** (vs. official close) | Yes — see candidate #1 |
| BNAI | -$0.80 | -$0.49 (narrower loss) | -2.7% | No — price doesn't confirm |
| SGLY | — (no estimate) | — (not detailed) | -3.4% | No — too small/thin |
| SGMOQ | -$0.06 | Not yet reported | — | Not pursued, tiny |

## Today's scheduled earnings (2026-10-14) — before the open unless noted, now reported

| Ticker | Timing | Est. EPS | Actual EPS | Pre-market reaction | Notable? |
|---|---|---|---|---|---|
| **BLK (BlackRock)** | am | $14.25 | **$15.93 — big beat** | **+5.1%** | Yes — see candidate #1 |
| **MS (Morgan Stanley)** | am | $2.90 | $3.03 — beat | -0.8% | Beat but down — see candidate #3 |
| **BAC (Bank of America)** | am | $1.11 | $1.08 — miss | -4.5% | Miss and down, consistent |
| **STT (State Street)** | am | $3.67 | $3.69 — beat | -6.9% | Beat but down big — see candidate #3 |
| **FAST (Fastenal)** | am | $0.34 | $0.35 — beat | -5.3% | Beat but down — see candidate #3 |
| **ASML** | am | $12.47 | $14.88 — big beat | -0.7% | Muted despite big beat |
| **PGR (Progressive)** | am | $4.37 | Not yet reported | +0.9% | Modest, not yet confirmed |
| EDUC, SOTK, EQBK, CMTL, PNFP, HOMB, VSEE, SNV | am/pm | various | mixed/not yet | Not checked | Small-caps, not pursued |

**Confirmed this morning: BLK is the clean beat+gap setup** (candidate #1); everything else in the
cluster either missed, or beat but sold off — the same "beat doesn't predict direction once
guidance is in play" pattern as yesterday's WFC/JNJ/DPZ.

## Scheduled macro events
September CPI is expected today, Wednesday 2026-10-14, 8:30am ET (per last week's research, not
independently re-verified this morning) — not yet released as of this true-up (~7:53am ET). VIX
this morning: **15.37**, essentially unchanged — no overnight risk-off signal. SPX/NDX cash levels
are stale (last prints from yesterday's regular session; they don't trade pre-market).

## Small-cap-tech shortlist
Checked at true-up (~7:53am ET): Technology sector scan returned **zero matches**. Nothing to
shortlist this morning — same result as several checks yesterday.

## Sources used in this build (6pm, 2026-10-13; trued up ~7:53am ET, 2026-10-14)
- `get_equity_positions` — confirmed flat, no held positions (Step 0 — nothing to defend), both at
  6pm and at the 7:53am true-up.
- `get_earnings_calendar` (today -1 day window, tomorrow +1 day window, unfiltered) — all figures
  in the earnings tables above.
- `get_equity_quotes` (AZZ, BNAI, SGLY, AAOI, COHR, LITE, CIEN, SPY, QQQ, SKYA, MS, BAC, BLK, STT,
  PGR, FAST, ASML) — all after-hours/pre-market figures above vs. official close.
- `get_option_chains` / `get_option_instruments` / `get_option_quotes` (AZZ, BLK 11/06 $1120 call)
  — options-read figures for candidates #1 and #2.
- `get_index_quotes` (VIX, SPX, NDX) — VIX 15.37 live; SPX/NDX stale (pre-market, no cash trade).
- `run_scan` (Technology sector sweep) — zero matches at true-up.
- Today's 11am/12pm/3pm market-hours cycles (this session's own chat record) — GS/UNH rejection,
  BMBL/JNJ/EFXT/AGBK/FRMI/STGW/RGC/API status, large-cap-basket pattern.
