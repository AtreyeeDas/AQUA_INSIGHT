# 🌊 Aqua Insight
### Sustainability, Climate Actions & Environmental Sciences - PROJECT
###4th Semester, BTech CSE.
### INSTITUTE OF ENGINEERING AND MANAGEMENT, Kolkata.

## 👤 Contributor
**Atreyee Das** - Solo Contributor 🎓💻

## 📌 Project Overview
Aqua Insight is a machine learning-based water quality analysis project designed to assess the potability of water based on various physicochemical parameters. The project takes user input, analyzes it, and determines whether the water is **safe** or **not safe** for consumption. Additionally, it provides insights into possible contamination causes and suggests purification methods.

## 📊 Dataset Used
The dataset used for this project includes various water quality parameters that influence potability. The key columns in the dataset are:

- **pH** - Acidity or alkalinity of water
- **Hardness (mg/L)** - The amount of dissolved calcium and magnesium
- **Total Dissolved Solids (TDS) (mg/L)** - The concentration of dissolved substances in water
- **Chloramines (mg/L)** - A disinfectant used to treat water
- **Sulfate (mg/L)** - A naturally occurring substance in water
- **Conductivity (µS/cm)** - Water's ability to conduct electricity
- **Organic Carbon (mg/L)** - The amount of carbon-based compounds in water
- **Trihalomethanes (µg/L)** - Chemical byproducts of disinfection
- **Turbidity (NTU)** - Cloudiness of water
- **Potability** - A binary indicator (1 = Safe, 0 = Not Safe)

## ⚙️ How It Works

The project follows these steps:

1. **Data Preprocessing** 🛠️
   - Handles missing values
   - Normalizes and scales the data
   - Balances imbalanced target class using SMOTE
   
2. **Model Training** 🤖
   - Uses a Random Forest classifier model to predict potability
   - Trains the model on labeled water quality data

3. **User Input & Prediction** 🧪
   - Accepts user-provided water quality parameters
   - Predicts whether the water is potable
   
4. **Quality Analysis with Gemini API** 🔬
   - Generates detailed insights on contamination reasons
   - Provides purification recommendations

## 🚀 Why is This Useful?

- **Ensures Safe Drinking Water** 🏡🚰
- **Provides Scientific Justification** 📚
- **Helps in Water Quality Monitoring** 🌎💧
- **Aids in Water Treatment Decisions** 🏭⚗️


## 📌 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   ```
2. Open the notebook in Google Colab.
3. Run the cells step by step.
4. Enter your water quality parameters when prompted.
5. Get the potability prediction and insights.

## 📢 Let's Connect!
💬 Feel free to contribute, report issues, or suggest improvements!

🌟 If you find this project useful, don't forget to **star ⭐ the repository**!

