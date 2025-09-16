# 📊 IOE Aspirants Data Analysis

This project analyses **IOE exam results** of students based on **districts, provinces, and gender** using Python. It visualizes the data with **pie charts 🥧** and **bar plots 📊**, and provides simple insights.  

---

## 🔍 Project Overview

The project aims to:  

- 🏷 Merge multiple data sources to include province information  
- 🧹 Clean and prepare the data  
- 📈 Visualize insights using charts  
- 📝 Extract statistical insights like most repeated district and average rank  

---

## 🛠 Technologies Used

- **Python 🐍**  
- **Pandas** – for data manipulation  
- **NumPy** – for numerical operations  
- **Matplotlib** – for plotting pie charts 🥧  
- **Seaborn** – for bar charts 📊  
- **SciPy** – for statistics  

---

## 📁 Data Files

1. `ioeResult.xlsx` – Student data including **District, Gender, Rank**  
2. `district_province.xlsx` – Maps **District → Province**  

---

## 💻 Key Steps in Code

### 1️⃣ Import Libraries & Read Data
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sb
from scipy import stats

result = pd.read_excel("ioeResult.xlsx")
province = pd.read_excel("district_province.xlsx")
