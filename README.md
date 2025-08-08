# MindAir: Linking Air Quality to Mental Health in the UK

## 📌 Overview

**MindAir** is a data-driven research project exploring the relationship between **air pollution** and **mental health outcomes** in UK communities. By combining environmental, health, and socioeconomic datasets, this project aims to uncover patterns and associations that could inform public health policy, local planning, and community well-being initiatives.

---

## 🎯 Objectives

* Quantify correlations between **air pollution levels** (PM2.5, NO₂, etc.) and **mental health statistics**.
* Identify **geographic and socioeconomic disparities** in exposure and outcomes.
* Provide a foundation for **predictive modelling** and **public health insights**.
* Enable reproducible, open-source analysis for researchers, policymakers, and activists.

---

## 📊 Data Sources

**Environmental Data**

* [DEFRA Air Quality Archive](https://uk-air.defra.gov.uk/data/) – Hourly pollution readings by postcode.

**Health Data**

* [NHS Digital Mental Health Services Data Set (MHSDS)](https://digital.nhs.uk/data-and-information/data-collections-and-data-sets/data-sets/mental-health-services-data-set) – Service contact and outcomes.
* [ONS Mortality Data](https://www.ons.gov.uk/peoplepopulationandcommunity/birthsdeathsandmarriages/deaths/datasets) – Mental health-related mortality rates.

**Socioeconomic Data**

* [Index of Multiple Deprivation (IMD)](https://www.gov.uk/government/statistics/english-indices-of-deprivation-2019) – Small-area deprivation measures.
* Housing quality & property prices from ONS and Land Registry.

---

## 🔍 Research Questions

1. Are higher levels of **airborne pollutants** (PM2.5, NO₂) associated with **increased prevalence** of mental health conditions such as depression and anxiety?
2. Do **deprived areas** experience a disproportionate burden of both poor air quality and mental health challenges?
3. How might **seasonal or temporal variations** in pollution correspond to fluctuations in mental health service demand?

---

## 🛠 Methods

* **Data Cleaning & Integration**: Merging datasets by postcode/Local Authority.
* **Statistical Analysis**: Correlation, regression, and geospatial clustering.
* **Visualisation**: Mapping pollution exposure and mental health indicators.
* **Machine Learning (Future Work)**:

  * Predicting mental health service usage from pollution + socioeconomic indicators.
  * Identifying high-risk communities for targeted interventions.

---

## 📈 Potential Impact

Findings from **MindAir** could support:

* Evidence-based **public health campaigns**.
* Improved **urban planning** and pollution mitigation strategies.
* Policy proposals for **environmental justice** and mental health funding.

---

## 🚀 Future Development

* Expand to **time-series modelling** for lag effects between pollution exposure and mental health outcomes.
* Apply **random forest regression** or **XGBoost** to detect non-linear relationships.
* Build an **interactive dashboard** to make insights accessible to the public.

---

## 📂 Repository Structure

```
mindair/
│── data/             # Raw and cleaned datasets
│── notebooks/        # Jupyter notebooks for analysis
│── scripts/          # Data processing scripts
│── visuals/          # Charts, maps, and infographics
│── README.md         # Project documentation
```

---

## 📜 License

This project is released under the **MIT License** – free to use, modify, and share with attribution.

