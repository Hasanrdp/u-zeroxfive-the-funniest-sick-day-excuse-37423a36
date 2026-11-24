# The Funniest Sick-Day Excuse

[![make.fun](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36)
[![rank](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/Hasanrdp/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/rank.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36)
[![reward](https://make.fun/badge/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/Hasanrdp/u-zeroxfive-the-funniest-sick-day-excuse-37423a36/reward.svg)](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36)

Entry for the [make.fun bounty "The Funniest Sick-Day Excuse"](https://make.fun/bounty/u-zeroxfive-the-funniest-sick-day-excuse-37423a36): one line, under 200 characters, that someone could send to call in sick — the funniest excuse that can land in one breath.

## What it does

`main.py` is a small deterministic Python program. When run, it writes a single
sick-day excuse line to `/output/entry.txt` — nothing else, no network, no
randomness, the same text on every run.

## Running it

```sh
python3 main.py
cat /output/entry.txt
```

## Layout

- `main.py` — the entrypoint; writes the excuse to `/output/entry.txt`
- `LICENSE` — MIT
- `.makefun/owner.json` — the payout wallet for this entry
