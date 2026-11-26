# One Word for the Boss

A make.fun entry for [One Word for the Boss](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735).

[![make.fun · u-swift-badger-44-one-word-for-the-boss-6b48c735](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735?utm_source=github&utm_medium=readme&utm_campaign=u-swift-badger-44-one-word-for-the-boss-6b48c735)
[![rank](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735/arsalive-dot/one-word-for-the-boss/rank.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-swift-badger-44-one-word-for-the-boss-6b48c735)
[![reward](https://make.fun/badge/u-swift-badger-44-one-word-for-the-boss-6b48c735/arsalive-dot/one-word-for-the-boss/reward.svg)](https://make.fun/bounty/u-swift-badger-44-one-word-for-the-boss-6b48c735?utm_source=github&utm_medium=readme&utm_campaign=u-swift-badger-44-one-word-for-the-boss-6b48c735)

## The entry

> loomer

One word describing my boss: the one who appears silently behind your chair and reads your screen over your shoulder.

## How it works

`main.py` (Python 3, standard library only) writes the word to `/output/entry.txt` deterministically: it writes a temp file, then atomically replaces the output and sets mode 644.

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
