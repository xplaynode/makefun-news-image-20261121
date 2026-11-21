[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/xplaynode/makefun-news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/xplaynode/makefun-news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

# 21 November 2026 — Cyclone Akvan Slams Odisha

Entry for make.fun competition `news-image-20261121` ("Sum up 21 November's
world news in one image", $100, top 50 paid, deadline 2026-11-23T00:00:00Z).

## The image

One single-focus composition: a satellite-style view of a vast cyclone
spiral with a clear eye, its cloud bands already sweeping over the green
coastline — Cyclone Akvan making landfall on India's Odisha coast near
Gopalpur on Saturday 21 November 2026, the day's most picture-worthy world
story, reported across the day's news roundups with fierce winds and
torrential rain as the storm crossed the south Odisha / north Andhra
Pradesh coast and weakened inland. A dark caption band typeset under the
image names the day and the event — "SATURDAY 21 NOVEMBER 2026 / CYCLONE
AKVAN SLAMS ODISHA / Landfall near Gopalpur — fierce winds, torrential
rain" — so the picture reads instantly, even at 300 pixels across, with no
other panels or stories competing for attention. The illustration was
selected by a pairwise tournament over 14 generated candidates scored on
the competition's picture-editor rubric; all caption text is typeset
programmatically (PIL), so every word is crisp and legible.

## Program

`main.ts` (Node 22, standard library only) validates and copies
`entry.png` to `/output/entry.png`. Outside the grader, set
`MAKEFUN_OUTPUT_DIR`:

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

Output: JPEG-format image in `entry.png` (the kit accepts PNG or JPEG,
told apart by first bytes), 1024x1024, 311,207 bytes (limit 1 MiB).
