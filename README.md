# Advance AI Fertilizer Recommendation after Soil and Crop Testing

An AI/ML-based system that recommends the most suitable fertilizer for a given crop based on soil and environmental parameters such as temperature, humidity, moisture, soil type, and nutrient levels (Nitrogen, Potassium, Phosphorous).

## 📌 Overview

Choosing the right fertilizer is critical for maximizing crop yield while avoiding over-fertilization, which can harm soil health and the environment. This project uses machine learning to analyze soil and crop conditions and predict the optimal fertilizer recommendation.

## 🎯 Problem Statement

Farmers often rely on generic fertilizer application without considering specific soil composition, crop type, or nutrient deficiencies — leading to reduced yield and soil degradation. This project aims to bridge that gap using a data-driven approach.

## 📊 Dataset

The dataset includes the following features:

| Feature | Description |
|---|---|
| Temperature | Ambient temperature (°C) |
| Humidity | Relative humidity (%) |
| Moisture | Soil moisture content |
| Soil_Type | Type of soil (e.g., Clayey, Loamy) |
| Crop_Type | Type of crop being grown (e.g., Rice, Wheat) |
| Nitrogen | Nitrogen level in soil |
| Potassium | Potassium level in soil |
| Phosphorous | Phosphorous level in soil |
| Fertilizer | Target label — recommended fertilizer |

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
- **Environment:** Jupyter Notebook

## ⚙️ Methodology

1. **Data Preprocessing** — Handling categorical variables (Soil_Type, Crop_Type), checking for missing values, and normalizing numerical features.
2. **Exploratory Data Analysis (EDA)** — Visualizing relationships between soil nutrients, crop type, and fertilizer choice.
3. **Model Building** — Training classification models to predict the appropriate fertilizer.
4. **Evaluation** — Assessing model performance using accuracy, precision, recall, and confusion matrix.

## 🚀 How to Run

1. Clone the repository:
```bash
   git clone https://github.com/soumyamanna-07/Advance-AI-Fertilizer-Recommendation-after-soil-and-crop-tasting.git
```
2. Navigate to the project folder:
```bash
   cd Advance-AI-Fertilizer-Recommendation-after-soil-and-crop-tasting
```
3. Install required libraries:
```bash
   pip install pandas numpy scikit-learn seaborn matplotlib
```
4. Open the notebook:
```bash
   jupyter notebook "ML_farti (1).ipynb"
```

## 📈 Results

Add your model's accuracy, key insights, or sample predictions here once finalized.

## 🔮 Future Scope

- Integrate real-time soil sensor data (IoT-based)
- Deploy as a web/mobile app for farmers
- Expand dataset to cover more crop and soil types

## 👤 Author

**Soumya Manna**
Final Year B.Tech, CSE (AI & ML)
GitHub: [@soumyamanna-07](https://github.com/soumyamanna-07)

## 📄 License

This project is open source and available for educational purposes.
