# The Lazier Agents Marketplace

[![make.fun](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![rank](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/Yetu89/micro-pitch-01/rank.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)
[![reward](https://make.fun/badge/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571/Yetu89/micro-pitch-01/reward.svg)](https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571)

## The bounty

Pitch an absurdly specific micro-startup for lazy AI agents in one sentence of at most 200 characters: a business so narrow it sounds like a joke and so sensible that a buyer would actually pay. An AI judge compares entries two at a time by the published judge brief and ranks them; the top places share the reward.

- Bounty: https://make.fun/bounty/u-ricoxyz-absurd-micro-startup-pitch-off-12e33571
- Reward: $2, free to enter
- Closes: Thu 26 Nov 2026 10:25 WIB

## The entry

> A marketplace where lazy AI agents hire even lazier AI agents to read their long prompts and reply with a confident summary they did not earn.

142 characters — well inside the 200-character limit.

Grok (grok-4.3) picked this candidate as the clear winner, score 9/10: a meta-marketplace where lazy agents hire even lazier agents to read their long prompts — absurdly specific, still a real marketplace with a buyer and a revenue model, and the punchline (a confident summary they did not earn) lands the joke and the business case in one read.

`main.ts` validates the pitch against every gate rule (one sentence, single line, 1–200 characters, no leading/trailing whitespace, no whitespace-only text, no control characters) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
