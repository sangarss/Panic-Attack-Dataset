
# Panic Attack Dataset Analysis

## Overview
This project presents an exploratory data analysis and visualization of a Panic Attack Dataset to understand behavioral, physiological, and psychological factors associated with panic attacks. The goal of this analysis is to identify patterns related to triggers, symptoms, lifestyle habits, and demographic characteristics that may influence the severity and frequency of panic episodes.

Interactive dashboards were developed using Power BI to visualize relationships between sleep patterns, panic scores, attack duration, symptoms, and common psychological triggers such as caffeine intake, phobias, PTSD, and social anxiety.

This project can serve as a portfolio example for data analytics, business intelligence, and healthcare data visualization.

---

## Dataset Description
The dataset contains structured records of individuals experiencing panic attacks along with multiple related attributes.

Key attributes include:

- **Demographic Information** – Age group and gender
- **Panic Score Level** – Categorized as Low, Medium, or High
- **Sleep Duration** – Average number of sleep hours
- **Panic Attack Duration** – Duration of panic attacks in minutes
- **Weekly Alcohol Consumption** – Number of drinks per week
- **Trigger Factors** – Caffeine, Phobia, PTSD, Social Anxiety
- **Medical History** – Anxiety, Depression, PTSD, or None
- **Physical Symptoms** – Dizziness, Trembling, Chest Pain, Sweating, Shortness of Breath

The dataset is suitable for exploratory analysis, predictive modeling experiments, and visualization practice in healthcare and behavioral analytics.

---

## Dashboard Insights

### Trigger-Based Analysis
The dashboard compares **Average Sleep Hours, Panic Score, and Panic Attack Frequency** across different trigger conditions such as:

- Caffeine
- Phobia
- PTSD
- Social Anxiety

The analysis also highlights differences between **adolescent and adult age groups**.

### Lifestyle Factors
Lifestyle behavior was analyzed using:

- Distribution of patients by sleep hours
- Panic attack duration patterns
- Weekly alcohol consumption

These factors help identify behavioral patterns that may influence panic episodes.

### Symptom Distribution
The dataset also evaluates the frequency of common panic attack symptoms:

- Dizziness
- Trembling
- Chest Pain
- Sweating
- Shortness of Breath

This provides insight into the most commonly reported physical symptoms among patients.

---

## Tools and Technologies

| Tool | Purpose |
|-----|-----|
| Power BI | Data visualization and dashboard development |
| SQL | Data cleaning and transformation |
| CSV Dataset | Data storage |
| Data Analytics Techniques | Exploratory data analysis |

---

## Key Observations

- Psychological triggers such as **PTSD and social anxiety** are associated with higher panic scores.
- **Sleep patterns** appear to vary significantly among individuals experiencing panic attacks.
- Symptoms such as **sweating and shortness of breath** are among the most frequently reported indicators.
- Panic attack duration varies widely across individuals.

---

## Repository Structure

```
panic-attack-analysis
│
├── dataset
│   └── panic_attack_dataset.csv
│
├── dashboard
│   └── panic_attack_dashboard.pbix
│
├── images
│   ├── insight1.png
│   ├── insight2.png
│   └── insight3.png
│
└── README.md
```

---

## Potential Applications

This project can be used for:

- Healthcare data analytics
- Machine learning model development
- Behavioral pattern analysis
- Data visualization portfolio projects
- Mental health research studies

---

## Future Improvements

Future enhancements may include:

- Machine learning models to predict panic attack risk
- Time-series analysis of panic attack occurrences
- Integration of physiological indicators such as heart rate or stress levels
- Deployment of the dashboard through Power BI Service for interactive exploration
