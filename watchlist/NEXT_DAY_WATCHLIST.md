# Next-Day Watchlist — built Monday evening, 2026-11-23 (for Tuesday, 2026-11-24)

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.** Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as an actionable candidate. Asian/European overnight-session news has NOT been checked yet at this hour — that's the job of Tuesday's ~8am overnight true-up.

## Step 0 — held position check

No stock or options position held as of this run (confirmed fresh: `get_equity_positions`). Nothing to defend.

## Market close — the broad rally held and extended through the whole session

SPX ~7250, NDX ~26,750, VIX 26.62 (close) — the best levels of the entire de-risking episode, and today's rally **extended into the close** rather than fading, a meaningfully different pattern from the gap-and-fade moves seen earlier last week. VIX has now pulled back for a second straight session (35.89 Fri close → 31.61 Mon 8am → 26.62 Mon close). This is the strongest two-day stretch of the whole stabilization attempt so far.

## COHR/AAOI — explicit user turnaround watch, stood down for the day per user instruction

Both spent most of Monday's session failing to hold a base (three separate failed-base attempts on COHR specifically — $212.29→$225.67→breakdown, $217-218.50 consolidation→breakdown to $215.24, then continued chop) despite the broader market rallying hard all day — a real divergence worth tracking. User explicitly said "stand down for today... let's revisit in AM" after the third failed attempt. User's own read: *"think it's oversold, but need broad agreement to make that pay."*

