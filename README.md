# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/renhongyu6666-cyber/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/renhongyu6666-cyber/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original 0x88 chess engine in 4,096 bytes of Python: negamax with PVS, a transposition table, null-move pruning, late-move reductions, check extensions and quiescence search, over an incremental material and piece-square evaluation. Local practice trials against the house gauntlet measured Elo 1654 on both practice instances (two-instance mean 1654), winning 5 of 6 games in each.

## Run it

```sh
MAKEFUN_ENV_URL=<trial env url> MAKEFUN_PROMPT_FILE=/input/prompt.txt python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=qx8twn3b&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
