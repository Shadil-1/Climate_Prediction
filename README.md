# 🌍 Climate Temperature Prediction

## 📌 Project Overview

This project analyzes historical global climate data and builds a Machine Learning model to predict **Land Average Temperature** using various climate-related features. The project includes data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling to understand temperature trends and climate patterns.

---

## 📊 Dataset

**Dataset:** GlobalTemperatures Dataset

### Features Include:
- Date (`dt`)
- Land Average Temperature
- Land Average Temperature Uncertainty
- Land Maximum Temperature
- Land Maximum Temperature Uncertainty
- Land Minimum Temperature
- Land Minimum Temperature Uncertainty
- Land and Ocean Average Temperature
- Land and Ocean Average Temperature Uncertainty

### Target Variable:
- `LandAverageTemperature`

---

## 🎯 Objectives

- Analyze historical climate trends
- Perform data preprocessing and cleaning
- Handle missing values and outliers
- Explore relationships between climate variables
- Build a Machine Learning model for temperature prediction
- Evaluate model performance

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Project Workflow

### 1. Data Collection
- Imported the Global Temperatures dataset.

### 2. Data Preprocessing
- Handled missing values using forward and backward filling
- Removed outliers using the IQR method
- Encoded date features
- Standardized numerical features

### 3. Exploratory Data Analysis
- Temperature distribution analysis
- Temperature category visualization
- Correlation heatmap
- Scatter plots and joint plots
- Climate trend analysis

### 4. Feature Engineering
- Feature scaling using StandardScaler
- Date transformation and encoding

### 5. Model Development
- Train-test split
- Regression model training
- Temperature prediction

### 6. Model Evaluation
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 🔍 Key Insights

- Land and Ocean Average Temperature has a strong relationship with Land Average Temperature.
- Global temperatures show noticeable long-term trends.
- Temperature uncertainty values can significantly affect prediction accuracy.
- Historical climate variables can effectively predict future temperature patterns.

---

## 📂 Project Structure

```text
Climate-Temperature-Prediction/
│
├── Climate.ipynb
├── GlobalTemperatures.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Installation & Usage

### Clone the Repository

```bash
git clone https://github.com/Shadil-1/Climate_Prediction.git
cd climate-temperature-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook
```

---

## 📊 Results

The Machine Learning model successfully predicts land average temperature using historical climate indicators. The analysis provides valuable insights into climate trends and demonstrates the application of data science techniques in environmental studies.

---

## 🔮 Future Improvements

- Incorporate advanced regression models
- Add time-series forecasting techniques
- Develop an interactive Streamlit dashboard
- Analyze regional climate variations
- Improve prediction accuracy through hyperparameter tuning

---

## 👨‍💻 Author

**Shadil K**

Data Science & Machine Learning Enthusiast

### Connect With Me

- LinkedIn: https://www.linkedin.com/in/shadil-k-
- GitHub: https://github.com/Shadil-1)

---

⭐ If you found this project useful, consider giving it a star!
