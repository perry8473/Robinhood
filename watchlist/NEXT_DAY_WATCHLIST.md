# Next-Day Watchlist — true-up for Wednesday, 2026-11-11

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.** Nothing below is pre-approved. Every entry must be re-verified against live price action and a fresh options chain at the open before being treated as an actionable candidate.

## Note on this file's state

This build supersedes last night's 2026-11-10 6pm build (FRNM/MRCY/CRWV/ZIP/SANM as top candidates) with fresh overnight/pre-market data. (An earlier local git-cache issue briefly made it look like that 6pm build and the whole day's history had vanished from the branch — a `git fetch` confirmed it was a stale local ref, not real data loss; everything is intact in the repo's history.)

## Step 0 — held position check

No stock or options position held (`get_equity_positions`/`get_option_positions` both confirmed empty, re-verified this pass). Nothing to defend.

## Standing watch — optoelectronic sector (AAOI / COHR)

Both up strongly pre-market, part of a **sector-wide move**, not isolated news:
- **AAOI**: prior close $48.32 → pre-market ~$51.60-51.72, **+6.9%**. Extending higher.
- **COHR**: prior close $214.66 → pre-market ~$233.15-234.80, **+8.9%**. Extending higher.
- Context (WebSearch): the AI-optics group (Coherent, Lumentum, and peers) has been rallying this week on "AI datacenter demand" and M&A-driven re-rating commentary (Marvell's $115B Lumentum deal cited as highlighting "the value of scarce AI optics"). COHR specifically beat on revenue (+49.9% YoY) when it reported 2026-11-04 and has been whipsawing hard since (a 13% one-day drop, then sharp rebounds) — still net up on the week but volatile. This is sector-wide tailwind, not a fresh dated catalyst on either name specifically this morning.
- Standing note unchanged: this is a watch item per explicit user interest in the sector, not a trade signal — the 9:40am cycle still applies its normal Step 5/6 gate before treating either as live.

## Overnight follow-through on yesterday's (2026-11-10) candidates

| Ticker | Yesterday's close | Pre-market now | Change | Status |
|---|---|---|---|---|
| **CRWV** | $48.73 | ~$56.14-56.20 | **+15.3%** | STRENGTHENED sharply — already a very large pre-market gap on top of yesterday's earnings beat. No specific new overnight catalyst confirmed via WebSearch (only historical CRWV volatility pattern found, nothing dated to today) — treat the size of this gap itself as the headline risk: this is already a big move before the bell, DON'T-CHASE caution applies heavily at the open. |
| **MRCY** | $83.58 | ~$86.50-87.38 | +3.5% further | STRENGTHENED modestly — continuing the post-beat move cleanly. |
| **SANM** | $155.43 (after a whipsaw day) | ~$165.00-166.59 | +6.9% further | STRENGTHENED — resolving cleaner than yesterday's chaotic intraday whipsaw; worth a fresh Step 6 structure check at the open since yesterday's disqualifier was structure, not catalyst. |
| **FRNM** | $10.77 | ~$10.94 (wide spread, bid $10.02/ask $11.10) | +1.6%, faded from last night's $11.42 AH print | WEAKENED — losing steam, thin/wide pre-market market. Still no options chain (unchanged). |
| **ZIP** | $6.59 | ~$6.55-6.58 | flat/slightly down | WEAKENED/fizzled — no overnight follow-through on yesterday's extended-but-real move. Demote. |

## Today's (2026-11-11) scheduled earnings — before the open

High-market-cap AM reporters today are thin; notable ones already reported with results in (per calendar): RUM (-$0.19 vs -$0.13 est, miss), ODD/Smartsheet ($0.37 vs $0.27 est, beat), NSANY (-$0.13, loss), GIB ($1.65 vs $1.64, in-line), BGSI ($0.68 vs $0.86, miss). None of these have been checked yet for pre-market price reaction — flag for the 9:40am cycle to verify fresh if any show unusual pre-market volume. After today's close (sets up Thursday, not today): CTVA, FNV, TTEK, ENS, CAE, OR — not actionable today.

## Macro / index tone

SPX 7,520.93 / NDX 27,740.80 (both modestly higher vs yesterday's close) / **VIX 18.46**, down meaningfully from yesterday's 20.09-20.82 range — tone has improved overnight, less choppy than described in the "sitting patiently is ok" stretch earlier this week. Worth noting but not a reason to loosen any standing gate.

## Pre-market small-cap-tech shortlist (Step 3b)

Technology sector scan (scan_id 4ab9bad9) returned **0 matches** pre-market. Nothing to shortlist this morning.

## Options consideration — top candidates (PRELIMINARY, NOT LIVE QUOTES — all priced off yesterday's 4pm close, before today's pre-market gaps)

- **CRWV** $56 call, 2026-11-20 (9 DTE): close $2.66/contract ($266) — **passes current $353 sizing cap**, OI 1,387, volume 413, tight $2.60/$2.71 spread. Structural read: DTE pass, premium pass, listed chain pass, liquidity good. **Caveat: this premium predates today's +15% pre-market gap in the stock — it will reprice materially higher once the options market opens and must be re-pulled live, not used as-is.**
- **MRCY** $87.5 call, 2026-11-20 (9 DTE): close $4.33/contract ($433) — fails the $353 cap; wide $2.75/$5.90 spread (thin), OI only 60, volume 36. Weak structurally even before repricing for the further +3.5% pre-market move.
- **SANM** $165 call, 2026-11-20 (9 DTE): close $4.65/contract ($465) — fails the $353 cap; wide $3.30/$6.00 spread, OI 852, volume 186. Also pre-dates the +6.9% pre-market move.

## Summary for the 9:40am cycle

Ranked by live-setup likelihood: **CRWV** (biggest pre-market move, options structurally the cleanest of the three but the stock-side move is already very large — treat as a don't-chase risk, not a slam dunk), **SANM** (cleaner structure forming, re-check Step 6 fresh), **MRCY** (still constructive but thinner options liquidity), then **AAOI/COHR** (standing watch, sector-wide tailwind, re-verify catalyst specificity before scoring). **FRNM** and **ZIP** are demoted — no real overnight follow-through.
