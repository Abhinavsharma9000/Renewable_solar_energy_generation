
****************************************Renewable_Energy_Forecasting********************************************

This project forecasts the generation of solar energy based on few parameters such as Sun exposure(GHI), wind and temperature.
The models used in forecasting the generation are Linear regression, Random Forest, Support Vector Machine and decision tree.

In training_data and test_data folders comprise of required data. The data is in csv format.
The data is preprocessed and then used to train the models.
The models are then saved in trained_model folder and are used to predict the generation of solar energy on dataset present in daily_processed_ghi_data folder.
The results are stored in R1_file and forecasted_data folders
