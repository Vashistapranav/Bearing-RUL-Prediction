# Bearing Remaining Useful Life (RUL) Prediction

## Project Overview
This project focuses on predicting the Remaining Useful Life (RUL) of bearings using Machine Learning techniques and the XJTU-SY Bearing Dataset.

The objective is to estimate the remaining operating time of bearings based on vibration signal analysis and extracted features.

## Dataset
- XJTU-SY Bearing Dataset
- Three operating conditions:
  - 35Hz12kN
  - 37.5Hz11kN
  - 40Hz10kN

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Support Vector Regression (SVR)

## Methodology
1. Vibration signal preprocessing
2. Feature extraction:
   - RMS
   - Kurtosis
   - Standard Deviation
   - Peak-to-Peak
3. Feature normalization
4. Health Indicator (HI) construction
5. Health Indicator smoothing
6. RUL prediction using Support Vector Regression (SVR)
7. Visualization of prediction results

## Machine Learning Model
Support Vector Regression (SVR) is used to estimate the Remaining Useful Life of bearings.

## Project Files
- `XJTU new (3).ipynb` – Project implementation and analysis.

## Project Objective
To develop a machine learning-based approach for estimating bearing degradation and predicting its remaining useful life.
