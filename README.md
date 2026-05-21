<h1 align="center">Hi, I'm Jinrui (Jerry) Zhang 👋</h1>

<p align="center">
  <b>Data Analyst &nbsp;·&nbsp; Business Intelligence &nbsp;·&nbsp; Machine Learning</b><br/>
  MS Business Analytics @ UC Irvine &nbsp;|&nbsp; Turning data into decisions
</p>

<p align="center">
  <a href="https://jerryzhang966.github.io" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-jerryzhang966.github.io-blue?style=flat-square&logo=github" alt="Portfolio">
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/jinrui-zhang-jerry/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-Jinrui%20Zhang-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn">
  </a>
  &nbsp;
  <a href="mailto:jerryzhang966@gmail.com">
    <img src="https://img.shields.io/badge/Email-jerryzhang966%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

## About Me

I'm a graduate student in Business Analytics at UC Irvine, passionate about extracting actionable insights from complex data. My work sits at the intersection of machine learning, statistical modeling, and business strategy.

- 🔍 Focused on **classification**, **predictive modeling**, and **BI dashboards**
- 🧠 Experienced with **imbalanced data**, **feature engineering**, and **model selection**
- 📊 Comfortable with Python, SQL, and visualization tools

---

## 🛠 Tech Stack

**Languages & Data**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)

**ML & Analytics**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Visualization & BI**

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)

---

## 📂 Featured Projects

### 🎵 High Note Freemium Conversion Analysis
> *UCI BANA — Customer & Social Analytics*

Analyzed 43,827 users of a music streaming platform to identify what drives freemium-to-premium conversion — combining descriptive analysis, causal inference, and predictive modeling.

| | Detail |
|---|---|
| **Methods** | Descriptive Stats · PSM · Logistic Regression · Forward Subset |
| **Key finding** | Having ≥1 paying friend causally increases conversion by ~8 pp (ATE = 0.0799, p ≈ 8×10⁻⁶⁰) |
| **Top predictors** | Loved tracks, songs listened, subscriber friend count, age |
| **Dataset** | 43,827 users, 15+ behavioral & social variables |

**Key finding:** Peer influence is causal, not just correlated — PSM confirms an 8-point lift after controlling for engagement confounders. Engagement behaviors (loving tracks, making playlists) outpredict all demographic variables combined.

📎 [Full case study on my portfolio →](https://jerryzhang966.github.io/uci-projects-portfolio/Customer-Social/high-note-freemium/)

---

### ✈️ Sun Country Airlines Customer Segmentation
> *UCI BANA 200 — Foundation of Business Analytics*

Applied K-Means clustering to 1.86M trip records to segment Sun Country's customer base into five actionable groups — enabling targeted marketing and loyalty program strategy.

| | Detail |
|---|---|
| **Method** | K-Means (k=5, scikit-learn) |
| **Data** | 1.52M unique customers, 90 variables, 2013–2014 |
| **Segments** | Family Vacationers, Budget Professionals, Mature Travelers, Group Travelers, Solo Budget |
| **Key output** | Segment-level marketing playbook + Ufly Rewards targeting |

**Key finding:** A clear elbow at k=5 revealed distinct traveler archetypes — from family vacationers booking tropical round-trips to young professional commuters on the BOS↔DCA corridor — each requiring a different marketing approach.

📎 [Full case study on my portfolio →](https://jerryzhang966.github.io/uci-projects-portfolio/BANA-200/sun-country-segmentation/)

---

### 📱 Smartphone Predictive Pricing Analysis
> *UCI BANA — Data & Programming*

Built a multi-stage regression pipeline to identify which smartphone specs actually drive price — and which are just marketing noise.

| | Detail |
|---|---|
| **Models** | OLS → Lasso → Log-Linear → Random Forest |
| **Best R²** | 0.847 (Log-Linear), 0.823 (Random Forest) |
| **Key techniques** | LassoCV feature selection, log transformation, residual analysis |
| **Dataset** | Kaggle Real World Smartphones (980 entries, 22 features) |

**Key finding:** iOS devices command a ~79% price premium over equivalent Android hardware even after controlling for all specs. Meanwhile, features like fast charging and SD card slots show weak or negative price relationships — performance is what consumers actually pay for.

📎 [Full case study on my portfolio →](https://jerryzhang966.github.io/uci-projects-portfolio/Data-Prog/smartphone-pricing/)

---

### 🏦 Predicting Bank Marketing Campaign Subscriptions
> *UCI BANA 273 · Machine Learning*

A Portuguese bank ran telemarketing campaigns with only **~11% subscription rate**. I built and compared classification models to predict which customers are worth calling — before picking up the phone.

| | Detail |
|---|---|
| **Models** | Decision Tree vs. Logistic Regression |
| **Key challenges** | Severe class imbalance (89:11), data leakage |
| **Techniques** | SMOTE, GridSearchCV, cross-validation |
| **Dataset** | UCI Bank Marketing (41,188 records, 20 features) |

**Key finding:** After removing the leaky `duration` feature and applying SMOTE, Logistic Regression significantly outperformed Decision Tree on recall for the minority class — the metric that matters most for campaign targeting.

📎 [Full case study on my portfolio →](https://jerryzhang966.github.io/uci-projects-portfolio/ML/bank-marketing-ml/)

---

## 📫 Get in Touch

- **Portfolio:** [jerryzhang966.github.io](https://jerryzhang966.github.io)
- **LinkedIn:** [linkedin.com/in/jinrui-zhang-jerry](https://www.linkedin.com/in/jinrui-zhang-jerry/)
- **Email:** jerryzhang966@gmail.com
