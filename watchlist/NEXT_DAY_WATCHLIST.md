# Next-Day Watchlist — build for Tuesday, 2026-11-03

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as a candidate. Built 6:05pm ET Monday 2026-11-02 (after-hours catalyst research), **trued up 8am ET Tuesday 2026-11-03** against overnight/pre-market action.
>
> **Standing instruction from the user Monday night: HOLD on LOAR/NXT/MGRC/ZG/CLRO — "let's hold... see what earnings reports bring and maybe sleep on those." Still in force this morning; none of these are to be treated as ready for action.**

## 8am true-up — Step 0 held position check
No stock or options position held (`get_equity_positions`/`get_option_positions` both confirmed empty). Nothing to defend. No action needed.

## Step 0 — held position defense check
`get_equity_positions` confirmed empty for account 787937630. Nothing to defend after-hours. TATT was closed out earlier today via its trailing stop (filled $36.12 vs. entry — realized loss -$5.04 / -1.7%); account is flat into Tuesday.

## Account state
Flat, fully in cash. Realized loss today: TATT stop-out, -$5.04 (-1.7%). Per the standing trailing-stop rule, this is a **clean stop-out — not to be chased for re-entry**, even though the underlying catalyst (see below) turned out to be real. Benchmark account (570898312, read-only, ETF buy-and-hold) tracked for comparison only — never traded.

