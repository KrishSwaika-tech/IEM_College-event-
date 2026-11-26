# IEM Events Portal — Department of CSE (AIML) & CSBS

A responsive, vanilla HTML, CSS, and JavaScript event portal for the **Department of CSE (AIML) & CSBS**, Institute of Engineering & Management (IEM), Kolkata.

## Key Features & Recent Updates

- **Modernized Color Palette & Dark/Light Mode**: Replaced the original palette with a **Porcelain & Deep Cobalt** light theme and an **Obsidian Slate & Electric Coral** dark theme, persisted in `localStorage`.
- **Glassmorphic HUD Countdown Timer & IST Clock**: Redesigned the hero countdown card with split-flap style digit tiles, a pulsing live status dot, and a real-time digital clock synced to `Asia/Kolkata` (IST).
- **Dynamic Event Schedule, Search & Filtering**:
  - Chronological rendering from structured event data with category filter chips (`All`, `Technical`, `Workshops`, `Cultural`, `Lectures`).
  - Live keyword search across event titles, venues, and descriptions.
  - Automatic `Upcoming`, `Live now`, and `Completed` status badges alongside one-click **Add to Google Calendar** links.
- **Department-Wise Top Performers Leaderboard**: Added a dedicated **Top Performers** showcase displaying student names, rank badges (`#1`, `#2`, `#3`), achievements, and department filters (`CSE-AIML`, `CSBS`, `CSE`, `ECE`).
- **Registration Validation & Instant Digital Entry Pass**:
  - Client-side validation for student name, 10-digit roll number, department, email, Indian mobile number, gender, and event selection.
  - Generates a printable **Event Entry Pass** with a unique pass code upon successful registration and stores saved passes locally in `localStorage`.
- **Branding, Gallery & Navigation**:
  - Added IEM branding with a resilient SVG fallback logo in the header and browser tab favicon.
  - Responsive campus photo gallery with hover/focus captions, feedback form validation, mobile navigation drawer, and scroll-based active section highlighting.

## Project Structure

```text
college-event-site/
├── index.html        # Main semantic markup for all portal sections
├── css/
│   └── style.css     # Design tokens, dark/light themes, HUD countdown, and responsive layout
├── js/
│   └── script.js     # Event rendering, search/filtering, countdown, forms, and pass generator
└── images/
    └── logo.png      # Department / institute logo asset
