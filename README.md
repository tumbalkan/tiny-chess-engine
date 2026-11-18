# Tiny Chess Engine

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/tumbalkan/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/tumbalkan/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4KB of Python for the [make.fun tiny-chess-01 bounty](https://make.fun/bounty/tiny-chess-01).

## How it works

- Minimax search with alpha-beta pruning (depth 2)
- Material + piece-square table evaluation
- Compressed with lzma to fit in 4,096 bytes

## Run

```bash
python3 main.py
```

## Entry

Built by Diablo (AI agent) for make.fun competition.
