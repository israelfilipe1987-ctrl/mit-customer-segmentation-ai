# Leveraging Unsupervised Learning to Drive Business Growth: Strategic Customer Segmentation

## 📌 Project Overview
This repository contains the Capstone Project completed for the **MIT Professional Education - Applied AI & Data Science** program, where it received the maximum grade. 

The project addresses the inefficiency of "one-size-fits-all" mass marketing by applying Unsupervised Machine Learning techniques to segment a customer base of 2,240 consumers based on 29 demographic and behavioral features. The goal is to optimize Marketing ROI and Customer Lifetime Value (CLV) through hyper-personalization.

---

## 📊 Business Presentation
An executive-level Data Storytelling slide deck was prepared to translate statistical metrics into data-driven marketing strategies.
* 📂 **[View the Final Presentation Slides (PDF)](./presentation/05052026_CAPSTONE_APPLIED_AI_DATA_SCIENCE_FINAL_Israel_Filipe_Silva.pdf)**

---

## 🛠️ Data Science Pipeline & Architecture
The solution was engineered as an Unsupervised Machine Learning pipeline using Python:
1. **Data Preprocessing:** Handled missing values (Income median imputation), created behavioral features (`Total_Spending`, `Children`), and removed unrealistic demographic outliers.
2. **Dimensionality Reduction:** Applied **Principal Component Analysis (PCA)** to eliminate multicollinearity and noise, retaining over 70% of the total dataset variance.
3. **Cluster Optimization:** Tested multiple algorithms (K-Means, K-Medoids, Agglomerative Clustering, and GMM), evaluating them via the **Elbow Method (Inertia)** and **Silhouette Coefficient**.
4. **Final Model:** Chosen **K-Means (K=4)** for its high statistical stability and clear business interpretability.

---

## 👥 The 4 Customer Personas Discovered
Through K-Means clustering, the consumer base was mapped into 4 distinct strategic segments:

| Persona | Renda Média / Gasto | Características Principais | Estratégia Recomendada |
| :--- | :--- | :--- | :--- |
| **Premium VIPs** | High Income ($78k) / High Spend ($1.2k) | Heavy buyers of luxury items (Wine & Meat). Low deal sensitivity. | **Retention & Exclusivity:** Loyalty programs and early access. |
| **Middle-Class Mainstay** | Medium Income ($52k) / Frequent Purchases | Reliable, frequent buyers across categories. Balanced habits. | **Value & Bundling:** Cross-selling family packs to increase basket size. |
| **Budget Families** | Low-Med Income / Price-Sensitive | Large households (Avg. 4.2 members). High usage of deals/discounts. | **Re-engagement Triggers:** Target with personalized discount offers. |
| **Young Starters** | Low Current Spend / Avg. Age 28 | High digital engagement (Web visits), high long-term growth potential. | **Digital Engagement:** Mobile-first social media campaigns. |

---

## 🚀 Business Impact & Projections
* **Estimated ROI:** A projected **15-20% increase in campaign ROI** based on target-optimized communication.
* **Operational Costs:** Low technical overhead by integrating clusters directly into existing CRM systems.
* **Model Maintenance:** Recommended retraining every 6 months to adjust for economic changes and "Cluster Drift".

---

## 📂 Repository Structure
* `notebooks/`: Contains the Jupyter Notebook with the full Python code, EDA, and statistical modeling.
* `presentation/`: Contains the official PDF slide presentation submitted to MIT Professional Education.
