# WaTech ECCP Program Dashboard

An interactive, single-file HTML dashboard for the Washington Technology Solutions (WaTech) **Enterprise Cloud Compute Program (ECCP)**. Designed to communicate the program's service strategy, staffing plan, and agency journey to internal stakeholders.

---

## Pages

### Dashboard (`index.html`)
The main program dashboard with three views:

- **Journey Map** — Visualizes the future-state agency experience blueprint alongside the Foundational Release Plan (FRP). Toggle between Future Vision and FRP layers independently, and drill into phase and step detail.
- **Services & Capabilities** — Catalog of all 22 ECCP services organized by domain, with capability breakdowns including Support Process and Marketplace — Order Fulfillment for every service.
- **Roles & Staffing** — Proposed staffing model with 11 roles across Phase I, Phase II, and future hiring horizons. Filter by hiring type and priority phase.

### Program Vision (`eccp-program-vision-new.html`)
A visual overview of the ECCP program vision, goals, and strategic context for the agency experience.

---

## Usage

Open either HTML file directly in a browser — no build step or server required. An internet connection is needed to load Google Material Icons and fonts from CDN.

### Importing Data

The dashboard supports importing updated service, role, or journey map data via the Import button in the toolbar. After importing, click **Save** to download an updated `index.html` with the new data baked in permanently — replace the existing file to persist changes.

---

## Tech Stack

| Concern | Approach |
|---|---|
| Framework | Vanilla HTML/CSS/JS — zero build tooling |
| Icons | [Google Material Icons Outlined](https://fonts.google.com/icons) via CDN |
| Fonts (Vision page) | Nunito Sans via Google Fonts CDN |
| Styling (Vision page) | Tailwind CSS via CDN |
| Data persistence | Embedded JS arrays in `index.html`; export via `saveUpdatedFile()` |

---

## Status

Active development — conceptual draft subject to refinement based on WaTech input and evolving program requirements.
