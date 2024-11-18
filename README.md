# README

# Statistical Analysis and Data Visualization of Normal Distributions

This repository contains comprehensive statistical analyses and visualizations that demonstrate proficiency in using Python for data science. The analysis was conducted using two datasets generated from normal distributions with varying sample sizes.

## Project Overview

**File Name**: `main.ipynb`  
**Dependencies**:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scipy`
- `scikit-learn`

## Key Features Demonstrated:

### 1. **Data Generation and Preparation**
- Generated two datasets from a normal distribution with `np.random.normal()`.

### 2. **Descriptive Statistics Calculation**
- **Mean**
- **Median**
- **Mode** (using `scipy.stats.mode`)
- **Quartiles** and **InterQuartile Range (IQR)**
- **Variance** (`np.var()`)
- **Standard Deviation** (`np.std()`)

### 3. **Visualizations**
- **Histograms** with overlaid **Probability Density Functions (PDFs)**
- **Boxplots** for visualizing spread, median, and potential outliers
- **Cumulative Density Functions (CDFs)**
- **Probability Point Function (PPF)**, showing inverted CDFs

### 4. **Data Scaling Techniques**
- **StandardScaler** (from `scikit-learn`) to standardize data
- **MinMaxScaler** (from `scikit-learn`) to normalize data

### 5. **In-depth Interpretations**
- Analysis of how sample size affects statistical measures (mean, variance, etc.)
- Comparative analysis between datasets with visual interpretations of central tendency, spread, and outliers
- Insights into the importance of scaling for data preparation

## Dependencies and Installation

Ensure the following Python packages are installed before running the notebook:

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn
```

## Project Highlights for Recruiters

This project showcases:
- Advanced use of **Python statistical libraries** and functions.
- Proficiency in **data visualization** to communicate data insights clearly.
- Comprehensive understanding of **data scaling techniques** and their importance in data preprocessing.
- A thorough, structured approach to data analysis with **descriptive statistics** and **visual representation**.

Explore the [repository](https://github.com/andy111223/10.3_Stats_Analysis.git) to view the full `main.ipynb` file and assess the analytical and visualization skills demonstrated in this project.
