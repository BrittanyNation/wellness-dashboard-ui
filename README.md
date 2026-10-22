# Lumen Studio — Wellness Dashboard UI Concept

An original dashboard UI concept for a fictional boutique yoga & pilates studio: an overview, a class schedule view, and a members view that give a small-studio owner bookings, class fill, retention signals, and weekly revenue at a glance.

**Live demo:** https://brittanynation.github.io/wellness-dashboard-ui/

## Roles this supports

Built to support applications for **UI Designer**, **Front-End Designer**, **Web Designer**, and **Junior UI/UX Designer** roles — product-interface work that sits between visual design and front-end implementation.

## What it demonstrates

- **Dashboard information architecture** — one job per view: Overview ("how is today?"), Schedule ("what's on and who's teaching?"), Members ("who needs a nudge?")
- **Data visualization with restraint** — labeled fill bars with plain numbers, stat cards with context (not just big numbers), and status badges that use words, never color alone
- **Warm, brand-matched data design** — deep plum for calm authority, coral for action, apricot for highlights, warm cream backgrounds; a wellness product that doesn't look like accounting software
- **Accessibility-minded choices** — contrast-safe text pairings, visible structure, a real `<table>` for the schedule, skip link, `aria-current` navigation, and status always paired with text
- **Responsive layout** — stat grids step from four columns to two to one, panels stack, and the schedule table scrolls safely on small screens
- **Semantic, framework-free build** — hand-written HTML/CSS, one stylesheet, no JavaScript required, no external images; all visuals are CSS-only

## Palette

| Token | Hex | Use |
| --- | --- | --- |
| Deep Plum | `#2D1B3D` | Header, dashboard shell head |
| Coral | `#FF6B4A` | Primary actions, fill bars |
| Apricot | `#FFB25E` | Highlights, celebrations |
| Warm Cream | `#FFF7ED` | Page background |
| Ink | `#24182E` | Body text |

## Contents

| Page | What it covers |
| --- | --- |
| `index.html` | Portfolio intro + live overview dashboard (stat cards, class-fill bars, needs-attention list) + design notes and palette |
| `schedule.html` | Thursday timetable: time, class, instructor, room, booked count, and status |
| `members.html` | Retention view: trials ending, quiet members, milestones, and a follow-up list |

## Workflow note

My design workflow runs in **Sketch and Webflow**, where I design interfaces and systems visually. This demo is hand-built in HTML/CSS to show the same dashboard thinking — information architecture, hierarchy, and states — expressed directly in code.

## Files

- `index.html` — overview / landing for the concept
- `schedule.html` — schedule view
- `members.html` — members view
- `styles.css` — design tokens and all component styles
- `og-image.png` — 1200×627 social preview image in the project palette

## Note

This is an original portfolio concept created by Brittany Nation. Lumen Studio is a fictional business; this project is not affiliated with any real studio or software product. All names and data shown are sample data.
