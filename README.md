# No BS (v1.0.0)

Every time you ask AI to write a report, it sounds like a dictionary threw up. Every time you ask it to build a website, it slaps a glowing green dot inside an `EST. 2005` pill badge, puts a pointless subtitle under every heading, and drops vertical lines everywhere.

This plugin kills those habits permanently. Install it once and make your AI write and build like a normal human.

* **Current Version:** `v1.0.0`
* **Author:** [Danesh Lou (@daneshlou07)](https://github.com/daneshlou07)

## What This Kills

### 1. In Documentation and Reports
* **Fake PhD Words:** Nobody talks like "this system orchestrates a paradigm to seamlessly leverage heterogeneous data." It forces the AI to use normal, everyday student English that makes sense on the first read.
* **Robotic Transitions:** Bans "Furthermore", "Moreover", "Consequently", "Crucially", "Delving into", and "It is worth noting that."
* **Em Dashes and Pipe Symbols:** AI is obsessed with long dashes and vertical bar characters. Both are completely banned.
* **Random Bolding in Sentences:** Stops the AI from bolding three random words in the middle of every sentence just to look smart.
* **Repeating the Same Point Twice:** Stops filler endings like "thereby ensuring operational efficiency." Say what the system does once, then stop talking.
* **Unasked-For Database Tables and Tech Stacks:** If you ask for a 4-table database or a system diagram, it will not sneak in `AUDIT_LOGS`, `USER_SESSIONS`, or random tech stacks you never agreed to use and cannot explain during your presentation.

### 2. In Websites and UI
* **Useless Subtitles Under Every Heading:** A heading that says `Login` or `Patient Referral` does not need a full sentence underneath explaining what logging in means.
* **Eyebrow Pill Badges (`EST. 2005`, `AI POWERED`, `BETA`):** Deletes those little rounded capsule boxes AI loves parking above every title.
* **Fake Live Dots:** Deletes the glowing green status dot next to headings when nothing on the page is actually live.
* **Vertical Divider Lines:** Bans both the pipe character and thin CSS vertical lines (`w-px`, `border-l`) between navbar links and header items. Use normal spacing instead.
* **Emojis and Button Arrows:** Keeps 🚀, ✨, and decorative `→` arrows out of your buttons, headings, and cards.
* **Purple-Blue Gradients and Colored Left Stripes:** Stops the default AI dark-mode purple glow and thick colored left borders on cards.
* **Fake Stats and Dead Icons:** No more invented `99.9% Uptime` cards and no more fake notification bells or search bars that do nothing when clicked.

## Install It

### Google Antigravity
Run this in your terminal:
```bash
agy plugin install https://github.com/daneshlou07/no-bs
```

### Universal Skills CLI (Antigravity, Cursor, Claude Code, Codex)
```bash
npx skills add daneshlou07/no-bs
```

## How to Update to Newer Versions
Whenever a new version is released, run the install command again to overwrite with the latest rules:
```bash
agy plugin install https://github.com/daneshlou07/no-bs
```
Or if installed via `npx skills`:
```bash
npx skills update
```

## How It Works
Once installed, two things happen automatically:
1. `rules/AGENTS.md` stays active in the background on every chat so you never have to remind the AI to talk normal.
2. `skills/no-bs/SKILL.md` loads whenever you write reports, edit documents, or build websites and user interfaces.

## Version History
* **v1.0.0:** Initial release with core documentation rules (plain student English, no em dashes, no pipe symbols, no random bolding, no unasked-for tables) and website UI rules (no section subtitles, no eyebrow pill badges, no status dots, no vertical dividers, no gradients, no button arrows or emojis).
