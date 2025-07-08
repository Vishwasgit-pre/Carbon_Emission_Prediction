# Carbon Emission Prediction using Machine Learning

## Project Overview

This project aims to build a regression-based machine learning model to predict **CO₂ emissions (g/km)** from vehicle specifications such as engine size, fuel consumption, number of cylinders, fuel type, and transmission.

The solution helps in:
- Understanding the key factors influencing carbon emissions
- Supporting environmental policy development
- Encouraging eco-friendly vehicle choices

## Dataset Description

The dataset includes the following features:
- `Make`, `Model`, `Vehicle Class`
- `Engine Size`, `Cylinders`
- `Transmission`, `Fuel Type`
- `Fuel Consumption (City, Hwy, Combined)`
- `CO2 Emissions (g/km)` (Target variable)

## Methodology

1. **Data Exploration** – Visualization and correlation analysis to identify influential features.
2. **Preprocessing** – Handled missing values, encoded categorical data, and scaled numeric features.
3. **Model Building** – Used `Linear Regression` and evaluated with R², MAE, and RMSE.
4. **Model Deployment** – Trained model saved using Python's `pickle` for real-world deployment.

## Tools & Technologies Used

- Python
- Jupyter Notebook
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- pickle (for model serialization)

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/carbon-emission-prediction.git
   cd carbon-emission-prediction
   ```

2. Install required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebooks to view the workflow:
   - `Data Exploration - Carbon Emission.ipynb`
   - `Model building.ipynb`

4. Use the trained model (see below) to predict emissions for new vehicle entries.

## Model File (Pickle)

Due to GitHub's file size limits, the trained model file (`carbon_emission_model.pkl`) is hosted on Google Drive.

**Download Link:**  
[Download Pickle File from Google Drive](https://drive.google.com/file/d/1hAzSHgdZXz14U0QUU3_Hu_L3ODezgL6I/view?usp=sharing)

> After downloading, place the `carbon_emission_model.pkl` file in the project root directory before running any deployment or inference script.

## Conclusion

- Fuel consumption and engine size are the most impactful predictors of CO₂ emissions.
- The model can be used by manufacturers, policymakers, and eco-conscious consumers.
- Demonstrates real-world application of regression and data science practices.

## Future Scope

- Incorporate more vehicle-specific features (e.g., weight, hybrid status).
- Use ensemble models for better accuracy.
- Deploy via a Flask or Streamlit web interface
