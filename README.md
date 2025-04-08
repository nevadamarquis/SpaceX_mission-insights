# SpaceX_mission-insights
Data science insights from SpaceX Falcon 9 launches, featuring EDA, geospatial maps, dashboards, and ML predictions.
# SpaceX Falcon 9 Launch Analysis Dashboard

## Project Overview

This project is part of the IBM Applied Data Science Capstone and focuses on analyzing and visualizing the historical launch performance of the SpaceX Falcon 9 rocket. The primary objective was to apply data wrangling, exploratory data analysis (EDA), interactive dashboarding, and basic machine learning techniques to derive meaningful insights and predict launch success outcomes.

The final deliverables include:
- A fully offline, interactive HTML dashboard
- A comprehensive set of Jupyter notebooks covering all major data science steps
- An executive-style PowerPoint presentation for stakeholders

---

## Contents

- `spacex-dashboard-fixed.html` — Final Plotly + JS dashboard with offline support
- `SpaceX_Data_Wrangling_.ipynb` — Data wrangling and initial preprocessing steps
- `SpaceX_EDA_Visual_Analytics_.ipynb` — Visual exploratory data analysis
- `SpaceX_Folium.ipynb` — Interactive map visualizations of launch sites
- `SpaceX_ML_Modeling.ipynb` — Binary classification model for predicting launch success
- `spacex_cleaned_data.csv` — Final cleaned dataset used across all analyses
- `presentation/` — PowerPoint slides used for executive-level communication
- `images/` — Supporting graphics and screenshots for presentation and documentation

---

## Data Sources

The data used in this project was obtained through the following sources:
- SpaceX official launch history web pages (scraped via `BeautifulSoup`)
- SpaceX launch metadata APIs
- Wikipedia launch logs
- Supplementary manual verification and correction

The data was split across multiple datasets, cleaned, normalized, and merged for downstream analysis. A total of 90 launches were analyzed after preprocessing.

---

## Key Methodologies

- **Data Collection & Web Scraping**: HTML parsing and tabular scraping using `requests`, `BeautifulSoup`, and `pandas`
- **Data Wrangling**: Merging, cleaning, type correction, null value handling, and feature engineering
- **Exploratory Data Analysis (EDA)**: Plotly visualizations for orbit success rates, launch site distributions, and payload relationships
- **Geospatial Mapping**: Folium maps showing launch site locations with contextual popups
- **Machine Learning**: Logistic regression classification model to estimate binary launch success
- **Interactive Dashboard**: Plotly Dash-powered web application with filters, charts, and export functionality

---

## Dashboard Features

- Multi-tab interface (Overview, Analysis, Map, Prediction Tool)
- Export to PDF and CSV functionality
- Offline access and rendering of all charts and maps
- Success rate breakdowns by orbit, site, booster version, grid fins, and landing gear
- Machine learning prediction based on user-input features

---

## Reproducibility

All notebooks are executable independently and structured in logical steps. The dashboard can be opened in any browser as a single self-contained HTML file. The codebase is designed for transparency, reusability, and clarity.

---

## Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Matplotlib, Seaborn
- Plotly Express, Dash, HTML/CSS/JS
- Folium (Leaflet.js)
- Scikit-learn
- BeautifulSoup4, Requests
- jsPDF, html2canvas (for exporting)

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for full terms.

---

## Acknowledgments

- IBM Data Science Professional Certificate Team
- SpaceX and Wikipedia for publicly accessible data
- The open-source Python data science community
