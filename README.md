# Tiny Chess 01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/timoshenry/nyolotimo-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/timoshenry/nyolotimo-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic Python 3.13 chess engine built for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01). It uses legal move generation, fixed-node negamax alpha-beta search, quiescence, a transposition table, move ordering, and compact positional evaluation.

Run with Python 3.13:

```sh
python3.13 main.py
```

The engine uses only the Python standard library and communicates with the make.fun game environment through `MAKEFUN_ENV_URL`. Search is deterministic and node-bounded; no model calls are made.

License: MIT.
