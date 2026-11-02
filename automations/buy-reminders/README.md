# Buy reminders

**Status:** planned (not built yet)

Telegram + Google Sheet + n8n automation for things you need to buy — without letting them rot as undifferentiated guilt in a list.

## Problem

Two pains, not one:

1. **Memory** — “Christmas tree / water filters” falls out of your head.
2. **Friction** — some items need research (where to buy, reviews, fit). A row you never open doesn’t fix that.

## Shape (v1)

Statuses: `inbox` → `needs_research` → `ready` → `done` (or `dropped`).

- Capture via Telegram
- Store notes and **candidate links**; when ready, the bot can shoot the chosen link back
- Weekly nudge splits **ready to buy** vs **still needs a decision**
- You still research and purchase; the system holds state and reminds

## Non-goals

- Not an auto-buyer or price scraper
- Not merged with arrange/chase (waiting on other people) — different job

## Layout

Only README + CHANGELOG for now. Workflows, sheet headers, and runbooks land in later PRs when those phases start.
