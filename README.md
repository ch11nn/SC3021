# SC3021 – Data Science Fundamentals

This repository contains coursework and project files for **SC3021 Data Science Fundamentals**, a module taken at Nanyang Technological University (NTU). The module covers core concepts in data science, including data preparation, exploratory data analysis, and machine learning.

---

## 📊 Project: Does Rainfall Affect the Frequency of Traffic Accidents in Singapore?

This project investigates whether variations in rainfall are associated with changes in traffic accident outcomes in Singapore.

Rainfall can affect driving conditions by reducing road friction, impairing visibility, and increasing driver reaction times — all of which may raise the frequency and severity of traffic accidents. Using historical meteorological and traffic data from Singapore, we applied a multiple linear regression model to quantify the relationship between monthly rainfall, traffic volume, and traffic casualties.

### Datasets Used
- **DS1** – Monthly Total Rainfall at Changi (Jan 1982 – Feb 2026) — *data.gov.sg*
- **DS3** – Singapore Road Traffic Accident Casualties, Monthly (Jan 2009 – Nov 2025) — *data.gov.sg*
- **DS4** – Average Daily Traffic Volume Entering the City (Jan 2004 – Jan 2023) — *data.gov.sg*

### Key Finding
While traffic volume was found to be a statistically significant predictor of casualties, **aggregate monthly rainfall was not** (p = 0.274). The model achieved an Adjusted R² of 0.416, suggesting that rainfall alone is insufficient to explain accident patterns without finer-grained temporal data.

### Tools & Libraries
`Python` · `pandas` · `numpy` · `matplotlib` · `scikit-learn`
