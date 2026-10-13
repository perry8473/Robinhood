# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built fresh by the after-hours routine on 2026-10-13 (Tuesday close), fired
~6:06pm ET. Asian/European overnight-session news has **not** been checked at this hour — that is
the job of the ~8am overnight true-up routine before tomorrow's (2026-10-14, Wednesday) open.

**Step 0 — held position defense check:** `get_equity_positions` confirms the account is **flat —
no equity or options positions held.** Nothing to defend off-hours this evening.

**Account status:** Flat, $2,943.47 cash/buying power. SKYA (bought earlier today on explicit user
instruction, stop raised $2.20→$2.35→$2.40 through the session) was stopped out at today's open
per the user's final $2.40 floor — that trade is closed; see this afternoon's chat for the exact
fill. No other positions opened today; GS, UNH, BMBL, JNJ, FRMI, MDB, EFXT, AGBK, STGW, RGC and the
rest of today's movers were all checked across the 11am/12pm/3pm cycles and none qualified (no
confirmed catalyst, or capped-arb/structure problems — see below).

**Standing watch — AAOI / COHR (per standing user instruction, checked every morning regardless of
scan results; AH figures below are for continuity only, not a substitute for the 8am true-up):**
**AAOI** close $100.68 → now $99.00 after-hours (**-1.7%**), still fading. **COHR** close $288.02 →
now $290.25 after-hours (**+0.8%**), a modest bounce off today's -7.9% close but not a reversal of
the broader thesis. **LITE** $995.41 → $990.00 AH (-0.5%), **CIEN** $405.01 → $401.99 AH (-0.7%) —
both still soft. No fresh catalyst found for any of the four. Unchanged recommendation from
yesterday: this optical-sector thesis (LITE/CIEN/COHR/AAOI) remains invalidated after Monday's full
reversal; retained here only per the standing AAOI/COHR morning-check instruction.

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

### 1. AZZ (AZZ Inc.) — NEW, confirmed earnings beat, clean after-hours follow-through
- **Catalyst confirmed:** Q2 FY2027 EPS $2.00 actual vs. $1.84 estimate (beat), reported after
  today's close (`get_earnings_calendar`, timing=pm, verified=true).
- **Price action:** Regular close $136.73 → after-hours $140.03 (**+2.4%** vs. last regular trade;
  **+1.65%** vs. yesterday's official close of $137.76), bid $139.69/ask $140.75 — real size
  ($4.14B market cap, industrials/metal-coatings), orderly follow-through, no halt.
- **Direction/magnitude:** Bullish, matches the catalyst direction, moderate-size mid-cap.
- **Freshness confidence:** High — same-evening, confirmed via the earnings calendar, with a clean
  AH price reaction already in hand.
- **Disqualifiers:** None identified yet on the stock side — needs the standard live re-verification
  at the open (gap size, whether it holds or fades pre-market, clean entry/stop structure).
- **Options read (PRELIMINARY, last-close-basis quotes):** Chain exists; expirations are 10/16 (3
  DTE from today, 2 DTE from tomorrow's open — **FAILS**, under the 4-DTE floor), 11/20 (37 DTE
  from tomorrow — **FAILS**, over the 30-DTE window), 2027-02/05 (far too long). **No expiration
  threads the 7-30 DTE window — FAIL on DTE structurally**, same way BMBL failed earlier this week.
  Stock-only if this re-qualifies live.
- **Verdict:** Best-qualified fresh setup of this build — real, same-day catalyst with clean AH
  confirmation. Top priority for tomorrow's 9:40am opening-bell cycle's live re-check.

### 2. Tomorrow's scheduled earnings cluster (before-the-bell, 2026-10-14) — WATCH, not yet actionable
- **MS (Morgan Stanley)**, **BAC (Bank of America)**, **BLK (BlackRock)**, **STT (State Street)**,
  **PGR (Progressive)**, **FAST (Fastenal)** all report before tomorrow's open; **ASML** also
  reports before the open (large semiconductor-equipment name, NDX-relevant).
- This is a direct continuation of today's bank cluster (GS/JPM/WFC/C/JNJ/UNH) — another wave of
  large-cap, high-market-cap reports hits right at tomorrow's open. None of these have reported yet
  (`eps.actual` is null for all as of this build), so there is no reaction to evaluate tonight.
- **Verdict:** Not a candidate yet — flagging for the 8am true-up and 9:40am cycle to check
  immediately once actuals post. Given today's lesson (GS/UNH beats both failed to hold a clean
  base), treat any gap here with the same Step 6 scrutiny rather than chasing the headline beat.
- **Options read:** Not checked — no catalyst to evaluate against yet.

### 3. BNAI — reported today, narrower-than-expected loss, not a setup
- **Catalyst:** Q2 EPS -$0.49 actual vs. -$0.80 estimate — a narrower loss, technically a "beat"
  but still a loss, reported pm, **unverified** per the earnings calendar.
