# Tripmate by Scapia — clickable prototype

A no-build, responsive HTML/CSS/JavaScript prototype for the Scapia Product Internship assignment. The primary flow helps geographically distributed friends choose dates that balance group availability and paid leave, then coordinate flights. The Travel Club remains a supporting community for first-hand recommendations; rewards are tucked under Account rather than competing with the core task.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a browser. No install, build step, backend, API key or package manager is required.
3. For a local server, run `python3 -m http.server 8000` in the project folder and visit `http://localhost:8000`.

## Publish on GitHub Pages
1. Create a new public GitHub repository (e.g. `scapia-tripmate`).
2. Upload `index.html`, `README.md`, and `RESEARCH.md` to the repository root, or push this folder using Git.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then **Save**.
6. Wait for GitHub Pages to publish; the URL will be shown on the Pages settings screen, usually `https://YOUR-USERNAME.github.io/scapia-tripmate/`.

## What works in this prototype
- Focused desktop and mobile navigation: Home, Trip planner, Flights, Travel Club, Account. Rewards live inside Account.
- Demo sign-in modal that personalises the greeting using local browser storage.
- Trip setup and editable sample group members, time zones, calendar status, leave balance and preferences.
- Clickable date recommendations that reorder based on the selected priority; selection feeds into the flight screen.
- Sample group flight arrival comparison with date/destination selectors.
- Destination discovery, filters and a shared shortlist are available as a secondary/demo flow, not the primary navigation focus.
- Travel Club stories, local demo posts and reactions; points and reward assumptions are shown under Account.
- Privacy toggles and reset-demo action.

## Important prototype boundaries
- This is a **front-end prototype**, not a production application. Calendar matching and flight listings are illustrative and use sample data; no Google/Microsoft calendar, flight inventory, venue, booking or payment API is connected.
- The date-fit percentages are demo heuristics, not a genuine optimisation model. A production version should score actual free/busy data, regional holidays, arrival feasibility, leave policies, group preferences and fare trade-offs.
- Sign-in is a demo only; do not enter sensitive credentials. Data is stored locally in the browser on the current device.
- Scapia payment acceptance is not verified for individual places in this demo. Do not represent the venue list as Scapia-approved merchants.
- Community points and redemption values are fictional. They are not existing Scapia rewards or cash/cashback promises.
- The visual design uses a Scapia-inspired navy, blue, mint and lime palette. This is an independent concept and is not an official Scapia product.

See `RESEARCH.md` for secondary-research links and how they inform the concept.
