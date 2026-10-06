# LoftSims CollegeGAS

Created for Sudheendra Pai. Version 1.3.0.

An interactive UC undergraduate cost, grant, scholarship, and financial aid dashboard built with plain HTML, CSS, JavaScript, and SVG. No build step or external dependencies.

## Run

Download the repository and open `index.html` in a browser, or serve the repository with any static web server.

## Explore

- Select among all nine undergraduate UC campuses.
- Filter Mechanical Engineering, Electrical Engineering, Applied Mathematics, Physics, or AI/Computing.
- Change residency and housing, edit annual expenses, and enter grants, scholarships, loans, work-study, and family contributions.
- Compare total expenses, gift aid coverage, total modeled funding, and the remaining gap.
- Model ZERO, MINIMUM, and MAXIMUM published fixed-dollar scholarship scenarios for the selected campus/subject. Need-based campus grants remain student-specific when no universal published maximum exists.
- Follow official campus scholarship and cost sources linked inside the dashboard.

## Data scope

Cost estimates cover the 2026–27 entering cohort; source checks are dated October 5, 2026. Awards and eligibility depend on individual circumstances. Modeled awards are scenarios, not financial aid offers. Loans and work-study are shown separately from grants and scholarships.

UC San Diego budgets and UC Santa Barbara off-campus/family budgets require manual entry where verified figures were unavailable. Further source and calculation notes appear in the dashboard. Inputs are not persisted between sessions.

JavaScript syntax and calculation checks passed. Full browser visual QA and the optional WebMCP integration were not validated.


## v1.2.0

Adds named funding-program contribution audit trails and downloadable JSON scenario evidence. UC Berkeley grant inventory is now explicitly represented; student-specific amounts are never fabricated when an official universal dollar amount is unavailable. Further UC campus inventories are being populated from official campus sources.


## v1.3.0

Adds student eligibility inputs and an eligibility-driven funding rules engine. Quantified federal/state grant rules are evaluated from the entered profile, named contributions are exposed in the UI, and the complete student profile plus program evidence is included in downloadable JSON. Campus-calculated awards remain explicitly marked rather than fabricated.
