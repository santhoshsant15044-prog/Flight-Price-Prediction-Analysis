# Flight Price Prediction and Analysis
## Problem Statement
This project aims to predict flight ticket prices using machine learning. The goal is to identify the key factors that influence airline pricing and build a regression model that can provide accurate price estimates for various routes and timings.
## Dataset
The dataset used for this project was sourced from Kaggle. [Link to the Kaggle dataset here](https://www.kaggle.com/datasets/nikhilmittal/flight-fare-prediction-mh)
## My Process
1.  **Data Cleaning:** Handled missing values and corrected data types for features like `Date_of_Journey` and `Duration`.
2.  **Exploratory Data Analysis (EDA):** Used Matplotlib and Seaborn to visualize relationships between features like Airline, Stops, and the final Price.
3.  **Feature Engineering:** Extracted new features like journey day/month and converted categorical columns (e.g., Airline, Source) into a numerical format using one-hot encoding.
4.  **Model Building:** Trained and evaluated several regression models, including Linear Regression and Random Forest, to find the best performer.
5.  **Evaluation:** The final Random Forest model achieved an R² score of 0.82 on the test set, explaining 82% of the price variance.
## Key Learnings
- Gained deep insights into the critical impact of feature engineering, where transforming columns like `Duration` and `Date_of_Journey` significantly boosted model performance.
- Learned to interpret model predictions by analyzing feature importance, identifying that factors like duration and number of stops are the most significant price drivers.

---
## Tech Stack 💻
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

---
## How to Use 🚀
To run this project on your local machine, follow these steps:
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/santhoshsant15044-prog/Flight-Price-Prediction-Analysis.git](https://github.com/santhoshsant15044-prog/Flight-Price-Prediction-Analysis.git)
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd Flight-Price-Prediction-Analysis
    ```
3.  **Install the required libraries:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: You will need to create a `requirements.txt` file by running `pip freeze > requirements.txt` in your terminal)*
4.  **Run the Jupyter Notebook:**
    ```bash
    jupyter notebook "Flight Price Prediction Analysis.ipynb"
    ```
