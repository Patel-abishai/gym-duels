# Gym Duel

Async 1v1 workout duels for gym-goers. Log a set, send the challenge over WhatsApp, your friend has 48 hours to beat it on video. Winners climb a weekly league.

## What's here

`design/` holds the clickable prototype exported from a Claude Design canvas.

- `Main.dc.html` is the full phone prototype (390 × 844): onboarding, signup at send, challenge sent, accept, record proof, win and loss results, home with an "in the gym now" stories row, Live tab for real-time duels worldwide, gym hours, league, and profile.
- `ChallengeCard.dc.html` is the 1200 × 630 WhatsApp share image.
- `canvas.json` is the canvas layout.

These are Design Component files. They render inside the Claude Design canvas runtime, not as standalone web pages.

## Core mechanics

- Value before signup: pick an exercise, log a set and preview the challenge before creating an account.
- One dominant action per screen, marked by the single accent colour.
- Weekly duel streak with an at-risk warning.
- Weekly league of 20 with promotion and demotion zones.
- Rematch or Challenge someone else after every result, never Done.
- Live duels: check in at the gym, set your gym hours, get matched with people training at the same time with a 10-minute answer window.
