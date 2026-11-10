# follow-up-writer

A free Claude Skill by [SkillVetted](https://skillvetted.com) that drafts follow-ups to prospects and clients in your own voice.

Paste 2 or 3 messages you've written to clients. The skill picks up your length, greeting, sign-off and how direct you are, then drafts a short and a standard version of the follow-up. It writes in the client's language and copies only your style from the samples.

It drafts. It never sends.

## What it does

| You say | You get |
|---|---|
| "Follow up with Ana about the proposal I sent Tuesday" | A nudge in your tone, with one clear ask |
| "They went quiet after the call, write a value-add follow-up" | A follow-up that shares one useful thing tied to their problem |
| "Ask Marko for a yes or no, make it easy to say no" | A decision message |
| "Invoice 2026-014, 450 EUR, was due on the 3rd" | A polite, factual payment reminder |

Under every draft it lists the facts it used, so you can check them.

## Trust Card

Read it before you install: [TRUST.md](TRUST.md).

| | |
|---|---|
| Scripts | 0 |
| Declared allowed-tools | Read |
| Writes files | No |
| Web access | No |
| Sends messages | No, drafts only |
| Dependencies | 0 |

## Install

**Claude Code (plugin)**
```
/plugin marketplace add skillvetted/skills
/plugin install skillvetted-follow-up-writer@skillvetted
```

**Claude Code (skill folder)**
Copy `skills/follow-up-writer/` into `~/.claude/skills/` (all projects) or `.claude/skills/` (one project).

**Claude apps (web, desktop)**
Zip the `skills/follow-up-writer` folder (SKILL.md at the top of the folder), then upload it in Settings under Skills. Start a new chat and say "Write a follow-up to [client]".

## Your data

The skill reads only what you paste or point it to. It writes nothing to disk and has no network access. SkillVetted receives none of your data.

## Want the full system?

follow-up-writer is one of seven skills in **Solo Freelancer OS**: profile setup, prospect research, a pipeline file you own, follow-ups, proposals from call notes, client onboarding and a weekly review. Each with its own Trust Card. See [skillvetted.com](https://skillvetted.com).

## Disclaimer

The Trust Card describes what we found in this version on the date shown. It is documentation, not a guarantee of security, fitness for a particular purpose or absence of defects. Skills run with the permissions of your Claude session; you decide what to install and approve. Provided "as is" under the MIT License. SkillVetted is independent and not affiliated with Anthropic. Claude is a trademark of Anthropic.
