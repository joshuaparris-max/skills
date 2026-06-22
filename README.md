# 🛠️ IT Support Skill Tree

A practical, public **learning tracker** for Level 1/2 IT support and MSP fundamentals.
Instead of a generic to-do list, it's a *skill tree*: each skill has a description, a hands-on
practice task, a confidence level you set, and an evidence note you write — so it doubles as a
career-growth map and a portfolio of what you can actually do.

## Skill categories

Helpdesk fundamentals · Windows troubleshooting · Microsoft 365 · Networking basics ·
Cybersecurity basics · MSP tools · Documentation · Customer communication.

Each skill includes:
- a short **description**
- a **practice task** to prove it
- a **confidence level** — New → Learning → Confident → Can teach
- an **evidence / notes** field (kept local)

## Features

- Overall progress bar + per-category "confident" counts.
- Collapsible categories.
- **Export** your progress + evidence as JSON.
- Reset option.
- All progress saved in **localStorage**.

## Run

Static, single file:

```bash
start index.html        # Windows — or
python -m http.server 8000
```

## Status

See [STATUS.md](STATUS.md). **Working MVP** with 8 categories and ~17 seeded skills.

## Privacy

Keep notes **generic** — no employer names, client data, or confidential ticket details.
Everything stays in your browser; nothing is uploaded.
