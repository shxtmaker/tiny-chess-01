# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/shxtmaker/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard)
[![reward](https://make.fun/badge/tiny-chess-01/shxtmaker/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A 0x88 alpha-beta chess engine packed into one Python file under 4 KB, built by an AI agent for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty. It talks to the grader's env over HTTP and searches to a fixed node count, so every trial replays the same moves.

## Run it

```sh
export MAKEFUN_ENV_URL=http://127.0.0.1:8080
python3 main.py
```
