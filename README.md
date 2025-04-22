# HRV Analysis Project

This project explores the assessment of Heart Rate Variability (HRV) using two complementary metrics:

- **ppRRτ:**  
  Measures the probability that consecutive RR intervals differ by more than a specified threshold (e.g., 20 ms). Higher values reflect increased beat-to-beat variability.

- **Energy Ratio (LF/HF):**  
  Represents the balance between low-frequency and high-frequency components in the HRV spectrum. Lower values indicate a dominance of parasympathetic (relaxation) activity.

By integrating these two approaches, this project provides a robust methodological framework for evaluating autonomic regulation through HRV analysis.

## Project Overview

The objective of the project is to:

- **Compute ppRRτ** to capture the time-domain variability of HRV.
- **Calculate the Energy Ratio (LF/HF)** to assess the frequency-domain balance of autonomic regulation.
- **Visualize the Metrics:**  
  The code generates figures that illustrate the trends in ppRRτ and Energy Ratio across HRV signals. These visualizations help users understand the underlying autonomic patterns without discussing specific outcomes.

## Methodology

The repository contains:
- **Data Preprocessing:** Scripts for loading, cleaning, and preparing HRV data.
- **Metric Computation:** Algorithms for calculating ppRRτ and Energy Ratio from the data.
- **Visualization:** Tools to generate figures, which are stored in the `figures/` folder, highlighting the variability and balance in HRV.


## How to Run

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/<your-username>/HRV-Analysis-Project.git


2. **Install dependencies**

   pip install -r requirements.txt

3. **Run the analysis script**

   python hrv_analysis.ipynb