**COHR**: regular close $215.74 (+15.3% vs Fri's $187.22), after-hours last $219.30 (bid/ask $218.85/$219.83) — a further **+1.65% AH**, modest continued firming, not a big move either way.
**AAOI**: regular close $38.68 (+17.5%), AH last $39.40 (bid/ask $39.30/$39.42) — **+1.86% AH**, similar modest continuation.

Neither shows a dramatic AH move. Tuesday 8am needs to check: (1) is the broad rally still holding into a second day, not just one green session, and (2) does COHR specifically show a real base now, not another failed attempt. Per the user's own framing, both conditions need to align before this pays off.

## Today's real catalyst, missed during market hours: ZS earnings beat

**ZS (Zscaler, $31.8B cap)** reported **before the open** today — EPS $1.23 vs $0.95 est., a big beat — confirmed via `get_earnings_calendar` (`report.verified=true`, `eps.actual` populated). This was the actual catalyst behind ZS's intraday scan appearances (+15.6% close, $225.35) that got marked "no catalyst found" during today's 11am/12pm/3pm cycles — **those cycles didn't cross-reference the earnings calendar against scan hits, a process gap worth fixing tomorrow:** check `get_earnings_calendar` for any scored candidate before concluding "no catalyst," not just WebSearch. ZS closed +15.6% and is **still climbing after hours**: last $229.30 (bid/ask $229.98/$230.75), **+17.8% from Friday's close, +1.75% further AH on top of the regular session**. Clean beat, clean continuation, real catalyst, large-cap, genuinely liquid. By tomorrow morning this will be ~24 hours past the catalyst — re-verify it hasn't already fully played out before treating as fresh, per the standing don't-chase judgment.

**KYMR (Kymera Therapeutics, $9.8B)** also continued climbing hard today (close $150.24, +30.3%; AH last $155.00, bid/ask $154.25/$157.00, **+34.4% total from Friday**) — still no confirmed catalyst found via `get_earnings_calendar` (not in today's reporting list) or WebSearch. Flag as "no catalyst found — exceptional price action, unexplained" for tomorrow's research budget; do not score without confirmation.

## Tonight's broader earnings slate — mixed reactions despite the strong tape

| Ticker | Result | AH move from regular close | Read |
|---|---|---|---|
| **A** (Agilent) | Beat: $1.86 vs $1.73 | **+7.1%** ($176.26→$188.70) | Strongest, cleanest reaction tonight — beat + continued AH strength. Top candidate for tomorrow, pending fresh options chain check. |
| **AMTM** | Beat: $0.71 vs $0.65 | **+5.6%** ($20.62→$21.78) | Good follow-through, smaller/less liquid name. |
| **CRWD** | Beat: $0.34 vs $0.31 | Regular session **-8.9%** ($229.44→$208.96), AH +1.5% off the lows ($212.00) | Beat but punished hard in the regular session (likely guidance-related) — the one real "beat crushed" case tonight despite the otherwise strong tape. Worth checking guidance commentary before considering either direction. |
| **HPE** | Beat: $1.43 vs $1.27 | **-7.6%** ($48.29→$44.60) | Faded hard after-hours despite the beat and a big (mostly macro-driven) regular-session gain. |
| **SMTC** | Beat: $1.17 vs $1.09 | -3.8% ($104.86→$100.89) | Same fade pattern as HPE. |
| **ZM** | Beat: $1.59 vs $1.39 | ~flat (-0.3%) | Muted. |
| **J** (Jacobs) | Beat: $2.20 vs $2.12 | ~flat (-0.4%) | Muted. |
| **DAC** | Beat: $8.32 vs $7.06 | ~flat | Muted. |
| **CENT/CENTA, FSCO, CDLR, CVAC** | Small-cap/unclear, not checked for AH reaction | — | Low priority, skipped this pass. |

**Freshness confidence:** all verified today. A/AMTM are the standouts for continuation; CRWD is the standout for caution.

## Tuesday 2026-11-24 scheduled earnings — a big retail/tech day

**Before the open (am):** DLTR, ANF (Abercrombie), BBY (Best Buy), KSS (Kohl's), DKS (Dick's Sporting Goods), BURL (Burlington), MDT (Medtronic), ADI (Analog Devices), DY, SJM, BILI, CMBT, KC, BWLP, WNGRF, MMED — a genuinely large pre-market retail-earnings slate, several well-known large caps (BBY, DLTR, KSS, DKS, BURL, ANF, MDT, ADI).
**After the close (pm):** WDAY (Workday), NTNX (Nutanix), AMBA, ADSK (Autodesk), HPQ, DELL, CLSK (crypto-related — note this is a held-complex name, not a new catalyst for Tuesday's open but relevant for Wednesday), URBN, BBAR.

**This is a much busier earnings morning than Monday's — the retail complex (BBY/DLTR/KSS/DKS/BURL/ANF) reporting together will be a real tell on consumer spending heading into the holiday season.** Worth checking each for verified results and AH-equivalent reaction at the 8am true-up.

## Options read (PRELIMINARY, NOT LIVE — re-verify everything fresh at the open)

Not checked this pass — none of tonight's candidates were ranked firmly enough yet (A/AMTM are fresh AH reactions needing a regular-session re-verify first; COHR is on explicit stand-down). Check A's chain first at the 8am/9:40am pass if its AH strength holds — large, liquid name, clean beat, good continuation.

## Ranking for Tuesday's open

1. **A (Agilent)** — cleanest, strongest reaction tonight (beat + AH follow-through). Top candidate to re-verify fresh at the open — confirm the gap holds and isn't already fully priced by the time of the 9:40am check.
2. **COHR** — still the user's explicit turnaround watch. Needs both the broad rally to hold a second day AND its own genuine base (three failed attempts Monday). Stood down for today; revisit at 8am per explicit instruction.
3. **AMTM** — good AH follow-through, smaller/less liquid, lower priority than A.
4. **ZS** — real, confirmed, large catalyst but already ~24hrs old and extended (+17.8%) by tomorrow morning — likely too extended to chase per the don't-chase judgment; re-verify structure before dismissing entirely.
5. **AAOI** — same stand-down status as COHR; dilution thesis-invalidation still stands independently.
6. **The retail earnings slate (BBY/DLTR/KSS/DKS/BURL/ANF)** — not yet reported, pure research placeholder; 8am true-up needs to check each once results land.
7. **CRWD** — flagged for caution, not opportunity; a beat that got punished hard is worth understanding (guidance?) before treating either direction as a signal.
8. **KYMR** — exceptional, unexplained move; no catalyst found, do not score without confirmation.

**Standing reminders for Tuesday:**
- **COHR stand-down lifts at 8am** — explicit user instruction to revisit fresh tomorrow morning, checking both broad-market follow-through and COHR's own structure before any entry. The $500 size / -3% to -5% stop / autonomous-execution authorization from today still applies once a genuine base is confirmed.
- **Process note:** cross-check `get_earnings_calendar` against every Step 4 scan hit before concluding "no catalyst found" — ZS's real earnings catalyst was missed today because this cross-check wasn't done during the day cycles.
- **VIX has now eased two sessions running (35.89 → 31.61 → 26.62)** — the most sustained improvement of the whole episode. Still needs a second day of the broad rally holding (not just today) before this is unambiguous "footing."
- Tuesday's retail earnings slate (BBY/DLTR/KSS/DKS/BURL/ANF) is a genuine consumer-spending tell — worth extra attention at the 8am true-up.
- Next week's PCE inflation report remains the next scheduled macro catalyst.
