# Box Office Mojo Web Scraping (Python)

Python scripts to scrape, normalize, and export structured box office data from Box Office Mojo into clean CSV files.

## Data Extracted
- Yearly domestic box office rankings (1982–present)
- Worldwide box office summaries (domestic vs foreign split)
- Daily box office performance (with holiday/occasion detection)
- Movie-level regional and release breakdowns

## Key Features
- Batch scraping across multiple years and movie IDs
- Handles inconsistent HTML and optional fields (holidays, re-releases)
- Normalizes complex tables into analysis-ready datasets
- Outputs clean CSV files for Excel, BI tools, or further processing

## Tech Stack
- Python
- requests
- BeautifulSoup
- pandas