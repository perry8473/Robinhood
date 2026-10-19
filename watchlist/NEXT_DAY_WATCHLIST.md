# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** this file is built FRESH this morning (2026-10-19, Monday 8am overnight
true-up) rather than updated in place. The standing 6pm after-hours routine only fires
weekdays, so no build ran over the weekend (Fri 10/16 close → Mon 10/19 open) — by explicit
user instruction on Friday afternoon ("button it down until Monday... pick it up with 6pm on
Sunday"), scans were paused from the Friday 3pm cycle through Sunday, and no Sunday 6pm firing
exists on the weekday-only schedule to have built a Sunday-night version anyway. The prior file
(dated 2026-10-16, Friday) is fully stale — it covered AA/RF/MTB/TRV/CFG/TFC, all closed out or
irrelevant to today — so per Step 1's own instruction this is a clean overnight-only build using
the standard format, not an edit of Friday's content.

**Step 0 (8am true-up) — held position defense check:** `get_equity_positions` confirms **zero
open positions** (stock or options) — the book was fully closed out Friday (AA sold flat,
MRSH/AZZ/WETO/AMOD/BLK all closed prior). **No action needed or possible** — nothing to defend.

**Account status:** Flat. No stock or options positions. Cash ~$2,655 (as of Friday's close;
not re-pulled this run since Step 0 found nothing to size against).

**Tone at this build (8am):** Mixed/cautious. SPX and NDX levels only reflect Friday's
regular-session close (7,659.44 / 29,187.55) — no pre-market index tick exists for either.
**VIX 18.81**, up from Friday's 17.20 (+9.4%) on a fresh pre-market read — a mild uptick in
caution heading into the week, consistent with Friday's "entire market turning negative" move
that prompted closing out. SPY pre-market $766.90 vs Friday's close $763.25 (+0.48%) — a small
positive drift, but not enough alone to call the VIX pickup resolved.

---

## Ranked candidates (fresh build, 2026-10-19 8am true-up)

### 1. CLF (Cleveland-Cliffs) — strong beat, strong confirmed pre-market reaction
- **Catalyst:** Q3 2026 earnings, reported this morning (before-open). EPS **$0.28 actual vs
  $0.24 est. — a ~17% beat**. Source: `get_earnings_calendar`.
- **Direction/magnitude:** Bullish. Pre-market **$13.40-13.51** (bid/ask) vs Friday's close
  $12.12 — **+11.5% pre-market**, a large, clean reaction to a real beat.
- **Freshness confidence:** High — fresh this morning, "am" timing confirmed, reaction already
  sizeable pre-market. Still needs live volume/spread confirmation at the open (pre-market
  prints can be thin).
- **Disqualifiers:** None found yet. Basic Materials/steel sector — not excluded under any
  standing rule.
- **Options read (PRELIMINARY, NOT A LIVE QUOTE — reflects Friday's close, options market not
  yet open):** $14C exp. 2026-11-06 (18 DTE — **passes** the 7-30 window). Friday's close premium
  $0.37/contract (~$37 total) — **passes** the current ~$295 sizing cap (10% of ~$2,955 balance,
  since balance is now over $2,000). OI 252, volume 50 — reasonable liquidity for a name this
  size. Listed chain: **pass**. Structural read: **PASS on all three checkable items**, same
  caveat as always that spread/volume must be re-verified live.
- **Verdict:** Top candidate — a real, fresh, sizeable beat-and-up reaction with a structurally
  viable options path. Check first at 9:40am.

### 2/3. AAOI / COHR — standing optoelectronic watch, both showing notable pre-market gaps
- **AAOI:** Friday close $75.57 → pre-market **$79.24-79.47** (bid/ask), **+5.1%**. Crosses the
  5% move threshold that would normally trigger a news check — but **no catalyst found (no
  equity-news tool available this session)**, so this cannot be confirmed as catalyst-driven vs.
  sector-wide drift.
- **COHR:** Friday close $232.90 → pre-market **$242.60-243.26** (bid/ask), **+4.3%**. Same
  situation — notable move, no verifiable catalyst with the tools available.
- Both names moving together in the same direction raises the possibility of a sector-wide
  optoelectronics/datacenter-optics catalyst, but this is speculation without a news tool to
  confirm it — treat as unconfirmed.
- **Options read (AAOI, PRELIMINARY):** $80C exp. 2026-11-06 (18 DTE — passes). Friday's close
  premium **$7.00/contract (~$700 total) — FAILS the ~$295 sizing cap** outright. OI only 41,
  volume 22 — thin. Structural read: **FAIL (premium far exceeds cap)**. Not pursued further;
  COHR not checked given AAOI already fails on sizing and COHR is a higher-priced name.
- **Verdict:** Standing watch only, not a trade signal per the routine's own framing — this is
  a real pre-market move worth flagging to the user, but neither has a confirmed catalyst and
  AAOI's options route is structurally closed on sizing. Re-check live at the open; do not treat
  the pre-market gap alone as tradeable.

### 4. FITB (Fifth Third Bancorp) — big beat, but reaction already negative
- **Catalyst:** Q3 2026 earnings, this morning. EPS **$1.13 actual vs $0.87 est. — a ~30% beat**,
  the largest beat of today's reporters.
- **Direction/magnitude:** Despite the beat, pre-market **$48.01-50.17** (bid/ask) vs Friday's
  close $50.37 — roughly **flat to -0.75%**, with a notably wide pre-market spread (~4.5%)
  signaling thin/unreliable liquidity at this hour.
- **Freshness confidence:** Catalyst is fresh, but the "beat but down" reaction (continuing last
  week's dominant pattern seen in TRV/CFG) makes this a weak setup regardless of beat size.
- **Disqualifiers:** Wide, unreliable pre-market spread.
- **Options read:** Not checked — reaction doesn't support a bullish thesis, so no options read
  pulled.
- **Verdict:** Not a candidate. Flagging for completeness only, consistent with the "beat does
  not predict direction" lesson from last week.

### 5. VFS (VinFast) — big miss, muted/thin reaction
- **Catalyst:** Q2 FY2027 earnings. EPS **-$0.53 actual vs -$0.31 est. — a large miss**.
- **Direction/magnitude:** Pre-market $3.00-3.20 vs Friday's close $3.12 — essentially flat
  (-1.6% at the low end), muted for a miss this size, likely already priced in on this
  low-value name.
- **Verdict:** Not a candidate — miss already largely discounted, no clean setup either
  direction.

### 6. CBZ (CBIZ) — small miss, no real pre-market tick
- **Catalyst:** Q3 2026 earnings. EPS **$1.21 actual vs $1.26 est. — a small miss**.
- **Direction/magnitude:** Pre-market quote shows no fresh print (last_non_reg_trade_price
  identical to Friday's final regular-session trade) — effectively no pre-market liquidity yet,
  bid/ask abnormally wide ($54.73/$59.97).
- **Verdict:** Not a candidate — no reliable pre-market signal to act on.

---

## Small-cap-tech shortlist
Technology sector pre-market scan (scan_id 4ab9bad9) returned **zero matches** this build.
Nothing to add.

## Today's earnings (2026-10-19) — actuals as of 8am true-up, before the open unless noted

| Ticker | Est. EPS | Actual EPS | Pre-market reaction | Notable? |
|---|---|---|---|---|
| **CLF** | $0.24 | $0.28 — beat | **+11.5%** | **Yes — candidate #1** |
| **FITB** | $0.87 | $1.13 — big beat | ~flat/-0.75% | Beat but down — see #4 |
| **VFS** | -$0.31 | -$0.53 — miss | ~flat/-1.6% | No — muted, already priced in |
| **CBZ** | $1.26 | $1.21 — small miss | No pre-market print | No — no liquidity yet |
| CCK, AERO, RMCF, AGNC, BOKF, RLI, HBCP, WTFC, SFBS, WASH, DX, RBB, ZION, KARO, WRB, WAL, FNB, SMBK, STLD, HCWC, IMMR | various | not yet reported (pm timing or unverified) | — | Pending/unchecked, mostly after today's close |

## Scheduled macro events
No major scheduled macro print identified for today as of this true-up. VIX ticked up overnight
(17.20 Friday → 18.81 this morning) — a mild caution signal, not a confirmed shock. No FOMC,
CPI/PPI, or jobs data flagged for today.

## Overseas session carry-over (Step 3)
Asian and European overnight sessions were not specifically checked for name-level news (no
equity-news tool available this session to search). SPX/NDX readings above reflect Friday's
regular-session close only — no live pre-market index tick exists for either; VIX's reading is
fresh and is the only overnight-tone signal directly observed.

## Sources used in this build (8am true-up, 2026-10-19)
- `get_equity_positions` — Step 0 check, zero open positions, nothing to defend.
- `get_equity_quotes` (AAOI, COHR, SPY, CLF, VFS, CBZ, FITB) — all pre-market figures above vs.
  official Friday close.
- `get_indexes` / `get_index_quotes` (SPX, NDX, VIX) — overnight tone read; SPX/NDX are
  Friday-close carryover, VIX is a fresh pre-market print.
- `get_earnings_calendar` (today, 1-day window) — confirmed actuals for CLF/FITB/VFS/CBZ and
  the pending after-close list.
- `run_scan` (Technology sector, scan_id 4ab9bad9) — zero matches.
- `get_option_chains` / `get_option_instruments` / `get_option_quotes` (CLF, AAOI) — CLF $14C
  11/06 passes all three preliminary structural checks; AAOI $80C 11/06 fails on premium vs. the
  current ~$295 sizing cap.
- No `get_equity_news` tool available this session (confirmed again) — AAOI/COHR catalyst check
  and all "no catalyst found" verdicts rely on price action only.
