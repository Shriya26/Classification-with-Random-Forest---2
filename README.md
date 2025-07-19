# Classification-with-Random-Forest---2
Random Forest Advance Project-10

Fraud Detection
Use Case
A financial institution aims to identify individuals with **taxable income ≤ 30,000** as “Risky” for fraud or default risk. The goal is to build a classification model to flag such individuals based on their demographics.

Objective
- Categorize individuals as **"Risky"** or **"Good"**
- Use features like `Undergrad`, `Marital.Status`, `Work.Experience`, `City.Population`, `Urban`
- Aid decision-making for credit approvals or fraud detection

Tools Used
- **Python**
- **Pandas, Seaborn, Matplotlib** for EDA and visualization
- **Scikit-learn** for modeling (Random Forest)
- **Jupyter Notebook** for development

 Key Insights
- Majority of data falls under the “Good” category → Imbalanced data
- Risky individuals are more concentrated in specific education and urban profiles
- `City.Population` and `Work.Experience` vary noticeably between “Risky” and “Good”
