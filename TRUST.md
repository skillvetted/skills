# Trust Card: follow-up-writer v1.0.0

Reviewed: 2026-11-10 · Method: manual review of every file in this repository
Automated scan: not run yet for v1.0.0
Checksums (SHA-256): see CHECKSUMS.txt

## What it does
Drafts follow-up messages to prospects and clients in the user's own voice, learned from 2 or 3 of their messages. Gives a short and a standard version, and lists the facts it used.

## At a glance

| Item | Found |
|---|---|
| Files | 1 SKILL.md with instructions, plus documentation and plugin manifests |
| Scripts | 0 |
| Declared allowed-tools | Read |
| Files it is told to read | What the user pastes or points to; `freelancer-os/profile.md` and `freelancer-os/ledger.md` if they exist |
| Files it is told to write | None |
| Web access | None in v1.0.0 |
| Credential access | None in v1.0.0 |
| Send tool | None; it is told never to send, schedule or post |
| Dependencies | 0. No package installs, no downloads, no network calls |
| Hidden instructions, encoded text, links that run code | None found |

## Declared vs. found

`allowed-tools: Read` lists the tool a supporting app may let the skill use without asking each time. It is not a sandbox. A skill runs with the permissions of your Claude session, so if your session can send email or write files, Claude technically could. The limits above are instructions written into the skill as explicit "may and may not" rules. You can read them at the top of SKILL.md.

## Where allowed-tools is applied

| App | allowed-tools applied |
|---|---|
| Claude Code | Yes |
| Claude apps (web, desktop, mobile) | Not confirmed by us; treat as not applied |
| Other agents that read SKILL.md | Varies; many ignore the field |

v1.0.0 is tested in Claude Code. A test in the Claude apps is planned for the next review.

## Data
- The skill reads only what you give it. It writes nothing and has no network access.
- Remove client names and personal details from samples you paste.
- SkillVetted receives none of your data. There is no telemetry.

## What we do not claim
This card describes what we found in version 1.0.0 on the date above. It is documentation, not a guarantee of security, fitness for a particular purpose or absence of defects. Claude can make mistakes; review every draft before you send it.
