# Nutrition Country Profiles

A static landing page linking two interactive nutrition reports: iron supplementation and infant and young child feeding counselling.

## Preview

Open `index.html` in a browser, or run `python -m http.server 8000` from this directory and visit `http://localhost:8000`.

## Publish

GitHub Pages serves the root of the `main` branch. No build step or external runtime dependencies are required. The `.nojekyll` file disables Jekyll processing.

Update the report HTML files in place to preserve their URLs. Update the edition dates on the landing page when replacing a report with a new edition.

## Data

Reports retain their embedded data, maps, scripts, and methods. The feeding counselling report includes an embedded downloadable workbook. Everything embedded in the published HTML is publicly accessible. Standalone local spreadsheets and ZIP archives are excluded from version control.
