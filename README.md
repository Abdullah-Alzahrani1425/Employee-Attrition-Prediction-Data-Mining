# Employee Attrition Prediction | Data Mining Project

## 📌 Project Overview
This project addresses a critical HR challenge: **Employee Turnover**. By leveraging the **Data Analytics Lifecycle**, we analyzed a dataset of 1,470 employees and 35 variables to identify the key drivers of attrition and build predictive models to help organizations improve retention strategies.

## 🛠️ Methodology (Data Analytics Lifecycle)
We followed a structured scientific approach to ensure data integrity and model accuracy:

1. **Discovery:** Defined business problems, formulated hypotheses (e.g., the impact of Monthly Income and Work-Life Balance on attrition), and set project objectives.
2. **Data Preparation:** Conducted extensive cleaning using **SAS Enterprise Miner**. This included handling missing values, identifying outliers, and reducing the dataset from 35 to 20 highly relevant variables.
3. **Model Planning (EDA):** Performed Exploratory Data Analysis to uncover patterns. We used correlation matrices, histograms, and box plots to visualize the relationship between variables like `Age`, `MonthlyIncome`, and `Attrition`.
4. **Model Building:** - Developed **12 different Decision Tree models** using various criteria (Gini, Entropy, and Information Gain).
   - Selected the "Best Model" based on a weighted score of **Accuracy (0.70)**, Stability, and Simplicity.
5. **Clustering:** Implemented **K-means Clustering** to segment employees into distinct groups, allowing for targeted HR interventions.

## 📊 Key Insights
* **Financial Impact:** Lower monthly income is the strongest predictor of attrition.
* **Role Specifics:** Sales Representatives and Laboratory Technicians show higher turnover rates.
* **Experience Matters:** Employees with fewer total working years are more likely to leave the organization.

## 👥 Contributors & Roles
| Name | Assigned Role | Key Contributions |
| :--- | :--- | :--- |
| **Mohannad Abdullah Alamri** | Data Preparation Lead | Data collection, cleaning, handling outliers, and defining variable roles in SAS. |
| **Tariq Zaid Alqhtani** | EDA Specialist | Visualizations (Histograms, Box plots), correlation analysis, and pattern interpretation. |
| **Abdullah Atiah Alzahrani** | Modeling & Evaluation Lead | DT model design, parameter tuning, and performance evaluation (Accuracy/Lift). |
| **Abdulelah Abdullah Nasser** | Clustering & Reporting Lead | K-means analysis, cluster interpretation, and final report/presentation coordination. |

## 📁 Project Structure
* `/Data`: Dataset specifications and cleaning logs.
* `/Reports`: Detailed documentation of all 4 Milestones.
* `/Presentation`: Final PowerPoint presentation summarizing findings and recommendations.

## 🔧 Tools Used
* **SAS Enterprise Miner** (Data Cleaning, Modeling, and Clustering)
* **Microsoft PowerPoint** (Professional Reporting)
