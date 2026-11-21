[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/abtravels/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/abtravels/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01)

# tiny-chess-4k

A chess engine in 4 KB of Python: 0x88 board, negamax alpha-beta with
iterative deepening under a fixed 75,000-node budget, transposition table,
killer-move and history-heuristic ordering with MVV-LVA, check extensions,
quiescence with delta pruning and reverse futility pruning, tapered
middlegame/endgame material + piece-square evaluation with a bishop-pair
bonus and a king pawn-shield term (missing shield pawns penalised in the
middlegame). No clock, no unseeded randomness — every move derives from the
position and the trial seed, so replays match. `main.py` is the kit's own
makefun-compress pack of `engine.py`: an LZMA stream that unpacks and runs
the engine.
