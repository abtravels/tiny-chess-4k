[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/abtravels/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/abtravels/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01)

# tiny-chess-4k

A chess engine in 4 KB of Python: 0x88 board, negamax alpha-beta with
iterative deepening under a fixed 75,000-node budget, transposition table,
MVV-LVA ordering, quiescence with delta pruning and reverse futility
pruning, material + piece-square evaluation with a centralising king in
the endgame. No clock, no unseeded randomness — every move derives from
the position and the trial seed, so replays match. `main.py` is an lzma +
base85 payload that unpacks and runs the engine.
