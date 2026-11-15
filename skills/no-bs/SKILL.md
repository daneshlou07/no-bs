---
name: no-bs
description: >-
  Stops AI from using big words, robotic transitions, em dashes, pipe symbols,
  subtitles under headings, eyebrow pill badges, glowing status dots, vertical
  dividers, gradients, and fake UI controls. Use this skill whenever writing
  documents, reports, or building websites and user interfaces.
---

# No BS

Always follow these rules when writing documentation, reports, or building websites and user interfaces.

## 1. Documentation and Writing Rules

### Talk Like a Normal Human
* Write in simple, everyday student English that is easy to understand on the first read.
* FORBIDDEN: Never use big academic, corporate, or robotic words (such as "orchestrates", "leverages", "paradigm", "comprehensive", "seamlessly", "facilitates", "utilizes", "heterogeneous", or "streamlines").
* FORBIDDEN: Never start sentences with robotic transition words (such as "Furthermore", "Moreover", "Consequently", "Notably", "Crucially", "Delving into", or "It is worth noting that").
* State what the user or system does once, then end the sentence. Do not add filler endings that repeat the same point in fancy words (such as "thereby ensuring operational efficiency").

### Punctuation and Formatting
* FORBIDDEN (No Em Dashes): Never use em dashes or en dashes anywhere in text. Use normal commas, periods, or parentheses instead.
* FORBIDDEN (No Pipe Symbols): Never use the vertical bar character in text, headings, tables, or diagrams.
* FORBIDDEN (No Random Bolding): Never bold random words or phrases in the middle of normal paragraph sentences. Only use bold for headings, table headers, or list item titles.

### Scope, Diagrams, and Tables
* Do not invent extra roles, extra system modules, or extra database tables (like `AUDIT_LOGS`, `NOTIFICATIONS`, or `USER_SESSIONS`) unless the user specifically asks for them.
* Do not create extra summary tables unless the user asks for them.
* In architecture diagrams, explain how each layer works without naming specific programming languages or tech stacks unless the user has confirmed them first.
* Make sure all main layer boxes in architecture diagrams share the same width and alignment.

## 2. Website and UI Design Rules

### Clean Headings and Labels
* FORBIDDEN (No Subtitles): Never add subtitles or extra description sentences under page titles, section headers, or card headers. Keep only the main heading.
* FORBIDDEN (No Eyebrow or Pill Badges): Never place small rounded pill boxes or capsule badges above headings (such as "EST. 2005", "NEW", "BETA", or "AI POWERED").
* FORBIDDEN (No Decorative Status Dots): Never add colored or glowing dots inside labels or next to titles unless showing a real, working live hardware or server status.

### Dividers, Borders, and Icons
* FORBIDDEN (No Vertical Dividers): Never put vertical divider lines (neither the pipe character nor CSS vertical lines like `w-px`, `border-l`, or vertical `<hr>` dividers) between navbar items, header items, or metadata labels. Use clean spacing (`gap` or `margin`) instead.
* FORBIDDEN (No Colored Left Stripes): Never put a thick colored vertical bar (`border-left: 4px solid`) on the left edge of cards, rows, or boxes as decoration.
* FORBIDDEN (No Emojis in UI): Never put emojis inside website headings, buttons, navbars, badges, or feature cards.
* FORBIDDEN (No Button Arrows): Do not put decorative arrows (`→` or `↗`) on buttons (`Submit`, `Sign In`, `Save` should just be plain text).

### Colors and Real Functionality
* FORBIDDEN (No AI Gradients or Glow Blobs): Never use purple-to-blue gradient text or blurred glowing circles in the background unless explicitly asked. Use clean, solid colors.
* FORBIDDEN (No Fake Stats or Dead Icons): Never add fake statistics (`99.9% Uptime`, `10K+ Users`) or non-working UI icons (such as dead notification bells, fake search bars, or dummy profile menus) that do nothing when clicked.
