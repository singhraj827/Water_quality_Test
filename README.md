# 🌊 Water Quality Test: Potability Prediction

## 📝 Problem Statement

Access to safe drinking water is essential for health, a basic human right, and a critical component of effective health protection policies. This project focuses on predicting whether water is **potable (safe for drinking)** based on various water quality metrics.

---

## 📄 Dataset Description

The dataset contains water quality metrics for **3,276 water bodies**. It includes the following parameters:

1. **pH Value**: Indicator of acidic or alkaline conditions in water (range: 6.5–8.5 recommended by WHO).  
2. **Hardness**: Caused by calcium and magnesium salts; measures water's ability to precipitate soap.  
3. **Solids (TDS)**: Total dissolved solids in water, affecting taste and appearance (desirable limit: 500 mg/L).  
4. **Chloramines**: Disinfectants formed by adding ammonia to chlorine (safe level: ≤4 mg/L).  
5. **Sulfate**: Naturally occurring substances, higher levels in some regions.  
6. **Conductivity**: Ionic concentration determining the ability to transmit electrical current (should not exceed 400 μS/cm).  
7. **Organic Carbon**: Total organic carbon present (drinking water limit: ≤2 mg/L).  
8. **Trihalomethanes**: Chemicals formed during water chlorination (safe level: ≤80 μg/L).  
9. **Turbidity**: Indicates the quantity of suspended solids (WHO recommended value: ≤5 NTU).  
10. **Potability**: Binary indicator where 1 = Potable (safe) and 0 = Not Potable (unsafe).

---

## 🎯 Objective

The primary goal is to **predict if water is safe for human consumption** based on the given quality metrics.

---

## 📂 Dataset Information

- **File**: `water_potability.csv`
- **Classes**:  
  - Potable (1) - Safe for drinking.  
  - Not Potable (0) - Unsafe for drinking.  
- **Class Distribution**: Approximately 60:40 ratio (balanced dataset).

---

## 🛠️ Installation and Dependencies

### Prerequisites
Ensure Python 3.8+ is installed.

### Required Libraries
Install the dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn
```

### Example Setup
The following Python libraries are used in the notebook:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/username/water-quality-prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd water-quality-prediction
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Water_quality_Test.ipynb
   ```

4. Execute the cells step-by-step to understand and reproduce the results.

---

## 📊 Exploratory Data Analysis (EDA)

The notebook includes:
- **Visualization of data distributions.**
- **Identification of missing values.**
- **Insights into water quality metrics.**

---

## 📈 Modeling

The project aims to train machine learning models to predict water potability:
- Preprocessing and feature engineering for optimal performance.
- Evaluation using metrics such as **accuracy**, **precision**, and **recall**.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📧 Contact

For queries or suggestions, please reach out to:  
**Email**: er.abhisingh827@gmail.com
**GitHub**: [Abhishek Kumar](https://github.com/singhraj827)

---
