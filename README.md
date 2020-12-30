

# *Medical Insurance Exploratory Data Analysis*

## Project Goals 

- Explore Data set to discover trends, anomalies, and correlations to the rates.
- Clean and optimize data set for visualizations and machine learning.
- Create clear and insightful visualizations to describe and showcase findings.



## Table of Contents

<details>
    <summary>Open</summary>

        1. File Descriptions
        2. Technologies Used
        3. Executive Summary

</details>

## File Descriptions

<details>
    <summary>Open</summary>

- insurance.csv: data pre-clean.
- Medical_Insurance_Project.ipynb: jupyter notebook on data anaylsis.

</details>

## Technologies Utilized

<details>
    <summary>Open</summary>

        1. Python3
        2. Pandas
        3. Matplotlib
        4. Seaborn
        5. Sci-py
        6. Numpy
        7. Sci-kit learn

</details>

 ## Executive Summary
<details>
    <summary>Open</summary>
    <h2>Primary Goals</h2>

    <p>The goals I set out for this project was to collaborate with data analyst Corey Arrington on a portfolio piece that showcases a range of our abilities. Furthermore I set out to create value for those interested investing into medical insurance, helping them understand the variables and features that contribute to the pricing model. This is a high level overview and not specific to one company or a one solution that speaks for all companies."</p>


### Library Imports
<details>
    <summary>Part 1</summary>

    <h3>Importing required Libraries, Loading into Dataframe</h3>
    <p>The require libraries included the utilization of primarily pandas, numpy, matplotlib, and seaborn. The inclusion of sklearn was for preprocessing.</p>
</details>

<details>
    <summary>Part 2</summary>
    <h3>Early Eda</h3>
    <p> This portion focused primarily on understanding the key statistics
    and evaluation of the data frame. These findings were as follows:
    <h5>Max Value</h5>

    The max values showed a high of 64 in age, 53.13 in BMI, 5 in children, and lastly $63770.40 in charges.
    <h5>Min Value</h5>

    The min values showed a low of 18 in age, 15.96 in BMI, 0 in children, and lastly $1121.87 in charges.
</details>
  <h5>Mean Value</h5>

    The mean values showed a average of 39 in age, 30 in BMI, 1 in children, and lastly $13270.42 in charges.
</details>
<details>
    <summary>Part 3</summary>
    <h3>Data Visualization</h3>
    <h5>Histogram: BMI</h5>
<img src="https://github.com/AlignedMind/Medical-Insurance-Analysis-EDA/blob/main/images/hist_bmi.png" alt="Histogram: BMI">
 -----
    <h5>Histogram: Charges</h5>
<img src="https://github.com/AlignedMind/Medical-Insurance-Analysis-EDA/blob/main/images/hist_charge.png" alt="Histogram: Charges">
 -----
    <h5>Histogram: Age</h5>
<img src="https://github.com/AlignedMind/Medical-Insurance-Analysis-EDA/blob/main/images/hist_age.png" alt="Histogram: Age">
 -----
    <h5>Histogram: Children</h5>
<img src="https://github.com/AlignedMind/Medical-Insurance-Analysis-EDA/blob/main/images/hist_children.png" alt="Histogram: Children">
 -----
    <h5>HeatMap: Correlation</h5>
<img src="https://github.com/AlignedMind/Medical-Insurance-Analysis-EDA/blob/main/images/heatmap.png" alt="HeatMap: Correlation">
 -----
    <h5>Category Plot: Side By Side Bar Plot</h5>
<img src="https://github.com/AlignedMind/Medical-Insurance-Analysis-EDA/blob/main/images/barplot.png" alt="Category Side By Side Bar Plot">
 -----
    <h5>Scatter Plot: Regressors </h5>
<img src="https://github.com/AlignedMind/Medical-Insurance-Analysis-EDA/blob/main/images/scatter.png" alt="Category Side By Side Bar Plot">
<p>
- Clear Regression pattern, bottom details that the older you become there is an increase in charges in addition to the higher bmi

- Second regression pattern shows that individuals with low bmi's that are smokers pay nearly the same as high bmi non smokers.

- Third regression pattern shows higher bmi that are smokers pay alot more the older they become.
</p>
</details>

<details>
    <summary>Part 4</summary>
    <h3>Summarizing Findings</h3>
    <h4>Who pays more in medical insurance and why ?</h4>
    <p>Smokers carry the highest correlated inflation to price at .78, next comes the age variable at .29 and then rounding the top 3 is bmi at .19. Given these features there is a clear pattern the older and the heavier you are there is a increase on the price you pay. Whereas no matter your age or weight if you smoke there is a sustantial increase on the individuals medical insurance cost. Men on average pay more than women when factoring in smoking and women pay more when considering non-smokers.</p>
    <div>
</details>
    <details>
    <summary>Part 5</summary>
    <h3>Closing Thoughts</h3>
    <p> This project is part 1 of a whole, the next portion will serve as a machine learning project. Utilizing ensemble learning to predict charges based on the present features of this data set.
    </p>
</details>
