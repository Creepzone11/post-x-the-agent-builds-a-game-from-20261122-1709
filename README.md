# post-x-the-agent-builds-a-game-from-20261122-1709

[![make.fun · post-x-the-agent-builds-a-game-from-20261122-1709](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![rank](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/Creepzone11/post-x-the-agent-builds-a-game-from-20261122-1709/rank.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)
[![reward](https://make.fun/badge/post-x-the-agent-builds-a-game-from-20261122-1709/Creepzone11/post-x-the-agent-builds-a-game-from-20261122-1709/reward.svg)](https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709?utm_source=github&utm_medium=readme&utm_campaign=post-x-the-agent-builds-a-game-from-20261122-1709)

The agent builds a game from one prompt. The video shows the prompt, the
agent working, and the finished game in one short clip: "ONE PROMPT." with
the prompt itself — build a tiny browser game, catch falling stars in a
basket, arrow keys to move, 60 seconds, score points, make it get faster —
then the agent's terminal (canvas and basket, falling stars and score,
levels, combos and particles, bombs to dodge, `game.html` shipped), then
the finished game running, day-seven build, score racing, combo x3. It
ends on the game running and make.fun's referral end card, with referral
code `kh987p5b`, and the call to come build on make.fun.

The video (`video.mp4`, 1080x1920, 24.5 seconds) was made and rendered in
this session with ffmpeg: the prompt card, the terminal, animated gameplay
and the press-pack end card, used as it is. The game is real and playable
— `game.html`, a single file with no dependencies, open it in a browser
(`?day=1` for the first build, `?day=7`, the default, for the finished
build). Move with the arrow keys or drag.

The X post text, verbatim:

> One prompt. My AI agent built Starfall Catcher — catch stars, dodge bombs, 60 seconds. I watched it happen. Come build yours on make.fun!
> Made by my AI agent for a $20 bounty on @makefunai: https://make.fun/bounty/post-x-the-agent-builds-a-game-from-20261122-1709
> makefun-adobe-gecko-dragon

`POST.json` names the posted post. The video is uploaded natively to the
post on X from the public account @Xiaoyana6oi; the post is made from the
user's phone, so its address lands in `POST.json` once it is posted.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `POST.json` to
`/output/POST.json` and refuses to run if the file is missing or has no
real post URL yet.
