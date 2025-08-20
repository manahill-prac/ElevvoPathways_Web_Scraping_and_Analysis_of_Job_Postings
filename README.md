# Job Market Analysis from Static HTML

This repository contains a Python-based job scraper and analyzer. It extracts job listings from a static HTML page (e.g., downloaded from Google Drive), cleans the data, identifies in-demand skills, visualizes trends, and exports detailed reports.

## Features

- Fetch HTML content from a URL
- Parse job listings (title, company, location, description, salary, skills)
- Clean and structure scraped data
- Analyze:
  - Top hiring companies
  - Top job locations
  - Most in-demand skills
  - Skills by city
- Visualizations:
  - Bar plots, heatmaps, pie charts
  - Word frequency for job titles
- Export:
  - Cleaned job data (`CSV`)
  - Skills data (`CSV`)
  - Summary report (`TXT`)

## Usage

```python
from job_scraper_analyzer import JobScraperAnalyzer

# Initialize analyzer
analyzer = JobScraperAnalyzer()

# URL to static HTML file (Google Drive or local)
file_url = "https://drive.google.com/uc?export=download&id=YOUR_FILE_ID"

# Run full analysis
analyzer.run_complete_analysis(file_url)
```

## Outputs

* `job_analysis_results_jobs.csv` → Cleaned job listings
* `job_analysis_results_skills.csv` → Skills extracted per job
* `job_analysis_results_summary.txt` → Summary report
* Visual plots (displayed inline)

---

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/YOUR_FILE_ID_HERE)

```
```
