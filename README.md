# Worlds 2026 Fan Hub

A fan-made guide to the 2026 League of Legends World Championship — built for fans who know everything and fans who know nothing.

**Live URL (after Pages is enabled):** https://brian-spanton.github.io/worlds-2026/

## What it is

One self-contained HTML file (`index.html`, ~50 KB) — no build step, no dependencies, no backend. Works on phones and laptops, loads instantly, works offline once loaded.

**Sections:** Home (beginner primer + format explainer) · Schedule (all stages, venues, dates) · Bracket & Stages (Play-In → Swiss → Knockouts → Final) · Teams (all 19, filterable by region) · Players (8 stars to know) · History (every Worlds winner 2011–2025).

## How to update it

All content lives in two places inside `index.html`:

1. **Static copy** (headings, explainer cards, schedule rows) — plain HTML in each `<section class="view">`.
2. **Data** — the `<script>` at the bottom of the file has three arrays:
   - `TEAMS` — 19 team objects (name, region, seed, blurb, history bullets)
   - `PLAYERS` — star-player cards
   - `HISTORY` — past winners

   Edit the array values, save, push. That's it.

When Riot announces the TBDs, search the file for `⚠︎` or `TBD` and fill them in:
- LCS final seed order + third berth — by **Oct 4**
- CBLOL champion + runner-up — by **Oct 10**
- Play-In pairings — after the draw
- Daily match times — ~1–2 weeks before each stage
- Team rosters (15-man lists) — locked closer to the event

## Data sources

Riot/lolesports announcements and Wikipedia's 2026 Worlds pages (main + qualification), cross-checked with esports press. Data current as of late September 2026.

## Not affiliated

This is a fan project. Not affiliated with or endorsed by Riot Games. "League of Legends" and "Worlds" are trademarks of Riot Games, Inc.
