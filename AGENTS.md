# AGENTS.md

## Project Overview

This project is for planning trips and compiling the plan into static HTML reports.

The final output should be easy to publish with GitHub Pages as static HTML. Keep the project simple, portable, and friendly to future edits.

## Working Language

- Use Japanese for project notes, reports, and user-facing travel content unless the user asks otherwise.
- Keep place names, transport names, hotel names, and official service names in their commonly used original or bilingual form when that helps accuracy.

## Main Deliverables

- Static HTML travel reports.
- Supporting assets such as CSS, images, maps, schedules, tables, and itinerary data.
- Clear source notes for prices, schedules, links, and other time-sensitive travel information.

## Recommended Structure

Use this structure unless the project naturally grows in another direction:

```text
.
├── index.html
├── assets/
│   ├── css/
│   ├── images/
│   └── data/
├── reports/
└── notes/
```

- `index.html`: main published page or entry point for GitHub Pages.
- `reports/`: separate trip reports or destination-specific pages.
- `assets/css/`: shared styles.
- `assets/images/`: photos, maps, and visual material.
- `assets/data/`: structured itinerary data, budgets, or reference tables.
- `notes/`: private or draft planning notes that may not be ready for publication.

## HTML Report Guidelines

- Build static, dependency-light HTML that works on GitHub Pages without a backend.
- Prefer semantic HTML with accessible headings, tables, lists, and links.
- Keep CSS in separate files once a page becomes more than a quick draft.
- Make pages readable on both desktop and mobile.
- Include practical travel sections when relevant:
  - overview
  - itinerary
  - transport
  - accommodation
  - budget
  - food and activities
  - maps and links
  - reservations and deadlines
  - open questions

## Research And Accuracy

- Travel information changes often. Verify current prices, opening hours, train or flight schedules, visa rules, and booking policies before presenting them as final.
- When using web information, include source links and the date checked.
- Distinguish confirmed facts from assumptions or ideas.
- Use exact dates for schedules and deadlines.
- Avoid relying on stale information for high-impact decisions such as flights, hotels, visas, insurance, or cancellation rules.

## GitHub Pages

- Keep published files static and relative-link friendly.
- Prefer relative paths such as `assets/css/style.css` instead of absolute local paths.
- Avoid build steps unless the user explicitly wants a generator or framework.
- Make `index.html` the default public entry point.
- Do not include secrets, private booking details, passport information, payment information, or personal contact details in published HTML.

## Editing Rules

- Preserve user-written notes and drafts.
- Do not delete travel options just because they are not selected; move them into an alternatives or notes section when useful.
- Keep changes focused and explain any major restructuring.
- Use concise comments only when they clarify non-obvious HTML, CSS, or data.

## Visual Style

- Travel reports should be clear, calm, and practical.
- Favor readable layouts, maps, schedule tables, and compact summary cards over decorative effects.
- Use images only when they help identify a place, route, hotel, restaurant, or activity.
- Ensure text and tables remain usable on mobile screens.

## Before Finishing Work

- Check that links and asset paths are valid.
- Check that the HTML opens locally.
- Check mobile readability for important pages when practical.
- Summarize what changed and mention any information that still needs verification.
