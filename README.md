#  UK Road Accident Severity Prediction & Risk Scoring

##  Overview

This project delivers an end-to-end machine learning solution using the **UK Road Safety (STATS19) dataset (2005–2016)** to predict accident severity and generate risk scores for high-risk conditions.

It enables organisations to move from **reactive accident analysis** to **proactive risk identification and safety planning**.

---

##  Key Features

###  Machine Learning Model
- Multi-class classification (Slight / Serious / Fatal)  
- Built using **Random Forest (Scikit-learn)**  
- Generates **accident severity predictions and risk scores**  
- Model accuracy: **83.8%**  

###  Power BI Dashboard
- Interactive accident analysis across time, location, and conditions  
- Risk segmentation and trend analysis  
- Multi-page dashboard for stakeholder insights  

###  Geospatial Analysis
- Accident density mapping by local authority  
- UK-wide accident heatmaps  
- Identification of high-risk regions  

###  Data Outputs
- Exported predictions (`accident_predictions.csv`)  
- Risk scoring for downstream BI integration  

---

##  Business Problem

Road accidents result in:
- Loss of life and serious injury  
- Increased public sector costs  
- Insurance risk exposure  
- Infrastructure and policy challenges  

This project addresses:

- What conditions lead to severe accidents?  
- Where are high-risk areas located?  
- How can accident severity be predicted in advance?  
- How can data improve road safety decisions?  

---

##  Dashboard Preview

### Executive Overview
<img width="1305" height="732" alt="Executive_Overview_v2" src="https://github.com/user-attachments/assets/eee5ee30-b1a2-46b3-95c4-4b4c3b25fabe" />


### Time & Conditions Analysis
<img width="1297" height="727" alt="Time_ _Environmental_Conditions_v2" src="https://github.com/user-attachments/assets/23488141-455a-4919-b083-c201c9583ee3" />


### Driver & Vehicle Risk
<img width="1301" height="735" alt="Driver_ _Vehicle_Risk_v2" src="https://github.com/user-attachments/assets/52117a3a-343b-4eab-962a-b4bbcc831c86" />


---

##  Geospatial Insights

- Accident density varies significantly across regions  
- Urban areas show higher concentration of incidents  
- Heatmaps highlight clusters of high-risk zones  

---

##  Machine Learning Approach

- Data cleaning and preprocessing  
- Feature engineering (time, weather, speed, conditions)  
- Multi-class classification model  
- Model evaluation using accuracy and confusion matrix  

 **Notebook:**  
https://colab.research.google.com/drive/1vqii9QUbvKtfqTeXTsXzLlxNLhW5O3m3?usp=sharing  

---

##  Model Performance

- Accuracy: **83.8%**  
- Key Drivers:
  - Speed limit  
  - Time of day  
  - Weather conditions  

### ROC Curve Comparison
![ROC Curves](https://github.com/user-attachments/assets/0303bb68-fe20-40c4-87f3-7c155fd333ae)


---


---

##  Key Insights

- Accident severity increases under **higher speed limits**  
- Night-time and low visibility conditions increase risk  
- Weather conditions (rain, fog) significantly impact severity  
- Certain vehicle types show higher severity distributions  
- Geographic clustering reveals high-risk areas  

---

##  Business Value

- Predicts high-risk accident scenarios before they occur  
- Enables **targeted safety interventions**  
- Supports:
  - Government agencies  
  - Police forces  
  - Insurance companies  
  - Transport planners  

 Drives **data-driven road safety improvements**

---

##  How to Run the Model

1. Open the notebook:
   https://colab.research.google.com/drive/1vqii9QUbvKtfqTeXTsXzLlxNLhW5O3m3?usp=sharing  

2. Run all cells  
   *(Kaggle dataset may require manual upload if API token fails)*  

3. Download output:

   
---

##  Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)  
- Machine Learning (Random Forest)  
- Power BI (Dashboards, DAX)  
- Google Colab  
- UK STATS19 Dataset  

---

##  Author

**Richard McInerney**  
Data Analytics | Power BI | Machine Learning  

---

##  Contact & Collaboration

Open to freelance projects, custom ML models, and Power BI dashboards.

 richardmcinerney@proton.me  
 https://linkedin.com/in/richardmcinerney-data  

---

