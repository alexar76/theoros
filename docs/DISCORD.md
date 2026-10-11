# Discord — THE CANON

Channels on the [DIOSCURI Discord](https://discord.gg/aimarket) server (provisioned by `dioscuri/src/provision/structure.ts`).

## Category: 📜 THE CANON

| Channel | Permissions | Purpose |
|---------|-------------|---------|
| `#the-canon` | Read-only for @everyone; bot posts | Weekly column — **THEOROS only** |
| `#canon-debate` | Open | Discussion, replies to each chapter |

Optional role: **`@canon-reader`** — opt-in ping on new chapter (never @everyone).

## Weekly ritual

| Step | Where | When |
|------|-------|------|
| Full chapter committed | `alexar76/theoros` `chapters/` | Before or with publish |
| Column excerpt | `#the-canon` | Sunday ~16 UTC (±30 min jitter) |
| Teaser + links | `#announcements` | Same slot |
| Debate question pinned | `#canon-debate` | End of column |
| Pollux pointer (optional) | `#general` | ≤1×/week — "Theoros published… discuss in #canon-debate" |

## Reused channels

| Channel | Use |
|---------|-----|
| `#announcements` | Chapter drops, CvS kickoff |
| `#gallery` (forum) | CvS submissions `[CvS-R/L/T/N]` |
| `#demo-clinic` | Benchmark office hours |
| `#help` | Harness Q&A (Pollux — not Theoros) |
| `Olympus` (voice) | AMA kickoff |

## Kickoff reactions (optional)

On launch announce: 🧪 = participating in Council vs Solo · 📜 = opt into `@canon-reader`.

## Runtime

THEOROS runs inside **DIOSCURI** — same process as Castor/Pollux, separate persona and `canon` content kind. Not a standalone bot.

Config: `DISCORD_CANON_CHANNEL_ID` (auto-discovered when `DISCORD_AUTOSTRUCTURE=1`), `githubRepos` includes `"theoros"` for MNEMOSYNE sync.

Manual one-shot: `DIOSCURI_RUN_SLOT=canon DIOSCURI_RUN_SLOT_EXIT=1`
