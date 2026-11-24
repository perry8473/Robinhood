# Next-Day Watchlist — trued up Tuesday 8am, 2026-11-24

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.** Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as an actionable candidate.

## Step 0 — held position check

No stock or options position held as of this run (confirmed fresh: `get_equity_positions`). Nothing to defend.

## 8am true-up — the headline is a broad retail-earnings beat morning, not COHR

**VIX ticked UP overnight: 26.62 (Mon close) → 28.77 (Tue 8am)** — the first reversal after two straight sessions of improvement. Not alarming on its own (still well off the 35.89 Friday high) but it breaks the clean "footing" narrative — worth confirming at the open whether this is just pre-earnings-morning jitters or a real risk-off tick. SPX/NDX pre-market levels weren't available live via this tool (stale index quotes) — re-check at 9:40am.

**COHR/AAOI — stand-down continues, no new catalyst found.** COHR pre-market $207.83 vs Monday's $215.81 close = **-3.7%**, reversing Monday night's modest AH firming. AAOI pre-market $38.80 vs $38.70 close ≈ flat. WebSearch turned up nothing dated to today for either name — no fresh news, just the same pattern of large unexplained swings this pair has shown for months (per search results, moves with "no stock-specific catalyst" are common for this trio). This pullback works **against** the "revisit in AM" turnaround thesis, not for it — COHR still hasn't shown the "slide-ends-and-re-climbs" structure the user asked for, and now it's also moving against the market's generally strong tone this morning. **Recommend treating COHR as still not ready** — no base, and now also underperforming a good tape. Will re ávaluate live at 9:40am once real price action starts, but the premarket data doesn't support lifting the stand-down yet.

**A (Agilent) — holding its gain, still the cleanest setup.** Pre-market $188.70, matching Monday night's AH peak — no overnight fade, no overnight extension either. Clean continuation of the beat+raise reaction. Still top of the list pending a live Step 6 price-structure check at the open.

**ZS — flat overnight, not extending further.** Pre-market $229.25 vs $229.24 close. Confirms the "likely too extended to chase" read from last night; the catalyst is now ~24hrs old with no fresh follow-through energy.

**KYMR — still climbing, still no catalyst.** Pre-market $157.88, **+5% further** on top of Monday's +34% move. No earnings-calendar entry, no news found. Remains a pure watch-only curiosity, never a candidate without a confirmed catalyst.

**PDD — pulling back.** Pre-market $85.02 vs $87.14 close, -2.4%. Not on today's active list regardless.

### The real story: a sweeping, broadly positive retail-earnings morning

Nearly the entire retail slate flagged last night reported before the open and **beat**, with large, genuine premarket reactions — all verified via `get_earnings_calendar` (actual EPS populated, not just estimates):

| Ticker | EPS actual vs est. | Premarket move | Read |
|---|---|---|---|
| **DKS** (Dick's) | $1.94 vs $1.38 | **+17.9%** | Biggest beat, biggest reaction. |
| **ANF** (Abercrombie) | $3.42 vs $3.10 | **+11.8%** | Big, clean beat and reaction. |
| **KSS** (Kohl's) | $1.76 vs -$0.01 | **+8.7%** | Est. was negative — a real turnaround surprise. |
| **DLTR** (Dollar Tree) | $1.16 vs $0.89 | **+7.9%** | Large beat (+30%), strong reaction. |
| **BBY** (Best Buy) | $1.62 vs $1.49 | **+6.2%** | Solid beat and reaction. |
| **BURL** (Burlington) | $1.73 vs $1.67 | **+5.9%** | Smaller beat, still a clean positive reaction. |
| **MDT** (Medtronic) | $1.34 vs $1.33 | **-3.3%** | In-line, but sold off — likely guidance concern, diverges from the sector. |
| **ADI** (Analog Devices) | $4.06 vs $3.89 | **-9.5%** | Beat the number but hit hard — guidance/outlook disappointment, the sharpest divergence of the morning. |

**This is a much bigger, more actionable development than anything on last night's board.** Six large, liquid retail names gapping 6-18% on confirmed beats is a genuine broad-sector tell on consumer spending heading into the holidays — exactly the kind of fresh, same-morning, high-conviction catalyst the 9:40am opening-bell cycle exists to catch. Two things to weigh before chasing any of these at 9:40: (1) pre-market gaps this large mean a chunk of the move is already priced in before the bell — the don't-chase judgment still applies, just against today's open rather than yesterday's; (2) MDT and ADI falling despite beating is a useful divergence signal — not every "beat" in this tape is being rewarded, so read each name's own guidance commentary, don't assume sector momentum carries every ticker.

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

## Ranking for Tuesday's open (updated 8am true-up)

1. **DKS / ANF / KSS / DLTR / BBY / BURL (retail beat complex)** — fresh, same-morning, confirmed catalysts, large and liquid, broadly positive. Top priority for the 9:40am live structure check. Treat each independently, not as one basket — confirm the gap isn't fully priced before the bell and read guidance commentary on each before sizing.
2. **A (Agilent)** — still clean, holding its +7% gain overnight with no fade. Re-verify fresh at the open; still a strong, lower-drama alternative to the retail names' bigger gaps.
3. **MDT / ADI (divergence watch)** — both beat but sold off premarket; not long candidates, but worth understanding why (guidance?) since it's a useful tell on how selective this tape is being with "beats."
4. **ZS** — flat overnight, confirms "too extended to chase" from last night. Low priority.
5. **COHR** — stand-down **not lifted**. Premarket pullback (-3.7%) and no new catalyst found work against the turnaround thesis. Needs live price action to even reconsider; do not treat the 8am data as sufficient to act.
6. **AAOI** — same stand-down status as COHR, flat overnight.
7. **KYMR** — still climbing, still zero catalyst found (earnings calendar + WebSearch both checked). Watch-only, never score without confirmation.
8. **PDD** — pulling back premarket; not an active candidate.

**Standing reminders for Tuesday:**
- **COHR/AAOI stand-down is NOT lifted by this 8am data** — the user's "revisit in AM" instruction has been honored (checked fresh), but both the market-direction read (VIX ticked up) and COHR's own action (-3.7% premarket, no base) argue for continuing to wait, consistent with the user's own caveat: *"think it's oversold, but need broad agreement to make that pay."* Re-check live at 9:40am before fully closing the door.
- **VIX reversed overnight (26.62 → 28.77)** after two sessions of improvement — don't treat the de-risking narrative as settled; confirm at the open whether this is pre-earnings jitters or a real shift.
- **Process note (standing):** cross-check `get_earnings_calendar` against every Step 4 scan hit before concluding "no catalyst found" — this caught the retail beats cleanly this morning; keep doing it every cycle.
- **The retail earnings complex (DKS/ANF/KSS/DLTR/BBY/BURL) is today's real opportunity**, not COHR — a broad, confirmed, same-day catalyst across liquid large caps. This wasn't anticipated at last night's 6pm build; treat it as the primary focus of the 9:40am opening-bell cycle.
- Next scheduled macro catalyst: PCE inflation report, date to be confirmed — no reliable dated confirmation found this morning; re-check calendar sources closer to the date.
