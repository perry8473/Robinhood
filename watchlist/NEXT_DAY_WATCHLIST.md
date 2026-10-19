# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% after-hours and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built fresh by the after-hours routine on 2026-10-19 (Monday close), fired
~6:06pm ET for tomorrow (2026-10-20, Tuesday).

**Step 0 (6pm) — held position defense check:** Only position is **CLF**, 21 sh @ $13.96 avg.
`get_equity_orders` confirms its regular-hours stop (was $12.90) expired at today's close as
expected (GFD) — no resting order right now. `get_equity_quotes` shows CLF trading
$14.00-14.15 after-hours (last non-reg $14.14), comfortably above both entry and the old stop
level. **No defensive action needed or possible to improve on** — nothing near the floor. A
fresh regular-hours stop will be re-placed at the next session (8am true-up safety-net check, or
9:40am opening-bell cycle at the latest).

**Account status:** One position — **CLF**, 21 sh @ $13.96 avg, ~$14.14 after-hours (+1.3%).
Cash ~$2,662. No options positions.

**Tone at this build (6pm):** Mildly positive. SPY $767.30-767.38 after-hours vs today's close
$766.54 (+0.1-0.2% drift). No overnight macro event identified yet at this hour.

---

## Ranked candidates (6pm build, 2026-10-20)

### 1. GE, RTX, NOC, MMM, HAL — tomorrow's big industrials/aerospace earnings wave (AM, before open)
- **Catalyst:** Q3 2026 earnings, all reporting before tomorrow's open: General Electric (GE,
  est. $2.01), RTX (Raytheon, est. $1.78), Northrop Grumman (NOC, est. $7.19), 3M (MMM, est.
  $2.39), Halliburton (HAL, est. $0.58). None have reported yet — all `eps.actual` still null as
  of this build.
- **Direction/magnitude:** Unknown — pending. This is the single biggest cluster of large-cap
  earnings reporting before tomorrow's open; flagging the cluster now so the 8am true-up and
  9:40am cycle know to check all five immediately once actuals post.
- **Freshness confidence:** N/A until actuals + pre-market reaction exist.
- **Disqualifiers:** None assessable yet — nothing to disqualify until there's a number and a
  reaction.
- **Options read:** Not checked — no reaction to evaluate against yet. Re-check live once
  earnings post pre-market.
- **Verdict:** Top priority for the 8am overnight true-up — check actuals and pre-market
  reaction on all five the moment they're available.

### 2. NFLX — tomorrow's after-close marquee earnings (PM, 2026-10-20)
- **Catalyst:** Q3 2026 earnings, est. EPS $0.82, reports after tomorrow's close (not tonight).
- **Direction/magnitude:** N/A yet — this is a heads-up for Wednesday's open, not tomorrow's.
- **Verdict:** Note for continuity; becomes relevant to the Tuesday 6pm build, not tomorrow
  morning.

### 3/4. IRON (Disc Medicine) / AMRO (Amaero) — continuing unconfirmed-catalyst momentum
- **IRON:** Friday close $56.84 → today's regular close $78.98 (**+39.0%**), now $77.6-78.1
  after-hours — holding most of the day's gain, pulling back slightly off the $80.22 intraday
  high. Still **no catalyst found (no equity-news tool available this session)** despite 3
  consecutive cycles of checking — the move's size and persistence suggest something is real
  (a trial/regulatory catalyst is likely for a biotech this size), but it remains unconfirmed.
  **Options disqualifier:** nearest listed expiration is 2026-11-20 — 31 DTE from tomorrow,
  just outside the 7-30 DTE preferred window. Options read: **FAIL (no expiration in 7-30 DTE
  window)**.
- **AMRO:** Friday close $4.50 → today's regular close $5.61 (**+24.7%**), extending further
  after-hours to $5.48-5.61. Also **no catalyst found**. **Options disqualifier: no listed
  options chain at all** (`get_option_chains` returned empty) — options read: **FAIL (no
  listed chain)**.
- **Verdict:** Both remain standing-watch momentum names, not scored candidates, given the
  catalyst can't be confirmed with the tools available this session. Re-check live at the open;
  if either is still extending cleanly with volume, it's a candidate for stock-only scoring (no
  options route exists for either regardless).

### 5. RLI, STLD, DX, AGNC, HBCP — today's after-close bank/financial earnings batch, no fresh setups
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

## Optoelectronic standing watch — AAOI / COHR (user standing interest, 6pm check)
- **AAOI:** today's regular close $78.26 → after-hours $78.24-78.68 (+0.5%) — continuing to
  extend modestly, still no fresh catalyst found.
- **COHR:** today's regular close $231.91 → after-hours $232.20-233.50 (~flat) — holding,
  no fresh catalyst found.
- Standing watch only, not a trade signal.

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

## Tomorrow's scheduled earnings (2026-10-20) — before the open ("am") unless noted

| Ticker | Est. EPS | Timing | Notable? |
|---|---|---|---|
| **GE** | $2.01 | am | **Yes — candidate #1 cluster** |
| **RTX** | $1.78 | am | **Yes — candidate #1 cluster** |
| **NOC** | $7.19 | am | **Yes — candidate #1 cluster** |
| **MMM** | $2.39 | am | **Yes — candidate #1 cluster** |
| **HAL** | $0.58 | am | **Yes — candidate #1 cluster** |
| SYF, KEY, UCB, VICR, GPC, MSCI, EFX, CBSH, AUB, VMI, ALLY, DCOM | various | am | Pending, second-tier — check live |
| COF, OZK, HWC, CB, QCRH, UAL, ELS, NLY, ISRG, ALK, GM, LRN, EWBC, HAS, **NFLX** | various | pm | After tomorrow's close — relevant to Wed 6pm build |

## Scheduled macro events
No major scheduled macro print identified for tomorrow as of this build. SPY drifting mildly
positive after-hours (+0.1-0.2%). Will be rechecked at the 8am true-up alongside SPX/NDX/VIX.

## Small-cap-tech shortlist
Not checked at this 6pm build (not yet run this cycle) — will be checked at the 8am true-up per
Step 3b. Continuity note: EXYN (Exyn Technologies) was flagged "already extended, not chasing"
earlier today per the DON'T-CHASE RULE — not carried forward as a live candidate.

## Sources used in this build (6pm, 2026-10-19)
- `get_equity_positions` / `get_equity_orders` (CLF) — Step 0 check, GFD stop expired as
  expected, no action needed or possible.
- `get_equity_quotes` (CLF, IRON, AMRO, SLN, AAOI, COHR, RLI, STLD, DX, AGNC, HBCP, SPY) — all
  after-hours figures above vs. official Friday close and today's regular close.
- `get_earnings_calendar` (today days=1, tomorrow days=1, both filtered and unfiltered) — all
  figures in the earnings tables above.
- `get_option_chains` (IRON, AMRO) — IRON fails DTE window (nearest expiration 31 DTE), AMRO has
  no listed chain at all.
- No `get_equity_news` tool available this session (confirmed again) — IRON/AMRO/AAOI/COHR
  catalyst checks and all "no catalyst found" verdicts rely on price action only.
