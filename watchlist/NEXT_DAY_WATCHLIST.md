# Next-Day Watchlist

> **PROVISIONAL — RESEARCH ONLY. NOT A TRADE LIST.**
> Nothing below is pre-approved. At market open, before anything else, every entry must be
> re-verified against live price action and a fresh options chain. A catalyst that gapped up
> 20% pre-market and is already fading by 9:35am ET is a PASS despite being on this list.
> This file is a head start for the search, not a decision.

**Build status:** built by the ~6:05pm after-hours routine on 2026-10-01 (fired ~6:06pm ET);
trued up by the ~6:00am overnight routine on 2026-10-02 (fired ~6:01am ET). This is the final
version before the 9:40am opening-bell scan — no further update until tonight's build.

**Data-gap flag — still active:** `get_equity_news` remains completely unreachable (checked
again this pass, zero matches). No way to confirm the "why" behind any price move overnight —
every catalyst claim below not sourced to a specific dated earnings print is inferred from
price action only.

**Asian/European overnight session:** could not be checked — news tool unavailable. Real gap
in this pass's coverage, same as every prior morning.

**Overnight/premarket tone (as of ~6:02am ET, 2026-10-02):** VIX is fresh and down slightly to
**15.96** (from 16.32 at yesterday's 3pm close) — mildly calmer. SPX/NDX quotes returned but
with stale venue timestamps from yesterday afternoon (not genuine overnight prints) — could
not confirm real overnight index levels, flagging rather than presenting stale data as live.

---

## For trading day: 2026-10-02 (Friday)

### Today's open positions — not new-entry candidates, included for continuity

**IOVA** — 12 sh @ $14.43 avg. Closed Thursday $14.23, premarket last $14.4858 (bid/ask
$14.31/$15.30 — wide, stale-looking ask) — a mild overnight bounce **away** from the $14.20
stop / $14.05 limit, though the book is thin enough this early that it shouldn't be read as a
confirmed reversal. Still the closest IOVA has been to its stop all week; re-verify at the open
rather than assuming the bounce holds.

**UTHR** — 1.000000 sh, blended avg cost $575.64. Closed Thursday $571.38; premarket book is
extremely wide (bid $554.00 / ask $638.29) and not a reliable read at this hour. Real
broker-side GTC stop remains live at $565.35 stop / $559.70 limit. Continue managing as an
open position, not a fresh entry — re-check with a tighter book once the market opens.

**ACN** — 1.000000 sh, blended avg cost $216.49. Closed Thursday $212.30, premarket last
$213.00 — essentially flat overnight, holding the pullback from Thursday's intraday high
without further slippage. Real broker-side GTC stop remains live at $204.22 stop / $202.20
limit. Continue managing as an open position, not a fresh entry.

**BE, CCL, KMX, CNXC** — all closed out via trailing stop earlier this week (gains on CCL,
CNXC; losses on BE, KMX). Per the standing rule, none are re-entry candidates without a fresh,
qualifying setup on their own merits.

### Ranked candidates

**1. NKE — Nike (confirmed earnings beat, but sharp and widening after-hours/overnight selloff) — STRENGTHENED (as a bearish setup)**
- **Catalyst:** Q1 FY2027 earnings, reported 2026-10-01 after close (`get_earnings_calendar`,
  verified) — actual EPS $0.48 vs. $0.44 est., a real beat.
- **Direction / magnitude:** Bearish despite the beat, and getting worse overnight, not better.
  Thursday regular close $35.15 → after-hours last night $32.94 (-6.1%) → premarket this
  morning $31.61 (bid/ask $31.58/$31.61) — now **-10.1%** total from Thursday's close. The gap
  is extending, not filling. Classic "beat the headline number but something in the details
  spooked the market" pattern (guidance, margins, tariffs, etc. — still can't confirm the
  specific driver without the news tool).
- **Freshness confidence:** High, and higher than last night's build — overnight persistence
  without any filling is a stronger signal than the after-hours print alone. Re-verify at the
  open that the gap is holding into the regular session.
- **Disqualifiers:** The "why" behind the beat-but-sell reaction is still unconfirmed (news
  tool down) — re-verify the specific negative detail once news access returns or via opening
  price action. Large-cap name, so a defined, liquid options chain should exist if a put-side
  or short-equity setup is considered.

