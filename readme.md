# 💼 Smart Salary Predictor

## 🚀 Why This Project?

In today’s competitive job market, fair and data-driven salary decisions are essential for both organizations and employees. This project leverages advanced machine learning to predict employee salaries based on real-world factors—empowering HR teams to make transparent, equitable, and strategic compensation choices.

I built this project to:

- **Demystify salary drivers** using interpretable AI.  
- **Support HR and business leaders** with actionable, data-backed insights.  
- **Showcase end-to-end ML engineering skills**—from data wrangling to model deployment.

---

## 📊 Project Overview

This repository contains a robust, production-ready pipeline for salary prediction, using a dataset of 1,000 employees with features such as:

- **Education**  
- **Experience**  
- **Location**  
- **Job Title**  
- **Age**  
- **Gender**

### The workflow includes:

- Data cleaning & EDA  
- Feature engineering & encoding  
- Model training (Linear Regression)  
- Performance evaluation  
- Insightful visualizations

---

## ✨ Key Achievements & Learning Outcomes

- **87%+ Predictive Power:** The model explains over 87% of salary variation on unseen data (R² = 0.87).  
- **No Overfitting:** Training and validation scores are closely matched, ensuring generalizability.  
- **Transparent Feature Impact:** Quantified the effect of each variable (e.g., education, experience, location) on salary.  
- **Industry-Standard Pipeline:** Modular, reproducible code using scikit-learn pipelines and best practices.  
- **Actionable Insights:** Delivered recommendations for HR and business stakeholders.

---

## 🛠️ How to Use

1. **Clone the repository**
2. **Install dependencies**

```bash
pip install -r requirements.txt
````

3. **Run the notebook**

* Open [`reg-1.ipynb`](reg-1.ipynb) in Jupyter or VS Code.
* Execute cells sequentially to reproduce results, visualizations, and insights.

> **Want to check or modify something?**
> All core logic and scripts are in the notebook. For custom analysis or automation, adapt the code cells as needed.

---

## 📈 Results Snapshot

* **R² Score:** 0.87 (Test Set)
* **RMSE:** ₦10,142
* **MAE:** ₦8,158
* **Key Drivers:** Education, Experience, Job Title, and Location
* **Minimal Bias:** Gender and Age have negligible impact, supporting fairness

---

## 🧠 Insights & Recommendations

* **Education & Experience:** Each higher degree and year of experience significantly boosts salary.
* **Location Matters:** Urban and suburban employees earn more—consider location-based adjustments.
* **Promotion Pathways:** Advancing job titles yields measurable pay increases.
* **Fairness:** Gender and age effects are minimal, but regular audits are recommended.

---

## 📚 Learning Highlights

* Built a full ML pipeline with real-world data
* Applied advanced feature encoding (ordinal, one-hot, binary)
* Automated model evaluation and visualization
* Communicated findings for non-technical stakeholders

---

## 🚀 Future Work & Deployment Plans

* **API Deployment:** Package the model as a RESTful API for integration with HR platforms.
* **Web Dashboard:** Build an interactive dashboard for real-time salary prediction and analytics.
* **Model Expansion:** Incorporate additional features (e.g., industry, company size) for even greater accuracy.
* **Bias Auditing:** Implement automated fairness checks and reporting.
* **Continuous Learning:** Enable the model to retrain as new data becomes available.

---

## 👤 Author

**Afolabi Olawale**
AI Engineer & Data Enthusiast

> *I’m passionate about building transparent, impactful AI solutions that bridge the gap between data and decision-making.
> If you have questions or want to collaborate, feel free to reach out!*

---

## 📂 Files

* [`reg-1.ipynb`](reg-1.ipynb): Main notebook with code, analysis, and results
* [`salary_prediction_data.csv`](salary_prediction_data.csv): Cleaned dataset
* `Salary Prediction . Regression.pdf` / `.pptx`: Project report and presentation

---

## ⭐️ Impressively Built With

* Python
* Pandas
* scikit-learn
* Matplotlib
* Seaborn

Built with clean, modular, and reproducible code—grounded in real-world business context and actionable insights.

---

> **Ready to make salary decisions smarter and fairer?**
> Dive into the notebook and see the power of AI in action!


