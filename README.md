## 📌 Introduction

### 🎯 Purpose  
This project analyzes local flight services to uncover patterns in revenue generation, flight trends, and service effectiveness across multiple years.

### 🧭 Objective of the Project  
The goal is to evaluate how different flight-related factors such as destinations, flight types, time, and agencies impact revenue performance. The analysis focuses on identifying top-performing destinations, flight agencies, and customer behaviors to support data-driven decisions.

### ❓ Problem Being Addressed  
Local airlines need to understand what drives their revenue. This analysis aims to answer:
- Which destination yields the most revenue?
- Which agency offers the most valuable services?
- How do time and distance relate to revenue?
- What year had the best performance and why?

### 🧰 Key Datasets and Methodologies  
- **Dataset**: Internal flight transaction records (2020–2023)  
- **Tool Used**: Microsoft Excel  
- **Methods**:
  - Pivot Tables
  - Slicers & Filters
  - Summary Statistics
  - Charts & Graphs

---

## 📖 Story of Data

### 📌 Purpose  
To provide a detailed overview of the dataset and its journey through analysis.

### 🗃️ Data Source  
Kaggle.com.

### 📥 Data Collection Process  
Compiled manually and semi-automatically from booking systems and flight agency logs.

### 📐 Data Structure  
- **Rows**: Represent individual flight services  
- **Columns**: Include:
  - `Flight From`, `Flight To`, `Flight Type`, `Agency`, `User Code`, `Travel Code`
  - `Date`, `Time`, `Distance`, `Price`

### ⭐ Important Features  
- **Flight To**: Indicates destination performance  
- **Agency**: Evaluates service provider efficiency  
- **Flight Type**: Shows customer preference  
- **Price & Distance**: Revenue metrics  
- **User Code**: Enables travel behavior tracking

### ⚠️ Data Limitations  
- Missing values  `None`  
- Seasonal bias (e.g., holiday peaks)  
- No demographic data

---

## ⚙️ Data Splitting and Preprocessing

### 🧼 Data Cleaning  
- Removed duplicates  
- Standardized spelling (e.g., "Florianopolis")  
- Fixed date/time formats

### 🔁 Data Transformations  
- Extracted `Year` from `Date`  
- Created `Distance/Price` ratio  
- Normalized agency performance

### ✂️ Data Splitting  
- **Independent Variables**:
  - `Flight From`, `Flight To`, `Flight Type`, `User Code`, `Agency`, `Travel Code`  
- **Dependent Variables**:
  - `Date`, `Time`, `Distance`, `Price`

### 🏭 Industry Context  
**Aviation (Local Air Travel Services)**

### 👥 Stakeholders  
- Chief Executives  
- Operations and Planning Teams

### 💼 Value to the Industry  
Helps optimize pricing, route planning, and agency partnerships for revenue growth.

---

## 📊 Pre-Analysis

### 🔍 Key Trends  
- Florianopolis is the most traveled-to city  
- First Class is the most chosen flight type  
- Flight time of 2–2.5 hours is common

### 🔗 Potential Correlations  
- Higher distance ≈ Higher price  
- Certain agencies dominate specific regions or years

### 💡 Initial Insights  
- User 925 traveled the longest distance  
- 2020 had an unexpectedly high number of flights

---

## 🧪 In-Analysis

### 🧭 Unconfirmed Insights  
- Rainbow Agency led in number of services — revenue review needed  
- 2020 performance spike may relate to internal strategy

### 📌 Recommendations  
- Promote Florianopolis routes with monthly discounts  
- Encourage Rainbow Agency to offer promos and bundles  
- Analyze 2020 operations to replicate success

### 🛠️ Excel Techniques Used  
- Pivot Tables  
- VLOOKUP  
- Conditional Formatting  
- Grouping and Slicers

---

## 📌 Post-Analysis and Insights

### 🔑 Key Findings  
- **Top Destination**: Florianopolis  
- **Top Agency**: Rainbow Agency  
- **Preferred Class**: First Class  
- **Best Year**: 2020  
- **Top User**: 925

### 🔄 Comparison with Initial Assumptions  
Most assumptions were validated; 2020’s spike was unexpected.


---

## ✅ Recommendations and Observations

### 🔁 Actionable Insights  
- Promote top destinations (e.g., Florianopolis)  
- Create loyalty rewards for frequent flyers  
- Feature flight times that optimize distance and cost

### ⚙️ Business Optimization  
- Introduce dynamic pricing  
- Prioritize agencies with high conversion and feedback

### 🧠 Unexpected Results  
- User 925’s travel behavior is significantly different  
- Distance vs. price ratio inconsistent across agencies

---

## 🧾 Conclusion

### 📘 Key Learnings  
- Destination, agency, and time are strong revenue indicators  
- Focused campaigns can improve route efficiency

### ⚠️ Limitations  
- Missing demographic info  
- Some inconsistencies in time data

### 🔍 Future Research  
- Add user profiles for deeper segmentation  
- Include marketing data for attribution analysis

---

## 📚 References & Appendices

### 🔗 References  
- Kaggle.com 
- Microsoft Excel
![Updated DashBoard 5](https://github.com/user-attachments/assets/fc9d06d9-33a9-47e6-930f-16cde607e672)
