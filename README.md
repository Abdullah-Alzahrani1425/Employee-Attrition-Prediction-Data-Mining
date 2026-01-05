# Employee Attrition Prediction | Data Mining Project

## 📌 Project Overview
This project addresses a critical HR challenge: **Employee Turnover**. By leveraging the **Data Analytics Lifecycle**, we analyzed a dataset of 1,470 employees and 35 variables to identify key drivers of attrition and build predictive models to help organizations improve retention strategies.

## 🛠️ Methodology (Data Analytics Lifecycle)
We followed a structured, scientific approach to ensure data integrity and model accuracy:

1. **Discovery:** Defined business problems, formulated hypotheses (e.g., the impact of Monthly Income and Work-Life Balance on attrition), and set clear project objectives.
2. **Data Preparation:** Conducted extensive cleaning and feature selection. Rather than random removal, we carefully evaluated all 35 original variables and strategically reduced them to **20 essential predictors**. This selection was based on statistical significance, correlation analysis, and predictive power to ensure model efficiency without losing critical information.
3. **Model Planning (EDA):** Performed Exploratory Data Analysis to uncover patterns. We used correlation matrices, histograms, and box plots to visualize the relationships between variables like `Age`, `MonthlyIncome`, and `Attrition`.
4. **Model Building:** - Developed **12 different Decision Tree models** using various criteria (Gini, Entropy, and Information Gain).
   - Selected the "Best Model" based on a weighted composite score of **Accuracy (0.70)**, Stability, and Simplicity.
5. **Clustering:** Implemented **K-means Clustering** to segment employees into distinct groups, enabling targeted HR interventions and deeper insight into turnover patterns.

## 📊 Key Insights
* **Financial Impact:** Lower monthly income was identified as the strongest predictor of attrition.
* **Role Specifics:** Sales Representatives and Laboratory Technicians showed significantly higher turnover rates.
* **Experience Matters:** Employees with fewer total working years and less experience in their current roles are more likely to leave.

## 📁 Project Structure
* `/Data`: Dataset specifications and cleaning logs.
* `/Reports`: Detailed technical documentation of all 4 Milestones.
* `/Presentation`: Final PowerPoint presentation summarizing the storytelling and recommendations.

## 🔧 Tools Used
* **SAS Viya** (Data Cleaning, Predictive Modeling, and Clustering analysis).
* **Microsoft Word** (Technical reporting and documentation).
* **Microsoft PowerPoint** (Professional results presentation).
