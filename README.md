# California Housing Price Prediction 🏡

## 📌 Project Overview

This project focuses on predicting house prices in California using Machine Learning. It uses housing data to train a Random Forest Regression model and predict median house values based on different features.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

## 🎯 Objectives

- Analyze California housing data.
- Perform data cleaning and preprocessing.
- Handle missing values in numerical and categorical features.
- Visualize housing price distributions.
- Build a Machine Learning model to predict house prices.
- Evaluate model performance using regression metrics.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🤖 Machine Learning Algorithm

**Random Forest Regression**

Random Forest Regression is used to predict median house prices by combining predictions from multiple decision trees.

## ⚙️ Project Workflow

1. **Data Collection:** Load the California housing dataset.
2. **Data Exploration:** Analyze dataset structure, statistical information, and missing values.
3. **Data Visualization:** Visualize the distribution of median house values.
4. **Data Preprocessing:**
   - Handle missing numerical values using median imputation.
   - Handle missing categorical values using most frequent imputation.
   - Apply StandardScaler to numerical features.
   - Apply OneHotEncoder to categorical features.
5. **Model Training:** Train a Random Forest Regression model using an 80:20 train-test split.
6. **Prediction:** Predict house prices using test data.
7. **Model Evaluation:** Evaluate predictions using MAE, RMSE, and R² Score.

## 📊 Model Evaluation Metrics

The model is evaluated using:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted prices.
- **RMSE (Root Mean Squared Error):** Measures prediction error while giving higher weight to larger errors.
- **R² Score:** Measures how well the model explains variations in house prices.

## 📂 Project Structure

```text
California-Housing-Price-Prediction/
│
├── machine_learningproject.ipynb
├── housing.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Navigate to the project folder:

```bash
cd California-Housing-Price-Prediction
```

3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `machine_learningproject.ipynb` and run all cells.

**Note:** Place `housing.csv` in the project folder and update the dataset path in the notebook to use the local file.

## 💡 Key Learnings

- Understanding Machine Learning workflows.
- Data cleaning and preprocessing techniques.
- Handling missing values and categorical features.
- Building ML pipelines using Scikit-learn.
- Training and evaluating regression models.
- Data visualization and exploratory data analysis.

## 👨‍💻 Author

**Adityavardhan Kakade**

- GitHub: https://github.com/Avk07-coder
- LinkedIn: https://linkedin.com/in/adityavardhan-kakade

---

⭐ If you find this project useful, feel free to explore the repository!
