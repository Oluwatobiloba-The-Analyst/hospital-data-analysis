# 🏥 Hospital Data Analysis – Power BI Project

## 📄 Project Overview

In the fast-paced world of healthcare, data is often abundant but underutilized. Hospitals gather vast amounts of information daily, yet critical insights often go unnoticed. Behind every hospital visit lies a complex interplay of medical decisions, clinical resources, patient care and outcomes, cost implications, and hospital management.  

With rising treatment costs and increasing readmission rates, hospitals face growing pressure to deliver high-quality care while maintaining financial sustainability.  

This project began with a simple question:  
**What can we learn from hospital data to improve patient care and reduce costs?**

Using a dataset of **984 patient records**, I built an interactive **Power BI dashboard** to explore relationships between **conditions, procedures, patient outcomes, readmissions, length of stay**, and **treatment costs**.  

This enables stakeholders to explore the questions that matter most:  
👉 *Where are we losing efficiency?*  
👉 *Which conditions drive our highest costs?*  
👉 *How can we deliver better outcomes at lower cost?*  

The goal is to help healthcare professionals identify operational inefficiencies and strengths, highlight cost drivers, and suggest actionable strategies for improving hospital performance, care delivery, and data-driven decision-making.

---

## 🎯 Objectives

- Analyze patient demographics such as gender distribution across patients and age distribution across conditions.  
- Explore the relationship between treatment outcomes, patient distributions, and healthcare costs.  
- Evaluate the impact of readmissions on total cost and length of stay.  
- Understand the cost implications of different conditions and procedures.  
- Identify the most common and cost-intensive medical conditions and procedures.  
- Explore condition and procedure distributions across patients.  
- Evaluate patient distribution across satisfaction levels and identify which level has the highest number of patients.  
- Develop actionable insights through interactive dashboards.  
- Provide data-driven recommendations and strategies to optimize hospital operations, improve healthcare delivery, and reduce avoidable costs.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – for interactive dashboard creation, analysis, and data storytelling  
- **DAX (Data Analysis Expressions)** – for building custom measures and KPIs  
- **Power Query Editor** – for data transformation and cleaning  
- **Microsoft Excel** – for data preparation and source file  
- **Data Storytelling Techniques** – for translating analysis into clear, meaningful insights

---

## 📁 Dataset

