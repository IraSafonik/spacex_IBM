# SpaceX Launch Success Prediction 🚀

## 💡 Project Overview

In this capstone project, I analyzed SpaceX launch data to predict the success of Falcon 9 first-stage landings. By determining the landing outcome, we can estimate the cost of a launch. This information is crucial for an alternate company planning to bid against SpaceX for a rocket launch.

## ☝️ Project Goals

- Collect and process SpaceX launch data from various sources
- Perform exploratory data analysis to uncover patterns and insights
- Develop interactive visualizations to present findings
- Create a machine learning model to predict landing outcomes
- Identify key factors that influence launch success rates

## 💼 Tasks

1. Data Collection
2. Data Wrangling
3. Exploratory Data Analysis (EDA)
4. Interactive Visual Analytics
5. Predictive Analysis

## 🛠️ Tools and Technologies

- Python
- Pandas and NumPy for data manipulation
- Matplotlib and Seaborn for data visualization
- Folium for interactive maps
- Plotly Dash for interactive dashboards
- Scikit-learn for machine learning
- SQL for database queries
- Jupyter Notebooks for development and documentation

## 🗂️ Data Sources

- [SpaceX REST API](https://api.spacexdata.com/v4/launches/past)
- [Wikipedia - List of Falcon 9 and Falcon Heavy launches](https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches)

## 💻 Process and Steps

### 1️⃣ Data Collection
- Utilized SpaceX API to fetch launch data
- Web scraped additional information from Wikipedia
- Merged data from both sources for a comprehensive dataset

### 2️⃣ Data Wrangling
- Cleaned and preprocessed the collected data
- Handled missing values and outliers
- Created new features for analysis

### 3️⃣ Exploratory Data Analysis (EDA)
- Performed statistical analysis on the dataset
- Created visualizations to understand data distributions and relationships
- Used SQL queries to extract specific insights

### 4️⃣ Interactive Visual Analytics
- Developed an interactive map using Folium to visualize launch sites
- Created a dashboard with Plotly Dash for dynamic data exploration

### 5️⃣ Predictive Analysis
- Prepared data for machine learning
- Trained and evaluated multiple classification models
- Used Grid Search for hyperparameter tuning
- Selected the best-performing model for predictions

## 🌿 Results and Conclusion

After thorough analysis and model development, I achieved the following results:

- Identified key factors influencing launch success, including:
  - Launch site (KSC LC-39A showed the highest success rate)
  - Payload mass (3000-4000 kg range had optimal success rate)
  - Orbit type (ISS missions were more successful than GTO)
- Developed a Decision Tree model with 94% accuracy on the test set
- Created interactive visualizations that provide insights into launch trends and outcomes

In conclusion, this project demonstrates the potential for predicting SpaceX launch successes using historical data and machine learning techniques. The insights gained and the predictive model developed can be valuable for companies looking to compete in the commercial space industry.

---

Feel free to explore the notebooks and scripts in this repository to see the detailed analysis and code implementation. 
