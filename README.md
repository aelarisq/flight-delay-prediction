# ✈️ US Flight Delay Analysis & Prediction (2013-2023)

![Python](https://img.shields.io/badge/Python-3.12%2B-blue)
![CatBoost](https://img.shields.io/badge/Model-CatBoost-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📖 Project Overview
This project explores the feasibility of predicting flight delay rates across the US domestic aviation network using 10 years of historical data (170k+ records). 

**Objective:** To determine the theoretical limits of predictability for flight delays using Machine Learning, separating stochastic noise (weather, anomalies) from systemic signal (seasonality, carrier efficiency).

**Key Hypothesis:** While individual delays are stochastic, aggregated delay rates exhibit predictable inertial and seasonal patterns.


## 🛠️ Installation & Usage

**Prerequisites:** You will need **Python 3.12** and **Conda** (Anaconda or Miniconda) installed.

It is recommended to use a virtual environment to avoid dependency conflicts. You can set up the environment using either `pip` (Option A) or `conda` (Option B).

### Option A: Using Pip (Manual Setup)
This method allows for manual control over packages.

1. **Create and activate the environment:**
    ```bash
    conda create -n flight_delay python=3.12 -y
    conda activate flight_delay
    ```

2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Set up the Jupyter Kernel:**
    ```bash
    python -m ipykernel install --user --name=flight_delay --display-name "Python (Flight Delay)"
    ```

### Option B: Using Conda (From YAML)
If you prefer a full Conda environment replication.

1. **Create the environment from the file:**
    ```bash
    conda env create -f environment.yml
    ```

2. **Activate the environment:**
    ```bash
    conda activate flight_delay
    ```

### 🚀 Running the Project

1. **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```

2. **Open** `delay-forecasting-end-to-end.ipynb`

3. **Important:** In the top menu, go to **Kernel -> Change Kernel** and select **"Python (Flight Delay)"**.