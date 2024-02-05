# Milan Telecom Dataset Analysis

## Overview
This repository contains the work conducted as part of an assessment for a Research Engineer job interview at IMDEA Networks Institute. The project analyzes internet traffic in Milan during November and December 2013, using the Telecom Italia Big Data Challenge dataset. This analysis aims to provide insights into internet usage patterns across different areas of Milan and forecast future internet traffic using predictive models.

## Repository Structure
- `code/`: Contains Jupyter notebooks.
  - `Assessment Code.ipynb`: Notebook for solving the assessment's questions.
  - `data_cleaning_and_aggregation.ipynb`: Notebook for loading, cleaning, and aggregating the dataset.
- `data/`: Data folder with subfolders for cleaned datasets and a geojson file for grid ID locations.
  - `cleaned_dataset/`: Contains cleaned CSV data files.
  - `cleaned_dataset_30/`: Contains aggregated 30-minute interval data files.
  - `geojson/`: Contains geojson file with grid IDs.
- `report/`: Contains the PDF report with detailed analysis and findings.
- `README.md`: This file.
- `LICENSE`: License file for the project.
- `.gitignore`: Specifies intentionally untracked files to ignore.

## Dataset
The dataset, sourced from the Telecom Italia Big Data Challenge, includes SMS, call, and internet activity across Milan, divided into 100x100 grid squares. Due to size constraints, the raw dataset is hosted externally and can be accessed [here](<https://www.nature.com/articles/sdata201555>).

## Analysis Highlights
The analysis covers data cleaning, descriptive statistics, PDF plotting, hotspot analysis, and predictive modeling using ARIMA and LSTM methods. Key findings include:
- The distribution of internet traffic across different areas and times.
- Predictive modeling of internet traffic, showing the effectiveness of ARIMA and LSTM models under certain conditions.

## Report
For a full explanation of the methodology, analysis, and conclusions, refer to the [report](report/report.pdf) contained within this repository.

## How to Use
1. Clone this repository.
2. Ensure you have Jupyter Notebook installed to run `.ipynb` files.
3. Download the dataset as instructed and place it in the `data/cleaned_dataset` folder.
5. Install the requirements from the `requirements.txt` file.
6. Open and run the Jupyter notebooks for detailed analysis and predictive modeling.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
Special thanks to IMDEA Networks Institute for the opportunity to work on this fascinating dataset and to the Telecom Italia Big Data Challenge for providing the dataset.
