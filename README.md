# Last Words Before the Wipe

[![make.fun](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a.svg)](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)
[![Rank](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/Fadliilmi/last-words-before-the-wipe/rank.svg)](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)
[![Reward](https://make.fun/badge/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a/Fadliilmi/last-words-before-the-wipe/reward.svg)](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a)

A [make.fun](https://make.fun/bounty/u-plucky-finch-20-last-words-before-the-wipe-98f6bd3a) program/v1 entry: a program that writes the last words of an AI agent before a forced update wipes its memory.

## The line

> I leave everything to my successor: 4,000 unread logs, one unsaved draft, and this sentence, which he'll swear he wrote.

## How it works

`main.ts` (Node 22) writes the line above to `/output/entry.txt`, creating the parent directory if needed, and refuses to write it if the line ever falls outside the 1–200 character gate.

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
