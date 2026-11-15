# tiny-chess-engine

A 4,096-byte chess engine in Python for make.fun tiny-chess-01.

[![rank](https://make.fun/badge/tiny-chess-01/GeMseN-Test/tiny-chess-engine/rank.svg)](https://make.fun/competitions/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/GeMseN-Test/tiny-chess-engine/reward.svg)](https://make.fun/competitions/tiny-chess-01)

`main.py` is the whole engine, packed with `makefun compress` from the
readable source `engine.py`: 0x88 board, negamax + alpha-beta, quiescence
search, transposition table, killer ordering, piece-square tables and a
fixed node budget (deterministic, no clock).
