# 🌍 Air Quality Analysis and Prediction

## 📌 Project Overview

Air pollution has become one of the major environmental concerns affecting human health and climate. This project focuses on analyzing air quality data, cleaning missing values, performing exploratory data analysis (EDA), and building a machine learning model to understand air pollutant behavior and support air quality prediction.

The project is implemented using Python in Google Colab/Jupyter Notebook.

---

## 📂 Dataset

**Dataset:** AirQualityUCI.csv

The dataset contains hourly measurements collected from an air quality monitoring station.

### Features include:

- Date
- Time
- CO (Carbon Monoxide)
- NMHC (Non-Methane Hydrocarbons)
- Benzene Concentration (C6H6)
- NOx
- NO2
- Temperature
- Relative Humidity
- Absolute Humidity
- Various Air Sensor Readings

---

## 🎯 Objectives

- Load and preprocess the Air Quality dataset.
- Handle missing values and invalid data.
- Perform Exploratory Data Analysis (EDA).
- Visualize relationships between environmental variables.
- Study correlations among air pollutants.
- Prepare data for machine learning.
- Build a predictive model for air quality analysis.

---

## 🛠 Technologies Used

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Handle Missing Values
5. Feature Engineering
6. Exploratory Data Analysis
7. Correlation Analysis
8. Data Visualization
9. Model Building
10. Model Evaluation

---

## 📈 Data Preprocessing

The following preprocessing techniques were performed:

- Removed unwanted rows
- Replaced invalid values (-100) with NaN
- Dropped empty records
- Converted Date into datetime format
- Extracted Month from Date
- Extracted Hour from Time
- Checked missing values
- Generated statistical summaries

---

## 📉 Exploratory Data Analysis

The notebook includes:

- Descriptive Statistics
- Correlation Matrix
- Heatmaps
- Distribution Analysis
- Relationship between pollutants
- Missing Value Analysis

---

## 📚 Machine Learning

The cleaned dataset is used for predictive analysis using machine learning techniques.

The workflow includes:

- Data Splitting
- Model Training
- Model Prediction
- Performance Evaluation

---

## 📁 Project Structure

```
Air-Quality-Analysis/
│
├── AirQualityUCI.csv
├── ML_PROJECT.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/Air-Quality-Analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Open Notebook

```bash
jupyter notebook ML_PROJECT.ipynb
```

or upload the notebook to **Google Colab**.

---

## 📦 Required Libraries

```
numpy
pandas
matplotlib
seaborn
scikit-learn
```

---

## 📌 Results

- Successfully cleaned the dataset.
- Performed exploratory data analysis.
- Identified relationships among air pollutants.
- Prepared the dataset for machine learning.
- Generated meaningful visualizations for air quality analysis.

---

## 🚀 Future Improvements

- Deploy the model using Streamlit or Flask.
- Real-time air quality prediction.
- Integration with IoT sensors.
- Weather-based air quality forecasting.
- Deep Learning models (LSTM/RNN) for time-series prediction.

---

## 👩‍💻 Author

**Dharshini G**

B.Tech Student

Interested in Machine Learning, Data Science, and Artificial Intelligence.

---

## ⭐ If you found this project useful

Please consider giving this repository a ⭐ on GitHub!
