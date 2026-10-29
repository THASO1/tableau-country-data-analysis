# Tableau Dashboard Actions — Country Data Comparison

An interactive Tableau project created for **Mini-Project 3: Advanced Tableau Storytelling & Interactive Analytics**. The project compares country-level economic, population, demographic, and quality-of-life indicators through three dashboards and a set of configured Tableau Dashboard Actions.

## Project Overview

This project uses the **Country Data Comparison** dataset to explore differences between countries through economic and demographic indicators. The goal is to support interactive country comparisons by highlighting related marks, filtering views, updating a selected-country set, navigating to a detail worksheet, and opening an external country reference.

## Dashboards

### 1. Economic Development & Quality of Life

Explores relationships between economic development and quality-of-life measures, including comparisons such as GDP per capita versus life expectancy.

![Economic Development & Quality of Life](Economic%20Development%20%26%20Quality%20of%20Life.png)

### 2. Global Economic Overview

Presents country-level economic information, including a GDP world map and related economic views.

![Global Economic Overview](Global%20Economic%20Overview.png)

### 3. Population & Demographic Analysis

Brings together population and demographic indicators to support comparisons across countries.

![Population & Demographic Analysis](Population%20%26%20Demographic%20Analysis.png)

## Interactive Tableau Actions

The workbook action guide documents **10 registered actions** across five action types:

| Action type | Purpose |
|---|---|
| **Highlight** | Emphasizes related marks while keeping other data visible. |
| **Filter** | Restricts a target view to matching data. |
| **Set** | Updates membership in a saved set for comparison. |
| **Go to Sheet** | Navigates to a destination worksheet. |
| **URL** | Opens an external web resource. |

Examples documented in the guide include highlighting a country across views, navigating from the GDP world map to a GDP detail worksheet, updating the `Selected Country Set`, filtering related quality-of-life charts, and opening an external country reference.

## Technical Verification Notes

The saved action configuration needs manual verification in Tableau Desktop before all actions are described as fully working. The action guide flags these items:

- **Action 4 — URL:** verify the trigger and test URL formatting with country names containing spaces or special characters.
- **Action 6 — Explore Quality of Life:** the inspected configuration appears to use the same sheet as source and destination; confirm whether this is intentional.
- **Action 9 — Filter Countries Across Demographic Charts:** the saved target appears narrower than the action name suggests.
- **Actions 3 and 10 — Selected Country Set:** both actions use the same set but have different clearing behavior; test how they interact.

These are configuration-audit notes, not claims that every action has passed live interaction testing.

## Tools

- **Tableau** — dashboard development and interactive actions
- **Country Data Comparison** — source dataset
- **Workbook XML inspection** — used to document saved action configuration

## How to Explore

1. Open `Mini-Project.twbx` in Tableau Desktop or Tableau Public.
2. Open each of the three dashboards listed above.
3. Hover over or select marks to explore the configured interactions.
4. Verify each action's settings and behavior before relying on it.

## Repository Files

- `Mini-Project.twbx` — Tableau packaged workbook
- `README.md` — project overview and dashboard previews
- Three dashboard screenshots — stored in the repository root and embedded above

> **Screenshot paths:** The image links in this README are intentionally matched to the three screenshot filenames currently shown in the repository root. If you move those images into a folder later, update each image path accordingly.

## Notes

This README describes the dashboards and the saved action configuration documented in the project guide. It does not claim that every action has been tested successfully. Add a Tableau Public link only after publishing the workbook and verifying the URL.

---

**Project:** Mini-Project 3 — Advanced Tableau Storytelling & Interactive Analytics
