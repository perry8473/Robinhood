# Next-Day Watchlist — built Thursday evening, 2026-11-19 (for Friday, 2026-11-20)

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.** Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as an actionable candidate. Asian/European overnight-session news has NOT been checked yet at this hour — that's the job of the ~8am overnight true-up routine. **Standing user instruction currently in effect: no new entries without explicit discussion/approval, regardless of score.**

## Step 0 — held position check

No stock or options position held as of this run (confirmed fresh: `get_equity_positions`). Nothing to defend.

## Headline overnight development — broad, tech-led market rout; this dominates everything below

**Today was a genuine risk-off event, not routine noise.** VIX closed/is reading ~28.44, up ~15.8% on the day (from Wednesday's 24.56 close) — the sharpest single-day VIX move of the week. Market commentary (Benzinga, Interactive Brokers' Steve Sosnick) describes an "AI-driven market rout" that wiped roughly $2.2 trillion off U.S. equity value, tech-sector weakness, monetary-policy concerns, and a key S&P 500 support level breaking that accelerated the selling. No single clean catalyst — a broad de-risking event. **This is the dominant fact for tomorrow: individual stock catalysts tonight are secondary to whether this macro rout continues, stabilizes, or reverses.** Re-verify SPX/NDX/VIX fresh at the open before treating anything below as a real setup.

## Tonight's earnings reactions — macro overwhelmed almost every single-name result

A striking pattern: **beats got crushed just as hard as misses tonight**, which is itself informative — the market is punishing exposure/valuation, not differentiating on fundamentals right now.

| Ticker | Result | AH reaction | Read |
|---|---|---|---|
| **PDD** | Beat big: $3.14 vs $2.69 est. (dated 11/19 am, verified) | **Closed regular session +11.0%** ($85.97 vs $77.45 prior close) — held its gain through the entire broad-market selloff | **Standout relative strength** — the one name that didn't get dragged down by the macro story today. Worth a fresh look at tomorrow's open, but re-verify structure given today's violent whipsaw (see 3pm cycle report: opened $82.44, spiked to $87.4, faded to $85.5 by 3pm, closed $85.97). |
| **INTU** | Beat big: $2.91 vs $2.61 est. | **-10.8% AH** ($279.46 vs $313.24 close) | Clean beat, brutal reaction — pure macro/valuation unwind, not a company-specific negative. Don't treat as a short thesis on fundamentals; don't treat a bounce as a long thesis either without the broader tape stabilizing first. |
| **ESTC** | Beat huge: $0.94 vs $0.68 est. (+38%) | **-8.6% AH** ($75.87 vs $83.01 close) | Same pattern as INTU — fundamentals point one way, tape points the other. |
| **ROST** | Beat: $1.91 vs $1.85 est. | **-8.2% AH** ($209.00 vs $227.64 close) | Same pattern. |
| **GAP** | Beat: $0.86 vs $0.76 est. | -2.0% AH | Milder version of the same pattern. |
| **KEYS** | Beat: $3.61 vs $3.32 est. | ~flat/-0.4% AH | Smallest reaction of the beat group — closest to a "normal" muted response. |
| **WMG** | Beat: $0.55 vs $0.42 est. | ~flat AH | Similarly muted. |
| **NTES** | Miss: $2.12 vs $2.49 est. | **-10.1% AH** ($106.49 vs $118.43 close) | Miss AND crushed — the one name tonight where the reaction actually matches the fundamental result. |
| **BABA** | Miss: $1.21 vs $1.64 est. | -0.7% AH (modest) | Miss but mild reaction — notably calmer than NTES despite a similar-sized miss. |

**Freshness confidence:** All of tonight's earnings catalysts are fresh (today, dated, verified via `get_earnings_calendar` with `eps.actual` populated). But given the macro override described above, freshness of the catalyst doesn't translate cleanly into freshness of a tradeable signal tonight — the open tomorrow needs to separate "is the market stabilizing" from "is this specific name's move real."

## Friday 2026-11-20 scheduled earnings

**Before the open (am):** FRO, RLX, BSP, BKE, IESC, MOG.A, WRD, BJ — all smaller-cap/lower-impact names, none large enough to be a major macro driver on their own.
**No large-cap/high-market-cap reports found for tomorrow** (per `get_earnings_calendar` with `filter=high_market_cap`) — tomorrow's tape will be driven by broad macro follow-through, not a fresh earnings slate.

## Options read (PRELIMINARY, NOT LIVE — re-verify everything fresh at the open)

Not checked this pass — given the macro-dominated, no-entries-without-discussion posture tonight, the research budget wasn't spent on options chains for names whose stock-level signal is itself this uncertain. Re-evaluate PDD's options chain fresh at the open if its relative-strength setup still looks clean after the overnight true-up.

## Ranking for Friday's open

1. **PDD** — the one name showing genuine relative strength through today's rout. Top candidate to re-verify fresh at the open, but still just a candidate for discussion, not a pre-approved entry.
2. **INTU, ESTC, ROST** — real beats, brutal reactions; watch for either a dead-cat bounce or continued unwind, but the move tonight is about the macro regime, not these companies. Not proposing either direction as a trade idea without seeing how the open behaves.
3. **GAP, KEYS, WMG** — milder reactions, lower priority.
4. **NTES** — real miss, crushed; stays a pass, no reason to fade a miss that got the reaction it deserved.
5. **BABA** — miss, muted reaction; not a priority either direction.

**Standing reminders for tomorrow:**
- **No new entries without explicit user discussion/approval** — this overrides the standard autonomous-execution authority until the user says otherwise.
- The core question for the 8am true-up and 9:40am opening-bell cycle: is VIX continuing to climb (confirms the rout is ongoing) or easing back (signals today was a one-day flush)? That answer matters more than any single name's setup tomorrow.
- Tonight's "beats got crushed as hard as misses" pattern is a reminder that individual catalyst quality doesn't override macro regime — a repeat of this week's recurring lesson (TGT/LOW/WMT's muted reactions earlier in the week), now at a much larger scale.
