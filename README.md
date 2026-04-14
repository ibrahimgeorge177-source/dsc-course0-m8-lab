# Aviation Accident Analysis


##  Project Overview

This project analyzes commercial and passenger aircraft safety using aviation accident data from 1948–2023. The goal is to identify aircraft **makes and models with the lowest risk of destruction and passenger injury** in the event of an accident.

The analysis supports an airline/insurance client in making **data-driven decisions on safer aircraft types**, separated into:
- Small aircraft (≤ 20 passengers)
- Large aircraft (> 20 passengers)

---

##  Objectives

- Identify aircraft makes/models with low:
  - Fatal injury rates
  - Serious injury rates
  - Aircraft destruction rates
- Compare safety between small and large aircraft
- Investigate how external factors (weather, flight phase, etc.) affect accident severity
- Provide statistically reliable recommendations based on sufficient observations

---

##  Dataset

- Source: Kaggle Aviation Accident Dataset
- Time Period: 1948–2023
- Key Features Used:
  - Aircraft Make & Model
  - Injury counts (fatal, serious, minor)
  - Aircraft damage status
  - Weather conditions
  - Phase of flight
  - Estimated passenger count

---

##  Tools & Technologies

- Python 
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code
- Git & GitHub (SSH)

---

##  Methodology

1. **Data Cleaning**
   - Handled missing values
   - Filtered dataset from 1983 onward
   - Created passenger-based aircraft size groups

2. **Feature Engineering**
   - Injury risk = Fatal + Serious injury fractions
   - Aircraft size classification (small vs large)

3. **Exploratory Data Analysis (EDA)**
   - Summary statistics
   - Group comparisons by aircraft Make
   - Distribution plots (violin, strip plots)
   - Destruction rate analysis

4. **Statistical Filtering**
   - Only included aircraft Makes with ≥ 4–10 observations for reliability

5. **Visualization**
   - Bar plots for mean safety metrics
   - Distribution plots for injury risk
   - Comparative analysis of aircraft categories

---

##  Key Analyses

###  Aircraft Safety by Size
- Small aircraft show higher variability in injury outcomes
- Large aircraft generally demonstrate more stable and lower risk profiles

###  Risk Factors
- Poor weather conditions increase injury severity
- Takeoff and landing phases are the highest risk stages of flight

###  Manufacturer Insights
- Some manufacturers consistently show lower injury and destruction rates
- Others exhibit higher risk profiles and variability

---

##  Key Findings

- Certain manufacturers (e.g., Cessna, Piper, Luscombe) show **lower overall risk**
- Large aircraft are generally **safer and more consistent** than small aircraft
- Operational conditions (weather and flight phase) significantly impact accident severity

---

##  Recommendations

- Prefer aircraft manufacturers with:
  - Low fatal and serious injury rates
  - Low destruction probability
  - Sufficient historical safety records
- Prioritize aircraft designed for stability during critical flight phases (takeoff/landing)
- Avoid models with high variability in safety performance

---

##  Repository Structure