## Key retroactive finding: TATT's catalyst WAS real — a tool-coverage lesson, not a thesis error
`get_earnings_calendar` for 2026-11-02 now shows **TATT beat Monday AM: EPS $0.58 actual vs. $0.43 est**, reported same day — this is the real, verified catalyst WebSearch failed to surface before entry. TATT closed the day $37.29 (+17.3% vs. Friday's $31.80), extending well past the level at which the position was stopped out intraday. This does not change the stop-out decision (the stop followed the standing trailing-stop rule correctly), but it's a reminder that "no catalyst found via WebSearch" is a **tool-coverage limitation**, not proof no catalyst exists — `get_earnings_calendar` with `eps.actual` populated remains the more reliable confirmation source this session. TATT itself stays excluded from re-entry (clean stop-out rule) regardless.

## Today's (2026-11-02) earnings slate — now mostly reported, actuals confirmed
**AM reporters (already reflected in today's price action):** TATT beat ($0.58 vs $0.43 — see above).
**PM reporters (after today's close — these are the fresh, relevant catalysts for Tuesday's open):**

| Ticker | Result | WebSearch corroboration |
|---|---|---|
| AAPL | Beat, $2.10 vs $1.98 est (per earnings calendar) | Not found — WebSearch surfaced only prior-year (FY24/FY25) Q4 reports; same-day-coverage gap persists |
| **ROKU** | **Big beat** — $1.20 vs $0.55 est (per earnings calendar); **independently corroborated**: SEC 8-K/shareholder letter shows Q3 revenue ~$1.5B (+24% YoY), above the ~$1.41B consensus, net income $183M, adj. EBITDA $249M | **Confirmed via primary-source SEC filing** — genuine news-source hit, not price action alone |
| PLTR | Beat, $0.44 vs $0.39 est | Not found |
| VRTX | Beat, $4.76 vs $4.70 est | Not found |
| ON | Beat, $0.90 vs $0.88 est | Not found |
| FANG | Beat, $5.86 vs $5.46 est | Not found |
| NBIX | Big beat, $3.29 vs $2.59 est | Not found |
| DOC, O | Beat | Not found |
| WMB, CRBG | Roughly inline | Not found |
| MTCH | Miss, $0.73 vs $0.98 est | Not found |
| JAZZ | Miss | Not found |
| GRAB | Not yet reported as of this build | — |

**ROKU is the one PM reporter with an actual news-source-confirmed beat tonight** — satisfies the mandatory catalyst-confirmation rule outright (eps/revenue beat + SEC-filing corroboration, not price action alone). The others remain earnings-calendar-only confirmations (reliable per tonight's TATT lesson, but not yet independently news-corroborated) — surfaceable for a live look at tomorrow's open, not yet auto-scorable under the strict rule.

## Tuesday 2026-11-03 earnings slate (large-cap, AM/PM)
PFE, YUM, ADM, BALL, AMGN, AMD, SHOP, BKNG, MPC, RACE, ANET, SMCI, ZBRA, WAT, ETN, and others — full slate pulled via `get_earnings_calendar(filter="high_market_cap")`. None of these report pre-open-relevant actuals yet; re-pull at the 9:40am cycle once AM actuals populate.

## Ranked candidates for Tuesday — by live-tradeable-setup likelihood

**#1 ROKU — fresh, independently-confirmed catalyst, reports after today's close**
- **Catalyst:** Q3 double beat, revenue ~$1.5B (+24% YoY) vs. ~$1.41B consensus, EPS $1.20 vs $0.55 est, positive operating income. Confirmed via `get_earnings_calendar` AND independently corroborated via SEC 8-K/shareholder letter — passes the mandatory catalyst-confirmation bar cleanly.
- **Direction/magnitude:** Bullish; no after-hours quote pulled yet tonight — **re-verify AH/pre-market price action and real (not thin) volume at the 9:40am cycle** before any scoring.
- **Freshness confidence:** High on the catalyst itself (double beat, first positive operating income since 2021 per sourcing); untested yet on price reaction — this is the key unknown for tomorrow.
- **Disqualifiers:** None yet identified; needs options-chain liquidity check, DTE window, and premium-vs-cap check live at the open. Not pre-approved.

**#2–#5 LOAR / NXT / MGRC / ZG — HOLD per explicit user instruction, still no catalyst found**
All four extended further after today's close, continuing a trend WebSearch could not explain at any point this session:
- **LOAR** $68.04 (+9.5% vs. Friday's $62.11 close)
- **NXT** $91.18 (+14.9% vs. $79.33)
- **MGRC** $129.44 (+9.5% vs. $118.28)
- **ZG** $32.91 (+3.2% vs. $31.89 — paring back from a larger intraday gain)
- **Catalyst:** None found via WebSearch on any of the four, consistent with every check run this session. Per the mandatory catalyst-confirmation rule, none of these can be auto-scored or auto-executed — no-catalyst status alone does not disqualify them from being surfaced, but **the user has explicitly instructed to hold and sleep on all four** pending tomorrow's fresh earnings reports and a clearer read. No action to be taken on any of these at tomorrow's open without a fresh conversation.
- **Micro-cap concurrency cap note:** none of these four are sub-$5/thin-float, so the micro-cap cap does not apply to them directly — the gating factor here is purely the user's explicit hold instruction.

**#6 CLRO — HOLD, still in chaotic/carve-out structure**
- $5.66 (+66% vs. Friday's $3.41), still showing volatility (non-reg last trade $5.78). This is the same name declined earlier today for a genuine spike-then-fade pattern even under the user's blanket "take swings at TATT and CLRO" approval — tonight's continued volatility reinforces that read. Also under the explicit hold instruction. No action tomorrow without a fresh re-evaluation of price structure.

**Flag — INO, completely unexplained, extreme move, approach with caution**
- INO closed/traded $1.90 vs. Friday's $0.6024 — **+215%**, by far the largest move of any tracked ticker tonight, and still entirely unexplained after repeated WebSearch attempts across the session. A move this size with zero confirmable catalyst is a textbook case for the mandatory catalyst-confirmation rule: it cannot be scored or auto-executed under any circumstance, and given the size of the move (likely extreme illiquidity/short-squeeze/retail-driven dynamics), it warrants real caution even as a discretionary idea. Flagging prominently rather than ranking it — this is not a "sleep on it" candidate, it's a "watch from a distance" one.

**Other no-catalyst movers (standing-watch only, not scored):** PERI $11.40 (+31% vs $8.70), EVGO $1.84 (+46% vs $1.26), ATYR $6.35 (+28.5% vs $4.94) — none have a confirmable catalyst; all would need the micro-cap concurrency cap applied if any were ever surfaced for approval (sub-$5 names among them: EVGO, PERI near the line).

## 8am true-up summary
**ROKU is flat pre-market ($155.95 vs. Monday's close $155.52, +0.3%) despite the confirmed double-beat** — the market is not yet pricing in last night's SEC-corroborated beat; this materially weakens (does not kill) the thesis — demoting from "promising fresh catalyst" to "needs real volume confirmation at the open" pending a clearer reaction. **LOAR/NXT extended further overnight** (LOAR $67.91 regular close holding, NXT now $92.75 pre-market, +1.8% on top of yesterday's +14.9%) — still no catalyst found, still on explicit hold. **MGRC/ZG pre-market quotes show abnormally wide bid/ask spreads** (MGRC bid $114.32/ask $205.80; ZG bid $29.93/ask $35.23) — thin/unreliable pre-market liquidity, not a real tradeable spread; disregard until regular-session quotes normalize. **CLRO and INO are both pulling back** from yesterday's extreme spikes (CLRO pre-market $4.97 vs. $5.66 close, -12%; INO pre-market $1.78 vs. $1.90 close, -6%) — consistent with the "unexplained spike, now fading" read on both; reinforces staying out. **AAOI (+3.4%) and COHR (+2.7%) are both extending their bounce** from Monday — see standing watch below. **VIX ticked up to 21.29** (7:53am ET) — a modestly more cautious pre-market tone than recent sessions, though no reliable overnight SPX/NDX futures-implied read is available (cash index timestamps still show Monday's close). Small-cap-tech shortlist: 0 matches. No positions to defend.

## Standing watch — optoelectronic sector (AAOI / COHR), update — bounce continues
Per the user's standing instruction (2026-10-07) to check both every morning regardless of scan hits:
- **AAOI:** Monday close $62.50. **Pre-market Tuesday $64.65** (bid $64.56/ask $64.70), **+3.4%** — extending its Monday pre-market bounce (+2.6% then) further. Trend read: extending higher, not fading. No fresh company-specific news found (get_equity_news unavailable all session; AAOI's own earnings aren't until 11/5).
- **COHR:** Monday close $199.95. **Pre-market Tuesday $205.39** (bid $203.85/ask $205.97), **+2.7%** — also extending its Monday bounce (+4.1% then), a bit more measured today. Trend read: holding the recent range on the upside, still no identified fresh catalyst.
- Still reads as sector-sentiment follow-through, not a scored or tradeable candidate — the 9:40am cycle's own Step 5/6 gate still applies before either could be treated as live.

## Top candidate — options read (preliminary, pre-open)
**ROKU, 11/13 expiration (~10 DTE):** $155 call — mark **$4.10** (bid $3.45/ask $4.75), IV 36.0%, delta 0.54, **OI 30 / volume 9** — thin. One contract = **$410**, likely above the account's ~10%-of-balance options cap (re-verify exact cap against live balance at the open). Structural read: DTE window PASS, listed chain PASS, premium-vs-cap **likely FAIL** (needs live balance check) — **PRELIMINARY, priced off Monday's regular-session close; same-day volume/spread and real price reaction are unconfirmed until the market opens.**

## Today's earnings slate (2026-11-03) — large volume of AM reporters already verified
Among the AM reporters already showing `eps.actual`: **PFE beat** ($0.87 vs $0.73), **ADM beat** ($1.77 vs $1.61), **ETN beat** ($3.68 vs $3.55), **ZBRA beat** ($4.95 vs $4.77), **SHOP beat** ($0.49 vs $0.43), **RACE beat** ($2.81 vs $2.66), **BNTX big beat** ($2.03 vs $0.97), **MDGL big beat/turned profitable** ($1.83 vs -$1.09 est), **WAT beat** ($4.10 vs $4.00), **YUM beat** ($1.56 vs $1.46), **TEVA beat** ($0.86 vs $0.72). **ADT beat** ($0.24 vs $0.23) — this resolves the standing "ADT unexplained move, report date TBD" note from prior builds: ADT did in fact report today, with a clean (if modest) beat. A few misses worth noting: **UPST miss** ($0.33 vs $0.55), **ALKS miss** ($0.09 vs $0.18), **ENLT miss**, **WLFC big miss**. None of these overlap with the ranked candidates above and none are pre-screened as new candidates here — worth a live scan at 9:40am given the broadly positive AM tape. **Heavy PM slate today** (AMD, AMGN, ANET, BKNG, SMCI, SHOP already AM, RIOT, ALAB, DUOL, XYZ, and more) — relevant for Wednesday's open, not today's.

## Macro / overseas check
WebSearch for overnight Asia/Europe futures and macro drivers returned no results dated to this session's simulated date (2026-11-03) — consistent with the same-day-coverage gap observed on every WebSearch query this entire session (TATT, CLRO, INO, and now broad-market futures). No reliable overnight macro read available via WebSearch. SPX/NDX cash index levels are not updating overnight (still showing Monday's regular-session close, ~7,541 / ~27,990); **VIX did provide a live overnight print: 21.29 as of 7:53am ET**, a modest uptick suggesting a slightly more cautious tone than the de-escalation seen Monday morning. Re-check live index levels at the 9:40am cycle.

## Pending binary events / standing notes
- TATT: clean stop-out Monday, catalyst retroactively confirmed real — **excluded from re-entry** per the standing "don't chase a clean stop-out" rule.
- CLRO: carve-out-eligible but declined on price-structure grounds Monday; now fading further pre-market (-12%) — still under explicit user hold.
- LOAR/NXT/MGRC/ZG: no catalyst found all session; under explicit user hold pending fresh earnings-informed context. MGRC/ZG pre-market quotes currently unreliable (wide spreads).
- INO: yesterday's +215% unexplained spike is now fading (-6% pre-market) — flag only, never score.
- ROKU: confirmed, news-corroborated double-beat, but pre-market price is flat — needs a real volume/price reaction before being treated as live.
- DAIC (CID HoldCo) remains excluded from consideration regardless of any future move — tied to the 2026-09-17 "don't chase" realized-loss lesson.
- ADT: earnings catalyst now resolved — reported today, clean beat ($0.24 vs $0.23). No longer "unexplained."
- Benchmark account 570898312 (ETF buy-and-hold, SPY/QQQ/SCHD/JEPI/WQTM/DDDD) remains **read-only** — tracked for performance comparison only, never traded.
