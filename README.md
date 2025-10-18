# Business Analytics Project

This project provides a synthetic dataset and exploratory data analysis (EDA) notebook suitable for aspiring business analysts, data analysts, or program managers. It demonstrates data-driven decision‑making using a fictional portfolio of projects.

## Overview

The dataset describes *projects* with features such as budget, duration, team size, complexity, stakeholder engagement, risk score, manager experience, and industry. Two target variables are included:

* **success** – a binary indicator (1 = project success, 0 = failure) synthesized via a logistic model.
* **completion_months** – how long the project actually took to complete, computed from the planned duration and other factors.

## Contents

* `synthetic_project_dataset.csv` – the synthetic dataset.
* `analysis.ipynb` – a Jupyter notebook that loads the dataset, performs exploratory data analysis (EDA), and builds predictive models for project success and completion time.
* `requirements.txt` – Python dependencies to recreate the environment.

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd business_analytics_project
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`
   ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch the Jupyter notebook:**

   ```bash
   jupyter notebook analysis.ipynb
   ```

Follow the notebook to explore the data, visualize relationships, and build predictive models.

## Synthetic Data Generation

The synthetic dataset was generated using random distributions and logical relationships among variables. Success probability depends on higher stakeholder engagement and manager experience while being negatively influenced by project complexity, risk, and longer durations. Completion time is influenced by risk, engagement, and manager experience.

Feel free to experiment with the code, add new features, or extend the models!
