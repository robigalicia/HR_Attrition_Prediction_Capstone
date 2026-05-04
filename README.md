# Strategic Talent Retention: HR Attrition Prediction

## 📌 Project Overview
This data science capstone project deploys a machine learning pipeline to predict employee attrition. By optimizing for Recall, the model is designed to act as a proactive "Early Warning System," successfully identifying high-risk talent before they leave.

## 📂 Repository Structure
Based on the project workflow, the files are organized into the following directories:

* **`Data/`**: Contains the raw and processed HR datasets used for training and evaluation (e.g., `HR-Employee-Attrition.csv`).
* **`Notebook/`**: Contains the core Jupyter Notebook (`Vincent Robert Galicia_Capstone_Project_v2.ipynb`) detailing the complete data science lifecycle, including Exploratory Data Analysis (EDA), feature engineering, model tuning (Logistic Regression vs. Random Forest), and algorithmic fairness auditing.
* **`Presentation/`**: Contains the Jupyter Notebook (`Vincent Robert Galicia_Technical Presentation.ipynb`) formatted explicitly with cell metadata to be rendered as an interactive technical slide deck for peer review.

## 🚀 Key Results & Ethical AI
* **Primary Metric:** Optimized for Minority-Class Recall (62%) to minimize the financial impact of False Negatives (undetected leavers).
* **Bias Auditing:** A quantitative fairness audit was conducted on the protected attribute of Gender. The model achieves a Disparate Impact Ratio of 1.09, passing the industry-standard Four-Fifths rule and ensuring equitable risk flagging.
