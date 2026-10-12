# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% pre-market and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** overnight true-up fired ~7:54am ET on 2026-10-12 (Monday). **This file's git
history was found reset to an older commit** (the 2026-10-08 true-up) when this run started —
the 2026-10-08 6pm build, the 2026-10-09 true-up, and the 2026-10-09 6pm build (which covered a
user-directed COHR buy, two stop raises, and its same-evening sale) are no longer in this file's
committed history, most likely from a merge/branch-recreation elsewhere on this repo. That trade
itself is unaffected — it happened in the brokerage account, not in git — and `get_equity_positions`
below confirms the account is flat. Rather than reconstruct lost file content from memory, this
build starts fresh from live data for today.

**Step 0 (held-position defense):** `get_equity_positions` and `get_option_positions` for account
787937630 both return empty. **No stock or options position held — nothing to defend.**

**Standing watch — optoelectronic sector (AAOI / COHR):** Both continuing to fade. **AAOI**
Friday close $109.64 → pre-market $106.75, bid $106.71/ask $107.16 (**-2.6%**). **COHR** Friday
close $312.62 → pre-market $306.15, bid $306.00/ask $306.35 (**-2.1%**). No fresh catalyst found.
This extends the pattern from last week (both names were the weak/lagging followers of the
Lumentum optical-shortage story, well behind LITE/CIEN) and now neither is holding even that —
logged as a standing sector-interest watch item per standing user instruction, not a candidate.

**Tone at this true-up:** VIX **15.44**, little changed from Friday — no overnight risk-off signal.
SPX/NDX cash indexes are stale (last print Friday's close; they don't trade over the weekend).
No Monday-specific scheduled macro data found. **Friday evening's broad after-hours rally across
several unrelated names (tower REITs, health insurers, SNOW/TEVA/FSLY) has fully reverted** —
see candidates below. Today's earnings calendar is thin: only LNAI, HKD, CGTL, NPT, all small/
unverified, all reporting **pm** (after today's close) — nothing scheduled before the open.
Small-cap-tech sector scan returned **zero matches** at the standing threshold.

---

## Today's open positions
None. Account flat.

---

## Ranked candidates

**No live candidate clears the standing framework this morning.** Everything below is either a
reverted/invalidated move or a weakened continuation — presented for continuity, not as something
to act on at the open without new information.

### 1. LITE / CIEN (optical components) — WEAKENED, catalyst still real but momentum stalled
- **Status:** WEAKENED. **LITE** Friday close $1,103.355 → pre-market $1,097.93, bid
  $1,096.00/ask $1,098.00 (**-0.5%**). **CIEN** Friday close $449.77 → pre-market $443.51, bid
  $443.66/ask $446.20 (**-1.4%**). Both gave back a slice of Friday's gain rather than extending.
- **Catalyst:** Still the Lumentum "sold out through early 2029" optical-shortage comment from
  last week — real and fundamental, but now several days old with no fresh confirmation overnight.
- **Verdict:** Thesis intact but stale and not extending. Options already failed the account's
  sizing cap at Friday's prices (LITE ~$3,530/contract, CIEN ~$1,565/contract on a 10/16 ATM
  call) and nothing about this morning's pullback changes that math — not re-pulled live given
  the move is the wrong direction for a fresh options read anyway. Re-check for a stock-only
  entry only if it reverses and extends again; don't chase the fade.

### 2. CCI / AMT / SBAC (tower REITs) — INVALIDATED, Friday's move fully reverted
- Friday's after-hours prints (CCI +15.7%, AMT +9.2%, SBAC +7.4%) have completely round-tripped:
  **CCI** pre-market $80.02 vs. Friday close $79.64 (flat, +0.5%). **AMT** pre-market $183.04 vs.
  close $182.24 (flat, +0.4%). **SBAC** quote unreliable (bid $172.75/ask $194.50 — absurdly wide),
  but last print $183.00 is also flat vs. $182.49 close. No catalyst was ever confirmed for
  Friday's spike despite dedicated searches; the full reversion strongly suggests it was noise
  (thin after-hours liquidity, not a real repricing). **Dropped from watch** — nothing here to
  track going into today.

