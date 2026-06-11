# Skin Cancer Risk Analysis System

## Objective
Analyzed 2,298 patient records to identify high-risk 
skin cancer patients — enabling early medical 
intervention and prioritizing doctor attention.

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn (MinMaxScaler)
- Matplotlib
- Excel (Pandas Styler, Pivot Tables)

## Key Highlights
- Handled 35%+ missing values using group-wise mean 
  imputation (biopsed=False group separately)
- Engineered custom Risk Scoring System (0-9 scale) 
  using 9 clinical parameters
- Identified 24 High-Risk patients out of 956 
  unbiopsied patients
- Built color-coded Excel Heatmap and Pivot Tables 
  for doctor-ready reporting

## Approach
1. Data Cleaning — Missing value pattern analysis
2. EDA — Biopsed column relationship discovery
3. Feature Engineering — Risk score calculation
4. Visualization — Heatmap, Box plots, Pivot tables

## Files
- Skin_Cancer.ipynb — Complete analysis notebook

## Business Impact
Doctors can now prioritize 24 high-risk patients 
for immediate biopsy — potentially saving lives 
through early cancer detection.
