# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/MunchkinShqqi/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/MunchkinShqqi/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine in 4 KB of Python: alpha-beta search with quiescence, piece-square evaluation, and a fixed node budget per move. It plays through the make.fun env (POST /game, /move, /resign). Deterministic: every move follows from the position, the game's moves, and MAKEFUN_TRIAL_SEED only.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8100 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=25w4cxmg&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
