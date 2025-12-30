# CardioSense: Resting Heart Rate Prediction Model 🏃‍♂️💓

## 📌 Executive Summary
**CardioSense** is a data science project investigating the physiological relationship between daily physical activity intensity and cardiovascular health, specifically **Resting Heart Rate (RHR)**. 

Using a hybrid dataset of personal Apple Watch data and public Fitbit data (Kaggle), this project applies machine learning (Linear Regression & Random Forest) to determine if increased workout intensity quantifiably lowers RHR over time.

## 🔍 Key Findings
* **Long-Term vs. Short-Term:** Confirmed that consistent activity over months lowers RHR, though high-intensity days can temporarily raise RHR due to acute recovery stress.
* **The Sleep Factor:** Sleep duration emerged as a stronger predictor of improved heart health than originally hypothesized.
* **Model Performance:** The model achieved an $R^2 \approx 0.25$, successfully identifying key drivers despite high daily physiological noise.

## 🛠 Technologies
* **Python** (Pandas, NumPy)
* **Machine Learning** (Scikit-Learn)
* **Visualization** (Matplotlib, Seaborn)
* **Data Sources:** Apple Health Export (Personal), [Fitbit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit)

## 📂 Project Structure
* `notebooks/CardioSense_Analysis.ipynb`: The primary analysis workflow, including data cleaning, EDA, and modeling.
* `data/`: Contains sample data structure for testing the pipeline.

## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/CardioSense.git](https://github.com/YOUR_USERNAME/CardioSense.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Launch the Notebook:**
    ```bash
    jupyter notebook notebooks/CardioSense_Analysis.ipynb
    ```

## 📊 Methodology
1.  **Data Harmonization:** Merged personal Apple Health exports with public Fitbit CSVs, standardizing time-series data to daily frequency.
2.  **Exploratory Data Analysis (EDA):** Analyzed correlations between active calories, steps, sleep duration, and RHR.
3.  **Modeling:** Trained Linear Regression and Random Forest Regressors to predict daily RHR.

## 👤 Author
**Sujeet Madihalli** [LinkedIn Profile Link](https://www.linkedin.com/in/sujeet-madihalli/) | [Portfolio Link](https://portfolio-sujeet-7ce13.web.app/)
