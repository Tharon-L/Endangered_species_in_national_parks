# 🐾 Endangered Species in U.S. National Parks

This project investigates patterns of endangered species across U.S. national parks using a combination of data analysis and visualization. The primary goal is to understand the distribution, conservation status, and observational trends of species in these protected areas.

## 📁 Project Overview

- **Data Sources**:  
  - `species_info.csv`: Information about species including their scientific name, category, and conservation status.  
  - `observations.csv`: Observational data for species in various national parks.

- **Objective**:  
  To identify factors contributing to species endangerment and assess the effectiveness of conservation status across categories and parks.

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- Jupyter Notebooks
- CSV datasets

---

## 📊 Visualizations & Key Insights

### 1. Conservation Status Distribution

This section visualizes the proportion and absolute counts of species by conservation status.

**Visual Output**:  

![Conservation_Status_Distribution](https://github.com/user-attachments/assets/8cde86bf-2811-44f5-a729-31a2861fb66d)


**Key Insight**:
- Most species fall under "Species of Concern".
- A small but non-negligible fraction is classified as "Endangered" or "Critically Endangered".

---

### 2. Endangerment Risk by Category

Assesses the relative endangerment rate across biological categories (e.g., mammals, birds) using statistical tests and heatmaps.

**Visual Outputs**:  
![Endangerment_Risk_by_Category](https://github.com/user-attachments/assets/1e16ff4c-5fb7-4821-8543-f39cef7b8cd1)

![Chi_Square_Residuals](https://github.com/user-attachments/assets/384de42a-9bf9-46cb-b531-ebc04f8440fb)


**Key Insight**:
- Chi-square test shows significant differences in endangerment rates.
- Mammals exhibit higher-than-expected endangerment rates.

---

### 3. Top Observed Species per Park

Highlights the most commonly observed species in each national park.

**Visual Output**:  
![Top_Observed_Species_per_Park](https://github.com/user-attachments/assets/b12f20bd-2e81-4e9b-bb82-4c33bee31e67)


**Key Insight**:
- Bird species dominate observations in most parks.
- Observation counts vary significantly between parks.

---

### 4. Observation Frequency vs. Conservation Status

Shows how often species are observed in relation to their conservation status, revealing potential observation bias.

**Visual Output**:  
![Observation_vs_Conservation_with_Insights](https://github.com/user-attachments/assets/63931d7b-d96b-463a-9b7d-a61264146406)


**Key Insight**:
- Endangered species are observed far less frequently.
- There's a strong negative correlation between conservation status and observation frequency.

---

### 5. Observation Patterns by Category

A detailed look into how observation trends differ across animal categories and conservation statuses.

**Visual Output**:  
![Observation_Patterns_by_Category](https://github.com/user-attachments/assets/7ad2d1b0-25e0-4d59-9d51-f029adc91e0c)


**Key Insight**:
- Faceted scatterplots reveal category-specific trends.
- Use of log-scale highlights hidden patterns.

---

## 🧠 Conclusions

- Conservation status has a measurable impact on species visibility and endangerment trends.
- Statistical and visual tools can effectively surface patterns to guide conservation efforts.
- More robust monitoring may be needed for less frequently observed endangered species.

---

## 📎 Author

Developed by **CodeCad** — exploring data one project at a time.

