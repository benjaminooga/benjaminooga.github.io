---
title: "Golf Metrics & KPIs"
date: 2026-10-16 10:05:00 -0400
categories: [Learning]
tags: [measurement, metrics, KPI, tracking, data]
description: A reference list of round- and hole-level golf metrics, how to record each one, and the KPIs they roll up into--with handicap-banded benchmarks from Shot Scope and Arccos data for comparison.
---

What follows is for idea purposes only. Depending on where your game is at, some of these items will not make sense to track. In fact, tracking certain stats too early may hurt your progress by putting a focus on something that is not a root cause. Disclaimer aside, if you know that data has no meaning until it is interpreted and it will not adversely affect your confidence/performance, feel free to track more than less. You may appreciate the data set later.

- **Measurement** data point recording what happened
- **Metric** a series of measurements; generally does not have a target but used to determine KPIs
- **Key Performance Indicator (KPI)** measure of how well it happened, calculated from the metrics and compared against goal or benchmark (such as handicap index (HI))

Since what follows is a set of measurements to get you thinking about what to track, it is not exhaustive. For instance, hole-based metrics has 'number of putts,' but round-based metrics does not include 'total putts.' Additionally, as you progress, you may only care about tracking 'number of three putts.'
The overall pattern is that hole-based metrics are aggregated as round-based metrics. Round-based metrics over time illustrate how we are tracking against our KPIs. KPIs are generally an average of round-based metrics.
Here's the detail, broken down by round and hole level.
---
## Metrics: Round Level

| Metric | How to record | Used for |
|---|---|---|
| Date | Date played | Trends, last-20 handicap window |
| Course & tees | Course name, tee box | Context, course-specific trends |
| Course rating | From scorecard | Score differential |
| Slope rating | From scorecard | Score differential |
| Holes played | 9 or 18 | Normalizing per-round KPIs |
| Conditions | Wind, temperature, firm/soft, rain | Explaining outlier rounds |
| Adjusted gross score | Total score with each hole capped at net double bogey | Score differential |

## Metrics: Hole Level

| Metric | How to record | Used for |
|---|---|---|
| Par | 3 / 4 / 5 | Scoring by par, GIR |
| Stroke index | Hole handicap (1–18) | Hardest-hole performance |
| Score | Strokes taken, including penalties | All scoring KPIs |
| Tee club | Driver, 3W, hybrid, iron | Club strategy, playable % by club |
| Tee result | Fairway / Left / Right / Short / Penalty | Fairways %, miss pattern |
| Tee shot playable | Y/N: clear shot at the green (no punch-out or penalty) | Playable % |
| Approach distance | Yards for the shot that is supposed to reach the green (par 3 = tee shot) | GIR % and proximity by distance band |
| Approach result | Green / Left / Right / Short / Long | GIR, approach miss pattern |
| Approach proximity | Feet from hole, if on the green | Proximity |
| Strokes to green | Strokes until the ball is on the green | GIR |
| Short-game shots | Count of chips, pitches, and bunker shots inside about 50 yds | Up-and-down, short-game efficiency |
| Short-game leave | Feet from hole after the first short-game shot | Short-game proximity |
| Putts | Count | 3-putts |
| Putt distances | Feet for each putt (e.g. 24, 3) | Make % by distance, first-putt leave, missed <3 ft |
| Penalty strokes | Count | Penalties |

---

## KPIs (calculated, with HI benchmarks)

Benchmarks are averages from shot-tracker user data, mostly Shot Scope's. They are not definitive: the users are self-selected, handicaps may be app-calculated, and no sample sizes are published. "—" means no published benchmark exists for that handicap; set your own baseline from your first 10–20 rounds. Per-round values marked "×18" are converted from published per-hole percentages.

