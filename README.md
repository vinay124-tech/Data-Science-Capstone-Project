# SpaceY Launch Pricing & Booster Reuse Prediction

**Capstone Project | IBM Data Science Professional Certificate**

## Scenario

As a data scientist at **SpaceY**, your mission is to analyze SpaceX launch data to:

- Determine the cost of each rocket launch.
- Predict whether the first-stage booster will be reused.

By leveraging public data, exploratory analysis, clustering, and predictive modeling, you will build dashboards and machine learning pipelines to support pricing and operational decisions.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Data Sources](#data-sources)
- [Methodology](#methodology)
- [Key Features](#key-features)
- [Usage](#usage)
- [Skills & Tools](#skills--tools)
- [Results](#results)
- [Author](#author)

## Project Structure

```
.
├── data/
│   └── spacex_launch_data.csv   # Raw launch data
├── notebooks/
│   ├── 01_data_collection.ipynb       # Data extraction & wrangling
│   ├── 02_exploratory_analysis.ipynb  # EDA & visualization
│   ├── 03_clustering.ipynb            # K-Means clustering of launch sites
│   ├── 04_modeling.ipynb              # ML pipeline & evaluation
│   └── 05_dashboard_deployment.ipynb  # Dashboard with Plotly Dash
├── dashboard/
│   └── app.py                         # Dash application
├── presentation/
│   └── SpaceY_Capstone.pptx           # Project summary slides
└── README.md                          # Project documentation (this file)
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<username>/SpaceY-Launch-Prediction.git
   cd SpaceY-Launch-Prediction
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook or run the dashboard:
   ```bash
   jupyter notebook notebooks/01_data_collection.ipynb
   # or
   python dashboard/app.py
   ```

## Data Sources

- **SpaceX Launch Data**: Publicly available data containing launch site, payload, orbit, flight number, success/reuse status.

## Methodology

1. **Data Collection & Wrangling**: Use Python, Pandas, and SQL to extract and clean data.
2. **Exploratory Data Analysis**: Visualize trends, cost distribution, success rates with Plotly & Folium.
3. **Clustering**: Apply K-Means to group launch sites geographically.
4. **Predictive Modeling**: Train and evaluate classifiers (Logistic Regression, Decision Tree, Random Forest, SVM) to predict booster reuse.
5. **Dashboard Deployment**: Build an interactive dashboard with Plotly Dash for pricing and reuse insights.

## Key Features

- Interactive visualizations of launch metrics.
- K-Means clustering of launch sites.
- Machine learning pipeline with hyperparameter tuning.
- Deployment-ready dashboard for real-time insights.

## Usage

- Open the Jupyter notebooks in the `notebooks/` folder to reproduce analysis.
- Run `python dashboard/app.py` to launch the interactive dashboard at `http://127.0.0.1:8050/`.

## Skills & Tools

- **Languages**: Python, SQL
- **Libraries**: Pandas, NumPy, Scikit-learn, Plotly, Folium, Dash
- **Tools**: Jupyter Notebook, GitHub, IBM DB2, PowerPoint

## Results

- **Price Estimation**: Derived launch cost insights through EDA and visualizations.
- **Booster Reuse Prediction**: Achieved X% accuracy on test set with Random Forest model. (Replace X with actual value)

## Author

**Manohar Vinay Mududundi**  
Integrated Dual Degree (B.Tech + M.Tech) in ECE, JNTU Hyderabad  
GitHub: [https://github.com/vinay124-tech](https://github.com/vinay124-tech)
