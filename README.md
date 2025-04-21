# 🎬 Movie Rating Prediction

This project focuses on analyzing and predicting IMDb ratings for Indian movies using machine learning techniques. It explores patterns in movie-related features such as genre, duration, cast, director, and votes to develop a reliable predictive model.

---

## 📌 Task Objectives

- Understand and preprocess the IMDb India Movies dataset.
- Perform exploratory data analysis (EDA) to identify trends and insights.
- Build and evaluate regression models to predict movie ratings.
- Optimize model performance using techniques like hyperparameter tuning.
- Present a clean and well-documented pipeline for reproducibility.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning modeling
- **Jupyter Notebook** – Code and analysis environment

---

## 📂 Dataset

- **Source**: [IMDb Indian Movies Dataset on Kaggle](https://www.kaggle.com/)
- **Format**: CSV
- **Columns**:
  - `Name`
  - `Year`
  - `Duration`
  - `Genre`
  - `Rating`
  - `Votes`
  - `Director`
  - `Actor 1`, `Actor 2`, `Actor 3`

---

## 🚀 Steps to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/movie-rating-prediction.git
   cd movie-rating-prediction
Install Dependencies Ensure Python and pip are installed, then run:

bash
Copy
Edit
pip install -r requirements.txt
Add the Dataset Download the dataset from Kaggle and place the CSV file inside the Data Files directory.

Run the Notebook Launch Jupyter Notebook and run the main file:

bash
Copy
Edit
jupyter notebook
Open movie_rating_prediction.ipynb and execute all cells sequentially.

## 📊 Project Workflow
  1. Data Cleaning
    Handle missing values
    
    Convert text-based columns to appropriate formats
    
    Extract and standardize numerical features (e.g., duration)
  
  2. Exploratory Data Analysis (EDA)
    Visualize rating distributions and relationships
    
    Analyze popular genres, directors, and actors
    
    Correlation heatmaps and outlier checks
    
  3. Feature Engineering
    Label encoding for categorical variables
    
    Generate new features like:
    
      Director Success Rate
      
      Average Votes of Cast
      
      Movie Age
  
  4. Model Building
    Algorithms used:
    
     1. Linear Regression
      
     2. Random Forest Regressor
      
     3. Gradient Boosting Regressor
      
     4. Evaluation metrics:
      
     5. R² Score
      
     6. Root Mean Squared Error (RMSE)
      
     7. Model tuning using GridSearchCV

## ✅ Evaluation Criteria

  ✔️ Functionality: Accurate and reliable prediction of IMDb movie ratings
  
  ✔️ Code Quality: Modular, clean, and well-commented scripts
  
  ✔️ Readability: Logical structure and descriptive documentation
  
  ✔️ Insights: Clear visualizations and understandable findings

## 📁 Folder Structure
    
    movie-rating-prediction/
    │
    ├── Data Files/
    │   └── indian_movies.csv
    │
    ├── images/
    │   └── charts and graphs from EDA
    │
    ├── models/
    │   └── saved_model.pkl
    │
    ├── movie_rating_prediction.ipynb
    ├── requirements.txt
    └── README.md


## 📬 Contact

  Prasanna Venkatesh
  📧 prasannavenkatesh.5261@gmail.com
