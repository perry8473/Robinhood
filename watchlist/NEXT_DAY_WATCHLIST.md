# Next-Day Watchlist — built for Thursday, 2026-11-12

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.** Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as an actionable candidate.

## Note on this file's state

This build OVERWRITES last night's 2026-11-11 file (CRWV/COHR/AAOI/RSKD/REZI watch, now fully resolved — see git history for that day's trade log). Built by the ~6pm after-hours research routine on 2026-11-11. Asian and European overnight-session news has NOT been checked yet at this hour — that is the job of the ~8:00am "Overnight true-up" routine, which will update this file again before the open.

## Step 0 — held position check

No stock or options position held (`get_equity_positions`/`get_option_positions` both confirmed empty — REZI was closed out after-hours on 2026-11-11 per explicit user instruction). Nothing to defend this run.

## Top candidate — NBIS (Nebius Group)

- **Ticker:** NBIS
- **Catalyst:** Q3 2026 earnings, scheduled **tomorrow (2026-11-12) before the open** (timing="am", verified=true on the earnings calendar; eps.actual still null as of this run — not yet reported). EPS estimate -$1.11.
- **Direction/magnitude:** Already running hot INTO the print — closed today +15.8% ($134.00 → $155.18), but fading in after-hours: last non-reg $150.25 (-3.2% off the regular close), bid $150.12/ask $150.37 as of 23:06 UTC. This is the broad AI-datacenter/optics sector move noted in today's cycles (CRWV/COHR/AAOI all moved on the same theme), not NBIS-specific news yet — the earnings print tomorrow AM is what turns this into a real, dated, company-specific catalyst.
- **Freshness confidence:** High for "there will be a fresh catalyst at the open" (verified, dated, before-the-bell report) — but direction is unknown pre-print, and the stock is already extended going in, which cuts both ways (a beat may be partly priced in; a miss has a long way to fall from today's run).
- **Disqualifiers:** DON'T-CHASE caution applies regardless of outcome — already up ~16% today before any confirmed results. Re-verify fresh at the open once eps.actual populates; do not treat today's pre-print run as the catalyst itself.
- **Options read (PRELIMINARY, NOT A LIVE QUOTE — last-close data, re-verify once market opens):** Listed chain exists (equity, no extended-hours support). Nearest 7-30 DTE expiration: 2026-11-20 (9 DTE). ATM calls (strike $150/$152.50/$155) priced at mark $13.20-$15.63, implied volatility ~135% — already extremely elevated ahead of the binary earnings event. Premium ($1,320-$1,563/contract) **far exceeds** the current OPTIONS SIZING cap (~$353 at today's ~$3,530 balance, 10% rule). **PRELIMINARY READ: FAIL on premium alone**, before even weighing the IV-crush risk of entering an option this rich right before an earnings gap. Stock-only route (if any) is the realistic path here, not options.

## Today's movers — after-hours follow-through (all from today's 2026-11-11 cycles)

| Ticker | Regular close (+% day) | After-hours last | AH change | Note |
|---|---|---|---|---|
| **AAOI** | $55.86 (+15.6%) | $54.01 | -3.3% | Faded after hours following the flat-top/breakeven-stop exit this afternoon (see today's log) — exactly the pattern that prompted the new FLAT-TOP EXIT RULE. No fresh catalyst for tomorrow; fold back into normal scan. |
| **CRWV** | $60.84 (+24.9%) | $57.15 | -6.1% | Still fading off the highs reached after being blocked by the permission classifier earlier. No CRWV-specific news found, same sector-sympathy move. Already very extended — don't chase. |
| **COHR** | $234.53 (+9.3%) | $229.22 | -2.3% | Similar fade pattern, smaller magnitude. Stale catalyst (earnings beat was 2026-11-04), no new news. |
| **RSKD** | $10.37 (+22.3%) | $10.39 | flat | Held up better than the others — real catalyst (Q3 beat $0.07 vs $0.02 est, reported today AM) but structure faded/chopped mid-session per today's log; continuing to watch for a fresh base, not currently a candidate. |
| **CARL** (Carlsmed) | $18.63 (+26.6%) | $18.59 | flat | No confirmed catalyst found today (WebSearch turned up only undated/stale items), already extended. Not on tomorrow's earnings calendar. Not pursued. |
| **FOSL** | $9.955 (+26.5%) | $9.85 | -1.1% | Same story as CARL — no catalyst found, already extended multiple days running. Not pursued. |

Broad takeaway: several of today's biggest movers put in a classic flat-top-then-fade pattern into the close and after hours — consistent with the new FLAT-TOP EXIT RULE added today. None of these carry a fresh, dated catalyst for tomorrow specifically; they're noted for continuity, not as candidates.

## Secondary earnings calendar — tomorrow (2026-11-12), high-market-cap names

Before the open (am) — potential opening gaps, not yet researched in depth this run, available for the 9:40am cycle to check fresh:
- **YETI** (Yeti Holdings) — EPS est $0.82.
- **TWST** (Twist Bioscience) — EPS est -$0.25.
- Several others (BLTE, ANDG, ASND, SPH, BN, HBM, SPB, SIEGY, ARCO, LUNR, EYE, XE, WWW, STDN, CLBT, MWH, OCTV, AVAH, FIGR, EROC, NIQ, ARX, LGN, BRDCY) — no pre-existing momentum context, not individually researched this run given time budget; the earnings calendar itself is the lead for the 9:40am/overnight-true-up cycles to re-check.

After tomorrow's close (pm) — sets up Thursday/Friday reactions, not actionable for tomorrow's open:
- **AMAT** (Applied Materials) — EPS est $4.06. Mega-cap semi-equipment name, worth watching for Friday's open.
- **CSCO** (Cisco) — EPS est $1.29. Mega-cap networking name, same timing note.
- **NU** (Nu Holdings) — EPS est $0.22.
- **ARWR** (Arrowhead Pharmaceuticals) — EPS est -$1.52.

## No scheduled macro/legislative events flagged

No new pending binary events beyond the already-resolved CLARITY Act vote noted in the standing Routine. Nothing else surfaced via this run's limited research budget — the 8am overnight true-up should re-check for anything that broke in Asia/Europe overnight.

## Ranking for tomorrow's open

1. **NBIS** — highest-confidence fresh catalyst (verified earnings date), but already extended and genuinely binary; re-verify completely fresh once eps.actual populates before the open, don't treat pre-print momentum as the signal.
2. **YETI / TWST** — scheduled AM reporters, no momentum context yet, worth a quick check at 9:40am.
3. Everything else — either stale/no-catalyst (CARL, FOSL, CRWV, COHR) or already a held/managed position's normal continuity watch (RSKD, AAOI) with nothing new to act on.
