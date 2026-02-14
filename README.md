# ROAD TRAFFIC ACCIDENT ANALYSIS PROJECT

## 📊 Project Overview

This project analyzes road traffic accident data to identify high-risk periods, locations, and patterns that can inform data-driven safety policies and interventions.

**Dataset:** 12,316 accident records  
**Analysis Period:** Multiple years of accident data  
**Objective:** Extract actionable insights to reduce traffic accidents and improve road safety

---

## 📁 Project Structure

```
RTA_Analysis_Project/
├── RTA_Dataset_with_DD.xlsx           # Original dataset
├── RTA_Analysis.ipynb                 # Complete analysis notebook
├── RTA_Analysis_Report.docx           # Comprehensive findings report
├── README.md                          # This file
└── charts/                       # Visualization images
```

---

## 🎯 Project Objectives

1. Identify high-risk accident periods (time of day, day of week)
2. Determine accident-prone locations and road conditions
3. Analyze driver demographics and behavioral patterns
4. Examine environmental factors affecting accident severity
5. Provide data-driven recommendations for road safety policies

---

## 📊 Dataset Information

**Total Records:** 12,316 accidents  
**Original Variables:** 32  
**Final Variables:** 27 (after cleaning)

**Key Data Fields:**
- Temporal: Time, Day of week
- Demographics: Driver age, gender, experience, education
- Vehicle: Type, ownership, movement
- Environment: Weather, lighting, road surface
- Location: Area type, road alignment, junction type
- Outcome: Accident severity, casualties, collision type

---

## 🔧 Technologies Used

- **Python 3.10+**
- **pandas** - Data manipulation
- **numpy** - Numerical operations
- **matplotlib** - Visualization
- **seaborn** - Statistical graphics
- **scipy** - Statistical analysis
- **Jupyter Notebook** - Interactive analysis

---

## 🚀 How to Run

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn scipy openpyxl jupyter
```

### Steps

1. **Clone/Download** the project files
2. **Ensure dataset** `RTA_Dataset_with_DD.xlsx` is in the same folder
3. **Open Jupyter Notebook:**
   ```bash
   jupyter notebook RTA_Analysis.ipynb
   ```
4. **Run all cells:** Cell → Run All
5. **View results** and visualizations inline

---

## 📈 Analysis Sections

### 1. Data Cleaning & Preprocessing
- Missing value analysis and treatment
- Removal of 5 redundant/incomplete columns
- Smart imputation using mode and conditional logic
- Data standardization

### 2. Exploratory Data Analysis
- Accident frequency by time and day
- Driver demographic patterns
- Environmental factor analysis
- Severity distribution and trends

### 3. High-Risk Identification
- Peak accident hours and days
- High-risk driver profiles
- Dangerous road and weather conditions
- Accident-prone locations

### 4. Correlation Analysis
- Driver age vs severity
- Experience vs accident outcomes
- Weather conditions vs severity
- Road surface impact on accidents

### 5. Key Insights & Recommendations
- Data-driven safety policy suggestions
- Targeted intervention strategies
- Infrastructure improvement priorities

---

## 🔍 Key Findings

### High-Risk Periods
- **Peak Hours:** Evening rush hours show highest accident frequency
- **Critical Days:** Weekdays have more accidents than weekends
- **Dangerous Times:** Poor visibility hours (dawn/dusk) increase severity

### High-Risk Demographics
- **Young Drivers (18-30):** Higher accident involvement
- **Inexperienced Drivers (<2 years):** Elevated risk levels
- **Male Drivers:** 93% of accidents (demographic imbalance)

### Environmental Factors
- **Weather:** Normal conditions have most accidents (more exposure)
- **Road Surface:** Dry roads show higher frequency (more traffic)
- **Lighting:** Daylight conditions dominate but night accidents more severe

### Location Patterns
- **Office Areas:** High accident concentration during work hours
- **Residential Areas:** Evening accident peaks
- **Junction Types:** Y-shape junctions most accident-prone

---

## 💡 Recommendations

### 1. Temporal Interventions
- Increase traffic enforcement during peak hours
- Deploy mobile traffic units during rush periods
- Implement dynamic speed limits based on time

### 2. Demographic Targeting
- Mandatory advanced training for new drivers
- Young driver awareness campaigns
- Experience-based licensing restrictions

### 3. Infrastructure Improvements
- Enhanced lighting at accident-prone junctions
- Road surface maintenance priority zones
- Junction redesign for high-risk Y-shapes

### 4. Policy Enhancements
- Data-driven enforcement scheduling
- Risk-based insurance premium structures
- Targeted safety education programs

---

## 📊 Visualizations Generated

The analysis produces 20+ visualizations including:

- Accident distribution by time and day
- Driver demographic breakdowns
- Environmental factor impacts
- Severity distribution charts
- Correlation heatmaps
- Comparative bar charts and pie charts

---

## 📝 Report Deliverables

1. **Jupyter Notebook** - Complete code and analysis
2. **Cleaned Dataset** - Processed data ready for further analysis
3. **Comprehensive Report** - Professional DOCX with findings and recommendations
4. **Visualizations** - All charts saved as high-resolution images

---

## 🎓 Learning Outcomes

This project demonstrates proficiency in:

- Data cleaning and preprocessing techniques
- Exploratory data analysis (EDA)
- Statistical analysis and hypothesis testing
- Data visualization best practices
- Translating data insights into actionable recommendations
- Professional reporting and communication

---

## 📄 Data Cleaning Summary

**Columns Removed (5):**
- Defect_of_vehicle (36% missing, 98.6% "No defect")
- Service_year_of_vehicle (32% missing, poor quality)
- Fitness_of_casuality (21% missing, 99.2% "Normal")
- Pedestrian_movement (redundant with Casualty_class)
- Casualty_severity (redundant with Accident_severity)

**Imputation Strategy:**
- Mode imputation for dominant categorical values
- Conditional imputation using related fields
- Age-based driving experience inference
- Time-based area occurrence prediction

**Result:** 100% data completeness with 27 quality variables

---

## 🔄 Future Enhancements

- Machine learning models for accident prediction
- Geographic mapping of accident hotspots
- Time series forecasting of accident trends
- Real-time accident risk scoring system
- Interactive dashboard for stakeholders

<!-- ---

## 👤 Author

**Project Type:** Road Traffic Accident Analysis  
**Purpose:** Data-driven road safety improvement  
**Tools:** Python, Pandas, Matplotlib, Seaborn  
**Date:** February 2026

---

## 📞 Contact

For questions or feedback about this analysis:
- Review the comprehensive report (RTA_Analysis_Report.docx)
- Examine the Jupyter notebook for detailed methodology
- Contact project maintainer for clarifications -->

---

## ⚖️ License & Data Usage

This analysis uses road traffic accident data for research and policy development purposes. All findings and recommendations are based on statistical analysis and should be validated with domain experts before implementation.

<!-- 
## ✅ Project Status

**Status:** ✅ Completed  
**Data Quality:** 100% Complete  
**Analysis Coverage:** Comprehensive  
**Recommendations:** Actionable  
**Documentation:** Professional -->

<!-- ---

**Last Updated:** February 2026  
**Version:** 1.0  
**Analysis Ready:** Yes -->
