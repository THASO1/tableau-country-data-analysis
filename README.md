# Tableau Dashboard Actions — Country Data Comparison

An interactive Tableau project created for **Mini-Project 3: Advanced Tableau Storytelling & Interactive Analytics**. The project compares country-level economic, population, demographic, and quality-of-life indicators, with Tableau Dashboard Actions intended to make exploration more interactive.

> **Verification note:** The action details below are based on the saved workbook configuration as documented in the project’s action guide. The actions have not all been tested interactively in Tableau Desktop, so their runtime behavior should be verified before describing them as fully working.

## Project Overview

The project uses the **Country Data Comparison** dataset to explore differences between countries through economic and demographic indicators.

The objective is to make the dashboards more useful for comparison by enabling users to highlight related marks, filter charts, update a selected-country set, navigate to a detail worksheet, and open an external country reference.

## Dashboards

The workbook screenshot shows these three dashboards:

### 1. Economic Development & Quality of Life

Explores relationships between economic development and quality-of-life measures. The action guide identifies views including GDP per capita versus life expectancy, life expectancy by country, infant mortality by country, and fertility-rate distribution.

![Economic Development & Quality of Life](screenshots/dashboard-economic-development-quality-of-life.png)

### 2. Global Economic Overview

Presents country-level economic information, including a GDP world map and related GDP views. The saved action configuration includes interactions between the map and economic charts.

![Global Economic Overview](screenshots/dashboard-global-economic-overview.png)

### 3. Population & Demographic Analysis

Brings together population and demographic views to support comparisons across countries. The action guide lists views such as population by country, population distribution, demographic indicators, birth rate, and population-versus-GDP comparisons.

![Population & Demographic Analysis](screenshots/dashboard-population-demographic-analysis.png)

> The image paths above are placeholders. Add your actual screenshots to a folder named `screenshots` using these exact filenames, or update the paths to match your filenames.

## Interactive Tableau Actions

The workbook action guide documents **10 registered actions** across five action types:

| Action type | What it does |
|---|---|
| **Highlight** | Emphasizes related marks while keeping other data visible. |
| **Filter** | Restricts a target view to matching data. |
| **Set** | Updates membership in a saved set for comparison. |
| **Go to Sheet** | Navigates to a destination worksheet. |
| **URL** | Opens an external web resource. |

Examples documented in the guide include:
- Highlighting a country across economic or demographic views.
- Navigating from the GDP world map to the GDP detail worksheet.
- Updating the `Selected Country Set` from a map or scatter plot.
- Filtering related quality-of-life charts based on a scatter-plot selection.
- Opening an external country reference using a URL action.

## Technical Verification Notes

The action guide flags the following items for manual verification in Tableau Desktop:

- **Action 4 — URL:** verify the trigger and test the URL format, including country names with spaces or special characters.
- **Action 6 — Explore Quality of Life:** the inspected configuration appears to use the same sheet as source and destination. Confirm whether this is intentional.
- **Action 9 — Filter Countries Across Demographic Charts:** the saved target appears narrower than the action name suggests.
- **Actions 3 and 10 — Selected Country Set:** both actions use the same set but have different clearing behavior. Test how they interact.
- Test all actions in Tableau Desktop or Tableau Public before stating that they work as intended.

These are configuration-audit notes, not claims that the actions have passed live interaction testing.

## Tools & Resources

- **Tableau** — dashboard development and interactive actions
- **Country Data Comparison** — source dataset
- **Workbook XML inspection** — used to document saved action configuration

## How to Explore

1. Open the `Mini-Project` Tableau workbook in Tableau Desktop or Tableau Public.
2. Open each of the three dashboards listed above.
3. Hover over or select marks to explore the configured interactions.
4. Verify the action settings and behavior against the testing checklist before relying on the interactions.

## Repository Structure

A recommended structure for the GitHub repository:

```text
.
├── README.md
├── Mini-Project.twbx
└── screenshots/
    ├── dashboard-economic-development-quality-of-life.png
    ├── dashboard-global-economic-overview.png
    └── dashboard-population-demographic-analysis.png
```

Adjust the workbook filename in this example to match the actual file you upload. Do not upload the dataset if its license or sharing terms do not permit redistribution.

## Notes

This README describes the dashboards visible in the provided workbook screenshot and the action configuration documented in the project guide. It does not claim that every action has been tested successfully. Add a Tableau Public link only after publishing the workbook and verifying the link.

---

**Project:** Mini-Project 3 — Advanced Tableau Storytelling & Interactive Analytics
