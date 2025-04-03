# Water-Portability-Analysis
EVS PROJECT - 4th Semester
# Water Quality Analysis using AI

## Overview
This project predicts the potability (safety for drinking) of water based on various water quality parameters. It utilizes machine learning to classify water as **safe** or **not safe**, and integrates **Google's Gemini AI** for further analysis and suggestions on water quality improvement.

## Dataset
The dataset used in this project is sourced from Kaggle: **Water Quality and Potability Dataset**. It contains various physicochemical attributes of water and a label indicating whether the water is potable.

### Features in the dataset:
- **pH**: Measure of how acidic/basic the water is.
- **Hardness (mg/L)**: Amount of dissolved calcium and magnesium in the water.
- **Total Dissolved Solids (TDS) (mg/L)**: Concentration of dissolved substances in water.
- **Chloramines (mg/L)**: Disinfectants used in water treatment.
- **Sulfate (mg/L)**: Concentration of sulfate ions in water.
- **Conductivity (µS/cm)**: Water's ability to conduct electricity.
- **Organic Carbon (mg/L)**: Presence of organic compounds in water.
- **Trihalomethanes (µg/L)**: Byproducts of chlorine disinfection.
- **Turbidity (NTU)**: Cloudiness of water.
- **Potability** (Target Variable): **1** (Safe), **0** (Not Safe)

## Code Explanation
This project is implemented as a **standalone Python script in Google Colab**, allowing users to input water quality values and receive predictions.

### 1. **Dataset Handling**
- The dataset is downloaded from Kaggle.
- Missing values are filled using the median.
- Features (X) and target variable (y) are separated.
- Train-test split is performed (75%-25%).
- **SMOTE** (Synthetic Minority Over-sampling Technique) is used to balance the dataset.

### 2. **Data Preprocessing**
- Data is normalized using **StandardScaler** to improve model performance.

### 3. **Model Training**
- A **RandomForestClassifier** is trained on the preprocessed data.

### 4. **User Input Handling**
- The program prompts users to enter values for each water quality parameter.

### 5. **Prediction**
- The trained model predicts whether the water is safe (**potable**) or unsafe (**not potable**).

### 6. **Google Gemini AI Analysis**
- The input values are sent to Google's **Gemini AI**.
- Gemini AI provides a detailed analysis explaining:
  - If the water is safe or not.
  - Main contamination reasons.
  - Suggested purification techniques.

## How This Project is Useful
- **Public Health Awareness**: Helps identify unsafe drinking water sources.
- **AI-Driven Insights**: Uses **Google Gemini AI** to provide advanced analysis.
- **Data-Driven Decision Making**: Can assist in **policy-making** and **environmental monitoring**.
- **Customizable & Expandable**: The code can be improved with additional parameters, more advanced ML models, or better AI integration.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/water-quality-analysis.git
   ```
2. Open the Google Colab notebook and run the cells.
3. Enter water quality values when prompted.
4. View the prediction and Gemini AI analysis in the output.

## Future Enhancements
- Integration with **deep learning models** for higher accuracy.
- Deploying as a **web app** for ease of access.
- Adding real-time water quality data sources.

---
**Contributors**: *Your Name*

For questions, feel free to raise an issue or contribute to the project!

