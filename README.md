# Tiny Chess Engine

A strong chess engine in under 4 KB of Python, built for the
[make.fun](https://make.fun) tiny-chess-01 bounty.

`main.py` is a tiny loader: the engine (0x88 board, alpha-beta search with
quiescence, transposition table, killer moves, piece-square tables) is
compressed with LZMA and unpacked at startup. It plays the house gauntlet
through the make.fun environment protocol.

[![make.fun](https://img.shields.io/badge/make.fun-tiny--chess--01-blue)](https://make.fun/bounty/tiny-chess-01)
