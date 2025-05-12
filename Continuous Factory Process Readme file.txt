# Multi-Stage Manufacturing Process Analysis

![Manufacturing Process](https://img.freepik.com/free-vector/factory-industrial-plant_74855-5276.jpg)

## Project Overview
This project analyzes sensor data from a continuous manufacturing process to:
1. Predict equipment maintenance needs
2. Forecast product quality
3. Optimize process parameters

The analysis combines machine learning techniques including classification, regression, and clustering to provide actionable insights for manufacturing operations.

## Features
- **Predictive Maintenance**: Identifies when machines are likely to need maintenance
- **Quality Prediction**: Forecasts final product quality based on process parameters
- **Process Optimization**: Recommends optimal parameter settings for best quality output
- **Integrated Dashboard**: Visualizes relationships between maintenance, quality, and process parameters

## Technologies Used
- Python 3.x
- Jupyter Notebook
- Libraries:
  - Pandas, NumPy
  - Scikit-learn
  - XGBoost
  - Matplotlib, Seaborn

## Dataset
The dataset contains:
- 1,210 time points collected at 1-second intervals
- 134 sensor measurements including:
  - Machine parameters (temperatures, pressures, motor metrics)
  - Stage outputs (measurements 0-14)
  - Ambient conditions

## Installation
1. Clone this repository:
```bash
git clone https://github.com/yourusername/manufacturing-process-analysis.git
cd manufacturing-process-analysis
Create and activate a virtual environment:

bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
Install required packages:

bash
pip install -r requirements.txt
Usage
Open the Jupyter notebook:

bash
jupyter notebook Manufacturing_Process_Analysis.ipynb
Run the notebook cells sequentially to:

Load and preprocess the data

Train predictive models

Generate optimization recommendations

Visualize results

Key Results
Predictive Maintenance
Model	Precision	Recall	F1-Score
Random Forest	0.92	0.88	0.90
XGBoost	0.93	0.89	0.91
Quality Prediction
Model	R² Score	RMSE
Random Forest	0.85	1.23
XGBoost	0.86	1.19
Process Optimization
Identified 4 distinct process states with Cluster 2 showing:

15% better quality output

10% lower energy consumption

File Structure
manufacturing-process-analysis/
├── data/
│   └── continuous_factory_process.csv
├── notebooks/
│   └── Manufacturing_Process_Analysis.ipynb
├── reports/
│   └── findings_report.pdf
├── requirements.txt
└── README.md
Contributing
Contributions are welcome! Please open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For questions or feedback, please contact:

[Junaid Iqbal] - junaid19tex@gmail.com



