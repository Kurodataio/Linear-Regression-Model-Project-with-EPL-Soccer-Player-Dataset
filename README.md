# Linear-Regression-Model-Project-with-EPL-Soccer-Player-Dataset
Linear Regression Model Project in Python with EPL Soccer Player Dataset #1


[Notebook Link](https://github.com/Kurodataio/Linear-Regression-Model-Project-with-EPL-Soccer-Player-Dataset/blob/main/lr-soccer-scores.ipynb)  

---

## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Analysis & Visualizations](#analysis--visualizations)  
- [Conclusion](#conclusion)  
- [Credits](#credits)  

---

## Overview
- This project uses linear regression, a foundational Machine Learning technique predict the scores of EPL soccer players.

## Dataset

- The dataet is the EPL player dataset (link if available)  
- The size of the dataset is 202 rows and 13 columns

Dataset: EPL_Soccer_MLR_LR.csv

---

<h2>Technologies Used</h2>

<ul>
  <li><strong>Languages & Libraries:</strong> Python, Pandas, NumPy, Matplotlib, Seaborn, Scipy, sklearn, statsmodels</li>
  <li><strong>Tools:</strong> Jupyter Notebook, VS Code, Git, GitHub</li>
</ul>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib">
  <img src="https://img.shields.io/badge/-Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Seaborn">
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/statsmodels-4C8CBF?style=for-the-badge&logo=python&logoColor=white" alt="statsmodels">
</p>

<P>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Notebook"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" alt="VS Code"/>  
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</p>

---

## Installation

Step-by-step instructions to set up the project locally:

```bash

# Clone the repository
git clone https://github.com/Kurodataio/Linear-Regression-Model-Project-with-EPL-Soccer-Player-Dataset.git

# Navigate to the project folder
cd https://github.com/Kurodataio/Linear-Regression-Model-Project-with-EPL-Soccer-Player-Dataset

# Launch Jupyter Notebook
jupyter notebook


```

## Usage

Instructions for using the project:

1. Open the main notebook (`lr-soccer-scores.ipynb`)  
2. Run each cell sequentially to reproduce the analysis  
3. Visualizations and results will be generated automatically  

---

## Analysis & Visualizations 
- Distibution of Numeric values
![Distibution of Numeric values](images/distribution_of_numeric_values.png)  
- We have plotted numerical value pairs to show any positive, negative or non correlations.
![Scatter plot between AgentCharges and Score](images/Scatter_plot_between_AgentCharges_and_Score.png)  
![Scatter plot between BMI and Score](images/Scatter_plot_between_BMI_and_Score.png)  
![Scatter plot between Cost and Score](images/Scatter_plot_between_Cost_and_Score.png)  
![Scatter plot between DistanceCovered(InKms) and Score](images/Scatter_plot_between_DistanceCovered(InKms)_and_Score.png)  
![Scatter plot between Goals and Score](images/Scatter_plot_between_Goals_and_Score.png)  
![Scatter plot between Height and Score](images/Scatter_plot_between_Height_and_Score.png)  
![Scatter plot between MinutestoGoalRatio and Score](images/Scatter_plot_between_MinutestoGoalRatio_and_Score.png)  
![Scatter plot between PreviousClubCost and Score](images/Scatter_plot_between_PreviousClubCost_and_Score.png)  
![Scatter plot between ShotsPerGame and Score](images/Scatter_plot_between_ShotsPerGame_and_Score.png)  
![Scatter plot between Weight and Score](images/Scatter_plot_between_Weight_and_Score.png)  
- Feature (column) correlation plot
![Feature_Correlation_Matrix](images/Feature_Correlation_Matrix.png)  
- Score & Cost ($0.96$), has a positive linear relationship
- ShotsPerGame & MinutesToGoalRatio (0.95), another strong positive correlation, showing a close relationship between shooting volume and scoring frequency metrics.
- Weight & Height (0.78), Weight & PreviousClubCost (0.93), Height & PreviousClubCost (0.80), have high positive correlations.
- DistanceCovered(InKms) with MinutesToGoalRatio (0.92) & ShotsPerGame (0.89), show distance covered strongly correlates with shots per game and minutes-to-goal ratio.

<!-- 
![Visualization Example](images/)   
-->

---

## Conclusion 
- The Cost and Score plot shows a strong positive correlation.
![Scatter plot between Cost and Score](images/Scatter_plot_between_Cost_and_Score.png)  
- There is a linear upward trend between cost (independent variable, x-axis) and score (dependent variable, y-axis).
- The regression model fitted to the training data, predicts the test data well. 
![Regression line through Training Data](images/Regression_line_through_the_Training_Data.png) 
![Regression line through Test Data](images/Regression_line_through_the_Testing_Data.png)  
- Based on the data, the cost of players is a strong predictor of average score per match. In other words the average score per match is strongly correlated withs costs of players.
- There is a strong correlation between ShotsPerGame and MinutesToGoalRatio of 0.95.
---

## Credits

- **ProjectPro:** Linear Regression Model Project in Python... #1 
- **Dataset Source:** [ProjectPro](https://www.projectpro.io/)   

---