- **Price action:** Close $5.28 → AH $5.14 (**-2.7%**) — down despite the narrower loss; market
  not rewarding it.
- **Verdict:** Decline — price action doesn't confirm the catalyst, and it's a small/thin name with
  an unverified report. Not pursued.

### 4. SGLY — reported/reporting today, no edge
- **Status:** No EPS estimate on file, timing pm, unverified. Close $0.704 → AH $0.68 (-3.4%).
  Sub-$1 micro-cap with no confirmed catalyst detail available.
- **Verdict:** Decline — too illiquid/small, no real catalyst data to evaluate.

### 5. GS / UNH — formally rejected intraday, carried forward for the record only
- Both beat materially this morning (GS $17.01 vs $13.05 est.; UNH $4.69 vs $4.14 est.) and gapped
  up clean at the open, but both failed Step 6 price structure by the 11am cycle — gapped to highs
  then reversed hard within the first 10 minutes (UNH went net negative intraday, GS failed to
  rebuild a base) and were formally rejected. Options were already a structural FAIL on premium cap
  for both regardless (~$1,540-$1,980/contract vs. the ~$294 cap).
- **Verdict:** Rejected for today. Would need a genuinely fresh setup (new basing structure,
  unrelated to today's earnings pop) to be reconsidered — not carried as an active candidate.

### 6. BMBL (Bumble) — still extending, still declined as capped merger-arb
- **Status:** Extended through the day to +56% intraday ($5.93-5.94), still no confirmed update to
  deal terms beyond Monday's WSJ/Reuters take-private-talks story (Ithaca Holdings, ~$1B
  valuation).
- **Verdict:** Unchanged — declined per standing merger-arb treatment (NWE/BKH precedent). Watch
  for deal-terms news, not a momentum re-entry point.

### 7. JNJ — deteriorating, no actionable thesis either direction
- **Status:** Beat this morning ($2.59 vs $2.53 est.) but sold off progressively through the day,
  -5.4% to -6.5% depending on the snapshot. No catalyst explains the magnitude of the decline beyond
  "beat but guidance-driven selloff," consistent with the broader WFC/DPZ pattern today.
- **Verdict:** No thesis either direction — not a short or long candidate under this framework.

### 8. EFXT / AGBK / FRMI / STGW / RGC / API and the broader large-cap basket (BP, INFY, ERIC, IFF,
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

## Tomorrow's scheduled earnings (2026-10-14) — before the open unless noted

| Ticker | Timing | Est. EPS | Notable? |
|---|---|---|---|
| **MS (Morgan Stanley)** | am | $2.90 | Yes — bank cluster continuation, see candidate #2 |
| **BAC (Bank of America)** | am | $1.11 | Yes — same cluster |
| **BLK (BlackRock)** | am | $14.25 | Yes — same cluster |
| **STT (State Street)** | am | $3.67 | Yes — same cluster |
| **PGR (Progressive)** | am | $4.35 | Yes — insurer, worth a check |
| **FAST (Fastenal)** | am | $0.34 | Moderate — industrials bellwether |
| **ASML** | am | $12.47 | Yes — large semi-equipment name, NDX-relevant |
| EDUC, SOTK, EQBK, CMTL, PNFP, HOMB, VSEE, SNV | am/pm | various | Small-caps, not pursued |

## Scheduled macro events
September CPI is expected tomorrow, Wednesday 2026-10-14, 8:30am ET (per last week's research, not
independently re-verified tonight) — directly relevant given tomorrow's open also carries the
MS/BAC/BLK/STT/PGR/FAST/ASML earnings cluster. VIX this evening: **15.43**, flat — no risk-off
signal heading into tomorrow.

## Small-cap-tech shortlist
Checked across today's cycles: IZM, VEEA, GMEX, JZ all surfaced in the Technology sector sweep at
various points today, all sub-$15M market cap, all thin/no catalyst confirmed. None carried forward
as live candidates — carve-out requires explicit user approval and none of these were caught early
enough or with a real catalyst to even propose.

## Sources used in this build (6pm, 2026-10-13)
- `get_equity_positions` — confirmed flat, no held positions (Step 0 — nothing to defend).
- `get_earnings_calendar` (today -1 day window, tomorrow +1 day window, unfiltered) — all figures
  in the earnings tables above.
- `get_equity_quotes` (AZZ, BNAI, SGLY, AAOI, COHR, LITE, CIEN, SPY, QQQ, SKYA) — all after-hours
  figures above vs. today's official close.
- `get_option_chains` (AZZ) — confirmed no expiration threads the 7-30 DTE window.
- Today's 11am/12pm/3pm market-hours cycles (this session's own chat record) — GS/UNH rejection,
  BMBL/JNJ/EFXT/AGBK/FRMI/STGW/RGC/API status, large-cap-basket pattern, small-cap-tech shortlist.