### 3. HUM / ELV (health insurers) — INVALIDATED, Friday's move mostly reverted
- **HUM** Friday close $431.87 → pre-market $437.70, bid $433.17/ask $437.60 (**+1.4%**, down
  sharply from Friday's +11.9% after-hours print). **ELV** quote unreliable (bid $391.28/ask
  $427.00 — very wide); last print $413.08 vs. close $412.70 is flat. Same pattern as the tower
  REITs — Friday's spike did not hold. **Dropped from watch.**

### 4. SNOW / TEVA / FSLY — INVALIDATED, Friday's move fully reverted
- **SNOW** pre-market $369.30 vs. close $368.89 (flat, +0.1%, down from Friday's +7.4% AH print).
  **TEVA** pre-market $41.07 vs. close $41.10 (flat). **FSLY** pre-market $29.21 vs. close $29.30
  (-0.3%, down from Friday's +16.3% AH print — the single largest reversal of the group). No
  catalyst was ever found for any of these; the clean reversion confirms they were not real
  moves worth tracking. **Dropped from watch.**

### 5. AAOI / COHR — standing sector watch, continuing to fade (see above)
- Covered in the Standing Watch section above. Not a scored candidate.

---

## Today's scheduled earnings (2026-10-12)

| Ticker | Timing | Notable? |
|---|---|---|
| LNAI | pm | Small, unverified |
| HKD | pm | Small, unverified (stale calendar entry — report date shows 2023Q1) |
| CGTL | pm | Small, unverified |
| NPT | pm | Small, unverified (stale calendar entry — report date shows 2025Q3) |

Nothing scheduled before today's open. The next notable cluster is Tuesday 10/13 — JPM, WFC,
JNJ, GS, UNH, DPZ, C, ACI, FBK, AZZ (large-cap bank/healthcare earnings season kickoff) — per
last week's research; worth reconfirming at tonight's 6pm build since today's calendar data
couldn't be cross-checked against that older note given the file-history gap.

## Scheduled macro events
- **VIX 15.44** this morning — essentially flat vs. Friday, no overnight risk-off signal.
- No Monday-specific economic data release found.
- Per last week's research (not re-verified fresh this morning, flag for Wednesday): September
  CPI was expected Wed 10/14 8:30am ET, retail sales + PPI Thu 10/15, import/export prices Fri
  10/16 — single-source calendar, treat as likely-but-unconfirmed until closer to each date.

## Small-cap-tech shortlist
Technology sector scan returned **zero matches** at the standing threshold (≥8% change, ≥3x
relative volume) this morning. Nothing to shortlist.

## Asian/European overnight session
WebSearch found no dated October 12, 2026 coverage of overnight Asian/European markets or
futures — most recent relevant item was six days old (Oct 6) and not usable as current
information. VIX (15.44, the only overnight-trading read available) shows no elevated stress.

## Options consideration
No candidate above clears the standing framework as a live setup this morning (LITE/CIEN's
options already fail the sizing cap; everything else is an invalidated/reverted move) — skipping
a fresh options pull rather than forcing one on a name with no live thesis. Re-evaluate at
tonight's 6pm build or if anything develops fresh intraday.

## Sources used in this true-up (~7:54am ET, 2026-10-12)
- `get_equity_positions` / `get_option_positions` (account 787937630) — confirmed flat.
- `get_equity_quotes` (AAOI, COHR, LITE, CIEN, CCI, AMT, SBAC, HUM, ELV, SNOW, TEVA, FSLY, SPY,
  QQQ) — all pre-market figures above, vs. Friday 2026-10-09's official close.
- `get_index_quotes` (VIX, SPX, NDX) — VIX 15.44 live; SPX/NDX stale (weekend, last print Friday).
- `get_earnings_calendar` (2026-10-12, 1-day window) — LNAI/HKD/CGTL/NPT, all small/unverified.
- `run_scan` (Technology sector sweep, scan_id 4ab9bad9-...) — zero matches.
- WebSearch: "stock market futures today October 12 2026 overnight Asia Europe Fed" — no
  same-day coverage found; most recent usable item was six days old.