**2. VICR / COHR / LITE / TSEM / AAOI — correlated optics/power-semiconductor basket (catalyst unconfirmed) — STRENGTHENED**
- **Catalyst:** Still unknown/unconfirmed — none on today's earnings calendar, news tool down.
  All five continuing to extend together overnight reinforces that this looks like a real
  shared sector catalyst (AI-datacenter optical/power-component demand is the obvious guess),
  but that remains inference, not a sourced fact.
- **Direction / magnitude:** Bullish, extending further overnight across the board. Thursday
  close → premarket this morning: VICR $308.59→$315.20 (+2.1%), COHR $319.19→$321.46 (+0.7%),
  LITE $1,045.78→$1,058.46 (+1.2%), TSEM $241.30→$244.50 (+1.3%), AAOI $107.32→$109.30 (+1.8%).
- **Freshness confidence:** Moderate-high and improved from last night — persistence through
  a full overnight session without fading is a better signal than the after-hours read alone.
  Still capped by the total lack of a confirmed source.
- **Disqualifiers:** Catalyst unconfirmed for all five. All are already up a lot over two
  sessions now — per the don't-chase judgment, a clean re-basing structure at the open would
  be needed before any of these look like a fresh entry rather than a late chase.

**3. MAT — Mattel (stalled overnight, catalyst still unconfirmed) — WEAKENED**
- **Catalyst:** Still unknown/unconfirmed — not on today's earnings calendar, news tool down.
- **Direction / magnitude:** Bullish but no longer extending — Thursday close $15.04, premarket
  last $15.15 (bid/ask $13.74/$15.90 — a very wide, likely-stale book this early), essentially
  flat overnight after yesterday's +18.8% day.
- **Freshness confidence:** Lower than last night — the move has stopped extending, and
  without a confirmed catalyst a stalled +18.8% name is a weaker setup than one still gaining
  ground (compare to the optics/semi basket above).
- **Disqualifiers:** Catalyst entirely unconfirmed; premarket book too wide to trust yet.

**4. KD — Kyndryl (stalled overnight, catalyst unconfirmed) — WEAKENED**
- **Catalyst:** Still unknown/unconfirmed — news tool down.
- **Direction / magnitude:** Bullish but flat overnight — Thursday close $12.12, premarket last
  $12.20 (bid/ask $11.86/$13.54, also a wide/unreliable book), little follow-through after
  yesterday's +10.8% peak.
- **Freshness confidence:** Lower than last night — no overnight extension, no source.
- **Disqualifiers:** Catalyst entirely unconfirmed; premarket book too wide to trust yet.

**5. EFXT — Enerflex (flat overnight, catalyst unconfirmed) — WEAKENED, demoted**
- **Catalyst:** Still unknown/unconfirmed — news tool down.
- **Direction / magnitude:** Bullish, holding but not extending — Thursday close $25.44,
  premarket last $25.73 (bid/ask $22.78/$27.53, thin/unreliable book this early).
- **Freshness confidence:** Low — now a repeat appearance across multiple cycles with zero
  overnight follow-through and no confirmed source.
- **Disqualifiers:** Catalyst unconfirmed; repeat name; premarket book too wide to trust yet.

### Today's scheduled earnings (2026-10-02) — reconfirmed at the true-up

- **Before the bell:** YYAI (no estimate available, report.verified=false — date still
  tentative). Thin micro-cap name; low priority.
- **Date correction:** CBAT's report date has shifted from tomorrow (2026-10-02) to **2026-10-05**
  per the refreshed calendar pull — no longer relevant to tomorrow's open, dropped from this
  list.
- Nothing else notable scheduled for today in the pulled window.

---

## Format each candidate follows

| Field | What goes here |
|---|---|
| Ticker | |
| Catalyst | What happened, with a specific timestamp, and the source (e.g. company PR, 8-K, news wire, exchange filing) |
| Direction / magnitude | Bullish or bearish, and the after-hours/pre-market % reaction if one exists yet |
| Freshness confidence | How likely this is still a live, tradeable setup at tomorrow's open — a catalyst from a few hours ago is fresher than one from days ago just being rehashed tonight |
| Disqualifiers | Anything that would knock this out going in: no listed options chain, earnings scheduled again soon, thin historical liquidity, already priced in/capped |

Entries are **ranked by likelihood of still being a live, tradeable setup at the open** — not
by headline size.

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
