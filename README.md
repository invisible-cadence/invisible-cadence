# Invisible Cadence

Official GitHub for [Invisible Cadence](https://www.invisiblecadence.com) — documented automations, workflows, and build notes.

Small systems that reclaim time without the hustle. Human stays in the loop; tools handle memory and follow-up.

## Stack

Typical pieces: **Telegram**, **Google Sheets**, **n8n Cloud**. Other tools appear when they fit better.

## Repository layout

```
automations/
  buy-reminders/     # first automation (in progress)
```

Each automation lives under `automations/<name>/` with its own README and CHANGELOG. Extra folders (workflows, sheet headers, runbooks) are added only when that automation needs them.

## Working agreements

- One concern per pull request
- No secrets in git (tokens, `.env`, credential exports)
- Prefer small, real systems over life-OS theatre

## Site

[invisiblecadence.com](https://www.invisiblecadence.com) · hello@invisiblecadence.com
