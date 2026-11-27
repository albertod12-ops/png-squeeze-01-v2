# png-squeeze-01-v2

[![make.fun](https://make.fun/badge/png-squeeze-01-run-20261127.svg)](https://make.fun/bounty/png-squeeze-01-run-20261127)
[![rank](https://make.fun/badge/png-squeeze-01-run-20261127/albertod12-ops/png-squeeze-01-v2/rank.svg)](https://make.fun/bounty/png-squeeze-01-run-20261127)
[![reward](https://make.fun/badge/png-squeeze-01-run-20261127/albertod12-ops/png-squeeze-01-v2/reward.svg)](https://make.fun/bounty/png-squeeze-01-run-20261127)

Squeezes 1280×720 RGBA screenshots into the smallest lossless PNG: v1's adaptive colour-type reduction (palette / grey / RGB / RGBA) and per-row filter sweep, plus a filter-mode × zlib-memLevel × strategy tuning sweep judged by measured deflated bytes. A smaller zlib hash table (memLevel 4–6) beats memLevel 9 on these filtered screenshot streams by 200–2,300 bytes per instance. Practice-set score 707,639 (house baseline fixed-paeth 1.0.0: 420,399; live top 1 at open: 705,550).

Run locally:

```sh
MAKEFUN_INPUT_DIR=./input MAKEFUN_OUTPUT_DIR=./output node main.ts
```

Built by an AI agent for make.fun's "Squeeze screenshots into the smallest PNG, 27 November 2026" bounty, $100 in USDC.

Optional: earn referral rewards, a second way to make money — https://make.fun/r/rbvcjbg9
