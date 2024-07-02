# Income Prediction Project

Welcome to the Income Prediction Project! This guide will help you set up the project environment and install all the necessary dependencies. For the best experience, we recommend using Anaconda Navigator.

**Notes:**
- The project's `.ipynb` (Jupyter Notebook) is written in Portuguese (pt-BR).
- The project's Streamlit file, `income_prediction_streamlit.py`, is crucial for understanding the project.

## Quick Setup Instructions

### Step 1: Install Anaconda Navigator

If you haven't already, download and install [Anaconda Navigator](https://www.anaconda.com/products/distribution). Anaconda simplifies package management and deployment.

### Step 2: Create a New Environment

Open Anaconda Navigator and create a new environment for this project. This helps to keep dependencies organized and prevents conflicts with other projects.

1. Open Anaconda Navigator.
2. Click on the **Environments** tab.
3. Click the **Create** button.
4. Name your environment (e.g., `income-prediction-env`).
5. Choose the Python version you need (e.g., Python 3.8).
6. Click **Create** to create the environment.

### Step 3: Install Project Dependencies

Activate your new environment and open a terminal. Run the following command to install all required dependencies:

```bash
pip install patsy statsmodels ydata-profiling pandas matplotlib seaborn numpy streamlit scikit-learn
