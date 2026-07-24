# Global Terrorism Database Analysis

## 📌 Project Overview

This project explores patterns and trends in global terrorism using the Global Terrorism Database (GTD). The analysis focuses on terrorist incidents recorded between **2007 and 2017**, examining how attacks, fatalities, weapons, targets, regions, and major terrorist groups changed over time.

The project combines data cleaning, exploratory data analysis, aggregation, and visualization to transform raw terrorism data into meaningful insights.

---

## 🎯 Objectives

- Analyze global terrorism trends between **2007 and 2017**.
- Examine how terrorist attacks and fatalities changed over time.
- Identify commonly used weapon types and compare their distribution across regions.
- Analyze fatalities across different attack and target categories.
- Identify major terrorist groups and compare their contribution to recorded attacks.
- Explore the geographical distribution of attacks carried out by major terrorist organizations.
- Present complex terrorism data through clear and interpretable visualizations.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas** — data cleaning, filtering, transformation, and aggregation
- **NumPy** — numerical data processing
- **Matplotlib** — data visualization
- **Seaborn** — statistical and categorical visualizations
- **Jupyter Notebook** — interactive analysis and documentation

---

## 🧹 Data Preparation & Assumptions

Before visualization, the dataset was filtered and prepared to make the analysis more consistent.

The analysis:

- Uses terrorism data from **2007 to 2017**.
- Includes only incidents classified as definite terrorist attacks.
- Treats attacks with an unknown number of fatalities as having zero recorded deaths for the purpose of the visualizations.
- Groups and aggregates incidents across dimensions such as year, weapon type, attack type, target category, region, and terrorist group.

Because of these assumptions, fatality-based visualizations should be interpreted as lower-bound estimates where fatality information was unavailable.

---

## 📈 Visualizations Included

### 1. Attacks by Weapon Type

Analyzes the number of terrorist attacks involving different weapon categories and compares their usage across regions.

The analysis highlights the dominance of **explosives** among recorded weapon types while excluding extremely rare categories where appropriate.

![Attacks by Weapon Type](img/attacks_by_weapon.png)

---

### 2. Fatalities by Attack Type Over Time

Examines how terrorism-related fatalities changed over the **2007–2017** period and compares deaths across different attack types.

The time-series visualization helps identify periods of increased terrorist activity and changes in the lethality of different attack methods.

![Fatalities by Attack Type Over Time](img/deaths_by_attack_over_time.png)

---

### 3. Fatalities by Target Category

Explores how fatalities are distributed across different categories of targets, helping identify which types of targets experienced the greatest human impact.

![Fatalities by Target Category](img/deaths_by_target_over_time.png)

---

### 4. Fatalities by Weapon Type Over Time

Examines how fatalities associated with different weapon categories changed throughout the analysis period.

![Fatalities by Weapon Type Over Time](img/deaths_by_weapon_over_time.png)

---

### 5. Top Terrorist Groups by Attack Percentage

Compares major terrorist organizations based on their share of recorded attacks, highlighting groups responsible for a significant proportion of terrorist activity.

![Top Terrorist Groups](img/top_five_groups_percent_ts.png)

---

### 6. Attack Locations by Terrorist Group

Visualizes the geographical distribution of attacks associated with five major terrorist groups.

Each plotted location represents an attack, allowing geographical patterns and areas of concentrated activity to be identified.

![Attack Locations by Group](img/group_attack_annotated_blue.png)

---

## 🔍 Key Insights

- Terrorist activity varied considerably across the **2007–2017** period, with noticeable changes in fatalities over time.
- Explosives were among the most frequently used weapons in recorded terrorist incidents.
- The human impact of terrorism differed substantially depending on attack type and target category.
- A relatively small number of major terrorist groups accounted for a significant share of recorded attacks.
- Terrorist organizations displayed distinct geographical patterns of activity.
- Combining temporal, categorical, and geographical analysis provides a more complete understanding of terrorism patterns than examining attack counts alone.

---

## 📚 Learning Outcomes

Through this project, I developed practical experience in:

- Cleaning and preprocessing real-world datasets using **Pandas**.
- Filtering data based on analytical assumptions and project requirements.
- Handling missing and incomplete values during exploratory analysis.
- Performing **grouping, aggregation, and categorical analysis** on large datasets.
- Conducting time-series and trend analysis.
- Comparing patterns across regions, attack types, weapon types, targets, and terrorist groups.
- Creating meaningful visualizations using **Matplotlib and Seaborn**.
- Translating raw data into interpretable analytical insights.
- Working with data in **Jupyter Notebook** and structuring an end-to-end exploratory data analysis workflow.

