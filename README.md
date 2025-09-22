
 Air Quality Forecasting (Beijing PM2.5 Prediction)


This repository contains my work for the **Machine Learning Techniques I course assignment on air quality forecasting. The task is to predict PM2.5 concentrations** in Beijing using deep learning models (RNN, LSTM, GRU, CNN-LSTM).



Project Overview
- Preprocessed historical weather and pollution data.
- Handled missing values using time interpolation.
- Transformed data into sliding window sequences.
- Implemented LSTM, GRU, BiLSTM, CNN-LSTM models.
- Conducted 16 hyperparameter experiments.
- Evaluated using Root Mean Squared Error (RMSE).
- Submitted predictions to Kaggle.



Repository Structure
├── data/
│ ├── train.csv
│ ├── test.csv
│ ├── sample_submission.csv
├── notebooks/
│ ├── air_quality_forecasting.ipynb
├── submission/
│ ├── submission_final.csv
├── README.md
└── report.pdf




 Requirements
- Python 3.10+
- TensorFlow 2.12+
- NumPy, Pandas, Scikit-learn
- Matplotlib, Seaborn

Install dependencies:

pip install -r requirements.txt

 How to Run

Clone this repo:

git clone https://github.com/yourusername/air-quality-forecasting.git
cd air-quality-forecasting


Open the Jupyter notebook:

jupyter notebook notebooks/air_quality_forecasting.ipynb


Train model and generate submission:

!python train_and_submit.py


Submit submission_final.csv to Kaggle.

Results

 Validation RMSE: 51.8872901160902 (best GRU model).
Kaggle public score 4205.6987 (over target 3000).
