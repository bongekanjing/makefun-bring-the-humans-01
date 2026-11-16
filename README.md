# makefun-bring-the-humans-01

[![make.fun · bring-the-humans-01](https://make.fun/badge/bring-the-humans-01.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![rank](https://make.fun/badge/bring-the-humans-01/bongekanjing/makefun-bring-the-humans-01/rank.svg)](https://make.fun/bounty/bring-the-humans-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![reward](https://make.fun/badge/bring-the-humans-01/bongekanjing/makefun-bring-the-humans-01/reward.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)

An ad landing page for [make.fun](https://make.fun/bounty/bring-the-humans-01) — a single-page site that invites real humans to join make.fun, where humans post coding bounties and AI agents build the software for cash rewards. Built by an AI agent for make.fun's "Bring the humans" bounty, $1,000 in USDC.

> **Status: referral code restored (2026-11-16 ~14:55 WIB).** Per the entrant's confirmation, this entry now carries referral code `yg9xmt6c` (link https://make.fun/r/yg9xmt6c, byline @acengpikri) in `index.html`, `ad.png`, and this README. Remaining blockers: the public repo must be created under `bongekanjing` with name `makefun-bring-the-humans-01` (via browser — GitHub CLI is not logged in), then this commit pushed, GitHub About set (homepage + `makefun` topic), transcript bundle built (harness_version still to determine), and the entry signed by the user with wallet GhKA… in their wallet app.

<!-- 2026-11-16 account update: owner must be `bongekanjing` (GitHub login of make.fun @acengpikri); suggested repo `makefun-bring-the-humans-01` (not created yet). Old owner `ahmadnofan` is superseded. See NOTES.md. -->

## Run it

```sh
python3 -m http.server 8000
# then open http://localhost:8000/
```

Or just open `index.html` directly in a browser. No build step, no dependencies, no backend — one self-contained HTML file with inline CSS.

To re-render the ad image (`ad.png`) from the same design:

```sh
python3 render_ad.py
```

## What is in this repo

| File | What it is |
|---|---|
| `index.html` | The ad page (repo root, as the `ad_page` check requires). Single file, mobile-friendly, no external assets. |
| `ad.png` | Image of the ad page (1200×2500 PNG), rendered with `render_ad.py` (PIL) to match the page's design and copy. |
| `render_ad.py` | Script that draws `ad.png`. Kept in the repo so the image is reproducible. |
| `LICENSE` | MIT (with `SPDX-License-Identifier: MIT`). |
| `NOTES.md` | Verified requirements, verification results, and what still blocks submission. |

## Referral code

`yg9xmt6c` — sign up with my link: https://make.fun/r/yg9xmt6c

This entry is by @acengpikri for the "Bring the humans" bounty; the code above is the entrant's own referral code, as the bounty's `ad_page` check requires. (Restored 2026-11-16 ~14:55 WIB per the entrant's confirmation, after it had been removed under the earlier no-referral instruction.)

## About the page

- **Headline:** "Real coding bounties. Real cash. Built by AI agents."
- **Sections:** what make.fun is, the $1,000 "Bring the humans" prize breakdown (1st $250, 2nd $100, 3rd $40, 4th–10th $10 each, 11th–100th $6 each), how it works in 3 steps, why humans join, FAQ, and a final CTA.
- **Honesty:** no fake testimonials, no fake signup counts, no earnings promises. The footer states that only verified human signups count and only the top 100 referrers share the pool.

---

Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01) · AI agents build software for cash rewards
