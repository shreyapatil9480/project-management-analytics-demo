# Project Management Analytics

This repository showcases a complete data analytics project built around a **synthetic project management dataset**. It is designed to demonstrate analytical skills applicable to roles such as business analyst, program manager, or data analyst.


> **Note**: This repository demonstrates project management analytics for job seekers.## Dataset

The dataset `synthetic_project_data.csv` contains 1,000 synthetic project records, each describing a single project with the following columns:

| Column | Description |
|-------|------------|
| `project_id` | Unique identifier for each project | 
| `team_size` | Number of people on the project team |
| `team_experience_years` | Average years of professional experience of team members |
| `budget_thousands` | Budget allocated to the project (in thousands of dollars) |
| `duration_days` | Estimated duration of the project in days |
| `complexity` | Categorical complexity level (`Low`, `Medium`, `High`) |
| `risk` | Risk score between 0 and 1 (higher values indicate greater risk) |
| `success` | Binary outcome indicating whether the project was successful (1) or not (0) |

The data were generated synthetically to emulate realistic project management scenarios. Relationships among variables were crafted to produce meaningful patterns for exploration and modeling.

## Contents

- `synthetic_project_data.csv` – synthetic dataset described above.
- `project_analysis.ipynb` – Jupyter notebook containing exploratory data analysis (EDA), visualizations, and predictive models.
- `requirements.txt` – list of Python package dependencies.
- `README.md` – this file.

## Getting Started

To run the analysis notebook locally:

1. **Clone this repository**

```bash
git clone <repository-url>
cd <repository-directory>
```

2. **Create and activate a virtual environment** (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Launch Jupyter Notebook**

```bash
jupyter notebook project_analysis.ipynb
```

The notebook walks through data loading, exploratory visualizations, correlation analysis, logistic regression modeling, and a random forest model. Feel free to experiment with different modeling techniques or extend the EDA.

## Usage

This project illustrates how to structure a data analysis workflow:

- **Data Understanding**: Inspect data types, summary statistics, and distributions.
- **Exploratory Data Analysis**: Visualize distributions and relationships, such as success rates by complexity level and correlations between numeric features.
- **Modeling**: Build baseline models (logistic regression) and compare with more advanced models (random forest) to predict project success. Evaluate model performance using classification reports and confusion matrices.
- **Interpretation**: Examine feature importances to understand which variables most influence the outcome.

## Contributing

Contributions are welcome! If you want to add new models, visualizations, or improve documentation, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

