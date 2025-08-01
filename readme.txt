#☀️ Renewable Energy Forecasting
This project focuses on forecasting solar energy generation using machine learning models, based on key environmental parameters such as Global Horizontal Irradiance (GHI),
wind speed, and temperature.

A variety of regression models are employed to predict energy output, helping support energy planning and sustainable resource utilization.

**************************************************************************************************************************************************************************

🔍 Overview
📊 Forecasts solar energy generation using historical and daily environmental data

📌 Uses parameters like:

GHI (Sun exposure)

Wind speed

Temperature

🤖 Models used:

Linear Regression

Random Forest

Support Vector Machine (SVM)

Decision Tree Regressor

***************************************************************************************************************************************************************************

🗂️ Project Structure
bash
Copy
Edit
📦 Renewable_Energy_Forecasting/
├── training_data/                  # Contains historical training data in CSV format
├── test_data/                      # Test data for model evaluation
├── trained_model/                  # Stores serialized/trained models
├── daily_processed_ghi_data/       # Daily input data used for forecasting
├── R1_file/                        # Forecast output results
├── forecasted_data/               # Final predicted energy generation
├── preprocessing_scripts/         # Scripts used for data cleaning and transformation
├── model_training.py              # Script to train all models
├── forecast_prediction.py         # Script to generate forecasts using saved models
└── README.md                      # Project documentation

***************************************************************************************************************************************************************************

🔄 Workflow
Load and preprocess data from the training_data/ and test_data/ directories.

Train multiple machine learning models on the preprocessed data.

Save trained models into the trained_model/ directory.

Use daily GHI and weather data from daily_processed_ghi_data/ to forecast solar energy generation.

Store prediction results in R1_file/ and forecasted_data/ folders for analysis and reporting.

***************************************************************************************************************************************************************************

📦 Requirements
Python 3.x

pandas

numpy

scikit-learn

matplotlib (optional for visualization)

***************************************************************************************************************************************************************************

📈 Applications
Renewable energy production planning

Smart grid optimization

Solar farm energy forecasting

Environment-aware energy analytics
