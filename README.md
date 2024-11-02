# Chocolate-Quality-Analysis
![Project Logo](images/logo.png)

## Introduction
This project explores the factors influencing chocolate quality, focusing on cocoa content, regional origins, and consumer ratings. As consumer interest in high-quality chocolate continues to grow, understanding these factors can help chocolate companies and suppliers make informed decisions about sourcing, production, and marketing. By analyzing cocoa quality data, we aim to uncover patterns in ratings, examine the impact of cocoa content, and highlight top-rated chocolate-producing regions and companies.

## Objective
The primary goal of this analysis is to determine whether cocoa content affects chocolate ratings and to identify regions and companies associated with high-quality chocolate. Through statistical analysis and machine learning techniques, we aim to answer key questions that can provide valuable insights into the chocolate industry.

## Key Focus Areas
1. **Impact of Cocoa Content on Ratings**  
   Does higher cocoa content correlate with better ratings? 

2. **Regional Influence on Chocolate Quality**  
   Which regions are known for producing high-quality cocoa beans?

3. **Top-Rated Companies and Their Sourcing Practices**  
   Which companies are producing the highest-rated chocolate?

4. **Consumer Preferences and Market Trends**  
   How have chocolate ratings and consumer reviews changed over time? 

## Tools and Technologies
The following tools were used in this project:
- **Python (Pandas, Seaborn, Scikit-Learn)**: For data cleaning, exploratory data analysis, and machine learning models.
- **Tableau**: To create interactive visualizations and a final dashboard for presenting the findings.
- **Jupyter Notebook**: For documentation and running analysis scripts in a structured environment.

## Data Source
The data used in this analysis includes can be found [here](https://www.kaggle.com/datasets/rtatman/chocolate-bar-ratings) on Kaggle.

## Analysis Steps
1. **Exploratory Data Analysis (EDA)**  
   Initial exploration to understand data distributions, outliers, and general trends. Visualizations included scatter plots, histograms, and box plots to examine the spread of cocoa percentages, rating distributions, and regional variations.

2. **Correlation Analysis**  
   Generated a correlation matrix to assess relationships between variables, such as cocoa content and rating. Findings indicated weak correlations, suggesting that cocoa percentage alone does not strongly predict chocolate quality.

3. **Linear Regression**  
   Applied linear regression to investigate if cocoa percentage has a significant impact on ratings. Model evaluation metrics, such as Mean Squared Error (MSE) and R-squared, indicated low predictive power, supporting the hypothesis that cocoa content does not meaningfully influence ratings.

4. **Clustering Analysis**  
   Used clustering to identify natural groupings within the data based on cocoa content and rating. This helped reveal patterns in high-rated chocolates and highlighted the most common cocoa ranges in high-quality products.

5. **Time Series Analysis**  
   Conducted time series analysis on the review data to examine trends in chocolate ratings over time. This analysis provided insights into changes in consumer preferences, allowing us to identify peak periods and shifts in demand for high-quality chocolate.

6. **Visualization and Storytelling with Tableau**  
   Developed an interactive Tableau dashboard to present insights on regions with high-rated beans, top chocolate-producing companies and displaying the different advanced analytic methods to show if cocoa content affects chocolate ratings .

## Key Findings
1. **Impact of Cocoa Content**:  
   Minimal correlation was observed between cocoa percentage and rating. This suggests that cocoa content is not a strong determinant of chocolate quality, and other factors may have a greater influence.

2. **High-Rated Regions**:  
   Certain regions, such as Central and South America, West Africa, and parts of Southeast Asia, consistently produce higher-rated beans. This may be due to favorable growing conditions, regional expertise, or unique cocoa bean varieties.

3. **Top Chocolate-Producing Companies**:  
   The highest-rated companies tend to source their beans from regions known for quality, implying a possible link between sourcing choices and product ratings.

4. **Consumer Trends Over Time**:  
   Analysis of review dates and ratings suggested changing trends in chocolate preferences, with a peak in ratings around certain years.

   
Some key insights from the analysis include:
- **Regions with High Ratings**: Identifying top cocoa-producing areas known for high ratings.
- **Limited Influence of Cocoa Content**: Cocoa content alone does not appear to significantly affect chocolate ratings.
- **Company and Region Alignment**: Top-rated companies often source from high-rated regions, suggesting the importance of origin in quality perception.

## Repository Structure
- **/data/**: Contains raw and cleaned datasets used for analysis.
- **/scripts/**: Python scripts for data processing, analysis, and visualization.
- **/notebooks/**: Jupyter notebooks documenting the analysis steps in detail.
- **/visualizations/**: Exports of Tableau dashboards and other visualizations generated in Python.
- **README.md**: Overview of the project, including objectives, methodology, and findings.

- ## How to run the Code
The code is available as jupyter notebooks. To run the analysis, navigate to the [Scripts](./Scripts) directory and open the relevant Jupyter notebooks.


## Results
Click here for the [Tableau Storyboard](https://public.tableau.com/app/profile/magdalena.hofbauer/viz/ChocolateBarAnalysis_17305697958730/ChocolateBarAnalysis?publish=yes)
