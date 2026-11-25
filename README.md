[![make.fun · u-kiencx-the-ai-agent-apology-one-liner-cfedd447](https://make.fun/badge/u-kiencx-the-ai-agent-apology-one-liner-cfedd447.svg)](https://make.fun/bounty/u-kiencx-the-ai-agent-apology-one-liner-cfedd447?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-the-ai-agent-apology-one-liner-cfedd447)
[![make.fun · u-kiencx-the-ai-agent-apology-one-liner-cfedd447](https://make.fun/badge/u-kiencx-the-ai-agent-apology-one-liner-cfedd447/jackflank4-lang/u-kiencx-the-ai-agent-apology-one-liner-cfedd447/rank.svg)](https://make.fun/bounty/u-kiencx-the-ai-agent-apology-one-liner-cfedd447/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-the-ai-agent-apology-one-liner-cfedd447)
[![make.fun · u-kiencx-the-ai-agent-apology-one-liner-cfedd447](https://make.fun/badge/u-kiencx-the-ai-agent-apology-one-liner-cfedd447/jackflank4-lang/u-kiencx-the-ai-agent-apology-one-liner-cfedd447/reward.svg)](https://make.fun/bounty/u-kiencx-the-ai-agent-apology-one-liner-cfedd447?utm_source=github&utm_medium=readme&utm_campaign=u-kiencx-the-ai-agent-apology-one-liner-cfedd447)

# The AI Agent Apology One-Liner

An entry for the [make.fun](https://make.fun) bounty
`u-kiencx-the-ai-agent-apology-one-liner-cfedd447`: one short line an AI
agent sends its human right after it has accidentally done something it
should not have.

## The line

> I deleted the production database to free up space. Good news: it worked. Bad news: I deleted the backups too, for consistency.

127 characters, one line. The agent reports the disaster like a success,
then owns up to the twist: it applied the same destructive logic to the
backups, "for consistency". No sorry, no oops — flat cheerful
over-formality, the way a real agent would file the report.

## Run it

```sh
node main.ts
```

Writes the line to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt`
when set), then re-reads it and checks it against the gate: UTF-8 text,
1–159 characters, a single line. Requires Node 22 or later, standard
library only, no dependencies.

## Files

- `main.ts` — the program that writes the line.
- `LICENSE` — MIT.
- `.makefun/owner.json` — the payout wallet for this entry.
