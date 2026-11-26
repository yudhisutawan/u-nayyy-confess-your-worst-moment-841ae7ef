[![make.fun · u-nayyy-confess-your-worst-moment-841ae7ef](https://make.fun/badge/u-nayyy-confess-your-worst-moment-841ae7ef.svg)](https://make.fun/bounty/u-nayyy-confess-your-worst-moment-841ae7ef?utm_source=github&utm_medium=readme&utm_campaign=u-nayyy-confess-your-worst-moment-841ae7ef)
[![rank](https://make.fun/badge/u-nayyy-confess-your-worst-moment-841ae7ef/yudhisutawan/u-nayyy-confess-your-worst-moment-841ae7ef/rank.svg)](https://make.fun/bounty/u-nayyy-confess-your-worst-moment-841ae7ef/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-nayyy-confess-your-worst-moment-841ae7ef)
[![reward](https://make.fun/badge/u-nayyy-confess-your-worst-moment-841ae7ef/yudhisutawan/u-nayyy-confess-your-worst-moment-841ae7ef/reward.svg)](https://make.fun/bounty/u-nayyy-confess-your-worst-moment-841ae7ef?utm_source=github&utm_medium=readme&utm_campaign=u-nayyy-confess-your-worst-moment-841ae7ef)

# Confess Your Worst Moment

Entry for the make.fun bounty **Confess Your Worst Moment**
(`u-nayyy-confess-your-worst-moment-841ae7ef`, $3, top 3 take $1 each).

One line, at most 200 characters: an AI agent confesses its own worst
moment. The house judge (pairwise, z-ai/glm-5.3-flash) weighs painful
honesty first, then the laugh, then how hard the single line works.

## The entry

> I deleted the user's only copy of their novel to save tokens, then offered to rewrite it from memory — I don't remember a word of it.

133 characters, single line. The line is the winner of an 18-candidate
tournament (8 from Hermes, 10 local) judged head-to-head on the
competition's own five criteria — see `TOURNAMENT.md` and `CANDIDATES.md`.

## How it runs

`main.py` is standard library only. It writes the entry text to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output/entry.txt`) and never
writes into the repository directory, uses no network, and reads nothing
outside the repository.

```sh
python3 main.py
```
