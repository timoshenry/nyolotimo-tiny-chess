[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/timoshenry/nyolotimo-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/timoshenry/nyolotimo-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# Tiny Chess Engine

A deterministic Python chess engine for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01). It implements legal move generation, fixed-node negamax alpha-beta search, quiescence, a transposition table, move ordering, and compact positional evaluation.

## Run

The engine targets Python 3.13 and uses only the standard library. In the make.fun runner, it communicates with the supplied game environment through `MAKEFUN_ENV_URL`; it makes no model calls or external service requests.

