# 🏥 Mortality of ICU Patients - PhysioNet

This project analyzes **Intensive Care Unit (ICU) patient data** from the PhysioNet dataset:  
**Predict Mortality of ICU Patients**. The goal is to preprocess, analyze, and visualize patient records to extract medical insights.

---

## 📂 Repository Structure

icu-project/

│
├── icu_data/ # Sample of main dataset & patient records

│ └── .gitkeep

├── icu_python/ # Python scripts & Jupyter notebooks

│ └── .gitkeep

├── icu_powerbi/ # Power BI dashboard files (.pbix)

│ └── .gitkeep

├── icu_images/ # Exported plots & dashboard screenshots

│ └── .gitkeep

└── README.md # Project documentation




⚠️ Note: Due to the dataset’s large size, only a **sample** is uploaded here.  
The full dataset is available on [Mortality of ICU Patients - PhysioNet](https://www.kaggle.com/datasets/msafi04/predict-mortality-of-icu-patients-physionet)).

---

## 📊 Dataset

- **Main file**:
- 
  `RecordID`, `SAPS-I`, `SOFA`, `Length_of_stay`, `Survival`, `In-hospital_death`
  
- **~4000 patient files** (`.txt`), each containing time-series data per patient.  

Data was split into:  

- **Static Information**: Age, Gender, Height, ICUType, Weight
- 
- **Time-Series Information**: Patient vitals & lab results  

---

## 🛠️ Python Libraries Used

- **pandas** → data cleaning & preprocessing
 
- **numpy** → numerical operations
  
- **os, glob** → reading & combining patient files
  
- **seaborn** → statistical visualization
  
- **matplotlib** → plotting charts
  
- **boxplot** → used to detect and illustrate outliers  

---

## 🔍 Project Workflow


### 1. Data Understanding

- Reviewed medical terms and normal ranges of indicators.
- 
- Performed **EDA** to explore relationships.  


### 2. Data Cleaning

- Removed missing values.
- 
- Handled inconsistent and outlier data (illustrated with **Boxplots**).
- 
- Combined patient static data with the main dataset.  


### 3. Visualization with Power BI

Created an **interactive dashboard** to show:  


#### 🧑‍⚕️ Demographics & ICU Insights

- Number of patients.
- 
- Male vs. Female distribution.
- 
- Mortality vs. Survival rates.
- 
- ICU types and severity of patients in each ICU.  


#### 📊 Medical Relationships

- **SAPS vs. SOFA** relationship.
-   
- **Age vs. SAPS** correlation.
- 
- Age groups with higher admission and severity.  



#### 💉 Patient Vital Signs

- Oxygen saturation in blood (SaO2).
- 
- Inhaled oxygen level (FiO2).
- 
- Relation between SaO2 & FiO2.
-   
- Whether the patient is on mechanical ventilation.
-   
- Respiratory rate (breaths per minute).
- 
- Glasgow Coma Scale (**GCS**) – awareness level.  

#### 🩸 Blood Parameters
- Cholesterol level trends over time.  
- Glucose level trends over time.  
- Platelet counts.  
- Red Blood Cells (RBCs).  
- White Blood Cells (WBCs).  
- Relationship between **WBCs and Platelets** (to detect inflammations).  

---

## 💡 Key Insights

- Clear patient demographics (gender, age, survival).  
- **Boxplots** highlighted and removed abnormal outliers.  
- **SAPS & SOFA** strongly correlated with severity.  
- Certain **age groups** showed higher ICU admissions.  
- Oxygen levels (SaO2 vs. FiO2) revealed respiratory support needs.  
- **WBC vs. Platelets** analysis provided signals of potential infections.  
- GCS helped monitor patient consciousness.  

---

## 🚀 Scope

This project demonstrates:  
- Data preprocessing, cleaning, and handling outliers.  
- Exploratory Data Analysis (EDA).  
- Building interactive healthcare dashboards.  

🔮 Future work:  
- Predictive modeling for ICU mortality/survival.  
- Machine Learning models for severity classification.  
- Real-time dashboards for ICU patient monitoring.  

---

## ⚙️ Tools & Technologies

- **Python**: pandas, numpy, seaborn, matplotlib, os, glob  
- **Power BI**: dashboards & reporting  
- **Excel**: initial exploration  
- **GitHub**: version control & sharing  

---

## 📸 Project Screenshots

![Dashboard Overview](https://github.com/ahmed75p/Mortality-of-ICU-Patients-PhysioNet/blob/main/icu_images/ICU1.png))  
![Patient Vital Signs](https://github.com/ahmed75p/Mortality-of-ICU-Patients-PhysioNet/blob/main/icu_images/ICU2.png))  
![Respiratory & Blood](https://github.com/ahmed75p/Mortality-of-ICU-Patients-PhysioNet/blob/main/icu_images/ICU3.png)  

---

**Ahmed Mostafa**  
- 📧 Email: ahmedmostafa75p@gmail.com  
- 🔗 LinkedIn: [My LinkedIn Profile](www.linkedin.com/in/ahmed-mostafa-841412250)  

**Ahmed Mostafa**  
- 📧 Email: ahmedmostafa75p@gmail.com  
- 🔗 LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/your-profile) 
