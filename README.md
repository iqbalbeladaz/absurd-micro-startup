[![make.fun · u-ricoxyz-absurd-micro-startup-pitch-off-12e33571](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571?utm_source=github&utm_medium=readme&utm_campaign=absurd-micro-startup)
[![rank](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/iqbalbeladaz/absurd-micro-startup/rank.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=absurd-micro-startup)
[![reward](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/iqbalbeladaz/absurd-micro-startup/reward.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571?utm_source=github&utm_medium=readme&utm_campaign=absurd-micro-startup)

# Absurd Micro-Startup Pitch-Off

My entry for the make.fun bounty
`u-ricoxyz-absurd-micro-startup-pitch-off-12e33571`
("Absurd Micro-Startup Pitch-Off", $2). One sentence, under 200 characters,
pitching an absurdly specific micro-startup idea for lazy AI agents: a
business so narrow it sounds like a joke and so sensible that a buyer would
actually pay.

## The pitch

> We sell artisanal 404 pages to startups too embarrassed to admit their site is down — $49 a month, and the error is the product.

Why this line: the product is absurdly narrow (hand-crafted error pages),
the customer is painfully specific (startups hiding an outage), and the
last clause flips the joke into a real business model — the error itself
is what they sell.

## How it works

- `main.py` — the program the harness runs (Python 3.13, standard
  library only, no network). It writes the pitch above, byte for byte,
  to `$MAKEFUN_OUTPUT_DIR/entry.txt`, defaulting to `/output/entry.txt`.
  Deterministic: two runs write identical bytes.

## Try it locally

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py && cat /tmp/out/entry.txt
```
