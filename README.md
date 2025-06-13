# Water-Quality-Analysis

# Overview

This project focuses on analyzing water quality data using various statistical and machine learning techniques. The primary objectives include bivariate and multivariate data analysis, correlation analysis, data preprocessing, and modeling using Decision Tree and Random Forest Classifiers.

# Data Set Information

The dataset used in this analysis is focused on water quality metrics. It includes several features that help in determining the quality of water based on different chemical properties.

**1. pH Value::**
  
The pH level is crucial for assessing the acid-base balance of water, indicating whether the water is acidic or alkaline. The World Health Organization (WHO) recommends a pH range of 6.5 to 8.5. The current study shows pH values between 6.52 and 6.83, which fall within WHO standards.

**2.Hardness::**

Water hardness is primarily caused by calcium and magnesium salts, which dissolve as water flows through geological deposits. The duration of water contact with these materials influences the level of hardness. Hardness is traditionally defined by water's ability to precipitate soap, mainly due to the presence of calcium and magnesium.

**3.Total Dissolved Solids (TDS)::**

Water can dissolve various inorganic and some organic minerals or salts, such as potassium, calcium, sodium, and sulfates. These dissolved minerals can affect the taste and appearance of water. High TDS levels indicate that water is highly mineralized. The desirable TDS limit is 500 mg/L, with a maximum allowable limit of 1000 mg/L for drinking water.

**4.Chloramines::**

Chloramines, formed by adding ammonia to chlorine, are commonly used as disinfectants in public water systems. Chlorine levels up to 4 milligrams per liter (mg/L) or 4 parts per million (ppm) are considered safe for drinking water.

**5.Sulfate::**

Sulfates are naturally occurring in minerals, soil, and rocks and are also present in air, groundwater, plants, and food. While sulfate levels in seawater are about 2,700 mg/L, freshwater supplies typically range from 3 to 30 mg/L, though some areas may have much higher concentrations, up to 1000 mg/L.

**6.Conductivity::**

Pure water is a poor conductor of electricity, but the presence of ions increases its conductivity. The amount of dissolved solids generally determines water's electrical conductivity (EC). WHO standards suggest that EC should not exceed 400 μS/cm.

**7.Organic Carbon::**

Total Organic Carbon (TOC) in water originates from decaying natural organic matter and synthetic sources. TOC measures the total carbon content in organic compounds within water. According to the U.S. Environmental Protection Agency (EPA), TOC levels in treated drinking water should be less than 2 mg/L, and less than 4 mg/L in source water used for treatment.

**8.Trihalomethanes (THMs)::**

THMs are chemicals that can form in water treated with chlorine. Their concentration varies depending on the organic material present, the chlorine dosage, and the water temperature during treatment. THM levels up to 80 ppm are considered safe in drinking water.

**9.Turbidity::**

Turbidity measures the cloudiness of water, which is influenced by the amount of suspended solid matter. It reflects water's light-emitting properties and is used to assess waste discharge quality regarding colloidal matter. The mean turbidity value observed (0.98 NTU) is lower than the WHO recommended limit of 5.00 NTU.

**10.Potability::**

Potability indicates whether water is safe for human consumption, where a value of 1 means potable (safe to drink) and 0 means non-potable.

# Steps Taken

- **Data Preprocessing**

      Includes steps for handling missing data, normalization, and train-test splitting.
  
- **Exploratory Data Analysis (EDA)**

      Visualizations and statistical summaries to understand data distribution and feature relationships.
  
- **Modelling**

      Implementation of machine learning models such as Decision Tree and Random Forest, along with their evaluation.

- **Visualization**

      Graphical representation of the Decision Tree model.

- **Hyperparameter Tunning**

     Optimization of Random Forest parameters for better performance.

# Tools and Technologies

    - Programming Language :: Python
    - Libraries :: Pandas,Numpy
    - Visualization :: ,Seaborn,Matplotlib,scikit-learn

# Results 

    The analysis provides insights into the most significant features affecting water quality and presents a predictive model with optimized accuracy.

# Conclusion

    This project demonstrates the application of data analysis and machine learning techniques to assess water quality, offering valuable insights and predictive capabilities.

  
