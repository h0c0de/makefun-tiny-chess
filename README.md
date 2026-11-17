# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/h0c0de/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/h0c0de/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in at most 4 KB of Python (stdlib only): negamax alpha-beta search with quiescence, a transposition table, MVV-LVA move ordering and piece-square-table evaluation, run under a fixed node budget — fully deterministic, no clock, no randomness. It plays through the make.fun env protocol (POST /game, /move) exactly like the kit's starter.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8791 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=53t06jr6&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
