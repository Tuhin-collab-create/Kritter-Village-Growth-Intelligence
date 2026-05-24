# Village Economic Growth Intelligence

[cite_start]This repository contains the intelligence system designed to identify the top 100 villages in India exhibiting the highest economic growth over the last 5 years[cite: 16, 20].

## Project Overview
Economic growth at the village level is often invisible in traditional datasets. [cite_start]This project leverages satellite imagery and public ground-truth data to capture signals—such as infrastructure construction, night-time lights, and land-use changes—to quantify ground-level economic activity[cite: 18, 19, 20].

## Project Structure
* [cite_start]`geo.ipynb`: The complete, reproducible data pipeline encompassing data extraction, cleaning, processing, and scoring[cite: 24, 25].
* [cite_start]`top_100_villages.csv`: The final ranked output dataset containing scores and key village attributes[cite: 28].
* [cite_start]`top_100_growing_villages.html`: An interactive map visualization of the top 100 villages[cite: 29].
* [cite_start]`Presentation.html`: A 5-7 slide presentation covering methodology, findings, and analysis[cite: 30].

## Methodology
### 1. Data Sources
* [cite_start]**Satellite Data**: [Insert Source Name, e.g., Sentinel-2] – Selected because [Insert justification, e.g., high temporal resolution allows for effective monitoring of construction signals][cite: 22, 23].
* [cite_start]**Ground-Truth Data**: [Insert Source Name, e.g., PMGSY/Census] – Used because [Insert justification, e.g., it provides reliable economic baseline validation][cite: 22, 23].

### 2. Scoring & Ranking
[cite_start]"Economic Growth" is defined in this framework as [Insert your definition, e.g., the sustained rate of change in infrastructure luminosity and land-use intensity over a 5-year period][cite: 27]. [cite_start]Our scoring methodology ranks villages based on [Insert specific signals used, e.g., normalized difference vegetation index (NDVI) shifts or building density growth][cite: 26, 27].

## How to Run
1. **Prerequisites**: Ensure you have a Python environment set up with the dependencies listed in `geo.ipynb`.
2. **Execution**: Open `geo.ipynb` in a Jupyter environment. [cite_start]Run all cells in sequence to execute the data pipeline from extraction to final scoring[cite: 24, 25].
3. [cite_start]**Outputs**: The script will automatically generate the `top_100_villages.csv` file[cite: 24, 28].

## Limitations
* [cite_start][Insert Limitation, e.g., Cloud cover limitations in optical satellite imagery][cite: 30].
* [cite_start][Insert Limitation, e.g., Data granularity gaps in specific remote regions][cite: 30].

## Future Directions
* [cite_start]If more time or data were available, I would [Insert next steps, e.g., incorporate more diverse socio-economic ground-truth datasets or improve spatial resolution by utilizing radar imagery (SAR) to overcome cloud cover][cite: 30].