- **Source:** [Hospital Patients Records Dataset – Kaggle.com](https://www.kaggle.com/datasets/blueblushed/hospital-dataset-for-practice/data)  
- **Size:** 985 rows × 10 columns  

The dataset used consists of hospital records for **984 patients**, including the following key attributes:

- Patient ID  
- Age  
- Gender  
- Condition  
- Procedure  
- Cost  
- Length of Stay  
- Readmission (Yes/No)  
- Outcome (Recovered or Stable)  
- Satisfaction  

---

## 📊 Exploratory Data Analysis (EDA)

Before building the dashboard, I explored the dataset to uncover base-level insights:

- **Demographics:** Distribution by age and gender  
- **Length of Stay:** Ranging from 1 to 76 days (average 38 days)  
- **Readmissions:** Occurred in 26.83% of cases  
- **Outcomes:** 60.06% of patients recovered; 39.94% remained stable  
- **Cost Trends:** Total hospital billing exceeded $8 million  

As I explored the data, patterns began to emerge that raised important questions and hypotheses:  
- Do readmissions drive more cost?  
- Which medical conditions are draining the hospital's budget?  
- Which procedures are most expensive?  
- Is age a strong factor in treatment outcomes?  
- Where could the hospital improve?

Using **bar charts, column charts, pie charts, doughnut chart, line and area charts, KPIs, and slicers** in Power BI, I broke the data into manageable, interactive segments—laying the foundation for the dashboard's insights.

---

## 🔍 Key Analysis and Observations

- **Total Patients Analyzed:** 984  
- **Average Age:** 54 years  
- **Total Treatment Cost:** $8.23 million  
- **Conditions & Procedures:** 15 each  
- **Average Length of Stay:** 38 days (range: 1–76 days)  
- **Gender Distribution:** 524 females, 460 males  
- **Outcomes:** 591 recovered (60.06%), 393 stable (39.94%)  
- **Readmissions:** 264 (26.83%) readmitted, 720 (73.17%) not readmitted  
- **Cost Breakdown:**  
  - Readmitted patients → $3.60M  
  - Non-readmitted patients → $4.63M  
  - Stable patients → $2.37M (28.78%)  
  - Recovered patients → $5.86M (71.22%)  
- **Average Length of Stay:**  
  - Readmitted → 39 days  
  - Non-readmitted → 37 days  
- **Top 3 Conditions by Cost:** Cancer, Prostate Cancer, Heart Attack  
- **Top 3 Costly Procedures:** Surgery & Chemotherapy, Radiation Therapy, Cardiac Catheterization  
- **Most Common Conditions:** Fractured Leg, Heart Attack  
- **Most Common Procedures:** Cardiac Catheterization, Cast and Physical Therapy  
- **Top Satisfaction Level:** 4 (458 patients, 46.54%)

---

## 🔎 Key Insights
From visualizing and analyzing the data, several crucial insights emerged:

1. 💸 **Recovery Requires More Resources** 
Stable patients made up 39.94% of the total patient and accounted for 28.78% of the total cost while Recovered patients which was about 60.06% of the total patients accounted for **71.22% of total costs**, suggesting that successful outcomes often required more intensive care, treatment and resources. This also indicate a possible link between cost and care intensity.

2. 🔄 **Readmissions Cost More**  
Readmitted patients which was only 264 patients (26.83%) contributed to nearly **44% (3.60 million) of costs**, with a slightly longer average length of stay of 39 vs. 37 days for non readmitted patients. These cases reflect operational inefficiencies and potential issues with discharge planning or post-care/treatment monitoring and follow-up. It also shows higher resource usage and strain on hospital budgets and capacity, and this suggest a need for better post-discharge care.  

3. 👵 **Age Patterns Reveal Risk Profiles**  
- Older patients (70+) were primarily associated with **high-cost conditions** like **Heart Attack, and Stroke**, which were linked to longer stays and more expensive treatments. Indicating the need for senior-specific care and prevention strategies. 
- Conditions like **allergic reactions** and **fractured arm and** were concentrated among younger patients with shorter stays and lower costs. 

4. 💉 **Chronic and Critical Conditions Dominate Costs**  
Conditions like **Cancer**, **Prostate Cancer**, and **Heart Attack** were the top 3 cost drivers,  **Cancer** led the chart with $1.65M, followed by **Prostate Cancer (1.3M)** and **Heart Attack* (1.2M)*. These three conditions made up the majority of hospital spending despite similar patient volumes to other conditions.

5. 🩺 **High-Cost Procedures Demand Scrutiny**  
Among procedures Surgery & Chemotherapy (1.65M) and Radiation Theraphy (1.30M) emerged as the top cost centers, and the most resource-intensive procedures, drawing attention to their frequency, efficiency and clinical necessity. These procedures consumed large portions of the hospital’s budget. In contrast, treatments like **Epinephrine Injection (7k), X-Ray and Splint (33k), antibiotics and Rest (52k) had minimal impact on the overall hospital’s budget.


6. 😊 **Patient Satisfaction Trends**  
Majority Rated Satisfaction as 4 (458 patients (46.54%)), this suggests that nearly half of the patients had a very positive experience, though not perfect. 132 patients (13.41%) rated experience as a perfect 5, this suggest that most patients are satisfied or very satisfied with their hospital experience.

261 patients (26.52%) gave a rating of 3 indicating a neutral or average experience, this group is significant and may be open to being converted into higher satisfaction with minimal effort.
133 patients (13.52%) rated experience 2, representing an important area for improvement while No patients rated Satisfaction as 1. 

---

## 💡 Recommendations

Based on the insights gained, I proposed the following solutions:

1. **Strengthen Discharge and Follow-Up Care**  
Implement better structured discharge protocols, home-care instructions, patient education, remote follow-up and post-discharge monitoring to reduce preventable readmissions and related costs.

2. **Audit High-Cost Procedures**  
   Regularly evaluate the necessity and effectiveness of high-cost treatments like chemotherapy and advanced imaging to ensure optimal resource use, cost-benefit balance, and consider alternative treatments where feasible to reduce unnecessary utilization.

3. **Prioritize Preventive Care for the Elderly**  
   Introduce screening and wellness programs targeting older adults to reduce critical, late-stage conditions like heart disease and stroke whose treatment are very expensive. This is because early intervention may reduce long term hospitalization needs.

4. **Embed Data Dashboards into Hospital Operations**  
   Use Power BI dashboards for real-time monitoring of key KPIs such as cost per condition, length of stay, readmission trends, and outcomes performance across department to drive better decisions.

5. **Replicate What Works** 
 Study the experience of patients who rated 5, what departments, staff or services did they interact with? use this to standardize high quality practices. Patients who rated 1 or 2 need attention target interventions such as service recovery, staff training, or clearer communication. Those who rated 3 should also be attended to with more services and improvement.

---

## 🔄 Future Work

- Incorporate **time-based trends** (e.g., monthly or seasonal spikes).  
- Add **department or ward-level breakdowns** for more granular performance tracking.  
- Develop **predictive models** for readmission risk.  
- Integrate additional datasets (e.g., lab results, insurance claims) for richer context.  
- Apply **machine learning** for predictive analytics.

---

## 📬 Contact

**Oluwatobiloba Taiwo**  
📧 [taiwooluwatobiloba2904@gmail.com](mailto:taiwooluwatobiloba2904@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/oluwatobiloba-taiwo-dvm-b43b51366?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app)  
🌐 [Portfolio Website](https://oluwatobilobataiwo.netlify.app)

---

> 📝 *This project was completed for professional development and portfolio presentation. 
