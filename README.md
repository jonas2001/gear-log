# Gear Log

Gear tracking, projects, offers and clock in/out for a small rental company (DJ gear, amps, Funktion One speakers, light and staging).

The app is a single self-contained HTML file (`index.html`) that runs as a Claude artifact. It stores its data (items, jobs, people, events, shifts, offers, etc.) in the artifact's database, so no data lives in this repo.

## Main parts
- **Today / Projects / Find / Gear / People** tabs: gear check-out/in history per numbered unit, projects with gear plans, crew and tasks.
- **Packing**: tickable packing list per project.
- **Offers / invoicing**: versioned offers with PDF export.
- **Clock**: simple phone clock-in with task categories; detailed hours view on computer.

## Updating
The live version is the Claude artifact. When it changes, copy the new HTML over `index.html` and commit.
