# Los Angeles Crime Data Analysis  

![Los Angeles skyline](media/la_skyline.jpg)

## 📌 Project Overview  
Los Angeles, California 😎 — the City of Angels, known for Hollywood, palm trees, and sunshine.  
But like any major city, LA also faces challenges with crime.  

In this project, I worked with crime data provided by **DataCamp** (a modified version of the publicly available [Los Angeles Open Data](https://data.lacity.org/)) to help the **Los Angeles Police Department (LAPD)** identify crime patterns.  

The goal was to explore the dataset, uncover trends, and provide insights that could help allocate resources more effectively in combating crime across different neighborhoods.  

---

## 📂 Dataset  

The dataset used is **`crimes.csv`**, containing information about reported crimes in Los Angeles.  

### Columns Description  
| Column          | Description |
|-----------------|-------------|
| `DR_NO`         | Division of Records Number: Official file number with year, area ID, and digits. |
| `Date Rptd`     | Date reported (MM/DD/YYYY). |
| `DATE OCC`      | Date of occurrence (MM/DD/YYYY). |
| `TIME OCC`      | Time of occurrence in 24-hour military format. |
| `AREA NAME`     | Geographic area / patrol division (e.g., 77th Street Division in South LA). |
| `Crm Cd Desc`   | Type of crime committed. |
| `Vict Age`      | Age of the victim in years. |
| `Vict Sex`      | Sex of the victim: `F` (Female), `M` (Male), `X` (Unknown). |
| `Vict Descent`  | Victim’s descent (ethnic background). |
| `Weapon Desc`   | Description of weapon used (if applicable). |
| `Status Desc`   | Status of the crime (e.g., report completed, investigation ongoing). |
| `LOCATION`      | Street address of the reported crime. |

---

## 🔍 Objectives  
1. Clean and explore the dataset.  
2. Identify temporal crime patterns (by hour of day and night).  
3. Find the geographic area with the highest night-time crime activity.  
4. Analyze victim demographics such as age brackets.  

---

## 🛠️ Tools & Skills Used  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **Exploratory Data Analysis (EDA)**  
- **Data Cleaning & Transformation**  
- **Visualization of crime trends**  

---

## 🚀 Analysis & Outcomes  

### 🔸 Crime by Hour  
- Extracted the **hour of occurrence** from the `TIME OCC` column.  
- Visualized crime frequency by hour of day.  
- **Finding:** Crime peaks around **midday (12:00 PM)**.  

### 🔸 Night-Time Crime Hotspots  
- Focused on **night hours**: 10 PM – 3 AM.  
- Grouped by `AREA NAME` to find the area with the highest incidents.  
- **Finding:** The area with the largest volume of **night-time crime** is **Central**.  

### 🔸 Victim Age Distribution  
- Categorized victims into **age brackets**: 0–17, 18–25, 26–34, 35–44, 45–54, 55–64, 65+.  
- Counted the frequency of each group.  
- **Finding:** The **most common victim age group** is **26–34 years old**.  

---

## 📎 Acknowledgements  
- **DataCamp** for providing the dataset and guided project structure.  
- Original dataset: [Los Angeles Open Data](https://data.lacity.org/).  

---
