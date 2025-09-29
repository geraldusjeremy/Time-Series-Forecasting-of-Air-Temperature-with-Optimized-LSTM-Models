
# Time-Series Forecasting of Air Temperature with Optimized LSTM Models

Project Overview

This project focuses on time-series forecasting, specifically predicting air temperature (AT) using a multivariable air quality dataset. The core of the project is a comparative analysis of three different Long Short-Term Memory (LSTM) network architectures to identify the most effective model.

The three models evaluated were:
1.  A **Baseline LSTM** to establish initial performance.
2.  A **Manually Modified LSTM** with an adjusted architecture.
3.  A **Hyperparameter-Tuned LSTM**, systematically optimized using the KerasTuner library.

Performance was measured using Mean Absolute Error (MAE), Mean SquaredError (MSE), and R-squared (R2) to provide a comprehensive evaluation.

Technologies Used
- Python
- TensorFlow / Keras
- KerasTuner
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

 Dataset
The project utilizes a multivariable time-series dataset containing various air quality metrics recorded over time, with Air Temperature (AT) as the target variable for prediction.

How to Run this Project
1. Clone the repository to your local machine:
   ```bash
   git clone [https://github.com/geraldusjeremy/Time-Series-Forecasting-of-Air-Temperature-with-Optimized-LSTM-Models.git](https://github.com/geraldusjeremy/Time-Series-Forecasting-of-Air-Temperature-with-Optimized-LSTM-Models.git)
