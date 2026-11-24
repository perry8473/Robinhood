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

## 3pm cycle — day closes with COHR/AAOI confirmed weak all session; retail leaders faded from midday highs (validates the no-chase call)

SPX 7173.19, NDX 26096.90, VIX 27.39 (ticked back up from 12pm's 26.36 — a choppy, not-fully-settled afternoon). Crypto still broadly red (COIN -5.3%, MSTR -7.3%, CLSK -6.9%, CORZ -11.8%).

**COHR closed out the regular session around $194.70, -9.8% — its worst level of the day, not an improvement.** LITE -10.9%, FN -10.9%, CIEN -8.8% — the whole group stayed deep red the entire session with no recovery. **This is a full trading day of confirmed, sustained weakness, not a one-off gap — the "oversold bounce" thesis needs to be weighed against a second straight day of real group-wide selling, not just stale weekend-old price levels.** Tomorrow's AM review should treat today as incremental evidence against the thesis, not neutral.

**Retail complex: ANF/KSS/DKS/BURL all pulled back meaningfully from their midday highs into the 1-3:30pm window** (ANF $178→$171, KSS $25.15→$24.39, DKS $157→$154, BURL $260→$253) — a textbook flat-top-then-fade pattern. This retroactively validates the 12pm "too extended, don't chase" call: anyone entering at the midday highs would be underwater into the close. Still finished the day up big (ANF +22%, KSS +15%, DKS +15.4%, BURL +7.6%) — real, large moves, just not ones this process could respectably enter today given the WebSearch corroboration gap (never resolved, 4 attempts) and the extension itself. ADI kept sliding, -16.9% by 3pm.

No trade taken this cycle either. End-of-day wrap for tonight's after-hours build: the retail-earnings story was today's real catalyst but the window to act on it responsibly never opened for this account (confirmation gap + extension); COHR/AAOI stand-down enters tomorrow having been reinforced, not weakened, by today's full session.

## 12pm cycle — retail complex now too extended to chase; market recovered; stand-down holds

Market recovered meaningfully: SPX 7212.91, NDX 26300.82, VIX 26.36 (down sharply from 11am's 28.78 — back near Monday's close level). Crypto still broadly red but less so (COIN -4.6%, MARA -5.5%, RIOT -7.7%, CLSK -9.4%, CORZ -11.7%).

COHR -8.2% (improved slightly from -10.4%), AAOI +0.8% (first positive reading of the day), LITE/FN/CIEN -8 to -10% (all improved slightly but still deep red) — stand-down holds, no real base yet despite the bounce off the worst levels.

**Retail complex kept extending through midday with no pullback: ANF +25.3%, KSS +18.6%, DKS +17.5%, BURL +10.5%, BBY +4.5%, DLTR +11.8% (flattening).** A 4th WebSearch attempt (broad "retail stocks surge" query) still found no dated same-day corroboration — confirmed index-lag, not a real doubt about the event. **At this point the extension itself (3+ hours in, 10-25% already realized, no pullback/base) is the controlling reason to stand aside, regardless of the catalyst-corroboration technicality** — don't-chase judgment applies squarely. ADI continued sliding to -16.3% (confirmed showing up on the options-flow scan too, elevated options activity) — a real, large guidance-driven move, not actionable long but notable.

AMTM (+20.6% today, $5.05B) is extending its Monday-night earnings beat into a second day — not deep-dived this cycle, flagged for the 3pm cycle if still active. Several new small/micro-cap scan hits (COGT, BBIO, PINS, TEX, FLNC + a cluster of sub-$500M healthcare names) not individually researched this cycle — mostly no catalyst found on quick inspection or too illiquid/thin (e.g. YFOR $135K market cap, GLXG $4.7M). No trade taken.

## 11am cycle — retail complex structure is clean, but catalyst corroboration gap flagged

COHR deepened further to ~$193 (-10.4% intraday, continuing straight-line lower highs/lower lows all morning — no base at all). LITE -11.2%, FN -11.9%, CIEN -9.7%, AAOI roughly flat (-0.8%) — group now down double digits. Stand-down confirmed correct again. Broader market also softened (SPX 7154, NDX 26020, both down from the 9:40 open; VIX 28.78, back up to the 8am level) and crypto is broadly red (COIN -5%, MARA/RIOT -9-10%, CLSK/CORZ -12%) — some of today's optoelectronics weakness may be beta to a mildly risk-off tape, not purely sector-specific, but the magnitude (double digits) still argues for genuine name-specific weakness on top of that.

Retail-earnings complex: DKS shows the cleanest structure of the day — a steady, orderly grind with higher lows all morning (151.19→154.59), tight range after the initial spike, near session highs. ANF broke out further to +23.8% with a clean stair-step (base, breakout, small pullback, hold). KSS/DLTR orderly but choppier. **However: ran a dedicated WebSearch check (3 queries) for same-day news corroboration on DKS specifically — found nothing dated to today, only historical/mismatched results.** Per the standing CATALYST CONFIRMATION MANDATORY rule, an earnings catalyst needs BOTH a verified `get_earnings_calendar` entry (have this — actual EPS populated, verified=true for all of DKS/ANF/KSS/DLTR/BBY/BURL) AND a corroborating news source (don't have this — WebSearch hasn't indexed today's reaction yet, a known same-day lag issue). **Not auto-scoring any of today's earnings names this cycle on that technicality, despite clean structure and verified EPS data** — will retry the news corroboration at 12pm/3pm as search indexing catches up. No trade taken.

Other scan hits (INSM, BBIO, COGT, TEX, ALTG, LVWR, AKAN, BDRX, APUS, EMBC): EMBC has a real verified earnings beat ($0.72 vs $0.29 est) but same WebSearch-lag issue, small-cap, not deep-dived this cycle. All others: no catalyst found or too illiquid/small (several sub-$10M microcaps showing classic thin-float pump patterns). Nothing scored.

## 9:40am opening-bell cycle — sector check result: group is WEAKENING, not basing

Live 5-min bars in the first 10 minutes of trading (9:30-9:40am ET): **COHR broke down further to ~$200** (open $209.67 → $199.96, now -7% intraday, a new low for this entire multi-day move, through Monday's $212.29 low). **LITE -6.7%, FN -6.4%, CIEN -6.4%** — the whole optoelectronics/networking-optical peer group is extending its losses, not reversing. AAOI is choppy (spiked to $41.05, pulled back to $39.49) — no clean signal either way, and a single noisy name doesn't satisfy the "coordinated group floor" bar. **Verdict: the sector check the user asked for comes back negative — this is continued group-wide weakness, the opposite of the entry signal we're watching for. COHR stand-down stays in force; no basis for AAOI either.** Re-check at 11am.

**Retail earnings complex, first 10 minutes:** KSS, DLTR, BURL show clean, steady uptrends (not spike-and-fade) — best structure of the group so far. DKS and ANF both spiked hard then gave back a meaningful chunk (ANF: premarket ~$167 → opened $158.89 → spiked to $171.98 → now $170.83; DKS: opened $148.76 → spiked to $155.78 → now $152.18) — more volatile, chasier. BBY V-shaped (dipped then recovered). ADI continues breaking down (-15% now, worse than premarket -9.5%) — confirms the outlook-disappointment read. **Only 10 minutes of data — too early to call a real entry per Step 6; re-check at 11am before sizing anything.** INSM (+14.2%, large-cap, $32.7B, biotech) appeared on the large-cap-movers sweep but no catalyst found (no earnings this week, no dated news) — flagged "no catalyst found," not scored. KYMR still extending (+12% more) with zero catalyst found across two days of checking — remains watch-only.

## COHR/AAOI — user adds a 52-week-range framing, wants a sector-wide tape check before entry (late 8am)

User's observation, verified: COHR and AAOI (and the whole optoelectronics/networking-optical complex — LITE, FN, CIEN checked as peers) are trading **much closer to their 52-week lows than their 52-week highs**, a genuine structural fact, not just impression:

| Ticker | 52wk low (date) | 52wk high (date) | Premarket | % up from low (of range) | % down from high |
|---|---|---|---|---|---|
| COHR | $142.46 (2025-11-25) | $440.00 (2026-06-03) | ~$206.80 | 21.6% | -53% |
| AAOI | $20.63 (2025-11-24) | $233.67 (2026-05-13) | ~$38.82 | 8.5% | -83% |
| LITE | $266.01 (2025-11-24) | $1143.00 (2026-10-09) | ~$515.42 | 28.4% | -55% |
| FN | $280.01 (**2026-11-20, 4 days ago**) | $748.89 (2026-05-14) | ~$313.00 | 7.0% | -58% |
| CIEN | $182.18 (2025-11-24) | $637.51 (2026-06-03) | ~$253.70 | 15.7% | -60% |

Several of these 52-week lows were set almost exactly a year ago (not fresh), but **FN just printed a new 52-week low four days ago** — this whole group has been under sustained pressure, not just COHR/AAOI in isolation. User's thesis: beaten-down-far-more-than-broader-tech + still-promising-upside = worth considering entries today, **contingent on watching what the optoelectronics group does generally first**, with disciplined stop management to cap downside if wrong.

**Live premarket read as of ~8am (before this can be acted on): the whole group is DOWN this morning, not showing sector strength.** COHR -4.2%, LITE -5.3%, FN -4.9%, CIEN -4.2%, AAOI roughly flat (+0.3%). This is a weak tape for the group right now, not a green light — consistent with the earlier finding that COHR/AAOI pulled back overnight with no fresh catalyst. **Plan: watch the sector as a group (not just COHR/AAOI) through the open and the day's scheduled cycles (9:40/11/12/3) for a real floor/reversal forming across multiple names together — that's a much stronger signal than COHR alone bouncing, since these names are known to move together (per WebSearch history, swings in this group are often described as having "no stock-specific catalyst," i.e., sector/sentiment-driven).** Only consider an entry once the group shows coordinated strength, not before. If pursued, size and stop discipline follow the user's existing framework (~$500 range, tight stop, standing autonomous-execution authorization for this specific setup once conditions are met).

**Standing reminders for Tuesday:**
- **COHR/AAOI stand-down is NOT lifted by this 8am data** — the user's "revisit in AM" instruction has been honored (checked fresh), but both the market-direction read (VIX ticked up) and COHR's own action (-3.7% premarket, no base) argue for continuing to wait, consistent with the user's own caveat: *"think it's oversold, but need broad agreement to make that pay."* Re-check live at 9:40am before fully closing the door.
- **VIX reversed overnight (26.62 → 28.77)** after two sessions of improvement — don't treat the de-risking narrative as settled; confirm at the open whether this is pre-earnings jitters or a real shift.
- **Process note (standing):** cross-check `get_earnings_calendar` against every Step 4 scan hit before concluding "no catalyst found" — this caught the retail beats cleanly this morning; keep doing it every cycle.
- **The retail earnings complex (DKS/ANF/KSS/DLTR/BBY/BURL) is today's real opportunity**, not COHR — a broad, confirmed, same-day catalyst across liquid large caps. This wasn't anticipated at last night's 6pm build; treat it as the primary focus of the 9:40am opening-bell cycle.
- Next scheduled macro catalyst: PCE inflation report, date to be confirmed — no reliable dated confirmation found this morning; re-check calendar sources closer to the date.
