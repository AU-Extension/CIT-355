# CIT 355 AI for Decision Making in Sports Management: course interactives

Interactive simulations for CIT 355 at Atlantis University, School of Information Technology. Each week has two self-contained HTML pages: an explorer (Interactive A) and a scored challenge (Interactive B). The Moodle description blocks link to these pages through GitHub Pages.

Live site: https://au-extension.github.io/CIT-355/

## Structure

| Folder | Topic | Interactive A | Interactive B |
|---|---|---|---|
| week1 | Data, AI, and decisions in sports | analytics-ladder.html | gut-or-data-challenge.html |
| week2 | Sports data and KPIs | kpi-explorer.html | dirty-data-challenge.html |
| week3 | Player performance and scouting | player-radar-explorer.html | scouting-shortlist-challenge.html |
| week4 | Predicting outcomes (midterm memo) | correlation-explorer.html | beat-the-model-challenge.html |
| week5 | Ticket pricing and revenue | dynamic-pricing-simulator.html | season-revenue-challenge.html |
| week6 | Fans, marketing, and sponsorship | fan-segmentation-explorer.html | sponsorship-roi-challenge.html |
| week7 | Player health and responsible AI | workload-monitor.html | ethics-dilemmas-challenge.html |
| week8 | Decision dashboards and the board meeting (final project) | chart-chooser-explorer.html | board-meeting-challenge.html |

The `data/` folder holds the fictional Biscayne Bay Sports Group datasets used in every assignment, with a data dictionary in `data/README.md`.

## Publishing

1. Upload the contents of this folder to the `main` branch of `AU-Extension/CIT-355` (keep the `week1` to `week8` folders at the root).
2. In the repository, open Settings, then Pages, and set Source to "Deploy from a branch", branch `main`, folder `/ (root)`.
3. Each page is then live at `https://au-extension.github.io/CIT-355/weekN/<file>.html`.

Every page loads the AU logo from `AU-Extension/items` and GSAP and fonts from public CDNs, and still works if GSAP fails to load. No build step is needed.
