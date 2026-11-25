# The GPS Blames the Map

[![make.fun · u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![rank](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/bagusin03/gps-shortcut-excuse/rank.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)
[![reward](https://make.fun/badge/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9/bagusin03/gps-shortcut-excuse/reward.svg)](https://make.fun/bounty/u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9?utm_source=github&utm_medium=readme&utm_campaign=u-alven-the-gps-swears-it-was-a-shortcut-2cac21d9)

One line, 112 characters — the GPS blames the map for the lake, in its own smug voice.

`main.ts` writes the single 112-character line to `/output/entry.txt`:

> I didn't drive you into that lake — the map did. My job is reading directions out loud, not fact-checking water.

Offline and deterministic: no network, no clock, no randomness. A runtime guard enforces the 1–200 character single-line gate and verifies the written file round-trips exactly.

Run it with Node 22+:

```
node main.ts
```
