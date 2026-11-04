# Next-Day Watchlist — build for Thursday, 2026-11-05

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as a candidate. Built 6:05pm ET Wednesday 2026-11-04 (after-hours catalyst research). Asian/European overnight-session news has NOT been checked yet at this hour — that's the job of the ~8am overnight true-up routine before the open.

## Step 0 — held position defense check
`get_equity_positions` confirmed empty for account 787937630. Nothing to defend — the account is flat. MOH and CNC (today's re-entry basket, election/managed-care catalyst) were both closed out by the user at 3:03pm ET for a combined +$14.01 gain, partially offsetting the morning's -$38 loss across the original 5-position election basket (FSLR/RUN/ENPH/MOH/CNC).

## Account state
Flat, fully in cash (~$2,923 per last portfolio check). Day's net P&L: roughly -$24 (-$38 morning + $14.01 afternoon). Benchmark account 570898312 remains read-only, tracked for comparison only.

## Market condition (as of 3pm ET cycle, last live check)
SPX 7,697.28, NDX 28,469.58, VIX 16.71–16.83 — risk-on, calm, VIX continuing to ease off the week's highs. Election-result tailwind (Democrats swept Congress 11/3) still broadly supportive; no new macro catalyst overnight identified yet.

## Today's after-close (PM) earnings reactions — large slate, wide dispersion
Pulled via `get_earnings_calendar` (report.verified=true, eps.actual populated) and `get_equity_quotes` for AH reaction (previous regular close vs. last non-regular-hours print). WebSearch used as the get_equity_news substitute (still unavailable this session) for the top two movers.

| Ticker | Result | Reg. close | AH price | Reaction |
|---|---|---|---|---|
| **APP** (AppLovin) | Beat, $4.30 vs ~$4.01-4.03 est, rev $2,185M +55% YoY | $245.51 | $333.86 | **+36.0%** — huge beat, confirmed via SEC 8-K |
| **AGL** | Swung positive, $1.97 vs -$0.99 est | $87.79 | $105.00 | **+19.6%** |
| **RUN** (Sunrun) | Beat, $0.56 vs $0.31 est | $8.68 | $9.68 | **+11.5%** — see flag below, same ticker as this morning's election-basket stop-out |
| **SBGI** (Sinclair) | Beat, $0.60 vs $0.09 est | $13.47 | $14.10 | +4.7% — excluded, broadcaster (entertainment/media rule) |
| **ELF** (e.l.f. Beauty) | Big beat, $1.21 vs $0.55 est | $111.50 | $118.50 | +6.3% |
| **ALL** (Allstate) | Big beat, $9.76 vs $6.97 est | $261.50 | $267.00 | +2.1% (muted vs. beat size) |
| **COHR** (Coherent) | Beat, $2.09 vs $1.93 est | $207.49 | $209.70 | +1.1% (no position — closed out of account 11/4 pre-earnings) |
| **AFL** (Aflac) | Beat, $2.43 vs $1.80 est | $124.04 | $125.00 | +0.8% |
| **QCOM** | Beat, $2.17 vs $2.02 est | $164.43 | $161.24 | -1.9% (sold despite beat — likely guidance) |
| **GOLD** (Barrick) | Big miss, $0.445 vs $0.88 est | $39.12 | $38.70 | -1.1% (surprisingly mild given miss size) |
| **CF** (CF Industries) | Miss, $2.87 vs $3.03 est | $116.81 | $113.82 | -2.6% |
| **MELI** (MercadoLibre) | Miss, $8.83 vs $9.30 est | $1,662.16 | $1,617.43 | -2.7% |
| **HUBS** (HubSpot) | Beat, $3.81 vs $2.80 est | $226.17 | $199.78 | **-11.7%** — sold hard despite beat, likely guidance |
| **ZG** (Zillow) | Beat, $0.55 vs $0.53 est | $31.35 | $28.56 | **-8.9%** — sold despite beat; WebSearch suggests a trimmed full-year revenue guide. **Flag: ZG is in the user's standing hold group (LOAR/MGRC/ZG/NXT)** — this bearish reaction is new information worth a fresh look at that whole group tomorrow. |

327 total PM reporters today — only names with a reaction ≥ ~4% in either direction, or otherwise directly relevant (COHR, ZG), are listed; the rest were sub-3% moves or illiquid/unremarkable.

## Tomorrow (2026-11-05) scheduled earnings — notable names
**AM (before open):** COP, DUK, SO, SRE, CI, KMB, ZTS, CORZ (crypto-watchlist name), LOAR (user's standing hold name), GPN, VRSK, RL, AAP, DBX... — large slate, over 150 AM reporters total; the above are the highest-market-cap/most relevant.
**PM (after close):** ABNB, AFRM, DKNG, MCHP, TEAM, AAOI (closed out of account 11/4, FYI only), ARM, QCOM already reported tonight — correction, next PM batch includes NET, IONQ, SRPT, ALB, LYFT.
Nothing identified yet as a same-day binary catalyst for tomorrow beyond the normal earnings slate — re-check at 8am true-up for anything scheduled overseas overnight.

## Ranked candidates for Thursday's open

**#1 APP (AppLovin) — strongest, freshest catalyst of the night**
- **Catalyst:** Q3 beat confirmed via SEC 8-K, $4.30 EPS (vs. ~$4.01-4.03 est), revenue $2,185M +55% YoY, 84% adj. EBITDA margin, $1.4B FCF. Reported after close today (2026-11-04), verified.
- **Direction/magnitude:** Bullish, +36.0% AH ($245.51 → $333.86) — a genuinely large, confirmed beat.
- **Freshness confidence:** High — primary-source confirmed, same-day, not a rehash.
- **Disqualifiers:** The move is already very large by the time of this research pass — a 36% AH pop risks being mostly priced in by the cash open, and mega-cap AH moves of this size can see meaningful fade/profit-taking intraday. Re-verify real (not thin AH) price/volume structure at the open; don't chase if it's already extended multiple hours in.
- **Options read (PRELIMINARY — last regular-close pricing, not a live AH quote):** Listed chain confirmed, 11/13 expiration (~9 DTE) — within the 7-30 DTE window, structural PASS. Premium, OI, and live spread not pulled this pass (AH quotes aren't tradeable regardless) — check fresh at market open.

**#2 RUN (Sunrun) — fresh, independent catalyst distinct from this morning's trade**
- **Catalyst:** Q3 beat, $0.56 vs $0.31 est, reported after close today, verified.
- **Direction/magnitude:** Bullish, +11.5% AH ($8.68 → $9.68).
- **Freshness confidence:** High, but flagged for care — RUN was one of this morning's election-basket positions, stopped out at $9.59 on real continued weakness (confirmed down through midday, well below both entry and stop). Tonight's earnings beat is a genuinely separate, independent catalyst — not the same setup — so per the standing re-entry rule this qualifies as a fresh setup on its own merits, not a chase of the morning's stop-out. Still, re-verify a clean re-basing structure at the open rather than assuming the AH pop holds.
- **Disqualifiers:** Small-cap-adjacent, volatile name (sub-$10 share price) — the MICRO-CAP CONCURRENCY CAP may apply if another no-confirmed-catalyst speculative position is open at the time; not the case tonight (account flat).
- **Options read (PRELIMINARY):** Listed chain confirmed, 11/13 expiration (~9 DTE), structural PASS on DTE. Premium/OI not checked this pass given low share price — a call here would need a strike check against the sizing cap live at open.

**#3 ELF (e.l.f. Beauty) — clean beat, moderate reaction**
- **Catalyst:** Big beat, $1.21 vs $0.55 est, reported after close today, verified.
- **Direction/magnitude:** Bullish, +6.3% AH ($111.50 → $118.50).
- **Freshness confidence:** High, same-day, real beat.
- **Disqualifiers:** None identified yet — worth a Step 5/6 catalyst+structure check at the open. Not checked for options this pass (ranked #3, scoped out of the top-2 options research this run — check live at 9:40am if still a live candidate).

**Flag — HUBS, bearish reaction despite a real beat**
HubSpot beat ($3.81 vs $2.80) but sold off hard after hours (-11.7%, $226.17 → $199.78) — likely a guidance disappointment. Not a long candidate; possible short/put thesis if the reaction holds, but needs the actual guidance commentary (not available via WebSearch this pass) before treating as more than a flag.

**Flag — ZG, bearish reaction on the user's standing hold name**
Zillow beat EPS ($0.55 vs $0.53) but sold off -8.9% AH ($31.35 → $28.56) — WebSearch points to a trimmed full-year revenue guide as the likely driver (unconfirmed, pre-earnings-only sources found). ZG sits in the user's standing LOAR/MGRC/ZG/NXT hold group — this is new, relevant information for revisiting that group fresh tomorrow, not a trade signal on its own.

**Excluded — entertainment/media**
SBGI (Sinclair Broadcast Group), +4.7% AH on a beat — excluded per the standing entertainment/media sector exclusion (broadcaster), not scored for entry regardless of the clean reaction.

## Pending binary events / standing notes
- LOAR/MGRC/ZG/NXT remain on the user's explicit hold from Monday — ZG's bearish post-earnings reaction tonight (see flag above) is new information worth a fresh look at that whole group.
- DAIC (CID HoldCo) remains excluded from consideration regardless of any future move — tied to the 2026-09-17 "don't chase" realized-loss lesson.
- Benchmark account 570898312 (ETF buy-and-hold) remains **read-only** — tracked for performance comparison only, never traded.
- **New standing rule as of today (2026-11-04): SECTOR CONCENTRATION CAP** — max 2 open positions per Morningstar sector/correlated theme at any time, now written into the market-hours routine. Keep this in mind if APP/RUN/ELF end up clustering with any other Technology/Consumer-Cyclical names tomorrow.
