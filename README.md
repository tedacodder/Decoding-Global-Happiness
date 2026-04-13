# 🌍 Global Happiness: A Multi-Dimensional Analysis of Well-Being

## 🎯 Project Overview

**Does money buy happiness, or is it merely the foundation for it?**

This project conducts a comprehensive analysis of over 5 years of data from the **World Happiness Report (2015–2019)** to uncover the true determinants of global life satisfaction. By integrating socio-economic and institutional indicators, the study provides actionable insights that can assist policymakers and researchers in enhancing national **Life Ladder** scores.

---

## 📊 Objectives

* **Identify Key Drivers**
  Examine the relationships between GDP per capita, social support, and personal freedom to determine their impact on overall happiness.

* **Evaluate Efficiency**
  Introduce the **Happiness-to-GDP Ratio** to identify countries that maximize well-being despite limited economic resources.

* **Analyze Trends**
  Track global happiness dynamics across significant world events from 2005 to 2024.

* **Segment Nations**
  Classify countries into **Happiness Tiers** to benchmark performance across socio-economic clusters.

---

## 📂 Dataset

The analysis utilizes a consolidated dataset: **`world_happiness_combined.csv`**, which includes the following variables:

| Feature                          | Description                                             |
| -------------------------------- | ------------------------------------------------------- |
| **Life Ladder**                  | Primary measure of subjective well-being (scale: 0–10). |
| **GDP per Capita**               | Economic productivity (log-transformed for analysis).   |
| **Social Support**               | Perceived availability of community and family support. |
| **Healthy Life Expectancy**      | Indicator of physical well-being and longevity.         |
| **Freedom to Make Life Choices** | Measure of personal agency and autonomy.                |
| **Perceptions of Corruption**    | Proxy for institutional trust.                          |
| **Generosity**                   | Indicator of altruistic behavior within society.        |

---

## 🛠️ Key Analytical Techniques

### 1. Feature Engineering

* **Happiness_Tier**: Categorization of countries into quartiles based on Life Ladder scores.
* **Log_GDP**: Logarithmic transformation of GDP per capita to address skewness.
* **Happiness_GDP_Ratio**: Efficiency metric assessing well-being relative to economic output.

### 2. Correlation Analysis

* Utilized correlation matrices and heatmaps to identify the hierarchy of happiness determinants.

### 3. Cohort Analysis

* Tracked the evolution of happiness for countries based on their year of entry into the dataset.

### 4. Efficiency Ratio Analysis

* Identified nations that “punch above their economic weight” in terms of well-being.

### 5. Time-Series Forecasting

* Visualized long-term trends and volatility in global happiness over two decades.

---

## 💡 Key Insights

### 📈 The Happiness Ceiling

Economic growth exhibits **diminishing returns** on happiness. Once basic needs are satisfied, further improvements in well-being are primarily driven by social and institutional factors.

### 🤝 Social Safety Nets

**Social support** emerges as the most consistent and robust predictor of happiness, acting as a buffer during economic and societal shocks.

### 🏛️ Trust as a Floor

High **perceptions of corruption** serve as a “happiness anchor,” limiting a country's ability to achieve top-tier well-being regardless of its wealth.

### 🗽 Freedom & Agency

**Freedom to make life choices** is the most volatile indicator but has the strongest immediate impact on year-to-year changes in happiness.

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/tedacodder/Decoding-Global-Happiness.git
cd Decoding-Global-Happiness
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv

# Activate the environment
# On Windows
venv\\Scripts\\activate

# On macOS/Linux
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter pathlib
```

### 4. Run the Notebook

```bash
jupyter notebook world_happiness_analysis.ipynb
```

---

## 🗂️ Project Structure

```
Decoding-Global-Happiness/
│
├── data/
|   └── raw/
│   └── processed
├── notebooks/
|   └── Visuals
│   └── world_happiness_analysis.ipynb
├── README.md

```

---

## 🛠️ Technologies Used

| Category                 | Tools               |
| ------------------------ | ------------------- |
| **Programming Language** | Python 3.x          |
| **Data Analysis**        | Pandas, NumPy       |
| **Data Visualization**   | Matplotlib, Seaborn |
| **Environment**          | Jupyter Notebook    |
| **Version Control**      | Git & GitHub        |

---

## 📊 Data Source

* **World Happiness Report** – Available via Kaggle and the official World Happiness Report publications.

---

## 📝 Summary

A concise written summary of this project, including the methodology, key findings, and policy implications, is available in the Google Document below. This document provides a high-level overview for readers who prefer a quick understanding of the analysis without navigating the full notebook.

📄 **Access the full summary:**  
[Global Happiness Project Summary](https://docs.google.com/document/d/1QoLD1i69uCdNYRCZuOnRH2kkiJ6t2eUvjBE03bVXMGQ/edit?usp=sharing)


---
## Summary
---

## 📬 Contact & Portfolio

**Author:** *Tewodros Mesfin*  
**LinkedIn:** [Tewodros Mesfin](https://www.linkedin.com/in/tewodros-mesfin-4ba5b23a9?utm_source=share_via&utm_content=profile&utm_medium=member_android)

Feel free to reach out for collaboration, feedback, or opportunities related to data science and analytics.

---


## 📄 License

This project is licensed under the **MIT License**. See the `LICENSE` file for more details.

---

## ⭐ Acknowledgements

* The **World Happiness Report** team for providing comprehensive global well-being data.
* The open-source Python community for their invaluable analytical tools.
