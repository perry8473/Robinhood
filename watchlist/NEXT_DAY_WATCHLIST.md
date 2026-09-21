# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% pre-market and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** not yet built — folder/template created 2026-09-21, pending first nightly
run. This file is built and updated automatically by two standing Routines (no manual edits
expected between runs):
- **~6:05pm ET** — "After-hours catalyst research (next-day watchlist)": builds the initial
  version for the next trading day from today's after-close earnings reactions, overnight/
  scheduled news knowable at 6pm, and tomorrow's scheduled catalysts.
- **~6:00am ET** (next morning) — "Overnight true-up (6AM pre-market check)": updates the same
  file in place with overnight developments the 6pm pass couldn't see yet — continued
  after-hours/pre-market reaction, Asian and European session news, and same-day scheduled
  catalysts (earnings before the bell, econ data, PDUFA dates, opex dynamics).

Git history of this file is the audit trail of what changed overnight and why.

---

## For trading day: _(pending first build)_

_No candidates yet — this section is populated by the routines above._

### Format each candidate should follow

| Field | What goes here |
|---|---|
| Ticker | |
| Catalyst | What happened, with a specific timestamp, and the source (e.g. company PR, 8-K, news wire, exchange filing) |
| Direction / magnitude | Bullish or bearish, and the after-hours/pre-market % reaction if one exists yet |
| Freshness confidence | How likely this is still a live, tradeable setup at tomorrow's open — a catalyst from a few hours ago is fresher than one from days ago just being rehashed tonight |
| Disqualifiers | Anything that would knock this out going in: no listed options chain, earnings scheduled again soon, thin historical liquidity, already priced in/capped |

Entries are **ranked by likelihood of still being a live, tradeable setup at the open** — not
by headline size. A loud but stale or already-priced-in catalyst ranks below a smaller, fresher
one with a clean setup.

---

## Sources every nightly build draws from

- **After-hours earnings releases today** — beats/misses, guidance changes, especially
  anything that moved the stock materially in after-hours trading.
- **Overnight news** — FDA/regulatory decisions, M&A announcements, contract wins, analyst
  upgrades/downgrades, litigation outcomes, macro events (Fed speakers, economic data
  releases scheduled for tomorrow morning).
- **Asian and European market-hours news** that could carry into the US session — a
  US-listed company with major news breaking on an overseas exchange or in overseas press.
- **Scheduled catalysts for tomorrow specifically** — earnings before the bell, FDA PDUFA
  dates, economic data releases, options expiration dynamics — anything with a known
  timestamp.
