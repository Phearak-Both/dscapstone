# SpaceX Falcon 9 First-Stage Landing Prediction

IBM Data Science Professional Certificate: Applied Data Science Capstone
by Pheng Phearakboth

SpaceX advertises Falcon 9 launches at about $62 million, while other providers charge $165 million or more. Most of the saving comes from reusing the first stage. This project predicts whether the first stage will land, which helps estimate the cost of a launch.

**Final report:** [Data Science Capstone Project Report.pdf](Data%20Science%20Capstone%20Project%20Report.pdf)

## Notebooks

| Step | File |
|---|---|
| 1. Data collection: SpaceX API | [jupyter-labs-spacex-data-collection-api.ipynb](jupyter-labs-spacex-data-collection-api.ipynb) |
| 2. Data collection: web scraping | [jupyter-labs-webscraping.ipynb](jupyter-labs-webscraping.ipynb) |
| 3. Data wrangling | [labs-jupyter-spacex-Data wrangling.ipynb](labs-jupyter-spacex-Data%20wrangling.ipynb) |
| 4. EDA with SQL | [jupyter-labs-eda-sql-coursera_sqllite.ipynb](jupyter-labs-eda-sql-coursera_sqllite.ipynb) |
| 5. EDA with data visualization | [edadataviz.ipynb](edadataviz.ipynb) |
| 6. Interactive map with Folium | [lab_jupyter_launch_site_location.ipynb](lab_jupyter_launch_site_location.ipynb) |
| 7. Dashboard with Plotly Dash | [spacex-dash-app.py](spacex-dash-app.py) (screenshots in [screenshots/](screenshots)) |
| 8. Predictive analysis | [SpaceX_Machine Learning Prediction_Part_5.ipynb](SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb) |

## Key results

- Landing success rose from 0% (2010-2013) to about 90% in 2019.
- KSC LC-39A has the highest launch success rate (76.9%).
- The SSO, HEO, GEO and ES-L1 orbits had 100% success.
- All launch sites are near the coast, highways and railways, and far from cities.
- Logistic Regression, SVM, Decision Tree and KNN all reach 83.3% test accuracy. The Decision Tree has the best validation accuracy.

## Running the dashboard

```
pip install pandas dash
python spacex-dash-app.py
```

Then open http://127.0.0.1:8050 in your browser.
