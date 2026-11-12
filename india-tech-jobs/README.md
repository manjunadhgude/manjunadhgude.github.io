# India AI/ML Job Market Dashboard

**Dashboard:** https://manjunadhgude.github.io/india-tech-jobs/

**Source:** [AI/ML India — Hourly Job Tracker](https://app.notion.com/p/b27904c4cf1543bdbd53dd8099ac9017)

**Google Colab notebook:** [Open in Colab](https://colab.research.google.com/github/manjunadhgude/manjunadhgude.github.io/blob/main/india-tech-jobs/notebooks/India_AI_ML_Job_Market_Analysis.ipynb)

## Files
- `data/jobs.json`: read-only tracker snapshot.
- `index.html`: interactive Chart.js dashboard.
- `notebooks/India_AI_ML_Job_Market_Analysis.ipynb`: pandas/matplotlib notebook.

## Limitations
This is a personal tracker sample, not a representative sample or census of Indian vacancies. Some records have stale or uncertain status checks. Compensation marked “Not disclosed” is not necessarily unpaid. Fit scores are personal prioritisation scores, not hiring probabilities. The notebook reads this published snapshot; it does not automatically sync with Notion or write back to it.

## Refresh
Verify records in Notion, export a fresh JSON snapshot, replace `data/jobs.json`, and commit. GitHub Pages republishes the dashboard.
