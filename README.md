# Life-Expectancy-Analysis
This project explores the relationship between key socioeconomic factors and life expectancy. Using Exploratory Data Analysis (EDA) and regression models, we analyze how variables like GDP per capita, Polio immunization rates, years of schooling, and Infant Deaths influence life expectancy across countries. Additionally, we implement What-If Scenarios to simulate how changes in these variables might affect life expectancy outcomes.

## 📊 Project Workflow
1. Exploratory Data Analysis (EDA)
   - Understand the dataset structure (e.g., missing values, distributions).
   - Visualize key relationships (e.g., GDP vs. Life Expectancy).
   - Identify patterns and potential outliers.
  
2. Feature Engineering & Data Cleaning
   - Handle missing value and data duplicate
   - Split the data into training and testing data
   - Standardize scales where necessary
     
3. Model Building (Regression)
   - Apply both Linear Regression and Random Forest models.
   - Evaluate model performance using metrics:
       - Mean Squarred Error (MAE)
       - Mean Absolute Error (MAE)
       - R² (Coefficient of Determination)

4. What-If Scenarios
   - Simulate the effects of increasing or decreasing:
     - GDP per capita (+10% / -10%)
     - Polio immunization rate (+5% / -5%)
     - Years of schooling (+5% / -5%)
     - Infant Death (10% / -10%)
   - Analyze how these changes impact predicted life expectancy.

## 📈 Key Insights
  - GDP per capita, Polio, and Schooling have the strongest positive correlation with life expectancy.
  - Infant Death, Adult morality, and Incidents HIV have the strongest negative correlation with life expectancy
  - Simulated increases in these variables suggest higher life expectancy, while decreases correlate with a drop in predicted outcomes.

## 🧰 Technologies Used
  - Python (pandas, scikit-learn, matplotlib, seaborn)
  - Machine Learning (Linear Regression, Random Forest)

## 📊 Future Improvements
- Expand to more advanced ML models (e.g., Gradient Boosting).
- Explore Hyperparameter Tuning for the best result.
- Deploy an interactive dashboard to explore the scenarios.
