# Swire Coca-Cola Machine Downtime Prediction Capstone

**Business Problem:**  
Swire Coca-Cola faces significant operational challenges due to unplanned machine downtimes, leading to an estimated $60 million in annual losses. These disruptions affect production efficiency and increase operational costs. Addressing this issue is critical for ensuring uninterrupted production and minimizing revenue losses.

**Project Objective:**  
The goal of this project was to develop predictive models capable of identifying key drivers of machine downtimes and accurately predicting major breakdowns. By leveraging data analytics and machine learning, our team aimed to deliver actionable insights that enable Swire Coca-Cola to proactively manage machine maintenance and improve operational efficiency.

**Group Solution:**  
Our team used a combination of Exploratory Data Analysis (EDA) and machine learning to analyze downtime data and predict breakdown risks. Key components of our solution include:
- **Random Forest Model:** Achieved an Out-of-Bag error rate of 6.93% and an accuracy of 89.59%, effectively identifying high-risk machines and critical downtime predictors.
- **Feature Engineering:** Introduced key variables such as machine age, minor vs. major breakdown classification, and rolling average downtime trends to enhance predictive power.
- **Insights:** Highlighted the importance of frequent minor breakdowns as a leading indicator of major breakdowns and emphasized the role of machine age in planned maintenance.

**Key Findings:**  
1. **Breakdown Classification:**  
   - Machines with frequent minor breakdowns (<60 minutes) are more likely to experience major breakdowns (>60 minutes).  
   - Machine age was found to be a significant predictor, with newer equipment requiring more planned maintenance.  
2. **Feature Importance:**  
   - Maintenance-related features such as maintenance plans and order descriptions were among the most critical in predicting major breakdowns.  
3. **Cost Impact:**  
   - Reducing major breakdowns by 20% could save Swire Coca-Cola approximately $3.8 million annually.  

**Files in Repository:**  
- **Business Problem Statement.pdf:** Document outlining the business context and objectives.  
- **Capstone.pdf:** Final presentation summarizing findings, results, and recommendations.  
- **EDA HTML.html:** Exploratory Data Analysis results in HTML format.  
- **EDA RMD.Rmd:** RMarkdown file used to generate the EDA report.  
- **Modeling HTML.html:** Machine learning modeling results in HTML format.  
- **Modeling.Rmd:** RMarkdown file used to generate the modeling report.  

**Group Contributions:**  
Our team collaborated extensively throughout the project:
- **EDA:** Analyzed downtime patterns, identified data quality issues, and visualized trends.  
- **Modeling:** Built and optimized Random Forest and Logistic Regression models to predict breakdowns.  
- **Feature Engineering:** Designed new variables, such as failure risk categories and rolling average downtimes, to improve model performance.  
- **Insights and Recommendations:** Synthesized findings into actionable recommendations for Swire Coca-Cola.

**Business Value:**  
- **Proactive Maintenance Planning:** The insights enable Swire Coca-Cola to identify high-risk machines and schedule maintenance before major breakdowns occur.  
- **Cost Savings:** The models provide a roadmap for reducing downtime-related losses by millions annually.  
- **Improved Data Processes:** Highlighting the need for improved data tracking (e.g., machine age) to enhance future analyses.

**Difficulties Encountered:**  
One of the main challenges was dealing with missing data in critical variables such as machine age and certain equipment-related fields. For instance:
- **Machine Age Data:** The lack of consistent tracking meant that machine age could only be calculated for planned maintenance events. This limited its application as a predictive feature across all data.
- **Imbalanced Data:** Some categories (e.g., minor vs. major breakdowns) had disproportionately large or small sample sizes, complicating model training.
- **Data Completeness:** Many fields had high percentages of missing values, requiring imputation or removal to maintain model quality. Columns with over 80% missing data were ultimately excluded due to their limited value.
These challenges underscored the importance of improving data collection processes for future predictive analytics.

**Lessons Learned:**  
- **Data Quality Matters:** Addressing missing data and feature engineering were critical to the project’s success.  
- **Collaborative Problem-Solving:** Each team member's unique contributions led to a well-rounded solution.  
- **Real-World Data Challenges:** Managing imbalanced data and aligning findings with business objectives were key hurdles.

**Next Steps:**  
1. Implement the Random Forest model into Swire Coca-Cola’s production systems for real-time breakdown monitoring.  
2. Develop processes for tracking and analyzing machine age and downtime trends.  
3. Use insights from minor breakdowns to optimize preventative maintenance strategies.  

This project showcases how predictive analytics can transform operational efficiency and drive significant cost savings for Swire Coca-Cola. For more details, refer to the files in this repository.