| Category | KPI | Calculation | Scratch | 5 HI | 10 HI | 15 HI | 20 HI | Source | Purpose |
|---|---|---|---|---|---|---|---|---|---|
| Outcome | Score differential | (113 ÷ Slope) × (Adj. gross − Course rating) | — | — | — | — | — | | The result all other KPIs roll up to. Your index is roughly the average of your best 8 of your last 20 differentials, so your typical round runs a few strokes above it. |
| Outcome | Double bogey or worse | Holes with Score ≥ Par + 2 | 0.27 | — | — | — | — | ‖ | Damage control. Big numbers inflate a handicap faster than missing birdies does. (25 HI: 9.18 per round.) |
| Outcome | Birdies | Holes with Score ≤ Par − 1 | 2.34 | 1.26 | 0.72 | 0.36 | 0.36 | ¶ | Scoring upside. Mostly relevant once you're in single digits. |
| Outcome | Bogey-or-better %, hardest holes | Holes at bogey or better ÷ holes with stroke index 1–6 | — | — | — | — | — | | Whether you play conservatively on tough holes. |
| Scoring | Par 3 average | Avg score on par 3s | 3.2 | 3.42 | 3.6 | 3.83 | 4.0 | † | Long-iron/hybrid quality |
| Scoring | Par 4 average | Avg score on par 4s | 4.2 | 4.53 | 4.67 | 5.05 | 5.31 | † | Driving and mid-iron approaches |
| Scoring | Par 5 average | Avg score on par 5s | 4.8 | 5.36 | 5.52 | 5.91 | 6.23 | † | Should be your best hole type vs. par; a high average usually means poor course management |
| Driving | Fairways hit % | Tee result = Fairway ÷ par 4/5 holes | 50% | 51% | 50% | 47% | 45% | † | Driving accuracy. Nearly flat across handicaps, so it explains little about scoring on its own. |
| Driving | Playable drive % | Playable = Y ÷ par 4/5 holes | — | — | — | — | — | ° | Whether driving is actually costing you strokes. Closest proxy: tee shots in trouble per round of 6.5 (100s shooters), 4.9 (90s), 3.3 (80s), 2.0 (70s). |
| Driving | Penalty strokes | Sum of penalty strokes | — | — | — | — | — | | Overall accuracy |
| Approach | GIR | Holes where strokes to green ≤ Par − 2 | 10.6 (59%) | 7.4 (41%) | 6.3 (35%) | 4.1 (23%) | 2.9 (16%) | † ◊ | Overall ball-striking; strongest predictor of scoring level at lower handicaps. Arccos: 8 (5 HI), 6 (10 HI), 4–5 (15 HI). Per-round values ×18. |
| Approach | Green hit % from 100 yds | Greens hit ÷ approaches from ~100 yds, fairway | 74% | 65% | 57% | 49% | 42% | § | Wedge accuracy from a standard distance |
| Approach | GIR % 50–100 yds | GIR ÷ approaches from that band | — | 55% | — | — | — | † | Pitching/wedge play |
| Approach | GIR % 100–150 yds | Same, 100–150 yds | — | 41% | — | — | — | † | Most common band; usually best practice payoff |
| Approach | GIR % 150–200 yds | Same, 150–200 yds | — | — | — | — | — | | Longer club accuracy |
| Approach | GIR % 200+ yds | Same, 200+ yds | — | — | — | — | — | | Low for everyone; lay-up decisions matter more than this number |
| Approach | Proximity, 100–150 yds | Average approach proximity from 100–150 yds, greens hit | — | — | — | — | — | † | Birdie setup quality; matters most at low handicaps. Published 5 HI figure (57 ft) includes missed greens, so it isn't comparable. |
| Short game | Up-and-down % | Missed-GIR holes with Score ≤ Par ÷ missed-GIR holes | 54% | 47% | 40% | 35% | 32% | † | Overall short-game success |
| Short game | Short-game proximity | First short-game shots left ≤ 6 ft ÷ holes with a short-game shot | — | — | — | — | 34% | † | Chipping and pitching quality. Published 20 HI figure counts only shots that reach the green. |
| Putting | 3-putts | Holes with Putts ≥ 3 | 0.5 (3%) | 1.1 (6%) | 1.4 (8%) | 1.8 (10%) | 2.3 (13%) | † | Mostly a lag-putting problem or speed for higher handicaps. Per-round values ×18. |
| Putting | Missed putts < 3 ft | Missed putts from under 3 ft | — | — | — | — | — | | Should be near zero... And then there's reality. (Scratch makes 98% from 0–3 ft.) |
| Putting | Make % 0–6 ft | Holed ÷ attempts from 0–6 ft | 93% | 89% | 89% | 85% | 84% | † | Par-saving putts. (Scratch makes 76% from 3–6 ft.) |
| Putting | Make % 6–12 ft | Holed ÷ attempts from 6–12 ft | 43% | 41% | 38% | 40% | 38% | ‡ | Scrambling and birdie conversion |
| Putting | First-putt leave, 20+ ft | Avg 2nd-putt distance when 1st putt ≥ 20 ft | 4.6 ft | — | — | — | — | * | Speed control (leading indicator of 3-putts). Published figures are from ~30 ft; 25 HI: 7.8 ft. |

**Source legend**

| Symbol | Source |
|---|---|
| † | Shot Scope, "Law of Averages" series (2024, updated 2025): [0 HI](https://shotscope.com/blog/practice-green/game-improvement/reduce-hcp-law-of-averages-0hcp/), [5 HI](https://shotscope.com/blog/stats/reduce-your-handicap-5hcp-averages/), [10 HI](https://shotscope.com/blog/stats/10handicap-law-of-averages-series/), [15 HI](https://shotscope.com/blog/stats/reduce-your-handicap-15hcp/), [20 HI](https://shotscope.com/blog/practice-green/game-improvement/reduce-your-handicap-20hcp-averages/) |
| ‡ | Shot Scope, [Putting make percentages by handicap](https://shotscope.com/blog/practice-green/stats-and-data/putting-make-percentages-by-handicap-how-do-you-compare/) (2022) |
| § | Shot Scope, [How many greens do amateur golfers hit?](https://shotscope.com/blog/practice-green/stats-and-data/amateur-golfers-greens-hit/) |
| ¶ | Shot Scope data via First Call Golf, [Is chasing birdies the quickest path to lower scores?](https://www.firstcallgolf.com/industry-news/release/2026-07-29/shot-scope-data-deep-dive-is-chasing-birdies-the-quickest-path-to-lower-scores) (2026) |
| ‖ | Shot Scope data via Golf Insider UK, [Birdies, bogeys & doubles by handicap](https://golfinsideruk.com/birdies-bogey-doubles-by-handicap/) (2024) |
| ° | Shot Scope, [6 Benchmarks for Success](https://shotscope.com/blog/practice-green/reduce-your-handicap/shot-scope-6-benchmarks-for-success/) (2026; by scoring range, not handicap) |
| ◊ | Arccos data via GOLF.com, [How many greens in regulation per round](https://golf.com/instruction/how-many-greens-in-regulation-per-round/) |
| * | Shot Scope data via MyGolfSpy, [Three-putting stats by handicap](https://mygolfspy.com/news-opinion/shot-scope-case-study/) (2022) |

