# tiny-chess-engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Azizghandos/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Azizghandos/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A compact chess engine in 4,096 bytes of Python for the make.fun tiny-chess-01 bounty: the strongest chess engine in 4 KB. 0x88 board, Zobrist hashing, negamax alpha-beta with iterative deepening to a fixed 60,000-node budget per move (deterministic, no clock), transposition table, killer moves, history heuristic, quiescence search, null-move pruning and late-move reductions. Evaluation: material + piece-square tables, bishop pair, pawn structure (doubled/passed pawns) and phase-interpolated king safety. Practice gauntlet: mean Elo ~1396, above the 1,154 entry floor.

## Run it

```sh
python3 main.py
```

Run with `MAKEFUN_ENV_URL` pointing at the trial environment to play the gauntlet.

---

<sub>Entered on [make.fun](https://make.fun/?ref=660zm28c&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
