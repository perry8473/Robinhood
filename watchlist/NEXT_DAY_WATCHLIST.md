# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% pre-market and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** fresh build by the after-hours routine on 2026-10-06 (Tuesday close), fired
~6:06pm ET. Will be trued up by the ~8:00am overnight routine tomorrow (2026-10-07).

**News-tool status:** `get_equity_news` remains permanently unavailable in this toolset.
WebSearch continues as the standing substitute for catalyst verification — all catalysts below
are sourced that way, with specific articles cited where used.

**Options consideration (new 2026-10-06):** Off-hours routines now record a preliminary options
read on top candidates (listed chain + 7-30 DTE confirmed, premium vs. current sizing cap) —
explicitly NOT a live quote, re-verify fresh at the open. Options orders can only execute during
regular market hours (9:30am-4:00pm ET) regardless of what's recorded here.

**Tone at this build (2026-10-06, ~6:06pm ET):** Today was dominated by two sector-wide
sympathy rallies layered on top of individual earnings reactions — a nuclear/power basket (Google
signed a 20-year, ~3,590MW nuclear PPA with Constellation) and an AI-networking/optical basket
(Marvell's Investor Day optimism on interconnect TAM + bullish sell-side initiations). SPX closed
at a new record high; VIX ~15. Tomorrow's macro event: **FOMC September-meeting minutes at 2:00pm
ET** — the week's main event risk, ahead of Thursday's CPI print.

---

## Today's open positions (context, not pre-approved for new sizing)

- **AAOI** — 3 sh, avg cost $111.45, last $130.16 (+16.8%), extended-hours $130.29. Stop resting
  at $128.00/$126.72 (raised throughout today). Appears in the options-flow scan with decent
  liquidity (rel. options volume ~2.6x, IV ~86%) if a scale-in or options overlay is considered
  tomorrow — informational only, not a recommendation.
- **PCVX put (10/16 $65 strike)** — closed today for a realized loss (-28% vs. the -20%
  mandatory stop, late-session reversal outpaced the exit) with the account's resting-stop
  mechanism now a standing fix. No open options position.

---

## Ranked candidates

### 1. CIEN (Ciena Corp) — AI-networking, real catalyst, strongest continuation
- **Catalyst:** Marvell's Investor Day (Oct 6, NYC) projected the AI interconnect market growing
  to ~$65B by 2030 (60-70% CAGR), validating demand for optical-networking suppliers; compounded
  by bullish sell-side initiations calling AI networking a "bona fide mega boom."
  [TradingKey](https://www.tradingkey.com/news/market-movers/262202264-market-movers-cien-20261006)
- **Direction/magnitude:** Bullish. Closed regular session +13.8% at $443.66, and **kept
  climbing after hours** to $444.16 — the single strongest closing/AH profile of anything
  scanned today (most other movers faded or went flat into the close).
- **Freshness confidence:** High — catalyst is today's news, price action confirms genuine
  demand (closed at/near highs, extended further AH) rather than a spike-and-fade.
- **Disqualifiers:** Already up ~14% intraday by the time it was caught at the 3pm cycle —
  don't-chase judgment applies to large-caps too; needs a fresh basing structure at tomorrow's
  open, not an automatic gap-chase.
- **Options read:** Listed chain confirmed (expirations through 2029, including 10/16 = 10 DTE
  and 10/23 = 17 DTE, both in window). Specific ATM strike/premium not resolved this build
  (the $445 strike didn't exist in the instrument list — strikes are likely at non-round
  increments for a $440+ name); re-check the actual strike ladder and premium live at the open,
  but note CEG's $300 ATM call priced at ~$960/contract tonight (see #2) — a $440+ stock's ATM
  premium is very likely to exceed the ~$300 sizing cap too, so any options expression would
  need to go meaningfully OTM to fit, which may also fail delta/liquidity screens. Flag as
  likely FAIL on premium pending live confirmation.

### 2. CEG (Constellation Energy) — nuclear deal, direct counterparty, but already rolling over
- **Catalyst:** Google signed a 20-year, ~3,590MW nuclear PPA with Constellation (the Oct 6 deal
  driving the whole sector).
  [Benzinga](https://www.benzinga.com/markets/tech/26/10/62190391/google-constellation-energy-nuclear-deal-stocks-rally)
- **Direction/magnitude:** Bullish catalyst, but price action already rolled over intraday —
  peaked ~$309.80 around 12:30pm ET, faded to $298-300 by the close, extended-hours $295.68
  (further fade, not a recovery).
- **Freshness confidence:** Catalyst is fresh and durable (20-year contract), but the stock's
  reaction has already priced in the initial pop and is now fading — weak setup for tomorrow
  without a fresh basing session first.
- **Disqualifiers:** Rolling-over price structure; already extended; direct deal party but
  arguably the most "used up" name in the basket by end of day.
- **Options read:** Listed chain confirmed, 10/16 (10 DTE) in window. $300 ATM call: bid $9.50 /
  ask $9.70, mark $9.60 → **~$960/contract, well above the ~$302 sizing cap. FAIL on premium**
  at any ATM/near-ATM strike; a deep-OTM contract might fit the cap but would carry a low delta
  weak directional expression — not a clean fit for this account's sizing.

### 3. PENG (Penguin Solutions) — fresh earnings beat + raised guidance
- **Catalyst:** Q4 FY2026 earnings beat ($1.00 actual vs. $0.74 est.) reported after today's
  close, with raised FY2027 guidance citing continued AI-infrastructure/memory strength.
  [Investing.com](https://za.investing.com/news/stock-market-news/earnings-call-transcript-penguin-solutions-tops-q4-2026-estimates-shares-rise-93CH-4492686)
- **Direction/magnitude:** Bullish. Up +5.77% in the regular session (likely pre-report
  positioning/leak-adjacent drift) plus another +5.12% after the print, AH price ~$67.50.
- **Freshness confidence:** High — this is a same-day, same-report catalyst, the freshest of
  tonight's build, with explicit forward guidance (not just a beat) as the driver.
- **Disqualifiers:** Small-ish cap (~$3.1B) with a now ~11% two-session move already in; AH
  liquidity/price can be unreliable — must re-verify the gap holds at the actual open before
  treating as live.
- **Options read:** Listed chain confirmed (10/16 = 10 DTE in window). Specific ATM strike
  ($67.50) not found in this build's instrument pull — likely a strike-spacing mismatch at this
  price level; re-resolve the real strike ladder and premium live at the open. Given PENG's
  lower share price (~$67) versus CIEN/CEG, this name is the most likely of the three to
  actually fit the ~$302 sizing cap on a near-ATM contract — worth prioritizing for the live
  options-potential check tomorrow.

### 4. Nuclear/power sympathy basket (OKLO, VST, SMR, NXE, TLN, CCJ, LEU, XE, UUUU, UEC) — broad-basket, not individually scored
- **Catalyst:** Same Google/Constellation nuclear PPA — sympathy buying across advanced-reactor
  developers and uranium/fuel names, treated by investors as evidence of real demand for the
  next wave of projects.
  [24/7 Wall St.](https://247wallst.com/investing/2026/10/06/nuclear-stocks-rally-as-googles-reactor-deal-lifts-the-sector-nano-nuclear-energy-jumps-8-oklo-climbs-8-nuscale-power-gains-7/)
- **Direction/magnitude:** Bullish, broad (OKLO +8%, VST +10.8%, SMR +7%, several others +5-12%).
  OKLO/VST both continued higher into AH (OKLO AH $38.78 vs regular $38.58; VST roughly flat).
- **Freshness confidence:** Moderate — real underlying catalyst, but these are sympathy plays on
  someone else's news, not idiosyncratic. A second day of follow-through would strengthen the
  case; a single name with its own fresh catalyst inside this basket would rank higher.
- **Disqualifiers:** Broad-basket moves are explicitly excluded from individual high-confidence
  scoring per the standing framework — no single name here is a scored candidate tonight, this
  is a theme to watch, not a trade list entry.
- **Options read:** Not checked — basket entries aren't individually scored, so the research
  budget wasn't spent on options chains for every name. If any of these show a fresh, idiosyncratic
  catalyst of its own by tomorrow's open (not just basket momentum), run it through properly then.

### 5. OPCH (Option Care Health) — unchanged, capped merger-arb
- Still the McKesson/CD&R advanced-talks situation ($32.05/sh cash target), +32.7% today,
  holding flat into AH ($31.01 → $31.02). Same declining verdict as every prior cycle — binary
  completion risk, multi-month timeline, doesn't fit this account's momentum framework. Carried
  forward for continuity, not as a live candidate.

---

## Today's earnings reactions (after-close)

| Ticker | Est. | Actual | Reaction |
|---|---|---|---|
| PENG | $0.74 | $1.00 | Beat big, +5.1% AH (see #3 above) |
| STZ (Constellation Brands) | $3.56 | $3.74 | Modest beat |
| NEOG | $0.05 | $0.08 | Beat |
| SAR | $0.49 | $0.46 | Miss |
| AXIL | $0.13 | $0.05 | Miss |
| WS | $1.16 | $0.57 | Big miss |

No major after-hours price reactions found for the misses beyond normal noise — none rank as
tomorrow candidates.

## Tomorrow's scheduled earnings (2026-10-07)
No high-market-cap names reporting tomorrow per the calendar (RELL, LFS, APLD, LEVI, RGP, and a
handful of unverified small/micro-caps only, mostly "pm" timing). Nothing here moves the needle
for an opening-bell watchlist.

## Scheduled macro events
- **FOMC September-meeting minutes, Wed 10/7, 2:00pm ET** — the week's primary event risk.
  Minutes detail the unanimous rate-hike vote and may hint at guidance for the next meeting —
  watch for volatility into and after the 2pm release, though this lands well after the
  standing cycle times (9:40am/11am/12pm/3pm) are mostly done for the day.
- **CPI + initial jobless claims, Thu 10/8, 8:30am ET** — flagged for the next build.

## Small-cap-tech shortlist
Not run this build (Step 3b is the overnight true-up routine's job, ~8:00am ET). Will populate
tomorrow morning's true-up per standing process.

## Sources used in this build
- [Ciena Corp Stock (CIEN) Moved Up by 11.02%/13.8% on Oct 6 — TradingKey](https://www.tradingkey.com/news/market-movers/262202264-market-movers-cien-20261006)
- [Google Bets 20 Years On Constellation Reactors — Benzinga](https://www.benzinga.com/markets/tech/26/10/62190391/google-constellation-energy-nuclear-deal-stocks-rally)
- [Nuclear Stocks Rally as Google's Reactor Deal Lifts the Sector — 24/7 Wall St.](https://247wallst.com/investing/2026/10/06/nuclear-stocks-rally-as-googles-reactor-deal-lifts-the-sector-nano-nuclear-energy-jumps-8-oklo-climbs-8-nuscale-power-gains-7/)
- [Penguin Solutions tops Q4 2026 estimates — Investing.com](https://za.investing.com/news/stock-market-news/earnings-call-transcript-penguin-solutions-tops-q4-2026-estimates-shares-rise-93CH-4492686)
- [What to Look Out for in Economic Data This Week (October 5-9) — Kiplinger](https://www.kiplinger.com/investing/economy/this-weeks-economic-calendar)
